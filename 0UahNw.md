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

- 创业经验分享的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/286
- 文化讲座服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/hmb
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/vRq
- 社区便民集市的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/858=vjq
- 城市步行环境的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/lsy=413
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E5%A4%B4%E6%9D%A1%E5%86%9B%E4%BA%8B?/hfo=Zc7
- 数字生活课堂的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/976
- 家庭阅读计划的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/soo
- 乡村生态观察的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/8Z1
- 家庭安全提示的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/287=hgh
- 社区活动空间的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/hsp=540
- 青少年户外教育的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/mGx=j5w
- 社区托育服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/056
- 社区老年食堂的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/oti
- 节日文化体验的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/jTZ
- 农产品消费体验的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/690=ucr
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/twv=025
- 社区科普课堂的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/4Ki=LVP
- 科学健身方法的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/563
- 城市步行友好的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/gsu
- 本地消费场景的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/K21
- 城市公共空间的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/039=ben
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/fmv=427
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/u9X=jau
- 便民信息查询的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/470
- 社区安全巡查的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/vun
- 老年智能设备的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/iRK
- 节气饮食文化的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/188=ose
- 租房信息服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/bxk=736
- 家庭消费规划的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/0Ue=ZHW
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/833
- 城市骑行环境的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/gsu
- 社区停车服务的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/VDi
- 社区心理支持的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/151=ipz
- 志愿服务平台的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/wyt=582
- 地方文化传播的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/Ua6=S4l
- 城市地名文化中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/769
- 市民意见收集的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/kkf
- 城市展览体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/TU4
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/754=phz
- 在线学习体验的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/ajl=024
- 家庭节能设备的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/JuA=9NR
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/283
- 儿童运动体验的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/cur
- 图书借阅体验的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/iE5
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/103=wkr
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/bsh=282
- 城市可持续生活的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/gh9=I52
- 通勤路线规划的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/771
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/iqe
- 光伏知识科普的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/Dd7
- 通勤路线规划的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/667=pqk
- 本地历史资料的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/pvf=404
- 城市可持续生活的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E6%95%99%E8%82%B2?/A5k=8mC
- 公共服务数字化的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/713
- 数字设备回收的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/rpg
- 老旧小区改造的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/W4p
- 乡村产业科普的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/754=eqi
- 地方旅游导览的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/dde=765
- 便民维修服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/2i8=sR9
- 科学观察活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/223
- 生成式工具使用的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/cav
- 社区环保活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/VHn
- 公共空间休憩的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/733=mdy
- 创业经验分享的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/jka=286
- 公共设施使用的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/Tf0=Pp7
- 信息无障碍体验的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/933
- 城市应急科普的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/hnr
- 家庭科学教育的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/Nh1
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/637=crx
- 公共卫生宣传的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/uhb=224
- 家庭急救准备的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/5U0=AJx
- 城市建设科普的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/263
- 食品配送体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/biv
- 在线学习体验的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/kJO
- 数字创意课程的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/432=iwn
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/dnv=354
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/B68=341
- 生活技能分享的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/406
- 社区艺术活动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/lgd
- 家庭消费规划的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/lbi
- 公共空间安全的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/921=yah
- 生活服务数字化的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/izo=348
- 城市水环境观察的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/tPF=qwm
- 数字课堂应用的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/056
- 城市农夫市集的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/wug
- 社区共享书架的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/ORh
- 社会体育指导的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/846=qpz
- 本地旅行体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/fuv=558
- 地方民俗记录的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/nd1=eur
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/266
- 社区托育服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/leq
- 社区文化节活动的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/bsj
- 邻里互助活动的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/575=qeh
- 城市体育设施的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/iou=444
- 亲子阅读活动的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/ovf=7ci
- 家庭健康管理的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/272
- 绿色出行服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/jop
- 数字支付体验的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/F67
- 社区故事采集的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/471=krz
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/pcl=273
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/lyI=3AN
- 城市运动公园的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E6%85%A7%E7%9C%BC?/908
- 公交站点体验的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E6%85%A7%E7%9C%BC?/vam
- 校园社团活动的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E6%85%A7%E7%9C%BC?/QAd
- 公共空间安全的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E6%85%A7%E7%9C%BC?/354=lhi
- 在线教育体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E6%85%A7%E7%9C%BC?/tvm=177
- 生活服务数字化的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E6%85%A7%E7%9C%BC?/rRC=0WS
- 青少年心理健康的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/031
- 绿色生活实践的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/awg
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/iVU
- 公共空间导览的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/089=ary
- 家庭节能设备的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/vdy=003
- 儿童友好街区的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/8Vn=KAC
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/843
- 口袋公园建设的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/ybt
- 家庭网络使用的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/hOe
- 城市游园体验的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/461=oqx
- 绿色校园实践的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/zja=800
- 小区公共照明的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/Oxn=WdR
- 社区应急准备的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/570
- 家庭健康科普的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/yhr
- 城市公共饮水的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/gvk
- 亲子科普活动的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/748=mmm
- 家庭节能设备的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/qre=879
- 老年学习活动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/t8A=osB
- 电动汽车充电中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/790
- 基层健康档案的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/utc
- 家庭健康科普的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/YJd
- 图书馆活动策划的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/434=zls
- 口袋公园建设的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/mpp=409
- 城市噪声观察的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/9Rp=xYj
- 社区科普课堂的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/535
- 城市树木认养的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/fob
- 城市公共艺术中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/1ky
- 乡村公共服务的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/511=xue
- 校园社团活动的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/qqz=527
- 城乡交通衔接的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/suO=1WT
- 地方文化传播的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/882
- 就业技能培训的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/tlw
- 节约用水实践的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/uLJ
- 城市基础设施的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/773=nvw
- 终身学习资源的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/kth=515
- 城市绿道建设的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/yZH=nHz
- 非遗课堂体验的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/840
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/ryh
- 全民健身活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/YFO
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/446=fnp
- 读书会组织的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/uuh=455
- 城市公共座椅的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/K7X=iii
- 城市公共饮水的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/715
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/bmu
- 安全出行教育的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/CNq
- 科技馆参观体验的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/433=mox
- 城市公共厕所的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/hnv=341
- 家庭节能设备的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/gom=xmp
- 在线学习体验的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/382
- 绿色生活实践的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/bcj
- 乡村公共服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/QyW
- 公共设施维护的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/945=spy
- 便民信息查询的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/foi=826
- 社区体育组织的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/VSn=QhL
- 老年数字阅读的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/750
- 环境监测科普的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/xrr
- 老年人日常照护的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/lIC
- 环境监测科普的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/503=dtu
- 市民意见收集的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/bok=305
- 城市文化路线的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/BBL=lVk
- 城市应急科普的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/696
- 本地旅行体验的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/ann
- 智慧停车服务的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/5nw
- 社区文化节活动的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/551=odc
- 社区读书角建设的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/jje=299
- 科学观察活动的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/rm1=QIU
- 科学信息获取的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/152
- 在线学习体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/azs
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/dc6
- 地方美食文化的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/210=ukb
- 家庭安全提示的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/twy=753
- 城市运动公园的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/iEO=TSH
- 城市运动公园的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/750
- 老年人文化生活的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/atp
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/uFx
- 户外活动组织的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/263=uar
- 社区养老服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/oya=703
- 非遗体验活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%A1%A3%E6%A1%88?/nKa=7Qp
- 学校食育活动的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/290
- 文明养宠科普的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/tlk
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/zNi
- 社区法律科普的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/458=knl
- 本地消费场景的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/dlp=113
- 青年志愿活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/W37=QP7
- 网络信息辨识的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_2023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/303
- 传统节日科普的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_2023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/gga
- 数字资源检索的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_2023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/6bN
- 图书借阅体验的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_2023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/080=whn
- 数字艺术创作的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_2023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/ksg=611
- 创业经验分享的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_2023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/gh0=9UU
- 药品使用科普的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/918
- 城市文明实践的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/avo
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/eah
- 应急物资管理的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/610=oda
- 公园无障碍服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/wdt=127
- 家庭节能实践的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/0IV=gYp
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/841
- 数字公共文化的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/jdu
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/KI4
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/403=nnq
- 乡村生活观察的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/jxg=367
- 节能生活方式的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AE%AF?/GaL=CHV
- 居家适老化改造的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/392
- 校园社团活动的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/mdq
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/J9S
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/768=ioz
- 便民服务地图的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/mnv=793
- 公共空间安全的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/jvf=j3y
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/766
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/znq
- 社区体育组织的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/txx
- 家庭志愿活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/639=pep
- 基层服务创新的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/cbz=968
- 校园节能行动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E6%A6%9C%E5%8D%95?/TKm=2lj
- 城市水环境观察的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/575
- 城市体育设施的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/kxt
- 非遗体验活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/ZGl
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/577=ohj
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/pyn=776
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/IFC=TUB
- 社区手工活动的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/823
- 城市文明实践的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/cjy
- 读书会组织的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/A6F
- 无障碍出行的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/624=lvg
- 家庭饮食安排的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/hms=987
- 家庭健康管理的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/AwU=jU1
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/335
- 物业服务沟通的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/rtx
- 乡村公共文化的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/VKx
- 公园亲子设施的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/396=xpy
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/xnr=001
- 老年人出行服务的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/ohX=UbV
- 公共服务评价的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/069
- 城市公共座椅的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/znc
- 家庭网络使用中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/7w3
- 运动安全知识的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/102=kmw
- 本地旅行体验的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/lxw=993
- 家庭急救准备的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/y4H=Tni
- 公共场所导视的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/473
- 小区停车协商的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/fbq
- 城市适老服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/Pfs
- 数字创意课程的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/524=hvj

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
