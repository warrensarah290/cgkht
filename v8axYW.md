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

- 图书馆数字服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/899
- 网络安全教育的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/vsh
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/hmU
- 新能源知识普及的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/755=rji
- 邻里互助活动的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/npi=695
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/Hir=cRu
- 小微企业服务的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/429
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/bql
- 开放数据应用的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/99l
- 创业经验分享的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/412=sto
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/vjf=255
- 乡村生态观察的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/Lbi=FGp
- 老年数字阅读的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/479
- 社会体育指导的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/eya
- 亲子科普活动的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/t3P
- 在线学习体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/153=tcd
- 小区电梯维护的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/rcr=437
- 城市适老服务的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/NOk=n5A
- 城市社区治理的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/639
- 城市适老服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/ymn
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/HM6
- 社区志愿服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/594=rjb
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/lom=388
- 便民服务窗口的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/0mO=oar
- 乡村公共服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E8%A7%82%E7%82%B9?/347
- 公共服务数字化的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E8%A7%82%E7%82%B9?/csp
- 城市空气科普的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E8%A7%82%E7%82%B9?/5l9
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E8%A7%82%E7%82%B9?/637=pjb
- 公共空间照明的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E8%A7%82%E7%82%B9?/lmb=741
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E8%A7%82%E7%82%B9?/ud6=Dol
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/730
- 街区小店体验的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/byz
- 图书馆数字服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/Jwo
- 数字支付体验的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/426=bem
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/vdp=941
- 传统节日科普的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/Re7=xFh
- 乡村生活观察的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/438
- 安全出行教育的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/rdr
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/kOy
- 周末休闲规划的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/150=rgl
- 在线学习体验的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/mwa=928
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/1b8=0kY
- 家庭理财科普的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/168
- 非遗课堂体验的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/akm
- 社区花园共建的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/Lpo
- 口袋公园建设的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/865=xtr
- 家庭养老规划的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/swz=074
- 农村环境治理的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/SoT=cEe
- 小区公共照明的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/206
- 家庭运动计划的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/zez
- 城市绿色交通的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/khm
- 城市水环境观察的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/941=fne
- 科学信息获取的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/pur=473
- 乡村公共文化中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/7B4=nPX
- 地方旅游导览的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/291
- 城市共享单车的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/vfo
- 城市共享单车的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/hmh
- 家庭照护支持的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/798=hct
- 公共服务沟通的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/kfy=231
- 社区互助网络的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/wR2=rlp
- 健康信息获取的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/455
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/fhs
- 科学健身方法的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/5qk
- 公共交通接驳的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/650=xna
- 邻里共享空间的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/pjd=572
- 社区互助网络的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/YD1=Sn3
- 城市微更新实践的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/764
- 数字创作工具的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/xcz
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/ldP
- 家庭理财科普的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/709=tig
- 城市适老服务的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/jhk=762
- 城市树木认养的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/N3u=X66
- 家庭网络使用的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/148
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/tfk
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/1wI
- 地方旅游导览的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/495=hed
- 乡村教育资源的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/bug=031
- 骑行路线规划的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/WPf=ESW
- 地方文化传播的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/251
- 人工智能科普的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/bbe
- 应急物资管理的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/qZY
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/565=kct
- 城乡交流活动的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/opw=943
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/CNO=8ce
- 城市适老服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/589
- 社区宠物管理的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/xei
- 儿童运动体验的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/b6E
- 社区活动空间的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/486=rsi
- 家庭饮食安排的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/gbi=728
- 全民健身活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/xdJ=Uok
- 街头绿植养护的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/495
- 家庭环保行动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/poh
- 数字素养提升的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/DWW
- 城市可持续生活的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/338=ima
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/txt=321
- 绿色办公实践的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/lCs=VLl
- 城市文化路线的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%AE%89%E9%98%B2?/449
- 数字课堂应用的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%AE%89%E9%98%B2?/gta
- 邻里共享空间的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%AE%89%E9%98%B2?/5pv
- 城市地名文化的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%AE%89%E9%98%B2?/401=cps
- 校园社团活动的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%AE%89%E9%98%B2?/kom=746
- 儿童安全出行的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%AE%89%E9%98%B2?/FCr=EDR
- 老年人出行服务的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/287
- 公益活动组织的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/cae
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/iN7
- 数字政务体验的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/396=kdp
- 城市树木认养的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/xad=564
- 城市农夫市集的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/RGg=q0l
- 公共场所导视的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/665
- 小区电梯维护的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/pln
- 数字政务体验的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/pYL
- 城市绿色交通的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/804=xhe
- 城市地名文化的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/lgz=102
- 亲子科普活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/wJv=sUH
- 地方美食文化的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/515
- 社区托育服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/gqf
- 居家适老化改造的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/Sw4
- 开放式学习空间的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/557=irp
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/kwu=659
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/ZFF=Km8
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/992
- 城市共享单车的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/mxx
- 社区宠物管理的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/Q30
- 电动汽车充电的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/204=rug
- 社区慢性病防控的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/dxm=528
- 社区体育组织的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/Xio=bWq
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/679
- 社区快递服务的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/hgf
- 青年职业探索的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/r9A
- 社区学习活动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/091=ljt
- 社区托育服务的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/hvg=659
- 城市生活服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/e3H=kuV
- 机器学习入门的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/142
- 公园休闲体验的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/dgo
- 社区防暑服务的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/qf6
- 公交无障碍服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/127=lyx
- 健康饮食教育的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/dsy=555
- 城市公共标识的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/oV6=lha
- 青少年编程学习中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/650
- 家庭急救准备的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/adt
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/Eoe
- 小区公共照明的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/591=qfo
- 市民意见收集的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/rvz=049
- 便民服务窗口的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/40m=iyu
- 城市夜间照明的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8E%86%E5%8F%B2?/796
- 市民意见收集的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8E%86%E5%8F%B2?/rkc
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8E%86%E5%8F%B2?/GEr
- 农业科普体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8E%86%E5%8F%B2?/299=csh
- 家庭科学教育的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8E%86%E5%8F%B2?/lia=823
- 社区设施共享的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8E%86%E5%8F%B2?/ZcM=39Q
- 社区菜市场服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/559
- 绿色消费选择的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/blv
- 城市夜间生活的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/ZgH
- 公交无障碍服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/740=mco
- 学校食育活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/njd=263
- 急救知识普及的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/5Pg=hYa
- 城市空气科普的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/684
- 环境监测科普的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/vpd
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/Bx3
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/549=evy
- 街区道路维护的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/iet=390
- 科普展览体验的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/TTx=jta
- 公共图书馆服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/425
- 小区公共照明的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/akn
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/y9Q
- 社区托育服务的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/699=agl
- 社区共享书架的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/dlh=471
- 乡村教育资源的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/Ug2=IUf
- 食品安全科普的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/694
- 学校食育活动的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/pct
- 家庭健康管理的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/Jfc
- 城市应急广播的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/525=zxz
- 传统节日科普的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/seq=583
- 地方美食文化的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/ewR=nn8
- 城市应急广播的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%9B%98%E7%82%B9?/674
- 家庭环保行动的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%9B%98%E7%82%B9?/aoz
- 绿色生活实践的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%9B%98%E7%82%B9?/TW5
- 乡村文化空间的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%9B%98%E7%82%B9?/703=nwq
- 家庭健康科普中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%9B%98%E7%82%B9?/pdm=743
- 公共空间安全的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%9B%98%E7%82%B9?/i1m=iJu
- 社区生活指南的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/293
- 地方旅游导览的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/blk
- 城市水环境观察的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/J8E
- 信息无障碍体验的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/845=mla
- 城市人文观察的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/gus=316
- 无障碍出行的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/leF=8Ul
- 居家适老化改造的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/708
- 校园阅读活动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/nvz
- 安全出行教育的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/5X1
- 乡村文化空间的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/962=sbh
- 儿童户外活动的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/koe=631
- 社区学习活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/vJ7=Axl
- 数字地图应用的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/556
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/hbo
- 软件开发学习的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/o3i
- 食品配送体验的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/954=lfo
- 市民意见收集的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/ats=998
- 乡村公共阅读的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/I0Z=LKu
- 公共场所导视的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/186
- 志愿服务平台的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/zww
- 老年数字阅读的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/pOW
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/331=rqd
- 社区健康讲座的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/jmm=292
- 公共设施维护的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/Apx=hAZ
- 乡村文化活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/918
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/tux
- 乡村电商实践的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/3Jy
- 食品安全科普的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/858=efy
- 传统手工艺体验的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/ofd=607
- 城市文化路线的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/18l=sP5
- 家庭节能设备的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/226
- 社区志愿服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/pcb
- 健康饮水科普的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/0JL
- 儿童友好空间的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/365=jxl
- 社区绿色空间的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/mjx=304
- 药品使用科普的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%85%AB%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%9B%BD%E9%99%85?/6El=xkh
- 通勤路线规划的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/811
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/zwm
- 公园休闲体验的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/tOJ
- 城市适老服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/555=lzo
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/lcn=645
- 跨代沟通活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8F%B8%E6%B3%95?/Je7=0S2
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/960
- 公共健身器材的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/ihl
- 街区更新实践的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/AbC
- 电动汽车充电的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/468=lwu
- 社区设施共享的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/nmf=664
- 邻里互助活动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/LuZ=jCU
- 地方民俗记录的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/664
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/euq
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/3vq
- 低碳社区实践的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/568=ltm
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/lhs=883
- 居家防滑改造的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/vLW=uU7
- 地方文化传播的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/406
- 儿童阅读角的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/alc
- 社区文化节活动的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/ptv
- 数字公共文化中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/233=itb
- 社区阅读服务的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/uom=424
- 市民意见收集的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/E1i=1ca
- 科学教育活动的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/049
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/vcy
- 公共文化活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/Y8M
- 城市绿色交通的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/169=kqq
- 非遗课堂体验的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/uua=819
- 社区便民集市的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/8oQ=Hxt
- 健康信息获取的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/222
- 基层健康服务的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/eww
- 城市便民驿站的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/GUs
- 城市微更新实践中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%A8%E6%8A%A5?/324=eee

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
