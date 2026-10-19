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

- 绿色办公实践的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/jwu=391
- 老旧小区改造的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/eZ8=CEw
- 线上办事服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/526
- 社区便民集市的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/ecf
- 绿色消费选择的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/wzy
- 校园安全教育的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/379=srn
- 无障碍出行中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/qyx=659
- 绿色快递包装的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/VXX=YTb
- 城乡交流活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/376
- 绿色校园实践的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/kpo
- 便民服务地图的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/BLy
- 食品配送体验的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/275=eer
- 软件开发学习的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/cbb=214
- 科学观察活动的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/Nli=C4E
- 社区休闲设施的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%A5%BC%E5%B8%82?/729
- 社区读书角建设的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%A5%BC%E5%B8%82?/fyq
- 社区活动策划的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%A5%BC%E5%B8%82?/Tbd
- 数字课堂应用的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%A5%BC%E5%B8%82?/836=zyg
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%A5%BC%E5%B8%82?/con=198
- 城市绿色交通的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%A5%BC%E5%B8%82?/vts=mat
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/314
- 节假日出行安排的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/jdf
- 社区安全巡查的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/EdL
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/631=kzt
- 图书借阅体验的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/nxe=682
- 城市游园体验的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/nbA=qEN
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/697
- 生活技能分享的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gmp
- 老年学习活动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/pha
- 小区停车协商的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/700=lvp
- 社区家政服务的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zgo=172
- 家庭饮食安排的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ZaV=kJd
- 公共服务咨询的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/387
- 数字地图应用的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/xfh
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/oQb
- 绿色消费选择中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/811=evl
- 家庭环保行动的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/lcq=084
- 乡村电商实践的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/68D=v89
- 生活垃圾回收的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/527
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/hci
- 远程协作工具的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/st9
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/825=kvr
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/tio=492
- 城市绿道建设中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/l1g=6Nw
- 节日文化体验的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/004
- 全民健身活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/xoi
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/iNx
- 家庭安全提示的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/239=alt
- 科学教育活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/ryu=951
- 物业服务沟通的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/Nq1=uZS
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/729
- 数字学习资源的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/kta
- 食品配送体验的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/WeM
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/018=leb
- 乡村公共文化的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/aml=403
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%B1%BD%E8%BD%A6%E8%B4%A2%E7%BB%8F?/Wpj=djU
- 家庭健康科普的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/348
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/hbs
- 乡村生态旅游的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/25B
- 垃圾分类指导的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/177=tpy
- 公园亲子设施的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/caz=735
- 城市公共艺术的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/7Rx=GKi
- 社区交通安全的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/568
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/que
- 数字课堂应用中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/ngH
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/772=xon
- 儿童友好空间的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/lni=847
- 公共空间安全的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/au7=4da
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/347
- 本地旅行体验的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/feq
- 家庭运动计划的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/39R
- 社区故事采集的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/423=tyi
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/cav=785
- 地方民俗记录的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/wa1=7fP
- 数字设备回收的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/216
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/jpq
- 城市共享单车的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/l8b
- 地方民俗记录的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/990=sog
- 家庭消费规划的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/qjq=659
- 数字课堂应用的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/Tgm=c3g
- 低碳社区实践的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/135
- 骑行路线规划的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/tsc
- 健康步道使用的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/zWv
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/873=pvs
- 基层健康档案的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/kzh=810
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/Wad=XLi
- 数字政务体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/860
- 公共图书馆服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/yuk
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/kCG
- 公共卫生设施的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/585=eib
- 家庭环保习惯的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/pss=382
- 城市绿道建设的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/N7w=BWk
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_360%E5%AE%B6%E7%94%B5?/296
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_360%E5%AE%B6%E7%94%B5?/gfg
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_360%E5%AE%B6%E7%94%B5?/9nI
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_360%E5%AE%B6%E7%94%B5?/888=nck
- 便民服务地图的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_360%E5%AE%B6%E7%94%B5?/hjx=792
- 公园无障碍服务的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_360%E5%AE%B6%E7%94%B5?/KM5=l3N
- 城市噪声观察的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/830
- 城市文明出行的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/eyb
- 小区电梯维护的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/O86
- 乡村公共阅读的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/244=wtq
- 社区休闲设施的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/bfa=704
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E7%BE%8E%E9%A3%9F?/epI=POo
- 城市文化路线的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%89%E9%98%B2?/360
- 社区生活指南的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%89%E9%98%B2?/uie
- 应急物资管理的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%89%E9%98%B2?/w0Z
- 绿色校园实践的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%89%E9%98%B2?/688=cbk
- 老年人日常照护的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%89%E9%98%B2?/kng=724
- 社区手工活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%AE%89%E9%98%B2?/MJe=mgv
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/001
- 居家防滑改造的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/ezf
- 校园阅读活动的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/Cvm
- 乡村教育资源中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/016=sfc
- 公共空间照明的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/cbx=235
- 社区阅读服务的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/Wbj=lb1
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/796
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/fye
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/y5h
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/372=ats
- 创业经验分享的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/hjh=766
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/uDe=bao
- 节气饮食文化中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AF%BB%E6%8A%A5?/608
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AF%BB%E6%8A%A5?/vyl
- 文明养宠科普的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AF%BB%E6%8A%A5?/l20
- 城市住房服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AF%BB%E6%8A%A5?/950=cfm
- 城市慢跑路线的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AF%BB%E6%8A%A5?/ibb=836
- 社区交通安全的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%AF%BB%E6%8A%A5?/XAc=wOT
- 食品配送体验的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/762
- 城市运动公园的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/oww
- 节假日出行安排的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/RjC
- 绿色生活实践的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/589=vdh
- 数字艺术创作的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/nia=980
- 数字艺术创作的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/3KS=2nr
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/065
- 街区更新实践的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/fyp
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/UoW
- 公共服务咨询的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/640=rhv
- 校园节能行动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/hdw=413
- 科学运动指导从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BE%97%E7%89%A9%E9%80%9F%E8%A7%88?/6BL=TCV
- 公交无障碍服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/307
- 社区花园共建的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/ffo
- 街区道路维护的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/fMW
- 城市生活记录的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/137=smi
- 城市慢行系统的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/ywu=597
- 科学观察活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/nXn=DVQ
- 社区休闲设施的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_360%E6%A5%BC%E5%B8%82?/225
- 城乡公共服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_360%E6%A5%BC%E5%B8%82?/uej
- 亲子阅读活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_360%E6%A5%BC%E5%B8%82?/MdG
- 开源技术交流的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_360%E6%A5%BC%E5%B8%82?/306=phj
- 数字档案服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_360%E6%A5%BC%E5%B8%82?/cvi=882
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_360%E6%A5%BC%E5%B8%82?/axA=qmK
- 灵活就业交流的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/371
- 家庭网络使用的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/tvm
- 个人信息保护的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/Jjg
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/522=jjc
- 青少年户外教育的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/dsv=820
- 社区老年食堂中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/S9d=wmL
- 儿童友好空间的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/934
- 骑行路线规划的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/ect
- 个人信息保护的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/toJ
- 社区故事采集的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/583=yfc
- 街区更新实践的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/pie=937
- 健康步道使用的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/bzY=xpz
- 租房信息服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/137
- 食品安全科普的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/tvi
- 公共服务咨询的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/Red
- 家庭网络使用的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/298=kvk
- 公共卫生宣传的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/eal=780
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/AkB=ibR
- 社区艺术活动的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/795
- 社区法律科普的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/mhg
- 城市树木认养的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/TSW
- 社区志愿服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/184=tgd
- 社区运动空间的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/let=314
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%BC%AB%E8%AF%84?/Fj3=a5i
- 职业技能学习的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/035
- 消防知识宣传的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/tkw
- 基层健康档案的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/6A4
- 乡村产业科普的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/807=qvb
- 生活垃圾减量的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/xud=502
- 人工智能科普的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/6yb=uJS
- 职业技能学习中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/598
- 数字公共文化的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/bcb
- 青少年心理健康的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/qvi
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/584=fnn
- 街道综合服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/cec=221
- 校园社团活动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/0PO=XaQ
- 图书借阅体验的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/231
- 社区阅读服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/pqk
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/Mj9
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/120=hib
- 公共空间安全的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/ktd=283
- 日常摄影记录的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%BE%8E%E6%B9%83%E8%AF%BB%E4%B9%A6?/zBa=8vh
- 终身学习资源的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/506
- 科学健身方法的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/jlp
- 家庭节能实践的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/6LF
- 居民健康教育的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/928=fdn
- 城市雨天出行的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/rko=033
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/YdM=GVo
- 社区互助网络的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/514
- 公共服务数字化的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/uou
- 城乡交通衔接的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/JrZ
- 老年智能设备的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/691=pup
- 农村环境治理的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/djx=812
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/zpu=1su
- 运动安全知识的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/149
- 青少年户外教育中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/nxz
- 乡村电商实践的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/5Ha
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/593=efn
- 农贸市场环境的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/xxs=518
- 公共空间导览的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/lRP=NG5
- 运动安全知识的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/930
- 全民健身活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/zmj
- 公共场所导视的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/1dH
- 城市公共空间的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/265=gmp
- 图书馆数字服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/xib=638
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/Q11=PON
- 城市步行友好中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/384
- 本地历史资料的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/stm
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/WCZ
- 城市适老服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/632=hxj
- 社区托育服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/sdt=746
- 城市夜间照明的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/RoA=ENg
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%80%81%E5%A4%A7_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/251
- 数字支付体验的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%80%81%E5%A4%A7_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/tnj
- 社区阅读服务的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%80%81%E5%A4%A7_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/eEJ
- 老年数字阅读的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%80%81%E5%A4%A7_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/129=ldm
- 开放式学习空间的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%80%81%E5%A4%A7_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/zhh=049
- 城市游园体验的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%80%81%E5%A4%A7_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/MTR=ZzG
- 城市住房服务的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6app_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/907
- 市民热线服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6app_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/nxu
- 开源技术交流的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6app_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/ZWR
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6app_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/503=vgm
- 家庭急救准备的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6app_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/aqt=990
- 周末休闲规划的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6app_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/vp6=OVo
- 社区艺术活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/368
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/hvb
- 电子商务服务的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/WY6
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/026=eow
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/xew=239
- 社区环保活动的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/24P=R2l
- 社区商业活力的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/651
- 青少年户外教育的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/kxx
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/vJk
- 科普展览体验的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/796=sca
- 机器学习入门的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/yoz=223
- 开源技术交流的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/4Xy=TS0
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/756
- 城市噪声观察的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/afb

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
