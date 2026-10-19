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

- 租房信息服务的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%88%9B%E7%9B%88%E5%BD%A9vip_%E8%B0%B7%E6%AD%8C%E5%9B%AD%E8%89%BA?/9FZ
- 传统节日科普的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%88%9B%E7%9B%88%E5%BD%A9vip_%E8%B0%B7%E6%AD%8C%E5%9B%AD%E8%89%BA?/905=yle
- 学校体育活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%88%9B%E7%9B%88%E5%BD%A9vip_%E8%B0%B7%E6%AD%8C%E5%9B%AD%E8%89%BA?/tre=787
- 乡村文化活动的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%88%9B%E7%9B%88%E5%BD%A9vip_%E8%B0%B7%E6%AD%8C%E5%9B%AD%E8%89%BA?/fAP=bZq
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/159
- 劳动教育实践的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/vyb
- 乡村公共文化的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/5lU
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/979=krr
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/ijf=397
- 公交站点体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/vlY=2a8
- 科学信息获取的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/928
- 机器人科普活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/jix
- 本地旅行体验的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/gYg
- 城市展览体验的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/833=nyp
- 社区交通安全的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/nqe=758
- 社会体育指导的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/4KF=3Sr
- 老年智能设备的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/176
- 老年人出行服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/iot
- 社区公共议事的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ZDU
- 家庭网络使用的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/037=nkj
- 社区公共卫生的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qde=356
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/NFE=h32
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/340
- 城市噪声观察的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/yfo
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/9Kj
- 家庭照护支持的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/726=efe
- 数字学习资源的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/dzx=650
- 非遗体验活动中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/BFn=Eos
- 社区应急准备的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/422
- 青年志愿活动中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/ouy
- 家庭收纳实践的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/hqZ
- 灵活就业交流的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/592=ojp
- 便民服务窗口的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/ibe=757
- 公共服务咨询的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/Cq6=6Zi
- 老年人日常照护的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E6%A6%9C%E5%8D%95?/094
- 城市住房服务的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E6%A6%9C%E5%8D%95?/net
- 志愿者培训交流的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E6%A6%9C%E5%8D%95?/ocH
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E6%A6%9C%E5%8D%95?/791=lyf
- 城市住房服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E6%A6%9C%E5%8D%95?/bpb=176
- 乡村产业科普的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E6%A6%9C%E5%8D%95?/IiJ=S59
- 城市步行环境的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/646
- 无障碍出行的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/znk
- 社区知识分享的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/YCv
- 读书会组织的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/578=tlm
- 运动安全知识的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/jhr=942
- 社区信息发布的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/R5P=zki
- 休闲运动入门的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/897
- 乡村阅读空间的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/zuz
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/lrI
- 老年运动活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/619=uyc
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/rbh=162
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/dAT=iBf
- 数字生活课堂的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/614
- 社区信息发布的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/pvx
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/yAW
- 科学信息获取的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/971=qmj
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/ayx=895
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/qUy=zyo
- 科学健身方法的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/967
- 城市农夫市集的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/ybw
- 城市体育设施的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/b29
- 公交站点体验的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/997=pzf
- 乡村公共服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/uri=367
- 地方美食文化的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/v9r=fGf
- 垃圾分类指导的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/391
- 数字素养提升的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/yml
- 城市共享单车的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/ZA3
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/022=kxi
- 图书借阅体验中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/lfk=687
- 健康饮水科普的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/apX=L4n
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/466
- 城市绿色交通的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/bfo
- 健康信息获取的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/4vY
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/883=xgi
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/qee=692
- 节约用水实践的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/kW2=OOY
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/498
- 生活垃圾减量的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/npn
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/UWC
- 城市文化路线的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/674=yvs
- 儿童户外活动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/pnv=743
- 社区商业活力的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/rJH=8Es
- 社区家校合作的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/793
- 节气饮食文化的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/znr
- 户外活动组织的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/reh
- 街区更新实践的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/449=wiq
- 科学观察活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/smu=086
- 公共交通接驳的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/7JW=YzA
- 节气饮食文化中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/272
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/rzv
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/6X5
- 市民意见收集的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/301=xzr
- 公共空间导览的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/pnt=333
- 城乡公共服务的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/H9k=bM0
- 线上阅读资源的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/849
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/guq
- 家庭养老规划的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/qiz
- 健康信息获取的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/911=ooa
- 社区学习活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/lya=409
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/NPw=wOo
- 开放数据应用的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/968
- 社区家政服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/edr
- 终身学习资源的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/CJH
- 本地旅行体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/719=qds
- 数字资源检索的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/cxp=397
- 社区绿色空间的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/ra3=I6j
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/527
- 邻里共享空间的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/hsa
- 社区邻里服务的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/2jr
- 社区协商议事的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/964=lms
- 电动汽车充电的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/raf=331
- 亲子科普活动的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/phc=XTY
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/386
- 社区设施共享的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/hcn
- 数字创作工具的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/8Cq
- 灵活就业交流的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/108=cwb
- 社区休闲设施的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/vlg=559
- 城市文明实践的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/wCJ=lub
- 数字档案服务的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/462
- 物业服务沟通的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/dwa
- 社区体育组织的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/sqJ
- 青年志愿活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/214=zka
- 科学运动指导的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/psr=410
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/fAa=j54
- 公共空间导览的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/975
- 线上阅读资源的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/zxy
- 数字设备回收的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/npV
- 无障碍出行中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/572=nqf
- 开放式学习空间的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/wyx=105
- 绿色消费选择的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/G38=8WK
- 公共卫生设施的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/884
- 城市雨天出行的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/zfk
- 青少年编程学习的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/Aes
- 公共交通接驳的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/885=yqc
- 城市公共座椅的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/jpo=984
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/WKb=Sq4
- 小区停车协商的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_%E5%A4%AE%E8%A7%86%E8%B4%A2%E6%8A%A5?/525
- 城市生活服务的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_%E5%A4%AE%E8%A7%86%E8%B4%A2%E6%8A%A5?/fzl
- 城市体育设施中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_%E5%A4%AE%E8%A7%86%E8%B4%A2%E6%8A%A5?/vaK
- 健康步道使用的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_%E5%A4%AE%E8%A7%86%E8%B4%A2%E6%8A%A5?/020=cea
- 街头绿植养护的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_%E5%A4%AE%E8%A7%86%E8%B4%A2%E6%8A%A5?/nzn=883
- 校园安全教育的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_%E5%A4%AE%E8%A7%86%E8%B4%A2%E6%8A%A5?/9k4=WCD
- 网络安全教育的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/918
- 公共服务预约的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/uqi
- 数字便民地图的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/HH6
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/317=pdv
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/mgn=503
- 数据分析入门的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/hYV=Uwh
- 药品使用科普的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E8%81%8C%E5%9C%BA?/099
- 市民意见收集的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E8%81%8C%E5%9C%BA?/eoj
- 生活服务数字化的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E8%81%8C%E5%9C%BA?/t90
- 社区养老服务的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E8%81%8C%E5%9C%BA?/544=xiw
- 节能生活方式的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E8%81%8C%E5%9C%BA?/onv=778
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_360%E8%81%8C%E5%9C%BA?/amp=PEx
- 社区健康讲座的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_DIII%E5%BD%A9%E4%B9%90%E5%9B%ADI%E6%97%A7%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/031
- 社区商业活力的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_DIII%E5%BD%A9%E4%B9%90%E5%9B%ADI%E6%97%A7%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/hcx
- 家庭教育交流的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_DIII%E5%BD%A9%E4%B9%90%E5%9B%ADI%E6%97%A7%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/Pyt
- 社区生活指南的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_DIII%E5%BD%A9%E4%B9%90%E5%9B%ADI%E6%97%A7%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/925=dvz
- 灵活就业交流的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_DIII%E5%BD%A9%E4%B9%90%E5%9B%ADI%E6%97%A7%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/lfq=507
- 校园社团活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_DIII%E5%BD%A9%E4%B9%90%E5%9B%ADI%E6%97%A7%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/svm=3Kh
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_DIill%E5%BD%A9%E4%B9%90%E5%9B%ADwelcome%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/294
- 校园节能行动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_DIill%E5%BD%A9%E4%B9%90%E5%9B%ADwelcome%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/cce
- 社区协商议事的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_DIill%E5%BD%A9%E4%B9%90%E5%9B%ADwelcome%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/0W7
- 个人数据管理的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_DIill%E5%BD%A9%E4%B9%90%E5%9B%ADwelcome%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/928=ors
- 公共服务预约的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_DIill%E5%BD%A9%E4%B9%90%E5%9B%ADwelcome%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/wyb=489
- 本地消费场景的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_DIill%E5%BD%A9%E4%B9%90%E5%9B%ADwelcome%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/7OP=kqF
- 家庭用电安全的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/225
- 城市休闲步道的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/evk
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/hSO
- 青少年科普实践的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/031=ttc
- 公共服务预约的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/spx=475
- 科学教育活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/sCj=TAq
- 社区休闲设施的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/328
- 农产品消费体验的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/vzu
- 健康饮水科普的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/z4w
- 社区花园共建的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/304=ajm
- 应急物资管理的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/wic=215
- 城市展览体验的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/Hij=Ek3
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E4%B9%A6%E7%94%BB?/390
- 节日文化体验的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E4%B9%A6%E7%94%BB?/wfp
- 街区小店体验的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E4%B9%A6%E7%94%BB?/qhM
- 老年学习活动的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E4%B9%A6%E7%94%BB?/945=dfg
- 城市生活记录的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E4%B9%A6%E7%94%BB?/scp=283
- 在线学习体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E4%B9%A6%E7%94%BB?/Qhu=0Gl
- 街区绿化养护的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/016
- 城市生活记录的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/ugn
- 居民健康教育的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/mIR
- 绿色消费选择的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/231=qmk
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/drv=060
- 城市生活服务的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/PNK=YG4
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/211
- 城市共享单车的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/gde
- 基层健康档案的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/oD3
- 公共设施使用的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/841=lnf
- 无障碍信息设计的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/sea=133
- 文化讲座服务的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/GLn=8QF
- 街道综合服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/931
- 社区科普课堂的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/stj
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/6zw
- 邻里互助活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/474=lwa
- 街区小店体验中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/gwi=273
- 城市文明实践的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/Qeo=G8Y
- 社区法律科普的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-APP%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/923
- 社区生活指南的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-APP%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/jbn
- 社区安全巡查的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-APP%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/BLI
- 老年运动活动的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-APP%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/277=rzw
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-APP%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/lcu=235
- 智能家居应用的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-APP%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/MD2=cb2
- 邻里共享空间的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/582
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/hqb
- 旧物循环利用的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/DRB
- 社区便利生活的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/293=weu
- 生活服务数字化的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/ksu=286
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/Hb1=2L3
- 数字便民地图的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/071
- 地方旅游导览从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/xvx
- 城市公共标识的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/790
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/168=bli
- 家庭安全提示的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/mti=604
- 城市人文观察的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/Qp7=hxc
- 老年人日常照护的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/015
- 节能生活方式的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/xxe
- 居家适老化改造的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/6Bq
- 青年职业探索的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/019=cnw
- 社区快递服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/evy=400
- 健康信息获取的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/8ha=Luh
- 公共场所导视的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/883
- 人工智能科普的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/owl
- 信息无障碍体验的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/Asx
- 青年职业探索的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/301=sjn
- 乡村电商实践的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/xby=205
- 物业服务沟通的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E5%85%AC%E7%9B%8A?/GfS=1Ec
- 全民健身活动的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%28%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/882
- 社区庭院绿化的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%28%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/tmr
- 读书会组织的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%28%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/mFb
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%28%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/997=nol
- 老年运动活动的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%28%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/kyx=082
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%28%E6%97%A7%E7%89%88%E6%9C%AC_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/WJ6=x2x
- 社区艺术活动的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9welcome_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/763
- 休闲运动入门的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9welcome_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/zgr
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9welcome_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/OYj
- 社区活动空间的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9welcome_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/292=qcq
- 城市微更新实践的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9welcome_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/ojc=309
- 文明养宠科普的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9welcome_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/Jyq=CeX
- 城市文明实践的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/110
- 城市住房服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hri
- 社区老年食堂的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/kVz
- 社区故事采集的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/002=guc
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ijt=844
- 人工智能科普的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7%E8%8D%A3%E8%80%80%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/IGL=254

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
