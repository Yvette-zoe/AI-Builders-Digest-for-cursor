# AI Builders Digest — 2026-09-13

## X / TWITTER

**OpenAI Codex & ChatGPT lead Thibault Sottiaux** says Astra-powered ships this week include Images 2.5, GPT-Live-1, Agents API, Data Agent, and ChatGPT for Financial Services, with more planned before DevDay. Separately he posts a quality reset for Astra users: skills for older models were triggering too often or blocking work checks; an opt-in context-management experiment that could early-stop or reply to older messages was disabled (roughly 4-5k users affected); and some badly configured engines that degraded a long tail of traffic were removed. He says follow-through, latest-message tracking, and mid-run work checks should feel better, with another reset landing by midnight. He also welcomes Aidan and Sasha from the Git AI team to OpenAI to keep their open-source tool (showing how coding agents contribute to a codebase) open source while making Codex impact easier to see for individuals and teams.

OpenAI Codex & ChatGPT lead Thibault Sottiaux 说本周 Astra 驱动的上线包括 Images 2.5、GPT-Live-1、Agents API、Data Agent 与 ChatGPT for Financial Services，DevDay 前还有更多计划。另外他给 Astra 用户发了质量修复与 reset：旧模型写的 skills 触发过频或妨碍模型自检；一个可选的 context management 实验会导致过早停或回复旧消息，已关闭（粗估影响约 4-5k 用户）；一些配置不良、拖累长尾流量质量的 engines 也已移除。他说 follow-through、跟踪最新消息、以及执行中对工作的检查会明显更好，午夜前还有一次 reset。他还欢迎 Git AI 团队的 Aidan 与 Sasha 加入 OpenAI，继续开源其展示 coding agents 如何贡献代码库的工具，并让个人与团队更容易看到 Codex 的影响。

https://x.com/thsottiaux/status/2098639827084480864
https://x.com/thsottiaux/status/2098612714704891959
https://x.com/thsottiaux/status/2098569976143806918

**AI product creator Peter Yang** is skeptical of "software factories": outside verification and testing, he does not think AI can yet self-improve a product or build a new feature end-to-end without a human in the loop, because one wrong overnight assumption wastes the whole token run. He asks for concrete products or features built end-to-end with no human defining requirements or checking the work. Separately he splits workflows cleanly: all local scheduled tasks live in Codex, and all cloud tasks he is porting to Grok Bot.

AI product creator Peter Yang 对 “software factories” 持怀疑：除 verification 与 testing 外，他认为 AI 还到不了无人在环就能自我改进产品或端到端做新功能的程度，因为过夜跑一轮只要一个错误假设整串 token 就废了。他反问有没有真正端到端、无人定需求也无人验收就做出来的产品或功能。另外他把工作流切干净：本地定时任务全放 Codex，云端任务则迁到 Grok Bot。

https://x.com/petergyang/status/2098565668241334366
https://x.com/petergyang/status/2098614492066435228

**Meta Sr Director of AI Madhu Guru** (ex-Google Gemini/Veo) explains why most enterprise AI efforts fail: CEOs staff a central AI team with trusted lieutenants using 15-year incremental product playbooks that do not fit AI's need for experimentation and invention; companies under-invest in evals; and central "platform" teams build tools disconnected from real workflows, getting begrudging adoption without productivity. His fix: hire leaders who have actually shipped AI products, make evals first-class, and embed the best AI builders inside finance, sales, and support to build with those functions.

Meta Sr Director of AI Madhu Guru（前 Google Gemini/Veo）拆企业 AI 为何大多失败：CEO 用亲信搭中央 AI 团队，沿用过去 15 年增量产品 playbook，对不上 AI 需要的实验与发明；对 evals 投入不足；中央 “平台” 团队做与真实工作流脱节的工具，只有勉强采用、没有生产力。他的解法：招真正做过 AI 产品的领导者，把 evals 当一等公民，并把最强 AI builder 嵌进 finance、sales、support，跟业务一起建。

https://x.com/realmadhuguru/status/2098448235048378456

**Anthropic Claude Code Thariq** ships plugin evals so you can tell whether skills still work after new model releases (`claude plugin eval init` in your plugin folder). He also argues pass/fail scores alone are nearly useless now: many benchmark failures come from overly strict hidden tests, and sometimes the model's answer makes more sense than the expected eval result.

Anthropic Claude Code Thariq 上线 plugin evals，方便在新模型发布后判断 skills 是否还有效（在 plugin 目录跑 `claude plugin eval init`）。他还认为如今只看 pass/fail 分数几乎没法解读：很多基准失败来自过严的隐藏测试，有时模型的答案比预期 eval 结果更合理。

https://x.com/trq212/status/2098531560643539440
https://x.com/trq212/status/2098490139798655427

**Replit CEO Amjad Masad** announces Replit acquired a business entirely built on Replit and expects more of that pattern; he also highlights Routines with budgets as a product update.

Replit CEO Amjad Masad 宣布 Replit 收购了一家完全建在 Replit 上的公司，并预期这类案例会更多；他还展示了带 budgets 的 Routines 产品更新。

https://x.com/amasad/status/2098548464452055437
https://x.com/amasad/status/2098317466682179643

**Vercel CEO Guillermo Rauch** says Tailscale's model router runs on Vercel AI Gateway, framing AI Gateways as the new CDNs: going direct to origin is brittle, DIY is painful and costly.

Vercel CEO Guillermo Rauch 说 Tailscale 的 model router 底层跑在 Vercel AI Gateway 上，并把 AI Gateway 类比为新 CDN：直连 origin 脆弱，自己做又痛又贵。

https://x.com/rauchg/status/2098531157230969062

**Box CEO Aaron Levie** highlights mounting Box into agent sandboxes so agents can read and write files on the agent's computer, arguing enterprise agents running critical workflows will need the same primitives people have long had.

Box CEO Aaron Levie 强调可以把 Box 挂载进 agent sandbox，让 agent 在自己的计算机上读写文件；他认为企业里跑关键工作流的 agent 会需要人们早就有的同类原语。

https://x.com/levie/status/2098478938003841123

**Cursor designer Ryo Lu** (ex-Notion/Stripe) points to long-lived agents for big ideas, now in Cursor.

Cursor designer Ryo Lu（前 Notion/Stripe）提到面向大想法的 long-lived agents 现已进入 Cursor。

https://x.com/ryolu_/status/2098324260867772806

**Builder Zara Zhang** argues the "one-person company" idea is overrated: AI lets one person do more, but building something new is lonely, and motivation collapses without someone to brainstorm, suffer, and celebrate with.

Builder Zara Zhang 认为 “一人公司” 被高估了：AI 让一个人能干更多，但做新东西很孤独；没有人一起 brainstorm、一起受苦、一起庆祝，动力极易崩掉。

https://x.com/zarazhangrui/status/2098483800456179923

**FPV Ventures partner Nikunj Kothari** revisits “Success has many fathers, but failure is an orphan” after watching successful VCs fight for attribution on hot deals, noting large exits and markups are rare and fund the next raise. He expects names to be scrubbed or omitted as people rewrite history, and tells emerging GPs to hold founders close as the real reference checks.

FPV Ventures partner Nikunj Kothari 重提 “Success has many fathers, but failure is an orphan”：他看到成功 VC 为热门项目抢 attribution，因为真正大的 exit/markup 稀缺，且决定下一轮能否募到。他预计接下来几年会有名字被 scrub 或省略、大家改写历史；并建议 emerging GP 把 founder 关系捂紧，那才是真正的 reference check。

https://x.com/nikunj/status/2098550718923997430

**OpenClaw builder Peter Steinberger** demos Astra on OpenClaw in a cloud session playing Doom with CUA: not quite AGI yet, but probably beats a fly brain. He also submitted a Linux key-reliability patch to the CUA framework and calls the framework dope overall.

OpenClaw builder Peter Steinberger 演示 Astra 在 OpenClaw 云 session 里用 CUA 玩 Doom：还不算 AGI，但大概超过苍蝇脑。他还给 CUA 框架提了 Linux 下按键可靠性补丁，并称整体框架很强。

https://x.com/steipete/status/2098527519213604889
https://x.com/steipete/status/2098527982709256637

**Every CEO Dan Shipper** says better benchmark scores do not tell you much about real work, which is why Every has done long-form vibe checks for three years. The team is now doubling down with an internal platform for personal benchmarks grounded in day-to-day work, making those checks more quantitative.

Every CEO Dan Shipper 说更高的 benchmark 分数说明不了模型在你真实工作上的表现，所以 Every 三年来一直做基于真实工作的长文 vibe check。团队现在加码：内部平台让大家按日常工作做 personal benchmarks，把 vibe check 做得更定量。

https://x.com/danshipper/status/2098481799047647715

## PODCASTS

### No Priors: Coinbase’s Everything Exchange: Agentic Finance, Stablecoins, and Tokenization with CEO Brian Armstrong

**The Takeaway:** Card rails break on sub-dollar agent commerce (about 76% of agent ecommerce transactions Coinbase sees are under 30¢), so Coinbase CEO Brian Armstrong wants agents banked on crypto rails with their own accounts, while Coinbase itself pushes toward recursive self-improvement via a repo/team "brain" and multi-agent harness.

**要点：** 借记/信用卡底价约 30¢，对不足 1 美元的 agent 电商几乎不可用（Coinbase 看到约 76% 的 agent ecommerce 交易低于 30¢），因此 Coinbase CEO Brian Armstrong 要用加密轨道给 agent 开户 “bank the AIs”；同时 Coinbase 内部用仓库/团队 “brain” 与多 agent harness 逼近 recursive self-improvement。

Coinbase cofounder and CEO Brian Armstrong, on No Priors with Elad Gil and Sarah Guo, frames three company bets: an Everything Exchange where stocks, commodities, crypto, derivatives, perps, and prediction markets trade in one place; stablecoin payments that keep growing even when Bitcoin is down ("send money at the speed of information"); and Agentic Finance / AIFi, from an in-app AI advisor for portfolios and tax-loss harvesting to tools that give agents their own financial accounts. "We don't want the AIs to be unbanked." Agents lack government IDs and cannot walk into a bank branch, so Coinbase offers self-custodial wallets over crypto rails (no KYC), plus upcoming segregated agentic accounts linked to a human identity. Agents get stuck on paywalls and credit-card forms; spend accounts and protocols like X402 (incubated at Coinbase, now in the Linux Foundation with Google, Cloudflare, AWS and others) are meant to clear that, with stats at edgentic.market and Coinbase Business accepting stablecoin payments from humans and agents alike.

Coinbase 联合创始人兼 CEO Brian Armstrong 在 No Priors 上与 Elad Gil、Sarah Guo 对谈，给出三条主线：Everything Exchange（股票、商品、crypto、衍生品、永续与 prediction markets 一处交易）；即便 BTC 下跌仍在猛涨的 stablecoin 支付（“以信息的速度汇款”）；以及 Agentic Finance / AIFi：从 App 内 AI advisor（组合配置、tax-loss harvesting 等）到给 agent 开金融账户的工具。“We don't want the AIs to be unbanked.” Agent 没有政府证件、走不进银行，所以提供无 KYC 的自托管钱包，以及即将推出的、挂在人类身份下的隔离 agentic 账户。Agent 常卡在付费墙与填信用卡；spend account 与 X402 等协议（Coinbase 孵化、已进 Linux Foundation，Google、Cloudflare、AWS 等参与）要打通这层，edgentic.market 可看流量，Coinbase Business 则让公司同时收人和 agent 的 stablecoin 付款。

Internally, after coding tools, data hooks, fraud ML, and support AI, Coinbase is chasing recursive self-improvement: a "brain" per team, service repo, or individual (policies so people can take their personal brain when they leave) that agents ingest before changing a service (incidents, financial controls, A/B tests, accepted/rejected PRs). When a human corrects an agent, that context must go back into the brain so one-shot PR accept rates rise over time. Their harness, Toshi, can call external vendors and pay over X402. Armstrong describes asking an expensive model to plan a feature in three phases of ten pieces, then spin up ten parallel agents (mix of open-source and Grok); minutes before the pod, phase one came back ready for review. Instead of Slack-pinging the team all day, he tags an agent or drops work into the harness and sends a PR: "That's a magical moment... It's very addictive."

内部方面，在 coding 工具、数据接入、风控 ML 与客服 AI 之后，Coinbase 在追 recursive self-improvement：按团队、服务仓库或个人建 “brain”（个人 brain 离职可带走），agent 改服务前先吞掉 incidents、财务控制、A/B 测试与 PR 接受/拒绝史。人修正 agent 时，上下文必须写回 brain，让 one-shot PR 接受率随时间上升。他们的 harness 叫 Toshi，可调外部供应商并用 X402 付款。Armstrong 描述让高价模型把功能拆成三阶段、每阶段十块，再并行拉起十个 agent（开源与 Grok 混用）；上播客前两分钟，phase one 已齐备待审。他不再整天在 Slack 催团队，而是 tag agent 或丢进 harness，直接发 PR：“That's a magical moment... It's very addictive.”

On markets, he ties tokenization to access: stablecoins mapped 1:1 to bank cash or Treasuries first; now tokenized stocks that are real securities in custody, not synthetics, for roughly four billion people without a US brokerage. The same rails should extend to private credit, Treasuries, and deposits, all tradeable on the Everything Exchange and sendable like a WhatsApp message. He is also cofounder of longevity company New Limit, but stresses Coinbase is the full-time job and distraction across too many companies early is dangerous.

市场侧他把 tokenization 绑在可及性上：stablecoin 先把 1 美元映射到银行存款或国债；现在是托管实货、非合成的 tokenized stocks，面向大约 40 亿没有美国券商账户的人。同一轨道还会延伸到 private credit、国债与存款，都可在 Everything Exchange 交易，像 WhatsApp 一样发送。他还是抗衰老公司 New Limit 的联合创始人，但强调全职仍是 Coinbase，过早分心多家公司很危险。

https://www.youtube.com/watch?v=uLDK4l_-gUE

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
