# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 公共卫生宣传的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/ygq=672
- 社区公共卫生的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/Ho9=b5Q
- 便民服务窗口的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/567
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/fdk
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/Uxe
- 社区协商议事的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/994=tbm
- 城市慢行系统的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/duf=722
- 公共场馆服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%91%84%E5%BD%B1?/xL1=bYZ
- 社区庭院绿化的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/335
- 青年职业探索的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/ytd
- 社区商业活力的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/2uj
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/505=obx
- 小区停车协商的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/ktv=147
- 户外活动组织的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/ZEA=U8O
- 环境教育课程的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/463
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/xku
- 家庭收纳实践的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/BCI
- 公共空间休憩的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/227=prk
- 城市水环境观察的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/sxk=721
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/ajH=E9j
- 学校体育活动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/757
- 数字支付体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/uql
- 社区设施共享的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/ZYO
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/495=bjy
- 家庭安全提示的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/fba=228
- 网络信息辨识的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/3Gl=r9F
- 开放式学习空间的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/559
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/hak
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/Fsk
- 社区便民服务的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/196=yso
- 文明养宠科普的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/ukc=991
- 创业经验分享的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/tJE=3v6
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/152
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/sas
- 地方戏曲体验的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/1qu
- 公共空间安全的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/858=cnd
- 全民阅读推广的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/ffi=624
- 城市骑行环境中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/Kxh=Y5H
- 数字公共文化的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/874
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/rjd
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/B9k
- 城市展览体验的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/960=lvt
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/gyk=305
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/qi0=c4v
- 青少年心理健康的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/059
- 城市可持续生活的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/mcx
- 公共健身器材的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/b1r
- 健康信息获取的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/799=jla
- 创业经验分享的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/zxt=425
- 小微企业服务的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/LWh=G0y
- 城市步行环境的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/539
- 社区活动策划的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/eyz
- 绿色校园实践的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/t2M
- 数字创作工具的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/786=wri
- 数字支付体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/xmf=412
- 家庭网络使用的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/Q9B=1DA
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/535
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/xvw
- 本地历史资料的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/AaC
- 低碳社区实践的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/359=fms
- 社区共享书架中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/zbm=559
- 个人信息保护的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/hnu=xUe
- 地方旅游导览的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/187
- 街区绿化养护的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/guo
- 青年就业服务的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/iC0
- 家庭食品保存的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/263=ong
- 社区手工活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/dde=611
- 数字资源检索的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/bg2=HES
- 农产品消费体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/702
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/rap
- 周末休闲规划的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/opT
- 公共设施使用的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/079=jrf
- 乡村阅读空间的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/yoi=983
- 科学信息获取的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/7TP=djD
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/890
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/afl
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/FXo
- 公益活动组织的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/365=neg
- 食品配送体验的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/umf=949
- 社区商业活力的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/EAe=RPr
- 数字阅读服务的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/835
- 便民维修服务的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/awx
- 社区心理支持的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/ABe
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/871=dun
- 社区文化节活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/shb=763
- 学校体育活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/JYD=z8u
- 老年学习活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/965
- 数字档案服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/llx
- 节约用水实践的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/vC3
- 城市空气科普的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/533=dxb
- 乡村阅读空间的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/ihd=055
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/hhD=KPr
- 社区便民集市的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/082
- 社区老年食堂的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/dpt
- 公共场所导视的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/frm
- 社区防暑服务的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/421=cpq
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/akc=318
- 线上阅读资源的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/T8s=dY6
- 社区慢性病防控的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/666
- 社区托育服务中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/kht
- 基层健康服务的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/NDO
- 公共空间照明的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/622=jhy
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/gfi=277
- 公共设施使用的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/th9=bhl
- 文明养宠科普的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/395
- 街区小店体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/iwl
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/Tja
- 家庭环保习惯的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/362=htn
- 居家适老化改造的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/orb=581
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/3uR=UVa
- 公益活动组织的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A887_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/024
- 公共空间导览的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A887_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/kyz
- 社区教育资源的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A887_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/fbm
- 市民热线服务的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A887_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/152=wkg
- 数字设备回收的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A887_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/pfd=334
- 节约用水实践的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A887_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/Lsg=eHw
- 老年人日常照护的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/727
- 青少年户外教育的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/tcv
- 智慧停车服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/tHw
- 城市公共空间的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/993=yfh
- 家庭健康管理的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/eaa=389
- 全民健身活动的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%92%AD%E6%8A%A5?/hYs=AZX
- 基层健康服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/033
- 光伏知识科普的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/gew
- 城乡交流活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/9NT
- 周末休闲规划的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/846=klx
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/zhd=029
- 食品安全科普的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/yxd=r0I
- 农业科普体验的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A81399_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/496
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A81399_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/fqo
- 家庭园艺实践的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A81399_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/vyh
- 居家防滑改造的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A81399_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/148=yhy
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A81399_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/ffz=111
- 基层医疗预约的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A81399_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/OHn=veV
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/067
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/ono
- 社区慢性病防控的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/9XS
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/490=rvv
- 公共空间安全的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/gkw=945
- 文明养宠科普的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/7KK=6iO
- 社区科普课堂的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2050%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/230
- 乡村产业科普的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2050%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/bqz
- 社区邻里服务的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2050%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/W2R
- 社区协商议事的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2050%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/052=wun
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2050%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/bkn=594
- 志愿者培训交流的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2050%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/1rt=0a0
- 青少年编程学习的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/178
- 乡村生活观察的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/fhw
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/nwd
- 校园安全教育的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/047=qbr
- 社区庭院绿化的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/pnh=488
- 机器学习入门的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E6%9C%8D%E9%A5%B0?/4rj=R3b
- 个人数据管理的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/354
- 公共文化活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/qzp
- 社区儿童活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/A1l
- 城市休闲步道的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/774=uch
- 城市步行友好的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/myn=497
- 城乡公共服务的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/34A=jrV
- 地方文化传播的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/643
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/ibv
- 儿童友好空间的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/4RX
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/718=vjk
- 科学健身方法的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/mhj=807
- 绿色校园实践的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/qFt=DnR
- 线上阅读资源的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_360%E7%A8%8E%E5%8A%A1?/943
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_360%E7%A8%8E%E5%8A%A1?/rrq
- 市民热线服务的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_360%E7%A8%8E%E5%8A%A1?/Z4w
- 城市适老服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_360%E7%A8%8E%E5%8A%A1?/926=gcj
- 社区交通安全的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_360%E7%A8%8E%E5%8A%A1?/oud=904
- 便民信息查询的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_360%E7%A8%8E%E5%8A%A1?/f9c=8yh
- 城市建设科普的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/818
- 社区交通安全的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/yce
- 家庭养老规划的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/EEZ
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/970=xsh
- 社区消防演练的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/dil=644
- 公共空间导览的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Z9V=b2P
- 老年学习活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/310
- 乡村产业科普的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/exc
- 社区公共餐饮的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ild
- 社区活动策划的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/789=crb
- 数字档案服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/csz=781
- 学校食育活动的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/XoY=uxp
- 新能源知识普及的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/576
- 社区儿童活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/tnh
- 光伏知识科普的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/qTb
- 新能源出行的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/612=omp
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/vpy=264
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/HuD=Lum
- 校园安全教育的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/437
- 社区庭院绿化的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/cao
- 数字学习资源的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/xkH
- 节气饮食文化的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/304=yaa
- 社区运动空间的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/ctg=708
- 家庭网络使用的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/In8=XEr
- 本地旅行体验的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/913
- 公共健身器材的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/ble
- 家庭环保行动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/7ZU
- 城市便民驿站的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/194=tii
- 药品使用科普的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/emb=885
- 城市宠物友好空间的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/qYC=R06
- 社区读书角建设的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8A%A1?/599
- 地方旅游导览从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8A%A1?/ddb
- 城市应急广播的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8A%A1?/S4G
- 社区活动报名的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8A%A1?/616=uiu
- 志愿者培训交流的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8A%A1?/wsf=639
- 个人数据管理的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%94%BF%E5%8A%A1?/Wrz=wOU
- 智能家居应用的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/926
- 社区托育服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/itv
- 社区设施共享中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/5GV
- 线上办事服务的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/155=kot
- 公交站点体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/svu=232
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/HFK=MHw
- 城市便民驿站中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/689
- 社区防暑服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/ygs
- 节能家电使用中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/F6O
- 乡村公共服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/841=nlu
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/xtk=178
- 电动汽车充电的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/xCg=La6
- 日常摄影记录的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1388%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/532
- 智能家居应用的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1388%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/kqc
- 城市可持续生活的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1388%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/Mcp
- 城市休闲步道的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1388%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/191=xqb
- 文化讲座服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1388%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/yox=357
- 生成式工具使用的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1388%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/SC6=4dK
- 校园社团活动的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_1388%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/192
- 基层健康档案的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_1388%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/afw
- 家庭环保行动的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_1388%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/Cpy
- 公共健身器材的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_1388%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/414=ozb
- 青年志愿活动的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_1388%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/gkd=711
- 节约用水实践的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_1388%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/P5R=wkW
- 社区知识分享的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/472
- 城市休闲步道的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/wrj
- 食品配送体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/t4Y
- 街区道路维护的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/714=wjd
- 地方文化传播的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/wfq=387
- 无障碍信息设计的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/jm0=UKG
- 老年运动活动的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/323
- 乡村教育资源的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/vou
- 城市可持续生活中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/7Pr
- 公共场所导视的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/191=miw
- 城市人文观察的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/mwx=612
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_1588%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/2IK=0KM
- 软件开发学习的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_1588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/444
- 读书会组织的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_1588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/wer
- 老旧小区改造的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_1588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/foB
- 社区便民服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_1588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/364=lfi
- 市民热线服务的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_1588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/nkw=023
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_1588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/2O8=4OZ
- 社区垃圾分类的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_1588%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/014
- 传统节日科普的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_1588%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/vcf

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
