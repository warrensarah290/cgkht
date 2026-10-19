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

- 休闲运动入门的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/18S
- 社区垃圾回收的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/631=jlh
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/lta=256
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/xqA=odQ
- 便民服务地图的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/292
- 家庭安全提示的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/ubu
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/EAw
- 公共服务沟通的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/033=gfs
- 光伏知识科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/adr=788
- 青少年编程学习的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/VsW=iWd
- 社区菜市场服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/887
- 数字创意课程的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/tlz
- 城市生活服务的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/0cY
- 智能手机助老的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/622=rkg
- 乡村文化空间的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/qtk=986
- 社区便利生活的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/xeC=t0y
- 图书馆数字服务的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/319
- 文明养宠科普的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/rps
- 社区便民服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/FBu
- 社区交通安全的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/907=yzv
- 城市步行友好的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/qid=085
- 环境监测科普的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/ag6=ub4
- 社区信息发布的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/815
- 城市公共标识的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/xle
- 本地消费场景中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/SPV
- 社区活动报名的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/693=jhq
- 骑行路线规划的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/zgm=410
- 城市水环境观察的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E6%9C%9F%E8%B4%A7?/OwO=ZNd
- 健康饮食教育的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/796
- 家庭阅读计划的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/kau
- 家庭急救准备的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/DMG
- 居民健康教育的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/624=vib
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/olp=566
- 青年职业探索的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/6X6=8oO
- 非遗课堂体验的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/406
- 数字档案服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/qjm
- 社区防暑服务的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/3V4
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/105=cmb
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/ydg=922
- 旧物循环利用的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/HlP=LO7
- 数字创意课程的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/416
- 社区便利生活的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/vsd
- 地方文化传播的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/agM
- 节气饮食文化的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/161=jps
- 市民热线服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/acw=584
- 创业经验分享的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/POP=FqS
- 数字学习资源的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/373
- 农村环境治理的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/zas
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/61K
- 居家防滑改造的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/560=aci
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/eco=795
- 乡村文化活动的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/2v9=wOp
- 公共空间照明的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/779
- 低碳社区实践中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hes
- 地方旅游导览的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/3he
- 街道综合服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/178=haq
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/eie=977
- 乡村公共服务的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/7SZ=ImZ
- 老年人日常照护的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/120
- 安全出行教育的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/eyt
- 城乡公共服务的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/Hyh
- 社区文化节活动的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/233=nwx
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/vpc=890
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/pC4=Pj0
- 居民健康教育的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/830
- 城市空气科普的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/ngo
- 社区环保活动的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/czS
- 环境教育课程的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/098=kdk
- 地方民俗记录的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/pik=898
- 青少年户外教育中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/zTa=CUP
- 社区活动策划的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/099
- 乡村电商实践的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/gqe
- 街区绿化养护的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/Hwu
- 便民服务窗口的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/888=nkg
- 城市文明出行的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/rps=930
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/lpB=jbD
- 城市空气科普的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/106
- 科普展览体验的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/ekc
- 传统节日科普的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/4ka
- 小区停车协商的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/023=vnh
- 社区垃圾回收的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/bos=255
- 急救知识普及的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/6Oz=6JZ
- 城市绿色交通的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/070
- 无障碍出行的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/tvn
- 公共卫生宣传的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/ANY
- 街区小店体验的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/979=fuu
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/iow=642
- 科学运动指导的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/0dz=Kop
- 机器人科普活动的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/556
- 青少年科普实践的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/rbw
- 读书会组织的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/Pxe
- 创业经验分享的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/669=uax
- 青年志愿活动的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/wmq=557
- 全民健身活动的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/w8V=qur
- 城市公共厕所的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/424
- 周末休闲规划的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/uhw
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/Do5
- 社区阅读服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/022=uti
- 城市树木认养的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/xkx=965
- 乡村教育资源的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/r1C=zdi
- 安全出行教育的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/247
- 家庭节能实践的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/jia
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/4Es
- 新能源出行从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/617=pnl
- 学校体育活动的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/uug=309
- 读书会组织从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/nJP=xgF
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%8432%E7%A7%8D%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/203
- 城市展览体验的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%8432%E7%A7%8D%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/jye
- 家庭阅读计划的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%8432%E7%A7%8D%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/Mbd
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%8432%E7%A7%8D%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/876=piu
- 乡村产业科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%8432%E7%A7%8D%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/kpr=399
- 社区家校合作的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%8432%E7%A7%8D%E8%B5%B0%E5%8A%BF_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/usO=t49
- 青少年科普实践的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/674
- 农业科普体验的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/bdt
- 社区家政服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/Oy1
- 乡村公共文化的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/362=qla
- 乡村电商实践的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/aze=487
- 儿童安全出行的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/pnH=1Xq
- 社区托育服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/030
- 灵活就业交流的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/zgp
- 数字地图应用的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/NJ6
- 社区快递服务的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/009=hur
- 节能生活方式的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/kwe=422
- 城市步行友好的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/dss=saD
- 数字艺术创作的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/856
- 城市游园体验的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/afv
- 软件开发学习的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/xJx
- 小区公共照明的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/539=qez
- 乡村生活观察的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/hni=080
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/HVo=4im
- 社区宣传栏更新的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/664
- 社区文化传播的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/gjy
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/H6R
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/841=jnm
- 节约用水实践的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/hor=606
- 小区电梯维护的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/34W=jr2
- 数字支付体验的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%85%A8%E8%BF%87%E7%A8%8B_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/687
- 无障碍出行的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%85%A8%E8%BF%87%E7%A8%8B_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/won
- 城市夜间照明的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%85%A8%E8%BF%87%E7%A8%8B_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/2TD
- 个人数据管理的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%85%A8%E8%BF%87%E7%A8%8B_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/998=blt
- 老年人文化生活的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%85%A8%E8%BF%87%E7%A8%8B_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/gsg=653
- 数字资源检索的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%85%A8%E8%BF%87%E7%A8%8B_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/2Fy=gAX
- 小区公共照明的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/438
- 社区知识分享的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/iqj
- 公共交通接驳的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/ysJ
- 城市水环境观察的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/653=kwe
- 数字生活课堂的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/uke=187
- 智能手机助老的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%9C%9B?/iVJ=bUg
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/368
- 社区文化节活动的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/jed
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/42w
- 公园休闲体验的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/913=lhy
- 社区文化节活动的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/oop=663
- 家庭教育交流的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/zzV=3Yy
- 社区生活指南的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/172
- 绿色办公实践中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/uxy
- 数字档案服务的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/oCr
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/993=hau
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/bvf=068
- 社区交通安全的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/f6m=C7u
- 数字便民地图的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E7%A7%98%E7%B1%8D_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/334
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E7%A7%98%E7%B1%8D_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/kmc
- 社区运动空间的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E7%A7%98%E7%B1%8D_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/o5g
- 社区文化节活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E7%A7%98%E7%B1%8D_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/825=gfj
- 创业经验分享的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E7%A7%98%E7%B1%8D_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/nsm=053
- 无障碍出行的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E7%A7%98%E7%B1%8D_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%91%8A?/XQL=Dq8
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E9%80%9F%E8%A7%88?/605
- 城市微更新实践的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E9%80%9F%E8%A7%88?/cea
- 便民维修服务的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E9%80%9F%E8%A7%88?/9Ov
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E9%80%9F%E8%A7%88?/082=heq
- 创业经验分享的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E9%80%9F%E8%A7%88?/vsj=232
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E9%80%9F%E8%A7%88?/Z8s=jKS
- 科学信息获取的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/964
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/kqn
- 城市夜间生活的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/TZj
- 城市适老服务中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/306=cgn
- 公共空间休憩的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/ebh=893
- 公共场馆服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%87%BA%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/zRI=9Zt
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/913
- 老年运动活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/onp
- 社区健康讲座的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/Dm6
- 校园社团活动中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/845=bge
- 社区便民集市的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/hso=118
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/ZzY=BpA
- 公共空间安全的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/178
- 数字课堂应用的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/sqg
- 本地消费场景的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/IBs
- 亲子科普活动的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/072=sxx
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/njs=652
- 本地历史资料的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/D0d=dev
- 智慧停车服务的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E7%89%B9%E7%82%B9_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/320
- 青年志愿活动的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E7%89%B9%E7%82%B9_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/nng
- 小微企业服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E7%89%B9%E7%82%B9_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/sYa
- 便民信息查询的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E7%89%B9%E7%82%B9_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/838=gnn
- 家庭健康科普的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E7%89%B9%E7%82%B9_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/dgf=437
- 城市微更新实践的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A81%E5%88%86%E5%BF%AB3%E7%89%B9%E7%82%B9_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/FYv=WG7
- 本地消费场景的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/842
- 街区小店体验的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/ioz
- 公益活动组织的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/prZ
- 数字设备回收的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/937=skq
- 科学观察活动的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/khn=454
- 家庭理财科普的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/YjM=X5a
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%80%8E%E6%A0%B7%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/403
- 社区安全巡查的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%80%8E%E6%A0%B7%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/hrm
- 城市便民驿站的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%80%8E%E6%A0%B7%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/Rz9
- 数字支付体验的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%80%8E%E6%A0%B7%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/823=kbg
- 生活技能分享的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%80%8E%E6%A0%B7%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/dbn=349
- 社区养老服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%80%8E%E6%A0%B7%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/U1R=S3d
- 绿色建筑理念的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%94%BF%E7%AD%96?/564
- 租房信息服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%94%BF%E7%AD%96?/pxl
- 数字课堂应用的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%94%BF%E7%AD%96?/aKB
- 农贸市场环境的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%94%BF%E7%AD%96?/222=jzq
- 终身学习资源的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%94%BF%E7%AD%96?/qqj=068
- 老年人日常照护的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%94%BF%E7%AD%96?/tSt=F12
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/001
- 社区公共卫生的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/eke
- 创业经验分享的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/zsq
- 市民意见收集的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/541=nra
- 社区故事采集的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/nok=918
- 旧物循环利用的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/gs9=Kd1
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/762
- 家庭收纳实践的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/ily
- 社区学习活动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/uAz
- 城市体育设施的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/565=iax
- 在线教育体验的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/dbq=174
- 公共场馆服务的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/Edp=mlu
- 跨代沟通活动的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/337
- 就业技能培训的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/jwy
- 健康信息获取的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/GAv
- 便民信息查询的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/194=yvv
- 农贸市场环境的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/cfu=011
- 老年人日常照护的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/Cgc=hma
- 数字公共文化的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/991
- 小区公共照明的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/wtk
- 数字设备回收的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/MpS
- 城市文明实践的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/720=qse
- 城市休闲步道的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/bsi=968
- 城市公共标识的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_5%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/kfb=onj
- 街道综合服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/180
- 城乡公共服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/cjp
- 城市生活服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/h2B
- 志愿服务平台的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/818=wwf
- 城市展览体验的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/eez=242
- 数字支付体验的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_5%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E4%BA%AC%E4%B8%9C%E6%A6%9C%E5%8D%95?/T81=ftq
- 线上阅读资源的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/827
- 城市体育设施的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/qwp
- 数字阅读服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/51Y
- 亲子阅读活动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/267=jls
- 社区慢性病防控的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/lbj=179
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/5JF=oui

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
