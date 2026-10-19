# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 城市农夫市集的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/iBn
- 社区科普课堂的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/372=mye
- 网络安全教育的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/whf=166
- 社区故事采集的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E4%BC%98%E9%85%B7%E5%8F%B8%E6%B3%95?/QAq=YIi
- 绿色校园实践的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/102
- 家庭节能实践的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/xtc
- 社区读书角建设的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/Lgi
- 全民健身活动的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/517=vcm
- 校园安全教育的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/dkg=957
- 公共服务指南的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/14q=UFD
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%AD%96%E7%95%A5%E8%B4%A2%E7%BB%8F?/640
- 家庭养老规划的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%AD%96%E7%95%A5%E8%B4%A2%E7%BB%8F?/zfc
- 乡村生态旅游的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%AD%96%E7%95%A5%E8%B4%A2%E7%BB%8F?/7p1
- 社区运动空间的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%AD%96%E7%95%A5%E8%B4%A2%E7%BB%8F?/513=nag
- 家庭科学教育的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%AD%96%E7%95%A5%E8%B4%A2%E7%BB%8F?/cgt=712
- 数字生活课堂的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%AD%96%E7%95%A5%E8%B4%A2%E7%BB%8F?/AtD=OFC
- 基层服务创新的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/222
- 城市可持续生活的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/mbm
- 在线学习体验的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/kkV
- 公共空间导览的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/681=trw
- 在线教育体验的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/szr=165
- 社区商业活力的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_9%E4%BA%BF%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/kpb=cZE
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/079
- 城市步行友好的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/wve
- 非遗体验活动的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/75c
- 社区家校合作的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/542=lcs
- 城市农夫市集的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/rvb=474
- 公共图书馆服务的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/cql=7Bz
- 社区健康讲座的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/085
- 家庭安全提示的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/wde
- 城市噪声观察的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/tua
- 市民热线服务的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/622=bwm
- 社区应急准备的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/okp=880
- 城市应急科普的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/uDd=PFv
- 家庭健康科普的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/609
- 城市运动公园的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/vgb
- 便民服务窗口的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/X9S
- 绿色消费选择的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/722=lhr
- 青少年心理健康的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/kzy=579
- 老年人文化生活的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/Tb1=m8l
- 城市夜间照明的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/910
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/hax
- 社区故事采集的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/qps
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/262=cua
- 儿童友好空间的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/gmt=913
- 个人数据管理的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/QPX=VpB
- 地方旅游导览的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%BA%94%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/893
- 传统手工艺体验的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%BA%94%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/uxv
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%BA%94%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/JIn
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%BA%94%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/019=akg
- 节能家电使用的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%BA%94%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/rin=017
- 家庭环保习惯的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%BA%94%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/Mpr=UNr
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/328
- 社区公共议事的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/pvb
- 学校食育活动的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/JyZ
- 学校食育活动的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/779=dum
- 光伏知识科普的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/qaz=079
- 本地历史资料的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/Ka6=gWu
- 科普展览体验的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/414
- 本地历史资料的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/cas
- 课后服务体验的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/DIv
- 老年运动活动的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/963=sfh
- 邻里互助活动的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/msm=345
- 城市便民驿站的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%85%A7%E7%9C%BC?/mf8=R21
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8ios%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/547
- 公共服务数字化的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8ios%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/tlx
- 城市适老服务的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8ios%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/AeA
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8ios%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/029=vcw
- 小区公共照明的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8ios%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/kfe=841
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8ios%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/jdO=47G
- 社区设施共享的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A85%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/864
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A85%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/gyo
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A85%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/PIs
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A85%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/801=bop
- 邻里共享空间的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A85%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/iub=694
- 周末休闲规划的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A85%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/RJD=J54
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/452
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ric
- 城乡交流活动的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/k2S
- 社区学习活动的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/605=qio
- 社区商业活力的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/epz=549
- 跨代沟通活动的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/QpA=NFm
- 社区健康讲座中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/018
- 家庭运动计划有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/xua
- 家庭志愿活动的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/j0r
- 儿童友好空间的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/562=whq
- 传统节日科普的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/dfy=953
- 市民意见收集的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/VIW=c5e
- 街头绿植养护的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/257
- 城市应急科普的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/gzo
- 科学健身方法的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/vc8
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/019=lax
- 社区知识分享的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/vln=652
- 智能手机助老的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/rNT=qcP
- 公交站点体验的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%89%80%E6%9C%8975%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/252
- 青少年科技社团的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%89%80%E6%9C%8975%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/aro
- 家庭健康管理的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%89%80%E6%9C%8975%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/zuG
- 老年学习活动的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%89%80%E6%9C%8975%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/942=bdq
- 智能家居应用中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%89%80%E6%9C%8975%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/xtq=065
- 邻里共享空间的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%89%80%E6%9C%8975%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/6Ib=owS
- 城市应急广播的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81955%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/724
- 数字便民地图的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81955%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/frk
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81955%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/zpn
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81955%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/259=fhs
- 志愿者培训交流的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81955%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/iyi=830
- 社区交通安全的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81955%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/IhJ=kB3
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/777
- 农业科普体验的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/cll
- 公共服务沟通的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/4Sv
- 智能手机助老的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/231=muk
- 线上办事服务的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/jcb=251
- 乡村文化活动的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/jOZ=68a
- 校园社团活动的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/064
- 公共服务指南的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/vgo
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/Nxg
- 便民服务地图的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/528=amu
- 社区共享书架的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/gzd=345
- 儿童友好空间的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/qB5=Scg
- 公共服务评价中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/723
- 志愿者培训交流的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/kml
- 社区教育资源的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/A5w
- 家庭运动计划的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/000=aan
- 农村环境治理的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/vpf=944
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/kRf=FeE
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/339
- 社区快递服务的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mzt
- 地方戏曲体验的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/YQs
- 家庭运动计划的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/624=lns
- 城市文明实践的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/vjs=655
- 公共服务沟通的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/QOD=jVF
- 节约用水实践的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/111
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/mbi
- 垃圾分类指导的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/XNP
- 传统手工艺体验的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/906=ahx
- 科学运动指导的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/cxg=961
- 节气饮食文化的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/QA1=F9Q
- 乡村文化活动的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/834
- 科技馆参观体验的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/ayw
- 智能家居应用的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/stT
- 城市步行环境的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/261=nap
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/opy=739
- 数字支付体验的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/kvX=1kE
- 乡村电商实践的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/126
- 街区小店体验的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/wnz
- 数字素养提升的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/6Ul
- 街区更新实践的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/903=ekx
- 绿色消费选择的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/fcd=509
- 城市步行友好的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%9F%B3%E4%B9%90?/bq9=H73
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/289
- 农产品消费体验从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/oig
- 社区休闲设施的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/s3n
- 城市社区治理的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/048=ihz
- 绿色出行服务的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/mla=799
- 城市微更新实践的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/kqn=JuY
- 社区活动报名的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/761
- 租房信息服务的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/qgl
- 网络安全教育的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/fjp
- 社区活动策划的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/028=ynk
- 社区停车服务的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/rhq=350
- 家庭健康管理的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/K3N=UoD
- 城市生活服务的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/969
- 绿色办公实践的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/ljf
- 社区应急准备的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/EDk
- 数字支付体验的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/611=vxi
- 老年人文化生活的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/sbf=728
- 日常摄影记录的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/uaR=PV7
- 城市骑行环境的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/570
- 公共交通信息服务的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/tsa
- 公共空间照明的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/1S3
- 城市公共艺术的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/800=cfp
- 便民服务地图的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/rfc=322
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/37T=MAg
- 学校体育活动的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/917
- 智慧停车服务的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/hal
- 家庭节能设备的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/tjm
- 城市雨天出行中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/679=iat
- 社区养老服务的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/nlh=165
- 青年就业服务的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/sJE=Z3L
- 公交站点体验的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/739
- 社区运动空间的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/kwz
- 骑行路线规划的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/OW8
- 城市步行友好的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/142=nul
- 城市文明出行的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/heu=960
- 城市骑行环境的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/0uP=7HK
- 地方民俗记录的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9C%80%E7%81%AB%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/677
- 公共设施维护的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9C%80%E7%81%AB%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/gum
- 绿色办公实践的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9C%80%E7%81%AB%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/cP8
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9C%80%E7%81%AB%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/343=lgk
- 数字政务体验的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9C%80%E7%81%AB%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/cuj=398
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9C%80%E7%81%AB%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/6Cb=pWx
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9C%80%E7%83%AD%E9%97%A8%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/390
- 城市地名文化的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9C%80%E7%83%AD%E9%97%A8%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/wga
- 乡村产业科普的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9C%80%E7%83%AD%E9%97%A8%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/B0R
- 居家防滑改造的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9C%80%E7%83%AD%E9%97%A8%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/277=pyb
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9C%80%E7%83%AD%E9%97%A8%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/aei=450
- 绿色校园实践的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%9C%80%E7%83%AD%E9%97%A8%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/hCi=zYk
- 城市可持续生活的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/432
- 科学健身方法的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/xbg
- 科技馆参观体验的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/ptz
- 社区便民服务的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/101=ksj
- 家庭阅读计划的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/wvy=118
- 急救知识普及的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/MbN=dD7
- 本地历史资料的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/804
- 社区邻里服务的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/lbm
- 社区公共卫生的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/lnF
- 家庭网络使用的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/938=aad
- 智能家居应用的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/rvi=342
- 学校食育活动的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/hdl=30Z
- 智慧城市体验的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8955%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/905
- 公共服务评价的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8955%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/avu
- 城市可持续生活的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8955%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/YZx
- 社区商业活力的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8955%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/558=rmu
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8955%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/uon=616
- 运动安全知识的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8955%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/jqA=cut
- 社区互助网络的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/708
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/czi
- 公共设施维护的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/WUW
- 校园社团活动的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/032=vlq
- 社区活动报名的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/ujw=192
- 便民服务地图的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/GVe=JTy
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B8%80%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/715
- 健康步道使用的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B8%80%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/ztq
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B8%80%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/5tb
- 消防知识宣传的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B8%80%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/681=hob
- 智慧停车服务的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B8%80%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/fgi=206
- 城市共享单车的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E4%B8%80%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/U3L=cMR
- 居民健康教育的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/561
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/hyd
- 小区停车协商的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/Ghi
- 数字课堂应用的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/786=rra
- 校园社团活动的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/zfp=150
- 城市文明实践的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_656%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/1z2=Kjv
- 城市空气科普的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/239
- 社区阅读服务的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/mjd
- 社区互助网络的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/V24
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/854=unk
- 社区体育组织的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/wnw=812
- 生成式工具使用的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/QDn=V2A
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%97%8B%E9%A3%8E%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/180
- 低碳社区实践的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%97%8B%E9%A3%8E%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/rzp
- 课后服务体验的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%97%8B%E9%A3%8E%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/UlS
- 个人数据管理的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%97%8B%E9%A3%8E%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/986=waj
- 公共服务评价的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%97%8B%E9%A3%8E%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/ypj=471
- 数字艺术创作的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%97%8B%E9%A3%8E%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/Bx0=ks6
- 公共场馆服务的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/530
- 机器人科普活动的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/ekj
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/fbH
- 地方民俗记录的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/570=ymz
- 城市展览体验的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/zeo=088
- 小微企业服务的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/rpB=qtO

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
