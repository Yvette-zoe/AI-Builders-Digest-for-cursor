# AI Builders Digest — 2026-09-23

## X / TWITTER

**AI educator Peter Yang** warns ad markets are heading for a rude awakening: if your business depends on targeted display ads to humans, what happens when agents browse the site and finish the job without a human ever seeing the creative? On the product side, he highlights ChatGPT Finances spotting missed charges and chasing refunds. Product lead Ethan booked a hotel with points and still got billed; ChatGPT caught it, worked customer service, and got him reimbursed. Yang had a similar loop asking ChatGPT to cancel a parents' hotel booking, monitor replies, and keep following up until the money came back. His framing of daily life is blunt: he no longer lives in email or text; he lives in the chat with his agent(s).

AI educator Peter Yang 警告广告市场要迎来一次 rude awakening：如果生意高度依赖给人看的定向 display ads，当 agent 自己逛站把事办完、人类根本看不到创意时，广告还怎么变现？产品侧他强调 ChatGPT Finances 能揪出漏掉的扣款并追退款。产品负责人 Ethan 用积分订酒店却仍被收费；ChatGPT 发现后对接客服，帮他拿回报销。Yang 也有类似经历：让 ChatGPT 取消父母的酒店订单、盯回复、持续跟进直到退款到账。他对日常入口的表述很直白：自己不再住在邮件或短信里，而是住在和 agent(s) 的对话里。

https://x.com/petergyang/status/2102215701255844074
https://x.com/petergyang/status/2102186174911746151
https://x.com/petergyang/status/2102181024507765167

**Vercel CEO Guillermo Rauch** says that beyond the type-safe TypeSafe AI SDK API, you can now use Jev over HTTP in AI Gateway. Separately, he gave Grok 4.7 a hard reverse-engineering problem against a running binary; it solved it cleanly and fast.

Vercel CEO Guillermo Rauch 说，除了 type-safe 的 TypeSafe AI SDK API，现在还能在 AI Gateway 里通过 HTTP 用 Jev。另外他给了 Grok 4.7 一道很难的 running binary 逆向题；它解得漂亮，而且很快。

https://x.com/rauchg/status/2102205684544852121
https://x.com/rauchg/status/2102089968860721335

**Box CEO Aaron Levie** argues the monetization upside of personal agents that transact on your behalf is large. Once agents can run arbitrarily complex tasks end to end, a substantial share of commerce flows through them: people start with daily annoyances, then escalate to harder work, and lower friction can mean more spend than before. That is a win for agent providers (Muse and peers) and for new layers agents want to hit (commerce, local, B2B services). In a separate post he says AI agents will use software 100X more than people ever did. Even as UIs fade into the background, agents still need CRM, ERP, and structured/unstructured data primitives, and those become more important when agents can take destructive actions or when context makes or breaks the workflow. Platforms that act as the security and guardrails layer, manage data for agents and people, and orchestrate business logic have a big opening now, for startups and for incumbents that move fast enough.

Box CEO Aaron Levie 认为，替你下单办事的 personal agents，变现空间很大。一旦 agent 能端到端扛任意复杂任务，相当一部分 commerce 会从它们走过：人们先甩日常琐事，再逐步加码更难的事，摩擦下降反而可能让人花得更多。这对 Muse 等 agent 提供方是机会，也对 agent 想对接的新层（commerce、本地服务、B2B）是机会。另一条里他说 AI agents 用软件的强度会是人类的 100 倍。即便界面退到后台，agent 仍需要 CRM、ERP、结构化/非结构化数据这些核心 primitives；当 agent 可能做出破坏性操作、或上下文直接决定工作流成败时，这些 primitives 更重要。能当好安全与 guardrails、为 agent 与人管好数据、编排业务逻辑的平台，现在有巨大窗口，不论新创还是够快的老平台。

https://x.com/levie/status/2102253246807261579
https://x.com/levie/status/2102235949430354273

**Y Combinator President & CEO Garry Tan** calls Capy his favorite new agentic coding secret weapon of the last week: it tracks multi-step workflows and ships large PRs faster than Codex or Claude Code on its own. He shared an example PR where it ran an ambitious bug-fix wave on GBrain with clear task delineation, automatic parallelization, and a clean GitHub PR plus CI workflow. He also still likes the Cluely thesis: a realtime thought helper and semi-adversarial assistant with ongoing context remains a good idea.

Y Combinator President & CEO Garry Tan 把 Capy 称作近一周最爱的 agentic coding 秘密武器：它能跟踪多步 workflow，大 PR 的速度比单独用 Codex 或 Claude Code 更快。他贴了一个示例 PR：对着 GBrain 跑一波野心很大的 bug fix，任务切分清晰、自动并行，GitHub PR 与 CI 流程也很干净。他也仍看好 Cluely 的命题：带持续上下文的实时 thought helper、略带对抗性的助手，依然是个好主意。

https://x.com/garrytan/status/2102095924893827501
https://x.com/garrytan/status/2102096495847551011
https://x.com/garrytan/status/2102233173833007536

**FPV Ventures partner Nikunj Kothari** has used Codex as his primary agent long enough that he forgets most people have never touched it. Instinct and Muse impress him for phone browser use with zero setup, what a mass-market agent can feel like. But Codex on Mac with Computer Use (credit to Ari and the Sky team) is still undefeated for one-shotting workflows he used to do by hand; he wants the coming mass-market Codex agent launch to showcase real work and make onboarding easy. Separately he says companies that boast about tokenmaxxing often ship the worst product experiences, because good products are curation and gardening, not throwing the kitchen sink at agents and hoping they figure it out. Less is more.

FPV Ventures partner Nikunj Kothari 用 Codex 当主 agent 太久，以至于忘了大多数人根本没用过。Instinct 和 Muse 在手机浏览器、零配置场景让他觉得这才是大众该感受到的 agent。但配上 Computer Use 的 Mac 版 Codex（向 Ari 和 Sky 团队致谢）在一键扛完他以前手工做的 workflow 上仍是 undefeated；他希望即将面向大众的 Codex agent 发布能多展示真实工作成果，并把上手做简单。另一条里他说，吹 tokenmaxxing 的公司往往产品体验最差，因为好产品靠 curation 与 gardening，而不是把厨房水槽一股脑丢给 agent 指望它们自己搞定。Less is more。

https://x.com/nikunj/status/2102186665863463199
https://x.com/nikunj/status/2102049065504739366

**OpenClaw builder Peter Steinberger** pushes back on the circulating "Meta uses OpenClaw" story: Meta built its own agent, inspired by OpenClaw, and he credits Nat and the team. He is also proud that a security review found nothing critical, and notes the upside of running a claw yourself: they cannot block you.

OpenClaw builder Peter Steinberger 澄清正在流传的 “Meta uses OpenClaw” 说法：Meta 是自建 agent，灵感来自 OpenClaw，并向 Nat 和团队点赞。他也骄傲地表示安全审查没有发现 critical 问题，并点出自己跑 claw 的好处：他们没法把你封掉。

https://x.com/steipete/status/2102116206371315854
https://x.com/steipete/status/2102049706830647467
https://x.com/steipete/status/2102044040397238286

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
