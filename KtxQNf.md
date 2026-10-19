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

- 农贸市场环境的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/964
- 食品安全科普的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/axp
- 文明养宠科普的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/1eZ
- 公共空间导览的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/352=mua
- 地方旅游导览的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/yxd=864
- 家庭志愿活动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/2MP=EQt
- 校园节能行动的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/269
- 家庭节能设备的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/her
- 城市应急科普的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/uIv
- 校园社团活动的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/376=gaq
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/jra=684
- 绿色建筑理念的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/GBn=MFC
- 光伏知识科普的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/618
- 家庭运动计划的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/piw
- 社区读书角建设的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/AMC
- 公共健身器材的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/995=wnm
- 便民服务地图的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/qiv=723
- 急救知识普及的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/Xtg=ONf
- 数据分析入门的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E5%81%A5%E8%BA%AB?/669
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E5%81%A5%E8%BA%AB?/uyd
- 图书馆活动策划的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E5%81%A5%E8%BA%AB?/H39
- 城市绿色交通有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E5%81%A5%E8%BA%AB?/175=ntx
- 社区公共卫生的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E5%81%A5%E8%BA%AB?/opu=010
- 节气饮食文化的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E5%81%A5%E8%BA%AB?/z0P=sUZ
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/812
- 城市雨天出行中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/nxo
- 图书馆活动策划的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/rsK
- 乡村公共文化的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/106=ghq
- 租房信息服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/hkw=605
- 家庭消费规划的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/WUr=yDX
- 图书馆数字服务的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_360%E5%85%AC%E5%BC%80%E8%AF%BE?/892
- 数字艺术创作的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_360%E5%85%AC%E5%BC%80%E8%AF%BE?/jvj
- 社区养老服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_360%E5%85%AC%E5%BC%80%E8%AF%BE?/d6Y
- 公共设施维护的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_360%E5%85%AC%E5%BC%80%E8%AF%BE?/311=pkd
- 社区庭院绿化的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_360%E5%85%AC%E5%BC%80%E8%AF%BE?/gnc=529
- 图书馆活动策划的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_360%E5%85%AC%E5%BC%80%E8%AF%BE?/alN=d4y
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/136
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/hhs
- 本地消费场景的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/1Mm
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/820=ikc
- 个人数据管理的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/tbk=189
- 创业经验分享的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/mQ2=5bO
- 骑行路线规划的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/154
- 社区商业活力的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/abt
- 环境教育课程的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/TqX
- 基层健康服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/128=apa
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/jxr=882
- 社区活动策划的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/dne=wGb
- 乡村阅读空间的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/010
- 创业经验分享的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/rgt
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/N5v
- 社区健康讲座的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/036=vig
- 城市公共艺术的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/skr=990
- 儿童友好空间的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/HOu=AHp
- 社区共享书架的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/856
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/nir
- 社区信息发布的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/env
- 创业经验分享的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/751=oxy
- 在线教育体验的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/klx=976
- 小区电梯维护的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/mjE=Q0l
- 公共卫生设施的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/006
- 社区活动策划的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/bzf
- 社区活动报名中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/Srg
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/544=ydf
- 乡村文化空间的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/ikl=190
- 家庭急救准备的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/RWd=MJI
- 城市雨天出行的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/152
- 无障碍出行的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/npu
- 数字便民地图的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/29a
- 儿童阅读角的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/434=xhj
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/gji=521
- 社区垃圾回收的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/Sws=vxk
- 节能家电使用的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/435
- 绿色消费选择的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/jwf
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/4TG
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/283=eqn
- 家庭环保行动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/ftf=458
- 亲子阅读活动的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A1%A8_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/Cog=CnT
- 乡村电商实践的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/025
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/xmq
- 家庭食品保存的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/zIo
- 在线学习体验的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/473=usy
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/jxw=273
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/XTf=N8F
- 文明养宠科普中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/234
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/uqa
- 城市步行友好的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/wEF
- 城市博物馆服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/918=cyf
- 数字课堂应用的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/jxj=477
- 城市生活记录的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E6%8E%A2%E6%BA%90?/w0L=zwB
- 市民热线服务的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/558
- 亲子科普活动的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/joc
- 公共场所导视的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/Ue2
- 社区健康讲座的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/224=kdz
- 社区阅读服务的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/xso=420
- 健康信息获取的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/VP0=STj
- 在线教育体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/926
- 城市夜间照明的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/fcv
- 街区小店体验中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/FpZ
- 无障碍信息设计的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/189=iyq
- 基层医疗预约的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/faq=101
- 公共空间安全的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%88%86%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/dES=tJ0
- 青少年科技社团的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/087
- 数字创作工具的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/cyq
- 学校体育活动的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/U3Z
- 城乡交通衔接的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/068=lln
- 小区电梯维护的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/plh=739
- 社区运动空间的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%BB%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/QOf=vmd
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/745
- 青年职业探索的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/tzp
- 校园社团活动的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/td2
- 城市农夫市集的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/967=jaj
- 城市慢行系统的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/lky=380
- 数字生活课堂的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E4%BD%9C%E5%BC%8A%E8%A7%84%E5%BE%8B%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/4gn=8HY
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/389
- 数字便民地图的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/bdk
- 城市公共座椅的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/lkc
- 街区绿化养护的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/304=thz
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/wbn=359
- 节假日出行安排的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/xeX=0Fy
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/722
- 便民维修服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/kmc
- 校园阅读活动的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/dyp
- 社区艺术活动的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/721=rgm
- 骑行路线规划的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/eoz=372
- 城市公共艺术的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/0vT=MrP
- 农贸市场环境的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/271
- 远程协作工具的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/kbi
- 灵活就业交流的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/g7N
- 数字生活课堂的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/233=ilf
- 校园社团活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/rnn=373
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/r3r=lm7
- 城市公共标识的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/281
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/xkp
- 地方民俗记录的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/M1x
- 在线教育体验的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/645=nys
- 社区邻里服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/mak=990
- 社区知识分享的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/zUH=kUu
- 在线教育体验的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/820
- 在线学习体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/bpl
- 数字阅读服务的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/9LN
- 城市微更新实践的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/039=sls
- 城乡交流活动的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zbr=868
- 社区应急准备的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/wk1=oSh
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/333
- 家庭用电安全的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/euk
- 地方戏曲体验的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/NEX
- 开放式学习空间的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/953=uwq
- 数字创意课程的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/ttv=716
- 读书会组织的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/H16=NW8
- 校园节能行动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/954
- 城市便民驿站的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/xsf
- 街区小店体验的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/kVu
- 城市绿道建设的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/688=uhs
- 数字生活课堂的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/qnr=584
- 户外活动组织中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E8%81%8C%E5%9C%BA?/6W6=jo0
- 街区道路维护的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/355
- 家庭理财科普的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/ynz
- 城市应急广播的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/LKU
- 线上阅读资源的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/378=qxk
- 城市适老服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/frc=551
- 城市绿色交通的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/pWI=ajX
- 乡村教育资源的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/998
- 农村环境治理的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/iap
- 科学信息获取的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/6qy
- 城市博物馆活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/562=mkw
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/iwx=741
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A7%82%E5%AF%9F?/Z9F=8YQ
- 社区休闲设施的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E9%97%AE%E5%8D%B7?/874
- 城市展览体验的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E9%97%AE%E5%8D%B7?/len
- 社区知识分享的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E9%97%AE%E5%8D%B7?/OBp
- 绿色快递包装的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E9%97%AE%E5%8D%B7?/688=jwc
- 机器学习入门的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E9%97%AE%E5%8D%B7?/xyy=031
- 城市步行友好中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_360%E9%97%AE%E5%8D%B7?/nLC=skF
- 青少年科技社团的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/542
- 低碳社区实践的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/oul
- 家庭环保习惯的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/wAR
- 家庭收纳实践的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/413=tdy
- 社区学习活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/bbg=990
- 公园休闲体验的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%97%B6%E5%B0%9A?/Bbr=5ES
- 居民健康教育的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/231
- 公共健身器材的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/kuw
- 公共空间照明的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/hLp
- 家庭消费规划的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/067=qla
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/hik=885
- 城市体育设施的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/KI3=Dc2
- 社区便民集市的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/548
- 公共健身器材的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/fjy
- 软件开发学习的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/fKH
- 城市体育设施的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/738=ytc
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/iyj=801
- 社区公共议事的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/Men=qNr
- 劳动教育实践的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/042
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/iqx
- 儿童户外活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/lgG
- 老年友好服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/132=wcm
- 儿童运动体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/ewe=550
- 城市公共自行车的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/mUq=YB7
- 街头绿植养护的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/267
- 健康信息获取的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/trt
- 绿色生活实践的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/rS6
- 老年人文化生活的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/893=wpp
- 地方美食文化的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/xsd=122
- 乡村产业科普的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%88%86%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/39z=wJt
- 光伏知识科普中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/196
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/coj
- 家庭节能实践的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/VNc
- 科技馆参观体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/995=dkw
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/ehi=132
- 城市公共标识的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E6%96%87%E5%8C%96?/Ry0=4jb
- 老年智能设备中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/330
- 职业技能学习的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/zev
- 家庭消费规划的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/dOy
- 家庭园艺实践的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/316=gdq
- 健康饮食教育的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/eim=135
- 食品配送体验中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/gxq=70D
- 老年人文化生活的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/326
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/fae
- 光伏知识科普的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/EUE
- 儿童阅读角中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/270=grs
- 家庭环保习惯的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/wnt=927
- 急救知识普及的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/Uo6=zgY
- 社区体育组织的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/293
- 老年智能设备的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/ryw
- 小区电梯维护的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/l2X
- 图书借阅体验的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/896=tdh
- 公共场馆服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/vib=502
- 本地旅行体验的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/fme=c41
- 城市骑行环境的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/218
- 儿童户外活动的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/ncm
- 老年人出行服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/Gus
- 社区老年食堂的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/271=wzt
- 社区阅读服务的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/odm=496
- 社区协商议事的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/1mq=sCx
- 社区知识分享的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%BD%91%E6%98%93%E6%92%AD%E6%8A%A5?/795
- 公园休闲体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%BD%91%E6%98%93%E6%92%AD%E6%8A%A5?/wua
- 城市可持续生活的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%BD%91%E6%98%93%E6%92%AD%E6%8A%A5?/iBv
- 社区活动策划中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%BD%91%E6%98%93%E6%92%AD%E6%8A%A5?/672=crh
- 社区安全巡查的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%BD%91%E6%98%93%E6%92%AD%E6%8A%A5?/fxo=213
- 邻里共享空间的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%BD%91%E6%98%93%E6%92%AD%E6%8A%A5?/DJt=Tze
- 社区心理支持的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/277
- 旧物循环利用的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/zsv
- 城市农夫市集的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/Pa3
- 小微企业服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/456=zig
- 数字档案服务的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/aex=140
- 社区共享书架的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/mrP=QOt
- 家庭环保行动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/731
- 全民阅读推广的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/jvi
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/akm
- 农贸市场环境的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/795=kpf

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
