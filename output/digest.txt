# AI Builders Digest — 2026-10-29

## X / TWITTER

**Box CEO Aaron Levie** says the vast majority of enterprise workflows still have no meaningful agent deployment, estimating the economy is under 1% there today. At best, companies run a single LLM pass for a decision or feedback with little real automation; that gap is partly enterprise adoption lag, but mostly current AI capability. With computer use, long-running agents, harness improvements, and surrounding infrastructure, he argues agents can finally tackle more complex workflows: self-improving systems that raise execution rates over many instances, plus agent swarms that throw arbitrary compute at a problem. The shift is organizational reengineering of workflows rather than end users prompting one-off tasks, with large upside in finance, life sciences, healthcare, and other information-heavy domains.

Box CEO Aaron Levie 认为绝大多数企业工作流仍未真正用上 agent，估算整个经济体的部署率可能不到 1%。最多是公司里有少量系统做一次 LLM 决策或反馈，几乎谈不上真正「自动化」；一部分是企业采用节奏，但更大头是 AI 能力本身。随着 computer use、长跑 agent、harness 改进与周边基础设施到位，他觉得终于能把 agent 用到更复杂的工作流：自改进系统在大量实例上抬高执行成功率，以及可任意加算力的 agent swarms。重点不是终端用户临时 prompt 完成单次任务，而是组织重写底层流程以嵌入 agent，在金融、生命科学、医疗等重信息领域机会很大。

https://x.com/levie/status/2115305369799110905

**Former Anthropic Claude Code builder Thariq** is experimenting with an AI-native macOS dock with custom modes (writing, building, and more) to stay focused. His agent can customize mode behavior and add modes, using jev to classify activity and notifications in real time and act on them; he calls it the HCI work he has wanted to do, but warns it is unfinished with many edge cases and not ready to share. Separately he argues open-source distribution needs a new model where people can modify software via agents while still getting upstream merges automatically; coding agents can do the edits, but they will not merge upstream on their own.

前 Anthropic Claude Code builder Thariq 在试验一个 AI-native macOS dock，带 writing、building 等自定义 mode 帮他保持专注。他的 agent 能改 mode 行为、加新 mode，并用 jev 实时分类活动与通知再采取行动；他说这是自己一直想做的 HCI 工作，但尚未分享，边界情况很多，不建议使用。另外他觉得开源分发需要新形态：人们能用 agent 改软件，同时还能自动合入上游；coding agent 能改代码，但不会自动把上游合进来。

https://x.com/trq212/status/2115135857669881939
https://x.com/trq212/status/2115135859075015137
https://x.com/trq212/status/2115188992861970693

**Replit CEO Amjad Masad** says if he were investing in frontier AI he would underwrite mostly on new discovery and applications like medicine, because coding and most knowledge work are quickly being saturated by sub-frontier models.

Replit CEO Amjad Masad 说如果投 frontier AI，他会主要押在新发现及其应用（如医学）上，因为编程和大部分知识工作正被 sub-frontier 模型迅速饱和。

https://x.com/amasad/status/2115207856496480261

**Y Combinator President & CEO Garry Tan** says the Capy software factory is renormalizing his GitHub contribution colors, with Capy Captains running 10 to 20 subagents at all times on GStack and GBrain. He is also trying to slim down GStack to cut token usage and task latency.

Y Combinator President & CEO Garry Tan 说 Capy software factory 正在「重整」他的 GitHub 贡献图颜色，Capy Captains 始终有 10 到 20 个 subagent 跑在 GStack 与 GBrain 上。他也在精简 GStack，以降低 token 用量和任务延迟。

https://x.com/garrytan/status/2115193524152860771
https://x.com/garrytan/status/2115215790756794496

**AI educator Peter Yang** lists hiring practices that need to change: filtering on years of experience or brand-name employers, prioritizing resumes and cover letters over proof of work, treating headcount managed as an accomplishment by itself, and endless interview rounds instead of short work trials. He also teases an unreleased Grok bot feature he calls one of his favorite and funniest recent AI moments, with a video coming soon.

AI educator Peter Yang 列出需要改掉的招聘做法：用年限或名企过滤、把简历/求职信看得比作品重、把管了多少人当成就、以及无尽面试轮次而不是短试用项目。他还预告了一个尚未全量上线的 Grok bot 功能，称是近期最喜欢也最搞笑的 AI 体验之一，并会做视频。

https://x.com/petergyang/status/2115319325137731757
https://x.com/petergyang/status/2115239304092106772

**FirstMark VC Matt Turck** contrasts the usual warning against too many co-founders with Anthropic (7), OpenAI (11), and Databricks (7).

FirstMark VC Matt Turck 把「联合创始人太多不好」的常规建议，对照 Anthropic（7 人）、OpenAI（11 人）和 Databricks（7 人）。

https://x.com/mattturck/status/2115132327131328806

**FPV Ventures partner Nikunj Kothari** makes the same co-founder point with Anthropic and Databricks as outliers, saying there is no single right way to build startups, only what works. He also lists AI terms that still get wildly different definitions in diligence: long horizon, out of distribution (especially data), intelligence per watt, RL environments, forward deployed, revenue, frontier, and self improving.

FPV Ventures partner Nikunj Kothari 同样用 Anthropic 与 Databricks 的 7 位联合创始人说明顶尖创业公司是 outlier，并称没有唯一正确的创业定义，只有对你奏效的那条路。他还列出尽调里定义仍极度发散的 AI 术语：long horizon、out of distribution（尤其数据）、intelligence per watt、RL environments、forward deployed、revenue、frontier、self improving。

https://x.com/nikunj/status/2115157188704612735
https://x.com/nikunj/status/2115111451614744845

**Every CEO Dan Shipper** argues video creation and game making will become widely distributed foundations of knowledge work the way docs and decks are today.

Every CEO Dan Shipper 认为视频创作与做游戏会像今天的文档和 slide 一样，成为广泛分布的知识工作基础能力。

https://x.com/danshipper/status/2115093098816745910

**Vercel CEO Guillermo Rauch** ships a nostalgia one-liner: alias now=vercel, then a tiny oven/bun:alpine Dockerfile that serves "we are so back" on port 80 and deploys with now.

Vercel CEO Guillermo Rauch 发了一段怀旧一行流：alias now=vercel，再用极简 oven/bun:alpine Dockerfile 在 80 端口返回 "we are so back"，并用 now 部署。

https://x.com/rauchg/status/2115218670389756243

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
