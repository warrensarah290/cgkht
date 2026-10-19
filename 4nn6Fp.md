# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 城市应急科普的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7005%E4%B9%90%E5%BD%A9%E7%BD%91_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/TKt
- 社区文化节活动的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7005%E4%B9%90%E5%BD%A9%E7%BD%91_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/034=bhk
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7005%E4%B9%90%E5%BD%A9%E7%BD%91_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/vqv=257
- 城市展览体验中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7005%E4%B9%90%E5%BD%A9%E7%BD%91_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/CQk=QdF
- 数字阅读服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%A6%8F%E5%BD%A93D_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/442
- 城市可持续生活的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%A6%8F%E5%BD%A93D_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/rgh
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%A6%8F%E5%BD%A93D_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/7q7
- 健康饮食教育的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%A6%8F%E5%BD%A93D_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/814=dpc
- 节能生活方式的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%A6%8F%E5%BD%A93D_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/toq=557
- 家庭安全提示的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%A6%8F%E5%BD%A93D_%E5%87%A4%E5%87%B0%E7%95%85%E6%B8%B8?/1NS=Z5A
- 社区志愿服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_17500%E6%97%A7%E7%89%88%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/136
- 社区学习活动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_17500%E6%97%A7%E7%89%88%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/pwr
- 街头绿植养护的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_17500%E6%97%A7%E7%89%88%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/Bef
- 社区活动报名的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_17500%E6%97%A7%E7%89%88%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/647=djg
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_17500%E6%97%A7%E7%89%88%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/mqj=955
- 数字生活课堂的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_17500%E6%97%A7%E7%89%88%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/typ=dBj
- 农业科普体验的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vl%E5%A4%A7%E5%8E%85-%E6%94%AF%E4%BB%98%E5%AE%9D_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/581
- 街区小店体验的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vl%E5%A4%A7%E5%8E%85-%E6%94%AF%E4%BB%98%E5%AE%9D_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/lky
- 家庭收纳实践的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vl%E5%A4%A7%E5%8E%85-%E6%94%AF%E4%BB%98%E5%AE%9D_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/ibQ
- 街区绿化养护的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vl%E5%A4%A7%E5%8E%85-%E6%94%AF%E4%BB%98%E5%AE%9D_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/657=dbs
- 老年数字阅读的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vl%E5%A4%A7%E5%8E%85-%E6%94%AF%E4%BB%98%E5%AE%9D_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/edh=330
- 学校食育活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vl%E5%A4%A7%E5%8E%85-%E6%94%AF%E4%BB%98%E5%AE%9D_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/KHQ=Gbi
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%BD%A9vl-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/069
- 社区快递服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%BD%A9vl-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/gmk
- 城市公共标识的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%BD%A9vl-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/n8k
- 社区托育服务的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%BD%A9vl-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/819=rvz
- 青年就业服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%BD%A9vl-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/bxq=996
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%BD%A9vl-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/5pK=q2x
- 社区花园共建的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9vl%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/733
- 休闲运动入门的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9vl%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/rey
- 绿色消费选择的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9vl%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/NRU
- 旧物循环利用的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9vl%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/579=bdc
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9vl%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/gby=562
- 社区修缮行动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9vl%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/JI0=2gB
- 在线教育体验的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_Welcome%E4%B9%90%E7%9B%88_%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/429
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_Welcome%E4%B9%90%E7%9B%88_%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/dmv
- 城市步行友好的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_Welcome%E4%B9%90%E7%9B%88_%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/di8
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_Welcome%E4%B9%90%E7%9B%88_%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/260=xpu
- 公共空间照明的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_Welcome%E4%B9%90%E7%9B%88_%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/aps=100
- 城市慢跑路线的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_Welcome%E4%B9%90%E7%9B%88_%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/Yje=pBg
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912ii_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/429
- 社区防暑服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912ii_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/ivd
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912ii_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/Fm3
- 乡村文化活动的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912ii_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/153=bpa
- 公共场馆服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912ii_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/hug=438
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912ii_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/oxv=mmA
- 街道综合服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/390
- 城市噪声观察的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/bvl
- 公共交通接驳的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/yM8
- 地方文化传播的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/390=vxw
- 节假日出行安排的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/izt=156
- 运动安全知识的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/772=XxH
- 家庭用电安全的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/270
- 社区文化传播的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/wch
- 家庭环保习惯的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/6y0
- 社区快递服务的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/129=umv
- 传统节日科普的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/orl=288
- 乡村生态观察的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/ijN=cWK
- 青年志愿活动的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91Ix_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/727
- 社区托育服务的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91Ix_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/urg
- 社区消防演练的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91Ix_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/8Bu
- 科技馆参观体验的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91Ix_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/825=twt
- 居民健康教育的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91Ix_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/xlz=743
- 老年友好服务的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91Ix_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/paU=0ET
- 公共服务咨询的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9vl%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/483
- 科学教育活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9vl%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/ker
- 家庭节能实践的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9vl%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/uQD
- 街区小店体验的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9vl%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/649=wnm
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9vl%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/kdl=654
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9vl%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/7Qw=jEp
- 地方旅游导览的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/291
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/qgz
- 社区家校合作的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/Srn
- 家庭阅读计划的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/452=nph
- 消防知识宣传的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/iwi=863
- 数字创作工具的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/JG3=JdD
- 城市水环境观察的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/186
- 社区便民集市的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/gxp
- 家庭用电安全的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/fJo
- 基层健康档案的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/972=wqh
- 社区商业活力的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/rrf=415
- 社区艺术活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9vl-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/llw=ZaE
- 社区垃圾分类的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/153
- 城市微更新实践中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/lyl
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/rm8
- 公共设施维护的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/353=wtc
- 城市人文观察的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/nhr=792
- 垃圾分类指导的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%BD%A9vIAPP%E5%AE%98%E6%96%B9%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/pjQ=v06
- 城市人文观察的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vI%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/052
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vI%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/qcd
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vI%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/28S
- 公共服务评价的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vI%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/341=qnf
- 社区菜市场服务的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vI%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/jed=669
- 城市应急广播的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B9%90%E5%BD%A9vI%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/gpF=k7z
- 小区电梯维护的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evl%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/175
- 城市生活记录的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evl%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/dha
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evl%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/2SP
- 社区养老服务的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evl%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/088=bhm
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evl%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/ufh=608
- 乡村电商实践中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evl%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/D09=V8D
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/231
- 公益活动组织的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/fna
- 校园安全教育的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/jjR
- 社区商业活力的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/221=puk
- 社区交通安全的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/imp=566
- 在线学习体验的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/Z83=O7Z
- 社区故事采集的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/581
- 公共空间休憩的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/hjs
- 青年职业探索的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/yoE
- 城市文明实践的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/789=gdl
- 老年运动活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/vug=244
- 社区便民集市的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/oSB=hei
- 城市噪声观察的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/160
- 公共设施使用的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/mfy
- 社区共享书架的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/uyW
- 小区公共照明的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/283=fyb
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/iwo=325
- 城市水环境观察的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/wDS=YsQ
- 非遗体验活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/019
- 家庭网络使用的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/vbq
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/tWe
- 传统节日科普的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/246=ulq
- 社区学习活动的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/vzh=533
- 社区休闲设施的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_9123%E5%A5%BD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/LkL=u3t
- 社区运动空间的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/175
- 节日文化体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/nhs
- 数字素养提升中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/zig
- 数字创作工具的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/122=hvw
- 家庭节能设备的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/eiv=920
- 城市基础设施的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_9123%E5%A5%BD%E5%BD%A9%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/v2A=a0J
- 居家适老化改造中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/369
- 物业服务沟通的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/vgk
- 城市便民驿站的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/6nN
- 城乡交流活动的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/310=gzv
- 儿童友好空间的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/xul=961
- 公园休闲体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_9123%E5%A5%BD%E5%BD%A9APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/DpQ=VxZ
- 社区法律科普的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/329
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/ash
- 环境教育课程的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/2Fz
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/356=hwp
- 城市适老服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/hve=687
- 城市慢行系统的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_9123%E5%A5%BD%E5%BD%A9%E6%AC%A2%E8%BF%8E%E6%82%A8_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/Itr=MNv
- 开源技术交流的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/402
- 健康步道使用的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/rfs
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/B7w
- 节假日出行安排的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/272=uly
- 数字设备回收的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/lpr=708
- 社区庭院绿化的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/dP8=mdR
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/520
- 家庭运动计划的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/dni
- 城市文明出行的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/2ne
- 周末休闲规划的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/086=gdw
- 城市生活记录的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/jyf=610
- 劳动教育实践的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Ev8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/m4y=CxH
- 公共服务指南的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5%E5%AE%98%E6%96%B9%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/815
- 社区安全巡查的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5%E5%AE%98%E6%96%B9%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/ryv
- 社区志愿服务的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5%E5%AE%98%E6%96%B9%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/AE7
- 绿色办公实践的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5%E5%AE%98%E6%96%B9%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/713=ytb
- 社区活动空间中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5%E5%AE%98%E6%96%B9%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/ocl=550
- 科学教育活动的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5%E5%AE%98%E6%96%B9%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/vR5=I8I
- 地方民俗记录的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/969
- 青少年科普实践的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/wwr
- 志愿服务平台的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/qqS
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/833=nkv
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/xez=551
- 学校体育活动的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/Ix5=r71
- 应急物资管理的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Ev8%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/779
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Ev8%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/kjx
- 社区便利生活的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Ev8%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/NTT
- 创业经验分享的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Ev8%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/949=nhq
- 数字生活课堂的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Ev8%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/uql=854
- 课后服务体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Ev8%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/xuy=XQG
- 社区便利生活的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_380%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/508
- 急救知识普及的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_380%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/vrx
- 数字档案服务的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_380%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/Zqc
- 市民热线服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_380%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/124=ssq
- 开放数据应用的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_380%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/hox=117
- 城市绿道建设的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_380%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/gYT=mru
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/078
- 农产品消费体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/hlr
- 家庭节能实践的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/OKL
- 本地旅行体验的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/810=eqi
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/qdj=294
- 智能手机助老的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/x5j=2qQ
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EVIIII_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/695
- 乡村文化活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EVIIII_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/jnm
- 家庭教育交流的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EVIIII_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/Tgk
- 小区电梯维护的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EVIIII_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/104=uqx
- 社区科普课堂的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EVIIII_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/ure=099
- 绿色快递包装的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EVIIII_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/iVL=aQP
- 城市公共标识的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/482
- 数字便民地图的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/vcy
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/NNO
- 家庭科学教育的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/158=vzg
- 家庭用电安全的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/tqj=231
- 社区托育服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%A5%9E%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%BE%9F%E8%B0%A3?/IuH=e0K
- 日常摄影记录的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/376
- 数字公共文化的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/orh
- 公共空间照明的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/ewA
- 数字艺术创作的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/419=szh
- 居家适老化改造的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/ess=582
- 家庭用电安全的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/CEl=2ja
- 光伏知识科普的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvlII%E5%B9%B8%E8%BF%90_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/464
- 创业经验分享的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvlII%E5%B9%B8%E8%BF%90_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/ltv
- 社区阅读服务的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvlII%E5%B9%B8%E8%BF%90_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/MR2
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvlII%E5%B9%B8%E8%BF%90_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/439=dth
- 家庭节能实践的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvlII%E5%B9%B8%E8%BF%90_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/agv=034
- 城市生活记录的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvlII%E5%B9%B8%E8%BF%90_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/4kM=Czh
- 乡村教育资源的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91VII%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/784
- 公共空间安全的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91VII%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/weq
- 新能源出行的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91VII%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/A8M
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91VII%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/454=vqx
- 街道综合服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91VII%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/mrg=385
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91VII%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/cQr=BDZ
- 社会体育指导的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/160
- 文化讲座服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/vgq
- 基层健康服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/e5d
- 公共健身器材的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/182=zmg
- 市民热线服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/hnr=787
- 老年智能设备的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/jk5=nBa
- 信息无障碍体验的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/131
- 读书会组织的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/chs
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/pY3
- 社区公共餐饮的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/482=trn
- 机器人科普活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/uuu=295
- 社区信息发布的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88app_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/Q3E=NF3
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/673
- 家庭网络使用的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/ywa
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/1Mn
- 城乡交流活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/406=ctl
- 新能源出行的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/eux=623
- 老年人日常照护的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/mY6=jQP
- 社区修缮行动的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%81%E5%BF%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/235
- 环境监测科普的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%81%E5%BF%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/cms
- 家庭运动计划的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%81%E5%BF%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/VsQ
- 全民健身活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%81%E5%BF%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/158=bxd
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%81%E5%BF%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/yuv=284
- 社区健康讲座的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%81%E5%BF%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/d8F=Cuw
- 应急物资管理的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/830
- 青年就业服务的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/qre
- 新能源知识普及的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/BZy
- 线上阅读资源的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/801=woy
- 数字创意课程的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/wcg=182
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/ycT=U74
- 街区小店体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/940
- 气象科普传播的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/zej
- 公共场所导视的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/2Jp
- 社区垃圾分类的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/538=kqt
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/mpu=471
- 安全出行教育中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/u0U=ZJk

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
