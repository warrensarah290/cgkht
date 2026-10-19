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

- 城市博物馆活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/766
- 口袋公园建设的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/urr
- 地方民俗记录的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/WDF
- 公共服务指南的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/075=ouw
- 城市噪声观察的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/vjp=643
- 口袋公园建设的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/I7p=emp
- 公共交通接驳的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/581
- 数字地图应用的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/wdl
- 安全出行教育的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/Rg6
- 城市可持续生活的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/655=zwv
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/xbz=552
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/RZF=4hN
- 社区停车服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/138
- 老年人日常照护的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/uii
- 家庭网络使用的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/U7N
- 公共场馆服务的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/151=hja
- 数字创意课程的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/onr=550
- 旧物循环利用的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/x9o=oqs
- 城市地名文化的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/161
- 市民热线服务的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/qjq
- 智慧城市体验的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/LWO
- 光伏知识科普的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/352=sjh
- 城市文明出行的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/siv=094
- 急救知识普及的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/WA2=Zqi
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/713
- 基层服务创新的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/irk
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jgT
- 城市便民驿站的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/600=dlg
- 社区安全巡查的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zan=267
- 公共服务评价的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/IoC=0BL
- 青年职业探索中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/590
- 公共空间安全的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/lxv
- 数字支付体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/Jko
- 科学观察活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/958=xyi
- 数字学习资源的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/ukk=149
- 乡村公共阅读的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/Z9I=TLJ
- 亲子科普活动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/309
- 青年职业探索的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/pdz
- 校园安全教育的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/Fzj
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/714=keh
- 城市可持续生活的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/xlp=159
- 数据分析入门中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/cBB=RPm
- 非遗体验活动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/813
- 全民健身活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/vit
- 生活技能分享的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/Vbs
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/887=dtm
- 街区小店体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/rom=910
- 节能生活方式的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/Kaz=M1v
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/584
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/jti
- 电动汽车充电的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/or2
- 城市文明出行的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/331=sim
- 绿色出行服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/jkg=498
- 科技馆参观体验的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/rkA=j0T
- 节日文化体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/785
- 社区快递服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/auw
- 公共文化活动的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/iLb
- 机器人科普活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/334=jxl
- 社区垃圾回收的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/mqd=116
- 农业科普体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/eXM=Qhe
- 职业技能学习的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/685
- 社区体育组织中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/wmy
- 公共服务预约的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/H21
- 家庭网络使用的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/505=csw
- 公益活动组织的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/kxw=890
- 课后服务体验的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%A0%E7%89%A9?/ygk=cgS
- 公共健身器材的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/523
- 数字生活课堂中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/wll
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/yJA
- 校园安全教育的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/900=ppk
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/uyn=216
- 人工智能科普的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/wrL=3Wr
- 社区便民集市的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/818
- 城市可持续生活的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/uxm
- 运动安全知识的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/L8E
- 家庭科学教育的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/142=mhj
- 家庭急救准备的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/iut=397
- 城市地名文化的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/MZ7=Rde
- 乡村文化活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/704
- 街区绿化养护中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/cdc
- 无障碍出行的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/rJ6
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/652=yrx
- 家庭养老规划的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/pis=448
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/Yth=MHz
- 社会体育指导的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/845
- 光伏知识科普的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/vef
- 城市噪声观察的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/8Ui
- 无障碍出行的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/230=upp
- 居民健康教育的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/ndh=501
- 垃圾分类指导的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/jIz=870
- 街区道路维护的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/596
- 社区宠物管理的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/itu
- 社区文化节活动的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/Mft
- 家庭科学教育的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/754=khf
- 城市地名文化的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/uxb=843
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/7KU=Omz
- 便民服务地图的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/840
- 智能手机助老的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/sbd
- 乡村公共文化的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/xXq
- 安全出行教育的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/161=mch
- 城市博物馆服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/joc=828
- 家庭健康管理的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/QuV=HhF
- 健康信息获取的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/035
- 社区教育资源的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/pcx
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/HB2
- 城市绿色交通的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/872=rfx
- 线上阅读资源的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/eci=426
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/Vkp=N2c
- 休闲运动入门的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/111
- 消防知识宣传的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/oep
- 城市空气科普的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/EOK
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/526=wdc
- 开放数据应用的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/pfb=034
- 节假日出行安排的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9F%E8%A7%88?/kvq=puQ
- 基层医疗预约的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/707
- 城市文明实践的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/edg
- 地方戏曲体验的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/5Ed
- 家庭环保习惯的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/679=vfi
- 软件开发学习的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/anw=907
- 户外活动组织的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/gHE=1Q8
- 社区科普课堂的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/531
- 医院导诊服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/iyp
- 公共空间照明的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/dqq
- 家庭消费规划的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/388=paf
- 城市博物馆活动的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/izl=817
- 老年人文化生活中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E6%97%B6%E6%8A%A5?/b7A=jwh
- 城市应急广播的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/024
- 医院导诊服务的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/nxo
- 绿色出行服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/sZs
- 文化场馆预约的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/655=suz
- 非遗课堂体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/kok=766
- 社区垃圾回收的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/qJE=v2Z
- 青年志愿活动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/969
- 气象科普传播的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/khx
- 科技馆参观体验的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ZQH
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/611=mrm
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/lrj=111
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/z63=Okh
- 邻里互助活动的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%B2%E5%9D%9B?/280
- 家庭志愿活动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%B2%E5%9D%9B?/iag
- 基层服务创新的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%B2%E5%9D%9B?/Xy8
- 青少年心理健康的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%B2%E5%9D%9B?/421=ipz
- 智能家居应用的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%B2%E5%9D%9B?/xyp=334
- 乡村生活观察中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%B2%E5%9D%9B?/I0B=zWM
- 绿色办公实践的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/225
- 家庭环保行动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/ugb
- 乡村公共服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/GwN
- 社区家政服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/977=hpm
- 居家适老化改造的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/kdt=247
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/ZAe=dPy
- 社区读书角建设的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/009
- 城市公共厕所中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/yfp
- 公共空间安全的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/5fT
- 科技馆参观体验的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/557=dwn
- 骑行路线规划的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/url=175
- 绿色快递包装的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/Y3C=EVT
- 城市应急科普的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/248
- 社区法律科普的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/pdn
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/zYm
- 社区休闲设施的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/663=pwe
- 公共服务预约的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/jny=650
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E8%88%86%E6%83%85?/WjM=eK5
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/009
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/sih
- 家庭养老规划的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/eqM
- 绿色生活实践中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/917=tqw
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/arq=929
- 数字学习资源的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/LWP=xM1
- 儿童运动体验的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/095
- 青年就业服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/bny
- 职业技能学习中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/zG0
- 电动汽车充电的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/638=spj
- 城市骑行环境的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/nqd=141
- 公园无障碍服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/sCc=L8R
- 租房信息服务的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/116
- 儿童运动体验的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/rrt
- 数字课堂应用的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/s7h
- 社区共享书架的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/489=fmr
- 邻里共享空间的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/jnc=457
- 周末休闲规划的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/UGG=gdd
- 老旧小区改造的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/586
- 社区读书角建设的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/dwh
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/xNs
- 小区电梯维护的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/002=csb
- 开放数据应用的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/xjo=212
- 数字档案服务的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/XWW=hvn
- 城市雨天出行中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/635
- 图书馆数字服务的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/lmb
- 城市公共艺术的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/Gd8
- 社区志愿服务的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/150=sls
- 地方美食文化的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/ala=672
- 社区便利生活的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%88%8A%E7%99%BB?/yGG=htQ
- 社区防暑服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/108
- 生活技能分享的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/gzu
- 城市展览体验的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/rRJ
- 开源技术交流的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/341=lsa
- 人工智能科普的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/vnk=148
- 社区停车服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/WwN=YGn
- 本地消费场景的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/551
- 全民阅读推广的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/yyi
- 社区商业活力的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/Nh6
- 绿色生活实践的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/422=vhl
- 乡村生活观察的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/khp=547
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/iLY=Rn9
- 城市运动公园的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/707
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/qam
- 休闲运动入门的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/DLt
- 公共交通接驳的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/810=dkx
- 老年学习活动的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/asv=421
- 社区快递服务的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/NSx=xfq
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/479
- 全民健身活动的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/hqt
- 儿童安全出行的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/bAB
- 节气饮食文化的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/145=shj
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/viv=501
- 便民信息查询的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/NH6=hZq
- 数字支付体验的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/544
- 家庭科学教育的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/ohc
- 城市应急科普的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/FTD
- 个人信息保护的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/671=epc
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/zsn=277
- 家庭志愿活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E6%95%B0%E8%AF%BB?/Dfe=w7V
- 社区邻里服务的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/636
- 数字公共文化的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/ege
- 城市基础设施的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/QfM
- 家庭网络使用的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/136=bzf
- 城市空气科普的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/mdr=894
- 社会体育指导的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/Ek0=E1T
- 健康饮水科普的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/605
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/zce
- 基层健康档案的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/wxD
- 城市基础设施的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/826=nhy
- 环境监测科普的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/ggn=838
- 科学健身方法的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/772=8cg
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/546
- 数字阅读服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/ndr
- 个人数据管理的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/qWA
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/946=hdw
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/tnq=617
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/dcI=5Eb
- 绿色校园实践的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/499
- 地方戏曲体验的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/emo
- 社区停车服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/WQT
- 便民服务地图的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/117=aue
- 社区法律科普的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/mgf=091
- 地方美食文化的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/udS=wlz
- 社区垃圾分类的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/778
- 乡村阅读活动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/zmm
- 社区健康讲座的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/un6
- 数字创意课程的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/508=gjj

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
