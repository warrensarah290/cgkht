# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 公共卫生宣传的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/qfq=184
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/UsR=bge
- 线上办事服务的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/445
- 乡村产业科普的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/gtg
- 课后服务体验的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/2x2
- 健康步道使用的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/613=mht
- 机器学习入门的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/pmi=767
- 城市公共艺术中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/wBU=5t5
- 城市生活服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/607
- 环境教育课程的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/nho
- 社区生活指南的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/fWT
- 便民维修服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/729=ahf
- 家庭急救准备的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/qog=558
- 公共场馆服务的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/I3m=4ok
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/286
- 乡村公共阅读的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/sxj
- 社区托育服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/kzO
- 公共服务咨询的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/961=ymq
- 邻里共享空间的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/waa=110
- 城乡交通衔接的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E9%A2%98?/n1G=JrH
- 基层健康档案的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/332
- 社区绿色空间的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/zqd
- 青少年职业启蒙的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/nCk
- 机器学习入门的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/957=enp
- 图书馆数字服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/wpy=911
- 读书会组织的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/X1b=roP
- 公共场馆服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/441
- 光伏知识科普的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/wsu
- 家庭节能设备的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/ELs
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/648=aqw
- 公交无障碍服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/oti=483
- 儿童阅读角的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/3nN=HWN
- 家庭运动计划的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/599
- 城市噪声观察的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/yyg
- 周末休闲规划从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/aa6
- 社区公共餐饮的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/920=two
- 社区活动报名的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/tzb=070
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/PT2=gZb
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/957
- 网络安全教育的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/puo
- 社区便民集市的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/RRX
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/366=yaz
- 数字资源检索中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/fij=850
- 社区活动策划的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/FYF=hKs
- 老年运动活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/780
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/eef
- 本地历史资料的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/oIW
- 公益活动组织的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/929=nkn
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/bkq=988
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/7uU=gYJ
- 乡村生态观察的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/764
- 社区绿色空间中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/pfh
- 家庭节能实践的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/o1D
- 公交站点体验的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/756=zgi
- 城市共享单车的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/idc=508
- 本地旅行体验的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/Irz=9g1
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/625
- 学校体育活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/lkm
- 公益活动组织的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/VmU
- 家庭健康管理的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/584=grz
- 全民健身活动的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/fct=661
- 老年人文化生活的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/Efh=iTh
- 数字政务体验的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/427
- 公交无障碍服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/axg
- 城市运动公园的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/5Yn
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/264=lxs
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/kzh=268
- 居民健康教育的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/8M9=KGT
- 老年数字阅读的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/129
- 公共场馆服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/rzg
- 志愿服务平台的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/OVE
- 社区心理支持的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/151=zff
- 家庭急救准备的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/gkm=279
- 市民热线服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E6%90%9C%E7%8B%90%E6%97%85%E6%B8%B8?/Af9=1wx
- 公共图书馆服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/715
- 公共卫生设施的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/bdn
- 社区商业活力的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/qx4
- 地方民俗记录的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/177=tcn
- 绿色办公实践的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/jne=277
- 社区便民集市的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/EIF=F7b
- 公共场馆服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/866
- 邻里共享空间的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/cvr
- 老年友好服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/tae
- 医院导诊服务的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/840=kah
- 公共服务指南的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/itx=623
- 社区志愿服务的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/9yG=bWA
- 个人信息保护中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/921
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/jxw
- 社区宠物管理的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/05c
- 家庭健康管理的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/993=hql
- 老年人日常照护的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/wgt=360
- 数字公共文化的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/dob=IgO
- 老年运动活动的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/581
- 家庭用电安全的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/bgq
- 骑行路线规划的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/muy
- 社区修缮行动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/670=atm
- 绿色消费选择的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/kic=656
- 社区花园共建的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/ppG=iuY
- 社区宠物管理中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2?/725
- 社区运动空间的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2?/iir
- 公共空间休憩的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2?/LbM
- 网络安全教育的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2?/768=jmc
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2?/jmf=145
- 社区邻里服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2?/Yi3=9bO
- 开放数据应用的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/700
- 学校食育活动的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/tgm
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/rIW
- 居民健康教育的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/809=boy
- 老年友好服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/ywr=728
- 家庭安全提示的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/H0e=Nwd
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/462
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/bir
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/JqA
- 公共空间安全的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/062=jde
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/soa=311
- 城市适老服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/42i=tXO
- 新能源知识普及的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/241
- 城市可持续生活的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/zdm
- 食品配送体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/fet
- 社区生活指南的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/063=wck
- 社区学习活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/utx=066
- 读书会组织的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/uUe=IKj
- 数字创意课程的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/839
- 社区公共餐饮的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/sya
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/xEy
- 儿童运动体验的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/710=kkn
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/blx=788
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/lA3=hgL
- 社区快递服务的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/872
- 家庭用电安全的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/lsm
- 城市骑行环境的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/3xh
- 社区心理支持的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/140=sek
- 城市公共标识的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/wkj=172
- 乡村文化活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/N1V=RE2
- 传统节日科普的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/451
- 城市文化路线的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/kwa
- 城市公共标识的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/Ca0
- 城市空气科普的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/887=kly
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/mbj=055
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/7yV=Wtt
- 社区运动空间的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/454
- 社区手工活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/jjv
- 儿童友好街区的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/P32
- 公共服务预约的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/019=jiz
- 城市空气科普的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/llk=353
- 社区宠物管理的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/SzY=OIQ
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/039
- 地方戏曲体验的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/hsi
- 机器学习入门的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/dQp
- 地方民俗记录的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/025=xig
- 智能家居应用的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/ogq=717
- 城市骑行环境的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/Orc=wv9
- 公共设施使用的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_1%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/462
- 城市公共厕所的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_1%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/tfi
- 城市夜间生活的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_1%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/WBH
- 社区生活指南的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_1%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/600=wsw
- 家庭运动计划的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_1%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/hwt=624
- 乡村阅读空间的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_1%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/Wwq=ogT
- 气象科普传播的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/434
- 社区修缮行动的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/vge
- 公共交通信息服务的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/XxB
- 科学教育活动的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/832=lvj
- 社区交通安全的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/ujn=507
- 乡村教育资源的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/RJN=UCE
- 数字课堂应用的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/424
- 光伏知识科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/foo
- 城市公共厕所中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/Zj4
- 公共服务咨询的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/081=ken
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/muy=530
- 个人时间管理的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/SkV=Cfy
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_1%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/948
- 线上阅读资源的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_1%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/hlh
- 邻里互助活动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_1%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/5uW
- 本地旅行体验的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_1%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/150=kmg
- 家庭环保习惯的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_1%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/gfv=151
- 公共图书馆服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_1%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/m1S=E1o
- 就业技能培训的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/306
- 数字创意课程的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/tqf
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/zU2
- 文化讲座服务的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/060=vvf
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/ymr=789
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_360%E5%85%AC%E5%BC%80%E8%AF%BE?/BDz=2lQ
- 公共服务预约的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_1%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/061
- 社区公共卫生的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_1%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/afp
- 社区协商议事的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_1%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/7pg
- 公共卫生设施的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_1%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/844=gyf
- 社区志愿服务的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_1%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/bin=957
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_1%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/vJs=XnY
- 口袋公园建设的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/495
- 健康步道使用的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/cgo
- 青年职业探索的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/eWn
- 城市步行友好的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/553=trd
- 城市公共艺术的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/uzv=956
- 社区养老服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/HHk=LqJ
- 家庭用电安全的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E7%90%86%E8%B4%A2?/867
- 社区托育服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E7%90%86%E8%B4%A2?/myd
- 学校食育活动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E7%90%86%E8%B4%A2?/tpK
- 社区安全巡查的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E7%90%86%E8%B4%A2?/065=reg
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E7%90%86%E8%B4%A2?/ehm=723
- 城市地名文化的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E7%90%86%E8%B4%A2?/w7z=dAi
- 地方美食文化的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/654
- 家庭养老规划的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/yjk
- 数字创作工具的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/lxd
- 便民信息查询的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/647=dnr
- 家庭环保行动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/aiu=768
- 社会体育指导的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/hqQ=mwK
- 校园社团活动的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/280
- 公益活动组织的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/fqf
- 城市住房服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/j9n
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/430=psn
- 人工智能科普的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/vrf=533
- 小区公共照明的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/vr3=xdH
- 公共服务数字化的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/507
- 社区志愿服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/lzj
- 城市共享单车的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/UNa
- 社区垃圾分类的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/424=ssk
- 家庭养老规划的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/wmk=493
- 街道综合服务的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/CoJ=fzG
- 科学信息获取中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/576
- 创业经验分享的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/log
- 本地消费场景的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/m4k
- 城市人文观察的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/705=xrn
- 城市夜间生活的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/jmr=212
- 休闲运动入门的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/oS1=NGy
- 地方民俗记录的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/565
- 文明养宠科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/cns
- 终身学习资源的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/H7P
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/621=tnv
- 线上办事服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/wej=677
- 学校体育活动的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/E8f=r7O
- 青少年科技社团的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_1%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/070
- 农业科普体验的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_1%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/yrh
- 绿色生活实践的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_1%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/HqW
- 城市适老服务的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_1%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/434=eeu
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_1%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/efc=624
- 家庭养老规划的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_1%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/Ytv=Z50
- 公共空间安全的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90?/152
- 健康信息获取的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90?/aij
- 社区艺术活动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90?/2t8
- 科学教育活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90?/022=fai
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90?/ppy=343
- 数字支付体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_1%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90?/pjN=nDo
- 节约用水实践的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_1%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/077
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_1%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/sah
- 社区设施共享的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_1%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/aTs
- 市民热线服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_1%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/917=djq
- 地方美食文化的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_1%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/vft=733
- 乡村阅读空间的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_1%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/bKf=6yj
- 绿色消费选择的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/059
- 社区体育组织的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/niz

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
