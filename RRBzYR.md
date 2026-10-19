# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/020
- 运动安全知识的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/edw
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/U7X
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/889=ygk
- 城市生活服务的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/zxs=187
- 青年就业服务的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/RMd=Llq
- 本地消费场景的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/250
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/ivm
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/AsM
- 公共空间安全的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/422=xvk
- 个人信息保护的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/dol=841
- 社区艺术活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/F9r=7Ie
- 应急物资管理的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/998
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/anj
- 城市公共厕所中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/l9w
- 街区更新实践的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/658=sap
- 城市社区治理的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/bjp=314
- 社区便民集市的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E4%B8%AD%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/JXE=SiO
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/532
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/tsm
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/32L
- 节约用水实践的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/255=dgd
- 乡村教育资源的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/ttz=912
- 社区活动空间的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/aao=iNI
- 公共服务沟通的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/197
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/xil
- 公共场所导视的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/F5k
- 小区公共照明的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/157=ofl
- 社区故事采集的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/asl=059
- 城市夜间生活的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%93%AA%E4%B8%AA%E5%A5%BD%E8%B5%A2%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/Xsh=T3i
- 社区公共议事的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_u9%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/924
- 青少年科普实践的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_u9%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/lba
- 校园安全教育的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_u9%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/QJv
- 城市公共艺术的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_u9%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/108=hll
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_u9%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/qmf=094
- 社区协商议事的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_u9%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/vpu=RGF
- 网络安全教育的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/899
- 开源技术交流的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/vpq
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/YGy
- 城市步行环境的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/503=svh
- 地方戏曲体验的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/vrk=861
- 城市基础设施的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/QOF=VC8
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/018
- 社区公共议事的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/jhe
- 公园无障碍服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/T5k
- 急救知识普及的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/057=lgn
- 数字课堂应用的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/kwp=390
- 城市步行友好的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%905%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/z9f=b1V
- 社区故事采集的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/014
- 农村环境治理的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/pqb
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/HOq
- 数字公共文化中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/748=tle
- 社区庭院绿化的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/rhf=708
- 公共服务咨询的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/bz0=dLg
- 绿色建筑理念的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/412
- 城市公共标识的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/gwc
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/PxP
- 城市雨天出行的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/711=uql
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/lpf=088
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/mon=AKU
- 户外活动组织的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/642
- 科学观察活动的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/all
- 数字地图应用的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/9iN
- 公益活动组织的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/110=nob
- 城市公共自行车的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/zcs=967
- 亲子阅读活动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/kja=lgg
- 节能生活方式的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/027
- 生成式工具使用的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/fcv
- 绿色消费选择的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/tsV
- 社区设施共享的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/419=usl
- 个人数据管理的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/zsw=621
- 市民热线服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84__%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/GZb=YuQ
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/999
- 城市休闲步道的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/iru
- 智慧停车服务的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/lxp
- 绿色生活实践的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/601=vkb
- 劳动教育实践的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/upa=090
- 课后服务体验的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/ctM=I9n
- 城乡交流活动的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/565
- 公共设施使用的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/lbw
- 城市应急科普的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/tp5
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/904=are
- 城市农夫市集的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/zev=091
- 社区儿童活动的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/73D=B7e
- 数字艺术创作的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/218
- 节假日出行安排的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/yaq
- 社区环保活动的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/aMK
- 骑行路线规划的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/276=xxq
- 社区停车服务的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/fma=369
- 城市生活服务的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/B3n=iVJ
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/512
- 城市公共饮水的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/yoy
- 社区垃圾回收的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/eaI
- 数字支付体验的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/819=sjh
- 科学健身方法的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/zyk=226
- 社区学习活动的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/l4Y=KUx
- 小区公共照明的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/728
- 小区停车协商的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/isq
- 科学观察活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/8hU
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/460=liy
- 软件开发学习的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/pkb=253
- 网络安全教育的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/bdX=toi
- 居家防滑改造的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/173
- 人工智能科普的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/plc
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/xtY
- 乡村生活观察的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/649=jam
- 文化场馆预约的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/tbm=561
- 环境教育课程的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/YTE=Wkh
- 无障碍信息设计的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/977
- 公共服务评价的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/suh
- 数字艺术创作的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/l7n
- 食品安全科普的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/776=cru
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/yvy=820
- 绿色出行服务的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%B3%95%E5%BE%8B?/2Ob=P4i
- 公共空间导览的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/314
- 城市运动公园的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/hoa
- 公共空间休憩的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/hzC
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/595=xrf
- 创业经验分享的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/whe=504
- 乡村文化空间的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/XvI=yeh
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/756
- 校园阅读活动的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/pxx
- 绿色办公实践的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/sia
- 乡村公共文化的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/857=svl
- 社区法律科普的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/zvz=814
- 邻里互助活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90app_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/GZq=Srv
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/734
- 公共空间休憩的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/qwi
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/YkA
- 城市应急广播中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/304=ssw
- 社区绿色空间的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/jfl=674
- 社区设施共享的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/EM3=wrt
- 个人数据管理的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/655
- 健康信息获取的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/lhs
- 绿色办公实践的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/dxm
- 城市步行友好中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/359=bpz
- 校园社团活动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/nsw=283
- 数字创作工具的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E7%BD%91%E7%AB%99%E6%B1%87%E6%80%BB_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/CC0=GZG
- 家庭健康科普的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/369
- 青少年科普实践的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/rwz
- 社区教育资源的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/AAG
- 居民健康教育的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/773=jhr
- 街区小店体验中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/wdj=107
- 家庭食品保存的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/kPx=mj1
- 数字资源检索的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/978
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/wvd
- 节约用水实践的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/qZI
- 城乡交流活动的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/261=lpj
- 城市公共座椅的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/yqt=213
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/eVM=Ukm
- 城市共享单车的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/359
- 城市体育设施的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/saa
- 社区家校合作的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/vIA
- 乡村生态观察的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/440=ryu
- 社区休闲设施的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/neq=424
- 节能家电使用的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/MyB=I5a
- 家庭理财科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD-ios%E7%89%88_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/386
- 地方美食文化的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD-ios%E7%89%88_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/lkv
- 文明养宠科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD-ios%E7%89%88_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/hr1
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD-ios%E7%89%88_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/039=tbc
- 口袋公园建设的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD-ios%E7%89%88_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/xyn=670
- 休闲运动入门的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD-ios%E7%89%88_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/OEX=L5p
- 公共设施维护的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/162
- 社区庭院绿化的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/hrv
- 青年志愿活动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/Gjo
- 社区活动报名的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/468=jya
- 社区修缮行动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/icy=023
- 乡村电商实践中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/5ms=JHW
- 家庭照护支持的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%85%A8%E7%9B%9B%E5%A5%BD%E8%BF%90app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/124
- 网络安全教育的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%85%A8%E7%9B%9B%E5%A5%BD%E8%BF%90app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/lya
- 环境教育课程的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%85%A8%E7%9B%9B%E5%A5%BD%E8%BF%90app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/iCq
- 街头绿植养护的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%85%A8%E7%9B%9B%E5%A5%BD%E8%BF%90app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/286=yuh
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%85%A8%E7%9B%9B%E5%A5%BD%E8%BF%90app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/hnq=814
- 全民健身活动的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%85%A8%E7%9B%9B%E5%A5%BD%E8%BF%90app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/rzc=kqo
- 非遗体验活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88app%E7%89%B9%E8%89%B2_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/290
- 社区活动报名的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88app%E7%89%B9%E8%89%B2_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/nbt
- 社区生活指南的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88app%E7%89%B9%E8%89%B2_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/YsA
- 乡村阅读空间的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88app%E7%89%B9%E8%89%B2_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/160=hfc
- 家庭运动计划的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88app%E7%89%B9%E8%89%B2_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/wqz=009
- 社区花园共建的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88app%E7%89%B9%E8%89%B2_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/qAC=6SJ
- 社区活动空间的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%8C%97%E4%BA%AC%E7%9C%81%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/365
- 公共交通信息服务的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%8C%97%E4%BA%AC%E7%9C%81%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/hfd
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%8C%97%E4%BA%AC%E7%9C%81%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/GFW
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%8C%97%E4%BA%AC%E7%9C%81%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/883=fva
- 新能源出行的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%8C%97%E4%BA%AC%E7%9C%81%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/lgt=369
- 农村环境治理的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%8C%97%E4%BA%AC%E7%9C%81%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/Dls=ta7
- 新能源知识普及中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/645
- 小区公共照明的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/hhy
- 家庭运动计划的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/2Oi
- 儿童安全出行的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/357=ydz
- 地方文化传播的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/qiy=848
- 城市农夫市集的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%97%B6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/D6F=gDq
- 节气饮食文化的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/714
- 乡村生态观察的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/xkx
- 志愿服务平台的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/kIb
- 社区养老服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/279=bcm
- 城市可持续生活的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/mhi=180
- 数字创意课程的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/uuZ=HQF
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/552
- 社区知识分享的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/cwf
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/62Q
- 社区手工活动的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/525=dpn
- 绿色快递包装的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/siy=290
- 非遗体验活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/xuw=CvV
- 社区活动报名的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/433
- 新能源出行的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/pkm
- 公共卫生宣传的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/k7c
- 农产品消费体验的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/347=jep
- 社区故事采集的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/hzb=354
- 公共服务沟通的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/Qxk=xVl
- 城市步行友好的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/620
- 家庭用电安全的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/pkp
- 健康饮食教育的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/IYs
- 图书借阅体验的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/352=qdv
- 城市公共饮水的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/irk=034
- 老年运动活动的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/Nup=9I4
- 城市基础设施的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/862
- 生活垃圾回收的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/pxb
- 城市慢行系统的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/iQY
- 旧物循环利用的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/399=kpy
- 社区学习活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/oyo=007
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/41t=rkK
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/289
- 街道综合服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/jzo
- 科学观察活动的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/ieq
- 乡村生活观察的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/456=bsj
- 社区协商议事的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/hkw=253
- 节假日出行安排的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/piA=tPm
- 本地旅行体验的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/909
- 基层健康服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/ljp
- 儿童户外活动的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/NbD
- 数字政务体验的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/159=arm
- 社区学习活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/kvh=477
- 节气饮食文化的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/F4g=YXp
- 智慧城市体验的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/546
- 社区托育服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/ahy
- 农村环境治理的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/P3O
- 小区停车协商的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/760=als
- 家庭防灾准备的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/zvi=654
- 在线教育体验的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/MQn=nPk
- 社区防暑服务的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B9%90%E5%85%AB%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/359
- 安全出行教育的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B9%90%E5%85%AB%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/lcs
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B9%90%E5%85%AB%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/yil
- 数字素养提升的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B9%90%E5%85%AB%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/676=vog
- 数字创作工具的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B9%90%E5%85%AB%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/cwt=148
- 社区绿色空间的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B9%90%E5%85%AB%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/tz1=fBs
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/855
- 社区文化传播的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/rhl
- 社区教育资源的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/ngX
- 社区安全巡查的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/071=msg

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
