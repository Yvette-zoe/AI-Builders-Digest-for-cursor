# AI Builders Digest — 2026-10-12

## X / TWITTER

**OpenAI Codex product builder Nan Yu** agrees that agents make engineers extremely powerful, while PMs stay bottlenecked on the bandwidth they have to talk to customers, so the ideal ratio is 1:1.

OpenAI Codex product builder Nan Yu 也感到：agents 让工程师极其强大，但 PM 仍受限于能和客户交流的带宽，所以理想配比是 1:1。

https://x.com/thenanyu/status/2108976262698115550

**Meta Sr Director of AI Madhu Guru** maps the agent stack's evolution as capability → trust → autonomy. Capability (model + harness + tools + context reliably getting work done) has gotten pretty far; focus now shifts to trust: right action with right permissions, plus observe, audit, and accountability. He warns agent capabilities will soon evolve at RSI pace, so agentic security (identity, permissions, observability) must outpace that.

Meta Sr Director of AI Madhu Guru 把 agents 空间的演化方向写成 capability → trust → autonomy。capability（model + harness + tools + context 能否可靠把活干完）已经走得很远；现在焦点转向 trust：是否在正确权限下采取正确动作，以及可观察、可审计、可问责。他警告 agent 能力很快会按 RSI 节奏演进，因此 agentic security（identity、permissions、observability）必须跑得更快。

https://x.com/realmadhuguru/status/2108982858513776899

**Box CEO Aaron Levie** says agent swarms are where tokens will be consumed: parallelizing agents against a unified goal when work volume is large or the search space is not known upfront, across software development, cyber, life sciences, AI research, finance, and more. Agents can fan out and coordinate in ways humans cannot, because people hit limits on communication, status, conflicts, and shared context; as models handle larger context and share infrastructure, outcomes in medicine, research, cyber defense, and discovery can be qualitatively different, which is why we will need 1,000X more compute. Separately, he frames enterprise AI safety as a coming "zero trust" era: treat frontier closed and open-weight models like insider risks (not because they are necessarily malicious, but because capable actors with access can err or be compromised), and build containment, governance, audit, and blast-radius controls for agents operating on the most valuable data.

Box CEO Aaron Levie 认为未来 tokens 会砸向 agent swarms：在工作量大或搜索空间事先未知时，让 agents 对着统一目标并行展开，覆盖软件开发、cyber、生命科学、AI 研究、金融等领域。agents 能以人类做不到的方式分头协作，因为人受限于沟通、同步状态、冲突与共享上下文；随着模型能扛更大 context、并有共享基础设施有效通信，医学、研究、网络防御与发现可能出现质变结果，这也是为什么需要 1000 倍算力。另有一则把企业 AI 安全写成即将到来的 “zero trust” 时代：把 frontier closed 与 open-weight 模型当 insider risk 来对待（不是因为它们一定恶意，而是有能力且有权限的行为体也会犯错或被攻破），并为触达最有价值数据的 agents 建 containment、治理、审计与 blast radius 控制。

https://x.com/levie/status/2109079686286565378
https://x.com/levie/status/2108952226714865966

**Y Combinator President & CEO Garry Tan** shares how he runs GStack in practice: experimental modes with Captain on, one coordinating thread that owns the merge PR queue and only lets full-CI green runs into master; `/autoplan` with an ELI5 plan he still approves, though he rarely has to intervene because frontier models are strong; and for GBrain-style retrieval/latency work, clear evals on retrieval, latency, and cost per compute across 40+ auto-researchable categories.

Y Combinator President & CEO Garry Tan 分享他实际怎么跑 GStack：打开含 Captain 的 experimental modes，用一条协调线程管 merge PR 队列，只让跑完完整 CI 且全绿的进 master；用 `/autoplan` 并让 agent 把计划 ELI5，自己仍会审批，但因为 frontier models 够强，很少需要插手；对 GBrain 这类 retrieval/latency 任务，围绕 retrieval、latency 与 cost per compute 设清晰 evals，覆盖 40+ 可自动研究与改进的类别。

https://x.com/garrytan/status/2108954741065879945
https://x.com/garrytan/status/2108954740013043789
https://x.com/garrytan/status/2108954738540863498

**FPV Ventures partner Nikunj Kothari** argues founders cannot both demand conviction and double-downs when chips are down, and then ask funds to skip contracted pro rata for dilution convenience. Every VC should earn the right to the cap table at every stage; breaking contracts and handshakes for short-term gain erodes brittle trust. Reminder for founders: choose partners and contracts carefully, and get a good independent lawyer.

FPV Ventures partner Nikunj Kothari 认为创始人不能既要求基金在筹码下跌时展示 conviction 并加注，又为稀释方便要求对方放弃 contracted pro rata。每个 VC 都应在每一轮重新挣到进入 cap table 的资格；为短期利益撕毁合同与握手，会侵蚀本就脆弱的信任。给创始人的提醒：认真选合作伙伴和合同条款，并找一位靠谱的独立律师。

https://x.com/nikunj/status/2109038632975876395

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
