AI Builders Digest — 2026-11-17

## X / TWITTER

**Thibault Sottiaux (Codex & ChatGPT, OpenAI)**

OpenAI Codex & ChatGPT lead Thibault Sottiaux says the Codex team may have fixed the recurring "model at capacity" errors that have been pestering users.

OpenAI Codex & ChatGPT 负责人 Thibault Sottiaux 说，Codex 团队可能已经修好了反复出现、一直折磨用户的 “model at capacity” 错误。

https://x.com/thsottiaux/status/2122206990101536852

**Peter Yang (AI tutorials / creator)**

Creator Peter Yang shares Anthropic's Nate Parrott on why Claude keeps inventing the same "brilliant" look: serif text, off-white background, orange, and bars on card edges, because each request feels like Claude's first time. Their Claude Design prompt explicitly tells the model it over-biases to those fonts and colors, so skip them unless the user asks. Separately, Parrott (ex Browser Company / Arc) says pre-production ideas that once took a couple of weeks to prototype can now be built in one to two days at Anthropic; what has not compressed is putting builds in people's hands and learning whether they will use them. Episode: https://www.youtube.com/watch?v=604T-74s3KE

Creator Peter Yang 转述 Anthropic 的 Nate Parrott：Claude 为什么总发明同一套“超有创意”的视觉（serif、米白底、橙色、卡片边缘横条），因为每次请求在它看来都像第一次。他们的 Claude Design prompt 会明确告诉模型：你容易过度偏向这两种字体和颜色，除非用户点名，否则别用。另，Parrott（前 Browser Company / Arc）说，过去预研一个想法要几周原型，现在在 Anthropic 一两天就能搭出来；还没被压缩的是把东西交到人手上、判断他们会不会真用。节目：https://www.youtube.com/watch?v=604T-74s3KE

https://x.com/petergyang/status/2122132596352327816
https://x.com/petergyang/status/2122060856498524510
https://www.youtube.com/watch?v=604T-74s3KE

**Nan Yu (Product, Codex, OpenAI; previously Head of Product, Linear)**

OpenAI Codex product lead Nan Yu asks for the best plug-and-play home automation hub if the goal is to let Codex control everything, ideally something Codex can treat roughly like another computer.

OpenAI Codex 产品负责人 Nan Yu 在问：如果目标是用 Codex 控制整套家居，最好的即插即用 home automation hub 是什么；理想情况是 Codex 差不多能把它当成另一台电脑来看待。

https://x.com/thenanyu/status/2122096965865664924

**Guillermo Rauch (CEO, Vercel)**

Vercel CEO Guillermo Rauch introduces xeet: a hermetic, pixel-perfect X post renderer in safe Rust / wasm with zero browser, network, filesystem, or system fonts, painting a post to PNG in about 1ms (0.4ms for Jack's "setting up my twttr"). It rebuilds Blink & HarfBuzz text shaping, 1/64px line breaking, RTL bidi, 28 Chirp font subsets, and CJK/Math/Emoji fallbacks, and is structured as an "autorepo" where an oracle boots Chrome to verify tens of thousands of layout rules while a CI canary watches the original and files signed PRs for agents. Demo: https://xeet-rs.vercel.app/ Repo: https://github.com/rauchg/xeet Separately, he jokes that models are getting good at naming: a CLI he built to diagnose system slowdowns named itself hog.

Vercel CEO Guillermo Rauch 发布 xeet：安全 Rust / wasm 里的密封、像素级 X 帖子渲染器，零浏览器 / 网络 / 文件系统 / 系统字体，把帖子渲成 PNG 大约 1ms（Jack 那条 “setting up my twttr” 约 0.4ms）。它重做了 Blink & HarfBuzz 文本整形、1/64px 换行、RTL bidi、28 套 Chirp 字体子集以及 CJK/Math/Emoji fallback，并做成 “autorepo”：oracle 拉起 Chrome 核对上万条排版规则，CI canary 盯着原版演进并给 agents 提 signed PRs。演示：https://xeet-rs.vercel.app/ 仓库：https://github.com/rauchg/xeet 另他调侃模型已经很会起名：自己写的系统卡顿诊断 CLI 被命名为 hog。

https://x.com/rauchg/status/2122184794209714368
https://xeet-rs.vercel.app/
https://github.com/rauchg/xeet
https://x.com/rauchg/status/2122127120055034258

**Dan Shipper (CEO, Every)**

Every CEO Dan Shipper says the team has been pushing compounding skills (skills that improve each time you use them), and that Mike Taylor finally cracked it. Over a weekend Dan built a skill for Context Window summaries, then used autoresearch until it hit about 80% of his taste versus a no-skill baseline. The Frontier writeup frames the method as saving real drafts plus gold-case edits into binary yes/no checks (74 checks across eight cases), then optimizing a reusable short-idea-summary skill from v1 to v9 across Gemini 4 Hydrogen, Claude Opus 5.5, GPT-6 Astra, and Claude Sonnet 5.5, with every model jumping 25+ points into a ~76-81% band. Writeup: https://frontier.every.to/experiments/turn-your-daily-newsletter-edits-into-ai-checks-and-watch-every-frontier-model-jump-25-points

Every CEO Dan Shipper 说团队一直在做 compounding skills（越用越好的 skills），并认为 Mike Taylor 终于把它打通了。周末他做了一个 Context Window 摘要 skill，再用 autoresearch 迭代到相对无-skill baseline 大约达到他 80% 的口味。Frontier 长文把方法写成：把真实草稿和 gold-case 改稿沉淀成二元 yes/no checks（8 个案例共 74 条），再把可复用的 short-idea-summary skill 从 v1 优化到 v9，覆盖 Gemini 4 Hydrogen、Claude Opus 5.5、GPT-6 Astra、Claude Sonnet 5.5，每个模型都跳了 25+ 分、落到大约 76-81% 区间。全文：https://frontier.every.to/experiments/turn-your-daily-newsletter-edits-into-ai-checks-and-watch-every-frontier-model-jump-25-points

https://x.com/danshipper/status/2122091033001337134
https://frontier.every.to/experiments/turn-your-daily-newsletter-edits-into-ai-checks-and-watch-every-frontier-model-jump-25-points

Generated through the Follow Builders skill: https://github.com/zarazhangrui/follow-builders
