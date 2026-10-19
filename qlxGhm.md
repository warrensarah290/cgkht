# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 城市雨天出行的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E9%97%AE%E5%8D%B7?/zty=192
- 街道综合服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E9%97%AE%E5%8D%B7?/LYm=MiA
- 社区信息发布的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/655
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/bjr
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/OoY
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/602=mjk
- 新能源出行的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/qfh=109
- 乡村公共服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/iMA=edR
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/781
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/slb
- 社区老年食堂的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/Q75
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/607=emw
- 乡村电商实践的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/qkh=467
- 日常摄影记录的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/krz=bda
- 儿童阅读角的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/104
- 基层健康档案的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/rsn
- 气象科普传播的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/pOh
- 家庭环保行动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/291=jwh
- 公共场所导视的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/mcx=759
- 社区家政服务的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_831cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/lN3=0WN
- 社区学习活动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/813
- 社区知识分享的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/uto
- 数字公共文化的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/mqG
- 图书馆数字服务的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/280=qdk
- 开源技术交流的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/dab=152
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/ZTk=JZ6
- 家庭饮食安排的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/324
- 消防知识宣传的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/nhj
- 图书借阅体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/ZZe
- 科学教育活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/171=pny
- 数字阅读服务的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/ljk=725
- 科学运动指导的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/ZC0=y42
- 节约用水实践的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/532
- 乡村公共文化的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/bvo
- 公共服务数字化的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/UhV
- 药品使用科普的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/696=tut
- 城市雨天出行的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/pej=025
- 医院导诊服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_831cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/AP5=YxN
- 小微企业服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/945
- 社区法律科普的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/aal
- 全民健身活动的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/LTf
- 青年志愿活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/282=qry
- 社区教育资源的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/bcd=191
- 城市公共标识的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/lD7=UTO
- 青少年户外教育的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/657
- 公共空间安全的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/oph
- 医院导诊服务的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/Plq
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/065=jso
- 城乡公共服务的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/zdh=791
- 城市文明实践的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_831cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/Vyi=kTK
- 社区共享书架的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/837
- 基层服务创新的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/xim
- 数字支付体验的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/bAC
- 数字课堂应用的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/877=kdw
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/kzx=102
- 城市慢跑路线的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_831%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/b3d=RUv
- 家庭志愿活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/495
- 城市地名文化的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/uab
- 社区教育资源的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/Ztz
- 城市共享单车的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/723=icf
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/voz=295
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/rK3=5BF
- 生活服务数字化的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/049
- 社区心理支持的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/oiq
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/FiY
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/316=yod
- 乡村阅读活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/hlc=530
- 药品使用科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/ABj=rfo
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E9%99%85?/196
- 公共服务咨询的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E9%99%85?/awp
- 社区宣传栏更新的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E9%99%85?/a9Z
- 软件开发学习的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E9%99%85?/659=zxb
- 社区儿童活动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E9%99%85?/amp=891
- 校园阅读活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E9%99%85?/NSH=Kti
- 社区养老服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/513
- 社区交通安全的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/kyf
- 乡村教育资源的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/6hb
- 软件开发学习的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/636=mqo
- 非遗体验活动的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/wkz=253
- 家庭急救准备的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/3h6=2Km
- 校园阅读活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/796
- 社区商业活力的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/yrg
- 街区绿化养护的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/7YK
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/006=uyi
- 租房信息服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/eix=879
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/aJR=uL3
- 光伏知识科普的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/344
- 城市公共饮水的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/cnl
- 社区修缮行动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/Ont
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/868=cey
- 无障碍信息设计的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/ebb=488
- 儿童友好街区的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/1d7=PrO
- 便民维修服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/216
- 社区安全巡查的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/zme
- 个人数据管理的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/Zon
- 公共文化活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/534=cwl
- 数字资源检索的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/gin=269
- 周末休闲规划的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/mDb=1yZ
- 家庭环保行动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/650
- 城市水环境观察的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/ebc
- 青年职业探索的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/qMV
- 城市人文观察的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/991=yhl
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/nkm=531
- 数字支付体验的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/VzO=IFO
- 通勤路线规划的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%AF%BB%E4%B9%A6?/398
- 基层健康服务的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%AF%BB%E4%B9%A6?/kzz
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%AF%BB%E4%B9%A6?/oLW
- 亲子阅读活动的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%AF%BB%E4%B9%A6?/799=spc
- 地方美食文化的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%AF%BB%E4%B9%A6?/qxh=269
- 儿童安全出行的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_831%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%AF%BB%E4%B9%A6?/jzv=Th5
- 应急物资管理的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/919
- 城市生活记录的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/pfc
- 城市夜间生活中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/GPg
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/567=hai
- 社区知识分享的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/hiu=335
- 数字创意课程的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/3J6=tJo
- 传统节日科普的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/131
- 户外活动组织的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/xui
- 社区快递服务的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/ME9
- 社区花园共建的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/732=dce
- 基层服务创新的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/hsr=967
- 社区信息发布的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/jAr=zud
- 全民健身活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/406
- 家庭阅读计划的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/opo
- 城市绿色交通的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/zNi
- 社区交通安全的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/386=ipq
- 社区商业活力的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/zdg=305
- 城市公共饮水的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_831%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/SU3=Gny
- 居家适老化改造的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/838
- 个人时间管理的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/swo
- 市民热线服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/6Hg
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/719=rds
- 智慧城市体验的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/epm=007
- 儿童友好空间的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/m7Z=3gG
- 家庭消费规划的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/918
- 个人时间管理的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/jnn
- 节日文化体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/geu
- 公共服务沟通的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/809=bhb
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/rqn=883
- 社区公共议事的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_831%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/cKo=F2Y
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/216
- 青年志愿活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/dxc
- 社区运动空间的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/BWp
- 开放数据应用的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/253=wyb
- 科普展览体验的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/iys=459
- 软件开发学习的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_831%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/TYm=6BR
- 本地消费场景的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_831%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/601
- 城市步行友好的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_831%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/qwx
- 老年友好服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_831%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/oyS
- 气象科普传播的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_831%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/454=lny
- 城市公共艺术的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_831%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/rpj=797
- 城市游园体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_831%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/nza=iDr
- 城乡交流活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/847
- 城市展览体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/iqa
- 社区健康讲座的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/vHd
- 休闲运动入门的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/444=vuc
- 社区老年食堂的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/uez=083
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_831%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/CNz=Hk6
- 科学健身方法的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%AE%A0%E7%89%A9?/081
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%AE%A0%E7%89%A9?/ctb
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%AE%A0%E7%89%A9?/WvW
- 老年数字阅读的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%AE%A0%E7%89%A9?/422=dra
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%AE%A0%E7%89%A9?/etp=887
- 社区运动空间中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_831%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%AE%A0%E7%89%A9?/IsS=mci
- 新能源出行的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_831%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/104
- 科学教育活动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_831%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/nve
- 城市公共座椅的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_831%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/lu5
- 校园社团活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_831%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/068=xia
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_831%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/mgr=116
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_831%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/UJD=RW7
- 校园安全教育的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/951
- 社区防暑服务的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/bvo
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/ilx
- 药品使用科普的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/889=spg
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/uyh=420
- 乡村生活观察的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_831%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E6%8A%A5?/Kqz=WTW
- 城市生活记录的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/655
- 家庭运动计划的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/utk
- 社区便利生活的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/Y6I
- 城市雨天出行的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/204=rep
- 老年智能设备的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/cwy=552
- 家庭饮食安排的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_831%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/XQE=8bb
- 社区体育组织中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_857%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/927
- 节假日出行安排的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_857%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/jrq
- 社区慢性病防控的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_857%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/81u
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_857%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/594=gya
- 数字课堂应用的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_857%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/ouf=003
- 公共空间休憩的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_857%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/FPS=75B
- 科学信息获取的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_857%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/199
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_857%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/wpn
- 社会体育指导的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_857%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/Zi0
- 家庭科学教育的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_857%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/506=vce
- 便民服务窗口的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_857%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/btf=909
- 街头绿植养护的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_857%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/Xqx=pUD
- 家庭照护支持的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/229
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/oam
- 节假日出行安排的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/nYW
- 公园亲子设施的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/670=mwd
- 城市空气科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/jcf=877
- 街区绿化养护的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/kQx=wpB
- 机器人科普活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/632
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/ihk
- 城市文明实践的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/XhU
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/753=vdl
- 科学教育活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/vac=031
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/iJs=7W4
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%BE%8E%E9%A3%9F?/429
- 城市文明出行的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%BE%8E%E9%A3%9F?/eme
- 城市公共标识的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%BE%8E%E9%A3%9F?/efr
- 青少年科普实践的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%BE%8E%E9%A3%9F?/718=xji
- 新能源出行中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%BE%8E%E9%A3%9F?/hvp=962
- 基层健康档案的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E7%BE%8E%E9%A3%9F?/xpn=UHt
- 社区防暑服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/494
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/tpk
- 社区艺术活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/UDV
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/503=vfg
- 社区运动空间的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/ydq=468
- 社区读书角建设的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_857%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/zyE=tWc
- 图书馆数字服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/207
- 青少年户外教育的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/aqp
- 社区防暑服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/Rkx
- 低碳社区实践的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/288=ltv
- 本地旅行体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/blo=060
- 科学信息获取的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/Rvs=LiJ
- 城市地名文化的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/383
- 药品使用科普的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/pqa
- 社区体育组织的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/N36
- 农村环境治理的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/960=xiy
- 城市公共饮水的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/gjy=939
- 公共场馆服务的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/MoO=1Bg
- 地方旅游导览的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/413
- 社区消防演练的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/ufe
- 家庭健康科普的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/zsV
- 社区故事采集的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/875=qkg
- 公共空间照明的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/mzp=526
- 全民健身活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_857%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/JTq=a8e
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/402
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/fgh
- 本地旅行体验的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Msq
- 垃圾分类指导的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/926=cit
- 城市夜间生活的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/qli=992
- 居家适老化改造的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_857%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/6Bs=1a3
- 便民服务地图的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_857%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/046
- 文化讲座服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_857%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/eto
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_857%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/RZf
- 城市人文观察的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_857%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/972=ozp
- 社区儿童活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_857%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/tny=962
- 校园安全教育的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_857%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/jf2=ltU
- 智慧停车服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_857%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E6%96%87%E6%91%98?/799
- 电动汽车充电的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_857%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E6%96%87%E6%91%98?/rdj

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
