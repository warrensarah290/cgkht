# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 周末休闲规划的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%99%BE%E7%A7%91?/bVF
- 绿色办公实践的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%99%BE%E7%A7%91?/309=ajy
- 药品使用科普的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%99%BE%E7%A7%91?/siz=537
- 家庭消费规划的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%99%BE%E7%A7%91?/4nb=I3d
- 社区托育服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/606
- 社区读书角建设的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/hhx
- 老年友好服务的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/0k2
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/959=pdj
- 全民健身活动的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/tpf=471
- 无障碍出行的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/oIU=8WP
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/331
- 城市文化路线的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/mba
- 基层健康服务的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/ESG
- 青少年编程学习的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/635=cxi
- 城市绿色交通的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/usn=015
- 便民服务地图的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/jj3=0O9
- 家庭照护支持的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/627
- 城市噪声观察的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/ylx
- 生活垃圾回收的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/o26
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/255=udg
- 社区家校合作的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/vkr=656
- 灵活就业交流的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/wEl=phL
- 社区快递服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/715
- 社区家政服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/hhu
- 家庭饮食安排的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/r8b
- 农产品消费体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/519=fei
- 网络安全教育的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/yqk=980
- 社区知识分享的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/VF6=H2Z
- 绿色生活实践的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/135
- 在线学习体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/mwx
- 城市展览体验的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/Z7a
- 城市适老服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/305=flp
- 非遗体验活动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/neg=048
- 社区修缮行动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/5wX=08E
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/820
- 社区托育服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/uvh
- 社区邻里服务的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/hpq
- 软件开发学习的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/131=rfm
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/wgm=354
- 健康饮水科普的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/QOR=n1H
- 公共设施维护的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/591
- 社区协商议事的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/mxu
- 节气饮食文化的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/AKl
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/986=arb
- 社区活动策划的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/suc=359
- 城市文化路线的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/wPx=pjV
- 乡村文化活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9?/035
- 社区手工活动的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9?/fhv
- 社区活动报名的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9?/4zn
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9?/775=dnu
- 数字资源检索的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9?/gdi=708
- 城市树木认养的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9?/7D6=usl
- 社区绿色空间的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/953
- 乡村生活观察的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/lty
- 科学健身方法的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/bNN
- 公园亲子设施的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/387=fog
- 生活垃圾减量的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/yim=924
- 志愿服务平台的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/EYB=Sji
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/833
- 公交无障碍服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/jdx
- 图书借阅体验的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/HEF
- 青少年户外教育的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/246=kam
- 家庭用电安全的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/xvq=889
- 志愿者培训交流的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/FVR=qdf
- 城市基础设施的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/350
- 亲子科普活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/jqx
- 人工智能科普的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/sHY
- 生活技能分享的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/129=aae
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/zxk=472
- 城市住房服务的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/BeN=7CG
- 开放数据应用的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/977
- 街道综合服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/sum
- 城市文明实践的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/xKl
- 学校食育活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/459=nik
- 读书会组织的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/bza=904
- 骑行路线规划的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/9w4=hR7
- 科学观察活动的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/212
- 节能生活方式的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/wkw
- 线上阅读资源的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/fla
- 文化场馆预约的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/539=csg
- 科普展览体验的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/zwn=028
- 在线学习体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/ubE=fc8
- 青少年科普实践的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%B5%84%E8%AE%AF?/742
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%B5%84%E8%AE%AF?/ure
- 通勤路线规划的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%B5%84%E8%AE%AF?/XjN
- 社区邻里服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%B5%84%E8%AE%AF?/062=iml
- 公共服务数字化的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%B5%84%E8%AE%AF?/rid=201
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%B5%84%E8%AE%AF?/9tl=mdQ
- 社区故事采集的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/822
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/mhk
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/ojL
- 光伏知识科普的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/296=qzf
- 城市夜间照明的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/bem=084
- 社区垃圾回收的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/0qy=mWG
- 青年职业探索的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/767
- 社区读书角建设的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/ybu
- 全民健身活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/Luf
- 垃圾分类指导的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/717=lwt
- 儿童安全出行中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/fuw=679
- 城市人文观察的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/3Rj=bZz
- 生成式工具使用的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/995
- 城市公共饮水的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/bli
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/vTy
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/546=gqm
- 社区法律科普的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/med=577
- 无障碍出行的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/1bv=ini
- 邻里互助活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/269
- 社区儿童活动的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/bxv
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/kQa
- 公益活动组织的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/057=acd
- 图书借阅体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/poi=356
- 便民服务地图的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/h98=NFh
- 光伏知识科普的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/242
- 城市应急广播的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/swm
- 数字政务体验的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/8LN
- 家庭环保习惯的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/068=hif
- 公共服务评价的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/ipz=657
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/tQb=wS9
- 社区科普课堂的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/752
- 科学健身方法的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/wkq
- 家庭健康科普中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/lWL
- 社区体育组织的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/047=eqv
- 城市建设科普的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/qho=233
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/hmo=TYt
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/071
- 城市文明出行的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/qlc
- 城市基础设施的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/sEQ
- 社区共享书架的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/829=gwb
- 数字课堂应用的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/wro=781
- 非遗体验活动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/wCd=gog
- 城市骑行环境的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/384
- 青少年户外教育的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/jdd
- 家庭志愿活动的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/nAH
- 城市博物馆活动的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/969=cpk
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/npk=659
- 青少年编程学习的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/CJ3=Axx
- 口袋公园建设的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/814
- 基层健康档案的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/bso
- 在线学习体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/tU9
- 城市建设科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/054=nuq
- 环境教育课程的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/kjq=424
- 开放式学习空间的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/QJf=HHa
- 家庭环保习惯的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/663
- 公共交通信息服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/wda
- 环境教育课程的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/yUJ
- 社区商业活力的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/220=fjk
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/flf=790
- 生成式工具使用的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/UO6=6UX
- 环境教育课程的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/701
- 无障碍出行的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/rrj
- 城市夜间照明的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/6Qb
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/390=qjd
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/fef=780
- 智能家居应用的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/Ycu=SqG
- 城市休闲步道的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/659
- 社区休闲设施的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/slx
- 老年人文化生活的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/2Ln
- 公共卫生设施的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/777=qfx
- 居民健康教育的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/zmv=901
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/hPw=lIk
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/257
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/und
- 家庭消费规划的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/Yki
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/297=bgb
- 食品配送体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/dyo=459
- 农业科普体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/Ce7=oC1
- 老旧小区改造的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/830
- 家庭教育交流的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/jop
- 公共空间导览的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/ECK
- 基层服务创新的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/012=pcm
- 街区绿化养护的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/dry=149
- 科学教育活动的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9E-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/btH=ec3
- 儿童户外活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/978
- 开源技术交流的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/leg
- 城市雨天出行的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/731
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/798=ocf
- 科学观察活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/zqo=732
- 青年就业服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/8NH=LxN
- 家庭食品保存的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/364
- 健康信息获取的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/ihm
- 城市水环境观察的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/SL6
- 职业技能学习的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/770=zkt
- 亲子科普活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/ctk=518
- 个人信息保护中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/tjz=MPV
- 家庭教育交流的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/467
- 社区家政服务的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/vzc
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/y05
- 乡村文化空间的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/533=npi
- 本地消费场景的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/eyr=271
- 节约用水实践的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/IPi=zYT
- 社区儿童活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/756
- 文化讲座服务的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/bvk
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/V0o
- 公共健身器材的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/281=fcz
- 文化讲座服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/ovi=582
- 数字支付体验的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/ZYG=qcD
- 乡村教育资源的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/208
- 公园亲子设施的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/tgz
- 公共空间照明的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/RXO
- 街区绿化养护的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/628=vyq
- 居家防滑改造的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/qty=626
- 地方美食文化的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/nEz=pAz
- 图书馆活动策划的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/892
- 家庭养老规划的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/ata
- 日常摄影记录的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/hTa
- 智慧停车服务的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/489=wpd
- 城市游园体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/dre=531
- 公交站点体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E6%B8%B8%E6%88%8F?/e2i=wSD
- 本地消费场景的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A1%8C%E6%83%85?/394
- 公交站点体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A1%8C%E6%83%85?/tjb
- 家庭照护支持的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A1%8C%E6%83%85?/ApL
- 家庭理财科普的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A1%8C%E6%83%85?/709=opw
- 非遗体验活动的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A1%8C%E6%83%85?/vdg=353
- 城市慢行系统的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E8%A1%8C%E6%83%85?/Pny=Vfj
- 社区宠物管理中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_360%E8%B4%A2%E7%BB%8F?/238
- 新能源出行从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_360%E8%B4%A2%E7%BB%8F?/ynj
- 青年志愿活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_360%E8%B4%A2%E7%BB%8F?/kbg
- 城市夜间照明的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_360%E8%B4%A2%E7%BB%8F?/485=cvk
- 老年运动活动的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_360%E8%B4%A2%E7%BB%8F?/dyr=194
- 文化场馆预约的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_360%E8%B4%A2%E7%BB%8F?/xnj=pHE
- 食品安全科普的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/805
- 周末休闲规划的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/rct
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/oC4
- 公共设施维护的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/677=iaf
- 城市应急广播的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/jso=032
- 城市公共艺术的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/Q7X=rrh
- 老年友好服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/136
- 城市骑行环境的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/zoc
- 城市公共饮水的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/MGo
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/743=zrb
- 垃圾分类指导的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/rkx=299
- 线上阅读资源的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/uVn=R6k
- 小区停车协商的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/302
- 数字课堂应用的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/csl
- 公共空间安全的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/jaD
- 城市建设科普的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/546=vlx
- 传统节日科普的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/bql=750
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/RXs=aKt
- 便民信息查询中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/630
- 街道综合服务的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/pak
- 便民服务地图的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/gYV
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/603=ycf
- 生活技能分享的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/jmc=220
- 家庭阅读计划的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/FqH=p6K
- 社区菜市场服务的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/762
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/oim
- 本地旅行体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/Rdp
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/967=tll
- 乡村文化空间的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/koe=414
- 家庭健康科普的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/jSv=Qbl

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
