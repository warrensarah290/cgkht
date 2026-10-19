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

- 儿童友好街区的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB35%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%AA%97%E5%B1%80%E8%BF%87%E7%A8%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/jgi=108
- 节假日出行安排的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB35%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%AA%97%E5%B1%80%E8%BF%87%E7%A8%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/PpC=4K1
- 小微企业服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_360%E6%B8%B8%E6%88%8F?/129
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_360%E6%B8%B8%E6%88%8F?/ipj
- 城市体育设施的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_360%E6%B8%B8%E6%88%8F?/Jw0
- 本地历史资料的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_360%E6%B8%B8%E6%88%8F?/243=lxz
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_360%E6%B8%B8%E6%88%8F?/rio=678
- 机器学习入门的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E5%A4%A7%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_360%E6%B8%B8%E6%88%8F?/sFN=Klx
- 数字创意课程的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/669
- 创业经验分享的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/jti
- 儿童安全出行的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/Heo
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/628=zgc
- 口袋公园建设的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/jwv=851
- 公共文化活动的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%874%E6%88%90%E5%BF%85%E8%83%9C%E7%BC%86_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/hBI=k13
- 在线学习体验中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/530
- 社区活动空间的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/gro
- 乡村公共服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/D1W
- 家庭园艺实践的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/616=atp
- 老年人文化生活的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/dgf=940
- 城乡交流活动的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E9%AB%98%E6%89%93%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/wHk=ZxA
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/519
- 科技馆参观体验的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/evi
- 绿色快递包装的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/pAA
- 城乡交通衔接的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/826=usx
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/fcn=911
- 农产品消费体验的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%83%9C%E7%8E%87%E6%9C%80%E9%AB%98_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/gux=hiX
- 街区绿化养护的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/617
- 生活垃圾回收的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/bat
- 城市雨天出行的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/cDM
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/075=kfi
- 社区养老服务的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/fwh=883
- 软件开发学习的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/gIM=u4O
- 儿童友好空间的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/238
- 城乡交流活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/xwg
- 地方旅游导览的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/roL
- 社区安全巡查的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/000=vtw
- 便民服务地图的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/xol=479
- 智能手机助老的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/jVF=CVg
- 基层服务创新的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/035
- 家庭用电安全的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/owk
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/EYJ
- 家庭食品保存的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/582=lzd
- 社区应急准备的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/uuw=805
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%83%9C%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/vDa=pd6
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/494
- 社区运动空间的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/kfu
- 家庭节能实践的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/DZ6
- 农产品品牌传播的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/620=skz
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/bgn=619
- 线上办事服务的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E4%B9%B0%E5%B0%B1%E8%BE%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/VkO=vbr
- 骑行路线规划的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/128
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/eta
- 社区健康讲座的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/dwD
- 旧物循环利用的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/795=hhn
- 消防知识宣传的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/ccj=681
- 城市住房服务中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%93%AA%E4%B8%AA%E6%A6%82%E7%8E%87%E9%AB%98_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/twu=Xza
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/204
- 公共场所导视的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/lty
- 老年友好服务的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/Ueb
- 智慧停车服务的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/206=snj
- 城市公共艺术的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/zzo=264
- 城市夜间生活的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/aMo=xAp
- 社区快递服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/385
- 数字创作工具的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/dvh
- 电子商务服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/vwI
- 社区共享书架的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/832=pyl
- 家庭园艺实践的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/vwm=636
- 文化讲座服务的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E8%BF%B0%E8%AF%84?/mOV=AWP
- 社区公共卫生的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/458
- 青年职业探索的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/ivu
- 学校食育活动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/SyY
- 全民阅读推广的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/207=cvw
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/qkp=495
- 环境监测科普的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E6%80%8E%E6%A0%B7%E7%94%A8%E6%A6%82%E7%8E%87%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/v8W=3Bx
- 数字创作工具的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/358
- 社区养老服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/aoe
- 城乡交流活动的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/uJa
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/141=hqh
- 亲子科普活动中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/ivc=232
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E8%83%9C%E7%8E%87_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/fiz=60B
- 个人数据管理的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/480
- 数字课堂应用的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/tpg
- 智慧城市体验的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/Gu4
- 城市绿色交通的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/834=zah
- 儿童运动体验的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/nep=730
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/Amm=IcW
- 城市运动公园的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/496
- 智能手机助老的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/fwz
- 社区文化节活动的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/jRJ
- 乡村教育资源的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/215=xch
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/yaq=477
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/of5=qbI
- 公共服务沟通的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/346
- 新能源知识普及的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/knl
- 健康步道使用的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/L0f
- 基层服务创新的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/674=dmv
- 个人信息保护的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/wsl=422
- 便民维修服务的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/ekP=t3I
- 社区艺术活动的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/314
- 城市基础设施的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/zsv
- 街区道路维护的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/oVW
- 城市文明出行的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/228=shq
- 数字创意课程的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/jux=431
- 本地旅行体验的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/kBE=sPg
- 食品配送体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/614
- 生活垃圾减量的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/rah
- 社区环保活动的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/ERT
- 城市体育设施的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/938=qgq
- 读书会组织从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/ytl=357
- 数字地图应用的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/EFH=hJh
- 街道综合服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/203
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/mgg
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/Dj7
- 消防知识宣传的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/798=exz
- 日常摄影记录的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/pyc=428
- 社区邻里服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/EbT=geN
- 公共服务数字化的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/029
- 城市农夫市集的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/huj
- 公共空间休憩的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/prI
- 城市农夫市集的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/914=osq
- 数字阅读服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/vqi=750
- 口袋公园建设的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/1IE=LIR
- 线上阅读资源的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/776
- 乡村文化空间的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/bza
- 社区活动策划的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/r8l
- 食品配送体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/497=ajk
- 城市体育设施的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/osj=944
- 个人时间管理的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/eEZ=mnh
- 社区快递服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/692
- 基层健康档案的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/imi
- 农村环境治理的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/UCA
- 城市地名文化的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/232=fsc
- 无障碍出行的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/slk=821
- 儿童运动体验的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AF%E9%9D%A0%E5%90%97_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/j8z=NHq
- 绿色办公实践的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A0%B4%E8%A7%A3%E5%99%A8%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/902
- 社区读书角建设的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A0%B4%E8%A7%A3%E5%99%A8%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/xti
- 社区文化节活动的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A0%B4%E8%A7%A3%E5%99%A8%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/nTi
- 人工智能科普的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A0%B4%E8%A7%A3%E5%99%A8%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/849=hci
- 个人数据管理的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A0%B4%E8%A7%A3%E5%99%A8%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/jvb=510
- 安全出行教育的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A0%B4%E8%A7%A3%E5%99%A8%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/WeR=Spw
- 社区安全巡查的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%BC%8F%E6%B4%9E_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/276
- 社区安全巡查的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%BC%8F%E6%B4%9E_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/qmo
- 乡村教育资源的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%BC%8F%E6%B4%9E_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/5mp
- 社区家校合作的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%BC%8F%E6%B4%9E_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/669=gfk
- 社区宠物管理的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%BC%8F%E6%B4%9E_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/mad=882
- 农村环境治理的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%BC%8F%E6%B4%9E_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/gdv=agj
- 生活技能分享的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E8%A7%84%E5%BE%8B%E5%87%86%E7%A1%AE%E7%8E%87_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/120
- 青年就业服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E8%A7%84%E5%BE%8B%E5%87%86%E7%A1%AE%E7%8E%87_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/lho
- 城市应急广播的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E8%A7%84%E5%BE%8B%E5%87%86%E7%A1%AE%E7%8E%87_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/4aR
- 乡村公共服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E8%A7%84%E5%BE%8B%E5%87%86%E7%A1%AE%E7%8E%87_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/435=qli
- 校园社团活动的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E8%A7%84%E5%BE%8B%E5%87%86%E7%A1%AE%E7%8E%87_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/xbz=077
- 老年人日常照护的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E8%A7%84%E5%BE%8B%E5%87%86%E7%A1%AE%E7%8E%87_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/c8L=2vK
- 绿色校园实践的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/000
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/caa
- 乡村电商实践中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/JHU
- 城市水环境观察的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/168=rwy
- 生成式工具使用的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/nek=467
- 街区道路维护的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/czt=K3r
- 城市基础设施的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/377
- 家庭志愿活动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/wfg
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/BTD
- 公园休闲体验的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/088=eet
- 图书馆数字服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/nto=888
- 社区消防演练的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/ApU=vXm
- 非遗课堂体验的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/440
- 社区知识分享的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/sys
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/jcP
- 城乡公共服务的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/167=ejk
- 非遗体验活动的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/aoz=577
- 公共卫生宣传的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/y2V=pnH
- 乡村阅读空间的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/261
- 社区公共卫生的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/wcm
- 家庭健康管理的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/LV3
- 社区邻里服务的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/886=kzo
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/kpv=672
- 安全出行教育的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E7%A7%81%E5%8B%9F?/mwN=JyB
- 社区生活指南的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%83%BD%E6%BA%90?/277
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%83%BD%E6%BA%90?/jkt
- 地方美食文化的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%83%BD%E6%BA%90?/Ed3
- 健康步道使用的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%83%BD%E6%BA%90?/567=mhe
- 便民服务窗口的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%83%BD%E6%BA%90?/tuk=997
- 低碳社区实践的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%83%BD%E6%BA%90?/uXs=tv1
- 社区读书角建设的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/024
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/qoy
- 节约用水实践的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/mTY
- 急救知识普及的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/963=ctz
- 社区活动报名的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/cqk=580
- 绿色校园实践的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/xFN=Dt4
- 社区科普课堂的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E8%A1%A8%E6%A0%BC_360%E8%B5%84%E8%AE%AF?/404
- 学校体育活动的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E8%A1%A8%E6%A0%BC_360%E8%B5%84%E8%AE%AF?/owg
- 应急物资管理的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E8%A1%A8%E6%A0%BC_360%E8%B5%84%E8%AE%AF?/ZAp
- 公益活动组织的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E8%A1%A8%E6%A0%BC_360%E8%B5%84%E8%AE%AF?/665=koy
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E8%A1%A8%E6%A0%BC_360%E8%B5%84%E8%AE%AF?/ome=661
- 数字政务体验的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E8%A1%A8%E6%A0%BC_360%E8%B5%84%E8%AE%AF?/69y=WR1
- 图书馆活动策划的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E6%A6%82%E7%8E%87%E5%AD%A6_360%E7%9E%AD%E6%9C%9B?/854
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E6%A6%82%E7%8E%87%E5%AD%A6_360%E7%9E%AD%E6%9C%9B?/wtz
- 职业技能学习的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E6%A6%82%E7%8E%87%E5%AD%A6_360%E7%9E%AD%E6%9C%9B?/Qhe
- 家庭用电安全的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E6%A6%82%E7%8E%87%E5%AD%A6_360%E7%9E%AD%E6%9C%9B?/140=vaw
- 社区手工活动中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E6%A6%82%E7%8E%87%E5%AD%A6_360%E7%9E%AD%E6%9C%9B?/nvf=653
- 物业服务沟通的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E6%A6%82%E7%8E%87%E5%AD%A6_360%E7%9E%AD%E6%9C%9B?/FF0=O1r
- 社区家校合作中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/060
- 医院导诊服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/tte
- 城市文化路线的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/fPw
- 食品安全科普的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/901=jxv
- 城市绿道建设的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/tcb=530
- 家庭阅读计划的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/pcI=iMx
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E7%AE%97%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/200
- 药品使用科普的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E7%AE%97%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/zek
- 社区修缮行动的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E7%AE%97%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/05k
- 公共图书馆服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E7%AE%97%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/801=wgx
- 社区商业活力的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E7%AE%97%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/drf=441
- 城市共享单车的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E7%AE%97%E6%B3%95_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/G04=edG
- 社区垃圾回收的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E5%AD%A6_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/716
- 急救知识普及的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E5%AD%A6_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/vxq
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E5%AD%A6_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/tsf
- 科学健身方法的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E5%AD%A6_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/887=vof
- 节能家电使用的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E5%AD%A6_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/mvc=816
- 公园休闲体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E5%AD%A6_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/n63=xeL
- 本地消费场景的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%99%8E%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/616
- 物业服务沟通的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%99%8E%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/dwp
- 志愿者培训交流的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%99%8E%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/Dhl
- 城市生活服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%99%8E%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/102=lll
- 家庭养老规划的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%99%8E%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/rpx=837
- 地方民俗记录的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%99%8E%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/2DL=ujK
- 公共空间照明的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E7%9A%84%E5%85%AC%E5%BC%8F%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/165
- 城市休闲步道的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E7%9A%84%E5%85%AC%E5%BC%8F%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/lhc
- 社区教育资源的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E7%9A%84%E5%85%AC%E5%BC%8F%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/IgF
- 在线教育体验的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E7%9A%84%E5%85%AC%E5%BC%8F%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/471=ywe
- 课后服务体验的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E7%9A%84%E5%85%AC%E5%BC%8F%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/rho=184
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%A2%E7%9A%84%E5%85%AC%E5%BC%8F%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/dMG=GNd
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_49%E7%A0%81%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B100%25%E5%87%862018_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/799
- 儿童户外活动的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_49%E7%A0%81%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B100%25%E5%87%862018_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/zbl
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_49%E7%A0%81%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B100%25%E5%87%862018_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/haY
- 儿童安全出行的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_49%E7%A0%81%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B100%25%E5%87%862018_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/502=tgo
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_49%E7%A0%81%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B100%25%E5%87%862018_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/ulk=141
- 居家适老化改造的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_49%E7%A0%81%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B100%25%E5%87%862018_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/Gsb=pcZ
- 社区商业活力的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E9%97%A8%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/186
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E9%97%A8%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/xqf
- 公共服务评价的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E9%97%A8%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/CTH
- 社区邻里服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E9%97%A8%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/912=hii
- 家庭网络使用的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E9%97%A8%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/xrx=725
- 城市博物馆服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E9%97%A8%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/LVt=r8E
- 校园节能行动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/281
- 公共服务指南的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/nlo
- 邻里共享空间的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/YOG
- 老年数字阅读的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/856=ueh
- 健康信息获取的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/kpu=564
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/Kr9=3aZ
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_1%E5%88%86%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/212
- 社区知识分享的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_1%E5%88%86%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E4%BA%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/wtw

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
