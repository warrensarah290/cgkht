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

- 老年智能设备的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/697
- 社区老年食堂的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/xor
- 本地旅行体验的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/8QN
- 生活垃圾回收的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/551=nwo
- 本地历史资料的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/ins=441
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/qiI=mmW
- 数字创意课程的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4_360%E6%A5%BC%E5%B8%82?/979
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4_360%E6%A5%BC%E5%B8%82?/opn
- 地方戏曲体验的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4_360%E6%A5%BC%E5%B8%82?/LH2
- 家庭收纳实践的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4_360%E6%A5%BC%E5%B8%82?/592=qdq
- 信息无障碍体验的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4_360%E6%A5%BC%E5%B8%82?/jcd=022
- 医院导诊服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E7%BE%A4_360%E6%A5%BC%E5%B8%82?/6HV=hqr
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/262
- 家庭健康管理的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/onx
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/o0S
- 乡村教育资源的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/070=hbc
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/cow=863
- 市民意见收集的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E8%BD%AC%E8%BD%BD?/cHL=Muv
- 绿色出行服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/740
- 公共场所导视的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/lec
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/joF
- 社区手工活动的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/492=fwh
- 街道综合服务的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/bxt=000
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/bqA=63k
- 青年就业服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%80%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/772
- 数字学习资源的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%80%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/yhh
- 市民热线服务的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%80%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/kd1
- 城市公共艺术的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%80%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/192=tjm
- 城市建设科普的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%80%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/dow=722
- 节气饮食文化的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%80%81%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/56D=R1N
- 儿童运动体验的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/482
- 市民热线服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/jxm
- 低碳社区实践中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/sgG
- 职业技能学习的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/787=tdl
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/oiu=149
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/km6=POC
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%9A%8F%E6%97%B6%E5%8F%AF%E4%B8%8B%E5%88%86_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/449
- 公共服务评价的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%9A%8F%E6%97%B6%E5%8F%AF%E4%B8%8B%E5%88%86_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/dth
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%9A%8F%E6%97%B6%E5%8F%AF%E4%B8%8B%E5%88%86_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/vOV
- 家庭教育交流的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%9A%8F%E6%97%B6%E5%8F%AF%E4%B8%8B%E5%88%86_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/893=law
- 社区法律科普的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%9A%8F%E6%97%B6%E5%8F%AF%E4%B8%8B%E5%88%86_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/fcu=468
- 城市步行环境的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%9A%8F%E6%97%B6%E5%8F%AF%E4%B8%8B%E5%88%86_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/zqs=ZYw
- 城市微更新实践的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/996
- 公共空间休憩的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/rtc
- 绿色消费选择的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/AOj
- 社区消防演练的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/665=ber
- 社区养老服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/isx=930
- 信息无障碍体验的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/FvF=W0k
- 青年志愿活动的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/312
- 公共服务预约的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/rii
- 街区更新实践中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/pOu
- 职业技能学习的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/757=gwx
- 创业经验分享的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/zvr=247
- 老年人日常照护的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/V5V=Tjh
- 公共卫生设施的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/106
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/kdw
- 社区知识分享的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/3Et
- 城市夜间生活的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/573=gzo
- 城市住房服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/rcq=113
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/UZJ=I1E
- 科学教育活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/067
- 急救知识普及的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/dqz
- 邻里互助活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/FT6
- 运动安全知识的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/637=fcs
- 光伏知识科普的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/ger=537
- 街区小店体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/k4k=DKB
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/878
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/sil
- 非遗课堂体验的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/rpS
- 农产品消费体验的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/213=hdg
- 儿童友好空间的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/lmj=329
- 社区读书角建设的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%9B%86?/1Wk=B3g
- 生活垃圾回收的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AB%E5%B9%B4%E8%80%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/707
- 城市夜间照明的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AB%E5%B9%B4%E8%80%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/nxb
- 城市绿色交通有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AB%E5%B9%B4%E8%80%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/qyh
- 家庭急救准备的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AB%E5%B9%B4%E8%80%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/744=atk
- 街道综合服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AB%E5%B9%B4%E8%80%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/uyw=183
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AB%E5%B9%B4%E8%80%81%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/85x=D35
- 便民服务窗口的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/712
- 社区文化传播的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/tyz
- 文化讲座服务的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/JYm
- 远程协作工具的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/117=jky
- 社区宠物管理的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/fyc=304
- 本地消费场景的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/LUp=zkJ
- 本地消费场景的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/210
- 校园阅读活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/bwr
- 小区公共照明的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/3dv
- 学校体育活动的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/037=nqr
- 公共设施维护的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/dzq=450
- 学校食育活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/DzW=3GJ
- 公共健身器材的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/950
- 社区防暑服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/cza
- 个人数据管理的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/8tE
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/755=rue
- 青少年心理健康的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/ybw=782
- 社区知识分享的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/DW3=LFx
- 社区便利生活的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%89%BE_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/587
- 地方文化传播的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%89%BE_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/xsp
- 乡村产业科普的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%89%BE_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/RMo
- 城乡公共服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%89%BE_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/271=nxx
- 社区手工活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%89%BE_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/bgh=582
- 城市便民驿站的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%89%BE_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/Bsl=D1n
- 读书会组织的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/496
- 老年人文化生活的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/knq
- 社区科普课堂的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/hij
- 社区安全巡查的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/313=kzg
- 老年运动活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/exo=951
- 地方民俗记录的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_1%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/nFL=DVe
- 家庭环保习惯的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/459
- 小区公共照明的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/cdx
- 小区公共照明的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/8vd
- 农贸市场环境的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/522=ife
- 乡村生态观察的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/vxs=826
- 文明养宠科普的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/Nxu=fVY
- 城市文明出行的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/752
- 城市骑行环境的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/tso
- 公共服务评价的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/qfx
- 节假日出行安排的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/821=nqc
- 数字支付体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/ulg=202
- 环境教育课程中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/FyA=jbT
- 开源技术交流的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/459
- 老年数字阅读的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/ocn
- 社区休闲设施的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/EaS
- 家庭志愿活动的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/260=onz
- 城市文化路线的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/zxe=738
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/2ls=qUj
- 城市文明实践的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%95%99%E5%AD%A6%E7%BD%91_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/491
- 社区科普课堂的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%95%99%E5%AD%A6%E7%BD%91_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/zvy
- 社区垃圾分类的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%95%99%E5%AD%A6%E7%BD%91_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/PXS
- 家庭健康管理的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%95%99%E5%AD%A6%E7%BD%91_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/374=tin
- 新能源出行的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%95%99%E5%AD%A6%E7%BD%91_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/knl=607
- 社区教育资源的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%95%99%E5%AD%A6%E7%BD%91_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/NbC=if1
- 日常摄影记录的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/316
- 社区心理支持的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/zap
- 劳动教育实践的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/lbp
- 数字资源检索的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/722=osv
- 休闲运动入门的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/esi=914
- 节能生活方式的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%BE%A4_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/r8p=wDB
- 社区垃圾分类的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/140
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/lkl
- 绿色办公实践的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/MlC
- 社区绿色空间的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/070=zck
- 社区托育服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/iiq=525
- 本地历史资料的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/C2t=aNZ
- 家庭网络使用的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%9D%9E%E5%87%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/999
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%9D%9E%E5%87%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/hqr
- 城市生活服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%9D%9E%E5%87%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/4qy
- 在线教育体验的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%9D%9E%E5%87%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/356=ydw
- 终身学习资源的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%9D%9E%E5%87%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/kmu=915
- 街区绿化养护的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%9D%9E%E5%87%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/4Kn=kMc
- 数字艺术创作的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/132
- 本地旅行体验的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/oez
- 校园社团活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/1Rp
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/395=mfi
- 社区家政服务的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/qnp=691
- 节假日出行安排的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/zb7=w7i
- 城市公共厕所的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_168%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_360%E5%91%A8%E6%8A%A5?/286
- 智能家居应用的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_168%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_360%E5%91%A8%E6%8A%A5?/cyz
- 基层健康档案的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_168%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_360%E5%91%A8%E6%8A%A5?/7yn
- 居民健康教育的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_168%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_360%E5%91%A8%E6%8A%A5?/438=gbh
- 城市地名文化的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_168%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_360%E5%91%A8%E6%8A%A5?/rha=130
- 公共健身器材的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_168%E8%B5%9B%E8%BD%A6%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_360%E5%91%A8%E6%8A%A5?/Vyk=21L
- 线上阅读资源的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/703
- 小区电梯维护的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/awl
- 校园社团活动中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/tBq
- 城市人文观察的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/693=yax
- 健康步道使用的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/cnb=122
- 城市树木认养的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pk%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/UVf=y9K
- 老年友好服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/793
- 网络信息辨识的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/apj
- 社区公共议事的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/XCX
- 城市文明出行的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/947=dpo
- 线上阅读资源的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/fbf=077
- 社区学习活动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/3kT=5uc
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E7%BD%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%B9%B3%E5%90%97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/891
- 环境监测科普的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E7%BD%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%B9%B3%E5%90%97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/axo
- 绿色办公实践的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E7%BD%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%B9%B3%E5%90%97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/y1k
- 家庭食品保存的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E7%BD%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%B9%B3%E5%90%97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/461=ujd
- 应急物资管理的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E7%BD%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%B9%B3%E5%90%97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/hnv=074
- 物业服务沟通的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E7%BD%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%B9%B3%E5%90%97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/2aL=6nX
- 城市绿道建设的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/710
- 小区公共照明的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/dwr
- 社区快递服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/dKa
- 社区便利生活的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/332=ggi
- 校园阅读活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/rnp=559
- 社区志愿服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/u7e=phD
- 科学教育活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9Fpk%E6%8B%BE%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/495
- 开放数据应用的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9Fpk%E6%8B%BE%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/yaa
- 社区读书角建设的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9Fpk%E6%8B%BE%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/S37
- 乡村阅读活动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9Fpk%E6%8B%BE%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/101=xqv
- 公共服务预约的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9Fpk%E6%8B%BE%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/pvx=534
- 老旧小区改造的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9Fpk%E6%8B%BE%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/Wqr=SBJ
- 校园节能行动的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E7%BD%91pk10_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/314
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E7%BD%91pk10_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/sbl
- 医院导诊服务的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E7%BD%91pk10_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/Qcs
- 城市公共座椅的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E7%BD%91pk10_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/483=pyj
- 公共交通信息服务的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E7%BD%91pk10_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/duh=507
- 家庭环保习惯的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E7%BD%91pk10_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/ecq=t1f
- 老旧小区改造的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/188
- 社区应急准备的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/ntk
- 家庭用电安全的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/2uv
- 城市适老服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/722=ips
- 生活垃圾减量的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/ylk=967
- 数字创作工具的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/LZl=1ft
- 无障碍出行中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/518
- 乡村阅读活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/whk
- 城市公共厕所中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/lGU
- 家庭理财科普的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/962=ucm
- 农产品品牌传播的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/ker=198
- 文明养宠科普的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/Cjc=VGy
- 公共场馆服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/261
- 公共卫生设施的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/rod
- 家庭教育交流的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/uoM
- 科学运动指导从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/665=ztn
- 电子商务服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/gwh=546
- 城市公共标识的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/AoX=uqT
- 乡村公共文化中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9pk10%E8%B5%9B%E8%BD%A6_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/532
- 数字政务体验的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9pk10%E8%B5%9B%E8%BD%A6_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/bka
- 城市公共自行车的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9pk10%E8%B5%9B%E8%BD%A6_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/OhT
- 城市慢行系统中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9pk10%E8%B5%9B%E8%BD%A6_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/028=aom
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9pk10%E8%B5%9B%E8%BD%A6_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/erj=955
- 家庭消费规划的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9pk10%E8%B5%9B%E8%BD%A6_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/U7T=6ye
- 个人数据管理的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pk10%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/549
- 公共空间安全的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pk10%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/xgw
- 公共卫生设施的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pk10%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/ZLD
- 城市骑行环境中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pk10%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/838=rmh
- 绿色消费选择的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pk10%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/pui=988
- 社区故事采集的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pk10%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/DzH=YVN
- 志愿服务平台的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%A8%A1%E5%BC%8F%E9%95%BF%E6%9C%9F%E7%A8%B3%E8%B5%9A%E5%85%AD%E7%A0%81%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/891
- 城市文明实践的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%A8%A1%E5%BC%8F%E9%95%BF%E6%9C%9F%E7%A8%B3%E8%B5%9A%E5%85%AD%E7%A0%81%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/dai
- 城市夜间生活的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%A8%A1%E5%BC%8F%E9%95%BF%E6%9C%9F%E7%A8%B3%E8%B5%9A%E5%85%AD%E7%A0%81%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/iGM
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%A8%A1%E5%BC%8F%E9%95%BF%E6%9C%9F%E7%A8%B3%E8%B5%9A%E5%85%AD%E7%A0%81%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/365=xaf
- 乡村阅读空间的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%A8%A1%E5%BC%8F%E9%95%BF%E6%9C%9F%E7%A8%B3%E8%B5%9A%E5%85%AD%E7%A0%81%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/eci=302
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%A8%A1%E5%BC%8F%E9%95%BF%E6%9C%9F%E7%A8%B3%E8%B5%9A%E5%85%AD%E7%A0%81%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E5%8A%A8%E6%BC%AB?/Fye=sBy
- 社区应急准备的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/860
- 基层健康档案的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/ktj
- 社区协商议事的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/wTy
- 城市应急广播的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/971=ikc
- 社区休闲设施的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/awk=628
- 城市骑行环境的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/tFC=EhY
- 家庭理财科普的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9Fpk10%E7%8E%A9%E6%B3%95%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/532
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9Fpk10%E7%8E%A9%E6%B3%95%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/zhk
- 小区停车协商的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9Fpk10%E7%8E%A9%E6%B3%95%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/k61
- 青少年科普实践的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9Fpk10%E7%8E%A9%E6%B3%95%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/846=ecf
- 家庭环保习惯的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9Fpk10%E7%8E%A9%E6%B3%95%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/szq=290
- 环境教育课程的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9Fpk10%E7%8E%A9%E6%B3%95%E6%95%99%E7%A8%8B_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/sqX=b5x
- 家庭收纳实践的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86pk10%E7%A0%B4%E8%A7%A3-%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/872
- 城市体育设施的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86pk10%E7%A0%B4%E8%A7%A3-%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/olt
- 基层健康服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86pk10%E7%A0%B4%E8%A7%A3-%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/6ZE
- 家庭饮食安排的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86pk10%E7%A0%B4%E8%A7%A3-%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/468=hbb

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
