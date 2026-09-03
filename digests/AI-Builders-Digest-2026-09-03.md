# AI Builders Digest — 2026-09-03

## X / TWITTER

**Anthropic Claude Code lead Boris Cherny** says Fable 5.1 writes with better tone and less "Claude-speak," while biology safeguards intervene on benign requests 85% less often than on Fable 5 and Claude Code users should see about 60% fewer cyber interventions per session. On pricing, cache reads for Enterprise, API, and SDK customers drop to $0.25 per million tokens from $1, up to 38% cheaper for a typical Claude Code session.

Anthropic Claude Code lead Boris Cherny 表示，Fable 5.1 文风更好、更少 “Claude-speak”；相对 Fable 5，biology safeguards 对良性请求的干预少约 85%，Claude Code 用户每个 session 的 cyber 干预也大约少 60%。价格方面，Enterprise / API / SDK 客户的 cache read 从每百万 token $1 降到 $0.25，典型 Claude Code session 最多便宜约 38%。

https://x.com/bcherny/status/2094864064648536068
https://x.com/bcherny/status/2094864063478276288
https://x.com/bcherny/status/2094864062186426373

**Claude (Anthropic)** shipped Claude Fable 5.1 everywhere and Claude Mythos 5.1 for cyberdefenders and life scientists through trusted access. Safeguards flag benign cyber requests about 60% less often and cut biology/medical fallbacks by around 85%. Enterprise Frontier Safeguards (EFS) aim for zero-data-retention-level privacy while still blocking adversarial use, rolling out in phases starting this fall.

Claude（Anthropic）宣布 Claude Fable 5.1 全面上线，面向 cyberdefenders 与生命科学的 Claude Mythos 5.1 通过 trusted access 提供。Safeguards 对良性 cyber 请求的误拦约少 60%，biology / medical 相关 fallback 约降 85%。Enterprise Frontier Safeguards（EFS）目标是在接近 zero data retention 的隐私水平下仍能拦截对抗性使用，今秋起分阶段上线。

https://x.com/claudeai/status/2094848592812917122
https://x.com/claudeai/status/2094848591617483020
https://x.com/claudeai/status/2094848590245965931

**Anthropic researcher Alex Albert** frames EFS as "ZDR++" for an agent world: traditional zero data retention could not spot cross-session patterns as companies give agents more internal access, so EFS keeps company data in the customer's cloud while an automated monitoring layer flags risky patterns to the customer's team. He expects this kind of agent observability and risk mitigation to become a standard enterprise requirement. Separately, he has been generating videos through code with Fable 5.1, including designing a house from a lot photo, rendering it, and producing a cinematic walkthrough in Blender headless.

Anthropic researcher Alex Albert 把 EFS 说成面向 agent 时代的 “ZDR++”：企业把更多内部系统交给 agent 后，传统 zero data retention 无法跨 session 发现风险模式；EFS 让公司数据留在客户自己的云里，再用自动化监控层把风险模式打给客户团队。他预计这类 agent 可观测与风险缓解会成为企业标配。另外，他用 Fable 5.1 通过代码生成视频：给一块地块照片，让模型设计房子、渲染，并用 headless Blender 做出电影感漫游。

https://x.com/alexalbert__/status/2094889286990446769
https://x.com/alexalbert__/status/2094860187743986169

**OpenAI CEO Sam Altman** says OpenAI spent the summer sprinting on safety so capabilities and safeguards can advance together, and that the next model (Astra) is coming soon. Astra has been done training for a while and is a significant step in both capabilities and alignment; for models after that, the company is slowing as needed to meet safety standards for new capability levels. He argues society and AI need an iterative loop to evolve together, and that managing the transition to abundant, powerful AI should be among the world's highest priorities.

OpenAI CEO Sam Altman 表示，OpenAI 整个夏天都在猛攻 safety，让能力与 safeguards 同步推进，下一款模型（Astra）即将发布。Astra 训练已完成一段时间，是能力与 alignment 上的明显一步；之后的模型会视需要放慢节奏，以满足新能力层级对应的安全标准。他认为社会与 AI 需要一起迭代演进，把向充裕且强大的 AI 过渡管理好，应是全球最高优先级之一。

https://x.com/sama/status/2094934592062959832

**Former Linear head of product Nan Yu** (joining OpenAI) says there is a lot of alpha in making agents less annoying: users need to stop rage-quitting before they get to value. He calls out Claude's less-annoying writing as a headline feature that looks small but matters, and sees an untapped UX opportunity for conversation and rhetoric designers.

Former Linear head of product Nan Yu（将加入 OpenAI）认为，让 agent 少惹人烦本身就有大量 alpha：用户得先别 rage-quit，才能真正用到价值。他把 Claude 更少烦人的写作当成看似细小却关键的 headline feature，并指出 conversation / rhetoric designer 是一块尚未被充分挖掘的 UX 机会。

https://x.com/thenanyu/status/2094928205753040999
https://x.com/thenanyu/status/2094928209095872530

**AI product creator Peter Yang** is pruning skills hard: keep about a dozen mostly self-authored ones, delete unused skills, and keep each as short as possible. For Fable 5.1 he recommends `/claude-api prompt-audit` to strip redundancies and rules that newer models no longer need. He also asks how to avoid skill drift when you iterate manually, then ask the model to update the skill for one-shot success and it overfits to that thread.

AI product creator Peter Yang 正在狠清 skills：只留大约十来个、大多是自己写的，不用就删，并且尽量写短。试 Fable 5.1 时他推荐跑 `/claude-api prompt-audit`，清掉新模型不再需要的冗余规则。他还追问：手动迭代修好后，再让模型改 skill 以求 one-shot，模型却往往过拟合这一条 thread，导致 skill 漂移，有没有好解法。

https://x.com/petergyang/status/2094999358525821099
https://x.com/petergyang/status/2094987791566622971
https://x.com/petergyang/status/2094995775952740795

**Anthropic Claude Code engineer Thariq** calls Fable 5.1 a very good model after diving deep, with a longer write-up coming. Practical tip: try lower effort on tasks that need less verification or have fewer edge cases, and switching effort no longer breaks the prompt cache.

Anthropic Claude Code 工程师 Thariq 深入试用后称 Fable 5.1 是非常好的模型，更长评测稍后会写。实用建议：对验证需求低、边界情况少的任务试试更低 effort；切换 effort 也不再打断 prompt cache。

https://x.com/trq212/status/2094945951865520458

**Meta Sr Director of AI Madhu Guru** (ex-Google Gemini/Veo) says every company should implement self-improving products, with building blocks including crisp primary/secondary/guardrail metrics, a strategy and roadmap tied to the metrics you most want to move, a knowledge base of past product decisions and principles, connections to dashboards/APIs/MCPs/tools so agents can observe and act, and a harness that knows the end-to-end product development flow. He separately praises Shopify's ML team as a world-class example of enterprises building their own post-training systems, evals, and data flywheels.

Meta Sr Director of AI Madhu Guru（前 Google Gemini/Veo）认为每家公司都应落地 self-improving products，核心积木包括：清晰的主指标 / 次指标 / guardrail、与最想撬动指标绑定的战略与 roadmap、沉淀过往产品决策与原则的知识库、接到 dashboard / API / MCP / 工具以便 agent 观察与行动，以及理解端到端产品开发流程的 harness。他另外点赞 Shopify ML 团队，称其为企业自建 post-training、evals 与 data flywheel 的世界级范例。

https://x.com/realmadhuguru/status/2094817857821704659
https://x.com/realmadhuguru/status/2094973690576576675

**Box CEO Aaron Levie** reports Fable 5.1 delivers a 7 percentage point jump over Fable 5 on Box's complex enterprise work eval for unstructured data tasks, with large gains in financial services (+17%), technology (+37%), and public sector (+16%) scenarios that need analysis, math, logic, and domain knowledge. Separately, he says AI for cyber is about to go vertical: models are getting extremely good at finding and exploiting vulnerabilities, open weights are not far behind frontier, and enterprises already flooded with discoveries will need AI-assisted triage and fixes with human oversight.

Box CEO Aaron Levie 称，在 Box 复杂企业工作 eval 上，Fable 5.1 相对 Fable 5 在非结构化数据任务上提升 7 个百分点；金融 (+17%)、科技 (+37%)、公共部门 (+16%) 等需要分析、数学、逻辑与领域知识的场景提升明显。另外，他认为 AI cyber 即将垂直化：模型在发现与利用漏洞上越来越强，开源权重离 frontier 不远；企业本就被 discovery 淹没，接下来只能靠 AI 辅助分诊与修复，再加人工监督。

https://x.com/levie/status/2094851976769257770
https://x.com/levie/status/2095024699441119612

**Vercel CEO Guillermo Rauch** says Fluid is what unlocked Vercel's build performance, sandbox reliability at massive concurrency, and 30-minute function durations, by unifying Dockerfile, security perimeters, networking, and file systems across compute products. He also notes Fable 5.1 is now available on Vercel AI Gateway.

Vercel CEO Guillermo Rauch 表示，Fluid 统一了各计算产品的 Dockerfile、安全边界、网络与文件系统，从而撑起 Vercel 的构建性能、大规模并发下的 sandbox 可靠性，以及 30 分钟 function 时长。他还指出 Fable 5.1 已上线 Vercel AI Gateway。

https://x.com/rauchg/status/2094831747037085978
https://x.com/rauchg/status/2094867652573528074

**FPV Ventures partner Nikunj Kothari** says people are still sleeping on WebMCP: agents can get native tool calls into a website, including UI/UX and interactive elements so they build their own views. His WebMCP challenge demo lets agents interact with an El Nino situation tracker, preserve human edits, and create shareable links for other agents or humans (live at elneenyo.com).

FPV Ventures partner Nikunj Kothari 认为大家仍低估 WebMCP：现在可以直接给 agent 网站原生 tool call，含 UI/UX 与交互元素，让它们自建视图。他提交的 WebMCP challenge demo 里，agent 可操作 El Nino 态势追踪器、保留人工编辑，并生成可分享给其他 agent 或人类的链接（体验地址 elneenyo.com）。

https://x.com/nikunj/status/2094922789128196314

## PODCASTS

### Training Data: Making Cities Awesome: Peregrine's Nick Noone & Ben Rudolph

**The Takeaway:** Public-safety AI wins by refusing the surveillance-state model: keep data owned by each city, obsess over permissioning and governance, and put forward-deployed engineers in the building until outcomes stick.

**要点：** 公共安全 AI 的打法不是堆监控，而是拒绝 surveillance state：数据仍归每个城市所有，死磕权限与治理，并把 forward-deployed engineer 送进现场，直到结果真正落地。

Peregrine co-founders Nick Noone (ex-Palantir SOCOM forward-deployed engineer) and Ben Rudolph describe the company as city infrastructure for safety and prosperity, not a data-collection business like sensor vendors that grow by capturing more inputs. Their inversion: customers already have sensitive data they cannot securely use; Peregrine helps them act on it under tight controls, then share only select pieces when needed. "We deeply believe in the idea that each customer, each institution owns their own data... it's not Peregrine's data."

Peregrine 联合创始人 Nick Noone（前 Palantir SOCOM forward-deployed engineer）与 Ben Rudolph 把公司定位为服务城市安全与繁荣的基础设施，而不是靠传感器继续堆采集、靠更多 input 增长的数据收集生意。他们的反转是：客户手里早就有用不了、也用不安全的敏感数据；Peregrine 帮他们在严控下用起来，并只在需要时分享选定片段。“We deeply believe in the idea that each customer, each institution owns their own data... it's not Peregrine's data.”

They cold-called through dozens of nos before San Pablo PD let them in on 2018-02-26. The product motion is classic FDE: co-own the customer's problem and get to the outcome three to five times faster, then treat hacky field work as the best product signal. One engineer with no edit UI wired comments that Peregrine read back to update properties; that workaround became a primitive. Deployment strategists have also shipped customer-specific tools such as a hurricane simulator and a fire-station placement model fed by 911 timing and budgets.

他们在被拒二十多次后，才于 2018-02-26 走进 San Pablo 警察局。产品动作是经典 FDE：与客户共担问题，用快三到五倍的速度打到 outcome，并把现场那些看似不可扩展的 hack 当最好的产品信号。有工程师在没有编辑 UI 时，用评论反向写回属性，这个绕路后来变成平台原语。Deployment strategist 还做出飓风模拟器、以及接入 911 响应时间与预算的消防站选址模型等客户专属工具。

On AI itself, Rudolph says about 95% of the work happens before the user types a question: data preparation so answers cite accurately. Use cases have moved from nicer search to semantic pattern finding (a detective querying antisemitic threats across synagogues without brittle keywords) and cold-case agents that can run thirty to sixty minutes over hundreds of gigabytes and reproduce what detectives previously found by hand. Noone calls the business an "anti network effect" practice: protect agency-by-agency data sanctity rather than centralizing a panopticon, and treat facial recognition as a customer-context decision, not a Silicon Valley imposition.

在 AI 本身上，Rudolph 说大约 95% 的工作发生在用户提问之前：把数据准备到能准确作答并引用。用例已从“更好用的搜索”，走到语义模式发现（警探不用脆弱关键词也能串起针对犹太会堂的威胁），再到可跑三十分钟到一小时、处理数百 GB、复现警探手工结论的 cold-case agent。Noone 把这门生意称为 “anti network effect”：按机构保护数据圣域，而不是做成中央全景监狱；面部识别也是客户语境下的决策，不是硅谷公司强加的通用开关。

A line that captures the stance: "95% of the work is what happens before the user types in the question."

最能概括其立场的一句："95% of the work is what happens before the user types in the question."

https://www.youtube.com/playlist?list=PLOhHNjZItNnMm5tdW61JpnyxeYH5NDDx8

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
