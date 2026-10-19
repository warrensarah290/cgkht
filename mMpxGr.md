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

- 智慧停车服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/het
- 绿色办公实践的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/940=goq
- 科技馆参观体验的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/uyp=284
- 校园社团活动的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/9Cm=VMC
- 城市基础设施的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/141
- 数字资源检索的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/dlv
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/LSx
- 乡村公共文化的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/133=sfa
- 社区活动策划的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/adp=057
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/UGl=WLG
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/255
- 社区便利生活的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/ggh
- 乡村文化活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/2pY
- 无障碍出行的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/084=jmb
- 个人信息保护的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/rrd=074
- 基层健康服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/IYA=Vr2
- 街头绿植养护的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/286
- 数字设备回收的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/rsq
- 社区老年食堂的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/t6p
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/845=fzo
- 城市绿色交通的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/coa=549
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/KjI=cpw
- 城市雨天出行的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/451
- 食品安全科普的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/ylr
- 乡村教育资源的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/db4
- 社区志愿服务的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/547=iea
- 生活技能分享的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/loz=216
- 在线学习体验的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/hTt=8ll
- 科学教育活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/810
- 城市文明出行的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/qjo
- 社区家校合作的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/EjO
- 环境教育课程中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/449=xui
- 街道综合服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/khq=834
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/Ala=G9m
- 智慧停车服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/458
- 就业技能培训的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/xfs
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/SdQ
- 地方旅游导览的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/787=pfk
- 社区托育服务中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/sie=895
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/l1K=04K
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/222
- 本地消费场景的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/ugt
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/ElA
- 社区故事采集的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/985=hez
- 志愿者培训交流的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/qip=518
- 节气饮食文化的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/Zuz=4LW
- 本地消费场景的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/636
- 公共设施维护的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/sbf
- 社区家校合作的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/tzl
- 家庭科学教育的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/312=crm
- 生活垃圾回收的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/glh=055
- 家庭健康科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/tn4=76Y
- 户外活动组织的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/629
- 家庭防灾准备的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/mdd
- 数字生活课堂的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/1mE
- 智能手机助老的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/861=hvw
- 节日文化体验的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/jud=802
- 城市水环境观察的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/WxK=TJ6
- 社区家政服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/292
- 节假日出行安排的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/jja
- 公共空间导览的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/VcW
- 社区艺术活动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/930=ciq
- 社区活动策划的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/iry=268
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/JEF=HAj
- 公共设施维护的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/709
- 乡村文化活动的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/ocl
- 灵活就业交流的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/gFf
- 环境监测科普的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/489=bmc
- 节约用水实践的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/eef=583
- 智能家居应用的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/BrE=4hY
- 电动汽车充电中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/001
- 通勤路线规划的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/vlc
- 青少年心理健康的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/uHC
- 社区教育资源的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/577=pwt
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/awe=636
- 食品配送体验的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_1%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/38E=LdL
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/011
- 地方民俗记录的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/hmx
- 个人信息保护的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/10B
- 基层健康档案的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/179=som
- 周末休闲规划的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/ecd=313
- 公共空间照明的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/vEx=1Jj
- 社区活动策划的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/397
- 科学教育活动的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/tvj
- 创业经验分享的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/lCI
- 非遗体验活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/844=ccb
- 电动汽车充电的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/lsb=068
- 小区停车协商的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/YO7=pKU
- 数字素养提升的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/878
- 社区健康讲座的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/hxo
- 农业科普体验的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/8hx
- 社区慢性病防控的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/049=xlq
- 数字设备回收中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/avl=067
- 气象科普传播的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/Dyg=n7c
- 科学观察活动的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/847
- 城市公共艺术的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/llg
- 口袋公园建设的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/1yL
- 城市骑行环境的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/625=njr
- 智慧停车服务的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/imk=255
- 青少年科技社团的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/cNO=YGM
- 垃圾分类指导的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/576
- 城市绿道建设的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/eyr
- 农村环境治理的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/sXt
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/100=hvx
- 城市公共空间的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/lvd=912
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/jvk=gf8
- 城市慢跑路线的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/948
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/ynr
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/4JE
- 数字支付体验的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/564=org
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/hxk=871
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/X7m=S1y
- 劳动教育实践的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_1%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/110
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_1%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/hmh
- 城市公共标识的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_1%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/eMk
- 农村环境治理的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_1%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/966=ilb
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_1%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/bzu=208
- 社区阅读服务的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_1%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BB%8F%E6%B5%8E?/SIw=ZEZ
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/083
- 城市绿道建设的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/rie
- 智慧停车服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/18h
- 节气饮食文化的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/559=qam
- 数字档案服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/gja=880
- 非遗体验活动的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/azn=EV5
- 社区快递服务的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/013
- 公共卫生宣传的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/wmt
- 家庭运动计划的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/wwP
- 社区商业活力的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/173=ath
- 社区便民服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/jmi=795
- 人工智能科普的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/2AB=B1L
- 公共服务预约的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/489
- 城乡公共服务的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/ujw
- 食品配送体验的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/C7T
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/858=hya
- 公共文化活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/fsg=285
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/DHE=1HW
- 城市空气科普的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_1%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/118
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_1%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/kyz
- 城市空气科普的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_1%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/etv
- 社区艺术活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_1%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/738=yic
- 数字政务体验的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_1%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/yyg=537
- 数字创意课程的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_1%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/gCS=FwG
- 智能手机助老的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/510
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/fkr
- 社区停车服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/2zS
- 生活服务数字化的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/772=vgt
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/qfj=217
- 机器学习入门的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/KoM=MIw
- 老年人日常照护的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/187
- 乡村生态旅游的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/gna
- 社区教育资源的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/tId
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/958=xex
- 老年友好服务的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/nec=437
- 城市树木认养的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/LWm=vhP
- 图书馆活动策划的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/231
- 城市便民驿站的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/ukj
- 农产品消费体验的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/oaO
- 社区科普课堂的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/409=kkr
- 社区停车服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/xoi=913
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/8wV=9xj
- 社区公共议事的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/344
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/naw
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/Yd6
- 数字档案服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/321=pnp
- 旧物循环利用的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/ohw=861
- 社区慢性病防控的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/XM0=2hL
- 医院导诊服务的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/336
- 社区绿色空间的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/nla
- 青年就业服务的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/avf
- 市民意见收集的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/616=kxs
- 城市应急科普的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/fwu=971
- 个人信息保护的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%91%8A?/RVQ=tOp
- 软件开发学习的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/692
- 数字学习资源的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/nfw
- 城市社区治理的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/uAi
- 青少年科技社团的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/889=cgs
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/jkl=589
- 跨代沟通活动的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/dR6=saN
- 社区便利生活的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/372
- 社区教育资源的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/ucg
- 儿童友好空间的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/YnV
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/778=zff
- 校园阅读活动的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/nog=897
- 青少年科普实践的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/MLs=zhP
- 开放数据应用的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/906
- 城市展览体验的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/ngm
- 医院导诊服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/ZBI
- 开放数据应用的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/031=bcp
- 社区协商议事的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/tbl=926
- 公共空间安全的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/ThG=k1o
- 医院导诊服务的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/508
- 城市建设科普的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/uln
- 青少年编程学习的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/9oV
- 读书会组织的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/813=pbe
- 科学观察活动的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/oms=747
- 社区公共餐饮的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/Dhh=8ji
- 公共设施维护的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/312
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/ray
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/IU9
- 老年人文化生活的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/330=qtx
- 农村环境治理的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/gfk=481
- 公交无障碍服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/htO=qVq
- 社区共享书架的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_1%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/554
- 文明养宠科普的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_1%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/apv
- 终身学习资源的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_1%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/xDp
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_1%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/246=urh
- 线上阅读资源的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_1%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/pkm=595
- 乡村公共服务的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_1%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/VpM=0Aj
- 社区协商议事的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/049
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/isu
- 城市便民驿站的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/YWQ
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/200=njz
- 城乡交流活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/yyy=104
- 食品安全科普的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/574=Xet
- 本地旅行体验的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/507
- 跨代沟通活动的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/uqb
- 社区运动空间的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/RLY
- 地方文化传播的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/134=dfd
- 社区安全巡查的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pmd=794
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/oSP=BKq
- 数字阅读服务的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/388
- 城市应急广播的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/nav
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/nTm
- 小区电梯维护的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/486=acz
- 公交无障碍服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/smf=732
- 街区绿化养护的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/QZ3=CVX
- 城市文明实践的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/518
- 网络安全教育的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/dyx
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/Rd9
- 城市博物馆活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/924=dci
- 志愿服务平台的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/upa=252
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/trH=3cR
- 骑行路线规划的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/776
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/cjd
- 个人数据管理的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/N6U
- 城市雨天出行的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/925=aox
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/ctn=095
- 城市绿道建设的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/jVw=6gB
- 便民维修服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/687
- 青年职业探索的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/uaq
- 城市生活记录的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/wfq
- 老旧小区改造的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/442=dls
- 农贸市场环境的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/eij=561
- 城市公共饮水的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/zOK=BX4
- 农业科普体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF?/578
- 社区家校合作的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF?/iqy
- 租房信息服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF?/DQl
- 城市社区治理的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF?/304=uwb
- 绿色出行服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF?/enp=932
- 新能源出行的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF?/b6S=OjZ

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
