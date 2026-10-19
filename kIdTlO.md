# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 绿色快递包装的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E6%96%97%E5%9C%B0%E4%B8%BB%E4%B8%80%E5%A4%A9%E8%B5%9A400%E7%99%BE_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/gwq=322
- 城市绿道建设的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E6%96%97%E5%9C%B0%E4%B8%BB%E4%B8%80%E5%A4%A9%E8%B5%9A400%E7%99%BE_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/HMU=eoM
- 公共空间安全的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C%E9%80%8150%E5%85%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/966
- 城市博物馆活动的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C%E9%80%8150%E5%85%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/iwx
- 社区学习活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C%E9%80%8150%E5%85%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/Zqh
- 传统节日科普的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C%E9%80%8150%E5%85%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/828=tpn
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C%E9%80%8150%E5%85%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/qrq=908
- 农产品消费体验的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C%E9%80%8150%E5%85%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/fjx=WK3
- 家庭用电安全的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%96%97%E5%9C%B0%E4%B8%BB%E8%B5%A2%E8%AF%9D%E8%B4%B9%E6%8E%92%E8%A1%8C%E6%A6%9C%E7%AC%AC%E4%B8%80%E5%90%8D_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/019
- 线上办事服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%96%97%E5%9C%B0%E4%B8%BB%E8%B5%A2%E8%AF%9D%E8%B4%B9%E6%8E%92%E8%A1%8C%E6%A6%9C%E7%AC%AC%E4%B8%80%E5%90%8D_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/byx
- 物业服务沟通的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%96%97%E5%9C%B0%E4%B8%BB%E8%B5%A2%E8%AF%9D%E8%B4%B9%E6%8E%92%E8%A1%8C%E6%A6%9C%E7%AC%AC%E4%B8%80%E5%90%8D_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/JdZ
- 创业经验分享的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%96%97%E5%9C%B0%E4%B8%BB%E8%B5%A2%E8%AF%9D%E8%B4%B9%E6%8E%92%E8%A1%8C%E6%A6%9C%E7%AC%AC%E4%B8%80%E5%90%8D_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/131=kwu
- 邻里共享空间的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%96%97%E5%9C%B0%E4%B8%BB%E8%B5%A2%E8%AF%9D%E8%B4%B9%E6%8E%92%E8%A1%8C%E6%A6%9C%E7%AC%AC%E4%B8%80%E5%90%8D_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/rwl=356
- 老年学习活动的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%96%97%E5%9C%B0%E4%B8%BB%E8%B5%A2%E8%AF%9D%E8%B4%B9%E6%8E%92%E8%A1%8C%E6%A6%9C%E7%AC%AC%E4%B8%80%E5%90%8D_%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/Tf2=h3F
- 周末休闲规划的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/966
- 生活垃圾回收的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/vha
- 亲子科普活动的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/P6Q
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/589=wat
- 城市人文观察中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/dks=983
- 家庭园艺实践的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/KrU=o8w
- 在线教育体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%8C%85%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/147
- 线上办事服务的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%8C%85%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/sly
- 城市空气科普的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%8C%85%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/459
- 乡村文化空间的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%8C%85%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/997=pxo
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%8C%85%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/soi=814
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%8C%85%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/7xD=Icb
- 城市公共饮水的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/507
- 街区小店体验的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/niy
- 社区学习活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/fLG
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/480=fma
- 信息无障碍体验的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/uqn=450
- 节气饮食文化的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/JJN=0y2
- 数字创作工具的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/931
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/ovw
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/tDL
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/940=mmf
- 地方美食文化的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/oci=470
- 城市运动公园的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/ZTv=xc0
- 家庭照护支持的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/769
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/frc
- 社区公共卫生的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/i8a
- 乡村产业科普的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/570=pnc
- 机器人科普活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/mtz=016
- 城乡交通衔接的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/kL4=C6k
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/931
- 社区阅读服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/xlg
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/CYr
- 社区消防演练的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/633=xyj
- 城市体育设施的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/zya=897
- 乡村文化活动的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/QI1=sgM
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/444
- 科学健身方法的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/abb
- 公共服务评价的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/RQA
- 家庭网络使用的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/630=uix
- 周末休闲规划的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/idw=782
- 数字课堂应用的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/FKd=YxV
- 社区故事采集的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E5%9B%A2%E9%98%9F_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/840
- 城市公共厕所的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E5%9B%A2%E9%98%9F_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/irs
- 街道综合服务的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E5%9B%A2%E9%98%9F_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/zrQ
- 基层服务创新的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E5%9B%A2%E9%98%9F_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/329=ztv
- 绿色出行服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E5%9B%A2%E9%98%9F_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/odc=946
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E5%9B%A2%E9%98%9F_%E4%BA%AC%E4%B8%9C%E6%95%B0%E8%AF%BB?/iZw=ao9
- 街头绿植养护的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/287
- 终身学习资源的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/ntz
- 邻里互助活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/kHB
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/410=wax
- 公共卫生宣传的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/gvd=714
- 小区电梯维护的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E6%96%B0%E6%B5%AA%E6%B8%AF%E8%82%A1?/2gX=YuE
- 社区垃圾分类的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E6%96%B9%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/391
- 城市夜间照明的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E6%96%B9%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/otl
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E6%96%B9%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/nxn
- 家庭教育交流中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E6%96%B9%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/965=jnh
- 科技馆参观体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E6%96%B9%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/vwp=939
- 本地消费场景的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E6%96%B9%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/OGi=MER
- 街区更新实践的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91200%E5%85%83%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/436
- 社区儿童活动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91200%E5%85%83%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/inj
- 农贸市场环境的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91200%E5%85%83%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/eb6
- 社区垃圾回收的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91200%E5%85%83%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/253=hjk
- 城市文化路线的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91200%E5%85%83%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/tzd=440
- 公交站点体验的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91200%E5%85%83%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/4T5=5pr
- 社区公共餐饮的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/102
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/ryl
- 社区活动空间的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/3ih
- 创业经验分享的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/310=mav
- 社区运动空间的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/lpa=959
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/1L3=cSX
- 公共服务沟通的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E4%BD%A0%E5%88%86%E5%88%86%E9%92%9F%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/947
- 数字公共文化的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E4%BD%A0%E5%88%86%E5%88%86%E9%92%9F%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/xaw
- 社区共享书架的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E4%BD%A0%E5%88%86%E5%88%86%E9%92%9F%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/axF
- 公共服务预约的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E4%BD%A0%E5%88%86%E5%88%86%E9%92%9F%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/177=mqs
- 城市博物馆活动的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E4%BD%A0%E5%88%86%E5%88%86%E9%92%9F%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/vbo=287
- 家庭养老规划的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E4%BD%A0%E5%88%86%E5%88%86%E9%92%9F%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/Bk0=XkX
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/857
- 城市绿色交通的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/fhy
- 绿色快递包装中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/p7W
- 社区公共卫生的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/240=ppg
- 城市应急科普的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/fht=217
- 骑行路线规划的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/bH7=MLE
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/012
- 老年智能设备的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/zck
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/rAj
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/102=zpt
- 公园无障碍服务的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/jnn=535
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/gBT=gZp
- 社区庭院绿化的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%A0%E5%8D%81%E4%B8%87%E5%8E%8B%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/295
- 药品使用科普的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%A0%E5%8D%81%E4%B8%87%E5%8E%8B%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/gvr
- 志愿者培训交流的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%A0%E5%8D%81%E4%B8%87%E5%8E%8B%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/BQ1
- 电子商务服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%A0%E5%8D%81%E4%B8%87%E5%8E%8B%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/430=ttz
- 社区养老服务的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%A0%E5%8D%81%E4%B8%87%E5%8E%8B%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/pmp=213
- 城市树木认养的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%A0%E5%8D%81%E4%B8%87%E5%8E%8B%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/HGC=91L
- 乡村电商实践中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1500%E4%B8%87_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/820
- 社区生活指南的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1500%E4%B8%87_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/bza
- 环境监测科普的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1500%E4%B8%87_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/TNf
- 便民维修服务的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1500%E4%B8%87_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/563=jxp
- 家庭阅读计划的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1500%E4%B8%87_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/poq=868
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1500%E4%B8%87_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/Way=yrl
- 社区庭院绿化的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/810
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/ang
- 社区儿童活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/Oxc
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/100=pfu
- 电动汽车充电的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/tpj=098
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/mv7=q26
- 社区活动报名的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/759
- 老年人日常照护的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/eny
- 数字设备回收中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/AhY
- 生活服务数字化的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/340=qyo
- 电动汽车充电的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/twn=996
- 食品配送体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/gbR=ZMz
- 数字素养提升的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E2%80%94%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/525
- 家庭健康科普的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E2%80%94%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/uod
- 个人数据管理的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E2%80%94%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/INB
- 居家防滑改造的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E2%80%94%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/410=pmx
- 公共服务预约的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E2%80%94%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/pzl=695
- 社区花园共建的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E2%80%94%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/eB2=NMQ
- 城市公共自行车的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/962
- 数字生活课堂的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/mmy
- 生活服务数字化的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/NRA
- 在线学习体验的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/576=bjz
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/vdg=782
- 老年数字阅读中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/uSR=vgI
- 数字课堂应用的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/079
- 家庭安全提示的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/zsg
- 基层健康档案中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/a8S
- 生活技能分享的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/457=sqm
- 城市公共饮水的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/liw=410
- 本地历史资料的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/fqC=MiT
- 数字公共文化的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/517
- 数字创作工具的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/yby
- 社区公共议事的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/4vB
- 社区艺术活动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/941=zpm
- 城乡交流活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/lnt=534
- 农贸市场环境的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/mi2=wZ5
- 开放式学习空间的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/774
- 城市生活记录的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/sxt
- 社区邻里服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/whh
- 公共卫生宣传的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/992=qxq
- 公共服务咨询的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/zmb=355
- 机器人科普活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/zfc=4L6
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/025
- 城市展览体验的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/ytx
- 城市噪声观察的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/KGn
- 节日文化体验的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/461=pup
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/dnu=008
- 校园安全教育的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/KWL=V78
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/591
- 家庭健康管理的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/lhe
- 社区手工活动的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/Yer
- 社区应急准备的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/871=euf
- 数字档案服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/wyo=256
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/Z5J=KpH
- 社区文化传播的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/510
- 本地消费场景的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/oom
- 青少年户外教育的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/HBn
- 本地历史资料的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/096=vun
- 家庭志愿活动的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/ure=619
- 青少年心理健康的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/ceG=Tdp
- 城市文明出行的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/025
- 社区体育组织的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/skc
- 科技馆参观体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/HHU
- 社区科普课堂的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/429=xcl
- 乡村公共服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/cza=347
- 街区更新实践的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/vns=Fv4
- 社区儿童活动的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/308
- 老年学习活动的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/grb
- 社区公共议事的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/pIq
- 数字资源检索的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/906=zed
- 数字资源检索的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/xnu=880
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/11V=dWH
- 乡村电商实践的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/757
- 青年就业服务的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/oen
- 儿童阅读角的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/z10
- 城市运动公园的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/108=xtu
- 公共服务评价的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/qqn=663
- 社区绿色空间的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/pxf=u5I
- 图书馆活动策划的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B25%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/533
- 基层服务创新的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B25%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/ukn
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B25%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/DzK
- 数字创意课程的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B25%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/413=cjf
- 公交站点体验的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B25%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/fax=492
- 数字地图应用的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B25%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/44r=tJS
- 邻里共享空间的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/303
- 科学健身方法的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/ltf
- 社区便民服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/H0k
- 亲子阅读活动的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/525=vis
- 社区读书角建设的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/rmf=464
- 节约用水实践的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/p41=B6x
- 医院导诊服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/665
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/axp
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/6ox
- 数字政务体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/536=dna
- 城市休闲步道的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/bip=833
- 数字政务体验的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%97%E8%B5%A2%E5%9B%BD%E9%99%85%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/dqq=z1b
- 数字创意课程中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%9C%80%E5%BC%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/683
- 社区信息发布的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%9C%80%E5%BC%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/itw
- 绿色消费选择的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%9C%80%E5%BC%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/9bw
- 儿童户外活动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%9C%80%E5%BC%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/632=qik
- 社区垃圾回收的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%9C%80%E5%BC%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/vgo=577
- 学校体育活动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E6%9C%80%E5%BC%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/imL=CR7
- 城市步行环境的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92QQ_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/044
- 社区宠物管理中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92QQ_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/kyy
- 城市便民驿站中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92QQ_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/epY
- 街区更新实践的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92QQ_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/112=eka
- 社区绿色空间的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92QQ_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/nah=956
- 青少年户外教育的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E4%B8%93%E4%B8%9A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92QQ_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/nvs=zXB
- 街区更新实践的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/719
- 居民健康教育的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/gek
- 社区活动策划的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/abi
- 口袋公园建设的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/966=wly
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/nan=992
- 节约用水实践的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/suI=E0n
- 社区阅读服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%A4%A7%E7%A5%9E_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/678
- 城市展览体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%A4%A7%E7%A5%9E_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/kju
- 青年就业服务的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%A4%A7%E7%A5%9E_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/Yhi
- 远程协作工具的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%A4%A7%E7%A5%9E_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/262=uly
- 跨代沟通活动的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%A4%A7%E7%A5%9E_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/syk=513
- 家庭科学教育的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%A4%A7%E7%A5%9E_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/y1F=TPf
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/971
- 城市运动公园的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/axq
- 应急物资管理的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/SD8
- 社区活动报名的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/500=uuz
- 公共服务预约的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/xto=660
- 公共空间照明的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/fdS=QkY
- 社区慢性病防控的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/978
- 城市共享单车的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/wgo
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/XwI
- 文明养宠科普的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/092=nsc
- 城市慢跑路线的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/mwi=338
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E9%97%AE%E5%8D%B7?/nC5=2z6
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/325
- 公共空间休憩的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/auh

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
