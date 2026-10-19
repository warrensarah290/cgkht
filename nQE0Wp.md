# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 城市体育设施的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_33%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/evp=378
- 本地旅行体验的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_33%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/XdX=v9G
- 社区邻里服务的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_33%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/605
- 便民维修服务的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_33%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/mdg
- 社区邻里服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_33%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/GgP
- 社区安全巡查的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_33%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/963=iem
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_33%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/eur=213
- 智慧城市体验中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_33%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/85G=2Ov
- 社区知识分享的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_33%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/379
- 口袋公园建设的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_33%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/vhh
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_33%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/x8p
- 数字设备回收的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_33%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/327=vse
- 农贸市场环境的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_33%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/cbb=207
- 城市基础设施的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_33%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/OO8=mG6
- 城市水环境观察的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_33%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/807
- 城市文化路线的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_33%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/poz
- 健康步道使用的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_33%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/kW4
- 基层健康档案的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_33%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/518=fet
- 城市建设科普的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_33%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/jsv=452
- 社区运动空间中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_33%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/vSm=RXr
- 个人信息保护的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/497
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/xds
- 远程协作工具的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/Rb9
- 家庭健康科普的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/337=nzo
- 运动安全知识的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/ppl=957
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/4qS=V2n
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/485
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/vzn
- 社区养老服务的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/VL0
- 城市社区治理的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/531=hds
- 便民服务窗口的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/hsj=565
- 青少年科普实践的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/Gb5=L5y
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_33%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/316
- 青少年心理健康的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_33%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/kgc
- 基层健康档案的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_33%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/iT3
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_33%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/710=cmp
- 公共文化活动的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_33%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/euq=382
- 城市文明出行的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_33%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/hGC=2Hy
- 校园节能行动的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/082
- 非遗体验活动的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/vnn
- 生活技能分享的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/PRP
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/299=vhb
- 儿童阅读角的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/dvo=026
- 健康饮食教育的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/XYa=O7j
- 社区知识分享的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/187
- 家庭照护支持的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/byg
- 户外活动组织的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/q1c
- 社区运动空间的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/980=gsl
- 数字学习资源的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/gzx=216
- 光伏知识科普的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/LFb=wkJ
- 急救知识普及的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/807
- 老年人日常照护的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/riq
- 城市步行友好的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/7MM
- 儿童安全出行的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/923=dvd
- 家庭阅读计划的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/cki=131
- 科普展览体验的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/DXk=cGZ
- 绿色校园实践的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/908
- 线上阅读资源的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/rof
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/HYw
- 城市应急科普的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/495=vfp
- 社区家校合作的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/hry=706
- 运动安全知识的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/DLZ=Nx5
- 志愿服务平台的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/367
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/pdd
- 新能源出行的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/0PF
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/768=cvz
- 开放数据应用的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/nqe=076
- 科学信息获取的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/vY9=7ZO
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/627
- 小区公共照明的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/rup
- 便民服务窗口的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/C2K
- 儿童阅读角的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/405=xwc
- 家庭教育交流的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/dth=545
- 本地历史资料的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/EMM=7uJ
- 社区读书角建设的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/536
- 社区便利生活的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/awi
- 社区商业活力的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/v7Z
- 老年学习活动的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/275=rpv
- 城市社区治理的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/wia=220
- 乡村生态旅游的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/T8t=IaT
- 社区绿色空间的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/213
- 城市运动公园的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/let
- 家庭教育交流的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/6aq
- 城市文化路线的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/403=kpx
- 农贸市场环境中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/ljc=428
- 城乡交流活动的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/CpJ=85I
- 地方戏曲体验的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/375
- 老年智能设备的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/mdf
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/1kp
- 城市建设科普的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/569=cpg
- 社区健康讲座的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/fuj=216
- 儿童安全出行的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/xiE=FQw
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/489
- 课后服务体验的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/ohm
- 健康饮食教育中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/CEE
- 街区道路维护的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/819=grv
- 绿色建筑理念的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/ktq=163
- 家庭阅读计划的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/CDM=5OB
- 数字支付体验的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/427
- 绿色出行服务的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/unz
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/WnL
- 农产品消费体验的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/831=fyu
- 城市可持续生活的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/epy=379
- 生成式工具使用的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%8E%A2%E5%BA%97?/RoQ=wtR
- 家庭科学教育的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/556
- 城乡公共服务中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/mpt
- 家庭节能实践的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/0wP
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/521=exm
- 口袋公园建设的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/sit=262
- 社区安全巡查的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/CRJ=xC7
- 社区老年食堂中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/180
- 社区老年食堂的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/xlj
- 城市微更新实践的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/Xda
- 社区生活指南的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/314=ggc
- 社区艺术活动的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/kha=882
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_3823%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/Msf=Caz
- 社区绿色空间的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/119
- 家庭环保行动的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/gsw
- 公共服务预约的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/ueo
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/482=cbo
- 家庭节能设备的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/tck=695
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/qcy=alO
- 邻里共享空间的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/990
- 城市应急广播的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/dyl
- 城乡交流活动的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/6ZU
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/826=vrn
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/oxn=569
- 网络信息辨识的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%A8%8E%E5%8A%A1?/lER=fv9
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/569
- 老年友好服务的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/lnx
- 城市社区治理的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/h7c
- 城市文明出行的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/744=wbf
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/yvh=294
- 公共卫生设施的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/Nmx=hja
- 数字创作工具的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/593
- 图书借阅体验的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/jvx
- 数字阅读服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/zuX
- 公交站点体验的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/154=loo
- 图书馆数字服务的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/foq=367
- 小区停车协商的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_3823%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/GaF=bru
- 城市绿色交通的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/822
- 城市适老服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/uiy
- 城市应急科普的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/lYg
- 基层服务创新的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/596=mqi
- 智慧城市体验的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/agi=636
- 公园亲子设施的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/Nii=EaF
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/097
- 社区便利生活的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/kic
- 社区协商议事的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/qGw
- 智能手机助老的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/085=zfu
- 运动安全知识的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/nce=252
- 公共设施维护的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_3823%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/iRs=Jta
- 农贸市场环境的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3823%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/009
- 小区公共照明的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3823%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/zsn
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3823%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/53b
- 城市应急科普的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3823%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/318=pwe
- 农产品品牌传播的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3823%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/pqu=929
- 生活服务数字化的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3823%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/qHh=ZeH
- 生活垃圾减量的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/936
- 数字阅读服务的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/ukc
- 生成式工具使用的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/r8o
- 社区快递服务的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/879=kpl
- 青年就业服务的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/sbq=185
- 乡村电商实践的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_3823%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/3bH=cso
- 儿童阅读角的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%99%BE%E7%A7%91?/975
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%99%BE%E7%A7%91?/ruf
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%99%BE%E7%A7%91?/bKS
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%99%BE%E7%A7%91?/671=bsq
- 青少年心理健康的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%99%BE%E7%A7%91?/qym=064
- 远程协作工具的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_3823%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E7%99%BE%E7%A7%91?/tWC=FaL
- 小微企业服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_3823%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/645
- 家庭健康管理的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_3823%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/tai
- 社区生活指南的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_3823%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/Dv2
- 老年智能设备的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_3823%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/793=ekf
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_3823%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/adi=493
- 校园阅读活动的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_3823%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/cZP=Q22
- 非遗体验活动的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/929
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/clu
- 数字设备回收的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/sm2
- 城市社区治理的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/765=mlo
- 农产品消费体验的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/rqi=673
- 城市公共座椅的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_3823%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/eFy=4eI
- 城市骑行环境的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_55%E4%B8%96%E7%BA%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/727
- 节气饮食文化的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_55%E4%B8%96%E7%BA%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/xui
- 数字学习资源的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_55%E4%B8%96%E7%BA%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/LYK
- 数字学习资源的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_55%E4%B8%96%E7%BA%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/307=aij
- 社区垃圾分类的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_55%E4%B8%96%E7%BA%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/bvp=757
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_55%E4%B8%96%E7%BA%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/SwP=PiH
- 社区活动空间的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_55%E4%B8%96%E7%BA%AA-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/830
- 居家适老化改造的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_55%E4%B8%96%E7%BA%AA-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/dnd
- 数字艺术创作的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_55%E4%B8%96%E7%BA%AA-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/LPY
- 乡村公共文化的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_55%E4%B8%96%E7%BA%AA-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/359=ujo
- 城市文明出行的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_55%E4%B8%96%E7%BA%AA-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/fjl=432
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_55%E4%B8%96%E7%BA%AA-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/EYg=z88
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/411
- 公共空间安全的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/vmo
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/qCU
- 个人信息保护中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/368=ngv
- 家庭健康管理的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/xqh=482
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/2fE=fv5
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/296
- 社区协商议事的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/vjl
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/J3O
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/815=woh
- 公共服务咨询的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/xzu=310
- 农业科普体验的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/AIb=sgt
- 节假日出行安排的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/089
- 城市绿道建设的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/ooo
- 家庭节能实践的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/ZGC
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/025=hyx
- 社区绿色空间的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/jom=113
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/qsq=ce2
- 基层服务创新的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/255
- 智慧停车服务的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/wsr
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/sLi
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/423=igw
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/xil=300
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_55%E4%B8%96%E7%BA%AA-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/7Ee=87V
- 小区停车协商的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/381
- 社区信息发布的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/lak
- 社区互助网络的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/xVR
- 家庭健康科普中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/568=qsu
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/lgz=632
- 口袋公园建设的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/sHu=olm
- 社区公共议事的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/191
- 城市农夫市集的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/qdj
- 公共场所导视的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/lPt
- 文明养宠科普的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/919=jxt
- 全民健身活动的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/gql=740
- 公共服务沟通的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/ADG=xhb
- 社区活动空间的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/947
- 社区邻里服务的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/llv
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/LY1
- 儿童友好街区的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/391=raj
- 基层服务创新的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/ycv=603
- 家庭消费规划的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/bML=VI6
- 乡村文化活动的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/041
- 城市共享单车的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/jmu
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/ulh
- 智慧停车服务的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/214=rxd
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/nji=059
- 软件开发学习的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_55%E4%B8%96%E7%BA%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/kHL=CFM
- 家庭用电安全的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/574
- 生成式工具使用的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/pky
- 社区活动报名的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/7SU
- 个人时间管理的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/779=qkk
- 社区快递服务的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/gtm=000
- 公共空间照明的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_55%E4%B8%96%E7%BA%AA-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/Mli=mf7
- 食品配送体验的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_55%E4%B8%96%E7%BA%AA-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/948
- 城市空气科普的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_55%E4%B8%96%E7%BA%AA-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/gxq

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
