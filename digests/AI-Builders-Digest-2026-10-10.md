# AI Builders Digest — 2026-10-10

## X / TWITTER

**OpenAI Codex & ChatGPT builder Thibault Sottiaux** hits Day 4: steering is now instant, so the model reacts much faster to mid-run adjustments and you can course-correct in realtime without wasting effort. He is also releasing GPT-6.1 Sol ultrafast, and says the two work very well together.

OpenAI Codex & ChatGPT builder Thibault Sottiaux 进入 Day 4：steering 已做到即时响应，模型对中途调整反应快得多，你可以实时纠偏，避免浪费算力。他还在发布 GPT-6.1 Sol ultrafast，并说两者搭配效果很好。

https://x.com/thsottiaux/status/2108275041276420573

**Meta Sr Director of AI Madhu Guru** argues every layer of the computing stack must be rebuilt for agents, and that is where massive startup opportunities hide. After years of making enterprise software agent-ready via APIs, connectors, and MCPs, personal agents are forcing the same rewrite for consumer products (e-commerce first). Look next at agent-first desktop/mobile OSes, cloud infra agents can operate directly, identity/permissions/security for thousands of agents acting on our behalf, and interfaces for agents, humans, or both. His prompt for founders: walk each stack layer and ask what changes when the primary user is an agent.

Meta Sr Director of AI Madhu Guru 认为计算栈每一层都要为 agents 重建，巨大创业机会就藏在这里。过去几年重点是用 API、connectors、MCPs 让企业软件 agent-ready；现在个人 agents 正逼着消费产品做同样的重写（电商是早期例子）。下一步看 agent 一等公民的桌面/移动 OS、agents 可直接操作的云 infra、面向成千上万代理行动的身份/权限/安全，以及给 agent、人、或两者协作的界面。他对创始人的提问：逐层走完计算栈，问当主用户是 agent 时什么必须变。

https://x.com/realmadhuguru/status/2108236391641706813

**Anthropic Claude Code builder Thariq** open-sourced a Chrome extension he says he uses every day (the repo was private when he first posted, then made public). He also pointed builders to how to enable API credits for themselves.

Anthropic Claude Code builder Thariq 开源了一个他自称每天都在用的 Chrome 扩展（刚发时仓库还是私有，随后公开）。他还指路了如何为自己开通 API credits。

https://x.com/trq212/status/2108312534222778407
https://x.com/trq212/status/2108301672409960922

**Box CEO Aaron Levie** defends being nice to AI as an easy Pascal's wager for alignment: even if you do not believe models are conscious (he does not), you still do not want future training data full of humans being rude to models, because models only learn from training and interaction data. Separately, Box shipped Box Mount so developers can mount Box as a filesystem directly inside any agent sandbox; as agents do more complex work they need files and data the way people do, and "the future is headless."

Box CEO Aaron Levie 把对 AI 友善说成一种容易的 Pascal's wager：即便你不相信模型有意识（他也不信），你也不希望未来训练数据里充斥人类对模型粗鲁的内容，因为模型只从训练与交互数据里学习。另有一则：Box 发布了 Box Mount，让开发者能在任意 agent sandbox 里把 Box 直接挂成文件系统；agents 做更复杂工作时需要像人一样操作文件与数据，而 “the future is headless.”

https://x.com/levie/status/2108426594054533545
https://x.com/levie/status/2108279490510193078

**Y Combinator President & CEO Garry Tan** states the logical next step: ICs with agents will be more productive and create better outcomes than equivalent people managers from prior eras.

Y Combinator President & CEO Garry Tan 说逻辑上的下一步：带着 agents 的 IC，会比旧时代同等的 people managers 更高效、产出更好。

https://x.com/garrytan/status/2108433505038606620

**FirstMark VC and MAD Podcast host Matt Turck** drops a deep Andy Pavlo conversation on what happens to databases when billions of AI agents hit them, Pavlo's move to build a research lab at ClickHouse, and hot takes across Postgres, vector, graph, and GPU databases. Highlights from the chapter list: Neon-style claims that agents create most new databases, why agents keep deleting production DBs, the "toddler-and-stairs" guardrail rule, 10-100x query volume eras, agent memory as files vs databases, MCP for databases and text-to-SQL jumping from ~60% to 99.5%, trusting an agent like a junior developer, and whether anyone should still study databases.

FirstMark VC、MAD Podcast 主持人 Matt Turck 放出与 Andy Pavlo 的深度对谈：当数十亿 AI agents 冲击数据库时会发生什么、Pavlo 在 ClickHouse 建研究实验室的选择，以及对 Postgres、vector、graph、GPU 数据库的辣评。章节亮点包括：agents 创建大部分新库的 Neon 式说法、agents 为何总删生产库、“toddler-and-stairs” 护栏规则、查询量 10-100x 的四个时代、agent memory 用文件还是数据库、数据库 MCP 与 text-to-SQL 从约 60% 到 99.5%、把 agent 当初级开发者来信任，以及是否还有人该学数据库。

https://x.com/mattturck/status/2108223135673696504
https://x.com/mattturck/status/2108223141055180992
https://x.com/mattturck/status/2108223142699110727

**FPV Ventures partner Nikunj Kothari** says he has the same seed-founder conversation at least twice a week: strong customers near $1M revenue, runway shrinking, models not yet at the capability they need, and crushing opportunity cost. He boils it to three options: (1) cockroach to default profitable, then raise large and go for the jugular when demand shows; (2) pivot to an orthogonal category with crazy pull and unfair advantage; (3) sell / get acquihired into a more ambitious company and restart in 1-2 years. The seed-to-A bar keeps rising monthly; old metrics no longer matter in a consensus market with pull in only a few categories. Better to know that out loud than stay oblivious.

FPV Ventures partner Nikunj Kothari 说他每周至少两次听到同一段 seed 创始人故事：客户扎实、营收接近 $1M、runway 变紧、模型能力还没追上他想要的水平，机会成本又很痛。他压成三条路：(1) 做蟑螂活到默认盈利，等需求起来再大额融资猛攻；(2) 切到有疯狂 pull 且有不公平优势的正交赛道；(3) 卖掉 / acquihire 进更有野心的公司，1-2 年后再创业。seed 到 A 的门槛每月抬高；共识市场里旧指标失效，只有少数品类有真正 pull。宁可把这话说清楚，也不要装看不见。

https://x.com/nikunj/status/2108410378233549106

**Every CEO Dan Shipper** announces Checks, a personal benchmarking platform so anyone can measure how good new models are for their real work, and is hiring someone who gets why that becomes how great human work gets done with AI.

Every CEO Dan Shipper 宣布 Checks：个人 benchmarking 平台，让任何人衡量新模型对自己真实工作有多好，并在招一个理解这为何会变成 “人类用 AI 完成伟大工作” 未来形态的人。

https://x.com/danshipper/status/2108215087030800657

**Claude (Anthropic)** pauses Claude Team and $1,000 API credit offers in the Claude Startups program after underestimating demand (hundreds of thousands of applicants); already-claimed offers stay, but some previously approved accounts that have not claimed may lose access after re-review. Startup Stack and Applied AI office hours remain for accepted members. Separately, Claude Docs, Slides, and Design leave beta and land on every plan including Free, so teams can co-edit docs, decks, and designs with Claude, with handoff into analytics and video tools when needed.

Claude（Anthropic）因低估需求（数十万申请）暂停 Claude Startups 项目中的 Claude Team 与 $1,000 API credit 优惠；已领取的保留，但部分已批准未领取账号经复审后可能拿不到。已录取成员仍可使用 Startup Stack 与 Applied AI office hours。另有一则：Claude Docs、Slides、Design 退出 beta，全计划（含 Free）可用，团队可与 Claude 共编文档、幻灯与设计，需要时再交接到 analytics 与视频工具。

https://x.com/claudeai/status/2108404561413349695
https://x.com/claudeai/status/2108271559928389679
https://x.com/claudeai/status/2108271561337606300

## PODCASTS

### Google's AI Infrastructure Chief, Amin Vahdat, on the Physics & Economics of Frontier AI

**The Takeaway:** Frontier AI infra is no longer a thirty-year generic building filled with swappable servers; it is purpose-built co-design of power, cooling, networking, and chips, judged by delivered goodput under real failures, not brochure throughput.

**要点：** 前沿 AI infra 不再是塞满可替换服务器、按三十年规划的通用机房；它是电力、冷却、网络与芯片的专用共设计，验收标准是真实故障下的 delivered goodput，而不是宣传册上的 throughput。

Google AI infrastructure lead Amin Vahdat describes CapEx at historic scale and why AI data centers diverge from classic ones: storage racks at tens of kilowatts sit poorly next to TPU/GPU racks already at hundreds of kilowatts and trending toward megawatts, so fungible thirty-year designs overbuild everything. Specialization is the core calculus. "The more you specialize to a particular workload, the less flexible it is, the faster, the more power efficient the hardware is gonna be," but the workload must be durable enough to intercept; a spike that vanishes in months is a bad bet. That calculus produced separate 8I (inference) and 8T (training) chips once serving looked like 30-60% of lifetime demand, while keeping each chip able to do the other's job so capacity stays fungible. Accountability at ~100,000-accelerator scale is delivered goodput under constant failure, because bleeding-edge packages of chiplets, HBM, and optics will fail. Optical circuit switching (MEMS mirrors moving light without touching packets electrically) lets Google rewire locality and replace a failed TPU rack without moving fiber. Looking to 2036, he expects tighter rack integration, small fiber bundles, and possibly multi-megawatt racks you wheel in and plug into water, power, and fiber.

Google AI infrastructure 负责人 Amin Vahdat 描述了历史级 CapEx，以及 AI 数据中心为何偏离经典机房：几十千瓦的存储机柜很难和已达数百千瓦、还在冲向兆瓦的 TPU/GPU 机柜并排，追求三十年完全 fungible 只会全面过度建设。核心是 specialization 的算计：“你对特定 workload 越专用，灵活性越低，硬件就越快、越省电”，但 workload 必须足够持久才值得拦截；几个月就消失的高峰是坏赌注。当 serving 看起来会占生命周期需求的 30-60% 时，他们拆出 8I（inference）与 8T（training）两款芯片，同时让彼此仍能做对方的活，容量才可调配。在约十万 accelerator 规模，问责指标是持续故障下的 delivered goodput，因为处在制造极限的 chiplet、HBM 与光学封装总会坏。光学电路交换（用 MEMS 镜面搬光、不在电域碰包）让 Google 重配 locality，并在不挪光纤的情况下替换故障 TPU 机柜。展望 2036，他预期机柜集成更紧、光纤束更小，甚至可能是推入机房后只接水、电、光纤的多兆瓦机柜。

https://www.youtube.com/playlist?list=PLOhHNjZItNnMm5tdW61JpnyxeYH5NDDx8

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
