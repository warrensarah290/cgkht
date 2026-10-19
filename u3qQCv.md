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

- 青年就业服务的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/c1J
- 智慧停车服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/118=qlx
- 消防知识宣传的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/puy=854
- 乡村文化活动的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/pXS=gOt
- 城市文化路线的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/523
- 公共服务预约的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/oxg
- 日常摄影记录的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/PKb
- 邻里共享空间的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/257=cgp
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/jln=950
- 周末休闲规划的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/YZP=CvL
- 农贸市场环境的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/802
- 乡村文化活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/arb
- 家庭养老规划的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/6Qo
- 社区活动空间的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/345=ykd
- 地方民俗记录的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/xbu=200
- 社区活动策划的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/Kd7=SB6
- 传统节日科普的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/090
- 科学信息获取的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/xpe
- 线上阅读资源的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/31w
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/424=njc
- 社区体育组织的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/soz=112
- 居民健康教育的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/k04=Fma
- 城市公共标识的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/830
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/evh
- 科技馆参观体验的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/pk6
- 校园社团活动的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/825=qql
- 电动汽车充电的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/deh=824
- 通勤路线规划的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/jW9=n1z
- 城市建设科普的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/838
- 学校体育活动的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/lkb
- 绿色办公实践的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/lXF
- 城市夜间照明的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/349=ody
- 城市基础设施的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/wcn=717
- 网络信息辨识的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/LMP=mtL
- 机器学习入门的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/328
- 青年职业探索的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/pto
- 校园节能行动的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/UXe
- 社区商业活力的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/484=kqz
- 医院导诊服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/fyz=857
- 旧物循环利用的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/VnV=m3q
- 本地旅行体验的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/335
- 社区艺术活动的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/pyh
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/YGc
- 光伏知识科普的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/268=vih
- 地方戏曲体验的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/zsx=476
- 老年人日常照护的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/XEv=quf
- 城市公共厕所的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/395
- 读书会组织的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/wbg
- 节能家电使用的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/gRR
- 公共空间导览的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/733=tcd
- 小微企业服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/vhm=392
- 公共文化活动中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/gmh=FAb
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/156
- 城市应急科普的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/pbc
- 科学运动指导的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/pRQ
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/710=max
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/uaf=413
- 城市游园体验的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/uMP=LKM
- 安全出行教育的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/747
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/utn
- 社区便利生活的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/kgg
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/919=xlf
- 社区设施共享的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/niq=503
- 医院导诊服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/1Wr=bER
- 社区垃圾分类的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/045
- 公共服务数字化的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/wms
- 城市雨天出行的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/pbY
- 健康步道使用中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/566=dsi
- 志愿者培训交流的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/qhr=216
- 生成式工具使用中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/cca=wpM
- 城市体育设施的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/135
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/jln
- 城市雨天出行的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/2fE
- 城市可持续生活的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/673=hbf
- 城市体育设施的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/mca=778
- 乡村生活观察的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/4IO=3lK
- 乡村生活观察的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/498
- 城市适老服务的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/izg
- 公共设施维护的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/x74
- 家庭急救准备的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/090=hle
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/dkn=741
- 邻里互助活动的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/4OJ=OAE
- 社区活动空间的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/597
- 智慧城市体验的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/cdh
- 公共场馆服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/ev8
- 城乡公共服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/909=ibi
- 日常摄影记录的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/nic=043
- 便民维修服务的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/3BC=vfG
- 社区邻里服务的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/814
- 青少年户外教育的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/iwj
- 城市应急广播的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/aHf
- 医院导诊服务的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/576=zoj
- 城市慢行系统的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/wgd=947
- 社区活动空间的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/C7i=HC8
- 休闲运动入门中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/816
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/htt
- 城市公共艺术的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/UdP
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/937=qnc
- 科普展览体验的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/txl=294
- 社区交通安全的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/Iwp=NJX
- 社区活动空间的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/073
- 城市便民驿站的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/gqm
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/zaB
- 社区文化节活动的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/760=fje
- 乡村公共服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/rur=351
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/AHX=gMe
- 家庭食品保存的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/380
- 社区活动报名的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/mjf
- 公共服务预约的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/lxh
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/175=fdm
- 公交站点体验的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/kez=538
- 家庭教育交流的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/g6Q=KvD
- 城市运动公园的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/377
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/tcd
- 个人数据管理的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/2ox
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/392=sqv
- 青年志愿活动的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/ccy=313
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/mKV=8tF
- 城市公共座椅的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/346
- 全民健身活动的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/lpm
- 环境监测科普的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/8zF
- 绿色快递包装的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/885=qby
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/zpv=753
- 科技馆参观体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/kuH=wKq
- 城市慢行系统的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AE%89%E8%A3%85%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/176
- 老年人日常照护的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AE%89%E8%A3%85%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/zwo
- 社区艺术活动的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AE%89%E8%A3%85%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/aIG
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AE%89%E8%A3%85%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/783=yri
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AE%89%E8%A3%85%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/srp=903
- 电子商务服务的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AE%89%E8%A3%85%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/HMa=yu2
- 城市生活服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/790
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/mjr
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/L3E
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/720=mec
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/rua=459
- 基层服务创新的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/dXT=OuI
- 电动汽车充电的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%88%86%E6%9E%90%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/625
- 家庭养老规划的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%88%86%E6%9E%90%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/ywv
- 城市便民驿站的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%88%86%E6%9E%90%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/4II
- 全民健身活动的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%88%86%E6%9E%90%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/405=oap
- 社区垃圾回收的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%88%86%E6%9E%90%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/gyr=114
- 街区道路维护的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%88%86%E6%9E%90%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/BuO=2QM
- 社区共享书架的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/477
- 日常摄影记录的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/naw
- 城市体育设施中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/k7Q
- 家庭志愿活动的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/373=mkm
- 家庭网络使用的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/ouf=013
- 环境教育课程的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/26P=4v2
- 社区活动报名的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/098
- 数字支付体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/wjd
- 城市雨天出行的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/miA
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/119=cqt
- 新能源出行中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/msw=278
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/5La=fup
- 开源技术交流的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E5%85%A8%E9%83%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/910
- 乡村公共服务的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E5%85%A8%E9%83%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/str
- 社区停车服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E5%85%A8%E9%83%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/bi4
- 个人时间管理的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E5%85%A8%E9%83%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/858=enr
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E5%85%A8%E9%83%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/hvl=811
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E5%85%A8%E9%83%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/cMh=ekT
- 城市生活服务的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/218
- 信息无障碍体验的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/ypr
- 城市地名文化中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/U5E
- 城市生活服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/492=rtq
- 老年数字阅读的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/izj=182
- 市民意见收集的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/SkB=Bjr
- 家庭防灾准备的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/596
- 社区生活指南的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/wrc
- 社区商业活力的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/SSC
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/821=sxj
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/vsq=083
- 绿色出行服务的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/aY4=LpN
- 社区法律科普的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/137
- 数字创意课程的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/sga
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/FNr
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/402=qdn
- 老年人日常照护的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/yev=742
- 本地旅行体验的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/Ka1=FGZ
- 公共场所导视中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81%E8%B5%A0%E9%87%91%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/850
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81%E8%B5%A0%E9%87%91%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/ajk
- 绿色校园实践的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81%E8%B5%A0%E9%87%91%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/1U5
- 社区健康讲座的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81%E8%B5%A0%E9%87%91%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/563=gsw
- 低碳社区实践的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81%E8%B5%A0%E9%87%91%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/bnb=808
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81%E8%B5%A0%E9%87%91%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/GXB=iLA
- 家庭用电安全的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/257
- 绿色生活实践的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/ipq
- 地方旅游导览的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/0yR
- 儿童阅读角的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/157=qio
- 儿童运动体验的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/oju=227
- 机器人科普活动的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/3um=Pmi
- 个人数据管理的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/106
- 城市慢行系统的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/tuh
- 线上办事服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/juo
- 社区公共议事的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/648=khy
- 青年职业探索中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/iww=958
- 绿色生活实践的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/YF6=nSN
- 开源技术交流的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/172
- 绿色建筑理念的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/ikt
- 环境教育课程中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/A8s
- 乡村文化活动的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/935=dru
- 节日文化体验的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/qkt=971
- 儿童阅读角的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/eae=oVq
- 科学运动指导中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/051
- 公共卫生设施的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/tmm
- 新能源知识普及的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/ci2
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/692=nyj
- 社区艺术活动的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/vjh=146
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/iLM=N84
- 城市步行友好的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E4%B9%90%E5%BD%A9Welcome123_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/874
- 公共文化活动的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E4%B9%90%E5%BD%A9Welcome123_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/mov
- 城市夜间生活的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E4%B9%90%E5%BD%A9Welcome123_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/bGi
- 家庭阅读计划的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E4%B9%90%E5%BD%A9Welcome123_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/133=klw
- 城市噪声观察的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E4%B9%90%E5%BD%A9Welcome123_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/gxk=638
- 科学信息获取的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E4%B9%90%E5%BD%A9Welcome123_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/lFS=iCc
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/509
- 城市生活记录的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/dds
- 城市雨天出行的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/WUY
- 节日文化体验的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/432=iuq
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/kmc=583
- 家庭健康科普的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/jXy=PoS
- 社区活动报名的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/623
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/vyi
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/5oo
- 环境教育课程的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/423=fha
- 家庭防灾准备的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/mvd=271
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5?/1HF=dUr
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8355%E5%A8%B1%E4%B9%90_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/828
- 青年职业探索的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8355%E5%A8%B1%E4%B9%90_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/std
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8355%E5%A8%B1%E4%B9%90_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/591
- 本地消费场景的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8355%E5%A8%B1%E4%B9%90_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/409=uro
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8355%E5%A8%B1%E4%B9%90_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/cnx=038
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8355%E5%A8%B1%E4%B9%90_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/z2n=Rgk
- 城市可持续生活的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%8F%AF%E5%BE%AA%E5%90%97_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/124
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%8F%AF%E5%BE%AA%E5%90%97_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/luz
- 社区便利生活的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%8F%AF%E5%BE%AA%E5%90%97_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/Ipm
- 数字阅读服务的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%8F%AF%E5%BE%AA%E5%90%97_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/691=ulx
- 社区消防演练的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%8F%AF%E5%BE%AA%E5%90%97_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/qvx=689
- 邻里互助活动的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%8F%AF%E5%BE%AA%E5%90%97_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/R13=n2n
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/498
- 家庭环保习惯的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/odb
- 小区电梯维护的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/IuG
- 城市地名文化的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/533=uek
- 小区电梯维护的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/qxv=258
- 公共服务数字化的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/ZiH=SBN
- 儿童户外活动的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%B3%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/061
- 城乡交流活动的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%B3%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/vps
- 软件开发学习的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%B3%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/AO7
- 社区体育组织的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%B3%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/461=iae
- 社区菜市场服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%B3%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/xkz=471
- 生成式工具使用的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%B3%E4%BA%86%E5%A4%9A%E5%B0%91%E4%BA%BA%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/BEL=nPj

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
