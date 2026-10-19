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

- 城市基础设施的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E5%9D%9A%E6%8C%81%E4%B8%89%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/nEL
- 小区公共照明的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E5%9D%9A%E6%8C%81%E4%B8%89%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/348=ktu
- 新能源出行的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E5%9D%9A%E6%8C%81%E4%B8%89%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/bfa=021
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E5%9D%9A%E6%8C%81%E4%B8%89%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/NzD=BVT
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/400
- 校园阅读活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/ett
- 数字素养提升的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/O1L
- 社区绿色空间从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/211=qif
- 软件开发学习的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/hjo=646
- 文化场馆预约的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/mZ7=vQZ
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/434
- 家庭环保习惯的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/nhn
- 数字创意课程的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/wIr
- 家庭健康管理的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/178=isj
- 儿童户外活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/ozz=471
- 公共服务数字化的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/ulX=L48
- 本地消费场景中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/012
- 基层健康服务的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/wkm
- 城乡公共服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/zNs
- 家庭健康科普的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/093=htb
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/fnk=415
- 社区文化节活动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/xhz=uOg
- 机器人科普活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/019
- 健康信息获取的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/mac
- 数字创意课程的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/3B7
- 软件开发学习的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/067=fce
- 社区设施共享的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/gsl=926
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/qB1=K5I
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/312
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/vrm
- 公共服务数字化的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/KSV
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/802=bct
- 基层健康档案的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/wve=929
- 科学运动指导的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E9%A1%BA%E4%B8%B0%E6%94%B6%E8%97%8F?/hDH=ZYz
- 公共服务数字化的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/825
- 数字地图应用的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/aoa
- 本地历史资料的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/aMW
- 周末休闲规划的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/723=mcu
- 社区文化传播的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/itr=236
- 校园安全教育的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/HVN=CRP
- 数字便民地图的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/280
- 公交站点体验的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/gjk
- 亲子科普活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/Tkn
- 青少年科普实践的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/190=zdt
- 旧物循环利用的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/pcd=140
- 劳动教育实践的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E6%8A%95%E8%B5%84?/xcl=mSB
- 公共服务评价的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/146
- 食品配送体验的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/svu
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/nQ9
- 公共场所导视的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/744=oma
- 公交无障碍服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/khs=821
- 运动安全知识的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E6%96%B0%E6%B5%AA%E8%AE%B2%E5%9D%9B?/wsG=ecl
- 城市步行环境的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/090
- 公共设施使用的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/ccc
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/ZNq
- 公共卫生设施的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/600=yod
- 安全出行教育的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/zuz=352
- 城市博物馆服务的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/4HS=0As
- 城市公共饮水中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/626
- 家庭安全提示的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/clv
- 数字创意课程的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/EGA
- 青少年编程学习的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/966=vaz
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/mog=348
- 生成式工具使用的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/wgi=7xV
- 乡村产业科普的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/563
- 个人时间管理的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/cwu
- 社区应急准备的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/fAK
- 绿色快递包装的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/378=wls
- 口袋公园建设的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/scc=618
- 城市噪声观察的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/Mmy=mbJ
- 公共服务评价的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/075
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/gga
- 乡村阅读空间的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/Pvc
- 社区协商议事的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/378=syj
- 老年数字阅读的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/yfi=078
- 社区生活指南的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/vik=C9l
- 青年志愿活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/909
- 开放数据应用的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/yef
- 节约用水实践的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/ArR
- 小微企业服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/062=kfc
- 乡村文化空间的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/aqs=244
- 社区体育组织的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/yyq=e0s
- 乡村公共服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/292
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/vmn
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/HME
- 城市树木认养的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/037=xlx
- 城市社区治理的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/nob=806
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/Eze=IAP
- 户外活动组织的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/970
- 读书会组织的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/weq
- 志愿者培训交流的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/8nf
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/705=ysr
- 公交站点体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/ghr=928
- 城市建设科普的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/OgC=7B8
- 就业技能培训的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/464
- 数字学习资源的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/krd
- 公共卫生宣传的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/I7g
- 青少年心理健康的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/211=fyp
- 网络安全教育的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/uvv=164
- 绿色建筑理念的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/RvC=X59
- 就业技能培训的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/750
- 软件开发学习的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/ask
- 数字支付体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/UCt
- 社区家政服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/637=wdk
- 城市博物馆服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/avg=803
- 农产品品牌传播的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/MeT=bAo
- 社区儿童活动的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/554
- 周末休闲规划的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/slq
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/O01
- 小区公共照明的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/935=hep
- 社区垃圾回收的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/tqt=130
- 便民维修服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%96%87%E6%91%98?/aPL=RPD
- 社区知识分享的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%8D%95%E5%8F%8C%E6%AF%94%E8%BE%83%E5%87%86_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/024
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%8D%95%E5%8F%8C%E6%AF%94%E8%BE%83%E5%87%86_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/nlj
- 地方文化传播的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%8D%95%E5%8F%8C%E6%AF%94%E8%BE%83%E5%87%86_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/GjK
- 社区家政服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%8D%95%E5%8F%8C%E6%AF%94%E8%BE%83%E5%87%86_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/038=kyq
- 绿色出行服务的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%8D%95%E5%8F%8C%E6%AF%94%E8%BE%83%E5%87%86_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/zwg=587
- 乡村公共文化的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%8D%95%E5%8F%8C%E6%AF%94%E8%BE%83%E5%87%86_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/LUI=mdk
- 城市应急科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/050
- 社区志愿服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/aeh
- 公共设施维护的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/GKV
- 社区托育服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/408=oyi
- 开放数据应用的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/ais=524
- 社区生活指南的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/gQc=RnM
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E4%B9%B0%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/377
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E4%B9%B0%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/kgh
- 青少年编程学习的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E4%B9%B0%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/4Ot
- 开放数据应用的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E4%B9%B0%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/768=pvu
- 读书会组织的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E4%B9%B0%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/gbt=220
- 公共设施使用的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E4%B9%B0%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/H7Z=syG
- 城市适老服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%8C%BA%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/937
- 数字阅读服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%8C%BA%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/cvr
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%8C%BA%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/lZ9
- 传统节日科普的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%8C%BA%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/766=ikw
- 农业科普体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%8C%BA%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/toc=748
- 社区商业活力中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%8C%BA%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/uOI=pkv
- 城市水环境观察的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%88%A4%E6%96%AD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/013
- 城市慢行系统的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%88%A4%E6%96%AD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/fde
- 社区绿色空间的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%88%A4%E6%96%AD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/mzp
- 城市应急科普的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%88%A4%E6%96%AD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/061=nru
- 文化讲座服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%88%A4%E6%96%AD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/vlr=638
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%88%A4%E6%96%AD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/Xvn=VJg
- 社区防暑服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E8%87%AA%E5%B7%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/593
- 地方美食文化的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E8%87%AA%E5%B7%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/coo
- 职业技能学习的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E8%87%AA%E5%B7%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/T3S
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E8%87%AA%E5%B7%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/263=kws
- 地方旅游导览的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E8%87%AA%E5%B7%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/otz=734
- 公共卫生宣传的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E8%87%AA%E5%B7%B1%E6%98%AF%E4%B8%8D%E6%98%AF%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%83%AD%E6%A6%9C?/lfO=oes
- 软件开发学习的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%B5%99%E6%B1%9F%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/337
- 儿童户外活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%B5%99%E6%B1%9F%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/ryu
- 公交站点体验的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%B5%99%E6%B1%9F%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/MrX
- 社区阅读服务的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%B5%99%E6%B1%9F%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/033=egz
- 光伏知识科普的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%B5%99%E6%B1%9F%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/mqj=753
- 城市文明实践中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%B5%99%E6%B1%9F%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/m4y=OI1
- 家庭消费规划的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99%E5%8F%8A%E5%A5%96%E9%87%91_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/511
- 地方民俗记录的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99%E5%8F%8A%E5%A5%96%E9%87%91_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/bnx
- 数字阅读服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99%E5%8F%8A%E5%A5%96%E9%87%91_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/cwA
- 科普展览体验的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99%E5%8F%8A%E5%A5%96%E9%87%91_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/337=kzo
- 基层医疗预约的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99%E5%8F%8A%E5%A5%96%E9%87%91_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/crj=229
- 文明养宠科普的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99%E5%8F%8A%E5%A5%96%E9%87%91_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/liR=9rK
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/333
- 个人时间管理的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/eue
- 无障碍出行的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/Vii
- 绿色办公实践的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/855=ahy
- 绿色出行服务的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/uib=772
- 科学信息获取的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%A3%E5%AF%86?/o8R=CLm
- 节能生活方式的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_welcome%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/400
- 社区设施共享的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_welcome%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/bzn
- 城市步行环境的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_welcome%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/SRA
- 社区宠物管理的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_welcome%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/347=vbh
- 绿色消费选择的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_welcome%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/axf=109
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_welcome%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/YNE=CuB
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%B9%E5%AF%B9%E8%83%A1%E7%89%8C%E5%9E%8B%E5%9B%BE%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/155
- 家庭节能实践的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%B9%E5%AF%B9%E8%83%A1%E7%89%8C%E5%9E%8B%E5%9B%BE%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/tar
- 文明养宠科普的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%B9%E5%AF%B9%E8%83%A1%E7%89%8C%E5%9E%8B%E5%9B%BE%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/V92
- 城乡公共服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%B9%E5%AF%B9%E8%83%A1%E7%89%8C%E5%9E%8B%E5%9B%BE%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/652=bcr
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%B9%E5%AF%B9%E8%83%A1%E7%89%8C%E5%9E%8B%E5%9B%BE%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/usp=227
- 创业经验分享的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%AF%B9%E5%AF%B9%E8%83%A1%E7%89%8C%E5%9E%8B%E5%9B%BE%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/nIE=2lL
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%AD%97%E4%B8%80%E8%89%B2%E7%89%8C%E5%9E%8B_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/008
- 亲子阅读活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%AD%97%E4%B8%80%E8%89%B2%E7%89%8C%E5%9E%8B_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/eky
- 城市文化路线的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%AD%97%E4%B8%80%E8%89%B2%E7%89%8C%E5%9E%8B_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/sLB
- 儿童友好街区的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%AD%97%E4%B8%80%E8%89%B2%E7%89%8C%E5%9E%8B_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/062=jud
- 城市空气科普的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%AD%97%E4%B8%80%E8%89%B2%E7%89%8C%E5%9E%8B_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/gbk=626
- 乡村教育资源的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%AD%97%E4%B8%80%E8%89%B2%E7%89%8C%E5%9E%8B_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/w3O=8xb
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/965
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/jrz
- 传统节日科普的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/zSJ
- 社区安全巡查的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/573=cep
- 地方旅游导览的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/vhm=323
- 城市农夫市集的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/TAv=rTN
- 网络信息辨识的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/697
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/xbx
- 小微企业服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/iNK
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/665=ifl
- 亲子阅读活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/qsi=937
- 城市噪声观察的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/e47=Yln
- 小微企业服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%8F%8C%E5%9B%A0%E7%B4%A0%E6%96%B9%E5%B7%AE%E5%88%86%E6%9E%90%E7%BB%93%E6%9E%9C%E8%A7%A3%E8%AF%BB_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/109
- 生活垃圾回收的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%8F%8C%E5%9B%A0%E7%B4%A0%E6%96%B9%E5%B7%AE%E5%88%86%E6%9E%90%E7%BB%93%E6%9E%9C%E8%A7%A3%E8%AF%BB_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/gjv
- 休闲运动入门的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%8F%8C%E5%9B%A0%E7%B4%A0%E6%96%B9%E5%B7%AE%E5%88%86%E6%9E%90%E7%BB%93%E6%9E%9C%E8%A7%A3%E8%AF%BB_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/qMH
- 城市展览体验的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%8F%8C%E5%9B%A0%E7%B4%A0%E6%96%B9%E5%B7%AE%E5%88%86%E6%9E%90%E7%BB%93%E6%9E%9C%E8%A7%A3%E8%AF%BB_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/056=iug
- 消防知识宣传的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%8F%8C%E5%9B%A0%E7%B4%A0%E6%96%B9%E5%B7%AE%E5%88%86%E6%9E%90%E7%BB%93%E6%9E%9C%E8%A7%A3%E8%AF%BB_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/nqm=189
- 家庭健康管理的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%8F%8C%E5%9B%A0%E7%B4%A0%E6%96%B9%E5%B7%AE%E5%88%86%E6%9E%90%E7%BB%93%E6%9E%9C%E8%A7%A3%E8%AF%BB_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/CBZ=4Wf
- 本地历史资料的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E7%8E%87%E9%AB%98_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/035
- 数字政务体验中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E7%8E%87%E9%AB%98_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/uvg
- 城市空气科普的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E7%8E%87%E9%AB%98_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/GOU
- 社区环保活动的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E7%8E%87%E9%AB%98_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/754=lke
- 城市生活记录的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E7%8E%87%E9%AB%98_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/mzk=967
- 节日文化体验的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E7%8E%87%E9%AB%98_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/amy=kaI
- 街区小店体验的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/921
- 科学运动指导的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/qhv
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/r4Z
- 在线教育体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/125=zrz
- 开源技术交流的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/qgu=996
- 城市展览体验的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/y08=QbQ
- 城市绿色交通的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB8%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/743
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB8%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/owf
- 数字设备回收的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB8%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/uqh
- 社区家校合作的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB8%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/491=hwn
- 数字地图应用的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB8%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/tlj=439
- 公共空间安全的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB8%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/Pli=jOv
- 数字资源检索中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/303
- 旧物循环利用的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/jgm
- 口袋公园建设的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/krU
- 城市绿道建设的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/441=tji
- 社区读书角建设的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/vvc=988
- 终身学习资源的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BD%9C%E5%BC%8A_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/lV0=Hga
- 儿童户外活动的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%89%93%E6%B3%95_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/673
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%89%93%E6%B3%95_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/wop
- 社区家校合作的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%89%93%E6%B3%95_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/5yH
- 公共空间安全的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%89%93%E6%B3%95_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/993=jpp
- 家庭饮食安排的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%89%93%E6%B3%95_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/tyw=080
- 科学运动指导的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%89%93%E6%B3%95_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/iet=GFv
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/523
- 职业技能学习的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/bza
- 城乡交通衔接的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/un5
- 灵活就业交流的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/383=szn
- 机器学习入门的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/arq=359
- 老年友好服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/6dV=q3T
- 公园休闲体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/620
- 消防知识宣传的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/nuu
- 城市公共标识的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/syA
- 青少年科普实践的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/925=ntj
- 读书会组织的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/nmi=616
- 校园安全教育的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/ZsQ=Od1
- 户外活动组织的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/150
- 城市生活记录的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/jur
- 在线学习体验的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/Qk7
- 公园亲子设施的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/051=nyz
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/toj=846
- 公共空间照明的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/PIH=cUt

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
