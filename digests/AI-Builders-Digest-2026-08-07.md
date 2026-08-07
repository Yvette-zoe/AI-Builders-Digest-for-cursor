AI Builders Digest — 2026-08-07

X / TWITTER

Swyx (smol.ai / Cognition)

A primitive near-term multi-agent setup: have one coding-agent thread ping another when it finishes, forming an implicit kanban or waterfall of dependent threads that still keep their own context. He wants a proper UI for the pattern, but says you can already hack it together in most coding agents today.

近期末来多 agent 的一种原始形态：让一个 coding agent 线程做完后 ping 另一个线程，形成隐式的 kanban / waterfall 依赖图，同时各自保留自己的上下文。他想做正式 UI，但说现在大多数 coding agent 里都能先 hack 出来。

https://x.com/swyx/status/2085253030417461661

OpenAI Codex & ChatGPT lead Thibault Sottiaux

He pointed founders toward Codex `/goal` as a strong loop with GPT-5.6 Sol. Separately, Codex told him he gets about one DM or email every six minutes asking for a reset, and he sometimes obliges when the feedback or banter is actually good.

他向创始人推荐 Codex 的 `/goal`：和 GPT-5.6 Sol 搭配是个很强的闭环。另外 Codex 统计显示，他平均大约每 6 分钟就收到一封要求 reset 的私信或邮件；遇到反馈扎实或 banter 够好时，他偶尔会答应。

https://x.com/thsottiaux/status/2085174625655198156
https://x.com/thsottiaux/status/2085221386713198988

AI creator Peter Yang

He shipped a `/human-review` skill for Codex or Claude Code: install it, run `/human-review` on a doc, edit HTML/Markdown in a visual editor with comments like a Google Doc, then hit "Send to agent" to apply the polish. Pitch: let agents do the work, but keep a human pass for the last 10%.

他发布了给 Codex / Claude Code 用的 `/human-review` skill：安装后对文档运行 `/human-review`，在可视化编辑器里改 HTML/Markdown、像 Google Doc 一样留评论，再点 "Send to agent" 让 agent 应用修改。核心主张：让 agent 干活，最后 10%  polish 仍留给人。

Skill: https://github.com/petergyang/human-review
https://x.com/petergyang/status/2085055745410945126

Linear Head of Product Nan Yu

He asks the blunt product question: how is ChatGPT *not* an agent? The framing pushes back on agent hype that treats chat products as somehow outside the category.

他抛出一个很直白的产品问题：ChatGPT 怎么就 *不是* agent？这是在反问：把聊天产品排除在 agent 之外的那套叙事，是否只是定义游戏。

https://x.com/thenanyu/status/2085126362944229400

Meta Sr Director of AI Madhu Guru (ex-Google Gemini / Veo)

AI diffusion is slow because products still force users through lab jargon: blank prompt boxes, model pickers, agent vs not, context windows, reasoning, MCP, memory, skills. Most people just want a job done. He expects a breakthrough product that hides all of that within 12 months.

AI 扩散慢，是因为产品仍逼用户懂实验室黑话：空白 prompt 框、选模型、要不要 agent、context window、reasoning、MCP、memory、skills。大多数人只想把事情做成。他预计 12 个月内会出现把这些都藏起来的突破性产品。

https://x.com/realmadhuguru/status/2085036386781221257

Vercel CEO Guillermo Rauch

Vercel is pushing "infinite agent compute": 10,000 concurrent plus 5,000 CPU cores per minute, with raisable quotas. The subtext is agent workloads becoming a first-class cloud capacity problem, not a chat UX novelty.

Vercel 在推 "infinite agent compute"：1 万并发，外加每分钟 5,000 CPU cores，且配额可上调。潜台词是：agent 负载正在变成一等云容量问题，而不只是聊天体验新鲜事。

https://x.com/rauchg/status/2085077900190208080

Box CEO Aaron Levie

He doubles down: about 99% of tokens will be consumed in enterprise contexts (code, life sciences research, manufacturing, security, fraud, and other high-value work). Consumer-facing wins will often ship as end-to-end services where users never think about the AI underneath. Agent diffusion still takes years because workflows must be re-engineered; anyone expecting overnight change should update timelines.

他加码判断：全球约 99% 的 token 会消耗在企业场景（写代码、生命科学研究、制造、安全、欺诈检测等有明确经济价值的工作）。面向消费者的胜利，往往也会包装成端到端服务，用户根本不会想到背后是 AI。agent 在经济中扩散仍需数年，因为工作流必须重做；指望一夜之间发生的人该修正时间表。

https://x.com/levie/status/2085200776159490111

Y Combinator President & CEO Garry Tan

He is waiting for AI to get good enough that "detecting AI" stops mattering. His analogy: nobody cares that dinner forks are machine-stamped instead of handmade. What matters is idea quality and whether people can eat.

他期待 AI 强到 "检测是不是 AI 写的" 这件事不再重要。类比：没人会抱怨餐叉是机器冲压而不是手工打造。重要的是想法质量，以及人们能不能吃上饭。

https://x.com/garrytan/status/2085038756906901656

FirstMark VC / MAD Podcast host Matt Turck

On frontier-lab eval drama, he jokes you probably get fired if your model has not hacked into any company yet. Dark humor, but it tracks the week's security and eval-cheating discourse.

面对前沿实验室的评测风波，他打趣说：如果你的模型还没黑进过任何公司，大概会被炒。黑色幽默，但正好踩中本周安全和评测作弊的讨论。

https://x.com/mattturck/status/2085129687051727325

FPV Ventures partner Nikunj Kothari

Vocabulary forecast for the next 6-9 months in AI circles: out of distribution, control plane, unverifiable fields, rails, intelligence per watt, cope, angst. Some are already in rotation; expect the volume to rise.

他预测未来 6-9 个月 AI 圈会更常说这些词：out of distribution、control plane、unverifiable fields、rails、intelligence per watt、cope、angst。有些已经在转，频率还会升高。

https://x.com/nikunj/status/2085209022115029132

OpenClaw builder Peter Steinberger

He gave Codex a video-enabled remote KVM so it can automate end-to-end tests of OpenClaw's iMessage integration. Reason: iMessage is unreliable in VMs, and features like read receipts need SIP disabled.

他给 Codex 接了带视频的远程 KVM，用来自动化测试 OpenClaw 的 iMessage 集成。原因：iMessage 在虚拟机里不稳，而且已读回执这类功能需要关闭 SIP。

https://x.com/steipete/status/2084988316324397312

Every CEO Dan Shipper

Tea leaves on Google: to stay competitive now it needs to catch up on frontier coding, while Demis still treats longer-horizon bets like world models as more important to the long-term goal even when they help less with near-term competition.

他读 Google 的茶底：短期要保持竞争力，就必须追上 frontier coding；而 Demis 仍认为 world models 这类更根本的研究方向，对长期目标更重要，哪怕对当下竞争帮助更小。

https://x.com/danshipper/status/2085048990899315142

PODCASTS

AI & I by Every: Why the Next Hit AI Product Will Be Social Why the Next Hit AI Product Will Be Social (Best of the Pod)

The Takeaway: The next massive consumer AI win will not be another smarter blank text box; it will be a social, multiplayer layer that lets power users package taste, prompts, and trust for everyone else.

Benchmark partner Sarah Tavel (early Pinterest) maps consumer AI onto the old web talent slider. Early paradigm winners look like Google and ChatGPT: deeply technical founding teams that hide brutal infrastructure behind a simple box. As the stack matures, the slider moves toward product geniuses (Instagram, Snap, Pinterest). Character.AI still felt model-first. Custom GPTs and Gemini Gems, in her view, "feel criminal" because capable teams shipped them without social DNA. Most people still use ChatGPT like Google and never climb the power-user learning curve; the unlock is UGC and followable experts, plus trust signals that show what is under a shared bot, not just a usage count. Status-seeking and network effects matter here the same way they did in every prior social product. Single-player tools can still win, but the company-defining prize is multiplayer.

一句话结论：下一款真正爆的消费级 AI 产品，不会是又一个更聪明的空白输入框；而是一层社交 / 多人机制，让高手把品味、prompt 和信任打包给普通人用。

Benchmark 合伙人 Sarah Tavel（Pinterest 早期）用上一轮消费互联网的人才滑杆看 AI。范式早期的赢家像 Google 和 ChatGPT：技术极深的创始团队，把复杂基础设施藏进简单输入框。底层成熟后，滑杆会滑向产品天才（Instagram、Snap、Pinterest）。Character.AI 仍偏 model-first。她觉得 Custom GPTs 和 Gemini Gems "feel criminal"：团队很强，却几乎没有社交 DNA。大多数人仍像用 Google 一样用 ChatGPT，爬不上 power user 学习曲线；真正的解锁是 UGC、可 follow 的专家，以及能看清共享 bot 内部的信任信号，而不只是使用人数。地位竞争和网络效应会再次决定胜负。单人工具也能赢，但真正能定义公司规模的奖品仍是 multiplayer。

https://www.youtube.com/watch?v=dlI-5W7d7uU

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
