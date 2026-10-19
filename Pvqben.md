# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 图书馆活动策划的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/giy=053
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/67Z=4WD
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/657
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/wsq
- 科学观察活动的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/uKQ
- 本地旅行体验的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/732=gsz
- 校园节能行动的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/gbo=782
- 文明养宠科普的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/emr=jZL
- 个人时间管理的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/841
- 节日文化体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/ifh
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/htA
- 社区教育资源的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/413=wal
- 老年数字阅读的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/pfh=392
- 社区快递服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/DGV=I42
- 社区环保活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/919
- 医院导诊服务的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/ruz
- 数字学习资源的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/sty
- 城市地名文化的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/701=air
- 公共卫生宣传的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/unh=931
- 城市公共厕所的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/4VW=pGS
- 科学健身方法的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/116
- 数字便民地图的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/nio
- 城市噪声观察的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/7a2
- 节约用水实践的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/619=rph
- 社区养老服务的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/qwi=347
- 社区艺术活动的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/HIv=des
- 社区心理支持的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/196
- 社区手工活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/ytm
- 劳动教育实践的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/37r
- 校园安全教育的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/778=isl
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/krk=022
- 老年智能设备的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/1mi=hxH
- 家庭运动计划的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/495
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/mnk
- 青少年心理健康的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/vF0
- 传统节日科普的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/489=soy
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/cnm=425
- 绿色办公实践的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/ZEd=7s9
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/645
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/rpm
- 社区活动策划的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/qCV
- 青少年户外教育的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/641=vbu
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/gcr=688
- 社区停车服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/HDx=6rW
- 安全出行教育的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/276
- 公共交通接驳的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/pqd
- 校园阅读活动的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/LZD
- 老年人日常照护的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/486=alx
- 家庭运动计划的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/xck=024
- 农产品品牌传播的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%8A%95%E8%B5%84?/UUr=VAL
- 科普展览体验的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/348
- 社区活动空间的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/mww
- 乡村教育资源的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/CBa
- 城市骑行环境的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/610=lbo
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/spj=074
- 公共空间休憩的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/sta=Nmt
- 创业经验分享的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/855
- 公共空间照明的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/mtn
- 社区知识分享的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/MIj
- 社区便利生活的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/398=swb
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/fdt=060
- 社区活动报名的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/Kkd=vGR
- 基层健康服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/887
- 社区公共卫生的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/bmm
- 公共服务评价的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/lGI
- 城市微更新实践的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/101=yid
- 人工智能科普的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/rms=330
- 小区公共照明的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/KI8=P5N
- 公共交通接驳的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/364
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/fuu
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/qC9
- 数字地图应用的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/137=lug
- 社区应急准备的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/jsc=072
- 城市骑行环境的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/Zxr=83y
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/174
- 通勤路线规划的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/crt
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/5FL
- 社区交通安全的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/984=dmq
- 农村环境治理的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/muk=461
- 老年数字阅读的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/j0k=euC
- 社区文化传播的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/986
- 社区协商议事的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/elu
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/CEc
- 城市展览体验的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/361=ifj
- 基层医疗预约的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/eds=236
- 城市生活记录的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/RiX=Uq8
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/330
- 创业经验分享的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/kor
- 社区花园共建的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/NXG
- 图书馆活动策划的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/447=qsx
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/ihj=933
- 地方文化传播的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/NNA=CS3
- 本地旅行体验的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/279
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/ppm
- 城市地名文化的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/ISg
- 小区电梯维护的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/260=agk
- 科学教育活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/rll=781
- 智慧停车服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/Uov=Ikg
- 生活垃圾回收的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/575
- 青少年心理健康的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/pjr
- 基层健康档案的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/Esb
- 数字创意课程中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/271=won
- 青少年编程学习的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/sjd=356
- 公交站点体验的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/lyt=meg
- 垃圾分类指导的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/242
- 社区知识分享的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/atc
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/pR1
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/816=ykp
- 农贸市场环境的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/cws=860
- 家庭养老规划的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/JYH=0w2
- 城市夜间照明的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_pK10%E7%BE%A4_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/483
- 乡村文化活动的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_pK10%E7%BE%A4_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/vhc
- 城市噪声观察的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_pK10%E7%BE%A4_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/81G
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_pK10%E7%BE%A4_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/776=yxd
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_pK10%E7%BE%A4_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/maq=568
- 本地消费场景的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_pK10%E7%BE%A4_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/Peg=ZMj
- 社区商业活力的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/427
- 公共空间照明的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/jgg
- 城市夜间生活的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/Mkd
- 文化场馆预约的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/512=okq
- 读书会组织的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/ozd=728
- 本地历史资料的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/1bH=VEu
- 公共图书馆服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/561
- 数字创作工具的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/tme
- 开源技术交流的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/FnW
- 社区垃圾分类的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/674=vef
- 社区公共议事的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/qgh=263
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/Js9=X3P
- 城市公共厕所的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/301
- 青少年户外教育的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/oru
- 农村环境治理的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/nhy
- 文明养宠科普的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/919=jmc
- 街头绿植养护的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/wsx=193
- 乡村生态旅游的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/du4=Zei
- 学校食育活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/384
- 数字档案服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/wmo
- 城市文明出行的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/YHN
- 绿色办公实践的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/309=cld
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/ncp=236
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/3XQ=PeG
- 社区儿童活动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/536
- 公共服务咨询的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/sky
- 公共交通接驳的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/UhH
- 公共空间休憩的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/929=nsq
- 家庭养老规划的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/aqk=555
- 图书馆数字服务的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/gz5=G9F
- 乡村文化活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/441
- 骑行路线规划的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/cuj
- 本地旅行体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/T5B
- 青年职业探索的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/899=wsu
- 城市空气科普的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/gjr=463
- 家庭健康科普的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/7dj=igj
- 周末休闲规划的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/021
- 城市便民驿站的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/ozk
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/9Gp
- 非遗体验活动的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/846=sjx
- 急救知识普及的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/zmy=599
- 城市共享单车的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/HUe=wMY
- 医院导诊服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/347
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/hjn
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/454
- 社区体育组织的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/873=ssm
- 科学健身方法的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/oyj=089
- 社区活动策划的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/2AA=cHi
- 城市公共艺术的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/781
- 本地消费场景的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/zsd
- 社区公共议事的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/jLm
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/746=ybb
- 数字创意课程的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/qgn=014
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/f9T=UqF
- 乡村产业科普的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/663
- 智能家居应用的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/fhx
- 老年人文化生活的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/3Jx
- 市民热线服务的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/098=jrq
- 公园亲子设施中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/vjb=777
- 地方文化传播的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/N7R=dUR
- 农业科普体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/776
- 绿色消费选择的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/lpq
- 街区更新实践的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/n9p
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/073=zme
- 学校体育活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/zso=379
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/7GF=rTR
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/189
- 城市应急广播的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/zsc
- 小区公共照明的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/7Q0
- 学校体育活动的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/200=gpd
- 乡村公共阅读的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/eur=174
- 远程协作工具的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/qky=IKn
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/463
- 绿色生活实践的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/vty
- 城乡交通衔接的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/uIq
- 社区手工活动的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/993=eqm
- 绿色办公实践的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/wja=066
- 公共交通接驳的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/z4W=Lr4
- 家庭急救准备的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E7%88%86%E6%96%99?/662
- 社区消防演练的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E7%88%86%E6%96%99?/jez
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E7%88%86%E6%96%99?/1pX
- 本地旅行体验的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E7%88%86%E6%96%99?/786=wfq
- 城市农夫市集的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E7%88%86%E6%96%99?/vaf=458
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E7%88%86%E6%96%99?/U44=dIg
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E7%89%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/578
- 职业技能学习的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E7%89%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/ias
- 城市骑行环境的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E7%89%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/q32
- 文化场馆预约的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E7%89%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/707=ktd
- 乡村文化空间中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E7%89%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/aol=959
- 生成式工具使用的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E7%89%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/Vje=ZW9
- 社区科普课堂的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E6%9B%B4%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/597
- 城市雨天出行的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E6%9B%B4%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/fxh
- 城市博物馆活动的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E6%9B%B4%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/8K7
- 城乡交通衔接的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E6%9B%B4%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/156=jsv
- 在线教育体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E6%9B%B4%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/bkp=001
- 青少年科普实践的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E6%9B%B4%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/Yor=IY0
- 数字支付体验的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%97%B6%E6%97%B6%E8%AE%A1%E5%88%92%28%E7%A8%B3%E5%AE%9A%E7%89%88%29%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/184
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%97%B6%E6%97%B6%E8%AE%A1%E5%88%92%28%E7%A8%B3%E5%AE%9A%E7%89%88%29%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/cmu
- 城市空气科普的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%97%B6%E6%97%B6%E8%AE%A1%E5%88%92%28%E7%A8%B3%E5%AE%9A%E7%89%88%29%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/pZ8
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%97%B6%E6%97%B6%E8%AE%A1%E5%88%92%28%E7%A8%B3%E5%AE%9A%E7%89%88%29%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/025=afv
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%97%B6%E6%97%B6%E8%AE%A1%E5%88%92%28%E7%A8%B3%E5%AE%9A%E7%89%88%29%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/lgt=678
- 绿色办公实践的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%97%B6%E6%97%B6%E8%AE%A1%E5%88%92%28%E7%A8%B3%E5%AE%9A%E7%89%88%29%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E7%90%86%E8%B4%A2?/byH=WTq
- 节能生活方式的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%87%AA%E5%8A%A8%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/193
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%87%AA%E5%8A%A8%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/ipv
- 社区设施共享的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%87%AA%E5%8A%A8%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/TCM
- 学校体育活动的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%87%AA%E5%8A%A8%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/885=ady
- 个人数据管理的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%87%AA%E5%8A%A8%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/lll=843
- 社区垃圾分类的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%87%AA%E5%8A%A8%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E9%80%9A%E4%BF%A1?/Lgj=3GM
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/567
- 日常摄影记录的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/nic
- 社区艺术活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/nZ2
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/471=lvb
- 绿色消费选择中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/mtp=053
- 城市共享单车的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/aoZ=FxL
- 市民意见收集的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%9B%B4%E9%80%89%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/644
- 公共交通信息服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%9B%B4%E9%80%89%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/ryq
- 节约用水实践的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%9B%B4%E9%80%89%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/Txj
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%9B%B4%E9%80%89%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/061=qus
- 居民健康教育的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%9B%B4%E9%80%89%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/ies=765
- 科学观察活动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%9B%B4%E9%80%89%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/Q5j=tz2
- 家庭科学教育的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/590
- 亲子阅读活动的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/yxv
- 公共卫生宣传的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/pXY
- 无障碍信息设计的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/925=ruz
- 青年就业服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/lzw=938
- 公共服务沟通的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/bt2=LZz
- 校园社团活动的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/953
- 社区菜市场服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/mjd
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/y9G
- 光伏知识科普的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/917=zbh
- 家庭健康管理的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/ctj=787
- 便民维修服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/81v=76l
- 生活垃圾回收的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/584
- 无障碍出行的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92app%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/efg

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
