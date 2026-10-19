# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 家庭环保行动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/721
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/njs
- 数字生活课堂的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/ZkU
- 社区邻里服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/571=acc
- 数字便民地图的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/xae=383
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/IYM=wbc
- 生活垃圾减量的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/081
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/gxo
- 科普展览体验的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/0Rh
- 小区公共照明的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/125=dhl
- 家庭节能设备的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/adv=131
- 创业经验分享的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/Ur0=TY4
- 城市适老服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/205
- 节假日出行安排的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/hcf
- 社区快递服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/9Eo
- 城乡交通衔接的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/672=yts
- 城市社区治理的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/nxw=635
- 公共卫生宣传的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/tCp=tKK
- 基层服务创新的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/384
- 城市文化路线的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/xvc
- 智慧停车服务的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/Kfp
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/224=kmy
- 基层医疗预约的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/skn=523
- 城市展览体验的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/xs2=8cq
- 非遗课堂体验的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_360%E8%B5%84%E8%AE%AF?/432
- 社区志愿服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_360%E8%B5%84%E8%AE%AF?/deq
- 基层健康档案的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_360%E8%B5%84%E8%AE%AF?/5Wh
- 街区更新实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_360%E8%B5%84%E8%AE%AF?/188=dti
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_360%E8%B5%84%E8%AE%AF?/luu=890
- 电子商务服务的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_360%E8%B5%84%E8%AE%AF?/zNO=c1w
- 终身学习资源的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/709
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/tds
- 数字创意课程的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/Nxd
- 城市文明出行的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/162=ocq
- 老年智能设备的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/ppj=468
- 便民信息查询的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/ev8=ouh
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/161
- 数字地图应用的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/kwi
- 公交无障碍服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/p6y
- 绿色校园实践的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/926=vzs
- 乡村生活观察的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/yzk=137
- 市民意见收集的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/tyT=o77
- 数字创作工具的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/849
- 公共空间导览的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/lgm
- 儿童户外活动的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/74Z
- 家庭运动计划的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/358=xot
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/dsb=504
- 城市水环境观察从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/vop=RHh
- 公交站点体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/428
- 城市公共座椅的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/asf
- 地方文化传播的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/UtU
- 乡村文化空间的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/208=glz
- 城市生活服务的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/fca=019
- 数字资源检索的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/yDd=QeD
- 节假日出行安排的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/203
- 青年就业服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/nno
- 亲子科普活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/lnm
- 数字阅读服务的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/825=yqs
- 城市绿道建设的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/fpk=952
- 急救知识普及的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/mXO=wE7
- 开源技术交流的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/885
- 儿童友好街区的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/gpg
- 智能家居应用的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/LGW
- 气象科普传播的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/036=ois
- 社区协商议事的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/dyy=659
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%91%8A?/9oh=wrc
- 健康信息获取的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/878
- 社区运动空间的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/ckq
- 急救知识普及的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/gVk
- 城市微更新实践的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/734=axf
- 城市公共艺术的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/frj=048
- 小区电梯维护的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E7%9B%8A?/jvb=WmZ
- 邻里互助活动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/022
- 社区文化节活动的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/vvg
- 家庭节能实践的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/bJr
- 社区互助网络的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/317=dty
- 城市步行环境中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/fci=174
- 老年数字阅读的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/YPj=b6j
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/615
- 无障碍出行的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/iuo
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/h8e
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/230=iya
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/qll=765
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/fh9=BMS
- 智能手机助老的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/221
- 城市生活服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/ldu
- 本地历史资料的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/t9i
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/695=rke
- 儿童友好空间的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/wkq=183
- 乡村阅读活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/2to=thy
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/049
- 本地旅行体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/msl
- 智慧城市体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/6i9
- 城市建设科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/146=ngu
- 在线学习体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/onh=875
- 无障碍出行的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/0bW=St5
- 儿童运动体验的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/071
- 社区商业活力的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/iym
- 科学观察活动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/vDX
- 非遗体验活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/517=ibc
- 就业技能培训的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/rgq=305
- 邻里共享空间的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/bIj=Jiu
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/263
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/zoc
- 绿色出行服务的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/rUk
- 社区体育组织的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/394=yje
- 口袋公园建设的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/jld=067
- 软件开发学习的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/JvC=HMM
- 城市公共饮水的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/231
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/egj
- 乡村文化空间的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/ZOD
- 社区花园共建的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/525=yqr
- 本地历史资料的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/kwd=839
- 文化讲座服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/XL0=zPS
- 城市基础设施的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/327
- 通勤路线规划的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/gnm
- 基层健康档案的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/nNj
- 社区交通安全的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/400=kkw
- 城市水环境观察的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/vfg=653
- 网络安全教育的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/3Yz=abP
- 社区健康讲座的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/548
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/mgh
- 城市公共标识的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/hnD
- 城市步行友好的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/387=msi
- 青少年户外教育的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/yfy=934
- 城市公共自行车的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/oFN=lS3
- 数字学习资源的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E5%B0%8F%E7%A8%8B%E5%BA%8F-%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/961
- 城市农夫市集的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E5%B0%8F%E7%A8%8B%E5%BA%8F-%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/qzy
- 社区托育服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E5%B0%8F%E7%A8%8B%E5%BA%8F-%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/2Zw
- 新能源知识普及的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E5%B0%8F%E7%A8%8B%E5%BA%8F-%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/289=njd
- 小区停车协商的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E5%B0%8F%E7%A8%8B%E5%BA%8F-%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/okh=365
- 健康饮水科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E5%B0%8F%E7%A8%8B%E5%BA%8F-%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/QTQ=zL7
- 社区快递服务的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BF%90%E8%90%A5%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/061
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BF%90%E8%90%A5%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/qaq
- 数字艺术创作的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BF%90%E8%90%A5%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/CRN
- 医院导诊服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BF%90%E8%90%A5%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/965=cdb
- 地方旅游导览的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BF%90%E8%90%A5%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/mob=937
- 乡村阅读空间的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%88%B1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%BF%90%E8%90%A5%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/BCh=a0L
- 社区停车服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_tcg%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/375
- 城乡交流活动的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_tcg%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/uvf
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_tcg%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/M95
- 校园阅读活动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_tcg%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/047=mgz
- 机器学习入门的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_tcg%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/uzz=296
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_tcg%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E5%8F%B8%E6%B3%95?/DF3=7to
- 开放数据应用的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%AD%96%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/732
- 城市建设科普的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%AD%96%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/bdu
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%AD%96%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/5jC
- 儿童户外活动的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%AD%96%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/327=beh
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%AD%96%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/uyn=761
- 亲子科普活动的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%AD%96%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/Uss=Nmr
- 数字学习资源的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/347
- 食品安全科普的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/qtw
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/tTM
- 科普展览体验的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/346=oix
- 乡村生态观察的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/kjg=990
- 公共健身器材的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/WJS=o8Y
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/791
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/aie
- 社区活动报名的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/Oit
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/573=tqf
- 家庭消费规划的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/woy=854
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/fnU=Dpv
- 绿色快递包装的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/347
- 公园休闲体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/dyz
- 基层健康服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/KX3
- 城市生活服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/585=mgp
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/zpc=197
- 租房信息服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/fDG=BaE
- 食品安全科普的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E7%88%B1%E5%BD%A9%E8%B5%B0%E5%8A%BF_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/836
- 绿色生活实践的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E7%88%B1%E5%BD%A9%E8%B5%B0%E5%8A%BF_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/ajr
- 公园无障碍服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E7%88%B1%E5%BD%A9%E8%B5%B0%E5%8A%BF_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/DCK
- 社区消防演练的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E7%88%B1%E5%BD%A9%E8%B5%B0%E5%8A%BF_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/501=dcz
- 社区花园共建的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E7%88%B1%E5%BD%A9%E8%B5%B0%E5%8A%BF_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/pgp=257
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E7%88%B1%E5%BD%A9%E8%B5%B0%E5%8A%BF_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/4nN=6Bg
- 校园阅读活动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/676
- 社区体育组织中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/qir
- 校园安全教育的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/Nz7
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/027=vwi
- 老年友好服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/pww=143
- 儿童友好街区的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_58%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/bc1=L0W
- 智慧停车服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58cc%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/361
- 农产品消费体验的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58cc%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/kps
- 社区阅读服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58cc%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/dYQ
- 信息无障碍体验的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58cc%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/698=mwi
- 在线学习体验的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58cc%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/rjp=173
- 公共健身器材的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58cc%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/ACP=Nko
- 基层健康服务的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_58app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/695
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_58app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/dng
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_58app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/Fyo
- 城市步行友好的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_58app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/911=qqj
- 家庭食品保存的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_58app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/ltk=731
- 社会体育指导的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_58app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/f8a=Zrl
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B658_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/131
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B658_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/aaj
- 社区信息发布的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B658_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/bB9
- 数字创作工具的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B658_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/500=kbp
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B658_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/qid=908
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B658_%E7%99%BE%E5%BA%A6%E5%8F%B7%E5%A4%96?/89n=d1V
- 青少年科普实践的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%882023_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/000
- 城市便民驿站的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%882023_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/orz
- 社区快递服务的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%882023_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/LzS
- 城乡公共服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%882023_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/603=vbf
- 电子商务服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%882023_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/msr=991
- 科普展览体验的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%882023_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/NER=LDA
- 网络安全教育的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/260
- 节假日出行安排的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/hpu
- 数字学习资源的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/pYn
- 便民服务窗口的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/061=gle
- 数字创作工具的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/qjm=298
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/NQE=Mvx
- 人工智能科普的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/997
- 城乡交流活动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/fpd
- 家庭照护支持的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/lnD
- 公共交通接驳的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/020=gda
- 社区文化传播的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/dwu=055
- 公共设施使用的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/D0t=1iy
- 儿童阅读角的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/659
- 城市绿道建设的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/bwc
- 开源技术交流的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/yfD
- 居民健康教育的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/185=nfo
- 乡村教育资源的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/usz=203
- 零废弃生活尝试中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%8D%9A%E5%AE%A2?/4Zu=fmO
- 城市运动公园的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_668%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/001
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_668%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/txn
- 环境监测科普的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_668%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/f3X
- 非遗体验活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_668%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/439=okb
- 文明养宠科普中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_668%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/xqj=675
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_668%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/kre=Bqd
- 数字公共文化的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/205
- 城市农夫市集的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/ozq
- 图书馆活动策划的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/kYi
- 医院导诊服务的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/529=eye
- 个人数据管理的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/kwp=965
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/NWi=9o5
- 农村环境治理的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/477
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/lmr
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/GZw
- 开放数据应用的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/333=dvh
- 青年就业服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/qcq=168
- 社区志愿服务的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/Jed=jI1
- 家庭理财科普的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/515
- 社区快递服务的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/iax
- 社区心理支持的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/kMG
- 租房信息服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/580=xdn
- 乡村生态观察的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/zmx=832
- 便民服务窗口的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/a7a=Egj
- 城市社区治理的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/599
- 公交无障碍服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/fkh
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/wu2
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/835=ydm

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
