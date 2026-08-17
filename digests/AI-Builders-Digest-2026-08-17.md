AI Builders Digest — 2026-08-17

## X / TWITTER

**Codex & ChatGPT lead Thibault Sottiaux (OpenAI)** explains why $/M tokens is a bad comparison unit: an OpenAI token is not another model's token, so cheaper per-token pricing can still mean a higher bill for the same text. His pizza analogy: 8 slices at $2 ($16 total) vs 16 slices at $1.25 ($20 total). In one small check across English, technical, multilingual, and numerical text, GPT-5.6 Sol used about 766 tokens vs ~1,170 for Claude Opus 5 (~34.5% fewer). Even after tokenizer correction, what matters is price per successful outcome. He separately asks companies still on Opus instead of Sol: why, and what would make them switch?

Codex 与 ChatGPT 负责人 Thibault Sottiaux（OpenAI）解释为何用 $/M tokens 比价很糟：OpenAI 的 token 不等于别家模型的 token，所以单价更低仍可能对同一段文字花更多钱。披萨类比：8 片每片 $2（共 $16）vs 16 片每片 $1.25（共 $20）。他在一小段覆盖英文、技术、多语与数字文本的对比里，GPT-5.6 Sol 约用 766 tokens，Claude Opus 5 约 1,170（少约 34.5%）。校正 tokenizer 之后，真正重要的仍是「每次成功结果的价格」。他还追问仍在用 Opus 而不是 Sol 的公司：为什么，以及什么才能说服你们换？

https://x.com/thsottiaux/status/2088866513008873560
https://x.com/thsottiaux/status/2088850995430477882

**Replit CEO Amjad Masad** pushes back on "AI structurally centralizes power because it is compute hungry": 125 years of compute price-performance growth, plus algorithm and hardware gains, give no reason to assume AGI-level capability always needs a data center. Scaling laws are not laws of physics; they are empirical curves for particular architectures, objectives, and datasets. If the brain is a guide, true AGI is likely very efficient; today's scaling may be a bug that exposes how inefficient current ML recipes still are.

Replit CEO Amjad Masad 反驳「AI 因吃算力而结构性集中权力」：过去 125 年算力性价比超级指数增长，外加算法与硬件效率提升，没有理由假定 AGI 级能力永远离不开数据中心。Scaling laws 不是物理定律，只是特定架构、目标与数据上的经验曲线。若以人脑为参照，真正的 AGI 很可能非常高效；当下的 scaling 或许是 bug，暴露的是现有 ML 配方仍然低效。

https://x.com/amasad/status/2088867492907327573

**Vercel CEO Guillermo Rauch** argues much of React's success is actually shadcn. React described the geometry of the bricks (the spec); shadcn is what people wanted: reusable, high-quality, tunable components. It is a pseudo-library: there is code, but it is meant to be digested into your context window and remixed.

Vercel CEO Guillermo Rauch 认为 React 的成功很大一部分其实是 shadcn。React 描述的是积木几何（规格）；shadcn 才是人们真正想要的：可复用、高质量、可调的组件。它是伪库：有代码，但本意是被吞进 context window 再 remix。

https://x.com/rauchg/status/2088757738037989755

**Swyx (smol.ai / Cognition)** says outsiders often assume top-tier people live in permanent secret group chats; they mostly do not. Those chats exist as short-lived exceptions. What you see in major headlines is largely what they see too. His read: most effort is still on doing the work, not working the narrative or the gossip, which he finds reassuring.

Swyx（smol.ai / Cognition）说外行人常以为顶流人物都泡在永久秘密群聊里；其实大多不是。那种群存在，但多为短命例外。你在大标题里看到的，基本也是他们看到的。他的解读：大部分精力仍在做事，而不是经营叙事或八卦；这一点让他安心。

https://x.com/swyx/status/2088755688361378082

**Product educator Peter Yang** is a fan of Grok Bot but says X is the #1 differentiated data source it should access, and the connector / cloud-computer login path is broken for him. He agrees with Dario that using AI to cure disease (and speeding regulatory approval of AI healthcare breakthroughs) could bring 10x the human benefit of everything else combined. He also previews a Riley Brown episode on running a content business with Codex, including a thumbnail workflow: Codex finds 100 top-performing niche thumbnails into a Paper canvas, then mixes them with selfies until the frame lands.

产品教育者 Peter Yang 喜欢 Grok Bot，但认为 X 本该是它最该接入的差异化数据源，而 connector / 云电脑登录对他来说是坏的。他同意 Dario：用 AI 治病（并加速 AI 医疗突破的监管审批）可能带来比其他一切合计还高 10 倍的人类收益。他还预告 Riley Brown 用 Codex 跑内容生意的一集，重点是缩略图工作流：Codex 找出 niche 里 100 个高表现缩略图放进 Paper canvas，再和自拍混搭直到满意。

https://x.com/petergyang/status/2088773343629750535
https://x.com/petergyang/status/2088772605323214999
https://x.com/petergyang/status/2088626815166464507

**Linear Head of Product Nan Yu** restates a builder dream: sit in a park all day recording with friends, while a fleet of agents turns that content into actions and working software.

Linear 产品负责人 Nan Yu 重申一个 builder 梦想：整天坐在公园跟朋友录内容，同时有一队 agents 把这些内容变成行动与可运行软件。

https://x.com/thenanyu/status/2088810666958196988

**Meta Sr Director of AI Madhu Guru (ex-Google Gemini / Veo / Nano Banana)** says there is no longer an excuse for B2B software to ship poor UX: with AI, every product can and should be as easy as the best consumer software.

Meta AI 高级总监 Madhu Guru（前 Google Gemini / Veo / Nano Banana）说：B2B 软件再没有理由交出糟糕 UX。有了 AI，每个产品都可以、也应该做到像最好的消费级软件一样好用。

https://x.com/realmadhuguru/status/2088710566689018103

**Claude Code builder Thariq (Anthropic)** calls lossless watermarking unintuitive ("doesn't feel like it should work") and shared a Claude-made artifact explaining how it works.

Anthropic Claude Code builder Thariq 说「无损水印」有点反直觉（感觉不该成立），并分享了一个用 Claude 做的 artifact 来解释它如何工作。

https://x.com/trq212/status/2088721023223132213
https://x.com/trq212/status/2088721024825344289

**FPV Ventures partner Nikunj Kothari** recounts a stealth portfolio founder stuck one yard from critical contracts in a fragmented, bureaucratic market: terms lined up, one random summer clause blocking ambitious timelines. Nikunj's laugh line: do you know how long it would take anyone else to get this far, even with leverage? Short-term pain; long-term moat. Performative 996 pain is not the moat; entrenched software and hard-won relationships are.

FPV Ventures partner Nikunj Kothari 讲了一个 stealth portfolio 创始人：在高度碎片、纯官僚的市场里，关键合同卡在一码线，条款与 champion 都齐了，就差夏天里某条随机条款，可能拖垮激进时间表。Nikunj 笑问：你知道别人就算有杠杆，要多久才能走到这一步吗？短期痛苦，长期护城河。表演式 996 不是护城河；深嵌软件与好不容易攒下的关系才是。

https://x.com/nikunj/status/2088716743615352963

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
