# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

---

## 🔥 今日头条

**1️⃣ Meta 发布首个前沿模型系列 Muse Wonder，全球前沿竞赛进一步多极化。** 10月12日，Meta 超级智能实验室（Meta Superintelligence Labs，AI 负责人 Alexandr Wang）正式发布 Muse Wonder 与 Muse Wonder Full 两款模型（开发代号"Watermelon"），称其在个人与专业智能体（Agentic）任务、记忆与编程场景达到业界前沿水平。Meta 公布的基准显示其性能与 Anthropic 的 Claude Fable 5.1、OpenAI 的 GPT-6 Astra 相当；在 Artificial Analysis 智能指数 v4.3 中，Wonder Full 得分 56（标准版 52），仅次于 Claude Opus 5.5（58 分）、高于 OpenAI 与 Google 的最强模型（各 53 分）；中文媒体转述称其编程智能体表现与 Claude 并列第一。定价 $4/$20 每百万 token（输入/输出），与 Opus 5.5 同价位；已通过 Meta Model API 与 Muse Code 提供（Full 版限高级订阅，新增 Active Memory / Active Focus 能力）。发布当日 Meta 股价上涨约 3.4%–4.1%（约报 $748）。[来源：TechCrunch/WIRED/NYT/The Verge/新浪科技]

**2️⃣ 微软发布第三代自研 AI 芯片 Maia 300：从"最大押注"到百万颗级部署。** 10月12日于 OCP 全球峰会（圣何塞）亮相：288GB HBM4 显存、18TB/s 带宽；微软称其每兆瓦可产出比"领先 GPU 系统"多 40% 的 token，机架级吞吐为 Maia 200 的 7 倍。微软计划 2027 年起以"多吉瓦级"规模部署超 100 万颗 Maia 300，使其成为自家 AI 服务的主要推理硬件；公司预计今年资本开支超 1,750 亿美元。纳德拉称其为"对自研芯片的最大一笔押注"；当日微软股价涨约 2.4%，英伟达、AMD 承压。[来源：GeekWire/CNBC/Reuters/HPCwire]

---

## ☝ Headlines

- **Meta·Muse Wonder**：Meta 首个前沿模型发布，对标 Claude Opus 5.5/Fable 5.1 与 GPT-6 Astra，$4/$20 定价、发布日股价涨约 3-4%
- **微软·Maia 300**：第三代自研 AI 芯片亮相，2027 年部署超百万颗、能效 +40%/MW
- **亚马逊·Decart**：洽谈约 70 亿美元收购 AI 芯片软件公司 Decart（Anthropic 尽调后退出、亚马逊接手）
- **英国 AI 安全**：白宫解除 17 天冻结，UK AISI 恢复 OpenAI/Anthropic/DeepMind 预发布模型访问；同日英国公布 AI 风险防御包
- **DeepMind·AlphaProof Nexus**：解出 9 个 Erdős 开放数学问题（2 个悬置 56 年）+ 44 个数列猜想，并通过同行评审
- **中国 AI**：大模型周调用量 86.74 万亿 Token（环比 +50.96%）连续 24 周全球第一、前五全为中国模型；美国头部两家厂商则占近九成收入

---

## 📊 分类详报

### 🧠 模型与技术

- **Meta Muse Wonder 更多细节**：该系列由 Meta 超级智能实验室开发（2025 年 6 月招入 Scale AI 创始人 Alexandr Wang 后启动 AI 重构，历时约 14 个月），定位"面向个人与专业智能体任务的前沿模型"，较前代 Muse Spark 明显升级（Artificial Analysis 智能指数 48 → 52/56）。WIRED 评价其"让 Meta 重回 AI 前沿"。社区侧：开发者对比指出 Wonder 定价与 Opus 5.5 完全持平，但在 Meta 自家 14 项基准中有 9 项落后（dev.to 分析）；Full 版目前仅限 Meta 高级 AI 编码订阅用户。[来源：TechCrunch/WIRED/NYT/Artificial Analysis/dev.to]

- **Claude Opus 5.5 Max 首次登顶 Arena 智能体榜**：Anthropic 新模型首次入榜即夺得智能体榜第一，工具幻觉率仅 0.37%；综合榜由 Google gemini-4-argon-high 居首；国产模型 kimi-k3-max 稳居综合榜前 20，qwen3.8-max 等多款保持中上游。[来源：Arena AI 周榜（网易/搜狐转载）]

- **OpenRouter 周度调用数据（10月5日-11日）**：全球总调用量 172 万亿 Token（环比 +3.61%）；中国大模型 86.74 万亿（+50.96%），连续 24 周超过美国（18.97 万亿，+17.1%），约为其 4.6 倍；全球前五全为中国模型——DeepSeek V4.1 Flash（41 万亿、+60%）、智谱 GLM 5.3 Flash（12.2 万亿）、小米 MiMo-V2.6-Flash（11.5 万亿）、阶跃星辰 Step 5 Preview（8.84 万亿）、腾讯 Hy4 preview（8.28 万亿）；Claude Opus 5.5 居第八（5.02 万亿）。[来源：每日经济新闻/OpenRouter 测算]

### 📋 政策与监管

- **英国恢复前沿模型预发布访问权（10月12日）**：白宫逆转此前"企业须先获美国批准才能向英方共享模型"的政策，为期 17 天的冻结解除。英国 AI 部长 Kanishka Narayan 确认：UK AISI 将继续对 OpenAI、Anthropic、Google DeepMind 的最强模型进行发布前安全评估（正评估 Gemini 4 Argon 等系统）；其称目标是让英国"成为全球最难被 AI 攻击的国家之一"。[来源：Quartz/Bloomberg/Firstpost/TheNextWeb]

- **英国公布 AI 风险防御包（10月12日）**：追加系列国家级防御措施——延长"用前沿 AI 审计政府代码"试点（既有两轮试点已发现 1,000+ 潜在漏洞；其中已公布一轮以约 £13,000 的 token 成本发现 407 处弱点）；政府表示或立法保护关键基础设施免受 AI 网络威胁，并着手准备"自主系统脱离人类控制"类事件的应急机制（有专家呼吁"终止开关"）。[来源：Unite.AI/TheNextWeb/bankinfosecurity/resiliencemedia]

- **美国 CAISI 拟"并入"白宫**：路透报道，特朗普政府计划将商务部 AI 标准与创新中心（CAISI）的三名高级官员转入白宫编制、直接向白宫汇报（重组仍在敲定中）；CAISI 此前负责与 OpenAI、Google、微软等开展自愿性模型评估。[来源：Reuters/US News/cryptobriefing]

- **Brad Smith："牛奶受到的监管都比 AI 多"**：微软副董事长兼总裁 Brad Smith 呼吁建立全球统一的 AI 安全规则，包括独立评估机构与面向开发者的"紧急刹车"机制——并称当前 AI 的安全要求比一盒牛奶还少。[来源：Reuters/Fox Business]

- **比尔·盖茨警告（10月11-12日）**：在 CNN 采访中称 AI 是"人类发明过的最危险的技术"，最紧迫威胁是"未来一年内 AI 驱动的网络攻击"；强调不能让企业"自我监管"，并提到社会需讨论如何对 AI 与机器人的使用征税。[来源：CNN/Yahoo Finance]

- **中国：《关于发展新质生产力的意见》持续发酵**：中共中央、国务院 10 月 9 日印发该文件，明确"全面实施'人工智能+'行动"、加快推进 AI 手机/电脑等新一代智能终端应用，并建立技术监测、风险预警与应急响应体系、确保 AI"安全、可靠、可控"；本周进入配套落实期（如工信部"AI 应用服务商培育专项行动"）。[来源：国家发改委/财新/VOA]

- **布鲁金斯学会：AI 智能体（Agent）的全球治理**：发文探讨 AI 智能体跨境运行带来的治理缺口（责任归属、跨国部署合规）。[来源：Brookings]

### 💰 产业与商业

- **亚马逊洽购 Decart（约 70 亿美元）**：WSJ 首发（10月11日晚）——Decart 开发让 AI 模型跨不同芯片高效运行的软件，并研发"世界模型"（模拟 3D 环境）；公司 2023 年成立，今年 5 月估值近 40 亿美元（若按 70 亿成交，较该估值高出约 75%）。此前 Anthropic 8 月曾洽谈约 60 亿美元收购、9 月尽调后放弃；亚马逊为其战略客户并给予 Trainium 芯片早期访问。交易若落地将强化 AWS 自研芯片生态、进一步对冲英伟达依赖。[来源：WSJ/Bloomberg/Calcalist/Quartz]

- **微软 Maia 300 详细规格与部署计划**：288GB HBM4、18TB/s 带宽；每兆瓦 token 数 +40% vs 领先 GPU 系统、机架吞吐 7× vs Maia 200；2027 年"多吉瓦"部署、逾 100 万颗；年内资本开支预期超 1,750 亿美元。市场解读：微软推理算力从"英伟达为主"转向"自研为主"的转折点。[来源：The Verge/Notebookcheck/The Tech Portal/Reuters]

- **英伟达联合 AMD、Google、Meta 发布"开放数据中心规范 v0.7"**：在 OCP 全球峰会上联合发布统一 AI 工厂设施蓝图（覆盖电力架构、冷却、物理布局）；Google、Meta、微软、英伟达另发布"OCP 电网韧性规范"（应对公用事业扰动、快速恢复）；英伟达同时通过 MGX 1.2 开放 Vera Rubin NVL72 机架设计（支持 250kW 级机架），并宣布 ConnectX-10 / BlueField 支持 Google Falcon 传输协议（开放互联再进一步）。[来源：NVIDIA博客/StorageReview/Yahoo Finance]

- **Salesforce 收购以色列 AI 分析公司 Loops（约 3,000 万美元）**：并入 Tableau，主打"agentic analytics"（解释业务指标变动并给出行动建议）；预计 11 月初交割；消息后 CRM 涨约 3%。[来源：CTech/Globes/Proactive Investors]

- **中美 AI 商业化分化（分析）**：Menlo Ventures 数据显示，2025 年 OpenAI + Anthropic 合计占企业 LLM API 支出 67%；其 5 月报告显示两家在追踪的 34 家头部 AI 初创中占 89% 收入；Ramp 数据称首次采购 AI 的企业中 Anthropic 占逾 73% 支出。对照中国侧"调用量份额领先、收入份额有限"的结构——模型能力差距正快速转化为商业收入差距。[来源：新浪科技（投资者内参）]

### 🚀 应用与产品

- **Apple "Welcome Home" 发布会（今日 10月13日，9:00 ET 纽约）**：预计推出智能家居中枢（HomePad 类新品）、新一代 Apple TV 4K、HomePod mini 等；以"新闻稿 + 媒体体验"形式发布，AI 家庭中枢为核心看点。[来源：The Verge/9to5Mac/MacRumors]

- **阶跃星辰 STEPX Neo 智能体手机（今日上海发布）**：阶跃终端"Ready Builder One"发布会推出首款"大模型原生智能体手机"；同日，千问新一代 AI 眼镜现货发售；阶跃星辰将于 10月15日 正式开源 Step 5 Preview（该模型已上线腾讯 WorkBuddy）。[来源：智东西/华尔街见闻/东方财富/IT之家]

- **富士胶片 Synapse Pathology v3.0**（10月12日）：数字病理平台扩展 AI 能力。[来源：BioSpace]

### 🔬 研究前沿

- **DeepMind "AlphaProof Nexus" 解出 9 个 Erdős 开放问题（10月12日集中报道）**：从 353 个未解 Erdős 问题中解出 9 个（其中 2 个自 1970 年起悬置 56 年），另证明 44 个 OEIS 数列猜想；解法先行在线公开、成果通过同行评审——AI 数学推理从"竞赛题"走向真实开放问题的标志性一步。[来源：the-decoder/Reddit/The Daily Star]

- **TikTok CEO 周受资（Shou Zi Chew）：AI 将在 3 年内带来"重大科学突破"**（CNBC，10月12日）——认为 AI 对科学的推动（药物研发、材料等）将在三年内集中兑现。[来源：CNBC]

---

## ⚡ 明日关注

- **10月14日：Anthropic 上市前投资者日（Investor Day）**——已向机构投资者发出邀请（Bloomberg）；正式 IPO 营销或于 11月9日当周启动、目标感恩节前挂牌。市场关注其 ARR 指引与算力承诺兑现节奏（22V Research 视其为"市场内部结构与 AI 前景的重要节点"）。
- **10月15日：台积电 Q3 财报**（14:00 台北时间）——营收预计 NT$1.49 万亿（约 $467 亿、同比 +51%，创纪录）、净利润预计同比 +65%；AI 需求风向标；同周还有 ASML 财报。
- **10月15日：阶跃星辰正式开源 Step 5 Preview**（600B 稀疏 MoE，面向 Agentic 任务）。
- **10月13-16日：TechCrunch Disrupt 2026（旧金山）与 OCP 全球峰会持续**——更多 AI 基础设施/芯片发布与创业公司动向。
- **持续跟踪**：① 英伟达-Reflection AI 谈判进展；② Anthropic IPO 流程（投资者日 → 路演）；③ 英国 AI 立法动向（关键基础设施保护）。

---

## ⚡ 其他新闻

- 青少年科技社团的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/038
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/jjh
- 社区家校合作的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/kl2
- 创业经验分享的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/698=fmn
- 农贸市场环境的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/cwj=274
- 在线教育体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/wiH=b8d
- 乡村公共服务的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/785
- 城市骑行环境的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/krn
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/8Sb
- 家庭用电安全的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/190=waq
- 家庭志愿活动的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/wrx=755
- 城市公共艺术的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/0d3=Yji
- 城市社区治理的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%AD%A3%E5%BC%8F%E7%89%88_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/440
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%AD%A3%E5%BC%8F%E7%89%88_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/xqx
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%AD%A3%E5%BC%8F%E7%89%88_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/lIF
- 城市适老服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%AD%A3%E5%BC%8F%E7%89%88_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/104=ihz
- 社会体育指导的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%AD%A3%E5%BC%8F%E7%89%88_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/cnn=930
- 社区活动策划的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%AD%A3%E5%BC%8F%E7%89%88_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/u68=lqu
- 城市公共厕所的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_365%E9%80%9F%E5%8F%91%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/457
- 环境监测科普的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_365%E9%80%9F%E5%8F%91%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/jsp
- 数字创作工具的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_365%E9%80%9F%E5%8F%91%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/UVI
- 城市住房服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_365%E9%80%9F%E5%8F%91%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/990=wtn
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_365%E9%80%9F%E5%8F%91%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/tjm=876
- 社区快递服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_365%E9%80%9F%E5%8F%91%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/GoX=Ihm
- 便民信息查询的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%89%88_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/528
- 本地历史资料的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%89%88_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/afn
- 运动安全知识的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%89%88_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/sMe
- 信息无障碍体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%89%88_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/292=wxr
- 基层健康服务的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%89%88_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/irw=851
- 口袋公园建设的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9%E7%89%88_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/R6K=lrB
- 课后服务体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%83%BD%E6%8F%90%E7%8E%B0%E4%B8%8D_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/519
- 公共健身器材的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%83%BD%E6%8F%90%E7%8E%B0%E4%B8%8D_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/wkl
- 公交站点体验的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%83%BD%E6%8F%90%E7%8E%B0%E4%B8%8D_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/QN4
- 地方美食文化的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%83%BD%E6%8F%90%E7%8E%B0%E4%B8%8D_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/972=uqx
- 医院导诊服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%83%BD%E6%8F%90%E7%8E%B0%E4%B8%8D_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/xxt=778
- 城市基础设施的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%83%BD%E6%8F%90%E7%8E%B0%E4%B8%8D_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/LnY=oZx
- 社区垃圾分类的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/589
- 环境监测科普的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/tlg
- 小区停车协商的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/nnA
- 社区消防演练的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/967=jnp
- 社区阅读服务的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/buk=157
- 环境教育课程的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/9ZQ=NPd
- 旧物循环利用的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%883.0.0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/549
- 终身学习资源的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%883.0.0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/nol
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%883.0.0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/oq0
- 乡村公共阅读的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%883.0.0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/736=wmg
- 灵活就业交流中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%883.0.0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/isp=144
- 小区停车协商的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%883.0.0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/UQF=io8
- 公园亲子设施的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8365_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/017
- 社区家校合作的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8365_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/lqe
- 智慧城市体验的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8365_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/yvc
- 绿色出行服务的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8365_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/938=bqe
- 生活服务数字化的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8365_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/ezf=798
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8365_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/Uh6=xxM
- 线上办事服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6?/616
- 家庭安全提示的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6?/zcu
- 开放数据应用的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6?/0aO
- 街区小店体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6?/599=fxc
- 儿童友好街区的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6?/uvb=845
- 社区活动报名的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_365%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6?/f2c=CFu
- 青少年职业启蒙的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/152
- 社区活动策划的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/bde
- 家庭安全提示的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/4Fd
- 社区教育资源的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/632=ujy
- 校园安全教育的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/mcs=329
- 节日文化体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/jgF=qrt
- 青年职业探索的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/760
- 家庭安全提示的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/hnc
- 数字资源检索的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/Nab
- 邻里互助活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/466=bjq
- 社区垃圾分类的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/tmz=754
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_365%E9%80%9F%E5%8F%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/fCK=bgL
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_49-%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/787
- 生活垃圾回收的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_49-%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/yks
- 公共空间照明的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_49-%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/M6A
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_49-%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/896=hae
- 文化讲座服务的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_49-%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/rql=645
- 机器学习入门的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_49-%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/jLR=Hqj
- 口袋公园建设的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_49%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/974
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_49%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/hal
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_49%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/QVz
- 公共设施维护中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_49%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/918=agc
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_49%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/xxa=393
- 绿色生活实践的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_49%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/xgd=WEK
- 绿色消费选择中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_49%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/855
- 城市公共标识的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_49%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/fci
- 儿童阅读角的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_49%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/sgM
- 日常摄影记录的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_49%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/688=xfo
- 社区文化传播的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_49%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/sxz=179
- 城乡公共服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_49%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/5SD=YXd
- 社区花园共建的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_49%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/597
- 文化场馆预约的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_49%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/rlt
- 小区公共照明的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_49%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/Lov
- 非遗体验活动的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_49%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/567=fdt
- 居家适老化改造的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_49%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/rtl=617
- 社区公共议事的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_49%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/JWe=ubi
- 社区活动策划的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/509
- 急救知识普及的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/kii
- 绿色办公实践的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/AiZ
- 城市公共座椅的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/586=ojk
- 数字资源检索的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/srx=459
- 学校食育活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/zHM=KxA
- 公园亲子设施的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_49%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/605
- 绿色办公实践的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_49%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/rox
- 志愿服务平台的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_49%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/ln1
- 城市基础设施的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_49%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/969=mgy
- 节日文化体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_49%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/zif=442
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_49%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/Rhk=nkB
- 社区公共卫生的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_49c%E5%BD%A9%E7%A5%A8%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/023
- 乡村公共阅读的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_49c%E5%BD%A9%E7%A5%A8%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/ove
- 数字生活课堂的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_49c%E5%BD%A9%E7%A5%A8%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/K4E
- 就业技能培训的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_49c%E5%BD%A9%E7%A5%A8%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/597=qbu
- 公共设施使用的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_49c%E5%BD%A9%E7%A5%A8%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/efq=777
- 社区便民集市的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_49c%E5%BD%A9%E7%A5%A8%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/QC0=MxD
- 社区便民集市的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_49cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88v5.0_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/404
- 节假日出行安排的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_49cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88v5.0_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/trs
- 社区交通安全的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_49cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88v5.0_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/lr7
- 社区阅读服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_49cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88v5.0_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/227=xfh
- 文明养宠科普的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_49cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88v5.0_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/bev=858
- 读书会组织的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_49cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88v5.0_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/tPU=lMl
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_506%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/236
- 社区文化节活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_506%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/ivo
- 公园亲子设施的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_506%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/FdV
- 社区快递服务的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_506%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/865=quw
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_506%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/dno=181
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_506%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E6%96%87%E6%91%98?/yzi=hDH
- 食品安全科普的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_506%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/110
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_506%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/uzf
- 科学信息获取中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_506%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/g3U
- 生活服务数字化的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_506%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/557=nxe
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_506%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/shz=328
- 志愿服务平台的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_506%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/wuf=PXN
- 儿童阅读角的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8506%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/106
- 城市体育设施中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8506%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/eoq
- 社会体育指导的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8506%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/C8e
- 城市噪声观察的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8506%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/224=obp
- 城市文化路线的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8506%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/lkv=534
- 健康饮水科普的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8506%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/CiK=DYx
- 人工智能科普的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_506%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/183
- 数字便民地图的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_506%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/obp
- 公共空间照明的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_506%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/WvF
- 远程协作工具的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_506%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/015=ecz
- 新能源出行的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_506%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/fbb=683
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_506%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/deB=LRU
- 家庭饮食安排的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8506%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/151
- 城市应急科普的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8506%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/gfa
- 社区法律科普的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8506%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/03H
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8506%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/915=bwe
- 城市公共标识的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8506%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/zlg=893
- 公共空间休憩的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8506%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/9H1=jnR
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_506%E5%BD%A9%E7%A5%A8IOS_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/175
- 读书会组织的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_506%E5%BD%A9%E7%A5%A8IOS_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/hyi
- 小微企业服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_506%E5%BD%A9%E7%A5%A8IOS_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/fgK
- 数字档案服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_506%E5%BD%A9%E7%A5%A8IOS_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/876=nyg
- 全民健身活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_506%E5%BD%A9%E7%A5%A8IOS_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/jgu=837
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_506%E5%BD%A9%E7%A5%A8IOS_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/y91=gm7
- 基层健康服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_506%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/224
- 乡村公共文化的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_506%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/qqy
- 公共服务数字化的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_506%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/7id
- 小区电梯维护的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_506%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/144=yca
- 社区托育服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_506%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/jvb=416
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_506%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/1pt=nTS
- 家庭健康管理的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_506%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA?/931
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_506%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA?/ovm
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_506%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA?/XJY
- 生成式工具使用的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_506%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA?/728=vqo
- 公共服务指南的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_506%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA?/bof=385
- 城市微更新实践的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_506%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA?/j9q=f61
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_59tt-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/936
- 社区法律科普的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_59tt-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/pzn
- 社区防暑服务的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_59tt-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/9tz
- 公共设施维护的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_59tt-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/651=nyn
- 通勤路线规划的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_59tt-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/oea=149
- 社区健康讲座的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_59tt-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/KKS=i7y
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_59tt%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/431
- 低碳社区实践的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_59tt%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/hxk
- 社区生活指南的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_59tt%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/Fle
- 科技馆参观体验的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_59tt%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/214=ott
- 职业技能学习的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_59tt%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/zdp=467
- 个人时间管理的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_59tt%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E7%BB%BC%E8%89%BA?/M5A=sla
- 青年职业探索的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_59ttIOS_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/166
- 乡村公共服务的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_59ttIOS_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/caa
- 家庭教育交流的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_59ttIOS_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/iHH
- 社区儿童活动的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_59ttIOS_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/946=keu
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_59ttIOS_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/ovy=316
- 生成式工具使用的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_59ttIOS_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/sQJ=KPX
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_59tt%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/786
- 数字阅读服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_59tt%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/vsx
- 青年职业探索的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_59tt%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/eB5
- 社区环保活动的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_59tt%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/182=rhu
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_59tt%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/eag=736
- 城市文明出行的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_59tt%E5%AE%89%E5%8D%93%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/psd=yv8
- 社区科普课堂的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/744
- 家庭节能设备的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/bhn
- 环境教育课程的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/NMX
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/829=cmp
- 职业技能学习的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/mbe=520
- 社区手工活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/coX=yXv
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/156
- 家庭安全提示的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/iwc
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/PVj
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/246=jwm
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/nwc=159
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6168%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/6c7=eYz
- 城市运动公园的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6168.com%E7%BD%91%E7%AB%99%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/160
- 节日文化体验的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6168.com%E7%BD%91%E7%AB%99%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/otl
- 食品安全科普的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6168.com%E7%BD%91%E7%AB%99%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/92J
- 骑行路线规划的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6168.com%E7%BD%91%E7%AB%99%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/012=uon
- 电子商务服务的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6168.com%E7%BD%91%E7%AB%99%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/wwm=538
- 便民服务地图的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6168.com%E7%BD%91%E7%AB%99%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/p9i=3wa
- 社区学习活动的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/088
- 城市博物馆服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/wjd
- 便民服务地图的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/wgs
- 乡村产业科普的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/691=iyy
- 城市基础设施的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/fpt=331
- 人工智能科普的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_6168%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/6MZ=pZ8
- 城市体育设施的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9APP%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/695
- 老年运动活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9APP%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/rgn
- 社区设施共享的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9APP%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/RSo
- 数字地图应用的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9APP%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/798=eni
- 乡村文化空间的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9APP%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/eie=267
- 老年人文化生活的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_6168%E5%BD%A9APP%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/G05=vKy
- 便民服务地图的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_6168vip%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/785
- 乡村阅读活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_6168vip%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/ssz
- 健康步道使用的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_6168vip%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/XEk
- 食品安全科普的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_6168vip%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/316=epu
- 数字便民地图的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_6168vip%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/fpy=792
- 家庭节能设备的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_6168vip%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/rhg=1FW
- 社区便民服务的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_6168%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/515
- 节假日出行安排的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_6168%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/dml
- 农村环境治理的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_6168%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/FkW
- 公共服务咨询的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_6168%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/513=cgo
- 社区知识分享的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_6168%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/swf=452
- 市民意见收集的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_6168%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/R6X=RAx
- 个人数据管理的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6168%E6%97%B6%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/203
- 个人数据管理从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6168%E6%97%B6%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/snh
- 家庭用电安全的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6168%E6%97%B6%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/EEx
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6168%E6%97%B6%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/332=gnd
- 社区公共餐饮的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6168%E6%97%B6%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/giv=413
- 公交站点体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6168%E6%97%B6%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/v2C=x8p
- 公共设施维护的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/356
- 城市游园体验的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/isr
- 居家防滑改造的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/QsM
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/512=ujr
- 城市慢行系统的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/tqf=819
- 应急物资管理的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/heA=UJQ
- 校园安全教育的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_61%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/084
- 基层健康档案的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_61%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/ccc
- 社区花园共建的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_61%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/ESf
- 无障碍出行的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_61%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/977=ray

---

## 📈 关键数据（10月11-13日）

| 指标 | 数值 | 变化/说明 |
|------|------|------|
| 全球大模型周调用量（10/5-11） | 172 万亿 Token | 环比 +3.61%（OpenRouter 测算） |
| 中国大模型周调用量 | 86.74 万亿 Token | 环比 +50.96%；连续 24 周全球第一 |
| 美国大模型周调用量 | 18.97 万亿 Token | 环比 +17.1% |
| Meta Muse Wonder 定价 | $4 / $20（每百万 Token 入/出） | 与 Claude Opus 5.5 同价位 |
| Meta / 微软股价（10/12） | Meta 约 $748（+3.4%–4.1%）；MSFT +2.4% | 模型与自研芯片发布驱动 |
| 微软 Maia 300 | 288GB HBM4；18TB/s；+40% tokens/MW | 2027 年部署超 100 万颗；资本开支预期 >$1750 亿（今年） |
| 亚马逊洽购 Decart | 约 $70 亿 | 较 5 月估值（近 $40 亿）高约 75% |
| AlphaProof Nexus 成果 | 9 个 Erdős 问题 + 44 个数列猜想 | 其中 2 题悬置 56 年；已通过同行评审 |
| 英国网络防御试点 | 累计发现 1,000+ 潜在漏洞 | 单轮试点：407 处弱点/£13,000 token 成本 |

---

*本简报由 Hermes Agent 自动生成*  
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  @PHWT7等*  
*仅供参考，不构成投资建议*
