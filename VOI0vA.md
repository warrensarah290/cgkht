# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 社区阅读服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/935
- 传统节日科普的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/bfz
- 老年学习活动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/Xoq
- 社区志愿服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/135=ilr
- 社区活动空间的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/nnd=389
- 智能家居应用的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/zaP=Oje
- 健康饮食教育的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/848
- 个人时间管理的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/pbe
- 城市人文观察的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/kr5
- 数字支付体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/434=vrg
- 机器学习入门的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/yco=050
- 数字政务体验的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/mDd=wkQ
- 社区手工活动的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/287
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/azu
- 公园休闲体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/Rm8
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/341=goj
- 家庭教育交流的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/ajg=399
- 城市共享单车的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/Vmv=kPP
- 社区互助网络的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/050
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/uxo
- 儿童友好街区的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/430
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/879=rcu
- 节气饮食文化的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/nzz=737
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/yCg=7j9
- 口袋公园建设的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/077
- 旧物循环利用的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/aev
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/lef
- 城市绿道建设的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/421=dno
- 社区阅读服务的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/wlp=605
- 科学信息获取的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/4hA=hjU
- 城市微更新实践的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/927
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/kdb
- 青少年科技社团的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/qO1
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/813=ymf
- 街区绿化养护中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/ilb=738
- 街区小店体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/RWw=ytT
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/051
- 社区宠物管理的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/vha
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/mri
- 地方旅游导览的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/252=diz
- 图书馆活动策划的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/zwm=644
- 公共文化活动中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/Y8C=YUz
- 青少年户外教育的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/926
- 公交站点体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/bbx
- 远程协作工具的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/Fbd
- 社区便民集市的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/569=mnp
- 社区商业活力的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/pyu=823
- 社区知识分享的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/KFt=k5D
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/114
- 数字素养提升的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/bef
- 小微企业服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/nUq
- 农贸市场环境的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/330=bio
- 城市生活服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/wte=830
- 社区公共议事的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/iy8=jpM
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/420
- 食品安全科普的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/atc
- 居民健康教育的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/wTh
- 小区电梯维护的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/647=tdl
- 亲子科普活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/czg=639
- 科普展览体验的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/WPz=PDw
- 骑行路线规划的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/399
- 科学睡眠习惯的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/ngk
- 灵活就业交流的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/QeY
- 绿色出行服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/312=xcp
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/mmr=552
- 文化讲座服务的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/zmP=zLU
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/136
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/csl
- 开放数据应用的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/ZsD
- 科学教育活动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/052=jia
- 运动安全知识的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/fge=664
- 居家适老化改造的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/qz8=iHM
- 城市生活服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/353
- 城市文明出行的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/gqn
- 数字创意课程的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/9t7
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/997=kqa
- 科学教育活动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/vkr=547
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/IDB=KAs
- 便民信息查询的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/262
- 乡村生态旅游的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/fiz
- 街头绿植养护的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/Sei
- 非遗体验活动的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/390=gyp
- 社区花园共建的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/cbl=995
- 城市农夫市集的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/B2s=2YJ
- 社区活动报名的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/828
- 亲子科普活动的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/gaw
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/C90
- 环境教育课程的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/750=yfo
- 社区设施共享的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/bio=257
- 小区停车协商的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%A5%BC%E5%B8%82?/QtD=OPB
- 邻里共享空间的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/627
- 校园社团活动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/cny
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/BPw
- 应急物资管理的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/116=lco
- 科学教育活动的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/ldp=259
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/6ZG=j1M
- 电子商务服务的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/879
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/bse
- 气象科普传播的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/pb9
- 城市地名文化的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/769=rpn
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/lls=083
- 社区活动报名的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/xDl=7jI
- 公共空间导览的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/197
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/wfa
- 老年友好服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/oqm
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/492=llv
- 数字设备回收的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/qhe=261
- 科普展览体验的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/3Gl=lai
- 数字便民地图的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%B8%8D%E6%98%AF%E5%BF%85%E6%AD%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/260
- 低碳社区实践的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%B8%8D%E6%98%AF%E5%BF%85%E6%AD%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/aaz
- 儿童阅读角的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%B8%8D%E6%98%AF%E5%BF%85%E6%AD%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/kHm
- 物业服务沟通的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%B8%8D%E6%98%AF%E5%BF%85%E6%AD%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/473=avz
- 读书会组织的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%B8%8D%E6%98%AF%E5%BF%85%E6%AD%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/msu=706
- 社区儿童活动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%B8%8D%E6%98%AF%E5%BF%85%E6%AD%BB_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/Akm=ZSo
- 乡村公共服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/244
- 软件开发学习的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/mmu
- 青少年户外教育的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/5Ub
- 家庭健康科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/622=ktn
- 城市博物馆活动的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/gjo=860
- 城市夜间照明的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/oep=4d0
- 社区垃圾回收的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/034
- 科学观察活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/pln
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/MgM
- 公共服务预约的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/226=wok
- 社区共享书架的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/ywn=495
- 家庭收纳实践的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/ede=cQu
- 数字生活课堂的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/240
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/poq
- 社区老年食堂的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/g2s
- 社区宠物管理的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/859=dom
- 城市文明实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/dto=514
- 生活垃圾减量的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/J1Y=39F
- 人工智能科普的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/081
- 口袋公园建设的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/bil
- 就业技能培训的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/L2I
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/862=vwf
- 绿色校园实践的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/dtx=529
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/iP5=gR7
- 传统节日科普的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%89%E7%A0%81%E5%80%8D%E6%8A%9520%E5%80%8D%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/110
- 文化讲座服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%89%E7%A0%81%E5%80%8D%E6%8A%9520%E5%80%8D%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/cut
- 社区活动策划的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%89%E7%A0%81%E5%80%8D%E6%8A%9520%E5%80%8D%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/wcg
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%89%E7%A0%81%E5%80%8D%E6%8A%9520%E5%80%8D%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/572=thl
- 城市展览体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%89%E7%A0%81%E5%80%8D%E6%8A%9520%E5%80%8D%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/hfq=695
- 灵活就业交流的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%89%E7%A0%81%E5%80%8D%E6%8A%9520%E5%80%8D%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%A9%E7%A5%A8?/P0w=jTB
- 乡村产业科普的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1000%E5%9D%97%E4%B8%89%E6%9C%AC%E9%87%91%E5%8D%81%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/298
- 家庭收纳实践的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1000%E5%9D%97%E4%B8%89%E6%9C%AC%E9%87%91%E5%8D%81%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/sla
- 居家防滑改造的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1000%E5%9D%97%E4%B8%89%E6%9C%AC%E9%87%91%E5%8D%81%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/FJC
- 生活技能分享的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1000%E5%9D%97%E4%B8%89%E6%9C%AC%E9%87%91%E5%8D%81%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/852=vdr
- 开放式学习空间的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1000%E5%9D%97%E4%B8%89%E6%9C%AC%E9%87%91%E5%8D%81%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/tue=478
- 社区法律科普的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1000%E5%9D%97%E4%B8%89%E6%9C%AC%E9%87%91%E5%8D%81%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/AqM=VII
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%A5%BD%E8%BF%98%E6%98%AF%E5%80%8D%E6%8A%95%E5%A5%BD%E4%B8%80%E7%82%B9_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/008
- 软件开发学习的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%A5%BD%E8%BF%98%E6%98%AF%E5%80%8D%E6%8A%95%E5%A5%BD%E4%B8%80%E7%82%B9_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/ilc
- 乡村阅读空间的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%A5%BD%E8%BF%98%E6%98%AF%E5%80%8D%E6%8A%95%E5%A5%BD%E4%B8%80%E7%82%B9_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/GqO
- 节气饮食文化的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%A5%BD%E8%BF%98%E6%98%AF%E5%80%8D%E6%8A%95%E5%A5%BD%E4%B8%80%E7%82%B9_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/048=zbm
- 骑行路线规划的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%A5%BD%E8%BF%98%E6%98%AF%E5%80%8D%E6%8A%95%E5%A5%BD%E4%B8%80%E7%82%B9_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/ulw=449
- 街头绿植养护的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B9%B3%E6%8A%95%E5%A5%BD%E8%BF%98%E6%98%AF%E5%80%8D%E6%8A%95%E5%A5%BD%E4%B8%80%E7%82%B9_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/jo9=WTo
- 儿童友好空间的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/852
- 社区学习活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/uay
- 城市展览体验的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/fay
- 电动汽车充电的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/760=vnb
- 社区读书角建设的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/sxw=667
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/1iD=Hvv
- 数字素养提升的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8%E5%91%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/158
- 城市夜间照明的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8%E5%91%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/ctk
- 儿童友好空间的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8%E5%91%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/uGt
- 环境监测科普的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8%E5%91%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/766=kch
- 街区小店体验的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8%E5%91%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/nwx=702
- 城市休闲步道的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%AE%89%E5%85%A8%E5%91%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/tH4=O1x
- 公共服务指南的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_1000%E6%9C%AC%E9%87%915%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/401
- 课后服务体验的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_1000%E6%9C%AC%E9%87%915%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/xxr
- 公共服务预约的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_1000%E6%9C%AC%E9%87%915%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/Yq5
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_1000%E6%9C%AC%E9%87%915%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/669=tar
- 社区防暑服务的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_1000%E6%9C%AC%E9%87%915%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/ptl=097
- 城市生活记录的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_1000%E6%9C%AC%E9%87%915%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/OG7=8cc
- 城市空气科普的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/442
- 市民意见收集的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/jxr
- 城市空气科普的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/WIa
- 网络安全教育的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/053=rcx
- 社区活动策划的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/mtb=393
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/QIa=rjg
- 绿色办公实践的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_1000%E6%9C%AC%E9%87%91%E7%A8%B3%E8%B5%9A%E5%80%8D%E6%8A%95%E6%B3%95_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/116
- 城市人文观察的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_1000%E6%9C%AC%E9%87%91%E7%A8%B3%E8%B5%9A%E5%80%8D%E6%8A%95%E6%B3%95_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/uuk
- 小区停车协商的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_1000%E6%9C%AC%E9%87%91%E7%A8%B3%E8%B5%9A%E5%80%8D%E6%8A%95%E6%B3%95_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/ntb
- 公共场馆服务的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_1000%E6%9C%AC%E9%87%91%E7%A8%B3%E8%B5%9A%E5%80%8D%E6%8A%95%E6%B3%95_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/631=lvl
- 公交无障碍服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_1000%E6%9C%AC%E9%87%91%E7%A8%B3%E8%B5%9A%E5%80%8D%E6%8A%95%E6%B3%95_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/sxj=501
- 家庭理财科普的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_1000%E6%9C%AC%E9%87%91%E7%A8%B3%E8%B5%9A%E5%80%8D%E6%8A%95%E6%B3%95_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/7BQ=1F5
- 公共设施维护的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_2000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/532
- 城乡公共服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_2000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/jas
- 城市体育设施的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_2000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/DyV
- 家庭节能设备的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_2000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/272=fyg
- 城市慢行系统的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_2000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/zdn=084
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_2000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/MWU=6BE
- 创业经验分享的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E9%80%92%E8%BF%9B%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/776
- 课后服务体验的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E9%80%92%E8%BF%9B%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/fsl
- 街道综合服务的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E9%80%92%E8%BF%9B%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/cPK
- 社区艺术活动的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E9%80%92%E8%BF%9B%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/433=jew
- 社区便民服务的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E9%80%92%E8%BF%9B%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/xhe=084
- 地方旅游导览的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E9%80%92%E8%BF%9B%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/YCN=OlS
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A830%E5%A4%A9%E7%9B%88%E5%88%A9%E5%9B%BE%E7%89%87_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/200
- 社区应急准备的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A830%E5%A4%A9%E7%9B%88%E5%88%A9%E5%9B%BE%E7%89%87_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/aay
- 公共卫生设施的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A830%E5%A4%A9%E7%9B%88%E5%88%A9%E5%9B%BE%E7%89%87_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/oEB
- 城市展览体验的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A830%E5%A4%A9%E7%9B%88%E5%88%A9%E5%9B%BE%E7%89%87_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/789=axi
- 乡村公共文化的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A830%E5%A4%A9%E7%9B%88%E5%88%A9%E5%9B%BE%E7%89%87_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/hxd=649
- 智能手机助老的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A830%E5%A4%A9%E7%9B%88%E5%88%A9%E5%9B%BE%E7%89%87_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/8SR=pyg
- 节约用水实践的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A920%25_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/425
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A920%25_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/tlh
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A920%25_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/hFE
- 社区垃圾回收的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A920%25_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/397=naj
- 社区老年食堂的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A920%25_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/yqc=467
- 基层健康服务中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A920%25_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%94%BE?/rhV=LPi
- 地方民俗记录的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E7%94%A810%E4%B8%AA%E6%9C%88%E8%B5%A2100%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%82%A1%E7%A5%A8?/934
- 职业技能学习的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E7%94%A810%E4%B8%AA%E6%9C%88%E8%B5%A2100%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%82%A1%E7%A5%A8?/hnb
- 个人数据管理的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E7%94%A810%E4%B8%AA%E6%9C%88%E8%B5%A2100%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%82%A1%E7%A5%A8?/5kc
- 儿童友好空间的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E7%94%A810%E4%B8%AA%E6%9C%88%E8%B5%A2100%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%82%A1%E7%A5%A8?/115=epv
- 社区养老服务的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E7%94%A810%E4%B8%AA%E6%9C%88%E8%B5%A2100%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%82%A1%E7%A5%A8?/kca=783
- 家庭园艺实践的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_1000%E6%9C%AC%E9%87%91%E7%94%A810%E4%B8%AA%E6%9C%88%E8%B5%A2100%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%82%A1%E7%A5%A8?/1Ue=SnT
- 终身学习资源的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_1000%E6%9C%AC%E9%87%91%E5%9C%9F%E8%B1%AA%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/371
- 就业技能培训的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_1000%E6%9C%AC%E9%87%91%E5%9C%9F%E8%B1%AA%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/lfb
- 老旧小区改造的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_1000%E6%9C%AC%E9%87%91%E5%9C%9F%E8%B1%AA%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/JS1
- 在线教育体验的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_1000%E6%9C%AC%E9%87%91%E5%9C%9F%E8%B1%AA%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/948=hcw
- 科普展览体验的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_1000%E6%9C%AC%E9%87%91%E5%9C%9F%E8%B1%AA%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/ahm=317
- 邻里共享空间的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_1000%E6%9C%AC%E9%87%91%E5%9C%9F%E8%B1%AA%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/6ot=n1w
- 创业经验分享的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/489
- 青年职业探索的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/wxp
- 节日文化体验的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/iCn
- 数字支付体验中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/372=ano
- 食品安全科普的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/pzy=793
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/pqj=i4x
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/701
- 城市骑行环境的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/kdv
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/Gy4
- 城市步行友好的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/543=jyb
- 乡村教育资源的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/kro=222
- 社区文化传播中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%918%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%81%A5%E8%BA%AB?/oER=Gqr
- 城市绿色交通的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2500%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/078
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2500%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/cxc
- 社区便利生活的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2500%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/qLg
- 医院导诊服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2500%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/449=lop
- 社区儿童活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2500%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/lun=227
- 智慧停车服务的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2500%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/xSw=bv9
- 在线教育体验中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/982
- 乡村公共服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/ezl
- 创业经验分享的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/ljt
- 校园节能行动的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/835=vrx
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/yuu=354
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/Uzo=HOd
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/758
- 公共服务数字化的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wvj
- 便民信息查询的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/HDL
- 城市骑行环境的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/392=vbi

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
