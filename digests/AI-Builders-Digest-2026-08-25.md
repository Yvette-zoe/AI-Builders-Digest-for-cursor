# AI Builders Digest — 2026-08-25

## X / TWITTER

**OpenAI Codex & ChatGPT lead Thibault Sottiaux** followed up on the Codex usage reset: the reset has been propagated to accounts, and OpenAI landed fixes for the usage issues called out the day before, so users should feel a positive difference, with more changes still coming. Separately he argued that 2026 is the year companies start seriously caring about model efficiency and reliability, because models are becoming critical infrastructure.

OpenAI Codex & ChatGPT lead Thibault Sottiaux 跟进了 Codex 用量重置：重置已同步到账户，OpenAI 也落地了前一天提到的用量问题修复，用户应能感受到明显改善，后续还会继续更新。另外他认为，2026 年会是公司开始认真对待模型效率与可靠性的一年，因为模型正变成关键基础设施。

https://x.com/thsottiaux/status/2091688655828246890
https://x.com/thsottiaux/status/2091581575108653374

**Meta Sr Director of AI Madhu Guru** (ex-Google Gemini/Veo) published "How to build great evals - part 7" on the Goldilocks principle for eval construction: measure at the level of the jobs to be done, not only the final answer. For a financial-analysis agent, a golden set of correct stock picks is the common mistake, because client understanding, evidence gathering, data analysis, and the recommendation are separate stages with intermediate outputs that each need their own evals. If the final pick is wrong, staged scores (for example client understanding 92%, evidence extraction 92%, data analysis 70%, recommendation 75%) tell you where to dig, and when a stage is too complex you break it into finer jobs. Not too granular, not too coarse: make the eval set as granular as you need to diagnose and act.

Meta Sr Director of AI Madhu Guru（前 Google Gemini/Veo）发布 “How to build great evals - part 7”，讲 eval 构建的 Goldilocks principle：评测要落在各个 jobs to be done 的层级，而不只看最终答案。以金融分析 agent 为例，只做正确答案股票的 golden set 是常见错误，因为理解客户、收集证据、分析数据、给出推荐是不同阶段，各自有中间产出，也应有独立 eval。若最终推荐错了，分阶段分数（例如客户理解 92%、证据抽取 92%、数据分析 70%、推荐 75%）会告诉你该往哪挖；某阶段太复杂时，再拆成更细的 jobs。不要太细也不要太粗：eval set 的粒度要以能诊断、能行动为准。

https://x.com/realmadhuguru/status/2091684812012875981

**Vercel CEO Guillermo Rauch** said intelligence is getting cheaper: OpenAI Sol price cuts plus discounts on Vercel AI Gateway made Sol their fastest-growing frontier model, which he reads as demand for intelligence being highly elastic as inference costs fall, and as a reason gateways matter for capturing price volatility that lowers OpEx and lifts margins. He also restated the fx extension philosophy around open protocols (MCP, Skills, Plugins) plus Unix-style small programs that compose, with libfx enabling embeddability into custom CLIs, background agents, and software factories in local or cloud setups.

Vercel CEO Guillermo Rauch 认为 intelligence 正在变便宜：OpenAI Sol 降价叠加 Vercel AI Gateway 折扣，让 Sol 成为他们增长最快的前沿模型；他据此认为对 intelligence 的需求高度弹性，推理成本下降会迅速拉动用量，而 gateway 能抓住这种价格波动，降低运营成本并提升利润率。他还重申了扩展 fx 的哲学：围绕 MCP、Skills、Plugins 等开放协议，外加 Unix 式小程序组合，以及让 libfx 可嵌入自定义 CLI、后台 agent 与软件工厂（本地或云端）。

https://x.com/rauchg/status/2091671326897713424
https://x.com/rauchg/status/2091583525661384813

**Y Combinator President & CEO Garry Tan** predicted that systems of record will need to become AI harnesses, or face replacement by agents.

Y Combinator President & CEO Garry Tan 预测：systems of record 必须变成 AI harness，否则会被 agent 替代。

https://x.com/garrytan/status/2091742825042030681

**Practical AI educator Peter Yang** highlighted Shreya's framing of two kinds of AI evals. Top-down evals start from the task description alone and ask what you would invent in a vacuum; Claude is strong at helping here. Bottom-up evals come from gut feedback after reading lots of sample outputs and externalizing that judgment into evals; Claude is very bad at inventing those, and that part stays human.

Practical AI educator Peter Yang 强调了 Shreya 对两类 AI eval 的划分。Top-down eval 从任务描述出发，想象真空中你会设计什么；Claude 很擅长协助这类。Bottom-up eval 来自大量看样本输出后的直觉反馈，再把它外化成 eval；Claude 很不擅长发明这类，这一半仍要靠人。

https://x.com/petergyang/status/2091586298779955512

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
