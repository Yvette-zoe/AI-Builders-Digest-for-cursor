# AI Builders Digest — 2026-10-23

## X / TWITTER

**OpenAI Codex & ChatGPT builder Thibault Sottiaux** posts "Dot, Dotter, Dottest" and clarifies that Dot is fully included in the Pro plan and does not draw on weekly usage.

OpenAI Codex & ChatGPT builder Thibault Sottiaux 连发 "Dot, Dotter, Dottest"，并补充说明 Dot 完全包含在 Pro plan 里，不占用每周 usage。

https://x.com/thsottiaux/status/2113029655095836957
https://x.com/thsottiaux/status/2113029854417600834

**Anthropic Claude Code & Cowork builder Cat Wu** says Claude Duet is a large step toward Claude proactively taking work off your plate: it notices work that needs doing and does it before you ask. Waitlist: https://claude.com/product/claude-duet

Anthropic Claude Code & Cowork builder Cat Wu 说 Claude Duet 朝「Claude 主动帮你减负」迈了一大步：它会发现该做的工作，并在你开口前就动手。候补名单：https://claude.com/product/claude-duet

https://x.com/_catwu/status/2112988751576330487

**Claude (Anthropic)** launches Claude Duet as an early research preview (waitlist on Pro and Max in the US), designed around Claude Opus 5.5 so it can judge what needs you, what can wait, and when to check first. It carries over memory, skills, and connected apps from your Claude account. Safety notes: it never directly sees passwords, a classifier guards sensitive sharing, and important decisions stay with you. It can still misjudge urgency; Anthropic will keep tuning from early users. More: https://claude.com/resources/articles/claude-duet

Claude（Anthropic）推出 Claude Duet 早期研究预览（美国 Pro / Max 候补）：围绕 Claude Opus 5.5 设计，判断哪些事要你、哪些可等、何时先确认；会沿用 Claude 账号的 memory、skills 与已连接应用。安全方面：不直接看到密码，有新 classifier 防止敏感信息外泄，重要决策仍由你做。它仍可能误判紧急程度，团队会根据早期用户反馈继续调优。详情：https://claude.com/resources/articles/claude-duet

https://x.com/claudeai/status/2112984666437546104
https://x.com/claudeai/status/2112984667758510197
https://x.com/claudeai/status/2112984669943968099

**Every CEO Dan Shipper** calls Anthropic's Duet the first personal agent he would label a pro tool after two weeks of testing, and says he has shifted from mostly ChatGPT to roughly 50/50 ChatGPT and Claude. He likes the separate app (iOS, Android, web), work/life channels, a visible todo list, and in-app docs/slides editing; gaps vs a true chief of staff include not directing Claude sessions on his computers, weaker email drafts than Dot, and voice as transcription-only. Agent comparison: https://every.to/personal-agents-comparison ; full vibe check: https://every.to/vibe-check/vibe-check-duet-anthropic-s-always-on-agent . Separately, he argues every company needs a frontier team whose job is to keep up as models change while everyone else uses what they learn.

Every CEO Dan Shipper 试用两周后称 Anthropic 的 Duet 是他愿意叫「pro tool」的第一个个人 agent，自己从几乎只用 ChatGPT 变成 ChatGPT 与 Claude 大约各半。他喜欢独立 App（iOS / Android / Web）、按工作与生活分区的 channels、可见 todo，以及在 App 内写改文档和幻灯片；相对真正的首席参谋，目前还不能指挥他电脑上的 Claude sessions，邮件草稿不如 Dot，语音也只是转写。对比页：https://every.to/personal-agents-comparison ；完整 vibe check：https://every.to/vibe-check/vibe-check-duet-anthropic-s-always-on-agent 。另外他主张每家公司都需要一支 frontier team：专门跟上模型变化，其他人用他们沉淀下来的东西。

https://x.com/danshipper/status/2112997559463506059
https://x.com/danshipper/status/2113007329990127942
https://x.com/danshipper/status/2113010761786175970

**Vercel CEO Guillermo Rauch** says Vercel proactively rolled out Firewall-level mitigations for a Node.js RCE vulnerability ahead of the official patch, so all traffic for all deployments is automatically protected, with managed runtime upgrades rolling out. Earlier, the industry coordinated weeks ahead on php2shell, and Vercel WAF mitigations already blocked attempts on PHP origins; he urges teams to flex the patch → redeploy muscle. Separately, DeepSeek v4.1 Flash (1017) is now in Vercel Token Pass: fast, extremely cheap, zero-data retention, and a strong fit for subagents that execute plans from larger models (e.g. porting TypeScript to Rust repeatedly without burning credits).

Vercel CEO Guillermo Rauch 说，Vercel 已在官方补丁前主动上线 Firewall 级缓解，针对当日 Node.js RCE；所有 deployment 流量自动受保护，并在推进 managed runtime 升级。此前行业还为 php2shell 提前数周协同，Vercel WAF 已挡住针对 PHP origins 的尝试；他提醒大家练好「打补丁 → 重新部署」的肌肉。另外，DeepSeek v4.1 Flash (1017) 已进入 Vercel Token Pass：又快又极便宜，带 ZDR（零数据保留），很适合跑「大模型定计划、小模型执行」的 subagents（例如反复把 TypeScript 迁到 Rust 也不容易把 credits 烧光）。

https://x.com/rauchg/status/2113050053724221732
https://x.com/rauchg/status/2112989629536440400
https://x.com/rauchg/status/2113010010766913815

**OpenClaw builder Peter Steinberger** notes that the PHP vulnerability expected to cause havoc this week was found with GPT-5.6 Sol.

OpenClaw builder Peter Steinberger 指出，预计本周会掀起波澜的那条 PHP 漏洞，是用 GPT-5.6 Sol 发现的。

https://x.com/steipete/status/2112913060709228764

**Box CEO Aaron Levie** argues cybersecurity will be one of AI's most profound domains and a top enterprise investment area: a tireless workforce can hunt, discover, patch, or attack any system ever built, while defenders use agents on logs, code, traffic, and anomalous patterns at previously incomprehensible scale. Even as work becomes more agentic, organizations will need more talent to aim agents at critical work, review findings, patch systems, and respond to incidents; he expects enterprises to care even more about networks, identity, devices, and data, and to burn far more tokens on this loop than people currently imagine.

Box CEO Aaron Levie 认为网络安全会是 AI 最深刻的领域之一，也是企业未来最大投资方向之一：不知疲倦的「劳动力」可以猎杀、发现、修补或攻击任何已有系统，防守方也能用 agent 以过去难以想象的规模扫日志、读代码、看流量并发现异常。即便工作更 agentic，组织仍需要更多人去把 agent 对准关键任务、审阅结论、打补丁、响应事件；企业会更在意网络、身份、设备与数据，并在这条闭环上烧掉远超当下想象的 tokens。

https://x.com/levie/status/2112964214818283917
https://x.com/levie/status/2113137032633757773

**FirstMark VC Matt Turck** flags a busy week with a $250M Series E at Pigment and a $550M Series E at Legora. On Pigment, he says that in an era of tokens, APIs, and agents, the world is shifting toward continuous financial planning, and Pigment is the platform for it (FirstMark has been in since seed).

FirstMark VC Matt Turck 盘点忙碌一周：Pigment 宣布 $250M Series E，Legora 宣布 $550M Series E。谈及 Pigment 时他说，在 tokens、API 与 agents 时代，世界正转向持续财务规划，而 Pigment 就是做这件事的平台（FirstMark 从 seed 起就投了）。

https://x.com/mattturck/status/2113026098669777365
https://x.com/mattturck/status/2112927524321726921

**Builder Zara Zhang** demos turning a photo into a 3D popup card with a single prompt, and says your personal website is the new resume.

Builder Zara Zhang 演示用一条 prompt 把照片变成 3D 立体贺卡，并说个人网站才是新的简历。

https://x.com/zarazhangrui/status/2113055591954526444
https://x.com/zarazhangrui/status/2113062991696744513
https://x.com/zarazhangrui/status/2113148949842534482

**SPC General Partner Aditya Agarwal** reflects that making things with AI can feel as fun as using them: after his son watched Star Wars Episode IV for about three hours, he spent about twenty hours building games about it and barely played them. As a programmer he recognizes that joy of building, and wonders whether AI will let everyone experience it.

SPC General Partner Aditya Agarwal 觉得用 AI「造东西」可以和使用 AI 一样好玩：儿子看了大约三小时《星球大战 IV》，却花了大约二十小时做相关游戏，几乎不怎么玩。作为程序员他懂这种创造的乐趣，并猜想或许人人都能借 AI 体会到这一点。

https://x.com/adityaag/status/2112923959176106056

## PODCASTS

**AI & I by Every: How a Frontier Team Can Help Your Company Keep Up With AI**

**The Takeaway:** Keep a dedicated frontier team so the company can track model change without forcing every employee to choose between shipping and chasing shiny tools.

**要点：** 设一支专门的 frontier team，让公司跟上模型变化，而不逼每个员工在「交付」和「追新工具」之间二选一。

Every CEO Dan Shipper and Head of Enterprise AI Adoption Natalia explain why a frontier team is a separation of concerns: pirates run messy, high-volume experiments (often becoming content first), while architects compress what survives into maintainable systems the rest of the company can adopt. Head of Evals Mike Taylor frames the job as hunting "capability overhang" (models can already do more than teams have time to try) and turning vibe checks into personal benchmarks; one Opus workflow pulled Slack and meeting notes into an explainer video with receipts. Across the roster, the through-line is attention: Jack Cheng's tabless browser with an agent pane, Katie Parrott on early model testing and vibe checks, and Compound Engineer Kieran Klaassen on agent-native editors. Klaassen's closing rule: inspire and listen, then integrate a few experiments that stick instead of dumping a hundred into a channel. Memorable line from Shipper: you get "a nice separation of concerns where you're both keeping up with what's going on on the frontier and you're actually getting your work done."

Every CEO Dan Shipper 与 Head of Enterprise AI Adoption Natalia 把 frontier team 说成职责分离：pirates 快速、略乱地海量试错（很多先变成内容），architects 把能留下来的压成可维护系统，再交给公司其他人用。Head of Evals Mike Taylor 把工作定义成寻找 "capability overhang"（模型能做的已经多于团队来得及试的），并把 vibe check 落成个人 benchmarks；有一次 Opus 工作流从 Slack 与会议笔记抽出叙事，剪出带「证据」的讲解视频。整场主线是注意力：Jack Cheng 的无标签浏览器加 agent pane，Katie Parrott 做早期测模与 vibe check，Compound Engineer Kieran Klaassen 做 agent-native 编辑器。Klaassen 的收尾原则：激励并倾听团队，再把少数能落地的实验接进组织，而不是往频道里倒一百个实验。Shipper 的金句：你得到的是「既跟上 frontier、又能真正把活干完」的清晰职责分离。

https://www.youtube.com/playlist?list=PLuMcoKK9mKgHtW_o9h5sGO2vXrffKHwJL

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
