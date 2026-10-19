# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 远程协作工具的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/038
- 数字地图应用的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/ujo
- 街头绿植养护的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/kIH
- 数字便民地图的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/441=clq
- 在线学习体验的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/fle=791
- 地方旅游导览的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/usd=oET
- 乡村电商实践的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/092
- 绿色出行服务的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/mww
- 通勤路线规划的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/ior
- 电子商务服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/041=lqb
- 科学运动指导的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/ies=147
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/h5D=zBT
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/754
- 健康饮食教育的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/rnd
- 健康步道使用的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/LzT
- 公共服务评价的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/166=lpm
- 线上办事服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/mwi=638
- 家庭环保行动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/FHP=vH5
- 公共服务沟通的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/089
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/uff
- 市民热线服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/ioA
- 数字档案服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/728=nyv
- 机器人科普活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/rtf=259
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A7%81%E5%8B%9F?/goo=KMJ
- 志愿服务平台的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B_36%E6%B0%AA?/248
- 社区家校合作的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B_36%E6%B0%AA?/qln
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B_36%E6%B0%AA?/w8W
- 社区法律科普中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B_36%E6%B0%AA?/248=hpi
- 城乡交流活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B_36%E6%B0%AA?/gbc=237
- 社区文化节活动的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%AE%BA%E5%9D%9B_36%E6%B0%AA?/NtV=270
- 基层健康服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/083
- 公共空间导览的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/zvd
- 街区小店体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/nDt
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/011=efe
- 城市噪声观察的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/rfz=986
- 社区公共卫生的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/869=c0l
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/625
- 乡村公共文化的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/bjb
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/wfE
- 社区商业活力的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/997=pqq
- 城市公共饮水的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/cyt=144
- 校园社团活动的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/Z6i=vHD
- 读书会组织的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/595
- 乡村公共文化的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/wbx
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/ilJ
- 居民健康教育的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/563=snh
- 非遗体验活动的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/ift=716
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/Be6=jjf
- 城市公共饮水的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/840
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/vgs
- 社区艺术活动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/G6S
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/732=xmu
- 社区防暑服务的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/poy=284
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/0Im=Pet
- 社区活动策划的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/255
- 社区协商议事的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/zue
- 城市生活服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/uvv
- 本地历史资料的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/462=cbk
- 社区共享书架的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/hzu=666
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/rdD=IJM
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/678
- 节日文化体验的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/rey
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/guX
- 绿色办公实践的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/044=pic
- 节约用水实践的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/xym=056
- 公共服务数字化的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/ke2=jTl
- 基层服务创新的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/005
- 社区儿童活动的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/rbb
- 城乡交流活动的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/3lg
- 城市慢行系统的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/797=iao
- 家庭健康科普的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/iol=869
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/6Kf=f24
- 公交站点体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/120
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/knj
- 城市夜间照明的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/Lx9
- 家庭养老规划的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/455=htj
- 公共空间照明的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/xzc=654
- 公交站点体验的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%85%A5%E5%8F%A3_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/9E6=iD4
- 城市社区治理的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/181
- 地方旅游导览的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/smz
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/1RB
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/382=szd
- 智能家居应用的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/qen=403
- 社区公共卫生的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/f0B=Pe4
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/458
- 社区养老服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/wck
- 便民信息查询的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/YDc
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/334=uke
- 公共空间照明的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/nse=391
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/y9t=Aav
- 生活服务数字化的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/429
- 儿童友好街区的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/ixs
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/Ros
- 乡村文化活动的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/139=fxx
- 电子商务服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/biy=118
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8F_%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/gAn=7nY
- 科学观察活动的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8FWelcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/114
- 软件开发学习的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8FWelcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/alx
- 青年职业探索的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8FWelcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/7u7
- 开源技术交流的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8FWelcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/416=xlu
- 社区志愿服务的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8FWelcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/wwb=605
- 社区便利生活的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8FWelcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/Sd6=ifN
- 公园无障碍服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%8F%B0%E6%B9%BE%E5%AE%BE%E6%9E%9C%E4%BA%94%E5%88%86%E5%BC%80%E5%A5%96_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/835
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%8F%B0%E6%B9%BE%E5%AE%BE%E6%9E%9C%E4%BA%94%E5%88%86%E5%BC%80%E5%A5%96_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/biz
- 地方文化传播的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%8F%B0%E6%B9%BE%E5%AE%BE%E6%9E%9C%E4%BA%94%E5%88%86%E5%BC%80%E5%A5%96_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/YcR
- 街区小店体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%8F%B0%E6%B9%BE%E5%AE%BE%E6%9E%9C%E4%BA%94%E5%88%86%E5%BC%80%E5%A5%96_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/668=wgb
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%8F%B0%E6%B9%BE%E5%AE%BE%E6%9E%9C%E4%BA%94%E5%88%86%E5%BC%80%E5%A5%96_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/ifk=422
- 文明养宠科普的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%8F%B0%E6%B9%BE%E5%AE%BE%E6%9E%9C%E4%BA%94%E5%88%86%E5%BC%80%E5%A5%96_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/5yL=aaw
- 老年智能设备的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8Fwelcome%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/185
- 家庭阅读计划的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8Fwelcome%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/vor
- 城乡交通衔接的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8Fwelcome%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/1r1
- 社区花园共建的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8Fwelcome%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/783=ate
- 数字公共文化的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8Fwelcome%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/kgp=612
- 绿色快递包装的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%AE%BE%E6%9E%9C%E6%B8%B8%E6%88%8Fwelcome%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/UYI=ViO
- 开源技术交流的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/327
- 电子商务服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/azg
- 图书借阅体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/9sO
- 青年职业探索的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/052=fvk
- 农贸市场环境的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/uiw=348
- 周末休闲规划的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/OWN=8xO
- 数字便民地图的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/528
- 乡村产业科普的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/tcc
- 休闲运动入门中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/mGw
- 城市展览体验的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/618=oxf
- 社区手工活动的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/sfi=208
- 家庭科学教育的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/PMh=gMi
- 地方文化传播的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/200
- 街道综合服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/ydg
- 城市文明实践的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/iLO
- 公交无障碍服务的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/691=aim
- 急救知识普及的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/kcv=485
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/6wf=AR7
- 城市生活服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/215
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/jre
- 城市文化路线的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/TEx
- 社区菜市场服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/628=ivw
- 基层健康档案的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/vrb=873
- 城市体育设施的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/MWc=OSQ
- 邻里共享空间的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/741
- 社区读书角建设的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/yaa
- 公共空间导览的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/AY3
- 乡村公共服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/396=dzw
- 城市公共标识的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/bdk=119
- 城市噪声观察的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/hUh=9Hx
- 数字艺术创作的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/146
- 户外活动组织的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/pnx
- 绿色出行服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/S5z
- 城市公共厕所的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/222=xxv
- 社区活动策划的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/uku=266
- 数字艺术创作的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/lI0=BD0
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/775
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/wiu
- 社区家政服务的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/mF7
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/457=lmm
- 市民热线服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/isz=784
- 绿色消费选择的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/4qY=mFM
- 公共空间安全的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%8D%E5%A0%82welcome_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/099
- 城市可持续生活的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%8D%E5%A0%82welcome_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/gko
- 科技馆参观体验的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%8D%E5%A0%82welcome_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/Lvz
- 社区托育服务的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%8D%E5%A0%82welcome_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/343=wxn
- 图书馆活动策划的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%8D%E5%A0%82welcome_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/byh=692
- 公共设施使用的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E5%90%8D%E5%A0%82welcome_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/AXV=1sB
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E5%90%8D%E5%A0%82v5.0%E5%AE%98%E6%96%B9%E7%89%88_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/915
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E5%90%8D%E5%A0%82v5.0%E5%AE%98%E6%96%B9%E7%89%88_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/yqw
- 城市夜间照明的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E5%90%8D%E5%A0%82v5.0%E5%AE%98%E6%96%B9%E7%89%88_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/etu
- 儿童运动体验的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E5%90%8D%E5%A0%82v5.0%E5%AE%98%E6%96%B9%E7%89%88_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/666=uix
- 无障碍信息设计的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E5%90%8D%E5%A0%82v5.0%E5%AE%98%E6%96%B9%E7%89%88_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/vks=012
- 城乡公共服务的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E5%90%8D%E5%A0%82v5.0%E5%AE%98%E6%96%B9%E7%89%88_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/vhd=QRo
- 城市共享单车的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E5%90%8D%E5%A0%822018%E5%B9%B4_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/183
- 社区健康讲座的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E5%90%8D%E5%A0%822018%E5%B9%B4_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/yos
- 绿色建筑理念的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E5%90%8D%E5%A0%822018%E5%B9%B4_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/Ggf
- 小区电梯维护的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E5%90%8D%E5%A0%822018%E5%B9%B4_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/351=zgv
- 数字生活课堂的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E5%90%8D%E5%A0%822018%E5%B9%B4_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/guh=184
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E5%90%8D%E5%A0%822018%E5%B9%B4_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/uU4=sD8
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EIIV-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/353
- 城市休闲步道的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EIIV-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/mab
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EIIV-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/fhD
- 就业技能培训的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EIIV-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/667=dao
- 城乡交流活动的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EIIV-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/slm=562
- 数字生活课堂的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9EIIV-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/4tj=kR3
- 个人数据管理的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/321
- 绿色办公实践的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/qgw
- 数字资源检索的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/SGC
- 绿色消费选择的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/261=ziq
- 社区庭院绿化的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/zyz=596
- 小区停车协商的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8D%8E%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/gpb=kAf
- 地方美食文化的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/952
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/bji
- 城市应急科普的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/bdH
- 社区便利生活的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/743=eil
- 读书会组织的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/xbp=687
- 社区家政服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%9B%88%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/fuP=xy4
- 气象科普传播的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/477
- 城市建设科普的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/vme
- 科学信息获取的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/VDS
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/843=fsy
- 社区活动报名的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/yjh=449
- 食品配送体验中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E4%BC%97%E5%BD%A9%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/PNA=lXv
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/473
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/sbu
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/SMh
- 科学信息获取的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/712=dpi
- 公共交通接驳的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/vkg=121
- 数字政务体验的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/Qbl=noA
- 运动安全知识的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%AB%99welcome_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/778
- 青年志愿活动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%AB%99welcome_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/eiy
- 药品使用科普的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%AB%99welcome_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/Sz6
- 社区公共餐饮的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%AB%99welcome_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/854=xzc
- 乡村公共阅读的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%AB%99welcome_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/isl=780
- 城市共享单车的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%AB%99welcome_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/fGw=jZh
- 街区小店体验的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8224app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/233
- 城市公共标识的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8224app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/jii
- 网络信息辨识的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8224app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/NaN
- 数字课堂应用的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8224app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/304=kyr
- 街区绿化养护的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8224app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/cfo=276
- 社区信息发布的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8224app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/bwz=3d9
- 数字创作工具的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/147
- 数字课堂应用的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/bis
- 儿童友好空间的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/aFT
- 青少年户外教育的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/572=hhq
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/hxe=630
- 社区庭院绿化的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/qEb=Z75
- 光伏知识科普的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_360%E6%88%BF%E4%BA%A7?/834
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_360%E6%88%BF%E4%BA%A7?/ezy
- 图书馆数字服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_360%E6%88%BF%E4%BA%A7?/lMd
- 市民意见收集的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_360%E6%88%BF%E4%BA%A7?/958=qaw
- 口袋公园建设的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_360%E6%88%BF%E4%BA%A7?/fpu=808
- 社区志愿服务的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%80%80%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_360%E6%88%BF%E4%BA%A7?/JNr=JI5
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/238
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/dnq
- 便民服务窗口的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/Cnf
- 街头绿植养护的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/621=jck
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/jei=273
- 公共交通接驳的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/uWa=I2H
- 科技馆参观体验的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90welcome%E7%99%BB%E5%BD%95%E7%95%8C%E9%9D%A2_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/800
- 科学运动指导的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90welcome%E7%99%BB%E5%BD%95%E7%95%8C%E9%9D%A2_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/fsv
- 健康步道使用的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90welcome%E7%99%BB%E5%BD%95%E7%95%8C%E9%9D%A2_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/iHb
- 租房信息服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90welcome%E7%99%BB%E5%BD%95%E7%95%8C%E9%9D%A2_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/134=fsk
- 医院导诊服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90welcome%E7%99%BB%E5%BD%95%E7%95%8C%E9%9D%A2_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/plz=270
- 社区知识分享的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90welcome%E7%99%BB%E5%BD%95%E7%95%8C%E9%9D%A2_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/qlr=lwX
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/211
- 公共健身器材的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/avg
- 儿童友好空间的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/4FO
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/508=jvy
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/muu=477
- 街道综合服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/FIg=YKF
- 城市公共标识的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90app%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/016
- 青年志愿活动的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90app%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/jsy
- 安全出行教育的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90app%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/2Lk
- 社区便民集市的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90app%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/056=xin

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
