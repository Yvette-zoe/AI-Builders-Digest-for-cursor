# AI Builders Digest — 2026-08-27

## X / TWITTER

**OpenAI Codex & ChatGPT lead Thibault Sottiaux** announced a ChatGPT plan for teams and small companies that works like the Pro $100 plan but adds workspace features: all ChatGPT, ChatGPT Work, and Codex features; connectors for Google Workspace, Slack, GitHub, Microsoft 365, and more; SAML, SSO, and MFA; centralized billing and admin; usage analytics and spend controls; and no 5-hour limits. He said demand for it has been huge.

OpenAI Codex & ChatGPT lead Thibault Sottiaux 宣布了一款面向团队与小公司的 ChatGPT 方案，用法类似 Pro $100，但加上 workspace 能力：覆盖全部 ChatGPT、ChatGPT Work 与 Codex 功能；可连接 Google Workspace、Slack、GitHub、Microsoft 365 等；支持 SAML、SSO 与 MFA；集中计费与管理；用量分析与支出控制；且没有 5 小时限额。他说市场对这款方案的需求非常大。

https://x.com/thsottiaux/status/2092345330272780499

**Meta Sr Director of AI Madhu Guru** (ex-Google Gemini/Veo) published "How to build great evals - Part 9" on the Eval Roadmap Problem: most evals fail because teams treat them as static artifacts while user expectations and behaviors keep evolving. He walks a financial research agent from summarizing one earnings report, to multi-filing synthesis, to proactive portfolio monitoring, and says evals must move with usage (short-context to long-context, single-turn to multi-turn, reactive chat to proactive agent). Practical steps: map the dimensions that will evolve, prioritize what matters, mine production traces, build P0 evals for the next stage, then find failure modes and hill-climb. He also posted an index linking Parts 1 through 9.

Meta Sr Director of AI Madhu Guru（前 Google Gemini/Veo）发布 “How to build great evals - Part 9”，讲 Eval Roadmap Problem：多数 eval 失败，是因为团队把它们当成静态产物，而用户预期与行为一直在变。他以金融研究 agent 为例，从总结一份财报，到多文件综合，再到主动监控组合，说明 eval 必须跟着用法演进（短上下文到长上下文、单轮到多轮、被动对话到主动 agent）。实操步骤：画出会演进的维度、排出优先级、挖掘生产 traces、为下一阶段做 P0 eval，再找 failure modes 并 hill-climb。他还发了一份串联 Part 1 到 Part 9 的目录。

https://x.com/realmadhuguru/status/2092426017118028266
https://x.com/realmadhuguru/status/2092461206783373758

**Anthropic Claude** shipped one memory across chat and Claude Cowork: hand Cowork a task and it starts from what Claude already knows from chats. Everything remembered is a list of topics in Settings you can read, edit, or delete; memory also updates on its own, and you can say "remember this." Sensitive topics like health or religious beliefs stay out unless you turn them on. Memory is on by default for Free, Pro, and Max. Anthropic Claude Code lead Boris Cherny called it a small improvement that makes memory simpler and more powerful; Anthropic Claude Code + Cowork engineer Cat Wu said unified memory means you tell Claude once and it has that context across surfaces.

Anthropic Claude 上线了跨 chat 与 Claude Cowork 的统一 memory：把任务交给 Cowork 时，它会从你在对话里已经让 Claude 知道的内容起步。所有记忆都以 Settings 里的 topic 列表呈现，可查看、编辑或删除；memory 也会自行更新，你也可以说 “remember this”。健康或宗教信仰等敏感话题默认不进 memory，除非你主动打开。Free、Pro、Max 默认开启 memory。Anthropic Claude Code lead Boris Cherny 称这是让 memory 更简单也更强的小改进；Anthropic Claude Code + Cowork engineer Cat Wu 说统一 memory 后，告诉 Claude 一次，就能在各表面复用同一上下文。

https://x.com/claudeai/status/2092299704864284888
https://x.com/claudeai/status/2092299707653439497
https://x.com/claudeai/status/2092299710002319742
https://claude.com/blog/claudes-memory-works-everywhere-and-you-decide-whats-in-it
https://x.com/bcherny/status/2092355642363453943
https://x.com/_catwu/status/2092337156455051345

**Vercel CEO Guillermo Rauch** introduced Run SDK for secure eval of dynamic Code Mode execution: when agents write code, you do not always need a full sandbox; you can run it in a lightweight QuickJS secure context that is faster and cheaper (`npm i run`). He also said Vercel Connect is GA: the hardest agent problem is secure connectivity to services and data, and `vercel connect create notion` (and similar) yields an MCP client you can query on behalf of the authenticated user.

Vercel CEO Guillermo Rauch 发布 Run SDK，用于安全 eval 动态 Code Mode 执行：当 agent 写代码时，不一定需要完整 sandbox；可以在轻量 QuickJS 安全上下文中运行，更快也更省（`npm i run`）。他还宣布 Vercel Connect 正式 GA：做 agent 最难的是安全连接服务与数据，执行如 `vercel connect create notion` 后，就能得到代表已认证用户查询的 MCP client。

https://x.com/rauchg/status/2092382653161107534
https://vercel.com/blog/introducing-run
https://x.com/rauchg/status/2092352411839193234

**Box CEO Aaron Levie** said applied AI at scale sits in the gap between raw models/agents and real enterprise workflows: the premium goes to companies that diffuse intelligence into outcomes, not those that only ship tokens. That means context, change management, multi-model harnesses, vertical system connectors, UX that puts agents in the right workflow, and domain evals. He argues there is a window now to build the defining companies that bring intelligence into critical enterprise domains.

Box CEO Aaron Levie 认为，规模化 applied AI 的机会在“原始模型/agent”与真实企业工作流之间的鸿沟里：溢价属于能把智能扩散成结果的公司，而不是只卖 token 的公司。这需要上下文、变革管理、多模型 harness、垂直系统连接、把 agent 放进正确工作流的 UX，以及领域 eval。他说现在有窗口去打造那些把智能带进企业关键领域的定义性公司。

https://x.com/levie/status/2092466424694649066

**Practical AI educator Peter Yang** open-sourced `/fuck-cancer`, an AI skill that helps patients and caregivers navigate diagnosis, treatment, and advocacy. It builds and updates a brief with five sections: patient and care-team info, up to three next actions, confirmed facts vs unknowns, plain-English medical terms, and a care log. It works from documents and context you provide, and can research via sources such as the National Cancer Institute and the ClinicalTrials.gov API; briefs can save as local Markdown or a shared Google Doc. He uses it with ChatGPT/Codex and Claude Code.

Practical AI educator Peter Yang 开源了 `/fuck-cancer`，一个帮助患者与照护者应对诊断、治疗与自我倡导的 AI skill。它会创建并更新一份含五部分的 brief：患者与医护团队信息、最多三项下一步行动、已确认事实 vs 未知、通俗医学术语解释，以及护理日志。它基于你提供的文档与上下文工作，需要时可通过 National Cancer Institute、ClinicalTrials.gov API 等可信来源检索；brief 可存成本地 Markdown 或可共享的 Google Doc。他本人用 ChatGPT/Codex 与 Claude Code 来跑它。

https://x.com/petergyang/status/2092249012913258946
https://x.com/petergyang/status/2092311110871617915
https://github.com/petergyang/fuck-cancer/

**smol.ai / Latent Space host Swyx** warned not to use Codex "locked use" on macOS right now: it relies on unstable Mac features and locked him out of his keychain twice this week. He cited Apple developer forums acknowledging a known bug, and said cloud would be nicer but is not there yet.

smol.ai / Latent Space host Swyx 警告眼下不要在 macOS 上用 Codex 的 “locked use”：它依赖不稳定的 Mac 特性，本周已两次把他锁出 keychain。他引用 Apple developer forums 承认这是已知 bug，并说理想情况是全上云，但云端还没准备好。

https://x.com/swyx/status/2092492963435946494

**Google Labs** launched Play with Putty, a collaborative vibe-coding experiment for building tools and websites together in real time. Waitlist is at labs.google/playwithputty (US only, ages 18+).

Google Labs 发布 Play with Putty，一个可实时多人协作的 vibe-coding 实验，用来一起搭工具与网站。候补名单在 labs.google/playwithputty（仅限美国，18 岁以上）。

https://x.com/GoogleLabs/status/2092293667688173593
https://labs.google/playwithputty

**SPC General Partner Aditya Agarwal** said public hatred of datacenter buildout is unsurprising while AI mainly helps knowledge workers and the highest-paid segments. He expects broader acceptance when AI finds cures for diseases that affect everyone, notes some of the brightest minds are moving there, and criticizes the industry for fear-mongering instead of painting a positive future.

SPC General Partner Aditya Agarwal 说，公众讨厌建数据中心并不意外，因为今天的 AI 主要帮知识工作者与收入最高的人群。他预计当 AI 能找到影响所有人的疾病疗法时，接受度会大变；也指出一些最聪明的人已转向那里，并批评行业只会渲染恐惧，而不是描绘积极未来。

https://x.com/adityaag/status/2092290497826173186

## PODCASTS

### Training Data: Parallel’s Parag Agrawal: Building a New Web for AI Agents

**The Takeaway:** Former Twitter CEO Parag Agrawal is building Parallel Web Systems so agents can search and use the web at 1000x human volume, treating human click data as a bug and pricing publisher value with Shapley-style attribution instead of ads.

**要点：** 前 Twitter CEO Parag Agrawal 正在做 Parallel Web Systems，让 agent 能以人类 1000 倍的量级搜索并使用网页；他把人类点击数据当成 bug，并用 Shapley 式归因（而非广告）给出版方定价。

Parallel started from the bet that agents will search and browse far more than humans ever did, so both the retrieval stack and the business model have to be reinvented for a customer that mostly does not exist yet. Agrawal says post-product-market-fit Twitter taught him loops from hundreds of millions of daily users; Parallel is the opposite: build for a not-yet-here customer while learning every week. They launched a search agent first (insurance underwriting, claims, sales enrichment, finance data prep) so they could compete with outsourced human web work and grow the index incrementally, instead of spending all infrastructure money before a customer existed.

Parallel 的起点是：agent 未来搜索与浏览的量会远超人类，因此检索栈与商业模式都要为“尚未大规模出现的客户”重做。Agrawal 说，已过 product-market-fit 的 Twitter 教给他的是来自数亿日活用户的反馈回路；Parallel 正好相反：为尚未到来的客户建设，并每周学习。他们先上线 search agent（保险核保与理赔、销售 enrichment、金融数据准备等），去替代外包人类网页工作，并逐步扩大 index，而不是在客户出现前把基建预算烧光。

Vs piping every deep-research step through Google, he claims Parallel search typically uses under half the tokens, with better accuracy and speed: "If you use parallel search, you will, for the most part, use under half the tokens in your agent." The north star is a forever billion-to-billion matching problem (pages vs queries) under quality, cost, and latency budgets. He rejects the idea that model labs will simply own agent search because their pretraining crawls are not completionist enough for slow JavaScript-heavy pages; Parallel crawls what model trainers skip. They did announce a Google Cloud partnership as a search and grounding option beside Google Search for enterprise agent APIs on GCP.

相对把 deep research 每一步都丢给 Google，他声称 Parallel search 通常能把 agent 的 token 用量压到一半以下，同时更准更快：“If you use parallel search, you will, for the most part, use under half the tokens in your agent.”北极星是在 quality、cost、latency 约束下，永远做十亿级页面与十亿级查询的匹配。他不认为模型公司会天然垄断 agent search，因为预训练爬取不够 completionist，不愿为慢速、重度 JavaScript 页面付出一到两个数量级更差的 token/compute 比；Parallel 专门爬模型方跳过的部分。他们也宣布与 Google Cloud 合作，成为 GCP 企业 agent API 上除 Google Search 外的 search/grounding 选项。

On internet economics, he argues ads worked because of differential pricing under scarce human attention; when agents show up instead of eyeballs, that breaks. Parallel’s answer is incentive-aligned payments with differential pricing on both content uniqueness and the value of the work reading it, estimated via Shapley values (leave-one-source-out simulations of agent quality vs extra compute). Full Shapley is too expensive to compute literally, so they train estimators. Macro math: if 2% to 10% of LLM inference spend for knowledge work flowed to web data, that dwarfs most non-walled-garden web data businesses today, and he thinks meaningful publisher dollars are 12 to 24 months away. The company was briefly incorporated as Shapley Inc.; "Parallel" stuck because publishing now means dual audiences (humans and agents) on a parallel web. The longer arc he wants is web pull turning into push: "call me if this happens" feeds so agents allocate compute across everything that changed on the web.

在互联网经济上，他认为广告之所以有效，是因为稀缺人类注意力下的差异化定价；当出现的是 agent 而不是眼球，这套假设就崩了。Parallel 的答案是激励相容的付费：对内容独特性与读取该内容的工作价值做双重差异化定价，并用 Shapley value（拿掉某个来源后，agent 质量损失 vs 额外 compute 的模拟）来估算。完整 Shapley 计算贵到不划算，所以他们训练估计器。宏观账：若知识工作 LLM 推理支出的 2% 到 10% 流向网页数据，规模会远超今天多数非围墙花园的网页数据生意；他判断有意义的出版方收入大约还要 12 到 24 个月。公司一度注册为 Shapley Inc.；“Parallel”留下，是因为发布内容现在意味着同时面对人类与 agent 两套受众，即 parallel web。他更长线想要的是网页从 pull 变成 push：用 “call me if this happens” 类 feed，让 agent 根据网页上持续变化的信息去分配 compute。

https://www.youtube.com/playlist?list=PLOhHNjZItNnMm5tdW61JpnyxeYH5NDDx8

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
