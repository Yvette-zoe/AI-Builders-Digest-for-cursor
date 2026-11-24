AI Builders Digest — 2026-11-24

## X / TWITTER

**Swyx (Latent Space / AI Engineer)**

Swyx highlights OpenAI's proposal to use perplexity (instead of FLOPS) as a shared industry metric for self-regulation and pacing, quoting the claim that surprising capabilities emerge via compression progress and that the ~0.68-0.7 log-perplexity window could bring further transformative capabilities. He calls the accompanying chart one of the cleanest ways to tell the last four years of pretraining progress, and argues that many post-training debates are the B plot next to large-scale pretrain as the A plot. Separately he asks whether that metric really implies more AI progress this year than in 2022-2025, noting it does not fully feel that way and that the metric may only translate at the frontier-math level.

Swyx 强调 OpenAI 提议用 perplexity（而非 FLOPS）作为行业自我监管与节奏控制的共享指标，并引用其论点：新的意外能力主要来自 compression 进步，进入约 0.68-0.7 log-perplexity 窗口可能带来进一步的 transformative capabilities。他认为配套图表是讲述过去四年预训练进展最漂亮的方式之一，并指出许多 post-training 争论相对大规模 pretrain 只是 B 线。另他追问：按该指标，今年 AI 进展是否真的超过 2022-2025；他感觉不完全像，并怀疑指标可能主要在 frontier math 层面才有意义。

https://x.com/swyx/status/2124583459356373052
https://x.com/swyx/status/2124590240539259381

**Peter Yang (AI educator / creator)**

Peter Yang highlights Microsoft Copilot EVP clamanna on agents as harsh customers: when agents become the main users of software, they optimize for performance, price, and reliability, and what an agent prefers is not always what a person would prefer. A human search gets ten links with snippets; an agent does not care and can take a thousand results. clamanna expects APIs and UX to evolve with modes that better support agents. Full episode: https://www.youtube.com/watch?v=Ka2c-DGJvWc

Peter Yang 转发 Microsoft Copilot EVP clamanna 的观点：agents 是非常苛刻的客户；当 agents 成为软件主用户时，它们会追求性能、价格与可靠性，且 agent 偏好并不总是人的偏好。人做搜索会拿到带摘要的 10 条链接；agent 不在乎，可以吃掉上千条结果。clamanna 预期 API 与 UX 会演化出更适合 agents 的模式。完整一集：https://www.youtube.com/watch?v=Ka2c-DGJvWc

https://x.com/petergyang/status/2124669298191090033
https://www.youtube.com/watch?v=Ka2c-DGJvWc

**Nan Yu (Product, Codex at OpenAI)**

OpenAI Codex product builder Nan Yu jokes that he found a secret prompt that makes vibecoded projects scale, perform better, and stay more reliable: "Use Postgres".

OpenAI Codex 产品构建者 Nan Yu 调侃说他找到一个让 vibecoded 项目更可扩展、性能更好、更可靠的 secret prompt：「Use Postgres」。

https://x.com/thenanyu/status/2124592238974156861

**Amjad Masad (CEO, Replit)**

Replit CEO Amjad Masad says desktop AI apps are generally a security and privacy nightmare, and that Replit worked with Windows to ship a world-class security model for Replit Desktop. He cites that as why Christie's, described as the world's preeminent custodian of rare art, chose Replit for secure agentic work (company post: https://x.com/Replit/status/2123914296673304790).

Replit CEO Amjad Masad 说桌面 AI 应用整体上是安全和隐私噩梦，而 Replit 与 Windows 合作，为 Replit Desktop 上线了世界级安全模型。他以此解释为何 Christie's（他称之为世界上首屈一指的珍稀艺术品保管方）选择 Replit 做安全的 agentic 工作（公司帖：https://x.com/Replit/status/2123914296673304790）。

https://x.com/amasad/status/2124604574606795002
https://x.com/Replit/status/2123914296673304790

**Guillermo Rauch (CEO, Vercel)**

Vercel CEO Guillermo Rauch argues AI should be pointed at human-understandability and conceptualization rather than "art": a Riemann proof should come with a paper, a walkthrough, and new concepts, much like intermediate representations remain useful even if LLMs someday emit CPU instructions directly. Separately he warns that "free" ZDR "stealth model" inference with huge reach looks like industrial-scale data exfiltration to nation-state programs, citing Dragos research as seeming confirmation, and notes Vercel AI Gateway built real-world token volume without those shortcuts, with more trust/privacy/security work coming.

Vercel CEO Guillermo Rauch 主张 AI 应指向人类可理解性与概念化，而不是「艺术」：Riemann 证明应附带论文、walkthrough 与新概念，就像即便 LLM 有朝一日直接吐出 CPU 指令，中间表示仍然有价值。另他警告：声称 ZDR 的「免费 stealth model」推理若有巨大曝光，很像面向国家项目的工业级数据外泄，并认为 Dragos 研究似乎印证了这一点；他还提到 Vercel AI Gateway 在不走这类捷径的情况下已积累真实 token 量，并预告将进一步提高信任、隐私与安全标准。

https://x.com/rauchg/status/2124654108124848350
https://x.com/rauchg/status/2124595496849445079

**Aaron Levie (CEO, Box)**

Box CEO Aaron Levie agrees that as agents take on more long-running project work and swarms parallelize against a goal, the agent harness and orchestration architecture must evolve. The hard shift is how agents collectively share knowledge, track tasks, and coordinate with humans: getting the right resource access without over- or under-exposure is complex. Lessons from how people already collaborate (files, computers, chats, inboxes) still apply, but primitives must support far higher throughput than humans, in a world where agents are also easier security vectors. He sees lots of opportunity in both horizontal and vertical approaches.

Box CEO Aaron Levie 同意：当 agents 承担更多长周期项目、swarm 围绕同一目标并行时，agent harness 与编排架构必须演进。最大转变是 agents 如何集体共享知识、跟踪任务并与人类协同：既要拿到相关资源，又不能过曝或欠曝，复杂度很高。人类既有协作方式（文件、电脑、聊天、收件箱）仍有启发，但原语必须支撑远高于人的吞吐，且 agents 更容易成为安全风险入口。他认为横向与纵向方案都有大量机会。

https://x.com/levie/status/2124658150771188157

**Ryo Lu (Designer, Cursor / Notion / Stripe)**

Designer Ryo Lu ships ryOS Karaoke native on iOS, saying it was almost one-shotted with airbuild, and notes that half-folding an iPhone Duo turns it into a tiny karaoke machine.

设计师 Ryo Lu 上线了 iOS 原生 ryOS Karaoke，称几乎是用 airbuild one-shot 出来的，并说把 iPhone Duo 对折一下就成了迷你点歌机。

https://x.com/ryolu_/status/2124473853858725907

**Dan Shipper (CEO, Every)**

Every CEO Dan Shipper says he is usually not alarmist, but if an incident is caused by an AI-assisted cyber attack it is very bad: messing with a plane and pilot's ability to know weight, remaining fuel, and location could make post-9/11 human-hijacker defenses less relevant. Without more information he also expects smaller attacks to probe edges of what is possible, while noting he is not an airplane-systems expert and that many planes have manual overrides, but visibility-bad conditions still make this extremely tricky.

Every CEO Dan Shipper 说自己通常不危言耸听，但若事件由 AI 辅助网络攻击引起就非常糟糕：干扰飞机与飞行员获知重量、剩余燃油与位置的能力，可能让 9/11 之后针对人类劫机者的安保措施失效。在信息不足时，他也预期更小规模攻击会试探边界；同时声明自己不是机载系统专家，且多数飞机有手动接管，但能见度差时仍然极其棘手。

https://x.com/danshipper/status/2124567533449613819

**Sam Altman (CEO, OpenAI)**

OpenAI CEO Sam Altman argues frontier labs should jointly set shared norms for evaluating models and red-teaming safety cases before first use, including shared transparency standards. He proposes common limits based on perplexity and other measurements that developers commit not to cross until understanding and monitoring (for example a successor to CoT monitors) hit a concrete milestone: an industry standard with a first development limit and a clear bar before going beyond it. He adds that labs already agreed under the White House Accords to establish standards and best practices, and that a perplexity discussion can further those goals.

OpenAI CEO Sam Altman 主张前沿实验室应联合制定共享规范：在模型首次使用前如何评估、如何 red-team safety cases，并包含共享透明度标准。他提议基于 perplexity 等可跨实验室追踪的指标设定共同上限，在理解与监控能力（例如 CoT monitors 的后继）达到具体里程碑前不得越过；也就是先有一个行业发展上限，以及越过前必须达成的明确条件。他还提到实验室已在 White House Accords 下同意建立标准与最佳实践，而关于 perplexity 的讨论可进一步推进这些目标。

https://x.com/sama/status/2124551883130114403
https://x.com/sama/status/2124558713646428663

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
