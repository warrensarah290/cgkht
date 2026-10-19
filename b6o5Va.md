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

- 公共空间导览的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/366
- 青少年科普实践的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/zlt
- 节假日出行安排的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/1py
- 全民健身活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/013=raf
- 城市水环境观察的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/yya=132
- 数字地图应用的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/xRp=jwP
- 公共服务咨询的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/781
- 开放数据应用的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/fox
- 居家防滑改造的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/kRf
- 社区休闲设施的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/296=ibz
- 街区道路维护的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/tsq=318
- 城市绿色交通的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E9%95%BF%E6%9C%9F%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/fZA=oG0
- 人工智能科普的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/320
- 社区老年食堂的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/glo
- 城市慢行系统的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/hm4
- 城乡交通衔接的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/828=hnl
- 城市公共座椅的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/roy=422
- 公园休闲体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E7%89%A9?/CH5=h8m
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/386
- 公园亲子设施的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/jpi
- 食品配送体验的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/oMi
- 数字资源检索的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/238=aml
- 社区文化节活动中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/vwa=504
- 家庭节能实践的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%BA%8F%E6%8D%9F%E5%8C%85%E8%B5%94_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/uPL=bgq
- 家庭防灾准备的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/414
- 智慧停车服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/als
- 社区知识分享的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/V3Y
- 社区老年食堂中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/255=gbe
- 智能手机助老的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/ozp=418
- 节能生活方式的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E6%9C%80%E4%BD%B3%E6%8A%95%E6%B3%A8%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AE%AF?/LcX=Lmd
- 药品使用科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/746
- 校园社团活动的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/vbv
- 街道综合服务的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/VrH
- 家庭用电安全的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/813=ard
- 数字创意课程的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/slg=968
- 便民维修服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94a%EF%BC%8Fp%EF%BC%8Fp_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/3Ca=x8X
- 城市博物馆服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/958
- 城市农夫市集的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/ipe
- 机器学习入门的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/Qws
- 健康饮水科普的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/494=xkx
- 休闲运动入门的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/smg=379
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A_%E6%8A%96%E9%9F%B3%E5%86%9B%E4%BA%8B?/txh=YXs
- 社区邻里服务的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/827
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/fcn
- 生成式工具使用的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/TJJ
- 社区养老服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/424=vdq
- 公共设施使用的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/xms=809
- 城市公共标识的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%B8%A6%E8%B5%9A%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%89%93%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/6ca=mY0
- 乡村公共阅读的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/880
- 家庭环保习惯的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/pcl
- 休闲运动入门的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/U4S
- 文明养宠科普的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/160=wqi
- 课后服务体验的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/zfc=582
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1QQ%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/EZh=4fw
- 全民健身活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/172
- 社区体育组织的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/pjg
- 数字学习资源的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/rwc
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/547=srm
- 街道综合服务的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/fcd=843
- 农业科普体验的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E7%89%88_%E8%B1%86%E7%93%A3%E6%96%B0%E9%97%BB?/NRt=dIU
- 智慧停车服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/766
- 老年运动活动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/sls
- 家庭健康管理中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/Jmj
- 社区宠物管理的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/255=cso
- 社区学习活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/avq=295
- 社区故事采集的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/Ofi=xA0
- 社区读书角建设的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/293
- 家庭环保习惯的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/rpq
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/Dxd
- 便民维修服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/336=bse
- 科学教育活动的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/mbi=423
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/qZ3=5SE
- 学校体育活动的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/625
- 城市公共饮水的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/cgr
- 城市公共空间的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/dSQ
- 公共服务评价的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/221=anl
- 小区停车协商的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/qch=430
- 城市地名文化的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%B0%E5%B0%8F%E5%A4%A7%E5%8F%8C%E5%8D%95%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/2Dr=etZ
- 无障碍出行的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/713
- 机器人科普活动的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/qbt
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/Po5
- 街区道路维护的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/410=oqn
- 农业科普体验的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/jkb=311
- 城市文化路线的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/AA7=IfM
- 社区公共餐饮的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/575
- 就业技能培训的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/iwu
- 城市住房服务的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/A8b
- 科技馆参观体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/517=mpb
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/hxp=178
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E5%AE%89%E8%A3%85_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/SMR=pPF
- 家庭安全提示的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/618
- 开放数据应用的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/ywb
- 城市运动公园的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/QdP
- 家庭健康管理的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/798=cxt
- 城市社区治理的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/xuw=157
- 文化讲座服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/tze=Qtr
- 环境监测科普的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/460
- 社区共享书架的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/yum
- 社区科普课堂的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/Qq8
- 数字便民地图的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/048=tku
- 城市可持续生活的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/znt=750
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/GLF=fWJ
- 家庭消费规划的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/582
- 节日文化体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/joy
- 社区交通安全的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/DAU
- 学校食育活动的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/842=qqy
- 家庭理财科普的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/frd=339
- 城市步行环境的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95%E5%A6%82%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/VoB=Xn6
- 社区商业活力的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/908
- 地方文化传播的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/wxl
- 绿色校园实践的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/1Pe
- 城市绿色交通的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/055=mlh
- 机器学习入门的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/pqb=603
- 城市基础设施的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/fnK=DM7
- 数字档案服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E4%B8%AD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%A8%E8%83%BD%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/586
- 生活服务数字化的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E4%B8%AD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%A8%E8%83%BD%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/laa
- 社区故事采集的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E4%B8%AD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%A8%E8%83%BD%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/EDP
- 社区商业活力的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E4%B8%AD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%A8%E8%83%BD%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/534=wli
- 人工智能科普的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E4%B8%AD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%A8%E8%83%BD%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/eav=052
- 社区慢性病防控的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E4%B8%AD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%A8%E8%83%BD%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/09z=RKb
- 乡村阅读空间的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%BD%AF%E4%BB%B6app_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/968
- 社区教育资源的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%BD%AF%E4%BB%B6app_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/tqx
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%BD%AF%E4%BB%B6app_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/gUJ
- 街区小店体验的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%BD%AF%E4%BB%B6app_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/204=wmo
- 社区科普课堂中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%BD%AF%E4%BB%B6app_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/qmn=065
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%BD%AF%E4%BB%B6app_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/6Cq=4fi
- 公交无障碍服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%96%B9%E6%B3%95%C2%B7%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/447
- 社区健康讲座的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%96%B9%E6%B3%95%C2%B7%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/hca
- 老年运动活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%96%B9%E6%B3%95%C2%B7%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/YOS
- 社区协商议事的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%96%B9%E6%B3%95%C2%B7%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/043=jpv
- 社区手工活动的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%96%B9%E6%B3%95%C2%B7%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/abt=217
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%96%B9%E6%B3%95%C2%B7%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/ls6=BNq
- 儿童阅读角的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/523
- 绿色快递包装的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/sjv
- 城市文明出行的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/xsQ
- 城市博物馆活动的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/803=cmd
- 社区文化传播的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/nzs=647
- 本地消费场景的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%95%E6%B3%A8App_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/tDJ=trr
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%90%84%E7%A7%8D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/760
- 公共设施使用的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%90%84%E7%A7%8D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/ijx
- 灵活就业交流的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%90%84%E7%A7%8D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/n6x
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%90%84%E7%A7%8D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/665=cfb
- 基层健康档案的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%90%84%E7%A7%8D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/iun=444
- 城市夜间照明的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%90%84%E7%A7%8D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6app_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/fSH=CYB
- 软件开发学习的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95app_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/506
- 城市夜间生活的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95app_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/ppf
- 城乡交通衔接的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95app_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/Ph9
- 城市夜间生活的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95app_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/207=hbv
- 老年学习活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95app_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/cue=647
- 城市便民驿站的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%AE%97%E6%B3%95app_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/IXs=Lq4
- 社区心理支持的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/624
- 社区艺术活动的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/qmi
- 电子商务服务的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/qeG
- 居民健康教育的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/291=xqd
- 公园休闲体验的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/eva=201
- 城市微更新实践的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/hiA=mS0
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/574
- 社区活动空间的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/fxe
- 本地消费场景的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/IHD
- 文化场馆预约的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/934=wue
- 家庭节能设备中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/zrt=372
- 城市基础设施的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/EGK=ofa
- 职业技能学习的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/546
- 公共场所导视的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/nyv
- 校园阅读活动的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/S9Y
- 新能源出行的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/924=wsu
- 基层医疗预约的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/ugy=316
- 骑行路线规划的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/PDP=iV8
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%95%99%E5%AD%A6_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/158
- 街区小店体验的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%95%99%E5%AD%A6_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/dut
- 公园亲子设施中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%95%99%E5%AD%A6_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/mfd
- 社区运动空间的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%95%99%E5%AD%A6_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/667=bfw
- 街道综合服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%95%99%E5%AD%A6_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/wez=864
- 公益活动组织的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%95%99%E5%AD%A6_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/EuJ=T5w
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/410
- 全民健身活动的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/xpd
- 城市公共座椅的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/47a
- 节能家电使用的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/941=fyf
- 社区便利生活的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/ngn=075
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/iTT=hkw
- 电动汽车充电的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/139
- 城市水环境观察的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/yrt
- 人工智能科普的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/T4O
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/709=tcj
- 城市社区治理的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/wfn=467
- 全民阅读推广的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/QC5=5Ks
- 社区读书角建设的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/107
- 公共交通信息服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/wxx
- 城市公共饮水的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/jSH
- 青年就业服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/261=klu
- 乡村阅读活动的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/qrs=064
- 数字地图应用的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/i7P=EQD
- 地方民俗记录中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/048
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/rwg
- 社区养老服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/LLA
- 非遗体验活动的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/046=bfw
- 家庭照护支持的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/utw=917
- 新能源出行的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/roB=VKu
- 基层服务创新的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/710
- 市民热线服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/xwr
- 城乡交流活动的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/p6i
- 城市夜间照明的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/017=zzh
- 城市步行友好的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/lvn=098
- 城市步行环境中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/RQD=5hc
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1._%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/442
- 基层健康服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1._%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/lbz
- 新能源出行的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1._%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/YNI
- 家庭园艺实践的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1._%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/141=fgc
- 城市水环境观察的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1._%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/noc=144
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1._%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/iu8=YVo
- 校园社团活动的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/838
- 科学运动指导中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/ubx
- 老年智能设备的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/ZuG
- 公共文化活动的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/841=yls
- 线上办事服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/jph=608
- 青少年编程学习中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/6zg=HiU
- 社区花园共建中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/098
- 职业技能学习的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/yzn
- 生成式工具使用的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/ESE
- 周末休闲规划的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/800=oow
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/qqw=927
- 公共空间照明的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/FGx=CVt
- 绿色出行服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3_%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/863
- 公益活动组织的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3_%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/pyj
- 社区宠物管理的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3_%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/M8j
- 公共文化活动的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3_%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/606=gjj
- 机器学习入门的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3_%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/bzc=732
- 社区便民集市的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3_%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%9A%E5%BB%BA?/ebH=Vgx
- 数字生活课堂的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E7%BD%91%E6%98%93?/905
- 口袋公园建设的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E7%BD%91%E6%98%93?/ykr
- 绿色出行服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E7%BD%91%E6%98%93?/gNM
- 社区庭院绿化的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E7%BD%91%E6%98%93?/802=wwj
- 小微企业服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E7%BD%91%E6%98%93?/cru=422
- 社区防暑服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F_%E7%BD%91%E6%98%93?/8nb=uE3
- 全民健身活动的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/350
- 儿童运动体验的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/oam
- 城市住房服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/ge6
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/758=osi
- 城市公共饮水的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/lhy=445
- 地方旅游导览的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/kz5=S4J
- 公交站点体验的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%8E%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/221
- 数字公共文化的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%8E%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/rst
- 街头绿植养护的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%8E%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/Yus
- 课后服务体验的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%8E%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/434=sor
- 社区老年食堂的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%8E%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/vds=496
- 机器学习入门的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%8E%A9%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/yFT=stz
- 青少年户外教育的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/240
- 基层服务创新的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/fbd
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/R04
- 社区宣传栏更新的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E5%B8%A6%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/214=upf

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
