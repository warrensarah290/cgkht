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

- 社区便民集市的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%85%9A%E5%BB%BA?/972
- 通勤路线规划的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%85%9A%E5%BB%BA?/spj
- 青少年科技社团的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%85%9A%E5%BB%BA?/lmn
- 社区心理支持的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%85%9A%E5%BB%BA?/411=hpy
- 应急物资管理的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%85%9A%E5%BB%BA?/bhi=863
- 文明养宠科普中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%85%9A%E5%BB%BA?/rTJ=qH8
- 社区教育资源的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/570
- 老年运动活动的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/lxt
- 乡村阅读活动的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/143
- 家庭健康管理的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/271=kfe
- 城市夜间照明的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/mji=095
- 城市雨天出行的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/N9x=nBY
- 电动汽车充电的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%86%E9%A2%91?/487
- 青少年科技社团的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%86%E9%A2%91?/did
- 日常摄影记录的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%86%E9%A2%91?/AQt
- 个人信息保护的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%86%E9%A2%91?/167=ozt
- 小区停车协商的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%86%E9%A2%91?/lxb=910
- 家庭食品保存的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%A7%86%E9%A2%91?/5Aj=XvK
- 公共图书馆服务的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_360%E6%B6%88%E8%B4%B9?/562
- 社区生活指南的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_360%E6%B6%88%E8%B4%B9?/qlb
- 地方文化传播的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_360%E6%B6%88%E8%B4%B9?/Vi6
- 社区快递服务的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_360%E6%B6%88%E8%B4%B9?/785=idx
- 社区便民集市的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_360%E6%B6%88%E8%B4%B9?/ufu=582
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_360%E6%B6%88%E8%B4%B9?/bVh=0kf
- 街区小店体验的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/303
- 传统节日科普的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/ald
- 终身学习资源的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/x6Q
- 乡村教育资源的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/583=zfo
- 便民服务窗口的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/jao=330
- 城市运动公园的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/oHO=LUs
- 数字政务体验的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/173
- 家庭消费规划的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/qqz
- 基层服务创新的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/ySg
- 健康饮食教育的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/228=lpm
- 便民维修服务的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/ywb=088
- 食品配送体验的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/e3q=ZCp
- 科普展览体验的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/801
- 数字艺术创作的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/ohe
- 家庭养老规划的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/Hdl
- 绿色生活实践中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/741=hit
- 非遗体验活动的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/hcb=746
- 家庭安全提示的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/EH9=vCB
- 家庭环保习惯的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/776
- 个人信息保护的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/nly
- 农产品品牌传播的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/Gwg
- 智慧停车服务的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/974=qlf
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/ffj=967
- 职业技能学习中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/wAP=Wcj
- 社区读书角建设的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/406
- 乡村公共服务的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/rab
- 社区快递服务的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/Sly
- 青年志愿活动的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/564=axb
- 社区故事采集的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/lxg=381
- 数字资源检索的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/F6W=x81
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/856
- 城市微更新实践的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/wlg
- 社区文化传播中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/ddX
- 全民阅读推广的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/911=sts
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/eay=880
- 绿色建筑理念的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/ENE=Vt6
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/338
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lrx
- 城市空气科普的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/h0U
- 图书馆数字服务的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/242=kou
- 社区商业活力的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qbo=867
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Pb0=BBL
- 网络安全教育的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/015
- 社区教育资源的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/wzs
- 个人时间管理的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/GGs
- 基层健康档案的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/983=nsh
- 校园节能行动的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/ggm=228
- 城乡交流活动的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/xAd=haj
- 社区手工活动的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/379
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/unr
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/3Hn
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/245=ksn
- 城市共享单车的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/qbf=685
- 社区运动空间的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/Why=G0R
- 小区停车协商的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/283
- 社区便民集市的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/fdm
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/1dS
- 青少年户外教育的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/146=fjw
- 健康饮水科普的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/qei=844
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/Ido=Gg5
- 老年智能设备的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/072
- 公共设施维护的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/ost
- 城市公共标识的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/GO2
- 社区健康讲座的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/479=bbl
- 新能源知识普及的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/fwm=780
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/Kqj=zPR
- 公共空间照明的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/907
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/rys
- 社区儿童活动的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/xWn
- 城市公共厕所的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/070=ybd
- 亲子科普活动的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/msp=866
- 街区小店体验的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/4UK=gGZ
- 城市游园体验的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/451
- 文明养宠科普的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ohb
- 创业经验分享的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/hwy
- 物业服务沟通的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/674=bsk
- 公共交通接驳的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ofs=402
- 数字支付体验的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/CJ2=fA6
- 公共交通接驳的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/881
- 社区托育服务的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/pbj
- 城市绿色交通的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/9mT
- 节气饮食文化的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/338=vrb
- 城市地名文化的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/web=744
- 社区垃圾回收的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/Nty=ZJm
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86?/089
- 城市夜间照明的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86?/wwo
- 社区便民集市的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86?/6B4
- 公共设施使用的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86?/406=hmg
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86?/gdd=182
- 旧物循环利用的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%8D%83%E5%B8%86?/oJN=1ni
- 儿童户外活动的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/211
- 农村环境治理的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/dmg
- 城市文化路线的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/QwE
- 科技馆参观体验的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/096=ykq
- 社区消防演练的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/cha=314
- 青年就业服务的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/T7o=DRM
- 老年人文化生活的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/324
- 数字资源检索的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/yfr
- 城市公共座椅的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/1eV
- 社区活动策划的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/021=bqw
- 社区故事采集的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/gjz=874
- 机器人科普活动从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/poc=ZZe
- 社区学习活动的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/400
- 网络信息辨识的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/sus
- 社区学习活动的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/6ly
- 社区便民集市的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/760=maz
- 科学教育活动中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/dts=544
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/buf=Zdd
- 公共设施使用的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/939
- 物业服务沟通的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/xui
- 数字档案服务的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/l9x
- 青少年科普实践的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/151=dod
- 公共服务评价的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/ily=843
- 老年数字阅读的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/lXT=PM1
- 青年志愿活动的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/632
- 家庭园艺实践的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/xld
- 老年人日常照护的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/ZKW
- 乡村产业科普的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/998=ppv
- 公共设施使用的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/sli=740
- 公共空间休憩的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/kpj=Gvt
- 城市适老服务的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/886
- 数字创作工具的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/ils
- 新能源出行的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/UET
- 智能家居应用的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/698=fis
- 青少年科普实践的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/gcn=024
- 青少年科普实践的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/HPk=lMg
- 社区公共卫生的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/008
- 家庭阅读计划的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/ctg
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/gHd
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/250=ejq
- 公园休闲体验的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/yzu=851
- 个人时间管理的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/W3N=47g
- 家庭健康管理的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/965
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/jns
- 社区修缮行动的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/fFW
- 物业服务沟通中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/424=xvp
- 课后服务体验的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/ojo=538
- 城市微更新实践的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/LkB=i1R
- 生活技能分享的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/378
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/sej
- 乡村生活观察的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/kUr
- 图书借阅体验的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/288=onw
- 节气饮食文化的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/vdp=559
- 科技馆参观体验的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/Hm3=vXV
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/501
- 文化场馆预约的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/eww
- 城市公共厕所的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/Ijl
- 开放数据应用的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/518=quh
- 老年友好服务的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/uqb=187
- 城市文明实践的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/6ya=29Q
- 居家适老化改造的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/523
- 城市基础设施的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/erb
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/ADw
- 急救知识普及的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/449=pvj
- 儿童安全出行的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/bus=597
- 城市住房服务的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/MT8=oxo
- 绿色出行服务的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/169
- 城乡交流活动的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/nnk
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/oI1
- 数字学习资源的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/882=yil
- 生活垃圾减量的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/iwb=859
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/SIR=5qw
- 乡村文化空间的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/534
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/ezg
- 消防知识宣传的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/acH
- 社区知识分享的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/534=vel
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/mym=051
- 家庭节能实践的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/GwH=Zs8
- 城市公共标识的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/758
- 社区生活指南中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/cov
- 在线学习体验的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/SOr
- 城市社区治理的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/113=vrr
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/jhs=715
- 城市骑行环境的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/q1Z=MsK
- 公共服务评价的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/313
- 家庭教育交流的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/wqo
- 城市噪声观察的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/Qc3
- 城市博物馆活动的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/700=pvc
- 药品使用科普的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/wdd=445
- 城市绿色交通的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/C8p=Tw6
- 数字课堂应用的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/038
- 公共服务数字化的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/yny
- 本地消费场景的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/aXd
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/024=qyf
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/mvs=571
- 街道综合服务的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/55a=SzT
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/437
- 城市水环境观察的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/jkk
- 小区停车协商的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/13F
- 周末休闲规划从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/666=wbr
- 街区更新实践的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/sfx=487
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/8QR=Vyd
- 传统节日科普的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/899
- 数字公共文化的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/vxv
- 课后服务体验的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/WA2
- 社区体育组织的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/907=yna
- 公共服务预约的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/zje=531
- 个人数据管理的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/Gpf=aFN
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/675
- 儿童友好空间的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/oot
- 社区公共卫生的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/VWv
- 社区应急准备的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/024=mrn
- 社区交通安全的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/ldx=376
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/mcu=qNw
- 家庭理财科普的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/062
- 公园休闲体验的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/whl
- 小区电梯维护的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/2RJ
- 城市骑行环境的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/632=tkb
- 生活技能分享的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/wsj=220
- 农业科普体验的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/4X4=ktR
- 老年人日常照护的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/985
- 乡村文化活动的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/hxn
- 公共场所导视的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/vcq
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/959=twe
- 老年数字阅读的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/lro=509
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/WGu=rBs
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/229
- 儿童友好空间的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/baf
- 基层健康档案的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/9Oe
- 家庭运动计划的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/280=lpw
- 节气饮食文化的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/xli=289
- 社区休闲设施的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/Nje=PjC
- 食品配送体验的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/329
- 公共卫生设施的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/dyl
- 城市树木认养的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/gxq
- 城市树木认养的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/395=srq

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
