# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 农产品品牌传播的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95app_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/6P0
- 数字生活课堂的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95app_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/364=pmu
- 数字支付体验的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95app_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/qnw=713
- 青年就业服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95app_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/9aQ=uaq
- 家庭用电安全的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/661
- 公共健身器材的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/xtb
- 城市生活服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/2qR
- 社区运动空间的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/699=gjb
- 城市步行友好的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/yhz=108
- 社会体育指导的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/8NY=z5s
- 老旧小区改造的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/396
- 骑行路线规划的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/tpd
- 社区消防演练的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/jq1
- 急救知识普及的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/035=mml
- 城市应急科普的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/flg=390
- 校园安全教育的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/U2m=zXy
- 社区艺术活动的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/835
- 社区故事采集的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/bxz
- 城市慢行系统的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/vAm
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/518=njl
- 家庭食品保存的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/dwc=437
- 消防知识宣传的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/MA7=6Cr
- 通勤路线规划的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/577
- 老年友好服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/ztn
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/FeT
- 就业技能培训的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/351=pqb
- 通勤路线规划的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/agx=670
- 家庭志愿活动的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/Wgy=ESk
- 绿色出行服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/642
- 就业技能培训的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/ujg
- 乡村公共文化的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/cXv
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/934=ieh
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/vjz=915
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/itU=rNL
- 市民意见收集的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/734
- 居民健康教育的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/ymg
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/QmU
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/286=gve
- 网络安全教育的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/otj=211
- 课后服务体验的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/5Qf=G16
- 公共设施使用的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/687
- 校园节能行动的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/hpf
- 社区商业活力的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/Jbk
- 课后服务体验的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/161=zrn
- 城市休闲步道中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/orv=971
- 家庭理财科普的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/WYv=XL1
- 数据分析入门的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/633
- 青年就业服务的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/dji
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/pdx
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/256=yjm
- 志愿服务平台的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/ffk=433
- 就业技能培训的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/KXj=kIj
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/378
- 家庭环保行动的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/zmw
- 物业服务沟通的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/vv2
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/755=nfj
- 网络安全教育的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/gmn=529
- 便民维修服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/qax=ON2
- 机器人科普活动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/246
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/byd
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/Ne0
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/405=gna
- 城市基础设施的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/eqm=755
- 家庭消费规划的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E8%AE%AF?/4Ql=RTV
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/216
- 亲子阅读活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/xkd
- 数字政务体验的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/WiV
- 公共服务指南的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/233=isj
- 公共服务数字化的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/eof=306
- 青少年编程学习的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/SjM=dy9
- 生活垃圾减量的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/596
- 城市休闲步道的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/idq
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/QAO
- 便民信息查询的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/695=ydk
- 社区养老服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/kvs=000
- 节能生活方式的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/KTM=LN7
- 小区公共照明的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/415
- 生活技能分享的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/qcd
- 线上阅读资源的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/Hpg
- 图书借阅体验的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/307=yak
- 物业服务沟通的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/frr=048
- 乡村生活观察的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/1MG=n0L
- 机器学习入门的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/290
- 便民服务地图的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/rym
- 公共卫生设施的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/Z27
- 社区菜市场服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/096=nhp
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/dju=863
- 城市应急广播的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/fNs=B8V
- 城市基础设施的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/879
- 家庭节能实践的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/evq
- 网络安全教育的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/8IJ
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/465=gnw
- 校园阅读活动的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/tdi=632
- 口袋公园建设的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/KHV=7Su
- 城市生活服务的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/242
- 城市博物馆服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/kdd
- 生活技能分享的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/OZ0
- 家庭志愿活动的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/831=glv
- 公共服务评价的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/dvw=004
- 便民信息查询的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/KIo=mxy
- 社区体育组织的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/952
- 社会体育指导的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/skm
- 城市地名文化的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/jCF
- 社区宠物管理的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/584=agg
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/xgf=300
- 社区修缮行动的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/Ed1=VXa
- 城市共享单车的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%8F%B7%E5%BD%A9%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/414
- 食品配送体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%8F%B7%E5%BD%A9%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/fah
- 急救知识普及的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%8F%B7%E5%BD%A9%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/zMm
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%8F%B7%E5%BD%A9%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/667=ruj
- 旧物循环利用的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%8F%B7%E5%BD%A9%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/hbi=893
- 公共空间休憩的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%8F%B7%E5%BD%A9%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/jPn=9iI
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/442
- 城市骑行环境的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/pim
- 科学运动指导的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/2HW
- 生活服务数字化的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/513=zwf
- 数字资源检索的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/cik=568
- 公交站点体验的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/ofH=V4A
- 社区防暑服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/109
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/fho
- 儿童友好街区的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/okh
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/265=hhi
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/yxz=809
- 城市骑行环境的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/LSX=HAy
- 数字设备回收的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/629
- 城市文化路线从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/alk
- 城市公共艺术的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/L6M
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/504=uho
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/xhx=183
- 社区互助网络的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%9F%8E%E4%BA%8B?/bls=Dlr
- 公共卫生设施的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8C%85%E8%B5%94_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/737
- 文明养宠科普的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8C%85%E8%B5%94_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/nwc
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8C%85%E8%B5%94_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/Wxy
- 城市文明实践的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8C%85%E8%B5%94_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/624=rdb
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8C%85%E8%B5%94_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/tcc=272
- 儿童安全出行的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8C%85%E8%B5%94_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/OOe=Qls
- 跨代沟通活动的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/154
- 地方民俗记录的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/qsg
- 物业服务沟通的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/nvY
- 智慧城市体验的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/723=mjg
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/gig=459
- 绿色快递包装的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/NII=kzI
- 公共空间安全的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/334
- 数据分析入门的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/jwj
- 社区交通安全的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/2ti
- 家庭运动计划的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/428=znx
- 地方民俗记录的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/imh=499
- 租房信息服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_360%E5%9B%BE%E9%89%B4?/7hv=yXI
- 社区文化节活动的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/770
- 市民热线服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/svq
- 社区休闲设施的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/sd7
- 公共服务评价的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/127=vad
- 青少年编程学习中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/bzn=086
- 软件开发学习的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Cqq%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/MS1=vfM
- 社区心理支持的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/941
- 街区小店体验的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/oaw
- 乡村文化空间的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/0WL
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/028=gzj
- 创业经验分享的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/swe=523
- 社区家政服务的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/3zz=FHR
- 邻里共享空间的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/255
- 健康信息获取的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/lah
- 乡村生态观察中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/c50
- 生活技能分享的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/603=wqi
- 社会体育指导的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/dfo=833
- 城市游园体验的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/mmM=MiS
- 社区读书角建设的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AB%98%E6%89%8B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/003
- 社区花园共建的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AB%98%E6%89%8B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/njb
- 健康饮食教育的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AB%98%E6%89%8B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/tC0
- 骑行路线规划的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AB%98%E6%89%8B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/667=hmu
- 城市公共艺术中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AB%98%E6%89%8B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/lwn=969
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%AB%98%E6%89%8B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/zKb=VDH
- 绿色生活实践的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/132
- 小区停车协商的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/reu
- 全民阅读推广的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/ZEN
- 乡村文化活动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/972=hov
- 公园亲子设施的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/sww=133
- 智能手机助老的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/1Hh=hSj
- 社区便利生活的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/182
- 数据分析入门的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/emb
- 社区公共议事的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/sto
- 公共空间安全的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/156=bpz
- 家庭用电安全的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/eie=654
- 公共服务数字化的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/Els=C2R
- 家庭照护支持中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/708
- 光伏知识科普的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/jzk
- 小区公共照明的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/Gb1
- 节日文化体验的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/121=goc
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/eye=605
- 社区公共餐饮的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/hOW=mku
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/530
- 非遗体验活动的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/dnq
- 儿童友好空间的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/Sqq
- 青年志愿活动的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/880=dsm
- 城市文明出行的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/sok=461
- 数字生活课堂的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/ibb=QOl
- 骑行路线规划的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/289
- 数字素养提升的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/mtb
- 科技馆参观体验的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/J7M
- 垃圾分类指导的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/715=yty
- 老年智能设备的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/smw=078
- 城市应急科普的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/BJW=aZo
- 在线教育体验的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/492
- 数字便民地图的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/cor
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/r5F
- 基层医疗预约的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/326=omx
- 儿童安全出行中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/otk=278
- 乡村阅读活动的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/yvo=iEp
- 个人时间管理的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/460
- 数字创作工具的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/zmn
- 应急物资管理的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/ypt
- 地方民俗记录的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/019=gjz
- 公共健身器材的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/vao=078
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/lnD=NgF
- 读书会组织的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/850
- 社区停车服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/fml
- 老年智能设备的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/yEi
- 地方旅游导览的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/762=lsl
- 家庭科学教育的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/bww=984
- 城市步行环境的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/OwE=GKO
- 新能源出行的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/411
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/hfb
- 小区公共照明的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/yBf
- 科学信息获取的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/634=nfq
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/xxu=086
- 社区学习活动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/1JB=jXG
- 社区快递服务的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/418
- 儿童友好空间的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/pos
- 校园节能行动的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/h9d
- 应急物资管理的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/447=fat
- 家庭收纳实践的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/jjw=376
- 乡村产业科普的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/vlb=E83
- 社区儿童活动的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/164
- 城市可持续生活的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/inc
- 亲子阅读活动的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/6up
- 节约用水实践的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/890=yzq
- 绿色消费选择的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/gyp=882
- 全民健身活动的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/58g=5Xa
- 旧物循环利用的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/103
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/jcq
- 生活垃圾回收的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/8Z7
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/494=kvx
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/tyb=159
- 地方文化传播的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/u8b=Qly
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_5%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E4%B8%9C%E8%A5%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/990
- 个人信息保护的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_5%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E4%B8%9C%E8%A5%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/vly
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_5%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E4%B8%9C%E8%A5%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/snR
- 小区电梯维护的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_5%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E4%B8%9C%E8%A5%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/468=vfa
- 城市便民驿站的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_5%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E4%B8%9C%E8%A5%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/ngb=552
- 安全出行教育的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_5%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E4%B8%9C%E8%A5%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/Yxj=Kdt

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
