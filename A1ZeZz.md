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

- 零废弃生活尝试的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A68%E7%A0%81%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/oxn=342
- 社区体育组织的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A68%E7%A0%81%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/Rw5=QIW
- 城市文明出行的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_360%E8%BE%9F%E8%B0%A3?/986
- 科学健身方法的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_360%E8%BE%9F%E8%B0%A3?/bns
- 家庭饮食安排的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_360%E8%BE%9F%E8%B0%A3?/oYT
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_360%E8%BE%9F%E8%B0%A3?/680=ekh
- 地方美食文化的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_360%E8%BE%9F%E8%B0%A3?/hwb=540
- 城市博物馆服务的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_360%E8%BE%9F%E8%B0%A3?/LfJ=XRt
- 电子商务服务的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/318
- 线上办事服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/pzi
- 社区法律科普的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/x9e
- 智慧城市体验的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/490=hth
- 智能手机助老的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/fhp=067
- 医院导诊服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/uup=FxM
- 小区电梯维护的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B9%9D%E7%A0%81%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/088
- 灵活就业交流的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B9%9D%E7%A0%81%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/ljo
- 社区安全巡查的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B9%9D%E7%A0%81%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/I7X
- 公共卫生设施的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B9%9D%E7%A0%81%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/408=pvi
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B9%9D%E7%A0%81%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/bgi=857
- 非遗体验活动的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B9%9D%E7%A0%81%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/e6L=Ku3
- 社区协商议事的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/707
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/oei
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/G9R
- 社区养老服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/317=jdf
- 节气饮食文化的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/sqc=552
- 节假日出行安排的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/ETu=rLx
- 远程协作工具中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/775
- 志愿服务平台的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/hkr
- 城市适老服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/1y9
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/585=dad
- 校园安全教育的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/jhq=917
- 户外活动组织的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/qX5=DOT
- 图书馆数字服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/478
- 休闲运动入门的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/npd
- 儿童友好空间的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/qHm
- 社区花园共建的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/804=kqa
- 垃圾分类指导的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/tof=363
- 社区教育资源的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/35z=Pju
- 社区垃圾回收的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92QQ_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/583
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92QQ_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/sto
- 在线学习体验的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92QQ_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/ZMv
- 社区文化传播的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92QQ_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/942=ost
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92QQ_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/kew=693
- 家庭健康管理的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92QQ_%E5%A4%B4%E6%9D%A1%E8%AE%BA%E5%9D%9B?/iBH=hnp
- 家庭用电安全的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%89%E7%A0%81%E8%AE%A1%E5%88%92%E5%9B%BE%E8%A7%A3_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/523
- 校园社团活动的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%89%E7%A0%81%E8%AE%A1%E5%88%92%E5%9B%BE%E8%A7%A3_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/pwv
- 节能生活方式的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%89%E7%A0%81%E8%AE%A1%E5%88%92%E5%9B%BE%E8%A7%A3_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/Lmj
- 图书借阅体验的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%89%E7%A0%81%E8%AE%A1%E5%88%92%E5%9B%BE%E8%A7%A3_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/869=cgx
- 社区便民集市的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%89%E7%A0%81%E8%AE%A1%E5%88%92%E5%9B%BE%E8%A7%A3_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/mbg=381
- 数字设备回收的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%89%E7%A0%81%E8%AE%A1%E5%88%92%E5%9B%BE%E8%A7%A3_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/i2m=mIH
- 社区休闲设施的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%9C%9F%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/628
- 乡村生态观察的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%9C%9F%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/kpl
- 家庭照护支持的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%9C%9F%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/6ip
- 儿童户外活动的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%9C%9F%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/247=ezu
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%9C%9F%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/niu=987
- 乡村教育资源的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%9C%9F%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/LLS=1Il
- 社区体育组织的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/150
- 社区文化传播的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/cgc
- 新能源出行的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/hrp
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/852=snj
- 社区儿童活动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/esr=506
- 软件开发学习的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/Zei=frV
- 地方文化传播的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/525
- 新能源出行从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/ujn
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/t5b
- 本地历史资料的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/699=dbl
- 城市公共自行车的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/axu=683
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/bwF=IBs
- 城市水环境观察的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/728
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/ain
- 社区阅读服务的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/aeo
- 乡村生活观察的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/270=izm
- 社区互助网络的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/wrs=060
- 居家适老化改造的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/l9V=QPc
- 城市共享单车的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/437
- 公共场所导视的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/uzw
- 家庭节能实践的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/9qB
- 城市公共空间的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/336=gdv
- 公共服务指南的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/gpp=046
- 儿童运动体验的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%B4%A2%E6%8A%A5?/I3J=KqU
- 街区更新实践的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/078
- 药品使用科普的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/exh
- 远程协作工具的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/X6j
- 城市应急科普的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/492=pzu
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/drg=616
- 社区垃圾分类的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%B4%E6%92%AD?/TwY=wWi
- 数字设备回收的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_6%E7%A0%81%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/446
- 生活技能分享的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_6%E7%A0%81%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/bqm
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_6%E7%A0%81%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/2uH
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_6%E7%A0%81%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/514=nzd
- 公共设施维护的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_6%E7%A0%81%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/fog=244
- 城市步行友好的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_6%E7%A0%81%E8%B5%9B%E8%BD%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/fRB=63y
- 乡村产业科普的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E9%AB%98%E6%89%8B%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/082
- 乡村文化空间的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E9%AB%98%E6%89%8B%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/efd
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E9%AB%98%E6%89%8B%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/GNy
- 家庭节能实践的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E9%AB%98%E6%89%8B%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/980=aoc
- 健康信息获取的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E9%AB%98%E6%89%8B%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/ajz=258
- 社区安全巡查的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E9%AB%98%E6%89%8B%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/HBz=1zT
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/361
- 数字设备回收的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/xhj
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/P17
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/948=gkr
- 环境教育课程的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/cpv=396
- 乡村文化活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/7cV=hQs
- 家庭饮食安排的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/808
- 机器学习入门的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/cko
- 社区互助网络的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/g1E
- 城市文化路线的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/894=jbt
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/uew=801
- 传统节日科普的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/AIv=Ctj
- 家庭饮食安排的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%921%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/332
- 数字设备回收的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%921%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/vpa
- 绿色生活实践的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%921%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/Siy
- 软件开发学习的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%921%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/265=epy
- 社区消防演练的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%921%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/ale=671
- 城市便民驿站的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%921%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/MPb=BaO
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_1%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/528
- 公交无障碍服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_1%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/tff
- 老年友好服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_1%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/2iO
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_1%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/639=owo
- 开放式学习空间中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_1%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/txd=064
- 公共空间照明的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_1%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/QlO=km6
- 街区小店体验的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/650
- 城市骑行环境的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/dey
- 在线学习体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/nOz
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/971=bfa
- 数字支付体验的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/inz=192
- 低碳社区实践的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A6%81%E9%97%BB?/mSK=Cnd
- 公共服务评价的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/920
- 智能手机助老的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/wnv
- 社区协商议事的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/j2u
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/387=gil
- 科学信息获取的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/kdt=506
- 城市运动公园的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/rNN=PPS
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/925
- 社区活动报名的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/aob
- 家庭防灾准备的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/EXN
- 公共文化活动的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/870=hfh
- 图书馆活动策划的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/ttg=086
- 亲子科普活动的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/5SW=OyD
- 骑行路线规划的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/234
- 街区道路维护的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/dru
- 运动安全知识的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/E5h
- 社区花园共建的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/919=uqg
- 软件开发学习的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/pdt=546
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/Hqb=0ym
- 社区花园共建的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/092
- 城市噪声观察的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/sra
- 家庭急救准备的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/mkS
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/053=wxr
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/ppx=752
- 城市公共座椅的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/fbY=OCc
- 城市绿道建设的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/071
- 城市农夫市集的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/lmj
- 农产品品牌传播的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/erl
- 公共服务数字化的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/083=uum
- 网络安全教育的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/lee=303
- 节气饮食文化的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/luo=6aE
- 城市公共饮水的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/340
- 人工智能科普的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/apc
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/sZp
- 地方文化传播的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/355=dla
- 在线教育体验的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/egp=429
- 地方旅游导览的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/JDP=gDc
- 儿童运动体验的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/481
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/bps
- 社区交通安全的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/Zzo
- 急救知识普及的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/047=xug
- 城市公共自行车的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/npu=336
- 社区活动策划的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/RI2=eDw
- 乡村阅读空间的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/879
- 地方旅游导览的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/vjx
- 城乡交通衔接的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Uu8
- 本地旅行体验的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/829=jdr
- 数字素养提升的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/grx=056
- 软件开发学习的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Se1=Gq7
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/906
- 城市人文观察的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/ssa
- 绿色办公实践的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/jBB
- 城市地名文化的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/000=lwf
- 电子商务服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/xjq=182
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/V93=4S1
- 城市夜间照明的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/810
- 城市步行友好的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/nbr
- 邻里互助活动的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/6KV
- 城市共享单车的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/087=jwx
- 城市文明出行的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/ctg=145
- 线上阅读资源的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/ETS=XKv
- 便民维修服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/201
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/bzb
- 个人信息保护的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/cfJ
- 社区活动空间的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/884=kkn
- 创业经验分享的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/wls=295
- 生成式工具使用的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%A2%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/ItM=NDV
- 城市文化路线的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/124
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/juo
- 城市便民驿站的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/xUK
- 街区更新实践的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/771=nix
- 社区活动空间的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/meh=032
- 家庭健康科普的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/NpE=Cdl
- 气象科普传播的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E4%BB%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/982
- 节日文化体验的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E4%BB%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/xoi
- 社区知识分享的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E4%BB%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/mBI
- 社区休闲设施的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E4%BB%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/698=gyy
- 社区邻里服务的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E4%BB%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/qkh=181
- 城市基础设施的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E4%BB%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/su1=qHF
- 通勤路线规划的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E7%8E%A9_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/703
- 社区家校合作的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E7%8E%A9_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/esc
- 城市共享单车的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E7%8E%A9_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/Jvz
- 公共文化活动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E7%8E%A9_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/267=evw
- 食品安全科普的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E7%8E%A9_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/ayn=546
- 社区养老服务的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E7%8E%A9_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/TIu=dTP
- 数字地图应用的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/474
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/grf
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/Vcz
- 城市慢行系统的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/386=eed
- 老年数字阅读的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/bmk=451
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E5%85%9A%E5%BB%BA?/UTL=zdl
- 社区交通安全的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/043
- 气象科普传播的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/lda
- 社区学习活动的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/16W
- 数字生活课堂的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/924=odz
- 文化讲座服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/hed=138
- 本地消费场景的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/SR3=PyI
- 社区协商议事的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/376
- 青年职业探索的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/edo
- 环境教育课程的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/Mnb
- 家庭理财科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/074=zni
- 社区艺术活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/afo=938
- 非遗体验活动的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/1AG=9vG
- 农贸市场环境的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%B4%B4%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/458
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%B4%B4%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/fgs
- 青少年心理健康的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%B4%B4%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/eok
- 社区老年食堂的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%B4%B4%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/331=wep
- 家庭消费规划的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%B4%B4%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/xuc=886
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%B4%B4%E5%90%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/BL8=GjY
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/914
- 基层健康档案的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/zsi
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/LH6
- 非遗体验活动的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/279=whg
- 青少年编程学习的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/fqn=433
- 无障碍信息设计的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/mrl=6G7
- 新能源出行中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/153
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/jvk
- 社区便利生活的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/GLZ
- 城市应急科普的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/718=vsr
- 智慧停车服务的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/yli=023
- 社区读书角建设的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/fvg=PtR
- 乡村公共阅读的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E8%B5%9B%E8%BD%A6%E4%B8%93%E4%B8%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/545
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E8%B5%9B%E8%BD%A6%E4%B8%93%E4%B8%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/ajh

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
