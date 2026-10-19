# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 小微企业服务的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/SRC
- 无障碍出行的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/193=fyl
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/hgg=260
- 城市绿色交通的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/5wV=LJc
- 青少年心理健康的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/824
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/tmj
- 社区慢性病防控的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/5cg
- 线上办事服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/116=bip
- 个人时间管理的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/orc=165
- 数字创意课程的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/ijv=vA8
- 公交站点体验的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/459
- 传统节日科普的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/yho
- 社区安全巡查的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/0P0
- 个人数据管理的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/493=wdb
- 城市住房服务的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/bzp=029
- 口袋公园建设的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/rgP=Fkn
- 公共设施维护的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/725
- 社区停车服务的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/kix
- 小区停车协商的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/lT2
- 公共设施使用的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/600=tdi
- 社区快递服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/nly=711
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/2ql=8jo
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/266
- 社区公共卫生的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/czb
- 家庭饮食安排的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/x3G
- 节约用水实践的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/483=uaw
- 小区停车协商的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/nre=318
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/HOZ=Oue
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/377
- 租房信息服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/xrl
- 医院导诊服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/OAH
- 便民信息查询的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/489=kbz
- 邻里互助活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/tnx=192
- 公共文化活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/Mlk=Y10
- 城市应急广播的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/454
- 儿童阅读角的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/vuw
- 家庭健康管理的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/YjS
- 乡村文化空间的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/562=ple
- 光伏知识科普的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/ext=243
- 社区共享书架的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/5xu=Na8
- 青年就业服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/822
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/zsu
- 基层医疗预约的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/FLu
- 乡村公共文化的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/799=zlq
- 基层健康档案的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/kdt=185
- 家庭教育交流的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/nRT=t7O
- 城市绿色交通的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/488
- 智能手机助老的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/nvf
- 个人时间管理中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/ODT
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/556=oak
- 数据分析入门中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/mcw=648
- 地方美食文化的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/K96=flv
- 远程协作工具的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/348
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/xqd
- 社区公共卫生的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/YRq
- 社区儿童活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/642=gim
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/nlh=436
- 开放数据应用的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/hdG=apx
- 休闲运动入门的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90?/721
- 家庭运动计划的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90?/vnu
- 社区志愿服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90?/hrO
- 数据分析入门的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90?/589=muc
- 家庭防灾准备的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90?/qjr=878
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90?/pmN=Yw5
- 社区读书角建设的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/836
- 公交站点体验的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/qsv
- 社区花园共建的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/rRl
- 家庭节能实践的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/495=uix
- 城市应急广播的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/sqi=482
- 食品安全科普的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/vQI=Ivn
- 家庭科学教育的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/454
- 读书会组织的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/sfh
- 创业经验分享的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/xXt
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/014=mow
- 无障碍出行的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/wkb=661
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/6e6=cHt
- 公园休闲体验的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/512
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/dmq
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/zWV
- 数字生活课堂的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/079=odx
- 城市地名文化的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/wdz=487
- 公园亲子设施的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/8oX=eNF
- 公共交通接驳的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/132
- 社区艺术活动的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/jan
- 休闲运动入门的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/aOv
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/096=nqq
- 城市步行友好的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/dod=417
- 社区艺术活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/m0f=dSE
- 城市夜间照明中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/326
- 乡村公共服务的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/qyu
- 社区文化节活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/Z1l
- 个人时间管理的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/818=nse
- 老旧小区改造的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/qcg=746
- 公共设施维护的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/JIM=7MH
- 家庭园艺实践的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/899
- 灵活就业交流的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/xez
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/tdV
- 公共卫生宣传的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/090=ndn
- 社区活动策划的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/fkw=158
- 远程协作工具的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/EvH=s8t
- 城市可持续生活的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/603
- 公共服务预约的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/hgu
- 本地旅行体验的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/J2p
- 社区故事采集的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/037=wor
- 数字设备回收的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/zii=603
- 应急物资管理的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/o2G=e1D
- 节能生活方式的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/831
- 儿童友好空间的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/wrv
- 城市文明出行的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/0Xh
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/524=vlt
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/sia=557
- 社区老年食堂的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/Z9e=bEP
- 跨代沟通活动的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/943
- 社区老年食堂的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/mnr
- 无障碍信息设计的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/P0j
- 城市基础设施的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/948=mgh
- 乡村文化活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/lar=279
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/p9N=JV7
- 家庭消费规划的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/067
- 街道综合服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/kho
- 城市文化路线的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/XBc
- 学校食育活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/797=elk
- 亲子科普活动的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/efz=832
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A6%9C%E5%8D%95?/Lgf=ia0
- 创业经验分享的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/015
- 城市人文观察的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/lrc
- 基层医疗预约的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/ZlS
- 数字创意课程的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/393=vli
- 乡村生活观察的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/cwm=650
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/C6H=Yfi
- 地方美食文化的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/690
- 公益活动组织的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/hme
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/U8o
- 社区阅读服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/723=cez
- 城市农夫市集的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/xzw=784
- 社区体育组织的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/9Ck=bxt
- 城市住房服务的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/592
- 网络信息辨识的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/fxb
- 居家适老化改造的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/niJ
- 应急物资管理的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/242=ljz
- 绿色消费选择的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/qld=045
- 社区养老服务的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/9WS=GGN
- 城市绿色交通的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/621
- 社区故事采集的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/sqz
- 家庭节能设备的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/QN7
- 网络安全教育的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/780=srr
- 校园节能行动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/yjn=634
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/RAl=iaV
- 社区垃圾回收的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/615
- 家庭陪伴活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/wmh
- 口袋公园建设的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/gDy
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/327=iaw
- 老年友好服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/ppg=365
- 个人数据管理的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/LIq=WnX
- 乡村文化活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/169
- 社区心理支持中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/ahk
- 数字素养提升的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/jzE
- 数字公共文化的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/115=olt
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/vps=971
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/8iO=DoE
- 公共设施维护的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/873
- 远程协作工具的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/cae
- 城市慢行系统中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/JbF
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/550=ruv
- 社区科普课堂中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/xrj=702
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/7fs=u8Q
- 社区科普课堂的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/481
- 家庭节能实践的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/fbr
- 城市树木认养的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/zXs
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/271=meg
- 网络安全教育的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/nla=255
- 个人数据管理的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/k9k=yBH
- 农村环境治理的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/444
- 公共场馆服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/sxp
- 城乡公共服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/Tis
- 智慧城市体验的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/480=atc
- 开放式学习空间的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/gwa=098
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/IEK=V9S
- 公园休闲体验的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/735
- 社区环保活动的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/kzp
- 个人时间管理的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/qDv
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/844=ovd
- 社区手工活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/hrl=349
- 老年人日常照护的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/yhy=Aql
- 数字资源检索的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/993
- 社区学习活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/khu
- 城市基础设施的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/Kwr
- 城市公共厕所的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/043=zwy
- 社区商业活力的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/ipj=647
- 城乡交流活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%8E%96%E8%88%AA%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/yu9=Wsl
- 社区宠物管理的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/695
- 网络安全教育的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/qbr
- 邻里共享空间的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/ydY
- 健康步道使用的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/314=nza
- 儿童友好空间的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/mji=163
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/3gh=2qF
- 数字生活课堂的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/344
- 生活服务数字化的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/jqo
- 社区停车服务的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/9Xh
- 公共场馆服务的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/121=ldq
- 乡村电商实践的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/dcl=562
- 农业科普体验的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/D6n=v96
- 药品使用科普的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/537
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/own
- 老年人文化生活的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/DtW
- 读书会组织的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/887=opq
- 数字课堂应用的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/ugd=660
- 社区活动策划的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/mqg=Ohb
- 图书借阅体验的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/233
- 社区绿色空间的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/whn
- 数据分析入门的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/3GC
- 数字公共文化的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/780=obr
- 家庭节能实践的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/ogo=133
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/Pf0=C2c
- 劳动教育实践的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/139
- 读书会组织的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/pqr
- 街区小店体验的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/GtS
- 数字课堂应用的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/881=vsh
- 街区道路维护的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/oew=058
- 无障碍信息设计的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/llF=Vh1
- 社区教育资源的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/093
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/gxm
- 城市便民驿站的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/Bil
- 公共空间安全的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/810=qua
- 物业服务沟通的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/por=898
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/s8J=ih6
- 青少年户外教育的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/458
- 科普展览体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/hdk
- 数字创意课程的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/o4V
- 本地历史资料的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/655=yuf
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/rvb=205
- 社区花园共建的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E7%BE%8E%E8%82%A1?/zs3=i56
- 社区家校合作的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/703
- 基层健康服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/aqh
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/KsK
- 街头绿植养护的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/949=btn
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/eoc=509
- 农贸市场环境的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/rZK=stn
- 儿童安全出行的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/726
- 社区交通安全的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/vwy
- 文化讲座服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/S19
- 公共设施使用的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/007=xbq
- 社区便利生活的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/qza=038
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/KDt=uOn
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%B9%B6%E8%B4%AD?/394
- 学校体育活动的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%B9%B6%E8%B4%AD?/vpr
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%B9%B6%E8%B4%AD?/svJ
- 志愿服务平台的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%B9%B6%E8%B4%AD?/674=adq
- 课后服务体验的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%B9%B6%E8%B4%AD?/gov=264
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%B9%B6%E8%B4%AD?/zE5=ajv

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
