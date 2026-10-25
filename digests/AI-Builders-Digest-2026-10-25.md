# AI Builders Digest — 2026-10-25

## X / TWITTER

**OpenAI Codex & ChatGPT builder Thibault Sottiaux** marks Day 19 with faster Dots call connect, mid-conversation reasoning or work changes that no longer invalidate the Codex cache, and a Codex CLI update. On the CLI: reusable prompt presets, inline model and permission settings, enterprise MCP sign-in, fixes for resuming long sessions, and Windows corporate-proxy authentication. He notes the CLI has grown about 2X in usage since DevDay. Separately he warns that the line between having a tool and being a tool is easy to cross: do not build yourself into being a tool.

OpenAI Codex & ChatGPT builder Thibault Sottiaux 在 Day 19 宣布：Dots 通话接通更快；对话中途改 reasoning 或继续工作不再让 Codex cache 失效；Codex CLI 也有更新。CLI 侧包括可复用的 prompt presets、内联 model 与 permission 设置、enterprise MCP 登录、长会话 resume 修复，以及 Windows 企业代理认证。他还提到自 DevDay 以来 CLI 用量大约涨了 2 倍。另外他提醒：拥有工具与沦为工具之间的界线很细，别把自己做成工具。

https://x.com/thsottiaux/status/2113770573994299544
https://x.com/thsottiaux/status/2113770862860222611
https://x.com/thsottiaux/status/2113838156193894447

**Anthropic Claude Code builder Thariq** says he has left Anthropic after more than a year on Claude Code, which scaled larger than he imagined. He still believes in Anthropic's mission and a "race to the top": work hard and responsibly, raise the bar, and push others toward better outcomes. He praises colleagues as the most talented and earnest people he has worked with, thanks the X community, and plans a short break before something new. For more Claude Code content he points people to Addy Osmani, Lydia Hallie, Cat Wu, ClaudeDevs, and Boris Cherny.

Anthropic Claude Code builder Thariq 表示，在 Claude Code 工作一年多、看着它规模远超想象之后，他已离开 Anthropic。他仍相信 Anthropic 的使命与「race to the top」：认真负责地做事、抬高标准，并推动彼此做出更好结果。他称同事是他遇过最有才华、最认真的人，感谢 X 社区，并计划先短暂休息再投入新事。若还想跟 Claude Code 内容，他推荐关注 Addy Osmani、Lydia Hallie、Cat Wu、ClaudeDevs，以及开创这一切的 Boris Cherny。

https://x.com/trq212/status/2113844051938054167

**Replit CEO Amjad Masad** welcomes Jeff and the Chroma team to Replit, calling them early AI pioneers who were building RAG before it had a name. At Replit they will tackle agent context and memory so agents can do real work, which he frames as a step toward the self-driving company. Separately he announces Replit for Government and welcomes Michael Greenwald, formerly of AWS public sector, to help governments build and operate software.

Replit CEO Amjad Masad 欢迎 Jeff 与 Chroma 团队加入 Replit，称他们是在 RAG 成名前就开始做的 AI 先驱。在 Replit，他们将解决 agent 所需的 context 与 memory，让 agent 能做真实工作，并视之为迈向 self-driving company 的重要一步。另外他宣布 Replit for Government，并请来曾负责 AWS 公共部门业务的 Michael Greenwald，一起改变政府构建与运营软件的方式。

https://x.com/amasad/status/2113736007111827606
https://x.com/amasad/status/2113676717105787192

**Vercel CEO Guillermo Rauch** explains a class of shared-host VM timing attacks known since at least 2015, with no complete fix. Agents raise the stakes: if two agents share a machine, one can make enough CPU-cache "noise" that the other detects it by timing its own computation (a noisy-neighbor attack). The only complete solution would be dedicated hardware per agent, with clear economic cost. For Vercel Sandbox he says they deployed every practical mitigation plus always-on monitoring and red-teaming, similar to where OpenAI landed on a related find.

Vercel CEO Guillermo Rauch 解释一类至少自 2015 年起就已知的共享主机 VM timing 攻击，至今没有彻底解法。Agent 抬高了风险：若两台 agent 同机，一方可通过 CPU cache「制造噪声」，另一方用自身计算与 cache 访问的耗时即可察觉（noisy-neighbor 攻击）。唯一完整方案是每台 agent 独占硬件，但经济代价明显。对 Vercel Sandbox，他说已部署所有可行缓解，并配合持续监控与 red-teaming，方向与 OpenAI 对此类发现的落地类似。

https://x.com/rauchg/status/2113759533801877920

**Box CEO Aaron Levie** says agent swarms for cyber defense are about to become one of the biggest AI categories: agents reviewing code and infra, testing every risk permutation, and processing huge data volumes. Security fits swarms because more compute clearly maps to more value, covering testing humans never finish fast enough.

Box CEO Aaron Levie 认为，用于网络防御的 agent swarms 即将成为 AI 最大品类之一：agent 审查代码与基础设施、穷举风险组合，并处理海量数据。安全很适合 swarms，因为算力投入与产出价值的对应关系清晰，能覆盖人类永远赶不及测完的范围。

https://x.com/levie/status/2113738768645808277

**Every CEO Dan Shipper** argues the best AI team configuration is only two kinds of people: pirates and architects.

Every CEO Dan Shipper 认为，AI 团队的最佳配置其实只有两类人：pirates 与 architects。

https://x.com/danshipper/status/2113693510629281895

**SPC General Partner Aditya Agarwal** notes that some of the biggest AI advances came from solving many problems together instead of training specialized systems for each task. He cites Physical Intelligence's Sergey Levine applying the same idea to robotics: make the problem bigger.

SPC General Partner Aditya Agarwal 指出，AI 一些最大的进展来自「一起解决很多问题」，而不是为每个任务训练专用系统。他引用 Physical Intelligence 的 Sergey Levine，把同一原则用到机器人上：把问题做得更大。

https://x.com/adityaag/status/2113666947766169868

**Claude (Anthropic)** points to a deeper look at how Claude Duet handles safety, privacy, and security.

Claude（Anthropic）给出一篇更深入的说明，介绍 Claude Duet 如何处理 safety、privacy 与 security。

https://x.com/claudeai/status/2113736176737845353

## PODCASTS

**No Priors: Democratizing Security for the Agentic Web with Cloudflare CTO Dane Knecht**

**The Takeaway:** AI is driving a temporary "vuln apocalypse," but the same models and harnesses that find bugs at weekly Log4j-scale frequency can also harden software and rebuild internet economics for agents, if defenders democratize protection the way Cloudflare did for CDN and WAF.

**要点：** AI 正在制造一段暂时的「漏洞末日」，但以接近每周一次 Log4j 量级挖洞的同一批模型与 harness，也能反过来加固软件，并为 agent 重建互联网经济；前提是防守方像 Cloudflare 对 CDN / WAF 那样，把防护平民化。

Cloudflare CTO Dane Knecht says priorities keep shifting, but the arc is clear: after a year of getting everyone onto AI, security stopped being an afterthought. Vulnerabilities that used to arrive about once a year now show up weekly; he expects much of engineering time over the next eighteen months to go to security, then ease once AI has surveyed most code. Attackers are not only nation-states: high-school "agent kitties" point agents at CTF-style targets and collect bug bounties. He rejects permanent air-gap doom, pointing to industry partnership in crises and the shift from castle-and-moat to zero trust. On building securely, start by shrinking attack surface; today's verbose models add complexity, so human judgment and written principles still matter. Cloudflare encodes practices in a "Codex" of RFCs and commandments that agents must follow in review, with adversarial security and performance runs deeper in the factory.

Cloudflare CTO Dane Knecht 说优先级不断在变，但主线清楚：花了一年让所有人用上 AI 之后，安全不再是事后补丁。过去大约一年一次的严重漏洞，现在几乎每周出现；他预计未来十八个月大量工程时间会砸在安全上，等 AI 把多数代码扫过一轮后再回落。攻击者也不只是民族国家：高中生「agent kitties」把 agent 对准 CTF 式目标并拿 bug bounty。他不认同永久物理隔离的末日论，强调危机时的行业协作，以及从「城堡护城河」转向 zero trust。安全构建上，先缩小攻击面；当下啰嗦的模型爱加复杂度，因此人的判断与成文原则仍关键。Cloudflare 把实践写进由 RFC 汇成的「Codex」与十条戒律，让 agent 在评审中遵守，并在产线更深处做对抗性安全与性能审查。

On the agentic web, humans and agents currently share the same rails. Agents want everything APIs never covered, so sites need agent-native delivery, lower crawl cost, and payment. Knecht sketches micropayments where an agent decides whether a page is worth a content site's CPM, enabled by new rails (Cloudflare's monetization gateway and agent wallets, Stripe's x402 / HTTP 402). Cloudflare also works with OpenAI on Signals so agents discover fresh content without constant full-site crawls. Internally, Cloudflare OS is a secure employee AI platform and reference architecture on Cloudflare's developer stack; go-to-market and G&A use it heavily. After an AI-first reorg, a three-team email campaign collapsed into one PM tool with manager approval. Token policy focuses on shipped output, not leaderboards, with spend notices escalating to managers. They hired about 1,000 interns over a year at a ~5,000-person company to import AI-native habits. Memorable line: "While AI has become the tool that's causing this kind of security apocalypse... it is also the tool that can help us solve it faster as well."

在 agentic web 上，人类与 agent 目前仍挤在同一套轨道。Agent 渴求 API 从未覆盖的信息，因此站点需要面向 agent 的内容分发、更低爬取成本，以及付费机制。Knecht 勾勒微支付场景：agent 自行判断一页内容是否值该站的 CPM，并依赖新支付轨道（Cloudflare 的内容变现网关与 agent 钱包，以及 Stripe 的 x402 / HTTP 402）。Cloudflare 还与 OpenAI 合作 Signals，让 agent 发现新内容而不必反复全站爬取。对内，Cloudflare OS 是安全的员工 AI 平台，也是建在 Cloudflare 开发者栈上的参考架构；Go-to-market 与 G&A 用得很多。AI-first 重组后，原先跨三个团队的邮件活动收成「产品经理写稿 + 经理一键批准」的单一工具。Token 政策看交付产出而非排行榜，超额消费会逐级通知到经理。约 5,000 人的公司一年招约 1,000 名实习生，用来注入 AI-native 习惯。金句：「AI 成了制造安全末日的工具……它也同样是能帮我们更快解决的工具。」

https://www.youtube.com/@NoPriorsPodcast

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
