# AI Builders Digest — 2026-08-24

## X / TWITTER

**OpenAI Codex & ChatGPT lead Thibault Sottiaux** gave a Codex rate-limit update: OpenAI found inefficiencies when using images in long sessions with multiple compactions, high p95+ usage for Computer History, and a conversation-title feature that was draining more usage than intended. A tiger team is shipping fixes the next day, and as part of those fixes OpenAI will do a full usage reset for all paid subscriptions. They also found a separate novel approach to drive efficiency up significantly and plan to work on it the following week.

OpenAI Codex & ChatGPT lead Thibault Sottiaux 更新了 Codex 限速问题：OpenAI 发现长会话里多次 compaction 时使用图片存在效率问题、Computer History 的 p95+ 用量偏高，以及一个本应用于生成对话标题的功能实际吃掉了超出预期的用量。tiger team 次日会上修复，并顺带对所有付费订阅做一次完整用量重置。他们还找到另一条无关但能显著提效的新路径，计划下周推进。

https://x.com/thsottiaux/status/2091407991736332689

**Meta Sr Director of AI Madhu Guru** (ex-Google Gemini/Veo) published "How to build great evals - part 6": hill climbing on evals means picking a dimension that matters and optimizing for it, whether quality on high-value production journeys, adjacent use cases, cost, or latency. The work is better harnesses and model selection via prompt eng, context eng, memory, post training, and deterministic code. Use the failure-mode taxonomy from part 3 as a compass. Example: if tool-calling failures dominate because you stuff 20 tools in context when each task needs 3-5, hill climb with context eng so the model gets the right tools at the right stage. On cost, launch with the best model first to maximize quality, then hill climb toward a smaller, cheaper, faster model once users love the experience. He also posted an index linking parts 1-5.

Meta Sr Director of AI Madhu Guru（前 Google Gemini/Veo）发布 “How to build great evals - part 6”：在 eval 上 hill climbing，本质是选定一个真正重要的维度并针对它优化，无论是高价值生产旅程的质量、相邻用例、成本还是延迟。落地靠更好的 harness 与模型选择：prompt eng、context eng、memory、post training，以及确定性老派代码。用 part 3 的 failure-mode taxonomy 当指南针。例如工具调用失败最多，是因为 context 里塞了 20 个 tools，而每个任务其实只要 3-5 个，那就用 context eng 让模型在正确阶段拿到正确工具，再迭代到可用。成本侧：先用最好的模型把质量拉满，用户爱上体验后再 hill climb 到更小、更便宜、更快的模型。他还发了 parts 1-5 的索引链接。

https://x.com/realmadhuguru/status/2091278653435072523
https://x.com/realmadhuguru/status/2091278899711967441

**Box CEO Aaron Levie** argued AI diffusion is far more rate-limited by good evals than most realize. Public model-release evals help show the shape of general progress and relative capability, but the much bigger space over time is evals on major enterprise workflows, down to the specifics of an individual company. You cannot automate what you cannot assess progress on, and enterprises will not be able to go just on vibes.

Box CEO Aaron Levie 认为 AI 扩散被好的 eval 卡住的程度，远超大多数人的认知。公开发布的模型评测有助于看清总体进步形态与相对能力，但长期更大的空间是针对企业主要 workflow、甚至落到单个公司细节的 eval。你无法评估进度，就无法自动化；企业不能只靠 vibes 推进。

https://x.com/levie/status/2091359223368315050

**Practical AI educator Peter Yang** reported that Instinct now lets you delete external data (he removed 36 Gmail records) under Data Privacy, and gave the Instinct team credit for shipping that quickly after privacy pushback. Separately he shared a privacy workflow: open Google's connected-apps page in Chrome, run a prompt in Codex or Claude Code pointing at the open tab, then have the agent disconnect apps that should no longer hold your Google info. He also said he is building a new AI skill, `/fuck-cancer`, to help patients and families navigate cancer care and stay informed, and asked what to include.

Practical AI educator Peter Yang 反馈 Instinct 现已可在 Data Privacy 下删除外部数据（他删掉了 36 条 Gmail 记录），并肯定 Instinct 团队在隐私质疑后快速上线。另外他分享了一个隐私清理流程：在 Chrome 打开 Google 已连接应用页，用 Codex 或 Claude Code 提示模型看当前标签页，再让 agent 断开不该继续持有 Google 信息的应用。他还在做新 AI skill `/fuck-cancer`，目标是帮患者和家属梳理就医流程并保持知情，并征集应覆盖的内容。

https://x.com/petergyang/status/2091187611507499321
https://x.com/petergyang/status/2091331251211059468
https://x.com/petergyang/status/2091239339204415969

**Builder Zara Zhang** observed that talented people can get roughly 10x their potential with AI when working on their own thing, but in a large organization the same person often gains at most about 20%, and sometimes loses ground. That gap, she says, is why more talented people are leaving big companies, with top AI labs like OpenAI and Anthropic as the likely exceptions. She also noted that everyone who is ahead in using AI still thinks they are behind.

Builder Zara Zhang 观察到：有才华的人用 AI 做自己的事时，潜力大约能到 10x；但放进大组织，同样的人最多大概提升 20%，有时还会下降。她认为这就是越来越多人才离开大公司的原因，例外大概只有 OpenAI、Anthropic 这类顶级 AI lab。她还说，凡是在用 AI 上已经领先的人，往往仍觉得自己落后。

https://x.com/zarazhangrui/status/2091379220257603593
https://x.com/zarazhangrui/status/2091338374447763481

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
