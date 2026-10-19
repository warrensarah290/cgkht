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

- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91weco%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/mnc=928
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91weco%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/JNx=kup
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/681
- 社区庭院绿化的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/foi
- 生活服务数字化的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/10I
- 城市文明实践的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/650=byj
- 社区养老服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/lmn=364
- 数字公共文化的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/vES=y9E
- 绿色建筑理念的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/103
- 公共卫生设施的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/zyb
- 城市生活服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/Jjr
- 健康饮水科普的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/273=tbd
- 便民维修服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/zof=790
- 社区心理支持的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/DEI=xK4
- 家庭理财科普的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/617
- 街头绿植养护的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/cbu
- 农业科普体验的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/5S6
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/060=ibw
- 社区邻里服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/qxg=193
- 乡村文化空间的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/9Mi=Tas
- 本地旅行体验的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/011
- 老年人日常照护的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/qug
- 网络信息辨识的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/1TI
- 乡村教育资源的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/588=hzm
- 文化讲座服务的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/imm=857
- 城市噪声观察的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/MT5=xVp
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/997
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/lar
- 社区活动策划的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/nJI
- 社区活动报名的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/136=qxt
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/wbe=350
- 节日文化体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/96b=URW
- 城市应急广播中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9?/367
- 居家防滑改造的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9?/yhn
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9?/zS1
- 数字生活课堂中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9?/180=vfg
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9?/tgt=064
- 数字艺术创作的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9?/QbD=YWD
- 社区文化传播的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/869
- 社区科普课堂的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/jqr
- 社区环保活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/z5Y
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/024=ztj
- 城市骑行环境的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/lqz=658
- 周末休闲规划中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/jUm=UEb
- 社区家校合作的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/486
- 家庭科学教育的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/sdw
- 科技馆参观体验的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Rpr
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/272=xrg
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zsg=182
- 城市步行友好的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jKf=faj
- 家庭科学教育的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/219
- 儿童友好空间的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/vwn
- 老年学习活动的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/Qkd
- 青少年户外教育的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/166=qzy
- 职业技能学习的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/onj=785
- 食品配送体验的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/IsU=l4Z
- 城市基础设施的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/560
- 城市噪声观察的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/zxw
- 城市文明出行的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/79O
- 公园亲子设施的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/436=ouz
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/hoj=909
- 社区花园共建的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/VDA=3AP
- 地方民俗记录的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/923
- 青年志愿活动的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/zdc
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/TV1
- 社区健康讲座中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/531=ehu
- 城乡交流活动的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/vfr=807
- 社区家政服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/xYN=n3Z
- 户外活动组织的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/210
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/zad
- 城市展览体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/xre
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/359=xdq
- 社区运动空间的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/zkd=585
- 志愿服务平台的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/mHO=2xh
- 公共交通信息服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/977
- 城市公共艺术的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/pqe
- 开放数据应用的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/NfF
- 街区更新实践的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/871=guq
- 公共交通接驳的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/sfc=122
- 租房信息服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/vDu=dJM
- 健康饮食教育的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/198
- 科学信息获取的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/lrs
- 城市夜间生活的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/3G7
- 城市空气科普的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/479=wub
- 老年数字阅读的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/qsh=388
- 城市公共座椅的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/wBy=px3
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/667
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/fzg
- 城市步行环境的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/maW
- 家庭环保行动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/299=khr
- 青年志愿活动的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/dcr=976
- 绿色建筑理念的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/fSg=4uJ
- 城市展览体验的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/837
- 开放式学习空间的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/ypo
- 城市生活记录的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/Ary
- 农业科普体验的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/192=ypn
- 家庭环保行动的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/dgv=457
- 周末休闲规划的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/8cq=BdD
- 个人信息保护的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/332
- 科学健身方法的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/gpg
- 社区便利生活的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/TMf
- 社区活动策划的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/132=cem
- 城市微更新实践有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/ewp=779
- 文化场馆预约的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/Pxd=hB5
- 数字学习资源的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/914
- 街头绿植养护的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/tyq
- 个人时间管理的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/aV2
- 社区宠物管理的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/131=pmg
- 家庭环保习惯的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/wwu=850
- 社区文化节活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/usF=Pyo
- 青年职业探索的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_2021%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/121
- 城市空气科普的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_2021%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/cad
- 基层健康档案的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_2021%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/Z8P
- 旧物循环利用的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_2021%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/070=zpx
- 低碳社区实践的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_2021%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/zem=524
- 节日文化体验的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_2021%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/agX=jKE
- 生成式工具使用中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/617
- 远程协作工具的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/vlr
- 租房信息服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/SoB
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/315=jdw
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/pen=334
- 软件开发学习的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/r7D=UmW
- 图书馆活动策划的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/893
- 城市公共空间的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/wuz
- 药品使用科普的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/Zoh
- 城市绿色交通的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/144=lpq
- 公交站点体验的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/sdm=456
- 社区应急准备的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/qzz=zuW
- 数字档案服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%9F%E8%B4%A3%E4%BA%BA%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/471
- 数字课堂应用的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%9F%E8%B4%A3%E4%BA%BA%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/mvo
- 公共服务预约的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%9F%E8%B4%A3%E4%BA%BA%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/1I8
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%9F%E8%B4%A3%E4%BA%BA%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/691=xec
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%9F%E8%B4%A3%E4%BA%BA%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/ryq=135
- 社区志愿服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%9F%E8%B4%A3%E4%BA%BA%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/7uF=fi8
- 本地消费场景的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_Welcome%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E7%94%B5?/149
- 老年友好服务的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_Welcome%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E7%94%B5?/zyy
- 社区设施共享的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_Welcome%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E7%94%B5?/Wui
- 城市公共空间的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_Welcome%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E7%94%B5?/876=xcn
- 公交站点体验中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_Welcome%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E7%94%B5?/nhp=444
- 食品配送体验的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_Welcome%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E7%94%B5?/Jug=2bx
- 社区托育服务的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%AF%94%E8%BE%83%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/126
- 绿色生活实践的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%AF%94%E8%BE%83%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/xwk
- 科技馆参观体验的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%AF%94%E8%BE%83%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/AD3
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%AF%94%E8%BE%83%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/013=rxi
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%AF%94%E8%BE%83%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/bvd=552
- 气象科普传播的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%AF%94%E8%BE%83%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/KwR=CHP
- 家庭收纳实践的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E__%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/904
- 智能家居应用的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E__%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/sgu
- 城市生活服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E__%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/1SP
- 在线学习体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E__%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/280=fcj
- 家庭防灾准备的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E__%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/dpi=605
- 便民维修服务的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E__%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/3z0=o39
- 小区停车协商的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E6%89%91?/446
- 社区公共卫生的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E6%89%91?/pqq
- 灵活就业交流的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E6%89%91?/WSh
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E6%89%91?/338=bxk
- 绿色快递包装的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E6%89%91?/psw=238
- 公共场馆服务的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E6%89%91?/QXx=Vtu
- 文化场馆预约的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/002
- 生成式工具使用的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/nyt
- 公共设施维护的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/cN5
- 公共设施维护的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/415=txm
- 低碳社区实践的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/ypb=162
- 家庭消费规划的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/SP1=nTt
- 社区协商议事的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8657%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/720
- 社区文化传播的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8657%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/eov
- 校园节能行动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8657%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/MYI
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8657%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/399=ioe
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8657%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/cqt=112
- 社区绿色空间的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8657%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/YJs=Kl0
- 社区手工活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/127
- 全民健身活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/gpj
- 安全出行教育的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/UEM
- 个人信息保护的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/951=kys
- 创业经验分享的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/bdc=449
- 城市生活服务的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/VE3=efA
- 基层医疗预约中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/637
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/fie
- 亲子科普活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/Qhk
- 数字创意课程的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/771=hzh
- 儿童运动体验中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/hpz=329
- 居家适老化改造的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/5Nb=03U
- 健康饮水科普的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/916
- 节约用水实践的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/zkh
- 城市水环境观察的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/eEJ
- 学校食育活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/870=djz
- 社区读书角建设的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/wby=586
- 家庭环保行动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/NLM=sCu
- 数字支付体验的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/403
- 生成式工具使用的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/yjx
- 软件开发学习的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/jV4
- 乡村公共文化的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/934=rtc
- 公共卫生设施的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/kmq=980
- 市民意见收集的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/RPI=FBa
- 食品配送体验的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome500_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/926
- 本地历史资料的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome500_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/svo
- 家庭志愿活动的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome500_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/vYO
- 家庭用电安全中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome500_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/348=cfz
- 城市共享单车的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome500_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/ryw=797
- 数字学习资源的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome500_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/b1Q=WVs
- 绿色出行服务的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/421
- 社区法律科普的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/uvz
- 乡村文化活动的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/S29
- 农业科普体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/406=bui
- 食品配送体验的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/xjg=379
- 职业技能学习的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/viU=Bjp
- 便民维修服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BDapp_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/938
- 城市便民驿站的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BDapp_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/hrc
- 环境监测科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BDapp_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/nU0
- 公园休闲体验的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BDapp_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/713=beb
- 食品配送体验的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BDapp_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/bdo=451
- 社区绿色空间的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%8B%E8%BD%BDapp_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/w55=GKy
- 劳动教育实践的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/501
- 校园社团活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/jen
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/M7h
- 基层健康服务的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/872=ico
- 数字资源检索的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/oxm=936
- 老年人日常照护的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/47T=QhJ
- 药品使用科普的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/090
- 老年人出行服务的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/udj
- 应急物资管理的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/TGQ
- 家庭教育交流的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/998=kdj
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/cbd=044
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/OEr=l9C
- 地方民俗记录的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/530
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/aji
- 小微企业服务的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/BTN
- 城市绿道建设的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/835=cfl
- 传统节日科普的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/vju=022
- 家庭教育交流的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/pvW=pUl
- 无障碍出行的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/458
- 社区信息发布的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/cpa
- 社区防暑服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/DpW
- 创业经验分享的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/793=koo
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/lpo=229
- 数字课堂应用的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/Ex5=mHS
- 乡村公共文化的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BAwelcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/258
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BAwelcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/cgz
- 非遗体验活动中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BAwelcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/qb3
- 本地旅行体验的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BAwelcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/780=paj
- 户外活动组织的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BAwelcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/ams=986
- 绿色校园实践的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BAwelcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/i0s=w6u
- 公共交通接驳的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/488
- 社区教育资源的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/hby
- 城市文明实践的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/cyA
- 公共空间导览的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/076=ejw
- 全民健身活动的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/ezu=539
- 公共服务评价的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/69y=UpQ
- 家庭运动计划的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8F%91_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/650
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8F%91_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/dxp

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
