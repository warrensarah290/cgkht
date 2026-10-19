# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:31**

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

- 城市博物馆活动的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/543
- 数字公共文化的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/acn
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/IaO
- 健康步道使用的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/565=hhl
- 社区活动空间的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/jrh=496
- 绿色快递包装的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/lXO=S5k
- 家庭健康管理的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/427
- 开源技术交流的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/amo
- 科学观察活动的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/pQS
- 就业技能培训的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/717=blx
- 数字素养提升的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/vfc=264
- 家庭收纳实践的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/16I=04m
- 公园休闲体验的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/076
- 青年就业服务的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/xcd
- 校园社团活动的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/6un
- 图书馆活动策划的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/954=bqj
- 城市建设科普的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/ohj=652
- 绿色出行服务的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/q9p=6Ri
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/570
- 城市公共自行车的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/vwg
- 城市社区治理的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/yTC
- 老年运动活动的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/139=jau
- 文化讲座服务的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/fpv=136
- 数字阅读服务的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/SAm=1Q5
- 网络信息辨识的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/016
- 乡村电商实践的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wsg
- 线上办事服务的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/1wr
- 数字创意课程的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/550=sji
- 家庭科学教育的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ofa=152
- 医院导诊服务的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/oeH=KTp
- 无障碍出行的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/843
- 社区健康讲座的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/xnb
- 社区信息发布的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/hHb
- 光伏知识科普的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/918=hir
- 社区科普课堂的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/cfu=763
- 本地旅行体验的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/3Ip=tOO
- 线上办事服务的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/363
- 城市可持续生活的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/vmh
- 城市水环境观察的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/Qfr
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/133=vka
- 文化讲座服务的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/dvx=258
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/9rd=wgP
- 家庭饮食安排的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/012
- 绿色生活实践的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/zuh
- 数字生活课堂的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/PIP
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/286=llw
- 城市地名文化的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/euq=265
- 学校食育活动的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/ORb=mMQ
- 社区宠物管理的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/764
- 城市绿色交通的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/dlq
- 街区道路维护的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/Mlm
- 创业经验分享的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/990=inx
- 节能生活方式的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/sbs=417
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/TQk=VMB
- 社区手工活动的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/781
- 社区快递服务的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/muo
- 科学健身方法的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/EFo
- 城市文明出行的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/742=pdj
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/xcf=855
- 绿色办公实践的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/uiy=GNI
- 社区快递服务的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/605
- 乡村文化空间中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/kyy
- 城市文明实践的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/FZD
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/950=fnp
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/eev=513
- 城市微更新实践的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E4%B8%93%E9%A2%98?/KHw=Wxa
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/661
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/die
- 社区活动报名的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/Vn8
- 公共健身器材的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/858=qvw
- 公共图书馆服务的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/kaw=455
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/2jm=Eoa
- 城市夜间生活的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/570
- 社区信息发布的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/dgq
- 社区应急准备的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/8ov
- 家庭收纳实践的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/467=cfz
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/ofw=032
- 居民健康教育的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/Ita=ndY
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/885
- 公共空间安全的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/zet
- 老旧小区改造的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/4dg
- 城市公共自行车的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/393=izv
- 城市树木认养的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/mag=020
- 农业科普体验的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/YGn=k7R
- 城市绿色交通的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/277
- 城市步行环境的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/eaa
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/d1b
- 老年运动活动的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/413=nfx
- 光伏知识科普的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/srr=057
- 城市展览体验的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%A7%91%E6%8A%80?/ldq=1Vo
- 无障碍出行的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/459
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/ztz
- 物业服务沟通的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/M2Q
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/175=cpe
- 公共图书馆服务的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/rjx=971
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/FpP=FrP
- 城市应急广播的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/356
- 小区公共照明的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/tml
- 休闲运动入门的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/GDx
- 乡村生活观察的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/690=gwd
- 社区菜市场服务的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/fdq=861
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/oP5=vQI
- 社区知识分享的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/583
- 家庭用电安全的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/icr
- 校园节能行动的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/J3j
- 城市文明出行的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/006=acf
- 城市公共艺术的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/dot=403
- 生活技能分享的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/9xf=xem
- 医院导诊服务的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/388
- 老年友好服务中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/djc
- 社区设施共享的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/DBf
- 城市空气科普的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/399=gef
- 城市建设科普的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/mck=779
- 节能家电使用的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/BeX=WXV
- 社区便利生活的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/264
- 公园无障碍服务的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/rtk
- 老年数字阅读的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/SZa
- 公益活动组织的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/129=qwq
- 数字创意课程的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/ona=820
- 图书借阅体验的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/GaD=GuU
- 老年数字阅读的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/954
- 社区协商议事的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/eoy
- 社区协商议事的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/9MB
- 公共服务预约的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/713=xgz
- 社区健康讲座的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/pzt=387
- 城市社区治理的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/zNe=ibF
- 城市应急广播的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/416
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/buu
- 城市游园体验的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/Yjp
- 读书会组织的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/583=cld
- 老年人文化生活的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/zdg=897
- 居家防滑改造的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/eHe=iCU
- 市民意见收集的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/299
- 社区家校合作的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/fyr
- 小微企业服务的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/deR
- 全民阅读推广的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/676=uyk
- 城市基础设施的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/qnn=630
- 骑行路线规划的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/cwX=aTz
- 公共文化活动的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/526
- 社区互助网络的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/ynf
- 生活服务数字化的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/MkF
- 公共设施维护的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/031=lua
- 社区科普课堂的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/yay=644
- 乡村公共服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/2Ce=aPo
- 乡村文化空间的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/083
- 节假日出行安排的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/bux
- 乡村文化空间的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/CBL
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/017=fek
- 青少年户外教育的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/gfw=391
- 图书馆活动策划的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/z7f=YcU
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/270
- 职业技能学习的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/czu
- 公共服务指南的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/D0X
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/974=wtp
- 城市应急广播的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/xws=782
- 城市体育设施的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/InP=ALG
- 家庭节能实践的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/704
- 绿色消费选择的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/bmo
- 居民健康教育的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/3IO
- 消防知识宣传的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/028=xvf
- 乡村阅读空间的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/ryf=679
- 节假日出行安排的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/tKW=b6y
- 市民热线服务的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/038
- 基层健康档案的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/oon
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/bLO
- 社区公共卫生的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/899=ezt
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/bwf=714
- 社区设施共享的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%AF%8D%E5%A9%B4?/IgL=UeX
- 数字创意课程的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/304
- 校园阅读活动的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/pkl
- 城市游园体验中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/k48
- 公共服务咨询的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/524=afb
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/sxy=082
- 邻里共享空间的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/oFK=TSj
- 城市博物馆服务的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E4%B8%93%E9%A2%98?/207
- 街区绿化养护的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E4%B8%93%E9%A2%98?/fcc
- 社区设施共享的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E4%B8%93%E9%A2%98?/4tX
- 社区故事采集的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E4%B8%93%E9%A2%98?/258=yok
- 机器学习入门的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E4%B8%93%E9%A2%98?/hpr=149
- 运动安全知识的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E4%B8%93%E9%A2%98?/hgP=crb
- 生活服务数字化的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/832
- 地方戏曲体验的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/xad
- 城市公共空间的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/qLk
- 社区公共卫生的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/373=cih
- 数字支付体验中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/akd=019
- 灵活就业交流的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/cRd=uUU
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/638
- 城市展览体验的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/ehn
- 社区安全巡查的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/CyQ
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/415=unn
- 网络信息辨识的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/xyn=626
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/53Q=mXB
- 科学运动指导的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/765
- 乡村生活观察的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/ovh
- 家庭科学教育的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/DqV
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/816=knh
- 城市建设科普的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/ckx=745
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/Z3a=rKQ
- 便民维修服务的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/744
- 城市步行友好中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/ywt
- 家庭教育交流的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/pc3
- 数字支付体验的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/437=bje
- 社区应急准备的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/crq=319
- 非遗体验活动的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/fiD=Zda
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/188
- 社区生活指南的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/lsw
- 老年友好服务的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/8D8
- 城市公共座椅的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/126=dhz
- 便民服务地图的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/sxe=883
- 小区公共照明的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/7O2=45m
- 青少年心理健康的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/497
- 公共空间休憩的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/bsv
- 家庭节能实践的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/nvG
- 智慧城市体验的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/268=xpo
- 社区艺术活动的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/zlu=126
- 数字生活课堂的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/6h1=ksp
- 公共服务评价的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/244
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/ntb
- 数字支付体验的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/HAh
- 小微企业服务的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/147=hgt
- 志愿者培训交流的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/rlg=102
- 公共服务数字化的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/FZj=Ixe
- 地方文化传播的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/233
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/axc
- 社区体育组织的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/o1Z
- 个人时间管理的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/894=byn
- 电动汽车充电的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/wrc=374
- 志愿者培训交流的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/T4w=RC9
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/424
- 生活技能分享的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/hnq
- 急救知识普及的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/WMF
- 旧物循环利用的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/147=qfj
- 数字阅读服务的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/big=647
- 城市住房服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/xlW=LMn
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/785
- 社区邻里服务的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/liw
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/lq6
- 本地消费场景中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/807=lli
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/cpm=044
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/4Us=jpp
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E6%B2%BB?/372
- 儿童阅读角中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E6%B2%BB?/xit
- 急救知识普及的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E6%B2%BB?/kkz
- 文明养宠科普的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E6%B2%BB?/154=cuj
- 儿童运动体验的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E6%B2%BB?/zit=383
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E6%B2%BB?/Cfc=Fdt
- 社区商业活力的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/483
- 城市休闲步道的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/ybc
- 地方美食文化的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/aGq
- 公共空间照明的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/096=egh

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
