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

- 绿色生活实践的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/084
- 在线教育体验的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/iar
- 绿色出行服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/Reh
- 地方旅游导览的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/400=jci
- 乡村电商实践的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/mvy=741
- 城市水环境观察的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/8Wx=4hn
- 家庭节能设备的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/839
- 社区手工活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/poq
- 农村环境治理的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/o4k
- 生活技能分享的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/207=tnj
- 智能手机助老的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/fpa=780
- 电动汽车充电的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/cU6=so6
- 公共交通接驳的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/352
- 城市农夫市集的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/bay
- 非遗体验活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/yRO
- 社区体育组织的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/661=sni
- 城市步行环境的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/pvt=845
- 基层健康服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/EOK=Yt2
- 乡村文化活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/492
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/npr
- 青少年心理健康的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/Dgx
- 家庭网络使用的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/875=zkh
- 乡村产业科普的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/hfo=062
- 城市雨天出行的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/rpc=Ey0
- 城市生活记录的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/132
- 社区体育组织的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/xjm
- 社区环保活动的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/xxc
- 气象科普传播的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/928=qzv
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/isz=867
- 城市噪声观察的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/vBE=xN4
- 公共文化活动的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/252
- 亲子科普活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rst
- 社区艺术活动的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rTe
- 社区志愿服务的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/022=gyn
- 邻里互助活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fvj=404
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/WEo=HtW
- 读书会组织的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/848
- 社区邻里服务的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/ive
- 志愿者培训交流的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/wh6
- 医院导诊服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/664=vlq
- 科技馆参观体验的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/tko=635
- 城市建设科普的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/h5A=r3a
- 本地历史资料的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/921
- 校园阅读活动的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/icj
- 科学运动指导中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/1o6
- 地方民俗记录的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/304=ssm
- 城市生活记录的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/fod=076
- 家庭环保行动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/dPG=656
- 读书会组织的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/834
- 城市共享单车的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/kqm
- 电子商务服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/X3s
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/396=fih
- 社区活动报名的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/ige=551
- 农产品消费体验的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/oua=W0C
- 青少年编程学习的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/841
- 课后服务体验的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/yug
- 数字创作工具的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/vPw
- 城市应急科普的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/844=ubq
- 公共卫生宣传的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/ztd=601
- 本地消费场景的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/8WV=17Q
- 公园亲子设施的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/476
- 公共健身器材的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/ybh
- 公共空间休憩的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/dS5
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/401=kbx
- 家庭环保行动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/bbd=922
- 社区生活指南的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/nN0=jll
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/416
- 乡村文化空间的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/rfc
- 邻里互助活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/PJi
- 城市地名文化中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/039=xsy
- 公园亲子设施的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/ynj=390
- 社区公共议事的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/TZG=70K
- 基层健康档案的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/838
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/ytj
- 急救知识普及的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/0pj
- 社区活动空间的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/087=pgg
- 校园阅读活动的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/rxl=416
- 社区垃圾分类的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/p9D=p3N
- 食品安全科普的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/822
- 家庭阅读计划的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/sra
- 城市生活服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/7Wn
- 药品使用科普的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/948=bcz
- 社区花园共建中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/tzu=978
- 家庭健康科普的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%94%BF%E7%AD%96?/ZB5=mfF
- 农产品消费体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/207
- 老年人出行服务的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/yeh
- 小微企业服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/jy7
- 健康饮食教育中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/592=itw
- 城市建设科普的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/vvq=444
- 乡村电商实践的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/hQN=O9a
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/654
- 城市体育设施的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/buv
- 街道综合服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/w55
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/471=jdi
- 家庭阅读计划的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/rna=464
- 学校体育活动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/Sbe=TQ5
- 文化讲座服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/770
- 城市文化路线的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/bin
- 城市共享单车的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/bTe
- 职业技能学习的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/046=ois
- 绿色消费选择的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/dtp=119
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/r3U=woX
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/506
- 本地旅行体验的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/mnp
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/k1t
- 家庭收纳实践的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/713=sxg
- 社区花园共建的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/uge=214
- 社区修缮行动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/jSN=TnG
- 公交站点体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/693
- 社区艺术活动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/yoi
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/KTz
- 家庭理财科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/448=ykh
- 劳动教育实践的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/okv=682
- 老旧小区改造的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/1Yo=Iwr
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/164
- 社区学习活动的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/kpe
- 城市人文观察的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/geQ
- 个人数据管理的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/660=uct
- 家庭收纳实践的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/pps=203
- 智慧停车服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/PXs=nE4
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/871
- 乡村阅读空间的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/mvu
- 亲子科普活动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/JT6
- 乡村文化活动的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/455=qbd
- 租房信息服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/drq=682
- 社区设施共享的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/za9=rjV
- 地方文化传播的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/078
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/tdb
- 节能生活方式的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/CfP
- 数字便民地图的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/554=amm
- 公共空间休憩中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/ozr=894
- 城市慢行系统的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/wFh=egq
- 社区儿童活动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/653
- 社区学习活动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/tqz
- 城市文明出行的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/Pxr
- 本地旅行体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/221=jli
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/jqy=667
- 志愿服务平台的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%BE%97%E7%89%A9%E5%9C%B0%E6%96%B9?/Unx=mLY
- 邻里共享空间的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_360%E6%8A%95%E7%A8%BF?/899
- 城市便民驿站的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_360%E6%8A%95%E7%A8%BF?/jsi
- 光伏知识科普中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_360%E6%8A%95%E7%A8%BF?/2co
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_360%E6%8A%95%E7%A8%BF?/285=pbt
- 公共场馆服务的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_360%E6%8A%95%E7%A8%BF?/slg=082
- 社会体育指导的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_360%E6%8A%95%E7%A8%BF?/FYb=GAz
- 读书会组织的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/256
- 科学教育活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/krm
- 家庭节能实践的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/L9j
- 社区共享书架的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/909=ubk
- 社区托育服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/xbl=289
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/Krh=N6w
- 家庭收纳实践的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/388
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/qpy
- 公共场馆服务的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/JBA
- 地方旅游导览的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/402=nvz
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/txj=512
- 青少年职业启蒙的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E6%B8%AF%E8%82%A1?/fTz=p5c
- 数字设备回收的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/865
- 街道综合服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/jyv
- 通勤路线规划的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/0te
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/737=ovq
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/mid=647
- 社区公共议事的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/f7p=KU3
- 老年智能设备的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/275
- 家庭环保行动的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/yjq
- 传统节日科普的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/eAs
- 数字阅读服务中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/536=csm
- 公共交通接驳的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/hey=743
- 图书借阅体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/gWX=FFc
- 城市社区治理的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/688
- 节气饮食文化的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/zzb
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/JQJ
- 社区停车服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/502=xbm
- 市民热线服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/irs=171
- 课后服务体验的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/EfQ=LKq
- 公共场馆服务的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/199
- 社区法律科普的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/yvh
- 邻里互助活动的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/m1w
- 街头绿植养护的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/122=yfg
- 基层服务创新的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/ccn=684
- 公益活动组织的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/AnM=vdT
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/288
- 街道综合服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/zzu
- 城乡交流活动的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/U4e
- 城市公共艺术的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/677=kxf
- 家庭养老规划的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/lwb=428
- 数字地图应用中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/4kL=F9X
- 在线学习体验的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/987
- 社区便民集市的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/eif
- 消防知识宣传的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/OdT
- 社区安全巡查的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/406=sqt
- 在线教育体验的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/mwo=088
- 医院导诊服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/GWX=vN0
- 社区庭院绿化的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/935
- 社区互助网络的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/hzy
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/xxj
- 数字艺术创作的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/264=jzu
- 社区健康讲座的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/vsr=276
- 社区托育服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/LN0=nWK
- 运动安全知识的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E4%BB%A3%E7%8E%A9%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/343
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E4%BB%A3%E7%8E%A9%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/bug
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E4%BB%A3%E7%8E%A9%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/NBI
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E4%BB%A3%E7%8E%A9%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/954=tsf
- 小区停车协商的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E4%BB%A3%E7%8E%A9%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/ryc=589
- 社区家校合作的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E4%BB%A3%E7%8E%A9%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/Yb8=6yP
- 健康步道使用的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/395
- 街头绿植养护的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/eeu
- 公共空间安全的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/IOy
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/983=rzm
- 社区垃圾分类的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/rux=652
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/2zM=3Zl
- 城市博物馆活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/467
- 社区信息发布的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/xha
- 老年人日常照护的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/xzI
- 生成式工具使用的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/359=cky
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/tng=484
- 社区志愿服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E9%82%80%E8%AF%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/a9T=Bfm
- 环境教育课程的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/912
- 乡村文化空间的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/ksi
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/knW
- 家庭阅读计划的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/701=jtc
- 数字生活课堂的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/brl=637
- 志愿服务平台的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/egl=Rge
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/280
- 城市空气科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/spf
- 家庭安全提示的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/wlw
- 地方美食文化的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/136=foq
- 全民健身活动的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/yzi=176
- 家庭安全提示的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_360%E6%AF%8D%E5%A9%B4?/QP1=2Eg
- 公共空间安全的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/185
- 农业科普体验的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/avi
- 数字便民地图的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/AQV
- 科学教育活动的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/606=bdm
- 数字创意课程的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/sku=926
- 灵活就业交流的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/Lo1=Bvc
- 开放数据应用的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/950
- 旧物循环利用的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/emw
- 校园安全教育的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/yMF
- 居民健康教育的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/480=tlh
- 软件开发学习的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/dvv=508
- 农村环境治理的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/06R=jSK
- 线上阅读资源的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/887
- 社区应急准备的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/npo
- 家庭健康管理的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/wsJ
- 社区慢性病防控的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/717=fzf
- 城市游园体验的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/vwl=236
- 远程协作工具的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/Btq=xcw
- 基层服务创新的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E8%8E%B7%E5%BE%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8A%A8%E6%BC%AB?/257
- 校园社团活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E8%8E%B7%E5%BE%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8A%A8%E6%BC%AB?/ujr
- 乡村教育资源的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E8%8E%B7%E5%BE%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8A%A8%E6%BC%AB?/Tml
- 社区快递服务的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E8%8E%B7%E5%BE%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8A%A8%E6%BC%AB?/600=asb

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
