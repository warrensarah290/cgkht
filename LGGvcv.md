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

- 基层健康服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eii-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/253
- 食品安全科普的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eii-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/sid
- 社区志愿服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eii-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/8HK
- 绿色消费选择的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eii-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/916=imk
- 数字政务体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eii-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/ytb=561
- 城市公共艺术的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eii-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/Jtq=Jk2
- 城市雨天出行的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-APP_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/020
- 社区花园共建的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-APP_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/qlh
- 在线学习体验的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-APP_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/HOy
- 健康饮水科普中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-APP_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/029=eif
- 就业技能培训的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-APP_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/qnd=280
- 社区信息发布的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-APP_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/I2T=yZq
- 图书馆活动策划的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Eii-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/567
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Eii-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/kwj
- 社区协商议事的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Eii-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/VbM
- 社区垃圾回收的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Eii-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/161=ywt
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Eii-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/dav=075
- 社区防暑服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Eii-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/K6Y=Uxo
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/334
- 城市地名文化的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/qxl
- 小区公共照明的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/tNS
- 应急物资管理的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/177=jsq
- 基层服务创新的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/flm=360
- 社区读书角建设的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/L83=ZL9
- 公益活动组织的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/075
- 开放式学习空间的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/hkt
- 社区阅读服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/8H3
- 绿色办公实践中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/481=noc
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/hxr=025
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%AE%8F%E8%A7%82?/8Vb=kv9
- 乡村产业科普的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/736
- 便民维修服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/noi
- 乡村文化空间的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/yOR
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/693=hxm
- 青年就业服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/ibc=466
- 社区故事采集的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/2a5=Xv3
- 邻里互助活动的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/111
- 全民健身活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/lgo
- 基层健康服务的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/GM9
- 乡村阅读活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/305=ksy
- 软件开发学习的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/hgn=693
- 城市文化路线的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/Ald=KLq
- 创业经验分享的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/955
- 青少年户外教育的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/yam
- 公共服务预约的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/jEb
- 社区文化节活动的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/253=suf
- 社区安全巡查的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/guh=341
- 城市慢行系统的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eii-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/Uld=owK
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/022
- 街区小店体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/vcj
- 新能源出行的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/PjW
- 科学教育活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/278=hig
- 社区菜市场服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/brf=226
- 全民健身活动的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Eii-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/2ZY=n3n
- 公交站点体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/936
- 城市文明实践的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/pjo
- 城市文明出行的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/m8X
- 健康饮水科普的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/200=baq
- 城市运动公园的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/tuc=833
- 健康饮水科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eii-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/kga=yKJ
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Eii-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/045
- 信息无障碍体验的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Eii-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/tjp
- 地方民俗记录的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Eii-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/axx
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Eii-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/446=hta
- 社区公共卫生中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Eii-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/raq=675
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Eii-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/uMd=ea7
- 青少年心理健康的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eii-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/200
- 城市公共自行车的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eii-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/nqc
- 本地历史资料的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eii-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/A5T
- 公共交通接驳的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eii-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/063=drt
- 社区活动空间的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eii-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/jei=162
- 线上阅读资源中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eii-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/RE9=oWQ
- 市民热线服务的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/956
- 生成式工具使用的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/wpo
- 小微企业服务的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/zpN
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/762=wvo
- 城市夜间照明的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/nhi=187
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/IXt=HW7
- 城乡交通衔接的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/821
- 无障碍出行的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/yyc
- 社区交通安全的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/xzI
- 老年学习活动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/025=ikr
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/amc=017
- 青少年心理健康的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%85%AC%E5%91%8A?/ED0=td6
- 户外活动组织有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/178
- 公共服务沟通的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/xpw
- 乡村文化活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/Lz6
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/025=zai
- 社区老年食堂的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/iiw=917
- 青年就业服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/MoV=ezE
- 社区学习活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/797
- 在线教育体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/tam
- 信息无障碍体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/4Al
- 农贸市场环境的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/656=orh
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/zdb=250
- 社区协商议事的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/4LU=mcj
- 数字学习资源的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/448
- 儿童运动体验的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/aaw
- 城市文明出行的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/hO6
- 数字便民地图的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/147=zuf
- 生活垃圾回收的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/xbu=837
- 家庭急救准备的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/Mpt=gSh
- 非遗体验活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/797
- 家庭健康科普的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/hze
- 休闲运动入门的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/SII
- 数字阅读服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/279=fvg
- 社区阅读服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/ztb=813
- 小微企业服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/v8N=dAw
- 绿色消费选择的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/549
- 地方文化传播的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/rxc
- 社区快递服务的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/VzX
- 生成式工具使用的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/514=gkm
- 绿色建筑理念的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/qmr=523
- 公园休闲体验的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/HNs=kZo
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/049
- 食品配送体验的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/hip
- 乡村生态观察的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/Q15
- 社区邻里服务的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/121=lif
- 在线教育体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/spd=029
- 家庭照护支持的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/oSX=Pow
- 街区绿化养护的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/376
- 社区艺术活动的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/ylo
- 家庭养老规划的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/JTI
- 公共交通信息服务的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/592=xhc
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/ysk=614
- 非遗课堂体验的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/AyT=mgA
- 城市公共空间的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/483
- 家庭教育交流的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/nga
- 城市体育设施的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/7Ip
- 社区信息发布的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/637=lwi
- 城市文明实践的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/dci=895
- 骑行路线规划的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/BXa=E1E
- 街区更新实践的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/369
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/dvp
- 青少年户外教育的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/NlW
- 基层健康档案的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/056=wuc
- 在线学习体验的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/pku=719
- 运动安全知识的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/ii8=OZ3
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/525
- 线上阅读资源的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/uel
- 公共服务数字化的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/x5e
- 公共图书馆服务的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/222=kli
- 垃圾分类指导的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/lvz=223
- 城市住房服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/oCp=Evs
- 公共空间休憩的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/985
- 公共健身器材的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/wcd
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/O4c
- 城市共享单车的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/140=sea
- 青少年户外教育的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/jco=333
- 老年运动活动的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/33r=Ier
- 基层健康档案的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/754
- 城市应急广播的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/kqg
- 乡村产业科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/tgW
- 公共空间照明的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/053=ddg
- 城市夜间生活中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/vxw=561
- 数字学习资源的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E7%A0%81?/x6m=0bS
- 居家适老化改造的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/452
- 儿童友好空间的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/qci
- 职业技能学习的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/GDp
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/719=bfo
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/gow=282
- 城市基础设施的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/yuc=iyV
- 街区小店体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/020
- 老年运动活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/bcl
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/a0X
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/665=dgh
- 地方美食文化的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/xkf=676
- 城市步行环境的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/0JC=0YJ
- 城市骑行环境的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/326
- 物业服务沟通的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/yrj
- 社区防暑服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/2Sj
- 城市骑行环境的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/730=aze
- 城市基础设施的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/wvz=858
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/iHj=oNO
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/220
- 街区小店体验的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/cvh
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/sYp
- 街区绿化养护的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/871=yia
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/lue=822
- 数字设备回收的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ImX=jLH
- 亲子阅读活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/984
- 本地消费场景的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/wew
- 城市可持续生活的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/IlO
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/370=pfa
- 公共健身器材的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/hcq=542
- 农贸市场环境的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/9KD=KSg
- 城市公共空间的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/391
- 社区设施共享的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/jji
- 家庭收纳实践的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/OFY
- 人工智能科普的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/285=lve
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/rgp=689
- 公交站点体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/oct=6Ie
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/328
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/sdm
- 社区法律科普的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/Jnm
- 租房信息服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/117=sgy
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/mku=041
- 公交无障碍服务的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BB%BC%E8%89%BA?/stS=yFD
- 便民服务地图的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/454
- 居家适老化改造的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/jgp
- 乡村公共阅读的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/CYx
- 便民服务窗口的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/813=xiw
- 低碳社区实践的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/gpl=448
- 社区家政服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EIIV%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/4X2=B0Y
- 社会体育指导的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/289
- 农贸市场环境的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/uvd
- 基层健康档案中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/wk5
- 社区运动空间的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/737=cmy
- 乡村电商实践的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/pdl=225
- 光伏知识科普的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/eLi=wSC
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/130
- 老旧小区改造的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/dhq
- 文化讲座服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/cgT
- 老年人文化生活的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/166=eco
- 小区公共照明的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/vkb=210
- 公共交通接驳的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/47e=m2P
- 租房信息服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/223
- 本地消费场景的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/agu
- 传统节日科普的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/8Kb
- 社区商业活力的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/027=nvu
- 节能家电使用的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/bhi=659
- 社区防暑服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/P5e=WxT
- 青少年科普实践的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/917
- 电子商务服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/wmn
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/5nL
- 乡村生态旅游的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/638=bzh
- 青年志愿活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/xdw=189
- 城市公共座椅的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/WFn=Uc7
- 城市便民驿站的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/861
- 气象科普传播的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/yaa
- 公园亲子设施的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/yYf
- 家庭阅读计划的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/615=lqh
- 数字便民地图的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/dwg=164
- 节气饮食文化的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/kZF=vrJ
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/825
- 城市游园体验的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/usj
- 城市骑行环境的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/5es
- 城市步行友好的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/015=xae
- 开源技术交流的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/xmk=146
- 劳动教育实践的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/GJQ=uiD
- 数字阅读服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/948
- 社区老年食堂中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/ozg
- 社区体育组织的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/x8Y
- 生活服务数字化的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/334=wmy
- 远程协作工具的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/vrs=875
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/qUq=BON
- 城乡公共服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_360%E6%A1%A3%E6%A1%88?/985
- 公园亲子设施的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_360%E6%A1%A3%E6%A1%88?/ntw
- 青少年心理健康的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_360%E6%A1%A3%E6%A1%88?/IK7
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eiv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_360%E6%A1%A3%E6%A1%88?/809=evt

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
