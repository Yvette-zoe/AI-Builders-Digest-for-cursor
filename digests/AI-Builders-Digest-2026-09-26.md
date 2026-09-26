# AI Builders Digest — 2026-09-26

## X / TWITTER

**Vercel CEO Guillermo Rauch** shares two months of Vercel AI Gateway spend: Anthropic is still #1 but fell 69% → 40%; OpenAI rose 10% → 24% and now leads in token count, with GPT-6 Astra and GPT 5.6 Sol ripping; Kimi K3 plus DeepSeek took roughly half of Anthropic's lost share; Opus 5.5 hit up to 10% of spend in two days; OpenAI is 62% of image generations.

Vercel CEO Guillermo Rauch 公布近两个月 Vercel AI Gateway 的 spend 分布：Anthropic 仍居第一，但份额从 69% 降到 40%；OpenAI 从 10% 升到 24%，且 token 量已领先，GPT-6 Astra 与 GPT 5.6 Sol 势头很猛；Kimi K3 加上 DeepSeek 吃掉了 Anthropic 流失份额的大约一半；Opus 5.5 两天内冲到约 10% spend；OpenAI 占 image generation 的 62%。

https://x.com/rauchg/status/2103216656747262419

**Claude Code builder Thariq** responds to plan-mode feedback: many people plan themselves and do not need it; others want a mode where Claude just thinks and brainstorms with them. His plan is to turn plan mode into a built-in mod, and let mods add new modes or override shift+tab, so you can customize the plan-mode prompt, create and share your own modes, or ignore it and rebind shift+tab entirely.

Claude Code builder Thariq 回应 plan mode 反馈：很多人自己就能规划，不需要它；另一些人想要一个 Claude 只负责思考、一起 brainstorm 的模式。他的计划是把 plan mode 做成内置 mod，并允许 mods 新增 mode 或覆盖 shift+tab，这样你可以自定义 plan-mode prompt、创建并分享自己的 mode，或者干脆忽略它、把 shift+tab 绑到别的事上。

https://x.com/trq212/status/2103212051065921632
https://x.com/trq212/status/2103212052391354794

**Replit CEO Amjad Masad** announces that Muse can now make apps on Replit.

Replit CEO Amjad Masad 宣布：Muse 现在可以直接在 Replit 上做 app。

https://x.com/amasad/status/2103129037011120525

**Google VP (Google Labs / Gemini App / AI Studio) Josh Woodward** highlights Dreambeans, a newer Google Labs experiment with a growing cult following: a fixed number of "beans" brew every morning and point you at the real world, with real people, doing things you care about together.

Google VP（Google Labs / Gemini App / AI Studio）Josh Woodward 介绍 Dreambeans，这是 Google Labs 较新的实验，已有一群死忠用户：每天早上固定数量的 “beans” 煮好，把你推向真实世界，和真实的人一起做你在意的事。

https://x.com/joshwoodward/status/2103182635992514569

**AI educator / Latent Space builder Swyx** says his January bet on "Scaling without Slop" is finally working: Latent Space took three years to hit the first 100k YouTube subscribers, then only 1.2 months for the next 100k, with similar traction on AEO/SEO/subscribers. He gives notice that the next phase of Latent Space, AINews, and the rest of swyx inc is coming.

AI educator / Latent Space builder Swyx 说他一月押注的 “Scaling without Slop” 终于见效：Latent Space 花了三年才到第一个 10 万 YouTube 订阅，下一个 10 万只用了 1.2 个月，AEO/SEO/订阅等指标也类似。他正式预告 Latent Space、AINews 以及 swyx inc 其他产品的下一阶段。

https://x.com/swyx/status/2103361254433993165

**OpenClaw builder Peter Steinberger** shares two practical agent tips. First: if you just tell an agent to clean up, it stops too early; give an ambitious goal like "remove 20% of the least useful tests while maintaining code coverage within 2%." Second: he ran Daybreak on an OSS dependency and found eight more long-standing leaks, urging people to care for their open-source deps.

OpenClaw builder Peter Steinberger 分享两条实用 agent 建议。第一：只说 “清理一下”，agent 会过早停手；要给够野心的目标，比如 “去掉 20% 最没用的测试，同时把 code coverage 保持在 2% 以内”。第二：他用 Daybreak 扫一个 OSS 依赖，又挖出八个长期泄漏，提醒大家好好照看开源依赖。

https://x.com/steipete/status/2103148444701610233
https://x.com/steipete/status/2103200311641076100

**FPV Ventures partner Nikunj Kothari** highlights a trades-software thesis: every small business owner, especially in the trades, will have bespoke software, and that last mile is where differentiation lives, letting you give a unique experience to customers and employees.

FPV Ventures partner Nikunj Kothari 强调一个面向 trades 的软件判断：每个小企业主（尤其是 trades 行业）都会拥有定制软件，真正的差异化在 last mile，能给客户和员工独特体验。

https://x.com/nikunj/status/2103360292973633770

**FirstMark VC and MAD Podcast host Matt Turck** frames Jensen's five-layer AI cake (energy, chips, infrastructure, models, applications): the middle software-infra layer is poorly understood, and that is where VAST Data became a ~$30B company few people know, powering xAI, CoreWeave, Nebius, Mistral, Nscale and more. He points to his conversation with VAST Data CEO Renen Hallak (also covered in PODCASTS below).

FirstMark VC、MAD Podcast host Matt Turck 用 Jensen 的五层 AI 蛋糕（能源、芯片、基础设施、模型、应用）做框架：中间的 software infra 层最不被理解，而 VAST Data 正是在这一层做到约 $30B 估值却少有人知，并服务 xAI、CoreWeave、Nebius、Mistral、Nscale 等。他指向与 VAST Data CEO Renen Hallak 的对话（详见下方 PODCASTS）。

https://x.com/mattturck/status/2103167531917721866
https://x.com/mattturck/status/2103167536141353053

## PODCASTS

### The MAD Podcast: Who Feeds the GPUs? Inside AI's Hidden $30B Layer | Renen Hallak, VAST Data

**The Takeaway:** VAST Data CEO Renen Hallak argues the overlooked middle of Jensen's AI stack (software infrastructure between chips and models) is becoming the operating system of the AI-factory era, and demand is already jumping from hundreds of petabytes to multi-exabyte orders.

**要点：** VAST Data CEO Renen Hallak 认为 Jensen AI 栈里最被忽视的中间层（芯片与模型之间的 software infrastructure）正在变成 AI factory 时代的操作系统，而需求已经从数百 PB 跳到多 EB 量级订单。

Hallak places VAST in that middle layer: manage compute, storage, and networking, then make sense of data and training/inference workloads, and increasingly give agents the tools to be simple, safe, fast, and resilient. An "AI factory" is not just a pile of GPUs. Racks go from ~10 kW to ~500 kW, networks and SSDs replace old ethernet and hard drives, and the data itself shifts from table columns to pictures, video, sound, and language, before generative AI even adds more. Labs lead first; enterprises that stay on the old BIS stack get left behind. His enterprise analogy: organizations distill IP into weights the way brains do, "we infer during the day, we fine tune at night," so each company's model of the world diverges through experience and reinforcement learning.

Hallak 把 VAST 放在这一中间层：管 compute、storage、networking，再把数据与训练/推理负载讲清楚，并越来越多地给 agent 提供简单、安全、快速、有韧性的工具。“AI factory” 不是一堆 GPU 就够。机架功耗从约 10 kW 走到约 500 kW，高速网络和大容量 SSD 取代老式以太网和硬盘，数据本身也从表格列变成图片、视频、声音与语言，生成式 AI 还会再加码。大实验室先带头；还停在旧业务信息系统栈上的企业会被甩开。对企业，他用大脑类比：组织会把 IP 蒸馏进 weights，“白天做 inference，夜里做 fine-tune”，每家公司对世界的模型因经历与强化学习而分叉。

Architecturally, VAST bets on "disaggregated shared everything" instead of classic shared-nothing sharding that hits communication limits at scale. Old databases were not built for trillions of vectors or thousands of agents querying at once (he cites a Singapore customer vectorizing camera feeds into trillions of rows). As inference and agents grow, the hard problems become model routing, KV-cache placement, RAG/long-term memory, and extending human auth/ACLs to agents so sensitive data does not leak through fine-tunes or prompts. On the business side, he says AI infra demand has been roughly 10x every two years; VAST sells software with high gross margins and stayed profitable partly because early VCs avoided "storage," which also meant less competition. Winning neoclouds, in his view, build capacity ahead of demand (power, hardware, financing) rather than waiting for offtakers; hyperscalers face innovator's-dilemma lag while their lunch is eaten.

架构上，VAST 押注 “disaggregated shared everything”，而不是经典 shared-nothing 分片（节点一多，节点间通信就会撞墙）。旧数据库不是为数万亿向量、或数千个 agent 同时查询而建的（他举新加坡客户把摄像头流向量化成数万亿行的例子）。随着 inference 与 agent 变多，真正难的变成 model routing、KV cache 放置、RAG/长期记忆，以及把人类的 auth/ACL 延伸到 agent，避免敏感数据经 fine-tune 或 prompt 泄漏。商业面，他说 AI infra 需求大致每两年 10 倍；VAST 卖软件、毛利率高，能保持盈利，部分因为早期 VC 回避 “storage”，竞争也更少。他认为能赢的 neocloud 是提前于需求建设产能（电力、硬件、融资），而不是等 offtaker；hyperscaler 则陷入 innovator's dilemma，午餐正在被别人吃掉。

Memorable line: "Sometimes it scares me. We had a customer... [who] said we're probably going to need about 500 petabytes over the next three years. Last week, came back to us and said, we're gonna need an extra two exabytes on top of that 500 petabytes."

最抓人的一句："Sometimes it scares me. We had a customer... [who] said we're probably going to need about 500 petabytes over the next three years. Last week, came back to us and said, we're gonna need an extra two exabytes on top of that 500 petabytes."

https://www.youtube.com/@DataDrivenNYC/videos

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
