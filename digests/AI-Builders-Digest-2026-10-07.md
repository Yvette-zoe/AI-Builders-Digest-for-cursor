# AI Builders Digest — 2026-10-07

## X / TWITTER

**OpenAI Codex & ChatGPT builder Thibault Sottiaux** highlights collaborative space landing inside ChatGPT, saying Sergio is shipping magic there and the surface is improving leaps and bounds every day.

OpenAI Codex & ChatGPT builder Thibault Sottiaux 点名 ChatGPT 里的 collaborative space：他说 Sergio 正在那里做出魔法，而且这个表面每天都在大幅变好。

https://x.com/thsottiaux/status/2107200530477101461

**AI product educator Peter Yang** shipped a tutorial for an AI language-learning app that teaches Japanese over live voice calls. The build path covers his spec skill for key designs, Gemini Live APIs for voice, and diorama art with Nano Banana, so readers can follow along and learn ~100 phrases for any language before a trip.

AI product educator Peter Yang 发布了一期教程：他做了一个用实时语音通话教自己日语的 AI 语言学习应用。路径包括用 spec skill 定关键设计、接 Gemini Live API 做语音，以及用 Nano Banana 做 diorama 视觉，读者可以照着做，在出行前学到约 100 句任意语言的短语。

https://x.com/petergyang/status/2107108755699900459

**Meta Sr Director of AI Madhu Guru** says the most common mistake is treating evals as an extra QA step after the agent is built. For AI products, evals are the product spec.

Meta AI 高级总监 Madhu Guru 说，团队最常见的错误是把 evals 当成 agent 建完之后多加的一步 QA。对 AI 产品来说，evals 就是产品规格。

https://x.com/realmadhuguru/status/2107292113214091355

**Anthropic Claude Code builder Thariq** names his favorite pattern "local hands": Claude runs in the cloud but can reach your local files, and he says the same is coming to Cowork. Separately, on planning artifacts instead of raw HTML, he notes the big win is token efficiency: the model does not have to remake components or logic for common pieces like state machines, diagrams, and code snippets.

Anthropic Claude Code builder Thariq 给自己最喜欢的模式起名叫 "local hands"：Claude 跑在云端，却能摸到你的本地文件，他说同样能力也会进入 Cowork。另有一则，关于用规划产物而不是 raw HTML，他认为最大好处是 token 效率：模型不必为状态机、图表、代码片段这类常见件反复重造组件与逻辑。

https://x.com/trq212/status/2107229483015258493
https://x.com/trq212/status/2107294499282293017

**Replit CEO Amjad Masad** says the US is catching up on open-weights models.

Replit CEO Amjad Masad 说，美国正在 open-weights 模型上追上来。

https://x.com/amasad/status/2107222388429766970

**Vercel CEO Guillermo Rauch** introduces gdp-ts (Ghosts of Departed Proofs for TypeScript): a library, linter, and AI skill for safer API design where sensitive functions require compile-time "proofs" that the caller did an authorization check. Human review and syntactic overhead once kept these patterns niche (think Haskell); agents invert that, because they write more code than humans can review and thrive in tight loops with hard constraints. The README models a real Vercel API rule: changing a Project password needs proof of a role plus an entitlement.

Vercel CEO Guillermo Rauch 推出 gdp-ts（Ghosts of Departed Proofs for TypeScript）：一套 library、linter 与 AI skill，用 compile-time “proof” 约束敏感函数，要求调用方已做过授权检查。过去人工 review 与语法开销让这类模式偏小众（类似 Haskell）；agent 把局面反过来了：它们写的代码超过人能审的量，又擅长在硬约束闭环里干活。README 用真实 Vercel API 约束举例：改 Project 密码需要角色 + entitlement 的证明。

https://x.com/rauchg/status/2107119811444748555

**Box CEO Aaron Levie** argues agent adoption is bottlenecked by testing, tuning, and optimizing agents on real work environments: the files, CRM, email, and more they actually need. You cannot know how agents perform without understanding eval execution and how they will hold up after a model or workflow change. Every enterprise is doing this one-by-one today; he expects dedicated roles and infra for building and running evals plus simulated environments, and calls it a huge space.

Box CEO Aaron Levie 认为 agent 落地卡在能否在真实工作环境里测试、调参与优化：文件、CRM、邮件等它们真正要用的东西。如果不理解 eval 执行得怎样、换模型或改流程后是否仍稳，就无法判断 agent 表现。眼下每家企业都在逐个手工做这件事；他预期会出现专人与基础设施来建跑 evals 和模拟环境，并称这是一个巨大空间。

https://x.com/levie/status/2107283615247999257

**Designer Ryo Lu** (Cursor / Notion / Stripe) shipped ryOS Subtitles: watch Netflix with dual-language subtitles plus pronunciation guides for Japanese, Chinese, and Korean, with customizable styles and hand-picked defaults, available as a Chrome add-on.

Designer Ryo Lu（Cursor / Notion / Stripe）发布了 ryOS Subtitles：在 Netflix 上叠加双语字幕，并为日语、中文、韩语提供发音指引，样式可自定义且有精选默认，可加到 Chrome。

https://x.com/ryolu_/status/2107146629338042853
https://x.com/ryolu_/status/2107146721591726323

**Y Combinator President & CEO Garry Tan** says AGI Science Loops are coming, and there will be Muse/Instinct-class interfaces for those loops; Halmos is building that. Separately, he argues lab harnesses are incentivized to burn tokens, so startup harnesses have real utility, like Grep swapping token burn into deterministic, tested, repeatable code just by observing agent use.

Y Combinator President & CEO Garry Tan 说 AGI Science Loops 正在到来，而且会有 Muse/Instinct 一类界面服务这些 loop；Halmos 正在做这件事。另有一则，他认为实验室 harness 有烧 token 的激励，所以创业公司的 harness 有真实价值，例如 Grep 只需观察 agent 使用，就能把 token 消耗换成确定性、可测、可重复的代码。

https://x.com/garrytan/status/2107173670699622830
https://x.com/garrytan/status/2107129959550685660

**SPC General Partner Aditya Agarwal** wants to run the Muse/Dot "computer" locally, arguing that feels like a better agent environment than increasingly locked-down MacOS.

SPC General Partner Aditya Agarwal 希望能把 Muse/Dot 的 “computer” 跑在本地，他认为这比日益锁死的 MacOS 更适合做 agent 环境。

https://x.com/adityaag/status/2107133989941387282

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
