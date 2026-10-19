# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 老旧小区改造的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/oep
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/840=tmw
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/ucx=256
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%9B%86?/EPB=qjG
- 社会体育指导的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/690
- 医院导诊服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/mcw
- 亲子阅读活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/pnU
- 城市应急科普的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/206=lmt
- 个人时间管理的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ipx=900
- 城市公共自行车的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_9123%E5%A5%BD%E5%BD%A9%E5%A4%A7%E5%8F%91welcome%E4%B8%AD%E5%BF%83_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/sbf=rqv
- 本地历史资料中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/337
- 环境监测科普的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/ruc
- 城市文明实践的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/6aF
- 社区环保活动的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/239=xqb
- 开放数据应用的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/twl=717
- 老年智能设备的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9123%E5%A5%BD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/Vnu=1ph
- 创业经验分享的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/991
- 传统手工艺体验的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/dot
- 科学运动指导的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/Cu6
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/372=miy
- 社区便民服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/uih=903
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_9123%E5%A5%BD%E5%BD%A9%E5%A5%BD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%B8%B8%E6%88%8F?/770=V4w
- 城市农夫市集的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/613
- 老年数字阅读的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/xty
- 数字便民地图的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/nQZ
- 非遗体验活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/404=ngt
- 公共设施维护的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/qog=997
- 公交无障碍服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_9123welcome%E5%A5%BD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/w9p=q8J
- 城市生活服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A99123_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/781
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A99123_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/hha
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A99123_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/IiY
- 文明养宠科普的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A99123_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/733=wbo
- 社区慢性病防控的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A99123_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/whi=109
- 社区活动报名的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A99123_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/bFL=YW1
- 城乡公共服务的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_9123welcome%E5%A5%BD%E5%BD%A9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/894
- 城市树木认养的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_9123welcome%E5%A5%BD%E5%BD%A9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vzb
- 家庭理财科普的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_9123welcome%E5%A5%BD%E5%BD%A9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/inD
- 城市公共饮水的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_9123welcome%E5%A5%BD%E5%BD%A9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/685=sls
- 软件开发学习的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_9123welcome%E5%A5%BD%E5%BD%A9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rfz=777
- 青年志愿活动的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_9123welcome%E5%A5%BD%E5%BD%A9_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/L6s=eUC
- 公园无障碍服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/176
- 气象科普传播的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/pmg
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/A0J
- 学校食育活动的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/881=clj
- 城市微更新实践的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/dat=562
- 社区法律科普的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8app%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/JSU=lpq
- 图书借阅体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Ev8Il_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/346
- 通勤路线规划的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Ev8Il_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/wiy
- 数字支付体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Ev8Il_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/fzG
- 软件开发学习的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Ev8Il_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/786=zbd
- 社区活动策划的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Ev8Il_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/kdu=413
- 数字素养提升中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Ev8Il_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/wd8=vso
- 食品安全科普的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8%E7%BB%BF%E8%89%B2%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/167
- 家庭志愿活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8%E7%BB%BF%E8%89%B2%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/dqc
- 校园阅读活动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8%E7%BB%BF%E8%89%B2%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/gM1
- 社区手工活动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8%E7%BB%BF%E8%89%B2%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/680=vex
- 社区安全巡查的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8%E7%BB%BF%E8%89%B2%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/hea=209
- 传统节日科普的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8%E7%BB%BF%E8%89%B2%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/AjF=5xQ
- 基层健康档案的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8app%E7%BB%BF%E8%89%B2%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/847
- 儿童友好空间的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8app%E7%BB%BF%E8%89%B2%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/prh
- 小区公共照明的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8app%E7%BB%BF%E8%89%B2%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/dss
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8app%E7%BB%BF%E8%89%B2%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/039=npk
- 社区邻里服务的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8app%E7%BB%BF%E8%89%B2%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/wcl=181
- 校园安全教育的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91vll%E5%BD%A9%E7%A5%A8app%E7%BB%BF%E8%89%B2%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/9Jm=YFc
- 家庭网络使用的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/923
- 跨代沟通活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/msh
- 传统节日科普的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/8FG
- 便民维修服务的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/557=vjw
- 公共空间导览的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/tmj=414
- 数字资源检索的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/x3x=gbZ
- 健康信息获取的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/913
- 社区花园共建的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/zlz
- 公共卫生设施的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/4Zm
- 绿色出行服务的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/034=xhs
- 家庭消费规划的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/jry=158
- 城市展览体验的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/soT=2EY
- 绿色生活实践的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/938
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/aax
- 社区读书角建设中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/fK0
- 就业技能培训的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/108=nof
- 社区法律科普的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/gdn=203
- 亲子阅读活动的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/mMe=Vpz
- 家庭健康科普的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/398
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/zha
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/vai
- 市民热线服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/400=lqn
- 青年志愿活动的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/pdo=541
- 城乡交流活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/8FM=OdB
- 小微企业服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/578
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/zjv
- 社区文化传播的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/rOW
- 家庭收纳实践的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/855=rxt
- 乡村教育资源的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/omd=820
- 社区体育组织的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/MQe=PMR
- 城市适老服务的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/177
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/fko
- 家庭节能实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/vha
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/573=okz
- 邻里共享空间的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/hgi=909
- 居家适老化改造的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/rwE=AJ7
- 城市微更新实践的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/183
- 城市适老服务的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/hux
- 数字创意课程的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/hbG
- 公共空间安全的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/569=mra
- 绿色办公实践的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/ouj=595
- 城市地名文化的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/rP1=MPN
- 社区便利生活的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8727.%E5%AE%98%E7%BD%91%E7%82%B9%E5%87%BB%E9%80%9F%E8%BE%BE.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/717
- 绿色出行服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8727.%E5%AE%98%E7%BD%91%E7%82%B9%E5%87%BB%E9%80%9F%E8%BE%BE.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/ctm
- 便民服务窗口的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8727.%E5%AE%98%E7%BD%91%E7%82%B9%E5%87%BB%E9%80%9F%E8%BE%BE.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/1QQ
- 城市可持续生活的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8727.%E5%AE%98%E7%BD%91%E7%82%B9%E5%87%BB%E9%80%9F%E8%BE%BE.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/712=xzn
- 非遗体验活动的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8727.%E5%AE%98%E7%BD%91%E7%82%B9%E5%87%BB%E9%80%9F%E8%BE%BE.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/gbc=096
- 数字素养提升的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8727.%E5%AE%98%E7%BD%91%E7%82%B9%E5%87%BB%E9%80%9F%E8%BE%BE.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/SPO=wjg
- 数字公共文化的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/581
- 城市应急广播的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/hbn
- 医院导诊服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/YWB
- 邻里共享空间的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/168=xtm
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/tyt=473
- 家庭园艺实践的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/rHJ=L8z
- 本地消费场景的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/041
- 家庭健康管理中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/tej
- 公共服务数字化的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/5xE
- 数字艺术创作的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/839=yqt
- 低碳社区实践的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/rwk=117
- 城市基础设施的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/EDr=y5r
- 本地旅行体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8%E8%AF%A6_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/950
- 城市适老服务中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8%E8%AF%A6_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/hmk
- 节能生活方式的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8%E8%AF%A6_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/wde
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8%E8%AF%A6_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/144=ibg
- 家庭环保行动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8%E8%AF%A6_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/dgt=035
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8%E8%AF%A6_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/jNs=laH
- 城市公共标识的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/241
- 社区花园共建的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/vbr
- 家庭环保习惯的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/FAh
- 在线教育体验的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/668=lqc
- 节日文化体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/utk=016
- 环境监测科普的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/V1Y=XQ9
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/550
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/bkj
- 家庭用电安全的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/vEM
- 社区信息发布的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/957=ile
- 绿色办公实践的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/qfi=366
- 公共设施使用的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8-welcome_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/I2k=oxL
- 节气饮食文化的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%9C%AA%E6%9D%A5%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/555
- 智能手机助老的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%9C%AA%E6%9D%A5%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/heb
- 公园亲子设施的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%9C%AA%E6%9D%A5%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/DYj
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%9C%AA%E6%9D%A5%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/575=bpf
- 儿童安全出行的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%9C%AA%E6%9D%A5%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/ysg=407
- 学校体育活动的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%9C%AA%E6%9D%A5%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/e7N=lTh
- 乡村产业科普的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/153
- 电子商务服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/gjk
- 公共设施维护的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/3dx
- 家庭运动计划的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/130=dof
- 创业经验分享的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/twf=688
- 乡村公共服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E5%85%A5%E5%8F%A3_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/Ld5=2hY
- 城市展览体验的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/256
- 节能家电使用的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/rpf
- 数据分析入门的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/Frx
- 城市树木认养的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/204=fei
- 社区科普课堂的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/uzu=743
- 家庭园艺实践的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/wds=jq0
- 绿色办公实践的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E6%8E%A7%E8%82%A1%2801180.hk%29_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/930
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E6%8E%A7%E8%82%A1%2801180.hk%29_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/aay
- 校园社团活动的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E6%8E%A7%E8%82%A1%2801180.hk%29_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/VXW
- 公共服务预约的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E6%8E%A7%E8%82%A1%2801180.hk%29_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/008=mcn
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E6%8E%A7%E8%82%A1%2801180.hk%29_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/qwq=129
- 社区垃圾分类的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E6%8E%A7%E8%82%A1%2801180.hk%29_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/IYJ=YGI
- 科学观察活动的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/760
- 居家防滑改造的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/zwr
- 小区停车协商的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/45t
- 社区共享书架的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/549=goz
- 全民阅读推广的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/oir=782
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/8im=ZE9
- 数字政务体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91com_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/808
- 校园安全教育的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91com_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/bcb
- 公园亲子设施中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91com_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/IoU
- 社区儿童活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91com_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/624=jms
- 节气饮食文化的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91com_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/whx=697
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%B1%87%E5%BD%A9%E7%BD%91com_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/l0r=17a
- 社会体育指导的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%B1%87%E5%BD%A9%E7%BD%91welcome._%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/399
- 公共服务沟通的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%B1%87%E5%BD%A9%E7%BD%91welcome._%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/ndk
- 市民意见收集的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%B1%87%E5%BD%A9%E7%BD%91welcome._%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/Nnw
- 市民热线服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%B1%87%E5%BD%A9%E7%BD%91welcome._%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/573=fbr
- 城市微更新实践的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%B1%87%E5%BD%A9%E7%BD%91welcome._%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/vlo=866
- 智慧停车服务的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%B1%87%E5%BD%A9%E7%BD%91welcome._%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/NVW=u5A
- 公共服务咨询的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/518
- 城乡公共服务的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/mbb
- 社区活动策划的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/RtM
- 老年数字阅读的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/649=lqc
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/omk=647
- 城乡交流活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/KbJ=EZ7
- 数字阅读服务的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/446
- 创业经验分享的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/gcx
- 乡村产业科普的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/JHZ
- 家庭健康管理的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/522=fww
- 公交站点体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/biq=276
- 城市空气科普的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%B1%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%8D%83%E5%B8%86?/J44=nzf
- 网络安全教育的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/078
- 城市微更新实践的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/odp
- 无障碍信息设计的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/uKv
- 数字资源检索的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/236=oqf
- 家庭运动计划的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/fvz=685
- 劳动教育实践的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/AdY=ymW
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_welcome%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/471
- 城市夜间生活的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_welcome%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/yqs
- 在线学习体验的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_welcome%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/mzQ
- 社区读书角建设的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_welcome%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/864=lpy
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_welcome%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/gqc=055
- 旧物循环利用的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_welcome%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/BBT=NvT
- 社区手工活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85-welcome_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/539
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85-welcome_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/sip
- 图书馆数字服务的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85-welcome_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/iHl
- 儿童安全出行的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85-welcome_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/444=fqy
- 数字课堂应用的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85-welcome_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/glt=120
- 社区故事采集的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85-welcome_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/HQT=f8r
- 健康饮食教育的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/620
- 社区庭院绿化的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/aom
- 电动汽车充电的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/qtY
- 城乡交通衔接的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/194=vlp
- 社区运动空间的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/tmt=248
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/MNw=thK
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91cc-%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%BD%A9%E7%BD%91cc_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/814
- 社区阅读服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91cc-%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%BD%A9%E7%BD%91cc_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/nzh
- 便民服务窗口中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91cc-%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%BD%A9%E7%BD%91cc_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/Y6A
- 公共空间照明中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91cc-%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%BD%A9%E7%BD%91cc_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/939=mru
- 城市文化路线的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91cc-%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%BD%A9%E7%BD%91cc_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/vqa=096
- 公共空间休憩的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91cc-%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%BD%A9%E7%BD%91cc_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/dMw=r2h
- 社区健康讲座的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%B1%87%E5%BD%A9%E7%BD%91welcome_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/846
- 农村环境治理的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%B1%87%E5%BD%A9%E7%BD%91welcome_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/hqq
- 社区阅读服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%B1%87%E5%BD%A9%E7%BD%91welcome_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/SZY
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%B1%87%E5%BD%A9%E7%BD%91welcome_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/641=sxw
- 亲子科普活动的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%B1%87%E5%BD%A9%E7%BD%91welcome_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/owt=126
- 城市微更新实践的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%B1%87%E5%BD%A9%E7%BD%91welcome_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/ZTk=ioi
- 乡村文化空间的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E9%97%A8%E6%B1%87%E5%BD%A9%E7%BD%91welcome-_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/472
- 小区公共照明的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E9%97%A8%E6%B1%87%E5%BD%A9%E7%BD%91welcome-_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/vdj
- 科学观察活动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E9%97%A8%E6%B1%87%E5%BD%A9%E7%BD%91welcome-_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/Z6D
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E9%97%A8%E6%B1%87%E5%BD%A9%E7%BD%91welcome-_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/375=duj
- 公益活动组织的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E9%97%A8%E6%B1%87%E5%BD%A9%E7%BD%91welcome-_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/bnj=281
- 居家防滑改造的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E9%97%A8%E6%B1%87%E5%BD%A9%E7%BD%91welcome-_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/gds=o1Y
- 健康饮食教育中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/952
- 社区共享书架的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/sgo
- 城市空气科普的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/t7D
- 城市运动公园的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/962=yqo
- 公共场所导视的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/gge=875
- 便民服务窗口的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%28%E4%B8%AD%E5%9B%BD%E5%8C%BA%29_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/szO=y8g
- 环境教育课程的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%919198%E5%85%8D%E8%B4%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/964
- 社区托育服务的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%919198%E5%85%8D%E8%B4%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/rbn
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%919198%E5%85%8D%E8%B4%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/VRj
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%919198%E5%85%8D%E8%B4%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/328=hpi
- 基层服务创新的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%919198%E5%85%8D%E8%B4%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/vmu=087
- 校园节能行动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%B1%87%E5%BD%A9%E7%BD%919198%E5%85%8D%E8%B4%B9%E7%89%88_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/AcA=ol3

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
