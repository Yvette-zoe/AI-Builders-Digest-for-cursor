# AI Builders Digest — 2026-09-19

## X / TWITTER

**Anthropic Claude Code Boris Cherny** says Projects have changed how he interacts with Claude and how he codes: he stopped managing sessions, sends thoughts as they come, Claude splits them into threads, and the project remembers how he works. He is writing a lot of code this way and is excited the new experience is rolling out now.

Anthropic Claude Code Boris Cherny 说 Projects 改变了他与 Claude 互动以及写代码的方式：他不再管理 sessions，想到什么就发，Claude 会拆成 threads，项目还会记住他的工作习惯。他现在大量代码都在这里写，并对新体验正在 rollout 感到兴奋。

https://x.com/bcherny/status/2100669598995816511
https://x.com/bcherny/status/2100639991244427490

**Anthropic Claude Code + Cowork Cat Wu** describes the new Projects experience: Claude coordinates all of your sessions so you can operate at a higher level of abstraction, fire off a batch of tasks, and get aggregated status updates on demand. It also keeps long-lived memory that evolves as you use it. Rollout continues over the coming weeks.

Anthropic Claude Code + Cowork Cat Wu 介绍新的 Projects 体验：Claude 统筹你的全部 sessions，让你在更高抽象层工作，批量丢任务后随时要汇总状态。它还有随使用演化的 long-lived memory。未来几周持续 rollout。

https://x.com/_catwu/status/2100641163120423057

**Anthropic Claude Code Thariq** says Projects brings the architecture of Claude Tag to Claude Code: one agent per project that manages memory and spins off subagents for tasks. You can ask it to be proactive or to do things on a schedule, and it feels nicer than juggling a bunch of sessions.

Anthropic Claude Code Thariq 说 Projects 把 Claude Tag 的架构带到了 Claude Code：每个项目一个 agent，负责 memory，并为任务拉起 subagents。你可以让它主动做事或按计划执行，比一堆 sessions 更好用。

https://x.com/trq212/status/2100638355872706571

**Anthropic product Claude** explains that a project builds over time: every thread adds to and draws from shared memory (for example remembering a release moved to Friday, or who to ask before touching billing), and the project library keeps files you add plus ones Claude creates. Threads run in the cloud and keep working offline from your machine, but cannot yet reach local files, tools, or internal networks (local support coming soon). Existing projects on Pro and Max keep working as today and will be upgraded as rollout expands; a waitlist is open for earlier access.

Anthropic 产品 Claude 解释项目会随时间生长：每条 thread 都会写入并读取共享 memory（例如记住 release 改到周五，或改 billing 前该问谁），项目 library 保存你添加的文件和 Claude 创建的文件。Threads 在云端运行，电脑离线也能继续，但还不能访问本机文件、工具或内网（local support 很快到来）。Pro 与 Max 上的现有 projects 暂时照旧，会随 rollout 升级；也可加入 waitlist 争取更早体验。

https://x.com/claudeai/status/2100632684074549309
https://x.com/claudeai/status/2100632687316730327
https://x.com/claudeai/status/2100632688625348890

**Google Labs** announces the new CC, an AI agent for families to spend less time on logistics and more time together: up to 5 members per agent, a shared "Your Day Ahead" morning brief email, autosync with Google Calendar and Tasks, coordination in Google Chat for meal plans and school lists, directed help on paperwork, and memory that separates family-wide vs person-specific details. Waitlist or upgrade is US only, 18+.

Google Labs 发布面向家庭的新 CC AI agent：减少后勤、多留相处时间。单 agent 最多 5 人，共享早间 "Your Day Ahead" 简报邮件，与 Google Calendar / Tasks 自动同步，可在 Google Chat 里协调周菜单与学校用品清单，按你的指示处理许可条等文书，并区分全员记忆与个人细节。Waitlist 或升级目前仅限美国、18+。

https://x.com/GoogleLabs/status/2100653821907366366

**Google Labs VP Josh Woodward** flags the family CC launch as something his household likes, and separately says if you are not using Gemini Notebook on your phone yet you are missing out.

Google Labs VP Josh Woodward 表示自家也很喜欢这款家庭 CC，并另发帖说如果你还没用手机上的 Gemini Notebook，你错过了。

https://x.com/joshwoodward/status/2100665648825483726
https://x.com/joshwoodward/status/2100616682431807860

**OpenAI Codex & ChatGPT Thibault Sottiaux** asks whether anyone has tried getting Astra and Fable to agree on a perfect styleguide, then hosting it somewhere with a web MCP.

OpenAI Codex & ChatGPT Thibault Sottiaux 问有没有人试过让 Astra 和 Fable 就完美 styleguide 达成一致，再把它挂到某处并用 web MCP 托管。

https://x.com/thsottiaux/status/2100645454245720513

**Vercel CEO Guillermo Rauch** argues more software will likely be produced next year than in all prior computing history: Vercel took 10 years to reach 1 billion deployments, then added another 1.4 billion in the last 10 months, spanning disposable HTML artifacts through sophisticated apps and agents. Deployment speed is an obsession; time to deploy, upload, assign a domain, and globally propagate an artifact is down to about 1 second, including CDN, Firewall, immutable deployments, observability, and rollbacks. Separately, agents under hotfix pressure can now run `vercel --turbo --prod` to use the fastest available build machine.

Vercel CEO Guillermo Rauch 认为明年产出的软件量很可能超过整部计算史：Vercel 花 10 年才到 10 亿次部署，过去 10 个月又加了 14 亿次，从一次性 HTML artifacts 到复杂 apps 与 agents 都有。部署速度是执念；部署、上传、绑域名并全球传播已压到约 1 秒，且包含 CDN、Firewall、不可变部署、可观测性与回滚。另外，赶 hotfix 的 agent 现在可以跑 `vercel --turbo --prod`，使用最快可用的 build machine。

https://x.com/rauchg/status/2100698591417499972
https://x.com/rauchg/status/2100682030170489160

**Box CEO Aaron Levie** says agents already make up the majority of inference and will trend toward nearly all of it over the next year or two, with most tokens spent by agents running background tasks 24/7: securing code changes, processing workflow data, recruiting and prospecting research, reviewing event streams and logs, plus personal-life tasks. He notes the rate of new token-hungry agents is not slowing, and that just in the past week he introduced multiple workflows that were not technically possible a month ago.

Box CEO Aaron Levie 说 agents 已占 inference 大头，未来一到两年会逼近几乎全部，绝大多数 tokens 会花在 24/7 后台跑任务的 agents 上：审查代码变更做安全、处理工作流数据、招聘与获客研究、扫事件流与日志，以及个人生活任务。他指出吃 tokens 的新 agents 上线速度没有放缓，过去一周他刚上线多种一个月前技术上还做不到的 workflows。

https://x.com/levie/status/2100799668573946191

**Y Combinator President & CEO Garry Tan** highlights Memorable for optimizing memory with embeddings instead of more tokens, calling it a powerful new way to do memory. He also stresses alignment to humankind versus any other goal, and says the future is already here if we choose it and spread it faster.

Y Combinator President & CEO Garry Tan 点赞 Memorable 用 embeddings 而非堆更多 tokens 来优化 memory，称这是做 memory 的强力新路径。他还强调要对齐人类而非其他目标，并说未来已在眼前，关键是选择它并更快扩散。

https://x.com/garrytan/status/2100668489178456268
https://x.com/garrytan/status/2100636443127210112
https://x.com/garrytan/status/2100612808568172830

**FPV Ventures partner Nikunj Kothari** ships nosugarforkids.com after a year of trying self-driving company products that did not meet his bar: a healthy kids-snack catalog with chat recommendations and a nutrient tier list, plus a Claude agent that wakes daily to refresh the catalog, prune dead products, find content ideas, check DataForSEO and Google Search Console, write and edit posts, protect quality, and pitch publications for backlinks. With zero backlinks and no social presence it still reached about 6k organic impressions and 60 clicks a day; MCP and WebMCP are available so other agents can use it.

FPV Ventures partner Nikunj Kothari 在试了大量 self-driving company 产品都不达标后，用 Claude in the loop 自建实验站 nosugarforkids.com：只收录健康儿童零食目录，可聊天拿推荐，并按营养做 tier list；另有每日醒来的 Claude agent 刷新目录、剔除失效商品、找内容点子、查 DataForSEO 与 Google Search Console、撰写编辑文稿、控质量，并向媒体要 backlinks。零 backlinks、无社交曝光下仍做到约每天 6k 自然曝光与 60 次点击；还提供 MCP 与 WebMCP 方便其他 agent 接入。

https://x.com/nikunj/status/2100714665571737885
https://x.com/nikunj/status/2100718806004064730

**SPC General Partner Aditya Agarwal** argues this is the right way to solve alignment and safety, calling GoodfireAI the leading non-frontier-lab company on the problem and generationally important.

SPC General Partner Aditya Agarwal 认为这是解决 alignment 与 safety 的正确路径，称 GoodfireAI 是非 frontier lab 里做这件事的领先公司，且具有世代级重要性。

https://x.com/adityaag/status/2100746235426836708

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
