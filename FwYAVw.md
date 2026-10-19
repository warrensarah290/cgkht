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

- 社区设施共享的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/vPF
- 公共健身器材的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/726=isw
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/gnn=128
- 便民信息查询的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/4Bn=hRT
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/625
- 青年职业探索的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/oph
- 乡村教育资源的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/O41
- 城市应急广播的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/565=jgl
- 健康步道使用的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qdh=167
- 城市空气科普的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8E%8C%E6%8F%A1%E6%8A%80%E5%B7%A7_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/2mJ=a3j
- 社区互助网络的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/265
- 校园社团活动的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/qcp
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/v2Z
- 网络安全教育的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/000=vyc
- 青少年科普实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/rku=761
- 科学教育活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/yaN=zwc
- 公共文化活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/729
- 电动汽车充电的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/nkg
- 城市夜间照明的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/A5u
- 城市公共标识的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/813=zlt
- 安全出行教育的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/kkw=916
- 社区活动空间的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E6%9C%80%E7%B2%BE%E5%87%86%E7%9A%84%E8%80%81%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/dit=cmc
- 城市文化路线的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/050
- 社区公共议事的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/lcp
- 街区绿化养护的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/2NY
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/577=lar
- 在线学习体验的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/lhy=286
- 亲子科普活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/Prf=88f
- 家庭运动计划的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/000
- 城市公共饮水的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/cws
- 传统节日科普的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/C05
- 公共服务沟通的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/546=agw
- 灵活就业交流的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/brw=159
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E6%9C%89%E6%95%88%E7%9A%84%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/9Tv=QQn
- 公共服务沟通的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/877
- 数字创意课程的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/nxo
- 软件开发学习的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/QKp
- 基层健康档案的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/878=xdu
- 社区活动报名的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/tnf=914
- 城市噪声观察的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/iwF=cpj
- 青年志愿活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/174
- 地方旅游导览的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/ktp
- 城市步行友好的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/KMi
- 公共设施使用的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/291=cuw
- 软件开发学习的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/psy=552
- 校园节能行动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2022%E6%9C%80%E6%96%B0%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/K9M=X1r
- 街头绿植养护的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/727
- 急救知识普及的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/glc
- 家庭节能设备中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/n1W
- 居家适老化改造的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/974=akg
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/nsq=093
- 社区防暑服务的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E5%B0%9A?/4yY=bUu
- 社区防暑服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/481
- 旧物循环利用的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/kxw
- 文明养宠科普的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/ia6
- 社区托育服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/671=sxa
- 社区学习活动的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/yje=721
- 社区应急准备的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/UfS=qaw
- 青少年心理健康的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/489
- 家庭环保行动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/yhl
- 城市噪声观察的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/lbY
- 青年志愿活动的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/318=hns
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/qme=408
- 社会体育指导的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/qH5=Zq1
- 机器人科普活动的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/484
- 科学信息获取的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/ccp
- 数字学习资源的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/6P7
- 数字公共文化的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/392=zmf
- 基层服务创新的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/upy=184
- 便民服务地图的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/FxJ=4al
- 生活服务数字化的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/827
- 地方民俗记录的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/ojx
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/o5l
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/402=rck
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/ohy=967
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/smm=lJm
- 绿色生活实践的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/169
- 社区便民服务的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/jsv
- 节能生活方式的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/6A3
- 学校食育活动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/131=cpr
- 食品配送体验的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/can=578
- 线上阅读资源的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/XeX=7kp
- 家庭运动计划的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/902
- 健康步道使用的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/fen
- 家庭科学教育的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/ced
- 数字便民地图的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/181=mbz
- 绿色消费选择的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/cpb=231
- 旧物循环利用的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/fIO=VIF
- 社区手工活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/869
- 基层服务创新的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/xct
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/Fga
- 公共服务预约的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/054=grh
- 家庭环保行动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/rdk=983
- 创业经验分享的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/UtM=TeN
- 社区垃圾分类的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/282
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/tjy
- 非遗体验活动的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/Exv
- 环境教育课程的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/538=ktz
- 社区教育资源的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/sgo=755
- 社区家政服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%95%99%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/6YL=1ag
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/154
- 社区菜市场服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/pqu
- 节能生活方式的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/L69
- 公共服务指南的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/637=tym
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/ael=599
- 社区教育资源的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/3LH=2GZ
- 社区休闲设施的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/998
- 数字公共文化的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/psc
- 节气饮食文化的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/Kqe
- 青年就业服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/582=jmf
- 农业科普体验的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/ssw=386
- 老年智能设备的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E5%AF%BC%E5%B8%88%E8%AE%B2%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/Xd1=v02
- 数字地图应用的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_360%E5%9C%B0%E4%BA%A7?/879
- 城市体育设施的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_360%E5%9C%B0%E4%BA%A7?/fba
- 公园休闲体验的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_360%E5%9C%B0%E4%BA%A7?/9cf
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_360%E5%9C%B0%E4%BA%A7?/761=sgy
- 图书借阅体验的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_360%E5%9C%B0%E4%BA%A7?/uym=443
- 节假日出行安排的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_360%E5%9C%B0%E4%BA%A7?/1ts=rUg
- 城市休闲步道的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/149
- 机器人科普活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/bdo
- 应急物资管理的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/vv4
- 农村环境治理的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/982=afo
- 市民意见收集的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/plb=710
- 环境监测科普的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%A2%E7%8E%A9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/U01=Jxa
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/177
- 智能手机助老中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/okl
- 乡村电商实践的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/w0N
- 家庭用电安全的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/598=fjc
- 周末休闲规划的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/lfj=386
- 个人数据管理的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/Fol=vm1
- 口袋公园建设的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/626
- 租房信息服务的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/vpc
- 劳动教育实践的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/aQb
- 乡村生态旅游的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/069=sxi
- 社会体育指导的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/fce=465
- 青少年心理健康的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/9C1=z9L
- 数字政务体验的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/877
- 本地旅行体验的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/dpd
- 物业服务沟通的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/jaF
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/243=lvx
- 应急物资管理的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/vrp=939
- 社区公共卫生的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%9C%A8%E5%B9%B3%C2%B7%E5%8F%B0%E8%BE%93%E4%BA%86%E9%92%B1%E5%A6%82%E4%BD%95%E8%A6%81%E5%9B%9E%E6%9D%A5_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/WaI=lEh
- 全民健身活动的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/274
- 城乡交流活动的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/fga
- 社区文化节活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/fAF
- 老年人日常照护的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/386=xdy
- 社区宠物管理的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/mjj=746
- 社会体育指导的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/W3x=L9D
- 家庭饮食安排的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/361
- 社区慢性病防控的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/cdb
- 绿色生活实践的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/d1c
- 社区宠物管理的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/115=qcx
- 文明养宠科普的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/gcq=991
- 社区健康讲座的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E6%9C%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/Hob=5o3
- 社区商业活力的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/394
- 社区活动空间的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/grq
- 社区花园共建的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/z91
- 校园节能行动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/254=eth
- 生活垃圾减量的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/rul=038
- 公共服务数字化的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9B%E7%A7%8D%E5%B8%B8%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/DMk=tcg
- 老年友好服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/753
- 城市雨天出行的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/oiz
- 数字学习资源的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/bTE
- 社区养老服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/669=gnp
- 公园休闲体验的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/dpb=685
- 乡村阅读活动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/6NF=Ae1
- 城市步行友好的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85?/911
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85?/ykj
- 社区设施共享的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85?/gBf
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85?/246=ohi
- 社区知识分享的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85?/qbb=256
- 地方民俗记录的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E9%9C%80%E8%A6%81%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85?/6nY=rsk
- 骑行路线规划的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/066
- 青年职业探索的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/xfr
- 绿色快递包装的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/dSv
- 亲子阅读活动的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/982=hxm
- 健康步道使用的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/ycl=357
- 非遗课堂体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/qdL=4Jr
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/536
- 个人信息保护的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/xtl
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/8UT
- 数字创意课程的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/132=ocy
- 环境教育课程的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/hgu=639
- 本地消费场景的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_1%E5%88%86%E9%92%9F%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/mtr=Njt
- 老年人日常照护的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/688
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/rtq
- 家庭环保行动的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/J29
- 儿童户外活动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/842=xeu
- 本地消费场景的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/cqe=721
- 健康步道使用的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/b86=veJ
- 健康饮食教育的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/721
- 数字政务体验的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/snq
- 社区商业活力的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/H4z
- 本地旅行体验的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/434=qqy
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/abb=262
- 社区邻里服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E9%AB%98%E6%89%8B%E5%B8%A6%E6%88%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/FII=03U
- 非遗体验活动的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/864
- 气象科普传播的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/cve
- 社区故事采集的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/KUt
- 数字档案服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/167=mwg
- 便民信息查询的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/hte=177
- 青少年心理健康的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/oIt=cSJ
- 儿童运动体验的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%89%80%E8%B0%93%E7%9A%84%E9%82%A3%E4%BA%9B%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/292
- 社区养老服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%89%80%E8%B0%93%E7%9A%84%E9%82%A3%E4%BA%9B%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/rjh
- 科学运动指导的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%89%80%E8%B0%93%E7%9A%84%E9%82%A3%E4%BA%9B%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/MqK
- 节能家电使用的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%89%80%E8%B0%93%E7%9A%84%E9%82%A3%E4%BA%9B%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/835=pli
- 数字生活课堂的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%89%80%E8%B0%93%E7%9A%84%E9%82%A3%E4%BA%9B%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/xej=315
- 社区信息发布的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%89%80%E8%B0%93%E7%9A%84%E9%82%A3%E4%BA%9B%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/WrY=Tb1
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/192
- 便民维修服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/tha
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/7Rc
- 社区养老服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/482=lnv
- 文明养宠科普的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/gmc=488
- 城市微更新实践的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/XVn=EV4
- 青少年科普实践的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BE%A4_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/699
- 城市基础设施的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BE%A4_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/afs
- 课后服务体验的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BE%A4_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/2C9
- 社区法律科普中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BE%A4_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/812=jiq
- 社区便利生活的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BE%A4_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/isf=226
- 社区手工活动的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BE%A4_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/KU1=v5t
- 食品安全科普的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/505
- 城市文化路线的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/jii
- 儿童友好街区的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/1E7
- 家庭健康管理的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/489=eua
- 日常摄影记录的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/das=539
- 社区安全巡查的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/Hz5=cPO
- 老年运动活动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/767
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/eha
- 节约用水实践的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/hJu
- 日常摄影记录的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/409=maa
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/oyb=180
- 周末休闲规划的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%95%85%E6%B8%B8?/qYc=wr8
- 家庭环保行动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88qq_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/060
- 智能家居应用的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88qq_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/ufx
- 城市夜间照明的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88qq_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/vx9
- 社区邻里服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88qq_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/846=eyz
- 社区家政服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88qq_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/hkp=234
- 绿色出行服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88qq_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/OKS=w01
- 开放数据应用的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/263
- 公交站点体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/cfz
- 社区便民集市的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/f50
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/588=uud
- 社区商业活力的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/gkf=952
- 小区停车协商的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/yWW=DPL
- 家庭防灾准备的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/945
- 城市绿道建设的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/wxt
- 读书会组织的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/XbI
- 城市夜间生活的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/465=fnl
- 小微企业服务中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/tyx=565
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/3rb=HDm

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
