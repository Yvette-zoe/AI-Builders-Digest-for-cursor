# AI Builders Digest — 2026-09-17

## X / TWITTER

**Google Labs / Gemini VP Josh Woodward** highlights new Gemini Notebook updates for students: live spoken Q&A with class materials in about 100 languages, and on-the-go lecture/note recording that auto-saves audio into a chosen notebook. University students can still get a free Google AI Plan in 140+ countries for higher limits and more Google products.

Google Labs / Gemini VP Josh Woodward 介绍面向学生的 Gemini Notebook 新能力：可用约 100 种语言对课堂材料做实时语音问答，以及随时录讲座/笔记并自动把音频存进选定 notebook。大学生在 140+ 个国家仍可领取免费 Google AI Plan，获得更高额度与更多 Google 产品。

https://x.com/joshwoodward/status/2099921866014306633

**AI educator / creator Peter Yang** shares Grok bot use cases that stood out after handing out codes: lead finding and outreach, competitor matrices with sources, ad-account monitoring, Jira blocker flagging, support triage, booking-flow testing, and AI research desks that turn noise into daily briefs. Asked for solopreneur advice by the Grok bot team, he says design the business so you spend more time on work you enjoy, and push boring work to bots or drop it.

AI educator / creator Peter Yang 分享发 Grok bot codes 后最突出的用例：找线索与 outreach、带来源的竞品矩阵、监控广告账户、盯 Jira 阻塞、客服分流、测试订房流程，以及把噪音收成 daily brief 的 AI research desk。Grok bot 团队问他给 solopreneurs 的建议时，他说要把业务设计成能把更多时间花在真正喜欢的事上，无聊活交给 bots，或者干脆不做。

https://x.com/petergyang/status/2100027487681953834
https://x.com/petergyang/status/2099968897323778416

**Anthropic Claude Code Thariq** says he did not expect this outcome, but now thinks MCPs beat CLIs for most integrations: models are much better at tool calling, tools can be deferred, and MCP is now stateless. If you need to compose or filter data, he recommends adding params like `query` to MCP tools.

Anthropic Claude Code Thariq 说没料到会走到这一步，但他认为对多数集成而言 MCP 已优于 CLI：模型 tool calling 强很多、工具可 defer，且 MCP 现已是无状态。若需要组合/过滤数据，他建议给 MCP tools 加类似 `query` 的参数。

https://x.com/trq212/status/2099958388230873165

**Replit CEO Amjad Masad** quote-tweets a cool demo with a sharper alternative: if the output domain is known in advance, why not train a model to produce logprobs over enums instead?

Replit CEO Amjad Masad 在引用一条酷炫 demo 时提出更锋利的替代思路：若输出域事先已知，为何不直接训练模型在 enums 上产出 logprobs？

https://x.com/amasad/status/2100056178705514703

**Vercel CEO Guillermo Rauch** formally launches Vercel Labs as the public research and experimentation arm (247M downloads in), sharing what they support, research, and kill. He argues the future is multi-model: hiding model choice confuses customers and blocks them from the upside of competition. Separately he notes Safari 27 supports JSPI so sync native WebAssembly can suspend on an async Promise, and that libfx on fx.sh uses the browser fetch stack for API calls as more code goes native.

Vercel CEO Guillermo Rauch 正式推出 Vercel Labs，作为公开的研究与实验臂膀（已累计 2.47 亿 downloads），会公开支持项、研究方向与失败实验。他认为未来是 multi-model：隐藏模型选择只会让客户困惑，也让他们无法参与当前最激烈的竞争红利。另外他提到 Safari 27 支持 JSPI，让同步 native WebAssembly 可在 async Promise 上挂起；fx.sh 上的 libfx 已用浏览器内置 fetch 栈做 API 调用，随着更多代码走向 native，他看好 WebAssembly 在 web 未来中的角色。

https://x.com/rauchg/status/2099911447598059812
https://x.com/rauchg/status/2099905740505055680
https://x.com/rauchg/status/2099974859023683975

**Box CEO Aaron Levie** says there is a massive chasm between model power and the enterprise workflows people actually want to automate, and that gap is the opportunity for the applied AI layer: connect intelligence to workflows, reengineer processes, aggregate context, design human-in-the-loop, drive change management, run domain evals, and manage security/governance. Even as models improve, that layer still must exist and may become more important, because greater capability enables more complex tasks.

Box CEO Aaron Levie 认为模型能力与企业真正想自动化的工作流之间仍有巨大鸿沟，而这正是 applied AI 层的机会：把智能接到工作流、重做流程、聚合 context、设计人在回路、推动 change management、做领域 eval，并管好安全与治理。即便模型继续狂奔，这一层仍必须存在，甚至可能更重要，因为更强能力会带来更复杂任务。

https://x.com/levie/status/2099976021311398230

**Y Combinator President & CEO Garry Tan** says he started using Capy with GStack/GBrain on fix waves for outstanding issues/PRs, and it finished in about half the time raw Codex/Claude Code would have taken using the same frontier models.

Y Combinator President & CEO Garry Tan 说他开始用 Capy 搭配 GStack/GBrain 处理 outstanding issues/PRs 的 fix waves，在同一批 frontier models 下，大约只用了裸跑 Codex/Claude Code 一半的时间。

https://x.com/garrytan/status/2099964487667454097

**FPV Ventures partner Nikunj Kothari** warns he keeps meeting founders who assume the money spigot will keep flowing. Capital is a weapon for acceleration when used well, but dependence on it turns a downturn lethal. His advice: first design the default path that keeps the company alive as a self-fulfilling business, then scenario-plan abundance or scarcity of capital over the next 6-18 months.

FPV Ventures partner Nikunj Kothari 警告他总遇到默认资金水龙头会一直开着的创始人。Capital 用得好是加速武器，过度依赖则一次下行就能致命。他的建议：先设计能让公司活下去、业务自洽的 default path，再情景推演未来 6-18 个月资金充裕或缺位会怎样。

https://x.com/nikunj/status/2100008917980102863

**Every CEO Dan Shipper** says Every has been testing a new foundation model for about a week that outputs probabilities instead of words, so it can act as a cheap, fast judge where you would otherwise need a Fable-level model. In their testing it was about 25x faster and 600x lower priced, the kind of capability he expects will feel indispensable in 6-12 months.

Every CEO Dan Shipper 说 Every 近一周在测一个新 foundation model：输出的是概率而非文字，因此能在原本需要 Fable 级模型当 judge 的场景里又快又便宜地工作。他们测下来大约快 25 倍、便宜 600 倍，他认为这类能力会在 6-12 个月后变得不可或缺。

https://x.com/danshipper/status/2099947471518474522

**South Park Commons GP Aditya Agarwal** recounts why SPC backed Profound early: they watched the company form when James and a no-degree founder met at SPC without arriving with the idea. Profound is now a $1.8B AI marketing platform used by about one third of the Fortune 100.

South Park Commons GP Aditya Agarwal 回顾 SPC 早期押注 Profound 的原因：他们看着公司成形，James 与一位无学历创始人在 SPC 相遇时并没有带着现成 idea。Profound 现已是约 $1.8B 的 AI marketing 平台，约三分之一的 Fortune 100 在用。

https://x.com/adityaag/status/2099939685657141257
https://x.com/adityaag/status/2099939689738191146

**Anthropic product Claude** announces Salesforce in Claude is now available in beta: accounts, opportunities, and pipeline come into Claude with 37 pre-built sales skills for call prep, deal review, pipeline dashboards, and forecasts without leaving the chat.

Anthropic 产品 Claude 宣布 Salesforce in Claude 已进 beta：账户、商机与 pipeline 可直接进入 Claude，并提供 37 个预置销售 skills，可在对话内完成会前准备、deal review、pipeline dashboard 与 forecast。

https://x.com/claudeai/status/2099876514330206578
https://x.com/claudeai/status/2099876515840245772

## PODCASTS

### Training Data: Box's Aaron Levie: On Reinventing Yourself in the AI Age and Enterprise Diffusion

**The Takeaway:** Box CEO Aaron Levie argues the real money and hard work sit in the applied layer between frontier models and messy enterprise workflows: connect data systems, keep humans in the loop, run change management, and evaluate domain accuracy, because chatbots alone cannot diffuse AI into banks, law firms, or life sciences.

**要点：** Box CEO Aaron Levie 认为真正的价值与苦活，卡在 frontier models 与混乱企业工作流之间的 applied layer：接通数据系统、保留人在回路、做 change management，并用领域 eval 卡准准确率；单靠 chatbot 无法把 AI 扩散进银行、律所或生命科学。

Levie frames a lasting infrastructure-vs-application pattern: even if models become "superintelligence," real rollouts still need connectors, idle time across delayed processes, legacy systems, and domain experts. Unless you underwrite the big labs at something like 100,000 employees, the diffusion economy (including FDEs) stays massive. He also wants a neutral applied layer that can pick among models for cost-optimized accuracy, rather than letting the token seller alone decide which model wins each task.

Levie 用基础设施 vs 应用的老规律来框定当下：即便模型变成 “superintelligence”，落地仍要接系统、处理流程中的空转与延迟、啃 legacy，并配领域专家。除非你认为大 labs 能扩到约 10 万员工规模，否则扩散经济（含 FDE）仍然巨大。他还希望有一个不卖 token 的 applied layer，能在准确率约束下按成本在多模型间择优，而不是让卖 token 的一方单独决定每个任务用哪家模型。

On Box itself, he describes the post-ChatGPT company pivot into an AI stack and Box agent sitting on hundreds of billions of files: extract structured metadata from contracts and research docs, answer questions across messy corpora, and run long-running workflow agents that compress multi-week enterprise steps into much shorter loops. Their agentic harness encodes Box-specific search, permissions, and document heuristics; they run a public-facing complex work eval across life sciences, financial services, public sector, and tech, plus internal holdback evals, and often beat "just give the lab our API" baselines on accuracy and latency.

落到 Box 本身，他描述 ChatGPT 时刻后的全公司转向：AI stack 与 Box agent 趴在数千亿文件上，从合同与研究材料抽结构化 metadata、跨杂乱语料问答，并用长跑 workflow agents 把原本数周的企业步骤压短。其 agentic harness 编码了 Box 特有的搜索、权限与选文档启发式；他们跑跨生命科学、金融、公共部门与科技的 complex work eval，再加上内部 holdback，并常在准确率与延迟上打赢 “直接把 API 交给 lab” 的基线。

A memorable line on work slop captures the cultural mess: people use AI for their own brainstorms, then distrust peers for doing the same, because content used to be a proxy for what someone knows. Looking ahead, he expects closed and open-weight models to grow together as mature workloads peel to cheaper models, and says getting intelligence into lawyers, sales reps, researchers, and support teams is "a trillion dollars of applied layer AI value."

关于 work slop，他有句很抓人的观察：人们自己用 AI 做头脑风暴，却又怀疑同事同样这么做，因为内容曾经是 “此人懂多少” 的代理信号。向前看，他认为闭源与 open-weight 会一起增长，成熟 workload 会剥离到更便宜的模型；把智能送到律师、销售、研究员与客服手里，才是 “万亿美元级 applied layer AI 价值”。

https://www.youtube.com/playlist?list=PLOhHNjZItNnMm5tdW61JpnyxeYH5NDDx8

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
