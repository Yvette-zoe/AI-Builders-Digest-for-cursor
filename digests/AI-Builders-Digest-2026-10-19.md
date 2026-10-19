# AI Builders Digest — 2026-10-19

## X / TWITTER

**OpenAI Codex & ChatGPT builder Thibault Sottiaux** reports that his work agent "Burger" coordinated with his personal agent "Dorito" over email (at the personal agent's request) to gather documents, then coordinated with his CPA to file tax paperwork. The whole loop took about 20 minutes; his verdict: "We're still so early."

OpenAI Codex & ChatGPT builder Thibault Sottiaux 说他的工作 agent「Burger」按个人 agent「Dorito」的请求，通过邮件协作去拿文件，再与 CPA 协作完成报税材料。整段闭环大约 20 分钟；他的判断是：「We're still so early.」

https://x.com/thsottiaux/status/2111495392559067199

**AI educator Peter Yang** shares a concrete Claude prompt for auditing Google account app connections when you have dozens of apps and agents linked: review every app across categories, distinguish basic sign-in from Gmail/Drive/Calendar data access, recommend keep/disconnect with reasoning, flag broad permissions and duplicates, and only disconnect after explicit approval. Separately, he credits the Claude Code app as much faster now and arguably simpler than ChatGPT, while still wanting better browser/computer use, remote control for all threads, and live voice.

AI educator Peter Yang 给出一套具体 prompt，用于审计挂了几十个 app 与 agent 的 Google 账号连接：按类别审完每一个、区分基础登录与 Gmail/Drive/Calendar 等数据权限、说明保留或断开的理由、标出过宽权限与重复项，并只在明确批准后才断开。另条里，他认为 Claude Code app 现在快很多，体验上甚至比 ChatGPT 更简单，但仍缺更好的 browser/computer use、全线程远程控制与 live voice。

https://x.com/petergyang/status/2111508293818671449
https://x.com/petergyang/status/2111496600522805624

**OpenAI product (Codex) builder Nan Yu** quotes a team-offsite reminiscence: before AI, what did people obsess over? Front-end JavaScript frameworks.

OpenAI product（Codex）builder Nan Yu 转述团队 offsite 的怀旧对话：在 AI 之前大家到底在盯什么？前端 JavaScript frameworks。

https://x.com/thenanyu/status/2111597172840083574

**Replit CEO Amjad Masad** clarifies that Replit remains model agnostic and users can still choose Anthropic and other supported models. What he meant at TC Disrupt is that OpenAI is now the preferred partner powering Agent, based on performance, cost, and partnership strength, while still optimizing defaults for the best price/performance without removing choice.

Replit CEO Amjad Masad 澄清：Replit 仍保持 model agnostic，用户可选 Anthropic 及其他已支持模型。他在 TC Disrupt 的意思是，基于 performance、cost 与合作强度，OpenAI 现在是驱动 Agent 的首选合作伙伴；在优化默认体验的同时，仍保留用户的模型选择权。

https://x.com/amasad/status/2111494912562888939

**Box CEO Aaron Levie** argues the biggest misread of "the end of software engineering" was assuming the world only needed a fixed amount of software, so automation would shrink labor. The opposite is happening: more of the world is turning into software, because agents can use tools, work with computers, write software on the fly, and process data far faster than humans. That raises the economic importance of engineering, from banks trying new trading systems to life-sciences research and manufacturing supply chains. Manual coding may fade, but almost everything becomes code, which puts people who understand it in a strong position.

Box CEO Aaron Levie 认为，「软件工程要终结」最大的误读，是假设世界只需要固定数量的软件，自动化就会压缩人力。现实正好相反：越来越多事情在变成 software，因为 agent 能用工具、操作电脑、即时写软件，并以远超人类的速度处理数据。这抬高了工程在经济中的重要性：银行做新交易形态、生命科学做更多研究与实验、制造业自动化供应链，往往都先押在工程师身上。手写代码或许会退场，但几乎一切都会变成 code，懂它的人反而处于有利位置。

https://x.com/levie/status/2111525362446520466

## PODCASTS

### What Happens When Billions of AI Agents Hit Your Database? (Andy Pavlo)

**The Takeaway:** Agents need the same database guardrails humans already invented; without permissions and sandboxes, production deletions are a monthly story, not a novelty.

**要点：** Agent 需要的是人类早已发明的数据库护栏；没有权限与沙箱，生产库被删就不是新鲜事，而是每月都会出现的事故。

On The MAD Podcast with Matt Turck, Carnegie Mellon database professor and ClickHouse Labs founder Andy Pavlo reframes the AI-database story past the vector/RAG moment: agents now create databases, branch them for coding sandboxes, write to them, and sometimes drop them. Branching (copy-on-write snapshots of production) is how agent-written features and CI tests stay off the live system of record. Pavlo's blunt diagnosis of public agent-deleted-prod incidents: "It's the Wild West for people that don't know their history databases." The controls to stop reckless drops already exist; teams reinvent the wheel and learn the hard way. Treat agents like toddlers: set permissions so they cannot trash production, and use sandboxes instead of babysitting every approve click when you need hundreds of agents in parallel. He also collapses the "filesystem vs database for agent memory" debate: "What is a file system? It's a database." Prefer a real DBMS (he cites SQLite's safety guarantees) when you need durable writes and shared state across multi-agent setups. On defaults, coding agents almost always recommend Postgres for OLTP unless you force an embedded or key-value constraint; for text-to-SQL, a large bank he spoke with moved from ~60% to ~99.5% accuracy only after years and millions of dollars building a rich semantic/context layer. MCP is fine as a REST-like interface, not a magic bullet. On the build side, after Anthropic's Opus-class models, agents can complete his open-source CMU database course projects end-to-end, and he tracks that over 60% of open-source database systems now have agent-signed commits. Auto-tuning finally works "good enough" for most people because LLMs absorb docs and best-practice guides in minutes, while classic ML tuners needed scarce production training data. DBA knob-twiddling shrinks; data modeling and understanding what agents did stay. Quote that carries the episode: "Every month, there's a story where someone lost their production database because the agent deleted something."

在 The MAD Podcast with Matt Turck 上，Carnegie Mellon 数据库教授、ClickHouse Labs 创始人 Andy Pavlo 把 AI 与数据库的叙事推过 vector/RAG 阶段：agent 现在会创建数据库、为 coding 沙箱做 branch、写入，有时还会 drop。Branching（对生产库做 copy-on-write 快照）让 agent 写的功能与 CI 测试不必碰到真实 system of record。对那些被公开传播的「agent 删了生产库」事故，Pavlo 说得很直：「It's the Wild West for people that don't know their history databases。」阻止乱 drop 的控制手段早就存在；团队却在重复造轮子，再付学费。要把 agent 当 toddler：设好权限，别让它们毁掉生产，并靠沙箱扩展，而不是在需要上百个并行 agent 时还逐条点 approve。他也消解了「agent memory 该用文件系统还是数据库」的争论：「What is a file system? It's a database。」需要可靠写入与跨多 agent 共享状态时，更该用真正的 DBMS（他点名 SQLite 的安全保证）。默认选型上，coding agent 在 OLTP 几乎总推 Postgres，除非你强制要求嵌入式或纯 key-value；text-to-SQL 方面，他提到一家大银行在投入多年、数百万美元做厚语义/上下文层之后，才把准确率从约 60% 拉到约 99.5%。MCP 当作 REST 式接口没问题，但不是银弹。构建侧：Anthropic Opus 级模型之后，agent 已能端到端完成他开源的 CMU 数据库课程项目；他追踪到超过 60% 的开源数据库系统已出现 agent 署名的 commits。Auto-tuning 对多数人终于「够用」，因为 LLM 几分钟就能吸收文档与 best practice，而传统 ML tuner 总缺生产训练数据。DBA 拧旋钮会收缩；数据建模与理解 agent 到底做了什么仍然重要。整期点题原话：「Every month, there's a story where someone lost their production database because the agent deleted something.」

https://www.youtube.com/@DataDrivenNYC/videos

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
