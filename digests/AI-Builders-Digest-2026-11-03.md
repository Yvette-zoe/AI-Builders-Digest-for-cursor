# AI Builders Digest — 2026-11-03

## X / TWITTER

**Andrej Karpathy** shipped HackerTube (https://hackertube.org/), a weekend hack that filters 43M Hacker News comments across 20 years down to 6,454 repeatedly recommended YouTube videos. Recs need no login (state stays in the browser session); thumbnails use a mid-video frame instead of upload-optimized covers; the comment-analysis zip is downloadable so you can point Claude at your own cut. He used Claude Code on Opus 5.5 medium effort, talking only to Claude except for a Google Cloud YouTube API key, spinning up a VPS, and buying the domain, then handing Claude the IP to update, harden, deploy, and optimize. His closer: many projects that used to take weeks or months can now be few-shotted for breakfast.

Andrej Karpathy 上线了 HackerTube（https://hackertube.org/）：一个周末 hack，把 20 年 Hacker News 上约 4300 万条评论筛成 6454 个被反复推荐的 YouTube 视频。推荐无需登录（状态留在浏览器 session）；缩略图取视频中段帧，而不是上传者超优化封面；评论分析 zip 可下载，方便你自己让 Claude 做版本。他默认用 Claude Code + Opus 5.5 medium effort，几乎只跟 Claude 对话，人工只做三件事：Google Cloud 里拿 YouTube API key、开 VPS、买域名，然后把 IP 交给 Claude 去更新、加固、部署与优化。结尾判断：许多以前要花数周甚至数月的项目，现在早餐前就能 few-shot 出来。

https://x.com/karpathy/status/2116957135661945283

**Box CEO Aaron Levie** argues the job description for many roles is flipping: from agents helping humans work a bit faster, to humans helping agents do their work. People in information-heavy jobs (coding, cybersecurity, legal, biotech, engineering) become managers of agent teams rather than ICs with a little AI leverage. Parallel agents decouple output from hours worked; organizations that orient around that earlier will compound.

Box CEO Aaron Levie 认为很多岗位的 JD 正在翻转：从 agent 帮人把活做得稍快一点，变成人类帮 agent 把活干完。信息密集型工作（coding、网络安全、法律、biotech、工程等）里的人，会变成 agent 团队的 manager，而不再是只多了一点 AI 杠杆的个人贡献者。并行 agent 让产出与工时脱钩；更早按这个逻辑重组运营的组织会看到 compounding 收益。

https://x.com/levie/status/2117134917847093491

**Vercel CEO Guillermo Rauch** says own your intelligence: anyone opposing that usually has something to sell you, possibly your own intelligence back. Local models should keep proliferating; absolute-unit frontier models may stay out of local reach for now, so keep options open and own your harness, data, connections, runtime, and agents, while embracing open source. Separately he reports Gemini on fx.sh (https://fx.sh/) doing well on two high-complexity projects.

Vercel CEO Guillermo Rauch 主张 own your intelligence：反对这一点的人通常有东西要卖给你，说不定卖的就是你自己的智能。本地模型应继续扩散；「绝对 bulk」级大模型短期内可能仍难本地跑，所以要保持选项开放，并拥有自己的 harness、数据、连接、runtime 与 agents，同时拥抱开源。另外他反馈在 fx.sh（https://fx.sh/）上用 Gemini 跑两个高复杂度项目，表现很好。

https://x.com/rauchg/status/2117000819623243925
https://x.com/rauchg/status/2116988333096370443

**Replit CEO Amjad Masad** highlights a one-toggle Replit feedback widget: user feedback on your site becomes prompts for agents to build against. He also warns that if you are enjoying a subsidized AI subscription, get ready to get rug pulled.

Replit CEO Amjad Masad 强调 Replit 上一个开关即可启用的 feedback widget：站点用户反馈会直接变成 agent 的构建 prompt。他也警告：如果你正在享用被补贴的 AI 订阅，做好被 rug pull 的准备。

https://x.com/amasad/status/2116998155925360965
https://x.com/amasad/status/2117010858845089805

**Y Combinator President & CEO Garry Tan** points to Particle-1 as matching much larger models on agentic retrieval at about 1/23 the price, citing a gbrain LongMemEval finding (https://github.com/garrytan/gbrain-evals/blob/b392700f2f647c201a8bedca71d43fd6a7fbb31c/docs/findings/2026-11-01-particle-1-longmemeval-w10b.md) where particle-1 sat ~3.4 points behind Opus 5.5 at roughly a twenty-third the list cost per correct answer.

Y Combinator President & CEO Garry Tan 指出 Particle-1 在 agentic retrieval 上能打更大模型，价格大约只有 1/23，并指向 gbrain LongMemEval 发现（https://github.com/garrytan/gbrain-evals/blob/b392700f2f647c201a8bedca71d43fd6a7fbb31c/docs/findings/2026-11-01-particle-1-longmemeval-w10b.md）：particle-1 准确率大约落后 Opus 5.5 约 3.4 分，但按 list price 每个正确答案成本约为其二十三分之一。

https://x.com/garrytan/status/2117137390016073977

**Creator / interviewer Peter Yang** says he wishes one AI tool covered everything, but today clear winners differ by job: browser/computer use goes to ChatGPT + Codex, design/video editing/"taste" to Claude, and 24/7 agents plus scheduled jobs to Grok Bot, with Gemini still underrated for writing. Separately he highlights Google Labs product director Jacalu Lu on when a product still needs a human in the UI: create and learn, yes; pure consume/entertain, often still the user; but many products he would happily stop being the main person at the interface.

Creator / interviewer Peter Yang 说他希望一个 AI 工具打天下，但眼下各赛道赢家很清楚：浏览器/computer use 是 ChatGPT + Codex，设计/视频剪辑/"taste" 是 Claude，7×24 agent 与定时任务是 Grok Bot，Gemini 写东西仍被低估。另外他引用 Google Labs product director Jacalu Lu 的问题：你为什么要让人待在产品里？需要创建与学习时，人仍有理由交互；纯消费/娱乐时用户往往仍是本人；但很多今天的产品，他其实很乐意不再当界面上的主交互者。

https://x.com/petergyang/status/2116946320674152810
https://x.com/petergyang/status/2116987415319740756

## PODCASTS

### Ep 95: Modal CEO on the Future of Inference, the Chaos of the GPU Market & Origins of the Sandbox Bet - Modal founder and CEO Eric (Unsupervised Learning / Redpoint)

**The Takeaway:** Modal's edge is aggregating messy GPU supply across ~25 clouds and owning hard infra (custom filesystem, container runtime, scheduler, CPU/GPU snapshots, RDMA), while sandboxes that started as an isolation bet for LLM-generated code are now roughly a third of revenue at a ~$300M run rate.

**The Takeaway：** Modal 的壁垒是把约 25 家云上混乱的 GPU 供给聚合起来，并自研重型基础设施（自定义文件系统、container runtime、调度器、CPU/GPU snapshot、RDMA）；而最初为隔离运行 LLM 生成代码押注的 sandbox，如今约占收入三分之一、约 $300M run rate。

On Redpoint's Unsupervised Learning, Modal founder and CEO Eric describes GPU procurement as still far from an efficient market: late-night WhatsApp groups, hotel-lobby number swaps, and GTC as "an open air drug market, but, like, GPUs." Compute is not a fungible exchange contract (cluster shape, chips, location, reliability all differ), so Modal does multiple capacity deals a week, absorbs neo-cloud failures by pulling capacity out of rotation, and tells customers not to think about whose GPUs are underneath.

在 Redpoint 的 Unsupervised Learning 上，Modal founder and CEO Eric 把 GPU 采购形容为仍远离有效市场：深夜 WhatsApp 群、酒店大堂互换联系方式，以及 GTC 像 "an open air drug market, but, like, GPUs." Compute 不是可上交易所买卖的 fungible 合约（集群形态、芯片、区位、可靠性都不同），所以 Modal 几乎每周做多笔容量交易，neo-cloud 出故障时直接移出轮转，并对客户说不必操心底下是谁的 GPU。

The sandbox origin story is early: after seeing people mess with LMs generating code, Modal shipped sandboxes in 2023 on infra already built for fast, isolated execution. It was not overnight; around 2025, when models got much better at writing code, sandboxes "grew, like, I don't know, a thousand x" and became a multi-product wedge alongside a newer training product. Alpha, in his framing, comes from "not being afraid to do hard things": own filesystem for fast container images, own container runtime and scheduler, almost no Kubernetes/Docker, gVisor for isolation, plus snapshotting and peer-to-peer RDMA so large models can fire up in seconds.

Sandbox 的起源很早：看到有人拿 LM 生成代码后，Modal 在 2023 年用已有的快速隔离执行基础设施上线了 sandbox。并非一夜爆红；大约 2025 年模型写代码变强后，sandbox「大概涨了上千倍」，并成为多产品楔子，后来又加上 training 产品。用他的话说，alpha 来自 "not being afraid to do hard things"：自研文件系统做快速 container image、自研 runtime 与调度器、几乎不用 Kubernetes/Docker、用 gVisor 做隔离，再加上 snapshot 与节点间 RDMA，让大模型也能在数秒内拉起。

Inference remains an empirical science (disaggregated prefill/decode, KV cache complexity, kernels, MoE, quantization), with a 20–30 person team living in papers and kernels because model paradigms can change overnight. Internally, "95% of the lines of code that gets merged as Modal is probably written by agents to some extent," yet infra still needs senior humans for reliability tail risk; adoption surprised him by skewing to seniors who treat agents like "10 interns" and can hand over a brutal test suite. On the broader market he calls neo-clouds fine but capital-inefficient financing vehicles with high leverage, and expects GPU prices to rise over the next twelve months because the biggest buyers still have little incentive to slow capacity acquisition.

Inference 仍是一门经验科学（disaggregated prefill/decode、KV cache 复杂度、kernel、MoE、量化），一支 20–30 人的团队泡在论文与 kernel 里，因为模型范式可能一夜改写。内部上，「Modal merge 进去的代码大概有 95% 在某种程度上是 agent 写的」，但基础设施的可靠性尾部风险仍需资深人类盯着；采用曲线出乎意料地偏向资深工程师：对他们来说 agent 像「10 个实习生」，可以丢一套残酷的测试套件。对更大市场，他认为 neo-cloud 商业模式没问题，但本质是资本效率低、高杠杆的融资/租赁载体，并预期未来 12 个月 GPU 价格会上涨，因为最大买家几乎没有放慢买容量的动机。

https://www.youtube.com/@RedpointAI

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
