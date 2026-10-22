# AI Builders Digest — 2026-10-22

## X / TWITTER

**smol.ai founder Swyx** says Opus is great for writing until a random banned word appears in the prompt, and argues he needs production-grade tools, not "god" filters, if he is going to build an AI media org with the model in the critical path.

smol.ai founder Swyx 说 Opus 写东西很好，但 prompt 里一旦出现某个被禁的随机词就翻车；如果要把模型放在关键路径上做 AI media org，他要的是能上生产的工具，而不是「神级」过滤。

https://x.com/swyx/status/2112772374823407870

**OpenAI Codex & ChatGPT builder Thibault Sottiaux** (Day 16) says API cache now lasts 12 hours, and for logged-in users across Codex and Work the cache is kept forever: no penalty for returning to an old conversation or resuming after a few hours, with a guaranteed cache hit. Separately, OpenAI found about 40,000 accounts where applied usage did not match the selected plan over the weekend; the team corrected it, is contacting those users, and will add credits where affected.

OpenAI Codex & ChatGPT builder Thibault Sottiaux（Day 16）说 API 现在可 cache 12 小时；登录用户在 Codex 与 Work 上 cache 会永久保留，回到旧对话或隔几小时再续也不会被罚，并保证能命中 cache。另外，周末约有 40,000 个账号出现「实际扣用量与所选 plan 不一致」的问题；团队已修正、正在逐一联系，受影响用户会补 credits。

https://x.com/thsottiaux/status/2112712984644784534
https://x.com/thsottiaux/status/2112592264686149749

**Vercel CEO Guillermo Rauch** says Vercel is open-sourcing a runtime-agnostic durability layer for agent harnesses, extending the infra behind Eve and Workflows to tools like Pi and OpenCode (local, Vercel, or DIY), similar in spirit to the AI SDK. He notes Claude Code and Codex can be made durable and observable this way too, but they are not designed for embedding today, so they are less efficient and portable and need an extra sandbox versus Pi or Fx. Separately, he sketches a future where AI computes the perfect delta of what you do and do not understand, enabling progressive, free "ultimate education."

Vercel CEO Guillermo Rauch 说，Vercel 正在开源一套 runtime-agnostic 的 harness durability 方案，把支撑 Eve 与 Workflows 的耐久基建延伸到 Pi、OpenCode 等（本地、Vercel 或自建），思路类似当年的 AI SDK。他也提到 Claude Code 与 Codex 同样能靠这套变 durable、可观测，但目前不适合 embedding，效率和可移植性不如 Pi 或 Fx，还多一层 sandbox 要求。另有一条愿景：AI 算出你懂与不懂之间的完美 delta，帮你渐进学习，通向免费的「终极教育」。

https://x.com/rauchg/status/2112658577110520122
https://x.com/rauchg/status/2112638107749355867

**Box CEO Aaron Levie** argues the emerging form factor for AI is autonomous systems dedicated to specific tasks or domains: a leap past LLM wrappers, where you farm out sophisticated work and can trust it gets done (still with a human in the loop) thanks to better tool and computer use, stronger domain judgment, and harnesses (sandboxes, file systems, data pipelines) that support longer, more complex agents. He sees these systems showing up in IT automation, cyber ops, drug discovery, manufacturing, AI research, and potentially one or more per role in the economy.

Box CEO Aaron Levie 认为，可预见的 AI 形态是面向特定任务或领域的自主系统：比 LLM wrapper 时代跃进一大步，你可以把更复杂的工作外包给 agent，并更放心地相信它能做完（仍需人在环），因为工具与 computer use 更强、垂直领域判断力更好，sandbox、文件系统、数据管线等 harness 也能支撑更长、更复杂的 agent。他看到这类系统已出现在 IT 自动化、安全运营、药物发现、制造、AI 研究等领域，并想象经济里几乎每个角色都可能有一个或多个这样的系统。

https://x.com/levie/status/2112769686798832013

**Y Combinator President & CEO Garry Tan** says GStack is now Capy-aware and works well with Capy's software-factory feature Captains.

Y Combinator President & CEO Garry Tan 说 GStack 现已支持 Capy，并与他们的 software factory 功能 Captains 配合良好。

https://x.com/garrytan/status/2112698243553579485

**FirstMark VC Matt Turck** flags a busy portfolio day: FirstMark led Daytona.io's Series B (after also leading the Series A), BabaHQ announced a Series A, GradiumAI launched a suite of tiny open-source on-device SOTA text-to-speech models, and Synthesia plus Rillet took over NYC subway ads.

FirstMark VC Matt Turck 盘点了忙碌的一天：FirstMark 领投 Daytona.io 的 Series B（此前也领投过 Series A），BabaHQ 宣布 Series A，GradiumAI 发布一套很小的开源、端侧 SOTA 文本转语音模型，Synthesia 与 Rillet 则刷屏纽约地铁广告。

https://x.com/mattturck/status/2112696155519775041
https://x.com/mattturck/status/2112623582098428015
https://x.com/mattturck/status/2112570721499042246

**Builder Zara Zhang** says for earliest-stage product builders, the biggest advantage of an audience is not distribution but the ability to test ideas and angles for what resonates, and to find the first 100 early adopters: signals beat distribution.

Builder Zara Zhang 说，对最早阶段的产品 builder 来说，有自己的受众最大优势不是分发，而是能测试不同 idea/角度看什么能引起共鸣，并找到前 100 个早期用户：signals 大于 distribution。

https://x.com/zarazhangrui/status/2112530473994072225

**OpenClaw builder Peter Steinberger** ran Astra for planning and Sol 6.1 for coding, and found prompting Astra to drive Codex CLI in worktrees works far better than relying on subagents. A second agent oversaw Astra to keep it on track (like /goal, but a challenger agent instead of the same agent reviewing a text file); he wrote an OC-plugin for this "smart goal" feature.

OpenClaw builder Peter Steinberger 用 Astra 做规划、Sol 6.1 写代码，发现让 Astra 在 worktrees 里跑 Codex CLI，远比依赖 subagents 好用。另有一个 agent 盯着 Astra 不跑偏（类似 /goal，但是第二个会挑战的 agent，而不是同一 agent 去读文本文件）；他还为此写了 OC-plugin，叫 "smart goal"。

https://x.com/steipete/status/2112605703219347503

**SPC General Partner Aditya Agarwal** maps Inference-time scaling → Subagents → Agent Swarms onto the older ladder of CPU threads → multi-core CPUs → multi-node distributed systems, noting that history rhymes.

SPC General Partner Aditya Agarwal 把 Inference-time scaling → Subagents → Agent Swarms，对照成当年的 CPU Threads → Multi-core CPUs → Multi-Node Distributed Systems，并说历史在押韵。

https://x.com/adityaag/status/2112579526379401408

**OpenAI CEO Sam Altman** says he is grateful Aleksander accepted OpenAI's request to take on safety and security work as the company confronts superintelligence, calling the challenges immense and Aleksander's skill set a strong fit.

OpenAI CEO Sam Altman 表示，感谢 Aleksander 接受邀请接手安全与安保相关工作；在面对 superintelligence 时这些挑战巨大，而 Aleksander 的能力组合非常合适。

https://x.com/sama/status/2112652656602923366

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
