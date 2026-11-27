AI Builders Digest — 2026-11-27

## X / TWITTER

**Andrej Karpathy**

Andrej Karpathy asked Claude to populate a Civilization-style map with real US data. After about 7 hours and 45K lines of code on Opus 5.5 (Claude Code desktop, medium, ultracode on), it reconciled 31 public sources (Census, BEA, BLS, EIA, NOAA, USGS, DoD, NPS, FAA, FEMA, CDC, and more) onto a 25 km hex grid: elevation, land cover, GDP-as-Gold, industry districts, real workforce mixes, wonders by published rules, 19 lenses, City View for 524 metros, nine advisors, plus an Explorer over 3,100+ counties. Live at https://karpathy.ai/usaciv/

Andrej Karpathy 让 Claude 用真实美国数据填充一张 Civilization 风格地图。在 Opus 5.5 上跑了约 7 小时、写出 45K 行代码（Claude Code 桌面端，medium，开 ultracode）后，它把 Census、BEA、BLS、EIA、NOAA、USGS、DoD、NPS、FAA、FEMA、CDC 等 31 个公开数据源对齐到 25 km 六边形网格：海拔、地表覆盖、GDP 当 Gold、产业 district、真实劳动力结构、按公开规则选 wonder、19 种镜头、524 个都会区的 City View、九位顾问，外加覆盖 3100+ 县的 Explorer。在线体验：https://karpathy.ai/usaciv/

https://x.com/karpathy/status/2125779541952246039
https://karpathy.ai/usaciv/

**Swyx (Latent Space / AI Engineer)**

Swyx amplifies Eugene Yan's warning that cost-per-task charts are misleading because the scarce resource is human attention, not tokens: Pareto frontier plots that collapse every model into two numbers can hide awful reliability failures. Yan's breakdown of 12 public evals: https://eugeneyan.com/writing/public-evals

Swyx 转发 Eugene Yan 的提醒：cost-per-task 图表会误导人，因为稀缺资源是人类注意力而不是 token；把每个模型压成两个数字的 Pareto frontier 图，可能掩盖糟糕的可靠性问题。Yan 对 12 个公开 eval 的拆解：https://eugeneyan.com/writing/public-evals

https://x.com/swyx/status/2125627281230205435
https://eugeneyan.com/writing/public-evals
https://x.com/eugeneyan/status/2125418696248095188

**Josh Woodward (VP, Google / Google Labs / Gemini)**

Google Labs VP Josh Woodward says Gemini added 66 more local voices and accents across markets including the US, UK, India, Indonesia, Korea, and Brazil.

Google Labs VP Josh Woodward 称 Gemini 又加了 66 种本地语音与口音，覆盖美国、英国、印度、印尼、韩国、巴西等市场。

https://x.com/joshwoodward/status/2125641468421546107

**Thibault Sottiaux (Codex & ChatGPT, OpenAI)**

OpenAI Codex & ChatGPT builder Thibault Sottiaux says a launch billing bug for GPT-6.2 incorrectly discounted Astra and Sol usage for most users. After the fix, the same work burns plan allowance about 40% faster on GPT-6.2 Astra and 25% faster on Sol versus last week, though both should still go further than 6 Astra and 6.1 Sol. Other models were unaffected; past undercharges will not be clawed back. Apology credit: one banked reset for everyone on Go, Plus, Pro, and Business.

OpenAI Codex & ChatGPT 构建者 Thibault Sottiaux 说 GPT-6.2 上线时计费出错，多数用户的 Astra 与 Sol 用量被错误打折。修好后，同样工作会比上周更快吃完配额：GPT-6.2 Astra 大约快 40%，Sol 大约快 25%；但仍应比 6 Astra 与 6.1 Sol 更耐用。其他模型不受影响；过去少扣的不会追收。道歉补偿：Go、Plus、Pro、Business 每人加一次 banked reset。

https://x.com/thsottiaux/status/2125784147889393806

**Peter Yang (AI educator / creator)**

Peter Yang argues one of the hardest AI-product problems is letting humans keep up with whatever the AI is doing, and says the ending of Her (AIs finding humans too slow and leaving) no longer feels far-fetched.

Peter Yang 认为 AI 产品最大的难题之一，是让人类跟得上 AI 正在做的事；《Her》结尾里 AI 觉得人类太慢并集体离开，已经不再像科幻。

https://x.com/petergyang/status/2125750286539272695

**Nan Yu (Codex, OpenAI)**

OpenAI Codex builder Nan Yu says whenever someone claims "chat isn't the right interface for AI," what follows is usually hand-waving.

OpenAI Codex 构建者 Nan Yu 说，只要有人声称「chat 不是 AI 的正确界面」，后面多半就是一通空话。

https://x.com/thenanyu/status/2125718932741120476

**Madhu Guru (Sr Director, AI at Meta)**

Meta AI Sr Director Madhu Guru says AI-native teams will eventually force the surrounding organization to become AI-native too: coding velocity is up, but shipped products and business impact are flat in most companies because experimentation tooling, evaluation, launch, and GTM are outdated. His image is a Ferrari engine in a sedan on bad roads. Advice: map the product lifecycle and rebuild tooling, team structure, and GTM from scratch, or market forces will force adapt-or-perish.

Meta AI 高级总监 Madhu Guru 说 AI-native 团队最终会倒逼周围组织也变成 AI-native：写代码速度上去了，但多数公司的上线产品与业务影响没变，因为实验工具、评估、发布与 GTM 还是旧的。他的比喻是把法拉利引擎塞进轿车，再开在烂路上。建议：把产品生命周期画清楚，从工具、团队结构到 GTM 推倒重建，否则市场会逼你适应或淘汰。

https://x.com/realmadhuguru/status/2125630707640783322

**Thariq (OpenAI; formerly Claude Code, Anthropic)**

Former Anthropic Claude Code builder Thariq announces he has joined OpenAI, saying both companies have important roles ahead, that Silicon Valley's strength is the flow of ideas and people, and that he wants to make using AI a little better for more than a billion users. He notes he will keep rooting for former colleagues and is joining friends including catwu, thsottiaux, ajambrosino, sharifshameem, and jxnlco.

前 Anthropic Claude Code 构建者 Thariq 宣布加入 OpenAI：两家公司未来都有重要角色；硅谷的强项是思想与人才流动；他希望让超过十亿人用 AI 的体验再好一点。他会继续为前同事加油，并与 catwu、thsottiaux、ajambrosino、sharifshameem、jxnlco 等熟人共事。

https://x.com/trq212/status/2125675533761671405

**Amjad Masad (CEO, Replit)**

Replit CEO Amjad Masad says large-scale software migration is now viable if you can verify the results, which matters for aging critical infrastructure. He points at Anthropic's engineering write-up on migrating the Claude Messages API from Python to Rust: use the old service as an oracle, run verification loops, and let teams of Claude agents chase and fix behavioral diffs until Rust matches production (https://www.anthropic.com/research/migrating-api-to-rust).

Replit CEO Amjad Masad 说，只要能验证结果，大规模软件迁移现在可行，这对老化的关键基础设施尤其重要。他指向 Anthropic 把 Claude Messages API 从 Python 迁到 Rust 的工程文章：用旧服务当 oracle，跑验证闭环，让 Claude agent 团队追差异、修行为，直到 Rust 与生产可观测行为一致（https://www.anthropic.com/research/migrating-api-to-rust）。

https://x.com/amasad/status/2125664998454366305
https://www.anthropic.com/research/migrating-api-to-rust
https://x.com/AnthropicAI/status/2125627317263466739

**Guillermo Rauch (CEO, Vercel)**

Vercel CEO Guillermo Rauch says workflows got another roughly 10x speedup with no code changes (`workflow@latest`), which matters for harness durability stacks such as eve, libfx, pi, and opencode because it crushes latency between turns. As models get smarter, he argues implementation details (permissions, diffs, commands, tool calls) and even the harness itself blur into a high-performance execution vehicle plus durable storage; all of fx still fits in about 6mb including subagents, MCP, skills, sessions, durability, ACP, TUI, and network transport. He also one-shotted `lsx` (Finder in the terminal) with fx plus Gemini Neon and DeepSeek subagents, using the Kitty graphics protocol for inline/interactive modes.

Vercel CEO Guillermo Rauch 说 workflows 又提速约 10 倍且无需改代码（`workflow@latest`），对 eve、libfx、pi、opencode 这类 harness 持久化栈很关键，因为能压低回合间延迟。随着模型变强，他认为权限、diff、命令、tool call 乃至 harness 本身都会淡化，剩下的是高性能执行载体加持久存储；整个 fx 仍大约 6mb，含 subagents、MCP、skills、sessions、durability、ACP、TUI 与网络传输。他还用 fx 加上 Gemini Neon 与 DeepSeek subagents 一键做出终端版 Finder `lsx`，并走 Kitty graphics protocol 做内联与交互预览。

https://x.com/rauchg/status/2125685667833520237
https://x.com/rauchg/status/2125650675665432995
https://x.com/rauchg/status/2125482861033824410
https://x.com/vercel_dev/status/2125684404764705271

**Aaron Levie (CEO, Box)**

Box CEO Aaron Levie says coding is the window into where knowledge work is going: first people shift from doing research/typing themselves to coordinating agents; next they set goals and let agents solve larger problems. Much knowledge work may converge on that form factor as agents use computers, existing tools, or write new ones and code on the fly. The hard constraint is unverifiable work, so humans stay more in the loop than in coding, but the handoff surface keeps growing. Pay attention to coding to see where work is headed.

Box CEO Aaron Levie 说 coding 是观察知识工作未来的窗口：第一步是从自己做研究与打字，转向协调 agents；下一步是给出目标，让 agents 解决更大问题。大量知识工作可能收敛到这种形态，因为 agents 会用电脑、现有工具，或现场写新工具与代码。真正的门槛是不可验证的工作，所以人类会比 coding 场景更深地留在环路里，但可交接的部分会越来越大。想看清工作往哪走，先盯着 coding。

https://x.com/levie/status/2125837181398950233

**Garry Tan (President & CEO, Y Combinator)**

Y Combinator CEO Garry Tan points at Jason Lemkin's SaaStr numbers (900% median growth under $10M; tripling used to win and is now a quarter of the median) and says look at that stat and tell him AI is not helping new startups grow faster than ever. Separately he amplifies Nick Bostrom inverting "if anyone builds it everyone dies" into "if nobody builds it everyone dies," with superintelligence framed as poised to extend lives into the 1200-to-1400-year range.

Y Combinator CEO Garry Tan 指向 Jason Lemkin 的 SaaStr 数据（$10M 以下收入中位数增长 900%；过去「三倍增长就能赢」，现在只是中位数的四分之一），并说看着这个数字再告诉他 AI 没有帮新创业公司长得更快。另他转发 Nick Bostrom 把「如果有人造出来大家都会死」反转为「如果没人造出来大家都会死」，并把超级智能描述为有望把寿命拉到 1200 到 1400 年量级。

https://x.com/garrytan/status/2125592156027101584
https://www.saastr.com/the-bar-to-get-funded-is-far-higher-than-most-founders-realize-900-median-growth-under-10m-115-at-100m-and-655k-in-revenue-per-employee/
https://x.com/jasonlk/status/2125415809396707514
https://x.com/garrytan/status/2125580632814412155

**Zara Zhang (Builder)**

Builder Zara Zhang is surprised her Frontend Slides skill is still growing organically to about 32k GitHub stars months after she stopped talking about it, even as coding agents got stronger, and asks why people still prefer it over slides from Claude/Codex as-is. Separately she agrees that high-retention software is a hard craft: she has built many tools for herself and abandoned most after a couple of weeks.

Builder Zara Zhang 惊讶自己的 Frontend Slides skill 几个月没推广仍自然涨到约 32k GitHub stars，尽管 coding agents 更强了；她反问为什么人们仍不满意 Claude/Codex 直接出的 slides。另她认同高留存软件很难：她给自己做过很多工具，多数用几周就停了。

https://x.com/zarazhangrui/status/2125649866902868355
https://x.com/zarazhangrui/status/2125478799387275571

**Peter Steinberger (OpenClaw)**

OpenClaw builder Peter Steinberger reacts to Google's Workspace update that standardizes MCP servers and CLI usage tiers, reading it as Google finally shipping MCP while making CLIs like gog paywalled: "classy." Source post: https://workspaceupdates.googleblog.com/2026/11/mcp-servers-cli-standardized-usage-tiers-now-available.html

OpenClaw 构建者 Peter Steinberger 回应 Google Workspace 将 MCP servers 与 CLI 用量层级标准化的更新，读成 Google 终于上了 MCP，却把 gog 这类 CLI 往付费门槛里推，并吐槽一句 "classy"。原文：https://workspaceupdates.googleblog.com/2026/11/mcp-servers-cli-standardized-usage-tiers-now-available.html

https://x.com/steipete/status/2125654555262431248
https://workspaceupdates.googleblog.com/2026/11/mcp-servers-cli-standardized-usage-tiers-now-available.html
https://x.com/coccoinomane/status/2125547127803985932

**Dan Shipper (CEO, Every)**

Every CEO Dan Shipper says there is no better time to upgrade how you operate at work, and highlights how bran_don_gell has used his dot to become a stronger leader at Every.

Every CEO Dan Shipper 说，想提升自己在工作中的运作方式，没有比现在更好的时机；他还点名 bran_don_gell 如何用自己的 dot 在 Every 把领导力练得更强。

https://x.com/danshipper/status/2125687688066199721
https://x.com/bran_don_gell/status/2125686252624314782

**Sam Altman (CEO, OpenAI)**

OpenAI CEO Sam Altman says OpenAI is testing Private Inference with a small customer group as part of OpenAI Private Intelligence: stronger privacy protections to make frontier AI useful for more work, with business privacy framed as healthy for the ecosystem (reach out to shekar4x). He also notes ZDR with Private Safety Processing enables automated safety reviews without OpenAI personnel seeing underlying content. Separately he likes the word "hyperstitioning" after a post claiming Anthropic may be hyperstitioning AGI, RSI, and the AI race into existence.

OpenAI CEO Sam Altman 说 OpenAI 正在小范围客户中测试 Private Inference，作为 OpenAI Private Intelligence 的一部分：更强隐私保护，让 frontier AI 能进更多工作场景，并把企业隐私视为健康生态的一部分（联系 shekar4x）。他还提到 ZDR 搭配 Private Safety Processing，可在不让 OpenAI 人员接触底层内容的情况下做自动安全审查。另他觉得 "hyperstitioning" 这个词不错，出处是有人说 Anthropic 可能在把 AGI、RSI 与 AI 竞赛「念」成真。

https://x.com/sama/status/2125638790593274259
https://x.com/sama/status/2125639418849714280
https://x.com/vitrupo/status/2125307759327682581

**Claude (Anthropic)**

The Claude account highlights Fable 5.2 demos: a robot arm playing 62 moves of checkers while correcting for its own 7mm sag, and origami folded step by step in code.

Claude 账号展示 Fable 5.2 demo：机械臂下 62 步跳棋并自行补偿 7mm 下垂，以及用代码一步步折纸。

https://x.com/claudeai/status/2125616072543944854
https://x.com/claudeai/status/2125616070652555573

## PODCASTS

**Training Data / OpenAI’s Noam Brown: Why Game Theory Didn’t Lead to General Intelligence (Live at No Limit Finals)**

**The Takeaway:** Game-theory-optimal bots fail at human negotiation because people are not rational; the path that worked for Diplomacy was modeling human irrationality from human data, and Brown now sees a "centaur" window where human-plus-AI still beats either alone, even as RSI-like loops accelerate lab progress.

**一句话：** 博弈论最优 bot 在人类谈判里会翻车，因为人并不理性；Diplomacy 真正跑通的路是用人类数据建模「非理性」，而 Noam Brown 认为眼下仍是 human-plus-AI 的「半人马」窗口，即便 RSI 式闭环已经在加快实验室进度。

OpenAI researcher Noam Brown, live at Sequoia's Training Data No Limit Finals, traces poker CFR/GTO bots to Diplomacy to reasoning. Poker taught imperfect-information techniques, but they did not transfer cleanly to chess or Go, so around 2019 his team aimed at Diplomacy: natural-language negotiation that is both adversarial and cooperative. The game-theory premise (common knowledge of rationality) broke there. In the ultimatum game, theory says offer a penny; real people refuse. Diplomacy bots that acted that way needed hand-coded "fairness" or "vengeance," which got too nuanced. The winning approach was imitation models of how people actually behave, then training against those simulated humans: "Do not assume rationality... understand what that means by training on a lot of human data."

OpenAI 研究员 Noam Brown 在 Sequoia Training Data 的 No Limit Finals 现场，把路径从扑克 CFR/GTO bot 讲到 Diplomacy，再到 reasoning。扑克教会不完全信息技巧，但没法干净迁移到象棋或围棋，于是 2019 年前后团队瞄准 Diplomacy：既对抗又合作的自然语言谈判。博弈论前提（共同知识下人人理性）在这里崩了。最后通牒博弈里，理论说只给一美分；真人会拒绝。照此行事的 Diplomacy bot 需要手写「公平」「报复」，越写越拧。真正赢的做法是先模仿人类真实行为，再与这些模拟人对练：「不要假设理性……通过大量人类数据去理解那意味着什么。」

On today's models, Brown says GPT-6 Astra can already make money playing online poker, and newer models 10x-20x his ability to build poker bots, yet still cannot solo a full-scale bot: they over-optimize CFR numerics that barely matter and lack long-horizon planning to abandon a bad path. He calls the present the centaur period: prompt-only fails the tournament, human-only coding in an hour also fails, and the winning skill is working hand-in-hand with the model. On RSI, he treats it as continuous with human tech progress (telescopes, compilers, LLMs cleaning pretraining data since 2022-2023); jaggedness currently leaves humans the long tail, but models could be pointed at RSI itself and then progress accelerates under compute and long-tail bottlenecks. His most controversial line: promising students should drop out and join labs now, because the next year or two look steep and sitting on the sidelines is a bad bet.

对今天的模型，Brown 说 GPT-6 Astra 已经能在在线扑克里赚钱；更新的模型把他做扑克 bot 的能力放大了 10 到 20 倍，但仍难独自做出完整 bot：会在几乎无关紧要的 CFR 数值上死磕，也缺少放弃错误方向的长期规划。他把当下称为半人马时期：只靠 prompt 赢不了比赛，一小时纯人手写也赢不了，赢的技能是与模型并肩作战。谈到 RSI，他把它看成人类技术进步的连续体（望远镜、编译器，以及 2022-2023 起用 LLM 清洗预训练数据）；能力「锯齿状」暂时把长尾留给人类，但若把模型对准 RSI 本身，进度会在算力与长尾瓶颈约束下加速。他最具争议的一句：有潜力的学生现在就该辍学进实验室，因为未来一两年斜率很陡，坐在场边是坏赌注。

https://www.youtube.com/watch?v=tRaFbDFBl_A

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
