# AI Builders Digest — 2026-11-02

## X / TWITTER

**Box CEO Aaron Levie** offers a litmus test for whether you are pushing AI hard enough: if the work you are doing could have been done the same way before AI, you are probably not pushing it enough. Until about six months ago, AI mostly sped up outputs you would have produced anyway; now the bar is qualitatively different outcomes in a fraction of the time. Prototypes should be fully functional, interactive, and meaningfully better featured; architectures should chase performance gains you would not have attempted; research should consume every relevant fact; AI-run processes should learn from past failures in ways no human could. Intelligence is still jagged, but combining AI with human strengths on enough axes yields results that are not just faster versions of the old path.

Box CEO Aaron Levie 给出一个判断你是否把 AI 用够了的 litmus test：如果你现在做的事用 AI 之前也能同样做到，那你多半还没用够。大约六个月前，AI 主要是把你本来就会产出的东西做得更快一点；现在的标准是在更短时间内做出质变结果。原型应可交互且功能明显更强；架构应去追以前不会碰的性能提升；研究应吃掉该主题所有维度的事实；用 AI 跑的业务流程应能以前所未有的方式从失败中学习。智能仍 jagged，但在足够多维度上把 AI 与人的长处结合，得到的就不只是旧路径的加速版。

https://x.com/levie/status/2116652002830963114

**AI Engineer / Latent Space host Swyx** notes that Andrej Karpathy uses medium effort on Opus 5.5 for his latest project (Hackertube launched today), and argues that strong opinions on effort levels are the new tabs-vs-spaces: tweak to taste. For throughput-constrained work, he prefers low effort plus a critique loop over "superultramaxhighwhatever," pointing to his babysit-runs skill.

AI Engineer / Latent Space host Swyx 提到 Andrej Karpathy 在最新项目（Hackertube 今日上线）上对 Opus 5.5 用 medium effort，并称对 effort 档位的执念已成新版 tabs vs spaces：按口味调即可。对 throughput 受限的工作，他更偏向 low effort + critique loop，而不是一路拉满的 "superultramaxhighwhatever"，并指向自己的 babysit-runs skill。

https://x.com/swyx/status/2116773135668404286
https://x.com/swyx/status/2116642586387730593

## PODCASTS

### Using Agents for Long-Horizon Financial Work — Aman Singh, Arca

**The Takeaway:** AI-native wealth firms win by making agents prompt advisors 24/7, not by handing clients a chatbot; the product is proactive long-horizon service behind a human, with deterministic money-moving guardrails.

**The Takeaway：** AI-native 财富管理机构靠的是让 agent 全天候主动 prompt 顾问，而不是给客户一个 chatbot；产品是人背后的主动、长周期服务，再加上 deterministic 的资金操作护栏。

At AI Engineer New York 2026, Latent Space talks with Aman Singh, who leads the AI platform team at Arca, an AI-native wealth management firm that recently raised $64M. Arca is not selling SaaS: it is the firm itself. Clients never touch the agents; they feel an advisor-delivered level of service that was not previously possible, while agents handle the machinery around each client: markets, life events, tax, estate, insurance, and the textures of daily financial reality.

在 AI Engineer New York 2026，Latent Space 对话 Aman Singh。他领导 Arca 的 AI platform 团队；这家 AI-native 财富管理机构近期融资 $64M。Arca 卖的不是 SaaS，它本身就是这家公司。客户不直接接触 agent；他们感受到的是顾问交付的、此前行业做不到的服务水准，而 agent 负责每个客户背后的机器：市场、人生事件、税务、遗产、保险，以及日常财务现实的各种纹理。

Singh's framing: "The role of AI at Arca is not to replace the advisor. It is to replace all of the work around the advisor." And the sharper version that becomes the company's thesis: "Agents prompt people more than people prompt agents." Model choice is driven by internal harness benchmarks rather than leaderboard lore (Claude is primary; external wins for Luna did not fit on latency and cost), with a deliberate model-agnostic stance so the firm never depends on one lab's harness.

Singh 的定位："The role of AI at Arca is not to replace the advisor. It is to replace all of the work around the advisor." 更锋利的公司命题是："Agents prompt people more than people prompt agents." 模型选型由内部 harness 基准驱动，而不是榜单叙事（Claude 为主；Luna 外部评测再好，延迟与成本也不合用），并刻意保持 model-agnostic，避免绑死某一家 lab 的 harness。

Long-horizon work (multi-day tax bills, plans that resume after new signals) lives in per-client memory plus a "dreaming" reflection loop that updates what is in flight, who owns what, and what must happen next. Safety is deterministic at the edges: agents can analyze freely, but money movement, liquidation, and client communication require human-in-the-loop; every write gets LLM verification; inbound email/docs/calls are checked for prompt injection; outbound surfaces get PII and exfil consensus checks. Sandboxes are for offloading computation and producing plan artifacts, then verifiers (deterministic rules plus fast models / JEV) block non-compliant language like promising returns. Decision models also catch confident-but-stale knowledge, such as models happily using 2025 tax brackets, and nudge the system toward a verified knowledge base or search. Memorable result: agents reviewing a prospect's statements surfaced hidden fees and that the prior advisor was not a fiduciary.

长周期工作（跨多日的税单、收到新信号后再续上的计划）落在 per-client memory，再加上一层会反思客户世界状态的 "dreaming"，用来更新进行中的事、责任归属与下一步。安全在能力边界上是 deterministic 的：agent 可自由分析，但动钱、清算资产、直接对客户沟通必须 human-in-the-loop；每次写操作有 LLM 校验；入站邮件/文档/通话做 prompt injection 检测；出站表面做 PII 与外泄共识检查。Sandbox 用于卸载计算并产出计划产物，随后 verifiers（deterministic 规则 + 小模型 / JEV）拦截承诺收益等不合规表述。Decision models 还会抓住「自信但过时」的知识，例如模型很乐意用 2025 税率表，并把它拉回已验证知识库或搜索。难忘结果：agent 审阅一位准客户的对账单时，挖出隐藏费用，并发现原顾问甚至不是 fiduciary。

https://www.youtube.com/@LatentSpacePod

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
