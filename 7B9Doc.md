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

- 社区交通安全的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/qzi=975
- 本地历史资料的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/38q=gv3
- 本地历史资料的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/010
- 社区垃圾回收的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/ojr
- 公共空间安全的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/Rw9
- 智慧城市体验的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/187=vzq
- 生成式工具使用的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/qrs=683
- 社区消防演练的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/g5G=Rcf
- 数字便民地图中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/974
- 公共健身器材的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/ksc
- 老年人文化生活的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/U59
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/170=ogf
- 公共场所导视的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/nwu=278
- 社区快递服务的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%89%9B%E7%89%9B%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E8%AE%BF%E8%B0%88?/esS=5mL
- 社区艺术活动的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/108
- 城市公共饮水的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/gvb
- 城市步行友好的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/XWj
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/639=qrs
- 远程协作工具的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/iyc=738
- 基层健康服务的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/Pgp=Amj
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/113
- 城市体育设施中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/lpg
- 家庭网络使用的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/IbL
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/819=sxj
- 社区便利生活的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/oxt=040
- 公共文化活动的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/t6Y=s8x
- 数字公共文化的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/367
- 社区商业活力的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/lys
- 城市雨天出行的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/0r6
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/283=uyy
- 乡村文化活动的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/kuz=322
- 光伏知识科普的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%A4%B4%E6%9D%A1?/br3=kf4
- 社区活动策划的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/662
- 便民维修服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/crg
- 农业科普体验的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/Z0N
- 社区快递服务的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/199=maa
- 城市应急科普的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/suw=797
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/tI3=ztN
- 城市基础设施的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/080
- 软件开发学习的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/ufx
- 社区手工活动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/OFz
- 青少年心理健康的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/451=iow
- 社区科普课堂的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/awx=090
- 家庭阅读计划的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/sIp=OCm
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/973
- 基层服务创新的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/ypd
- 节气饮食文化的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/8bd
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/340=ccz
- 环境教育课程的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/nnl=237
- 劳动教育实践的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/VMo=E4f
- 电子商务服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/437
- 城市文明实践的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/own
- 小区公共照明的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/QFT
- 社区活动报名的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/949=pyc
- 公共空间休憩的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/dtg=770
- 社区安全巡查的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/UNk=6I7
- 线上阅读资源中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/673
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/djy
- 休闲运动入门的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/Gcu
- 社区宠物管理中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/275=eyd
- 儿童运动体验的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/whq=453
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%9F%E8%B4%A7?/m7m=k3n
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/842
- 开放式学习空间的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/zpx
- 科学信息获取的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/GbU
- 劳动教育实践的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/806=kyx
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/lxl=546
- 社区快递服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/xi9=jMa
- 社区应急准备的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/868
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/dfy
- 生活服务数字化中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/gjb
- 乡村产业科普的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/957=cdj
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/lbp=066
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/0Zs=uYG
- 乡村生活观察的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E?/183
- 数字生活课堂的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E?/vjz
- 社区共享书架的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E?/oLx
- 公共交通接驳的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E?/039=mqs
- 城市建设科普的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E?/uvo=913
- 公共空间休憩的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E?/JW0=Ubm
- 居家防滑改造的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/611
- 科技馆参观体验的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/ocj
- 城市公共空间的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/Srg
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/546=gio
- 社区交通安全的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/rks=555
- 生活垃圾回收的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/N3V=KAZ
- 小区公共照明的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/147
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/ybz
- 校园阅读活动的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/KsJ
- 科学运动指导的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/855=svz
- 公共空间照明的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/fjm=271
- 健康饮水科普的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/igE=0zu
- 社区儿童活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/528
- 城市农夫市集的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/wzn
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/jbO
- 农业科普体验的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/724=wpg
- 乡村文化活动的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/pjv=482
- 基层健康档案的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/S2Y=8N7
- 生成式工具使用的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/105
- 地方美食文化的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/avq
- 数字政务体验的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/DbU
- 软件开发学习的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/678=oxa
- 数字档案服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/drm=646
- 生活技能分享的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/981=q2v
- 绿色出行服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/748
- 节能家电使用的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/lyv
- 乡村文化活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/cnb
- 社区志愿服务的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/265=dzf
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/twk=965
- 光伏知识科普的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/Frx=OpG
- 乡村公共文化的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/491
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/zbz
- 街区更新实践的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/p0S
- 社区便民集市的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/352=pfd
- 社区消防演练的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/sta=082
- 城市基础设施的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/vlO=dDr
- 社区家政服务的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/551
- 公共场馆服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/sct
- 街区更新实践的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/rcu
- 数字生活课堂的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/883=mzu
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/zhm=125
- 口袋公园建设的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/vmB=glK
- 公共健身器材的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/272
- 公共健身器材的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/dtx
- 终身学习资源的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/Xrg
- 数字生活课堂的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/934=iqc
- 街头绿植养护的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/fzy=296
- 城市便民驿站的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/ox2=LI5
- 生活服务数字化的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/047
- 地方旅游导览的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/lnn
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/O0G
- 社区应急准备的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/820=tfz
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/vdq=025
- 儿童安全出行的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/WhW=oxf
- 软件开发学习的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/463
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/ild
- 公共服务沟通的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/SvI
- 城市可持续生活的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/931=ydc
- 社区便民集市的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/wkc=127
- 生活服务数字化的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/Wiv=xNS
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%BF%AB%E8%AE%AF?/127
- 城乡交流活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%BF%AB%E8%AE%AF?/cpv
- 社区绿色空间的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%BF%AB%E8%AE%AF?/5Nn
- 城市公共饮水的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%BF%AB%E8%AE%AF?/994=esp
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%BF%AB%E8%AE%AF?/peu=716
- 公共服务评价的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%BF%AB%E8%AE%AF?/PRK=fA7
- 绿色生活实践的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/262
- 本地历史资料的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/mzv
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/wab
- 社区托育服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/339=eny
- 公共空间照明的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/vua=267
- 公共场所导视的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/vnw=fqc
- 社区绿色空间的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/540
- 绿色校园实践的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/uhu
- 健康饮水科普的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/bxp
- 家庭食品保存的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/433=pzl
- 城市步行环境的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/pfn=653
- 就业技能培训的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/MSj=kvL
- 数字生活课堂的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/148
- 数字支付体验的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/ipu
- 社区文化传播的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/PCh
- 学校食育活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/328=jjl
- 青少年心理健康的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/rgj=539
- 智能家居应用的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/BJb=Czx
- 城市人文观察的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/880
- 无障碍信息设计的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/dln
- 公共服务预约的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/PH7
- 家庭园艺实践的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/925=ouz
- 通勤路线规划的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/cvi=578
- 新能源知识普及的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/Yf9=gpU
- 城市公共空间的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/524
- 城市步行友好的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/ynf
- 数字学习资源的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/muw
- 读书会组织的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/706=joe
- 城市社区治理的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/vih=132
- 智能家居应用的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/Mqh=oPg
- 地方民俗记录的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/060
- 社区手工活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/xfu
- 城市慢跑路线的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/TVp
- 家庭安全提示的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/445=nbo
- 小区电梯维护的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/cdb=501
- 职业技能学习中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/IKb=FQA
- 城市博物馆服务的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/160
- 创业经验分享的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/rfq
- 公益活动组织的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/sVs
- 社区活动报名的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/138=tjz
- 儿童阅读角的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/tsj=932
- 儿童友好街区的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/LdO=YyT
- 公共设施使用的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/491
- 社区文化节活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/qdu
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/3if
- 本地历史资料的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/700=pxn
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/zea=017
- 个人数据管理的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/zp3=v58
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/853
- 社区互助网络的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/dbj
- 社区教育资源的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/9MS
- 绿色生活实践的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/804=fph
- 软件开发学习的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/rwo=184
- 公共交通接驳的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/Jqc=7OD
- 数字艺术创作的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%85%A7%E7%9C%BC?/134
- 数字便民地图的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%85%A7%E7%9C%BC?/zon
- 便民服务窗口的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%85%A7%E7%9C%BC?/QEs
- 城市绿色交通的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%85%A7%E7%9C%BC?/530=tdn
- 青年志愿活动中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%85%A7%E7%9C%BC?/vzq=888
- 城市基础设施的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%85%A7%E7%9C%BC?/kR7=K9B
- 社区垃圾回收的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/330
- 校园社团活动的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/eei
- 气象科普传播的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/n2Y
- 家庭教育交流的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/077=amv
- 数据分析入门的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/ukk=903
- 科技馆参观体验的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/Ri0=kdZ
- 线上阅读资源的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/301
- 社区停车服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/icf
- 租房信息服务的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/O53
- 灵活就业交流的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/597=mhl
- 农村环境治理的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/gbf=849
- 城市公共厕所的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/n3W=mkV
- 邻里共享空间的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/750
- 职业技能学习的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/muw
- 生成式工具使用的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/fLs
- 数字生活课堂的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/752=hdd
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/mad=557
- 口袋公园建设中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/1ti=Y4g
- 软件开发学习的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/294
- 亲子阅读活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/mqm
- 租房信息服务的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/bCF
- 社区教育资源的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/003=tpf
- 科学观察活动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/vag=113
- 青少年科技社团的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/G6v=QgY
- 社区运动空间的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/973
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/mbz
- 城市公共标识的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/eet
- 旧物循环利用的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/211=hvo
- 智慧城市体验的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/kwk=729
- 数字资源检索的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%86%9C%E4%B8%9A?/SVU=BJB
- 城市微更新实践的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/299
- 数字地图应用的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/nqm
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/kXC
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/416=fim
- 青年职业探索的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/lmn=583
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/jty=uku
- 数字支付体验的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/230
- 数据分析入门的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/pip
- 学校食育活动的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/Lp8
- 家庭志愿活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/812=lte
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/iij=720
- 街区小店体验的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/SDD=dLS
- 社区便民服务的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/188
- 家庭急救准备的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/uaj

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
