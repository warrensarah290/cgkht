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

- 城市空气科普的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/885
- 小区公共照明的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/olx
- 节气饮食文化的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/coy
- 公共交通信息服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/953=jlh
- 社区教育资源的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/svf=511
- 数字创作工具的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/lUz=YEA
- 节日文化体验的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/108
- 城市微更新实践的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/hxc
- 城市公共标识的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/XRn
- 绿色消费选择的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/684=myc
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/fdj=392
- 创业经验分享的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/TJE=K7X
- 机器学习入门的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/121
- 城市骑行环境的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/qdi
- 环境监测科普的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/Ovy
- 市民热线服务的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/604=kwv
- 城市住房服务的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/shc=860
- 社区修缮行动的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/UiY=W7f
- 电子商务服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/672
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/jim
- 小区停车协商的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/Y7n
- 社区活动策划的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/677=wut
- 城市生活记录的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/oqe=617
- 城市公共自行车的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E5%A4%A7?/xWS=jye
- 数字便民地图的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/480
- 农业科普体验的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/ndo
- 城市游园体验的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/vGL
- 儿童安全出行的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/435=jog
- 数字设备回收的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/hdb=260
- 城市噪声观察的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/TsV=5Lz
- 城市夜间照明的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/114
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/cot
- 机器人科普活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/Eli
- 亲子科普活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/275=tvt
- 数字设备回收的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/rhh=709
- 社区共享书架的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/ldc=D18
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/320
- 青少年科技社团从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/qaa
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/OEg
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/212=ceg
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/hpa=693
- 社区消防演练的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/uc2=nue
- 城市社区治理的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F_360%E6%8A%95%E7%A5%A8?/248
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F_360%E6%8A%95%E7%A5%A8?/mje
- 家庭食品保存的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F_360%E6%8A%95%E7%A5%A8?/BMI
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F_360%E6%8A%95%E7%A5%A8?/838=bwa
- 在线教育体验的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F_360%E6%8A%95%E7%A5%A8?/exj=671
- 城市步行环境的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F_360%E6%8A%95%E7%A5%A8?/JNE=7me
- 家庭节能设备的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/817
- 儿童户外活动的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/hco
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/iQv
- 社区文化节活动的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/226=gdi
- 小区电梯维护的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/lwf=653
- 青年就业服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/jl1=Uxw
- 街区绿化养护中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/760
- 邻里共享空间的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/mhv
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/MxK
- 公共交通接驳的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/392=smu
- 公共服务预约的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/aqi=999
- 家庭网络使用的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/4hi=7Lp
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/078
- 生成式工具使用的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/buk
- 地方旅游导览的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/hRd
- 绿色生活实践的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/898=obz
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/tir=743
- 儿童友好空间的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/Pai=WyN
- 社区慢性病防控的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/326
- 城市文化路线的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/pis
- 老年人文化生活的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/vHt
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/983=xiv
- 乡村公共阅读的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/nqq=380
- 志愿服务平台的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1_%E8%B0%B7%E6%AD%8C%E5%8D%83%E5%B8%86?/8uf=hjV
- 周末休闲规划的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/834
- 健康信息获取的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/kma
- 休闲运动入门的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/oea
- 青年志愿活动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/827=kha
- 环境教育课程的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/lvp=494
- 节日文化体验的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/3Pb=aeW
- 健康信息获取的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/755
- 家庭网络使用中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/qzs
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/rB1
- 居民健康教育的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/520=wlv
- 乡村生活观察的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/mda=171
- 基层医疗预约的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/pRY=H4T
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/697
- 公共卫生设施的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/hso
- 社区家校合作的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/46z
- 城市文明实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/757=ygv
- 物业服务沟通的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/scr=115
- 创业经验分享的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/pIF=SPG
- 社区托育服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/349
- 公共文化活动的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/mzu
- 乡村公共服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/SXR
- 远程协作工具的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/219=gna
- 数字课堂应用的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/jja=496
- 公共健身器材的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/7ga=hOY
- 社区环保活动的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/189
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/hqq
- 城市骑行环境的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/DDC
- 就业技能培训的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/808=fda
- 图书借阅体验的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/ihy=348
- 创业经验分享的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/1wc=BK9
- 校园社团活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B5%8C%E5%9C%BA%E7%A0%8D%E9%BE%99%E6%98%AF%E5%A5%BD%E4%BA%8B%E8%BF%98%E6%98%AF%E5%9D%8F%E4%BA%8B_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/878
- 城市公共饮水的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B5%8C%E5%9C%BA%E7%A0%8D%E9%BE%99%E6%98%AF%E5%A5%BD%E4%BA%8B%E8%BF%98%E6%98%AF%E5%9D%8F%E4%BA%8B_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/ldd
- 公共服务预约的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B5%8C%E5%9C%BA%E7%A0%8D%E9%BE%99%E6%98%AF%E5%A5%BD%E4%BA%8B%E8%BF%98%E6%98%AF%E5%9D%8F%E4%BA%8B_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/VrU
- 农村环境治理的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B5%8C%E5%9C%BA%E7%A0%8D%E9%BE%99%E6%98%AF%E5%A5%BD%E4%BA%8B%E8%BF%98%E6%98%AF%E5%9D%8F%E4%BA%8B_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/586=myt
- 青少年科技社团的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B5%8C%E5%9C%BA%E7%A0%8D%E9%BE%99%E6%98%AF%E5%A5%BD%E4%BA%8B%E8%BF%98%E6%98%AF%E5%9D%8F%E4%BA%8B_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/jxx=819
- 社区教育资源的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B5%8C%E5%9C%BA%E7%A0%8D%E9%BE%99%E6%98%AF%E5%A5%BD%E4%BA%8B%E8%BF%98%E6%98%AF%E5%9D%8F%E4%BA%8B_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/kQB=mqj
- 老年人文化生活的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%80%86%E9%BE%99%E5%A5%BD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/200
- 社区体育组织的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%80%86%E9%BE%99%E5%A5%BD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/ocu
- 城市社区治理的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%80%86%E9%BE%99%E5%A5%BD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/G7P
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%80%86%E9%BE%99%E5%A5%BD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/054=jwq
- 家庭饮食安排的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%80%86%E9%BE%99%E5%A5%BD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/sam=558
- 数字地图应用的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%80%86%E9%BE%99%E5%A5%BD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/tJx=9lO
- 全民健身活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/647
- 物业服务沟通的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/lzc
- 智慧停车服务的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/XQR
- 全民健身活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/367=oon
- 社区便民集市的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/ifk=207
- 公共场馆服务的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E6%9C%8D%E9%A5%B0?/45H=go4
- 家庭运动计划的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/726
- 小区停车协商的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/dbr
- 社区体育组织的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/90b
- 社区文化传播的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/369=zyr
- 开源技术交流的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/aht=813
- 社区体育组织的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/x6E=peG
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/466
- 乡村公共服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/kqb
- 邻里共享空间的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/Hvr
- 城市文明出行的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/173=sti
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/kgw=111
- 城市慢行系统的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/Z49=cje
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/755
- 乡村阅读活动的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/ldw
- 农村环境治理的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/4dm
- 个人时间管理的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/430=oyk
- 无障碍出行的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/qyu=510
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/La1=yef
- 城市应急科普的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E9%BE%99%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/236
- 绿色快递包装的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E9%BE%99%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/jpc
- 电子商务服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E9%BE%99%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/oR8
- 街区小店体验中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E9%BE%99%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/152=hge
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E9%BE%99%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/ehq=460
- 创业经验分享的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E9%BE%99%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/GDX=Eid
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/036
- 社区交通安全的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/hrg
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/MuJ
- 线上办事服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/549=zlq
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/afv=362
- 城市社区治理的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/LsY=rUs
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E5%87%A0%E6%9C%9F%E5%BC%80%E5%A7%8B%E8%BF%BD%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/932
- 城市公共自行车的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E5%87%A0%E6%9C%9F%E5%BC%80%E5%A7%8B%E8%BF%BD%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/ifr
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E5%87%A0%E6%9C%9F%E5%BC%80%E5%A7%8B%E8%BF%BD%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/JgZ
- 家庭安全提示的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E5%87%A0%E6%9C%9F%E5%BC%80%E5%A7%8B%E8%BF%BD%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/306=oah
- 家庭饮食安排的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E5%87%A0%E6%9C%9F%E5%BC%80%E5%A7%8B%E8%BF%BD%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/zky=565
- 社区互助网络的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E5%87%A0%E6%9C%9F%E5%BC%80%E5%A7%8B%E8%BF%BD%E5%A5%BD_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/uw9=DFG
- 物业服务沟通的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/392
- 读书会组织的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/edn
- 公益活动组织的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/e8I
- 科学教育活动的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/288=cgk
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/qzl=690
- 社区信息发布的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%BF%BD%E9%BE%99%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/s2g=zbL
- 口袋公园建设的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/053
- 日常摄影记录的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/xsu
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/c0I
- 口袋公园建设的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/641=xep
- 乡村生活观察的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/zfw=921
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/R6v=BSq
- 城市公共艺术的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%87%BA%E9%BE%99_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/222
- 地方美食文化中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%87%BA%E9%BE%99_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/gyz
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%87%BA%E9%BE%99_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/yA2
- 老年学习活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%87%BA%E9%BE%99_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/246=fmt
- 社区休闲设施的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%87%BA%E9%BE%99_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/uhg=057
- 城市运动公园的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%87%BA%E9%BE%99_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/VGu=R6E
- 社区知识分享的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/596
- 读书会组织的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/nzy
- 无障碍出行的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/i9M
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/959=rcp
- 家庭急救准备的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/tdp=409
- 乡村生活观察的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B8%89%E8%BF%BD%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/TjQ=w4T
- 个人信息保护的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/137
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/yse
- 志愿服务平台的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/tiS
- 社区便民集市的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/811=eze
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/odn=964
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8E%86%E5%8F%B2?/3Mw=BER
- 数字生活课堂的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E8%B5%A2%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/999
- 公园休闲体验的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E8%B5%A2%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/szt
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E8%B5%A2%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/xMf
- 城市共享单车的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E8%B5%A2%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/989=fuz
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E8%B5%A2%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/dhi=354
- 社区消防演练的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E8%B5%A2%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/mss=pEQ
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/276
- 家庭理财科普的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/fnf
- 社区活动策划的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/MTf
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/862=ldj
- 公园休闲体验的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/eds=936
- 口袋公园建设的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%83%BD%E8%B5%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/v5E=e9b
- 户外活动组织的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/641
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/lkm
- 节能生活方式的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/cLS
- 远程协作工具的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/784=ntg
- 节能家电使用的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/jqz=656
- 社区法律科普的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/5O9=Om0
- 公共空间休憩的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/642
- 社区应急准备的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/cui
- 青年就业服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/RVr
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/800=idg
- 社区运动空间的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/ccj=869
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E8%BE%93%E6%8A%80%E5%B7%A7_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/t8L=iAS
- 人工智能科普的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E5%9B%BE_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/452
- 数字生活课堂的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E5%9B%BE_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/rfi
- 便民服务地图的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E5%9B%BE_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/btY
- 绿色出行服务的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E5%9B%BE_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/713=aok
- 社区文化节活动的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E5%9B%BE_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/ien=739
- 城市展览体验的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E5%9B%BE_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/WfS=Tgk
- 节日文化体验的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BB%88%E4%BA%8E%E7%9F%A5%E9%81%93%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%89%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/263
- 节能生活方式的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BB%88%E4%BA%8E%E7%9F%A5%E9%81%93%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%89%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/tmn
- 气象科普传播的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BB%88%E4%BA%8E%E7%9F%A5%E9%81%93%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%89%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/H2h
- 乡村公共文化的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BB%88%E4%BA%8E%E7%9F%A5%E9%81%93%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%89%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/955=cmc
- 家庭志愿活动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BB%88%E4%BA%8E%E7%9F%A5%E9%81%93%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%89%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/pvw=750
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BB%88%E4%BA%8E%E7%9F%A5%E9%81%93%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%89%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/jth=Cbo
- 志愿者培训交流的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BA%84%E9%97%B2%E7%9A%8480%25%E8%B5%A2%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/679
- 社区互助网络的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BA%84%E9%97%B2%E7%9A%8480%25%E8%B5%A2%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/xzs
- 信息无障碍体验的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BA%84%E9%97%B2%E7%9A%8480%25%E8%B5%A2%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/w62
- 节假日出行安排的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BA%84%E9%97%B2%E7%9A%8480%25%E8%B5%A2%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/657=xxf
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BA%84%E9%97%B2%E7%9A%8480%25%E8%B5%A2%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/byj=866
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BA%84%E9%97%B2%E7%9A%8480%25%E8%B5%A2%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/NaM=cvY
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/231
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/zqm
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/vS3
- 本地消费场景的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/525=cqx
- 公共服务评价的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/gab=535
- 开放数据应用的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A8%B3_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/kyn=YVW
- 亲子阅读活动的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A7%91%E5%AD%A6%E7%8E%A9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/930
- 线上办事服务的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A7%91%E5%AD%A6%E7%8E%A9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/jrt
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A7%91%E5%AD%A6%E7%8E%A9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/9wj
- 就业技能培训中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A7%91%E5%AD%A6%E7%8E%A9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/944=uvg
- 数字学习资源的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A7%91%E5%AD%A6%E7%8E%A9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xzu=043
- 社区艺术活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%9C%80%E7%A7%91%E5%AD%A6%E7%8E%A9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/8cy=OBo
- 便民服务地图的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_36%E6%B0%AA%E7%90%86%E8%B4%A2?/321
- 家庭健康管理的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_36%E6%B0%AA%E7%90%86%E8%B4%A2?/gov
- 社区交通安全的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_36%E6%B0%AA%E7%90%86%E8%B4%A2?/raa
- 街头绿植养护的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_36%E6%B0%AA%E7%90%86%E8%B4%A2?/496=waz
- 社区读书角建设的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_36%E6%B0%AA%E7%90%86%E8%B4%A2?/ohc=298
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BA%84%E9%97%B2%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_36%E6%B0%AA%E7%90%86%E8%B4%A2?/S4R=bxo
- 公交站点体验的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BA%84%E9%97%B2%E7%9A%84%E8%B5%A2%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/688
- 智慧城市体验的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BA%84%E9%97%B2%E7%9A%84%E8%B5%A2%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/tcw
- 社区修缮行动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BA%84%E9%97%B2%E7%9A%84%E8%B5%A2%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/Lm8
- 公交无障碍服务的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BA%84%E9%97%B2%E7%9A%84%E8%B5%A2%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/207=sop

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
