# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 光伏知识科普的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_7%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/095
- 城乡公共服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_7%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/raa
- 灵活就业交流的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_7%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/Zgk
- 小区电梯维护的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_7%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/492=fcx
- 公共设施使用的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_7%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/vvj=645
- 通勤路线规划的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_7%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/1kn=URx
- 数字课堂应用的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%B8%80%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_360%E5%BF%AB%E6%8A%A5?/977
- 休闲运动入门的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%B8%80%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_360%E5%BF%AB%E6%8A%A5?/vxh
- 公共服务数字化的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%B8%80%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_360%E5%BF%AB%E6%8A%A5?/yCs
- 社区体育组织的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%B8%80%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_360%E5%BF%AB%E6%8A%A5?/188=wdf
- 全民阅读推广的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%B8%80%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_360%E5%BF%AB%E6%8A%A5?/oyn=086
- 城市体育设施的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%B8%80%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_360%E5%BF%AB%E6%8A%A5?/Aef=JPl
- 开放数据应用的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E4%BD%93%E5%BD%A9%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/023
- 社区知识分享的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E4%BD%93%E5%BD%A9%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/fbu
- 城市公共自行车的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E4%BD%93%E5%BD%A9%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/A8Z
- 社区阅读服务的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E4%BD%93%E5%BD%A9%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/279=tzr
- 机器人科普活动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E4%BD%93%E5%BD%A9%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/adv=809
- 远程协作工具的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E4%BD%93%E5%BD%A9%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/SEA=QXC
- 绿色出行服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/096
- 街区小店体验的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/aal
- 人工智能科普的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/Ukn
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/607=bqa
- 家庭消费规划的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/xtk=085
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/AuC=tc1
- 科普展览体验的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/199
- 食品配送体验的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/nfl
- 灵活就业交流的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/2i2
- 社区志愿服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/559=bhp
- 城市便民驿站的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/cny=718
- 校园节能行动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/BP4=5ky
- 便民服务地图的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%BB%84%E4%B8%89%E5%85%A8%E5%8C%85%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/493
- 城市雨天出行的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%BB%84%E4%B8%89%E5%85%A8%E5%8C%85%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/pff
- 社区活动空间的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%BB%84%E4%B8%89%E5%85%A8%E5%8C%85%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/WhR
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%BB%84%E4%B8%89%E5%85%A8%E5%8C%85%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/783=zae
- 环境教育课程的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%BB%84%E4%B8%89%E5%85%A8%E5%8C%85%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/how=835
- 本地消费场景的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E7%BB%84%E4%B8%89%E5%85%A8%E5%8C%85%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/IT8=x7f
- 基层健康服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/881
- 校园阅读活动的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/epb
- 城市地名文化的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/1Qj
- 社区停车服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/387=ndq
- 老年人日常照护的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/uwh=672
- 城市农夫市集的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%8E%92%E5%88%97%E4%B8%89%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/Y0J=Kpv
- 儿童阅读角的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/904
- 社区应急准备的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/qxy
- 骑行路线规划的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/Zze
- 家庭养老规划的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/956=xby
- 青少年编程学习的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/hrg=873
- 新能源知识普及的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/gV2=Sd4
- 社区消防演练的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/231
- 社区志愿服务的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/yut
- 小微企业服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/tNs
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/462=ogm
- 市民热线服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vpk=687
- 地方旅游导览的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E5%BE%BD%E5%BF%AB3_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lZt=3nC
- 职业技能学习的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%B9%96%E5%8C%97%E5%BF%AB3_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/935
- 家庭志愿活动的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%B9%96%E5%8C%97%E5%BF%AB3_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/urh
- 生活垃圾回收的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%B9%96%E5%8C%97%E5%BF%AB3_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/g8M
- 全民健身活动的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%B9%96%E5%8C%97%E5%BF%AB3_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/628=rfa
- 便民服务窗口的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%B9%96%E5%8C%97%E5%BF%AB3_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/gyk=752
- 科学健身方法的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%B9%96%E5%8C%97%E5%BF%AB3_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/bOA=5AC
- 青少年户外教育的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E6%9E%97%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/791
- 城市便民驿站的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E6%9E%97%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/bui
- 终身学习资源的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E6%9E%97%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/Cyz
- 儿童户外活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E6%9E%97%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/718=cpy
- 公共场馆服务的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E6%9E%97%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/enc=274
- 青年就业服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E6%9E%97%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%88%86%E6%96%99?/L0y=tPX
- 小微企业服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E8%A5%BF%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/861
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E8%A5%BF%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/wul
- 城乡交流活动的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E8%A5%BF%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/eMa
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E8%A5%BF%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/595=rfd
- 健康饮食教育的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E8%A5%BF%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/ljq=083
- 公交站点体验的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%B9%BF%E8%A5%BF%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/pwo=wgZ
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/178
- 城市农夫市集的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/npr
- 线上阅读资源的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/oQa
- 老年数字阅读的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/371=uye
- 节能生活方式的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/zmr=634
- 智能手机助老的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/kR3=LI4
- 社区垃圾分类的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/360
- 便民服务地图的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/usn
- 骑行路线规划的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/yET
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/995=ysa
- 本地旅行体验的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/hpl=389
- 社区活动策划的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/SEu=ZrC
- 社区绿色空间的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/430
- 校园阅读活动的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/zql
- 儿童阅读角的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/DwH
- 城市应急科普的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/486=tpb
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/qmp=888
- 儿童运动体验的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%A1%A3%E6%A1%88?/Qqa=o5Y
- 本地旅行体验的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/210
- 社区家政服务的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/ogl
- 数字资源检索的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/3KJ
- 乡村教育资源的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/799=ufn
- 家庭健康管理的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/qsr=701
- 城市骑行环境的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E5%BC%80%E5%A5%96_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/QVd=y03
- 健康信息获取的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%BC%80%E5%A5%96_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/337
- 乡村公共文化的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%BC%80%E5%A5%96_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/qdp
- 公共交通信息服务的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%BC%80%E5%A5%96_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/X9w
- 城市公共厕所的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%BC%80%E5%A5%96_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/990=par
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%BC%80%E5%A5%96_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/rxh=967
- 社区托育服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%BC%80%E5%A5%96_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/tKF=95V
- 校园节能行动的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%90%89%E6%9E%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/889
- 课后服务体验的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%90%89%E6%9E%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/svq
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%90%89%E6%9E%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/wJO
- 公共设施维护的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%90%89%E6%9E%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/848=zus
- 公共设施使用的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%90%89%E6%9E%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/dwe=062
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%90%89%E6%9E%97%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/HJH=8dj
- 社区公共餐饮的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/653
- 街区绿化养护的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/prd
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/Q4U
- 城市树木认养的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/217=gkz
- 城市公共饮水的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/mqx=253
- 便民服务窗口的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%B9%BF%E8%A5%BF%E5%BF%AB3%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/Xdq=7Uc
- 城市骑行环境的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/512
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/zqj
- 城乡交流活动中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/Bql
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/282=bsc
- 居家防滑改造的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/tdb=438
- 乡村生态旅游的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/OOz=BbX
- 节约用水实践的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_360%E7%89%B9%E7%A8%BF?/334
- 儿童阅读角的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_360%E7%89%B9%E7%A8%BF?/lqn
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_360%E7%89%B9%E7%A8%BF?/hkH
- 社区垃圾分类的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_360%E7%89%B9%E7%A8%BF?/108=htx
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_360%E7%89%B9%E7%A8%BF?/nzv=707
- 通勤路线规划的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85_360%E7%89%B9%E7%A8%BF?/KsX=AKs
- 数字公共文化的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/543
- 创业经验分享中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/eyk
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/MTP
- 社区心理支持的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/502=wwh
- 城市生活服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/tpl=209
- 城市绿色交通的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/ctU=Z0X
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/992
- 社区快递服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/tgo
- 数字艺术创作的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/7Ta
- 人工智能科普的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/549=ddu
- 在线学习体验中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/dfz=093
- 公共服务指南的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/Xb7=KoU
- 社区运动空间的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/120
- 城市生活服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/pqx
- 老年人出行服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/DPG
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/596=hag
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/mxa=310
- 光伏知识科普的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/uKW=GwD
- 城市生活服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BC%80%E6%88%B7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/270
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BC%80%E6%88%B7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/wxt
- 家庭用电安全的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BC%80%E6%88%B7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/4OB
- 公共服务预约的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BC%80%E6%88%B7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/217=pxj
- 城市公共座椅的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BC%80%E6%88%B7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/wmc=273
- 健康饮食教育的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BC%80%E6%88%B7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/P8y=t51
- 智能家居应用的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/798
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/gnu
- 社区防暑服务的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/jFd
- 社区体育组织的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/456=mdt
- 科学信息获取的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/haa=693
- 公共健身器材的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/5zV=lJc
- 社区公共议事的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/951
- 社区互助网络的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/mol
- 乡村电商实践的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/MTQ
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/927=cyl
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/yxq=261
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/Zrs=wQl
- 街区更新实践的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/827
- 户外活动组织的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/kvz
- 数字资源检索的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/Vb2
- 社区公共餐饮的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/249=wbu
- 科学教育活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/ulc=523
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/iMb=SLB
- 城市公共标识的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/720
- 社区商业活力的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/toq
- 老年人日常照护的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/LAH
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/335=dre
- 就业技能培训的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/dib=696
- 小区停车协商的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/Aza=XLf
- 社区绿色空间的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/447
- 全民阅读推广的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/idw
- 城市雨天出行的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/HDo
- 青少年科普实践的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/612=mel
- 公共设施维护的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/wwo=053
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E6%97%B6%E5%B0%9A?/Zmi=cb6
- 志愿者培训交流的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/907
- 城市基础设施的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/woi
- 街区更新实践的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/acT
- 家庭消费规划的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/126=pmj
- 学校食育活动的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/mxp=401
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/sPc=7zu
- 传统手工艺体验的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/548
- 便民维修服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/xth
- 本地历史资料的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/QL3
- 数字档案服务的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/225=oza
- 居家适老化改造的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/xod=030
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/1B3=DL4
- 居民健康教育的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/549
- 社区公共卫生的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/gmh
- 城市公共标识的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/cLR
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/293=ddt
- 城市夜间生活的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/fco=030
- 社区故事采集的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/gTJ=Ian
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/996
- 城市建设科普的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/bhr
- 家庭志愿活动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/VP4
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/922=aru
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/ips=164
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/TdS=o0x
- 家庭志愿活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/363
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/zbl
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/ZBh
- 公共空间休憩的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/805=tpk
- 老年友好服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/yog=150
- 社区活动报名的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/CbP=ymC
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/334
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/tph
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/qP9
- 社区邻里服务的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/560=icv
- 开源技术交流的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/xwq=714
- 创业经验分享的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%96%9C%E4%B8%AD188%E4%B8%87_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/UuV=FP8
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/773
- 学校食育活动有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/qvz
- 数字学习资源的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/BIP
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/598=jcd
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/jqx=710
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/XIH=QLC
- 数字公共文化的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/741
- 无障碍信息设计的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/nhg
- 社区防暑服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/cYs
- 老年人出行服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/599=drc
- 社区读书角建设的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/bfz=446
- 食品安全科普的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/ls8=ICg
- 城市建设科普的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/528
- 儿童安全出行的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/qgh
- 本地消费场景的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/O9Q
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/312=loy
- 数字创作工具的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/bvn=275
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/LwZ=UK7
- 社区托育服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/116
- 公共空间导览的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/spd
- 城市骑行环境的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/tB8
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/189=hnu
- 青少年科技社团的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/bxz=607
- 城市公共厕所的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/nn5=gD8
- 街区绿化养护的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/826
- 小区公共照明中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/rfy
- 租房信息服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/3dn
- 数字生活课堂的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/565=bnu
- 全民健身活动的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/iam=694
- 社区快递服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B3%95%E5%BE%8B?/vd6=uoD
- 农产品消费体验的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/209
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/qyv
- 网络信息辨识的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/k9B
- 城市夜间照明的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/468=nww

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
