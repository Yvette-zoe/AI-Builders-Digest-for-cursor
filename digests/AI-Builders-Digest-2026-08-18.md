AI Builders Digest — 2026-08-18

## X / TWITTER

**Codex & ChatGPT lead Thibault Sottiaux (OpenAI)** documents how to unlock a 1M-token context window for GPT-5.6 Sol in Codex: set `model`, `model_context_window = 1000000`, and `model_auto_compact_token_limit = 900000` in `~/.codex/config.toml` (or pass the same via one-shot CLI flags), then restart into a new session. He warns the smaller default was tuned for performance and cost; a bigger window keeps more code, tool output, and history before compaction. Separately, Sol 1M support that used to be API-key-only now works for ChatGPT-account usage too. He also posts a Codex checklist: almost 100% reliable, occasional resets, open-source, and "(will have Astra)".

Codex 与 ChatGPT 负责人 Thibault Sottiaux（OpenAI）写明如何给 GPT-5.6 Sol 在 Codex 打开 100 万 token context：在 `~/.codex/config.toml` 设置 `model`、`model_context_window = 1000000`、`model_auto_compact_token_limit = 900000`（或用一次性 CLI 参数），然后重启进入新会话。他提醒更小的默认值是按性能与成本调过的；更大窗口能在压缩前保留更多代码、工具输出与历史。另外，原先仅 API key 可用的 Sol 1M，现已对 ChatGPT 账号用量开放。他还发了 Codex checklist：几乎 100% 可靠、偶尔 reset、开源、以及 “(will have Astra)”。

https://x.com/thsottiaux/status/2089082893804896524
https://x.com/thsottiaux/status/2089143488696705077
https://x.com/thsottiaux/status/2089149255382438340

**Replit CEO Amjad Masad** highlights an 18x improvement in intelligence per joule over 16 months, amplifying the efficiency side of the capability story rather than raw scale alone.

Replit CEO Amjad Masad 强调过去 16 个月 intelligence per joule 提升了 18 倍，把能力叙事拉回效率一侧，而不只是堆规模。

https://x.com/amasad/status/2089069905375351169

**Vercel CEO Guillermo Rauch** says internal evals put GLM 5.3 at the new open frontier for cybersecurity capabilities. Because costs are lower, he expects a boost for defensive security work, arguing teams can run the linked defensive workflow at least 3× more often.

Vercel CEO Guillermo Rauch 称内部 eval 显示 GLM 5.3 已成为 cybersecurity 能力的新 open frontier。由于成本更低，他预期这对防御安全工作是利好，例如可以把所链防御工作流至少多跑 3 倍频次。

https://x.com/rauchg/status/2089126690043916495

**Box CEO Aaron Levie** frames agent value as tireless work that was never impractical for lack of desire, only for lack of feasibility: exhaustive vulnerability hunting, reading every contract, combing every customer signal for upsells. The opportunity is markets where more compute qualitatively changes what customers can do. Separately on spend: AI budgets are nowhere near a wall; in engineering-weighted data the top 1% spend about $7,500/mo per employee and the top 10% about $660/mo, with today's top-decile token volume possibly looking like the median in three years as costs fall and agents absorb more of the workload.

Box CEO Aaron Levie 把 agent 的价值说成：那些你并非不想做、只是以前根本不现实的活，现在可以不眠不休地做：穷尽漏洞扫描、读完每一份合同、扫过每个客户信号做 upsell。机会在「更多算力会质变客户能力」的市场。花费上：AI 预算远未撞墙；偏工程公司的数据里，top 1% 约每人每月 $7,500，top 10% 约 $660；随着成本下降、agent 吃下更多工作，今天的 top 10% token 用量三年后可能变成中位水平。

https://x.com/levie/status/2089209131391729763
https://x.com/levie/status/2088995821056659901

**Claude Code builder Thariq (Anthropic)** notes it says a lot that the creators of three iconic web frameworks (Django, Flask, and Rails) got AI-pilled so early.

Anthropic Claude Code builder Thariq 说：Django、Flask、Rails 这三套标志性 web framework 的创造者都那么早就 AI-pilled，本身就很能说明问题。

https://x.com/trq212/status/2089085004966207679

**Every CEO Dan Shipper** is skeptical that AI's optimal design stays maximally centralized. He traces the fear to Lewis Mumford's authoritarian vs democratic technology split and Thiel's "crypto is libertarian and AI is communist," then points to fine-tuning for specific purposes plus the human brain as evidence for decentralization benefits, even if today's systems still look like early "bee or ant" hyper-central phases. Separately, he used Fable to vibe-code an app that visualizes and clusters everyone who applied to Thesis, arguing detailed customer clustering is now possible with very little effort.

Every CEO Dan Shipper 怀疑 AI 的最优形态会一直极度中心化。他把这种担忧追溯到 Lewis Mumford 的威权 vs 民主技术二分，以及 Thiel 的 “crypto is libertarian and AI is communist”；同时指出面向具体用途的 fine-tuning，以及人脑作为去中心化收益的证据，即便当下系统仍像早期 “bee or ant” 式的超中心阶段。另外，他用 Fable vibe code 做了个把 Thesis 申请者可视化并分群的 app，认为对每个客户的细致理解与聚类，现在几乎不用费力就能做到。

https://x.com/danshipper/status/2089127868903375257
https://x.com/danshipper/status/2089121597017759800

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
