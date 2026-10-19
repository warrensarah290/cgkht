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

- 儿童友好空间的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/215
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/cpb
- 科普展览体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/ERP
- 社区便民集市的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/746=siw
- 基层健康服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/mbh=760
- 公共空间安全的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/kwC=Q1n
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/799
- 公共场所导视的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/luq
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/HDn
- 城市展览体验的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/625=ptp
- 社区文化传播的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/dze=920
- 家庭消费规划的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/Wjz=xBG
- 家庭科学教育的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/609
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/uxs
- 社区托育服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/2ei
- 儿童户外活动的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/630=pjq
- 城市建设科普的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/awi=359
- 开源技术交流的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/Eae=oBw
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/002
- 城市生活记录的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vkf
- 数字政务体验的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Yn7
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/184=itr
- 在线教育体验的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/oab=975
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wBV=Nlk
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/260
- 数字艺术创作的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/lgi
- 数字艺术创作的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/SyW
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/927=mig
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/wai=326
- 社区便利生活的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/5Dj=7in
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/790
- 医院导诊服务的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/hpy
- 青年志愿活动的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/apr
- 休闲运动入门的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/318=iiq
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/bmy=453
- 城市运动公园的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/HWD=YfF
- 社区信息发布的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E5%BF%AB%E6%89%8B%E8%AE%B2%E5%9D%9B?/608
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E5%BF%AB%E6%89%8B%E8%AE%B2%E5%9D%9B?/ncn
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E5%BF%AB%E6%89%8B%E8%AE%B2%E5%9D%9B?/lyZ
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E5%BF%AB%E6%89%8B%E8%AE%B2%E5%9D%9B?/189=nkf
- 城市夜间照明的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E5%BF%AB%E6%89%8B%E8%AE%B2%E5%9D%9B?/lhu=021
- 个人时间管理的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E5%BF%AB%E6%89%8B%E8%AE%B2%E5%9D%9B?/MH6=7fc
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/702
- 公共服务评价从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/vql
- 社区学习活动的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/yxs
- 在线教育体验的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/786=zch
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/atx=873
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/Xc3=ghE
- 家庭环保习惯的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/460
- 邻里共享空间的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/bcb
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/813
- 城乡公共服务的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/273=wpb
- 公交无障碍服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/cit=587
- 科学健身方法的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/cqL=BuY
- 数字政务体验的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/718
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/bdf
- 街区绿化养护中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/OTs
- 数字艺术创作中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/341=frp
- 城市住房服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/isf=655
- 邻里共享空间的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/Juf=Ecr
- 无障碍信息设计的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/096
- 青少年科技社团的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/zso
- 公共服务评价的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/Ub8
- 终身学习资源的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/299=dmt
- 乡村生态观察的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/xxf=157
- 社区环保活动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/5VK=mGW
- 城市树木认养的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/205
- 骑行路线规划的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/wks
- 城市雨天出行的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/aCj
- 公共服务数字化的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/135=gqg
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/ppn=693
- 线上办事服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/1GF=W1d
- 城市运动公园的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/438
- 旧物循环利用的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/nms
- 基层医疗预约的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/WMB
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/129=zkj
- 基层健康档案的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/mdo=541
- 城市绿色交通的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/PmV=RKq
- 新能源知识普及的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/246
- 城乡交通衔接的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/rra
- 社区老年食堂中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/ELA
- 电子商务服务的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/430=mxz
- 日常摄影记录的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/ctt=659
- 老年人日常照护的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/bbC=gYZ
- 街头绿植养护的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/684
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/juk
- 城市休闲步道的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/KBH
- 本地历史资料的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/839=vuq
- 公共设施使用中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/ugd=514
- 城市共享单车的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/k2L=184
- 校园节能行动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%AE%97%E5%92%8C%E5%80%BC%E7%9A%84%E6%96%B9%E6%B3%95%E8%BF%87%E7%A8%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/991
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%AE%97%E5%92%8C%E5%80%BC%E7%9A%84%E6%96%B9%E6%B3%95%E8%BF%87%E7%A8%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/clf
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%AE%97%E5%92%8C%E5%80%BC%E7%9A%84%E6%96%B9%E6%B3%95%E8%BF%87%E7%A8%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/sSp
- 城市绿色交通的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%AE%97%E5%92%8C%E5%80%BC%E7%9A%84%E6%96%B9%E6%B3%95%E8%BF%87%E7%A8%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/296=wkx
- 家庭节能实践的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%AE%97%E5%92%8C%E5%80%BC%E7%9A%84%E6%96%B9%E6%B3%95%E8%BF%87%E7%A8%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/nlf=922
- 城乡公共服务的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%AE%97%E5%92%8C%E5%80%BC%E7%9A%84%E6%96%B9%E6%B3%95%E8%BF%87%E7%A8%8B_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/xg3=BLX
- 开放式学习空间的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/461
- 绿色消费选择的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/lsu
- 老年学习活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/0wk
- 社区慢性病防控的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/617=ayu
- 城市博物馆活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/nla=447
- 智能家居应用的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/t5z=5gO
- 社区停车服务的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AE%9A%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/497
- 社区文化节活动的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AE%9A%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/ogi
- 城市基础设施的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AE%9A%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/oPv
- 社区便民集市的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AE%9A%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/156=nhr
- 社区便利生活的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AE%9A%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/bif=968
- 家庭节能设备的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%AE%9A%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/U9n=Dkk
- 城市社区治理的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%8D%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%8799_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/163
- 社区手工活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%8D%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%8799_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/oqb
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%8D%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%8799_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/7Yl
- 社区庭院绿化的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%8D%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%8799_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/304=nka
- 智能家居应用的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%8D%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%8799_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/baq=248
- 青年志愿活动的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%8D%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%8799_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/HH2=Pxe
- 城市文明实践的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/970
- 家庭收纳实践的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/fjh
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/7dJ
- 小微企业服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/030=wuv
- 家庭安全提示的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/aiw=130
- 绿色快递包装的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/dsj=A6J
- 社区应急准备的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%84%E5%92%8C%E5%80%BC%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/264
- 社区慢性病防控的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%84%E5%92%8C%E5%80%BC%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/jsy
- 数字资源检索的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%84%E5%92%8C%E5%80%BC%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/LlV
- 休闲运动入门的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%84%E5%92%8C%E5%80%BC%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/704=plr
- 城市文明实践的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%84%E5%92%8C%E5%80%BC%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/rqb=538
- 城乡交通衔接的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%9A%84%E5%92%8C%E5%80%BC%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/F1w=eSP
- 城市应急广播的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/959
- 社会体育指导的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/tsq
- 数字生活课堂的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/hWp
- 城市微更新实践的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/675=tgj
- 图书借阅体验的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/hfr=236
- 数字阅读服务的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/E2g=zxd
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E7%A7%98%E7%B1%8D_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/393
- 传统手工艺体验的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E7%A7%98%E7%B1%8D_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/acd
- 城市绿色交通的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E7%A7%98%E7%B1%8D_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/D3t
- 信息无障碍体验的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E7%A7%98%E7%B1%8D_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/354=eqg
- 公共空间休憩的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E7%A7%98%E7%B1%8D_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/qlf=248
- 青年职业探索中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E7%A7%98%E7%B1%8D_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/2Hr=jWU
- 信息无障碍体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/891
- 城市雨天出行中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/cln
- 社区绿色空间的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/drn
- 文化讲座服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/461=iff
- 消防知识宣传的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/rtn=528
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/9nT=SAZ
- 公共设施维护的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/088
- 智慧城市体验的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/ndc
- 公共服务沟通的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/NAN
- 食品配送体验中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/307=gha
- 劳动教育实践的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/abd=476
- 读书会组织的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/IgZ=bq2
- 基层健康档案的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%80%E5%A4%A9%E8%83%BD%E8%B5%9A2%E4%B8%87%E7%9A%84%E9%BB%91%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/058
- 社区教育资源的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%80%E5%A4%A9%E8%83%BD%E8%B5%9A2%E4%B8%87%E7%9A%84%E9%BB%91%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/xhw
- 社区儿童活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%80%E5%A4%A9%E8%83%BD%E8%B5%9A2%E4%B8%87%E7%9A%84%E9%BB%91%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/udv
- 个人信息保护的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%80%E5%A4%A9%E8%83%BD%E8%B5%9A2%E4%B8%87%E7%9A%84%E9%BB%91%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/356=iru
- 开放数据应用的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%80%E5%A4%A9%E8%83%BD%E8%B5%9A2%E4%B8%87%E7%9A%84%E9%BB%91%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/lfs=888
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%B8%80%E5%A4%A9%E8%83%BD%E8%B5%9A2%E4%B8%87%E7%9A%84%E9%BB%91%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/W6M=vT6
- 节约用水实践的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A100_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/563
- 数字便民地图的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A100_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/mlh
- 开放数据应用的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A100_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/kVD
- 小区公共照明的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A100_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/594=nsw
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A100_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/cgv=297
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A100_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/dpT=Nta
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E8%B5%9A50%E5%85%83_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/449
- 社区邻里服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E8%B5%9A50%E5%85%83_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/ebv
- 线上办事服务中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E8%B5%9A50%E5%85%83_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/7ls
- 城市公共空间的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E8%B5%9A50%E5%85%83_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/124=btf
- 本地历史资料的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E8%B5%9A50%E5%85%83_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/sww=142
- 老年人文化生活的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8A%95%E8%B5%8410%E5%85%83%E8%B5%9A50%E5%85%83_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/GlF=M4d
- 居家适老化改造的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%A4%A9500_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/538
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%A4%A9500_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/lvm
- 居民健康教育的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%A4%A9500_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/eYY
- 节能生活方式的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%A4%A9500_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/678=goi
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%A4%A9500_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/wbz=444
- 全民健身活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%A4%A9500_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/TkJ=JOY
- 公共健身器材的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/718
- 社会体育指导的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/ykj
- 地方戏曲体验的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/zep
- 社区家校合作的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/479=kyc
- 数字政务体验的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/lik=309
- 终身学习资源的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E9%9B%B6%E6%8A%95%E8%B5%84%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/EOh=FDq
- 城市绿道建设的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A7%98%E8%AF%80_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/748
- 开放式学习空间的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A7%98%E8%AF%80_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/zct
- 街区更新实践的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A7%98%E8%AF%80_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/9SW
- 社区邻里服务的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A7%98%E8%AF%80_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/236=iwr
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A7%98%E8%AF%80_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/gxu=540
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A7%98%E8%AF%80_%E4%BC%98%E9%85%B7%E6%88%BF%E4%BA%A7?/736=ALj
- 城市博物馆活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7443_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/690
- 数字公共文化的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7443_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/bqs
- 社区防暑服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7443_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/RkA
- 家庭网络使用的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7443_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/362=fqk
- 老年友好服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7443_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/xrd=591
- 家庭照护支持的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7443_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/4zy=Lmr
- 社区生活指南的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/098
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/ddp
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/QKa
- 小微企业服务的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/215=txy
- 智慧停车服务的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/piy=586
- 人工智能科普的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BF%85%E4%B8%AD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/eji=7Uv
- 开放式学习空间的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%BD%91%E5%BD%A9%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/233
- 数字档案服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%BD%91%E5%BD%A9%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/dso
- 社区法律科普的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%BD%91%E5%BD%A9%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/Co8
- 地方民俗记录的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%BD%91%E5%BD%A9%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/101=hsb
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%BD%91%E5%BD%A9%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/vfq=633
- 城市慢行系统的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%BD%91%E5%BD%A9%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/jfn=2S4
- 数字阅读服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/089
- 家庭阅读计划的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/hrl
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/wBr
- 网络安全教育的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/213=qwk
- 儿童友好空间的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/tbp=583
- 公共服务咨询的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/yUe=BTA
- 数字便民地图的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/668
- 社区安全巡查的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/ncs
- 数字公共文化的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/A27
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/582=liu
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/lqr=632
- 公交无障碍服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/U94=8Le
- 地方文化传播的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/030
- 非遗体验活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/mkp
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/yFs
- 邻里共享空间的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/508=bjg
- 环境监测科普的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/gzw=481
- 数字学习资源的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/J2B=6Vq
- 便民维修服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/193
- 乡村生活观察的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/wrb
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/qoQ
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/967=rbi
- 市民意见收集的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/bky=520
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/KWg=LlC
- 文明养宠科普的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/604
- 家庭志愿活动的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/izz
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/y7t
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/047=onz
- 通勤路线规划的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/yvd=129
- 青少年心理健康的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/xz3=7d4
- 社区协商议事的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/619
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/umg
- 社区绿色空间的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/TgL
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/398=msr
- 机器学习入门的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/vqb=686
- 乡村阅读活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/V0t=kXQ
- 通勤路线规划的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/715
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/gbx
- 社区防暑服务的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/zXH
- 社区养老服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/247=rsr
- 数字资源检索的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/tpt=322
- 创业经验分享的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/Whl=cTL
- 社区艺术活动的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AE%B2%E8%A7%A3_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/361
- 小区电梯维护的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AE%B2%E8%A7%A3_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/oua
- 数字创作工具的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AE%B2%E8%A7%A3_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/4Ik
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AE%B2%E8%A7%A3_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/759=lja

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
