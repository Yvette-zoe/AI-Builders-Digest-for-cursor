# AI Builders Digest — 2026-09-12

## X / TWITTER

**OpenAI Codex & ChatGPT lead Thibault Sottiaux** says OpenAI will pause new subscriptions to the $200 Pro plan so current users keep a strong Astra experience; Pro puts the most strain on capacity, while all other plans and the API stay open, existing accounts are unaffected, and more capacity is coming. Separately, he highlights scaled agents on demand: the same infrastructure under ChatGPT Work, wrapped as an API you can start using in under a minute.

OpenAI Codex & ChatGPT lead Thibault Sottiaux 表示，为了让现有用户继续获得稳定的 Astra 体验，OpenAI 将暂停 $200 Pro 计划的新订阅；Pro 对系统压力最大，其他套餐与 API 仍可使用，现有账户不受影响，并在尽快扩容。另外，他展示了 scaled agents on demand：这正是 ChatGPT Work 底层基础设施，已封装成可在一分钟内上手的 API。

https://x.com/thsottiaux/status/2098113585683808624
https://x.com/thsottiaux/status/2098238138334548260

**Claude Code lead Boris Cherny** flags Anthropic’s latest Threat Intelligence report as essential reading: as models get smarter without matching safeguards, dual-use risk rises (strong coding can attack infrastructure; biology help can aid pandemics). Separately, answering builders who worry Claude’s code quality, he draws a hard line: throwaway prototypes can be black boxes, but production Claude code should face a higher bar than human code via lint, tests, Claude e2e tests, fuzzers, automated review/security/refactor routines; hold the bar with Opus 5 or Fable 5.1, high/xhigh effort, and a tight CLAUDE.md and skills.

Claude Code lead Boris Cherny 强调 Anthropic 最新 Threat Intelligence 报告值得一读：模型越强、防护跟不上，双用途风险越大（会写代码也能攻击关键基础设施；会做生物研究也能助力制造大流行）。另外，回应担心 Claude 代码质量的建设者时，他划清界限：可丢弃的原型可以当黑盒；但生产环境的 Claude 代码应比人类代码标准更高，靠 lint、测试、Claude e2e、fuzzer、自动化审查/安全/重构等护栏；不达标就换 Opus 5 或 Fable 5.1、提高 effort 到 high/xhigh，并打磨 CLAUDE.md 与 skills。

https://x.com/bcherny/status/2098281805770309686
https://x.com/bcherny/status/2098217571153838124
https://x.com/bcherny/status/2098217573276131577

**Box CEO Aaron Levie** reports themes from dozens of enterprise tech leaders on agents: cyber anxiety after AI-driven vulnerability discovery and the OpenAI Hugging Face incident; multi-frontier-model deployments with spend still concentrated; rising focus on agent security and identity; biggest ROI when companies reengineer workflows (often with embedded FDEs) rather than bolt agents onto old process; vendors get swapped fast when they lag; evals are still early; legacy systems and fragmented data remain the bottleneck. Separately, Box is deepening its OpenAI partnership so enterprise content in Box can be used securely inside ChatGPT as software goes headless.

Box CEO Aaron Levie 汇总本周与银行、媒体、保险、咨询等数十位技术负责人谈 enterprise agents 的主线：AI 放大漏洞发现与 OpenAI Hugging Face 事件后，企业对 cyber 高度紧张；多 frontier 模型并存但预算仍集中在少数供应商；agent 安全与身份管理升温；真正高 ROI 来自改造工作流（常靠嵌入式 FDE），而不是把 agent 硬贴进旧流程；供应商跟不上就被快速换掉；evals 仍早期；遗留系统与碎片化数据仍是瓶颈。另外，Box 加深与 OpenAI 合作，让企业可在 ChatGPT 中安全使用 Box 内容，呼应软件走向 headless、agent 到处执行工作流的方向。

https://x.com/levie/status/2098218284139311615
https://x.com/levie/status/2098135659714085281

**Vercel CEO Guillermo Rauch** says Vercel’s global CDN metadata store (the system that keeps billions of multi-tenant deployments routable and syncs rollbacks/config/routes in hundreds of milliseconds worldwide) is now 91% faster at p99, speeding the build-to-deploy pipeline under heavy agentic deployment growth: about 10 million deployments a day and 2.35 billion to date. Separately, he points to a computer for every agent, in every region.

Vercel CEO Guillermo Rauch 称支撑 CDN、让数十亿多租户部署随时可路由、并在全球数百毫秒内同步回滚/配置/路由的元数据存储，p99 已提速 91%，在 agentic 部署暴增压力下加快了 build→deploy；目前约每天 1000 万次部署、累计 23.5 亿次。另外，他指向「每个 region、每个 agent 一台 computer」的能力。

https://x.com/rauchg/status/2098091056302833837
https://x.com/rauchg/status/2098158541932794222

**Meta Sr Director of AI Madhu Guru** continues his evals series: judge agent trajectories by the steps, not only the final answer. Two paths can both land on 42, but four clean tool calls beat seventeen noisy ones with retries; define the full workflow, per-step tasks and measures, and median vs hard cases, then study steps before scores.

Meta Sr Director of AI Madhu Guru 续写 evals 系列：评估 agent 轨迹要看步骤，而不只看最终答案。两条路径都能得到 42，但 4 次干净 tool call 优于 17 次嘈杂调用加重试；先定义完整工作流、每步任务与度量、以及 median/hard 任务，再先看步骤、后看分数。

https://x.com/realmadhuguru/status/2098064969464217720

**Claude Code builder Thariq** shares a Claude chat prompt that interviews you in depth (free text, or AskUserQuestion for multiple choice) about relevant life context it does not yet know, then saves everything to memory so the model has richer personal context.

Claude Code builder Thariq 分享一段 Claude chat prompt：用自由文本深度采访你（多项选择时用 AskUserQuestion），补齐它还不了解的相关生活背景，并全部写入 memory，让模型拥有更丰富的个人上下文。

https://x.com/trq212/status/2098157600361861579

**AI product creator Peter Yang** offers a blunt productivity ranking: for getting things done, Sol beats Astra.

AI product creator Peter Yang 给出直白的效率排序：要把事情做完，Sol 胜过 Astra。

https://x.com/petergyang/status/2098215935467544604

**Replit CEO Amjad Masad** says AI carries real risk (he worries especially about cybersecurity), but literal human extinction risk is not remotely on his list.

Replit CEO Amjad Masad 认为 AI 确有风险（他尤其担心网络安全），但「人类灭绝」这类 extinction risk 根本不在他的清单上。

https://x.com/amasad/status/2098171265924116732

**OpenClaw creator Peter Steinberger** endorses a coding-era shift: duplicating logic is no longer painful; abstractions still are.

OpenClaw creator Peter Steinberger 认同当下写代码的新权衡：复制逻辑不再痛苦，抽象依然痛苦。

https://x.com/steipete/status/2098089196800098798

**SPC GP Aditya Agarwal** asks how much GDP you would devote to a machine whose only job is finding cures for the hardest diseases, answers “very high,” and says that is the world we live in now.

SPC GP Aditya Agarwal 追问：如果有一台机器只做一件事（寻找最紧迫疾病的疗法），你会愿意投入多少 GDP？他认为答案是「非常高」，而这正是我们此刻所处的世界。

https://x.com/adityaag/status/2098112281267843264

**Google VP Josh Woodward** announces Gemini is now available on Windows, with a download link.

Google VP Josh Woodward 宣布 Gemini 现已登陆 Windows，并附下载入口。

https://x.com/joshwoodward/status/2098131750660772342

**FPV Ventures partner Nikunj Kothari** lists three early-stage venture truths: everyone wants a $50M seed, everyone thinks they will hit $30M ARR next year, and every hot tranched seed somehow lands near a $300M valuation.

FPV Ventures partner Nikunj Kothari 列出早期投资三条真相：人人想融 $50M seed；人人以为明年能到 $30M ARR；每轮火热的 tranched seed 最后都神奇落在约 $300M 估值。

https://x.com/nikunj/status/2098078391065018816

**Anthropic’s Claude account** announces Fable 5.1 Build Days: Claude community buildathons worldwide from September 11-25; bring a problem or idea, or just show up, and RSVP via the linked page.

Anthropic 的 Claude 账号宣布 Fable 5.1 Build Days：9 月 11-25 日全球 Claude 社区 buildathon，带问题或想法来，或直接到场；可通过链接 RSVP。

https://x.com/claudeai/status/2098138736642933143

## PODCASTS

### When AI Improves Itself | Richard Socher (Recursive)

**The Takeaway:** Anything you can simulate and verify, AI will eventually solve, and that loop is the path into recursive self-improvement.

**核心结论：** 凡是你能模拟并验证的东西，AI 最终都能解决；这条回路正是通向 recursive self-improvement 的路径。

Recursive founder Richard Socher (one of the most cited AI researchers, raising $650M for a company built around RSI, and author of forthcoming book The Eureka Machine) argues scientific progress has slowed not from lack of people or money, but because knowledge fractured into a labyrinth: tens of thousands of journals, niche jargon, and careers that punish ideas that are too novel. Antibiotics largely “solved” bacterial infection; viruses, cancer, and foundational physics leaps have not kept the same pace, and no Renaissance generalist can master every subfield anymore.

Recursive founder Richard Socher（引用量极高的 AI 研究者，为围绕 RSI 的公司融资 $650M，并即将出版 The Eureka Machine）认为科学进步放缓并非缺人或缺钱，而是知识碎成迷宫：数万期刊、小圈子黑话，以及过于新颖就会被打压的学术生涯。抗生素大体「解决」了细菌感染；病毒、癌症与基础物理飞跃并未同速推进，也不再有人能当横跨所有子领域的文艺复兴通才。

His counterintuitive bet is that next-token prediction is not “just a chatbot skill.” The same machinery that once looked absurd as a universal question-answerer (he recalls DecaNLP-era prompt engineering being widely rejected) now speaks the language of proteins and molecules: sequences humans never evolved to read, yet models can explore combinations never seen in training. For AI science, he flips a common complaint: hallucination can be a feature when you want novel proteins outside the distribution; raise temperature to explore, and use retrieval when you need facts.

他的反常识判断是：next-token prediction 不只是聊天技能。当年被当成万能问答器还显得荒谬的那套方法（他回忆 DecaNLP 时代的 prompt engineering 曾被大面积拒稿），如今已能「说」蛋白质与分子的语言：人类从未进化去读的序列，模型却能探索训练里从未出现的组合。对 AI 科学，他把常见抱怨反过来：当你想要分布外的新蛋白质时，hallucination 可以是特性；升温探索，需要事实时再用检索。

The RSI path he sketches starts where verification is strongest: programming. “Anything you can simulate, AI will solve.” Software already eats the world; AI eating software means infinite synthetic tasks (for example, screenshot-to-frontend with exact visual match) and powerful verifiers. Harder domains (cells, tissues, organs) still lack perfect simulators, so The Eureka Machine’s four pillars are human knowledge/LLMs, richer measurements, simulation, and robotic data collection/verification, topped by agent swarms and scientist communities. Biology will still take years of trials even with perfect molecules; progress should beat the skeptics without a hard takeoff fantasy.

他勾勒的 RSI 路径从验证最强的地方开始：编程。「凡是你能模拟的，AI 都能解决。」软件已在吞噬世界；AI 吞噬软件意味着近乎无限的合成任务（例如截图到像素级一致的前端）与强验证器。更难的领域（细胞、组织、器官）仍缺完美模拟器，因此 The Eureka Machine 的四支柱是人类知识/LLM、更丰富测量、模拟、以及机器人采集/验证，上层再叠 agent swarm 与科学家社区。即便有完美分子，生物学仍要多年试验；进步会超过怀疑者，但不必幻想硬起飞。

https://www.youtube.com/@DataDrivenNYC/videos

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
