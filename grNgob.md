# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 小区公共照明的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%95%99%E5%AD%A6_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/S6k
- 全民健身活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%95%99%E5%AD%A6_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/431=xnj
- 青年职业探索的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%95%99%E5%AD%A6_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/njn=272
- 社区邻里服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%95%99%E5%AD%A6_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/qpR=7nF
- 家庭健康科普的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%E5%85%AC%E5%BC%8F_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/974
- 街道综合服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%E5%85%AC%E5%BC%8F_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/hiw
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%E5%85%AC%E5%BC%8F_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/kCk
- 青少年心理健康的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%E5%85%AC%E5%BC%8F_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/913=fac
- 城市运动公园的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%E5%85%AC%E5%BC%8F_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/fkh=788
- 农产品消费体验的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%E5%85%AC%E5%BC%8F_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/ab0=nJu
- 公共服务指南的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%AE%80%E5%8D%95%E7%9C%8B%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/013
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%AE%80%E5%8D%95%E7%9C%8B%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/lbw
- 社区邻里服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%AE%80%E5%8D%95%E7%9C%8B%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/ANy
- 职业技能学习的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%AE%80%E5%8D%95%E7%9C%8B%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/978=azj
- 应急物资管理的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%AE%80%E5%8D%95%E7%9C%8B%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/wok=459
- 数字学习资源的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%AE%80%E5%8D%95%E7%9C%8B%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%94%BE?/IMy=MDj
- 校园节能行动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E8%AF%81%E5%88%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E7%AD%94?/798
- 城市建设科普的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E8%AF%81%E5%88%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E7%AD%94?/rkh
- 农贸市场环境的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E8%AF%81%E5%88%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E7%AD%94?/0tT
- 志愿服务平台的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E8%AF%81%E5%88%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E7%AD%94?/129=tvm
- 地方旅游导览的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E8%AF%81%E5%88%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E7%AD%94?/jei=710
- 社区家校合作的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E8%AF%81%E5%88%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E7%AD%94?/qmD=Jw7
- 社区庭院绿化的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/230
- 社区公共卫生的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/lyx
- 青少年编程学习的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/8Nx
- 休闲运动入门的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/586=jio
- 课后服务体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/ewg=543
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E4%BA%BA%E7%94%9F%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/vFi=vaN
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E8%B5%8F%E4%B9%90%E5%B8%AEapp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/115
- 社区健康讲座的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E8%B5%8F%E4%B9%90%E5%B8%AEapp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/tyl
- 科技馆参观体验的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E8%B5%8F%E4%B9%90%E5%B8%AEapp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/rA2
- 网络安全教育的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E8%B5%8F%E4%B9%90%E5%B8%AEapp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/026=qpt
- 文化遗产保护科普的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E8%B5%8F%E4%B9%90%E5%B8%AEapp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/ouy=555
- 城市人文观察的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E8%B5%8F%E4%B9%90%E5%B8%AEapp%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/ENb=m9R
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%80%8128%E5%85%83_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/357
- 在线学习体验的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%80%8128%E5%85%83_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/zuy
- 社区快递服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%80%8128%E5%85%83_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/Msr
- 家庭理财科普的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%80%8128%E5%85%83_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/185=cfx
- 公共服务数字化的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%80%8128%E5%85%83_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/taw=862
- 邻里互助活动的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%80%8128%E5%85%83_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/kEG=EmY
- 节约用水实践的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B9%B012%E7%94%9F%E8%82%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/083
- 图书借阅体验的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B9%B012%E7%94%9F%E8%82%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/flr
- 小微企业服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B9%B012%E7%94%9F%E8%82%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/R5j
- 电动汽车充电的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B9%B012%E7%94%9F%E8%82%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/697=hqp
- 机器人科普活动中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B9%B012%E7%94%9F%E8%82%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/dzy=329
- 数字课堂应用的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E4%B9%B012%E7%94%9F%E8%82%96%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E9%80%9F%E8%A7%88?/JYD=pZc
- 公共空间安全的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%96%E7%95%8C%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/474
- 城市绿色交通的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%96%E7%95%8C%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/xnv
- 公共服务沟通的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%96%E7%95%8C%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/8lL
- 基层服务创新的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%96%E7%95%8C%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/914=lfc
- 读书会组织的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%96%E7%95%8C%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/ynr=787
- 市民意见收集的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%96%E7%95%8C%E8%B6%B3%E7%90%83%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/qAv=tDV
- 城市文明出行的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/881
- 城市共享单车的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/xuq
- 数字阅读服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/dES
- 社区慢性病防控的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/639=pwg
- 环境教育课程的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/pbh=521
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/pqc=3VE
- 家庭食品保存的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%9C%A8%E7%BA%BF%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/496
- 公共服务评价的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%9C%A8%E7%BA%BF%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/bxm
- 基层健康档案的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%9C%A8%E7%BA%BF%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/aNF
- 非遗体验活动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%9C%A8%E7%BA%BF%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/038=lay
- 灵活就业交流的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%9C%A8%E7%BA%BF%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/mny=732
- 在线教育体验的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%9C%A8%E7%BA%BF%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/v8p=QrS
- 社区互助网络的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8cp2588cc_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/413
- 儿童户外活动的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8cp2588cc_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/ejz
- 在线学习体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8cp2588cc_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/pJb
- 家庭运动计划的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8cp2588cc_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/629=pqb
- 社区儿童活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8cp2588cc_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/vjx=304
- 社区儿童活动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8cp2588cc_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/nQ6=Q6U
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%95%99%E7%A8%8B_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/180
- 城市水环境观察的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%95%99%E7%A8%8B_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/qcw
- 通勤路线规划的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%95%99%E7%A8%8B_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/c0v
- 电动汽车充电的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%95%99%E7%A8%8B_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/003=whk
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%95%99%E7%A8%8B_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/oaf=141
- 市民意见收集的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%95%99%E7%A8%8B_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/PVB=GmI
- 老年学习活动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E6%8F%90%E9%AB%98%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/221
- 文明养宠科普的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E6%8F%90%E9%AB%98%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/qpl
- 节日文化体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E6%8F%90%E9%AB%98%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/aFT
- 光伏知识科普的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E6%8F%90%E9%AB%98%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/727=tfa
- 小区电梯维护的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E6%8F%90%E9%AB%98%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/tqw=530
- 社区手工活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E8%83%BD%E6%8F%90%E9%AB%98%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/ayf=qaO
- 健康步道使用的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9300%E5%85%83_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/077
- 电子商务服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9300%E5%85%83_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/nfr
- 社会体育指导的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9300%E5%85%83_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/1zX
- 生活服务数字化的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9300%E5%85%83_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/938=brv
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9300%E5%85%83_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/vpf=959
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9300%E5%85%83_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/neR=ilu
- 城市住房服务中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E8%83%BD%E8%B5%9A%E5%88%B0%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/516
- 文明养宠科普的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E8%83%BD%E8%B5%9A%E5%88%B0%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/jiq
- 家庭节能实践的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E8%83%BD%E8%B5%9A%E5%88%B0%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/UqW
- 开放数据应用的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E8%83%BD%E8%B5%9A%E5%88%B0%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/619=kti
- 亲子科普活动的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E8%83%BD%E8%B5%9A%E5%88%B0%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/cox=986
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E8%83%BD%E8%B5%9A%E5%88%B0%E9%92%B1_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/TQl=VZn
- 社区活动空间中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E8%B5%8C%E5%8D%9A%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/023
- 急救知识普及的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E8%B5%8C%E5%8D%9A%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/drm
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E8%B5%8C%E5%8D%9A%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/xIS
- 急救知识普及的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E8%B5%8C%E5%8D%9A%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/697=chy
- 小微企业服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E8%B5%8C%E5%8D%9A%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/kuf=958
- 小区公共照明的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E8%B5%8C%E5%8D%9A%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/ecs=W9y
- 家庭安全提示的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB33%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/321
- 社区艺术活动的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB33%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/ojx
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB33%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/FGm
- 数字公共文化的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB33%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/563=qmw
- 地方文化传播的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB33%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/eum=465
- 绿色校园实践的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB33%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%91%A8%E6%8A%A5?/mwC=ia4
- 城乡交通衔接的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E7%A7%98%E7%B1%8D%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/054
- 社区便民服务的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E7%A7%98%E7%B1%8D%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/qon
- 城市建设科普的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E7%A7%98%E7%B1%8D%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/msi
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E7%A7%98%E7%B1%8D%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/607=rjk
- 城市应急科普的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E7%A7%98%E7%B1%8D%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/iay=607
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E7%A7%98%E7%B1%8D%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/0nP=TKO
- 社区修缮行动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/748
- 城市绿道建设的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/zcu
- 数字政务体验的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/wO1
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/428=xyz
- 社区交通安全的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/qlj=618
- 家庭收纳实践的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/qAr=aCK
- 公共服务预约的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%87%86%E7%A1%AE%E7%8E%87100%25%E6%88%98%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/640
- 城市绿道建设的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%87%86%E7%A1%AE%E7%8E%87100%25%E6%88%98%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/eoy
- 家庭运动计划的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%87%86%E7%A1%AE%E7%8E%87100%25%E6%88%98%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/EyW
- 运动安全知识的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%87%86%E7%A1%AE%E7%8E%87100%25%E6%88%98%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/250=dfl
- 公共卫生宣传的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%87%86%E7%A1%AE%E7%8E%87100%25%E6%88%98%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/pys=886
- 社区读书角建设的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%87%86%E7%A1%AE%E7%8E%87100%25%E6%88%98%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/Z4b=6Tm
- 生活服务数字化中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9A%E4%BD%8D%E8%83%865%E6%9C%9F%E5%86%85%E7%A8%B3%E4%B8%AD%E6%8A%80%E5%B7%A7_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/940
- 通勤路线规划的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9A%E4%BD%8D%E8%83%865%E6%9C%9F%E5%86%85%E7%A8%B3%E4%B8%AD%E6%8A%80%E5%B7%A7_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/jfb
- 创业经验分享的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9A%E4%BD%8D%E8%83%865%E6%9C%9F%E5%86%85%E7%A8%B3%E4%B8%AD%E6%8A%80%E5%B7%A7_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/EH8
- 青年就业服务的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9A%E4%BD%8D%E8%83%865%E6%9C%9F%E5%86%85%E7%A8%B3%E4%B8%AD%E6%8A%80%E5%B7%A7_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/999=qtf
- 社区邻里服务中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9A%E4%BD%8D%E8%83%865%E6%9C%9F%E5%86%85%E7%A8%B3%E4%B8%AD%E6%8A%80%E5%B7%A7_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/tqr=716
- 社区慢性病防控的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9A%E4%BD%8D%E8%83%865%E6%9C%9F%E5%86%85%E7%A8%B3%E4%B8%AD%E6%8A%80%E5%B7%A7_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/ejw=Hu9
- 社区公共议事的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E7%8E%A9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/878
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E7%8E%A9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/lhj
- 公共空间休憩的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E7%8E%A9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/OgQ
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E7%8E%A9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/229=vft
- 数字便民地图的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E7%8E%A9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/jje=877
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E7%8E%A9%E6%B3%95%E8%AF%A6%E8%A7%A3_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/TPd=6FH
- 城市应急广播的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E7%9A%84%E7%A7%98%E8%AF%80_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/312
- 在线学习体验的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E7%9A%84%E7%A7%98%E8%AF%80_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/gxw
- 远程协作工具中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E7%9A%84%E7%A7%98%E8%AF%80_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/7gX
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E7%9A%84%E7%A7%98%E8%AF%80_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/336=fzj
- 青少年户外教育的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E7%9A%84%E7%A7%98%E8%AF%80_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/pey=926
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E7%9A%84%E7%A7%98%E8%AF%80_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/g9p=B7v
- 城市树木认养的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E8%B5%941%E6%9C%80%E5%A5%BD%E7%9A%84%E6%8A%95%E6%B3%A8%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/779
- 城乡交流活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E8%B5%941%E6%9C%80%E5%A5%BD%E7%9A%84%E6%8A%95%E6%B3%A8%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/mpz
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E8%B5%941%E6%9C%80%E5%A5%BD%E7%9A%84%E6%8A%95%E6%B3%A8%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/fhy
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E8%B5%941%E6%9C%80%E5%A5%BD%E7%9A%84%E6%8A%95%E6%B3%A8%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/276=szl
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E8%B5%941%E6%9C%80%E5%A5%BD%E7%9A%84%E6%8A%95%E6%B3%A8%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/poo=350
- 生活垃圾减量的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E8%B5%941%E6%9C%80%E5%A5%BD%E7%9A%84%E6%8A%95%E6%B3%A8%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/taM=70f
- 户外活动组织的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_4%E7%A0%81%E5%B9%B3%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/379
- 骑行路线规划的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_4%E7%A0%81%E5%B9%B3%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/sag
- 城乡公共服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_4%E7%A0%81%E5%B9%B3%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/cOO
- 城市可持续生活的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_4%E7%A0%81%E5%B9%B3%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/969=fyy
- 社区心理支持的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_4%E7%A0%81%E5%B9%B3%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/rhv=803
- 全民健身活动的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_4%E7%A0%81%E5%B9%B3%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/uuO=Dau
- 志愿服务平台的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A8%B3%E8%B5%A2%E6%88%98%E6%B3%95%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/997
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A8%B3%E8%B5%A2%E6%88%98%E6%B3%95%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/tuk
- 公共图书馆服务的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A8%B3%E8%B5%A2%E6%88%98%E6%B3%95%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/JsK
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A8%B3%E8%B5%A2%E6%88%98%E6%B3%95%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/379=ynl
- 家庭节能实践的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A8%B3%E8%B5%A2%E6%88%98%E6%B3%95%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/bnx=730
- 周末休闲规划的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A8%B3%E8%B5%A2%E6%88%98%E6%B3%95%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/BS2=KjN
- 智慧城市体验的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%AB%E5%B9%B4%E6%80%BB%E7%BB%93%E5%87%BA%E6%9D%A5%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/531
- 开源技术交流的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%AB%E5%B9%B4%E6%80%BB%E7%BB%93%E5%87%BA%E6%9D%A5%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/tda
- 城市步行友好的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%AB%E5%B9%B4%E6%80%BB%E7%BB%93%E5%87%BA%E6%9D%A5%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/uOi
- 老年友好服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%AB%E5%B9%B4%E6%80%BB%E7%BB%93%E5%87%BA%E6%9D%A5%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/722=rip
- 食品安全科普的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%AB%E5%B9%B4%E6%80%BB%E7%BB%93%E5%87%BA%E6%9D%A5%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/afk=879
- 开放数据应用的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%AB%E5%B9%B4%E6%80%BB%E7%BB%93%E5%87%BA%E6%9D%A5%E7%9A%84%E6%9D%80%E5%8F%B7%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/9ir=RaR
- 青年志愿活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E5%BC%8F_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/255
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E5%BC%8F_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/fdb
- 城市文明出行的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E5%BC%8F_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/DB8
- 社区家校合作的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E5%BC%8F_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/845=rsv
- 青少年科普实践的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E5%BC%8F_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/oic=125
- 农村环境治理的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E5%BC%8F_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/fDp=w5M
- 居民健康教育的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/109
- 数字课堂应用的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/avz
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/VIg
- 租房信息服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/651=wat
- 全民健身活动的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/qqk=225
- 老旧小区改造的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/llm=HGN
- 本地旅行体验的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E5%A4%9A%E8%B5%A2%E5%B0%91_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/775
- 图书馆数字服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E5%A4%9A%E8%B5%A2%E5%B0%91_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/hrz
- 电动汽车充电的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E5%A4%9A%E8%B5%A2%E5%B0%91_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/TyH
- 居民健康教育的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E5%A4%9A%E8%B5%A2%E5%B0%91_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/305=ico
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E5%A4%9A%E8%B5%A2%E5%B0%91_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/eyd=743
- 数字阅读服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E5%A4%9A%E8%B5%A2%E5%B0%91_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/ktQ=c9l
- 家庭运动计划的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E6%98%AF%E9%A1%BA%E9%BE%99%E8%BF%98%E6%98%AF%E7%A0%8D%E9%BE%99%E5%A5%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/190
- 科技馆参观体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E6%98%AF%E9%A1%BA%E9%BE%99%E8%BF%98%E6%98%AF%E7%A0%8D%E9%BE%99%E5%A5%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/pif
- 社区宠物管理的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E6%98%AF%E9%A1%BA%E9%BE%99%E8%BF%98%E6%98%AF%E7%A0%8D%E9%BE%99%E5%A5%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/ZDF
- 家庭健康科普的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E6%98%AF%E9%A1%BA%E9%BE%99%E8%BF%98%E6%98%AF%E7%A0%8D%E9%BE%99%E5%A5%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/030=mxl
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E6%98%AF%E9%A1%BA%E9%BE%99%E8%BF%98%E6%98%AF%E7%A0%8D%E9%BE%99%E5%A5%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/cgt=939
- 城市雨天出行的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E6%98%AF%E9%A1%BA%E9%BE%99%E8%BF%98%E6%98%AF%E7%A0%8D%E9%BE%99%E5%A5%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/IIa=BD3
- 网络安全教育的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8D%E8%B4%AA%E5%BF%83%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/858
- 智能家居应用的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8D%E8%B4%AA%E5%BF%83%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/hwf
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8D%E8%B4%AA%E5%BF%83%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/0Pj
- 数字创意课程的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8D%E8%B4%AA%E5%BF%83%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/015=azr
- 家庭食品保存的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8D%E8%B4%AA%E5%BF%83%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/chr=519
- 社区科普课堂的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%8D%E8%B4%AA%E5%BF%83%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/KGi=a0q
- 消防知识宣传的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%9B%BD%E5%AE%B6%E6%AD%A3%E8%A7%84%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%9C%8D%E9%A5%B0?/288
- 城乡交流活动的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%9B%BD%E5%AE%B6%E6%AD%A3%E8%A7%84%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%9C%8D%E9%A5%B0?/qvu
- 老年友好服务的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%9B%BD%E5%AE%B6%E6%AD%A3%E8%A7%84%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%9C%8D%E9%A5%B0?/KqG
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%9B%BD%E5%AE%B6%E6%AD%A3%E8%A7%84%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%9C%8D%E9%A5%B0?/216=rda
- 公园亲子设施的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%9B%BD%E5%AE%B6%E6%AD%A3%E8%A7%84%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%9C%8D%E9%A5%B0?/jem=115
- 乡村文化空间的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%9B%BD%E5%AE%B6%E6%AD%A3%E8%A7%84%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%9C%8D%E9%A5%B0?/3dn=sbl
- 数字学习资源的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/682
- 老年运动活动的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/smc
- 社区心理支持的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/Rec
- 科学教育活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/582=gef
- 数字便民地图的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/bff=180
- 社区安全巡查的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/KaB=cKL
- 安全出行教育的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%AB%98%E6%89%8B%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%AB3%E7%9A%84_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/927
- 城市生活服务的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%AB%98%E6%89%8B%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%AB3%E7%9A%84_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/kvh
- 城市休闲步道的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%AB%98%E6%89%8B%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%AB3%E7%9A%84_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/iEd
- 老年智能设备中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%AB%98%E6%89%8B%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%AB3%E7%9A%84_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/412=bsz
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%AB%98%E6%89%8B%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%AB3%E7%9A%84_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/snf=306
- 城市应急广播的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%AB%98%E6%89%8B%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%AB3%E7%9A%84_%E6%90%9C%E7%8B%97%E6%88%B7%E5%A4%96?/h79=Gix
- 个人数据管理的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/092
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/fwe
- 小区电梯维护的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/ub9
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/066=ptn
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/ydi=438
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/fOS=zS3
- 读书会组织的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E9%AB%98%E6%89%8B%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/334
- 周末休闲规划的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E9%AB%98%E6%89%8B%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/lwe
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E9%AB%98%E6%89%8B%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/ckF
- 智慧停车服务的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E9%AB%98%E6%89%8B%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/388=zyx
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E9%AB%98%E6%89%8B%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/hri=505
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E9%AB%98%E6%89%8B%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/3kz=ZoG
- 绿色办公实践的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A8%B3%E5%AE%9A%E7%9B%88%E5%88%A9%E7%9A%84108%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/392
- 街区小店体验的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A8%B3%E5%AE%9A%E7%9B%88%E5%88%A9%E7%9A%84108%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/vxg
- 食品安全科普的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A8%B3%E5%AE%9A%E7%9B%88%E5%88%A9%E7%9A%84108%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/dPC
- 社区生活指南的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A8%B3%E5%AE%9A%E7%9B%88%E5%88%A9%E7%9A%84108%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/599=ufs
- 农产品消费体验的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A8%B3%E5%AE%9A%E7%9B%88%E5%88%A9%E7%9A%84108%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/nmy=375
- 家庭防灾准备的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A8%B3%E5%AE%9A%E7%9B%88%E5%88%A9%E7%9A%84108%E4%B8%AA%E6%8A%80%E5%B7%A7_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/uAE=Xgj
- 社区停车服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/408
- 生活技能分享的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/ter
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/fMp
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/802=uwk
- 终身学习资源的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/cpp=401
- 社区阅读服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%91%84%E5%BD%B1?/dJQ=kcY
- 租房信息服务的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/556
- 医院导诊服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/ebq
- 公园亲子设施中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/qb4
- 社区快递服务的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/920=xvc
- 运动安全知识的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/icp=696
- 城市文化路线的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/Lwa=7Aj
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/651
- 地方旅游导览的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/tdl
- 农贸市场环境的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/TqU
- 就业技能培训的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/678=koe
- 社区便民服务的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/jkx=555
- 创业经验分享的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/Q70=GTn

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
