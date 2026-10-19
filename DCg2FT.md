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

- 图书借阅体验的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%ADTT%E5%BC%80%E5%A5%96%E7%BD%91_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/825
- 公共服务数字化的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%ADTT%E5%BC%80%E5%A5%96%E7%BD%91_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/srk
- 城乡交通衔接的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%ADTT%E5%BC%80%E5%A5%96%E7%BD%91_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/jCM
- 社区生活指南的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%ADTT%E5%BC%80%E5%A5%96%E7%BD%91_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/851=cfa
- 节约用水实践的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%ADTT%E5%BC%80%E5%A5%96%E7%BD%91_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/pah=848
- 城市住房服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%ADTT%E5%BC%80%E5%A5%96%E7%BD%91_%E5%87%A4%E5%87%B0%E4%B8%93%E6%A0%8F?/kTN=8iO
- 公共健身器材的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD%2C%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%2C%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%8E%86%E5%8F%B2_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/893
- 市民意见收集的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD%2C%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%2C%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%8E%86%E5%8F%B2_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/ylw
- 线上阅读资源的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD%2C%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%2C%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%8E%86%E5%8F%B2_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/jFM
- 家庭科学教育的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD%2C%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%2C%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%8E%86%E5%8F%B2_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/055=zbv
- 城市公共饮水的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD%2C%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%2C%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%8E%86%E5%8F%B2_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/lie=573
- 便民维修服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD%2C%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%2C%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%8E%86%E5%8F%B2_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/hN9=g3b
- 安全出行教育的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90168%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/617
- 社区故事采集的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90168%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/ufx
- 公益活动组织的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90168%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/wpc
- 社区便民集市的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90168%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/908=ykp
- 社区心理支持的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90168%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/ccw=246
- 安全出行教育的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90168%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E6%BE%8E%E6%B9%83%E6%8E%A2%E5%BA%97?/231=xx1
- 数据分析入门的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/765
- 社区托育服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/mjq
- 科学健身方法的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/RoY
- 老年学习活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/452=cag
- 儿童户外活动中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/utc=442
- 城乡交流活动的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/h9d=O04
- 城市适老服务的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%8E%86%E5%8F%B2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/528
- 急救知识普及的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%8E%86%E5%8F%B2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/vkh
- 小区停车协商中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%8E%86%E5%8F%B2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/1a6
- 地方戏曲体验的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%8E%86%E5%8F%B2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/721=eeu
- 城市体育设施中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%8E%86%E5%8F%B2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/bic=181
- 城市文明出行的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%8E%86%E5%8F%B2%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/Mgp=FYj
- 城市文化路线的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/113
- 街头绿植养护的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/ciq
- 个人数据管理的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/hBg
- 乡村文化活动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/645=rer
- 科技馆参观体验的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/bqk=559
- 家庭照护支持的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/LD0=9l5
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/906
- 城市基础设施的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/dgp
- 公共服务沟通的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/b8F
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/093=svh
- 乡村文化空间中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/doh=215
- 小区电梯维护的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%84%89%E8%84%89%E7%99%BE%E7%A7%91?/sRk=a6k
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/900
- 信息无障碍体验的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/zxd
- 软件开发学习的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/anu
- 在线学习体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/218=ofu
- 科学运动指导从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/tih=170
- 家庭园艺实践的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/ZA5=ooq
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E5%9F%BA%E9%87%91?/907
- 药品使用科普的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E5%9F%BA%E9%87%91?/itk
- 城市慢行系统的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E5%9F%BA%E9%87%91?/QjF
- 全民健身活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E5%9F%BA%E9%87%91?/016=ldg
- 个人信息保护的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E5%9F%BA%E9%87%91?/cjt=326
- 科普展览体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E8%A1%8C%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E5%9F%BA%E9%87%91?/Q8Y=8Qp
- 社区商业活力的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_168%E5%BC%80%E5%A5%96app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/539
- 青少年心理健康的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_168%E5%BC%80%E5%A5%96app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/uhw
- 在线教育体验的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_168%E5%BC%80%E5%A5%96app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/IPp
- 图书借阅体验的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_168%E5%BC%80%E5%A5%96app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/462=wsy
- 气象科普传播的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_168%E5%BC%80%E5%A5%96app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/inf=980
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_168%E5%BC%80%E5%A5%96app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/F5W=gqM
- 城市应急广播的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_PK10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/706
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_PK10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/esn
- 数字生活课堂的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_PK10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/FVu
- 小区公共照明的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_PK10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/111=iid
- 街区绿化养护的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_PK10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/arw=892
- 街头绿植养护的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_PK10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/Aq6=uNj
- 物业服务沟通的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E9%BE%99%E8%99%8E_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/434
- 城市文化路线的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E9%BE%99%E8%99%8E_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/pvj
- 城市游园体验的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E9%BE%99%E8%99%8E_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/TDV
- 城市文明实践的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E9%BE%99%E8%99%8E_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/014=qat
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E9%BE%99%E8%99%8E_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/qxx=351
- 城市可持续生活的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E6%8A%8A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E9%BE%99%E8%99%8E_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/5Mb=7yN
- 社区庭院绿化的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk10%E5%86%A0%E5%86%9B%E5%A6%82%E4%BD%95%E7%A8%B3%E6%9D%80%E4%B8%80%E7%A0%81_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/226
- 青少年科普实践的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk10%E5%86%A0%E5%86%9B%E5%A6%82%E4%BD%95%E7%A8%B3%E6%9D%80%E4%B8%80%E7%A0%81_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/gxx
- 家庭饮食安排的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk10%E5%86%A0%E5%86%9B%E5%A6%82%E4%BD%95%E7%A8%B3%E6%9D%80%E4%B8%80%E7%A0%81_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/EXd
- 家庭照护支持的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk10%E5%86%A0%E5%86%9B%E5%A6%82%E4%BD%95%E7%A8%B3%E6%9D%80%E4%B8%80%E7%A0%81_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/222=wvd
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk10%E5%86%A0%E5%86%9B%E5%A6%82%E4%BD%95%E7%A8%B3%E6%9D%80%E4%B8%80%E7%A0%81_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/zon=232
- 全民阅读推广的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pk10%E5%86%A0%E5%86%9B%E5%A6%82%E4%BD%95%E7%A8%B3%E6%9D%80%E4%B8%80%E7%A0%81_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/F49=IA3
- 城市绿色交通的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pk10%E5%86%A0%E5%86%9B%E6%80%8E%E6%A0%B7%E5%81%9A%E5%8F%B7%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/977
- 学校食育活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pk10%E5%86%A0%E5%86%9B%E6%80%8E%E6%A0%B7%E5%81%9A%E5%8F%B7%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/ekv
- 终身学习资源的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pk10%E5%86%A0%E5%86%9B%E6%80%8E%E6%A0%B7%E5%81%9A%E5%8F%B7%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/4dl
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pk10%E5%86%A0%E5%86%9B%E6%80%8E%E6%A0%B7%E5%81%9A%E5%8F%B7%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/397=oza
- 数字公共文化的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pk10%E5%86%A0%E5%86%9B%E6%80%8E%E6%A0%B7%E5%81%9A%E5%8F%B7%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/snl=141
- 基层健康档案的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pk10%E5%86%A0%E5%86%9B%E6%80%8E%E6%A0%B7%E5%81%9A%E5%8F%B7%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/FrJ=fJ8
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/411
- 社区家校合作的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/gty
- 药品使用科普的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/ksr
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/876=kai
- 公共交通接驳的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/zsy=327
- 小微企业服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%89%B4?/Cr3=bny
- 生活垃圾减量的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_pk10%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/326
- 青少年心理健康的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_pk10%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/ilm
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_pk10%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/0MC
- 家庭环保行动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_pk10%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/028=aej
- 数字设备回收中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_pk10%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/ktw=827
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_pk10%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/lYl=yHv
- 科技馆参观体验的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E4%B8%89%E7%A0%81%E5%BF%85%E4%B8%AD%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/315
- 学校食育活动的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E4%B8%89%E7%A0%81%E5%BF%85%E4%B8%AD%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/fjx
- 城市慢行系统的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E4%B8%89%E7%A0%81%E5%BF%85%E4%B8%AD%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/cXQ
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E4%B8%89%E7%A0%81%E5%BF%85%E4%B8%AD%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/466=wvs
- 乡村生活观察的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E4%B8%89%E7%A0%81%E5%BF%85%E4%B8%AD%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/zgy=068
- 公共设施使用的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E4%B8%89%E7%A0%81%E5%BF%85%E4%B8%AD%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/rBw=SVY
- 乡村文化活动的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%80%E7%A0%81%E6%96%B9%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/260
- 家庭科学教育的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%80%E7%A0%81%E6%96%B9%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/gyl
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%80%E7%A0%81%E6%96%B9%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/VS0
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%80%E7%A0%81%E6%96%B9%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/801=yis
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%80%E7%A0%81%E6%96%B9%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/lbq=364
- 公共空间休憩中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%80%E7%A0%81%E6%96%B9%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/mtz=HPP
- 智慧停车服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E5%9B%BD%E5%86%85?/842
- 社区艺术活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E5%9B%BD%E5%86%85?/orm
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E5%9B%BD%E5%86%85?/fVF
- 本地消费场景的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E5%9B%BD%E5%86%85?/399=zkb
- 街头绿植养护的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E5%9B%BD%E5%86%85?/uci=534
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E5%9B%BD%E5%86%85?/IGC=dHL
- 城市适老服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%89%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/941
- 社区公共餐饮的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%89%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/mhk
- 家庭运动计划的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%89%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/d1D
- 公共空间休憩的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%89%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/323=oee
- 老年运动活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%89%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/hfz=769
- 儿童友好空间的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E5%86%9B%E6%9D%80%E4%B8%89%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/7o9=N96
- 公共图书馆服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_pk10%E7%8C%9C%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/302
- 便民服务窗口的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_pk10%E7%8C%9C%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/mje
- 环境教育课程的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_pk10%E7%8C%9C%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/SG5
- 市民意见收集的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_pk10%E7%8C%9C%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/351=yeu
- 社区公共卫生的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_pk10%E7%8C%9C%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/nsw=738
- 社区文化节活动的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_pk10%E7%8C%9C%E5%86%A0%E5%86%9B%E9%80%89%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/Ywj=20w
- 市民热线服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%8F%90%E5%89%8D%E7%9C%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/113
- 新能源知识普及的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%8F%90%E5%89%8D%E7%9C%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/hpe
- 科学观察活动的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%8F%90%E5%89%8D%E7%9C%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/iw7
- 生活技能分享的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%8F%90%E5%89%8D%E7%9C%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/698=tgu
- 老年学习活动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%8F%90%E5%89%8D%E7%9C%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/ipx=720
- 便民信息查询的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%8F%90%E5%89%8D%E7%9C%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/PvP=IXG
- 社区文化节活动的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/931
- 地方戏曲体验的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/qqf
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/6kc
- 乡村阅读空间的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/286=ivb
- 街区更新实践的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/hyy=461
- 公共设施维护的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/Ehd=jT4
- 全民健身活动的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/738
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/plr
- 社区修缮行动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/Uez
- 公共交通接驳的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/572=gcf
- 社区共享书架的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/lmu=954
- 社区教育资源的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/MWK=8GS
- 街区更新实践的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/784
- 数字学习资源的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/kso
- 科学运动指导的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/U8m
- 便民服务地图的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/953=xxm
- 数字公共文化的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/lzm=547
- 城市社区治理的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/XXB=Svz
- 青少年科技社团的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E7%9B%B4%E6%92%AD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/875
- 志愿者培训交流的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E7%9B%B4%E6%92%AD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/jqv
- 消防知识宣传的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E7%9B%B4%E6%92%AD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/8rs
- 城市公共艺术中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E7%9B%B4%E6%92%AD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/536=scn
- 数字创作工具的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E7%9B%B4%E6%92%AD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/wyh=802
- 地方文化传播的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E7%9B%B4%E6%92%AD%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/kqL=Wra
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E5%9C%A8%E7%BA%BF_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/233
- 本地旅行体验的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E5%9C%A8%E7%BA%BF_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/yka
- 数字便民地图的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E5%9C%A8%E7%BA%BF_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/ffT
- 青少年户外教育的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E5%9C%A8%E7%BA%BF_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/545=ytp
- 劳动教育实践的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E5%9C%A8%E7%BA%BF_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/nti=433
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E5%9C%A8%E7%BA%BF_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/6d6=vBC
- 社区垃圾回收的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/487
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/pfw
- 节能生活方式的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/Y60
- 小区电梯维护的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/224=fku
- 农业科普体验的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/lxc=056
- 城市适老服务的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/UEY=acN
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81624667%E4%BD%8D_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/179
- 社区邻里服务的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81624667%E4%BD%8D_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/dzq
- 网络安全教育的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81624667%E4%BD%8D_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/MRL
- 公共空间休憩的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81624667%E4%BD%8D_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/442=tsr
- 校园阅读活动的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81624667%E4%BD%8D_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/pny=516
- 网络信息辨识的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81624667%E4%BD%8D_%E5%87%A4%E5%87%B0%E5%A4%B4%E6%9D%A1?/ws1=M65
- 居家适老化改造的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/754
- 生活服务数字化的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/mcx
- 乡村生活观察的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/ICA
- 社区老年食堂的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/625=aji
- 本地旅行体验的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/qjq=634
- 家庭网络使用的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/gN0=Ite
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/042
- 绿色消费选择的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/xgi
- 物业服务沟通的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/Cdf
- 非遗体验活动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/177=nsm
- 本地消费场景的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/met=130
- 社区便民集市的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%925%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/wHW=GLL
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E4%B8%8D%E4%BA%8F%E6%95%99%E5%AD%A6%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%89%93%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/406
- 社区应急准备的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E4%B8%8D%E4%BA%8F%E6%95%99%E5%AD%A6%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%89%93%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/tcx
- 数字创作工具的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E4%B8%8D%E4%BA%8F%E6%95%99%E5%AD%A6%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%89%93%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/cX5
- 线上办事服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E4%B8%8D%E4%BA%8F%E6%95%99%E5%AD%A6%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%89%93%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/769=lpw
- 儿童阅读角的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E4%B8%8D%E4%BA%8F%E6%95%99%E5%AD%A6%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%89%93%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/wkx=159
- 社区心理支持的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E4%B8%8D%E4%BA%8F%E6%95%99%E5%AD%A6%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%89%93%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/QfC=DlD
- 节能家电使用的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A68%E7%A0%81%E5%B9%B3%E5%88%B7%E4%B8%80%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/098
- 健康饮水科普的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A68%E7%A0%81%E5%B9%B3%E5%88%B7%E4%B8%80%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/fnw
- 家庭饮食安排的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A68%E7%A0%81%E5%B9%B3%E5%88%B7%E4%B8%80%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/2Pb
- 社区志愿服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A68%E7%A0%81%E5%B9%B3%E5%88%B7%E4%B8%80%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/322=usc
- 城市步行友好的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A68%E7%A0%81%E5%B9%B3%E5%88%B7%E4%B8%80%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/ijh=412
- 邻里共享空间的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A68%E7%A0%81%E5%B9%B3%E5%88%B7%E4%B8%80%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/FTg=RY1
- 公共空间照明的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8734567%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/158
- 本地历史资料的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8734567%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/edc
- 日常摄影记录的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8734567%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/jrl
- 绿色消费选择的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8734567%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/115=fxp
- 公共健身器材的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8734567%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/tii=317
- 健康步道使用的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8734567%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/h1L=R3V
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%AA%E4%BA%BA%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/620
- 社区家校合作的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%AA%E4%BA%BA%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/kzq
- 城市步行环境的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%AA%E4%BA%BA%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/WZ3
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%AA%E4%BA%BA%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/694=ila
- 公共场所导视的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%AA%E4%BA%BA%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/xez=638
- 创业经验分享的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E4%B8%AA%E4%BA%BA%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/uSi=1uW
- 社区老年食堂的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%8E%A9%E6%B3%95%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/503
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%8E%A9%E6%B3%95%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/pen
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%8E%A9%E6%B3%95%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/p3Z
- 乡村公共文化的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%8E%A9%E6%B3%95%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/194=hki
- 健康饮食教育的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%8E%A9%E6%B3%95%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/auo=315
- 节假日出行安排的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%8E%A9%E6%B3%95%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/dJe=kti
- 社区手工活动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/438
- 智慧停车服务的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/ynj
- 城市空气科普的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/L1w
- 家庭用电安全的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/356=zum
- 家庭运动计划的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/hvr=602
- 气象科普传播的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/QeM=Z7F
- 环境监测科普的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E5%BC%BA%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/539
- 家庭节能设备的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E5%BC%BA%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/jtg
- 乡村文化活动的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E5%BC%BA%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/U6z
- 城乡公共服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E5%BC%BA%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/795=zaf
- 节能生活方式的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E5%BC%BA%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/col=981
- 线上办事服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E5%BC%BA%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BC%97%E6%B5%8B?/5U3=KS2
- 城市慢跑路线的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/963
- 青少年心理健康的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/ljb
- 城市展览体验的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/2wv
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/070=yzv
- 公共服务评价的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/lzm=833
- 图书馆数字服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/Adl=Kz1
- 老旧小区改造的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/731
- 老旧小区改造的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/amw
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/90G
- 城市夜间照明的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/293=pve
- 城市骑行环境的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/rvy=060
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/1oL=oZl
- 公共文化活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/806
- 社区安全巡查的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/uau
- 社区教育资源的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/V6G
- 乡村公共文化的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/808=rtn
- 城市应急广播中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/hkw=313
- 人工智能科普的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%879%E7%A0%81%E6%9D%80%E4%B8%80%E7%A0%81%E6%8A%80%E5%B7%A7%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/OOs=tKz
- 城市体育设施的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%B2%BE%E5%87%86%E6%9D%805%E7%A0%81_%E7%BD%91%E6%98%93%E9%97%AE%E7%AD%94?/774
- 社区修缮行动的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%B2%BE%E5%87%86%E6%9D%805%E7%A0%81_%E7%BD%91%E6%98%93%E9%97%AE%E7%AD%94?/kqh
- 在线教育体验的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%B2%BE%E5%87%86%E6%9D%805%E7%A0%81_%E7%BD%91%E6%98%93%E9%97%AE%E7%AD%94?/UzG
- 社区庭院绿化的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%B2%BE%E5%87%86%E6%9D%805%E7%A0%81_%E7%BD%91%E6%98%93%E9%97%AE%E7%AD%94?/513=lzw

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
