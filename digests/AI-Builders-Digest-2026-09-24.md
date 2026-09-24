# AI Builders Digest — 2026-09-24

## X / TWITTER

**OpenAI Codex & ChatGPT lead Thibault Sottiaux** announces GPT-6 Sol and Luna are out: a broad capability jump, plus clearer gains in writing and that hard-to-measure "you know when you try it" quality. OpenAI is permanently cutting API prices by 50% so both models become viable for more use cases and stretch subscription usage further, and is loading a banked reset into Plus, Pro, and Business accounts.

OpenAI Codex & ChatGPT 负责人 Thibault Sottiaux 宣布 GPT-6 Sol 与 Luna 上线：整体能力明显抬升，写作和那种“一试就知道”的质感也更好。OpenAI 将 API 价格永久下调 50%，让两个模型覆盖更多 usecase，也让订阅额度更耐用，并为 Plus、Pro、Business 账户加载了 banked reset。

https://x.com/thsottiaux/status/2102463847714247142

**Anthropic Claude Code + Cowork lead Cat Wu** says Claude Opus 5.5 is now the default model in Claude Code and the Claude app (including Cowork) for Pro, Max, and Team. Products default to effort medium, which she frames as comparable to Fable 5.1 on intelligence but faster, and rate limits go about 25% further on Opus 5.5 than on Opus 5. She has been using it as a daily driver for clearer communication and writing in her style.

Anthropic Claude Code + Cowork 负责人 Cat Wu 说，Claude Opus 5.5 现已成为 Claude Code 与 Claude app（含 Cowork）在 Pro、Max、Team 上的默认模型。产品默认 effort medium：智力大致对标 Fable 5.1，但更快；相对 Opus 5，rate limit 大约多用 25%。她自己已把它当 daily driver，看重更清楚的沟通和能按她的文风写。

https://x.com/_catwu/status/2102437713781944397

**Claude Code lead Boris Cherny** used Opus 5.5 to formally verify the Claude Agent SDK in Lean: a couple of short prompts produced 16 PRs fixing bugs and race conditions. He also mixes TLA+ for data flow, concurrency, and state issues, and asks whether formal verification is becoming a real path for bug finding even when you do not know Lean or TLA+ well. Separately, Opus 5.5 and Fable 5.1 each ported HAProxy from C to Rust and both nearly passed the test suite; Opus finished in 9.5 hours vs Fable's 12 hours at 51% lower cost.

Claude Code 负责人 Boris Cherny 用 Opus 5.5 在 Lean 里形式化验证 Claude Agent SDK：几条短 prompt 产出 16 个 PR，修掉 bug 与竞态。他也用 TLA+ 查数据流、并发和状态问题，并追问：即便你不太会 Lean / TLA+，形式化验证是否正成为找 bug 的实用路径。另一边，Opus 5.5 与 Fable 5.1 各自把 HAProxy 从 C 迁到 Rust，几乎都过了测试；Opus 用 9.5 小时对 Fable 的 12 小时，成本低 51%。

https://x.com/bcherny/status/2102543349102338309
https://x.com/bcherny/status/2102439069053747549

**Box CEO Aaron Levie** calls it an insane day for cost: Opus 5.5 price cuts plus GPT-6 Sol and Luna dropping token prices 50%. Like-for-like cost per task is falling faster than almost any other tech, and each drop opens more agent use cases. That is Jevons paradox for agents: cheaper tokens unlock scanning all your data, security review of code, log-driven decisions, and agent swarms in workflows. At Box, Opus 5.5 on complex unstructured enterprise tasks showed frontier quality vs Opus 5: 63% fewer tokens, 42% less verbosity, 30% faster, with big accuracy lifts on financial due diligence, cloud cost analysis, client onboarding targets, and clinical diagnostics; customers will get Opus 5.5 agents in Box AI Studio shortly.

Box CEO Aaron Levie 说这是成本疯狂的一天：Opus 5.5 降价，加上 GPT-6 Sol 与 Luna token 价再砍 50%。同等任务的 cost per task 跌速几乎超过任何其他技术，每次下跌都会打开更多 agent usecase。这是 agent 版的 Jevons paradox：更便宜的 token 让全量扫数据、代码安全审查、日志决策、workflow 里的 agent swarm 变得可行。在 Box，Opus 5.5 做复杂非结构化企业任务相对 Opus 5 达到 frontier 水平：token 少 63%、啰嗦少 42%、快 30%，在金融尽调、云成本分析、客户 onboarding 目标、临床诊断等任务上准确率明显提升；客户很快能在 Box AI Studio 用上 Opus 5.5 agents。

https://x.com/levie/status/2102477253070430322
https://x.com/levie/status/2102448415775051790

**Vercel CEO Guillermo Rauch** posted fresh Next.js evals: Opus 5.5, GPT-6 Sol, and Fable 5.1 all at 97%, with Grok 4.7 at 94% but 2x-7x cheaper. He also argues software need not die: if you liked Google Reader, you can generate and deploy your own forever. On Anthropic's shipping taste, he says AI removes the excuse not to push the design frontier, and points to Next.js examples of pages taking whatever shape you want.

Vercel CEO Guillermo Rauch 晒了新的 Next.js evals：Opus 5.5、GPT-6 Sol、Fable 5.1 都是 97%，Grok 4.7 为 94% 但便宜 2x-7x。他还说软件不必再死：喜欢 Google Reader？你可以生成并部署属于自己的，永远在线。谈到 Anthropic 的发布品味，他认为有了 AI 就没借口不把设计边界往前推，并指向 Next.js 上页面可随心塑形的例子。

https://x.com/rauchg/status/2102519097770885231
https://x.com/rauchg/status/2102594015669756323
https://x.com/rauchg/status/2102438365455167883

**Anthropic research lead Alex Albert** has been deep on Blender with Opus 5.5: better 3D modeling and vision let you build a whole world from one prompt. He shared a historically grounded Market Street, San Francisco, on the afternoon before the 1906 earthquake, driven by a Claude Tag prompt that forces a sourced evidence file (Sanborn maps, Miles Brothers film, period photos), reusable Blender Python generators, and a 10-second street video with no downloaded meshes.

Anthropic research 负责人 Alex Albert 最近用 Opus 5.5 猛玩 Blender：更好的 3D 建模与视觉能力，让你用一条 prompt 搭出整个世界。他展示了 1906 地震前一天下午的旧金山 Market Street 重建；Claude Tag prompt 要求先建有出处的 source file（Sanborn 地图、Miles Brothers 影片、同时期照片），再用可复用的 Blender Python generator 组装街道，并输出 10 秒沿街视频，且禁止下载现成 mesh。

https://x.com/alexalbert__/status/2102466523164274839
https://x.com/alexalbert__/status/2102466524934271381

**Claude Code builder Thariq** argues the right use of stronger models is not shipping 10x more features to prod. It is spending more time understanding users, running experiments, building prototypes, and learning what you do not understand so you ship things that actually work. He also notes workflows are a huge part of how he uses Claude now that Fable-like intelligence is affordable enough to run inside them.

Claude Code builder Thariq 认为，更强模型的正确用法不是往生产里塞 10 倍功能，而是多花时间理解用户、做实验、搭原型、补自己不懂的东西，从而做出真正能用的产品。他也提到，现在有了成本上用得起的 Fable 级智力，workflows 已成为他日常用 Claude 的重要部分。

https://x.com/trq212/status/2102548686303854790
https://x.com/trq212/status/2102477527688388752

**OpenClaw builder Peter Steinberger** reports ChatGPT sometimes crashing after a macOS 27 update, and that Astra found an approximately 14-year-old bug in libuv.

OpenClaw builder Peter Steinberger 说升级到 macOS 27 后 ChatGPT 有时会崩溃，而 Astra 在 libuv 里找到了一个大约 14 年的老 bug。

https://x.com/steipete/status/2102501642176528743

**AI educator Peter Yang** says Opus 5.5 is the most excited he has been about a Claude model in a while, and points to a longer write-up on why.

AI educator Peter Yang 说，这是他一段时间以来对 Claude 模型最兴奋的一次，并指向一篇更长的文章解释为什么是 Opus 5.5。

https://x.com/petergyang/status/2102577425838485916

**Every CEO Dan Shipper** points new readers to his vibe check of Opus 5.5 vs Sol-6 on Every, plus his take that AI automation creates more good work for human experts rather than simply removing it.

Every CEO Dan Shipper 给新读者指路：他在 Every 上对 Opus 5.5 vs Sol-6 的 vibe check，以及他认为 AI 自动化会给人类专家创造更多好工作、而不是单纯取代的观点。

https://x.com/danshipper/status/2102556723244564715

**Y Combinator President & CEO Garry Tan** says Capy lets him drop PRs much faster than Codex or Claude Code alone.

Y Combinator President & CEO Garry Tan 说，有了 Capy，他提 PR 的速度远快于单独用 Codex 或 Claude Code。

https://x.com/garrytan/status/2102544711647129902

**SPC general partner Aditya Agarwal** notes that today's model safety and alignment debate had an earlier cousin in autonomous vehicles. Hosting Waymo's Dmitri Dolgov at SPC, he highlights Waymo's extensive eval and testing infrastructure as what builds confidence to put multi-ton robots on city streets at speed, and plans to release the full talk video soon.

SPC general partner Aditya Agarwal 指出，今天关于 model safety / alignment 的争论，其实早先在自动驾驶里就打过一轮。他在 SPC 主持 Waymo 的 Dmitri Dolgov 分享时，最看重 Waymo 庞大的 eval / testing 基础设施：正是这些测试支撑了把数吨机器人以城市车速放上街头的信心，完整视频随后会放出。

https://x.com/adityaag/status/2102457464432284019
https://x.com/adityaag/status/2102498288658526614

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
