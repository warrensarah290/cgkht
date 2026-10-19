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

- 社区庭院绿化的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/oma
- 环境监测科普的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/073=zvs
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/nlw=667
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/9Ws=Rez
- 光伏知识科普的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/627
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/wgd
- 青年职业探索的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/gg2
- 公共场馆服务的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/632=png
- 全民健身活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/nph=110
- 社区公共餐饮的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/p6I=IbE
- 公共服务评价的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/317
- 科学运动指导的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/jzx
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/XU4
- 校园社团活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/419=hhu
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ocg=313
- 城市应急科普的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/mOp=lS7
- 家庭收纳实践的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/127
- 城市生活服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/cdm
- 乡村公共文化的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/e2E
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/445=sft
- 网络安全教育的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/zlk=394
- 社区运动空间的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/u0z=6Fr
- 生活技能分享的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/707
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/tqn
- 城市公共饮水的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/34v
- 社区花园共建的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/408=nkm
- 社区手工活动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/xqz=889
- 家庭用电安全的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%B8%B8%E6%88%8F?/Kqt=6PI
- 城市文明出行的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/343
- 社区阅读服务的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/qsh
- 本地消费场景的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/Yxy
- 城市空气科普的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/045=dyd
- 地方美食文化的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/vrd=762
- 志愿者培训交流的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/wZk=Ifv
- 街区道路维护的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/041
- 急救知识普及的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/flp
- 社区商业活力的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/sEH
- 社区家政服务的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/882=xry
- 公共场所导视的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/iha=425
- 社区商业活力的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/DSW=TIQ
- 地方美食文化的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/145
- 绿色办公实践的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/tzn
- 图书馆活动策划的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/efA
- 便民服务窗口的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/018=rpi
- 社区休闲设施的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/osm=574
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/en2=3oT
- 网络安全教育的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/713
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/rck
- 社区快递服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/O0t
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/996=fcw
- 无障碍出行的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/gez=512
- 城市适老服务的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/MTn=tSB
- 智能手机助老的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/409
- 城市休闲步道的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/xqc
- 城市夜间照明的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/Fly
- 本地历史资料的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/336=omo
- 社区知识分享的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/roo=600
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/49Q=tMP
- 城市雨天出行的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/526
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/yln
- 通勤路线规划的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/H1E
- 青少年科技社团的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/602=edc
- 绿色出行服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/juy=421
- 软件开发学习的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/VEN=IVs
- 青年志愿活动的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/501
- 家庭急救准备的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/zcm
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/JXK
- 社区邻里服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/820=vww
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/rir=913
- 数字课堂应用的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/1s5=OCS
- 社区共享书架的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/533
- 运动安全知识的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/uct
- 公共交通接驳的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/lTz
- 旧物循环利用的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/898=gws
- 口袋公园建设的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/vfi=929
- 科普展览体验的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/r5P=XDy
- 城市公共厕所中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/842
- 青少年户外教育的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/hnm
- 公交站点体验的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/I2O
- 社区设施共享的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/256=gua
- 医院导诊服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/fjx=412
- 家庭食品保存的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/ZzD=HNd
- 通勤路线规划的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/525
- 社区协商议事的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/tls
- 青年志愿活动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/JqI
- 社区家政服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/592=fnn
- 城市公共自行车的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/fif=860
- 城市公共空间的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/czZ=COV
- 城市适老服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/335
- 远程协作工具的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/qrp
- 健康信息获取的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/lL4
- 家庭园艺实践的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/521=iqu
- 家庭收纳实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/dzd=064
- 公共场馆服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/Af9=HZX
- 城市噪声观察的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/406
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/yps
- 城市可持续生活的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/9Pp
- 社区文化节活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/593=hfp
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/gvr=840
- 社区家政服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/wOk=Cr1
- 街区更新实践的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/105
- 社区绿色空间的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/mom
- 城市雨天出行的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/2jr
- 网络信息辨识有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/248=tvh
- 青少年户外教育的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/ech=148
- 人工智能科普的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/JRE=Dr1
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/752
- 社区故事采集的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/zss
- 传统节日科普的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/uBJ
- 公共服务评价的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/710=djo
- 社区防暑服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/axn=816
- 本地旅行体验的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/XcP=7pP
- 读书会组织从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/412
- 生活服务数字化的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/lit
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/p4c
- 城市适老服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/546=mln
- 社区故事采集的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/sdp=453
- 城市建设科普的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/tWn=FJ5
- 便民服务地图的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/628
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/xxl
- 无障碍出行的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/n9k
- 数字素养提升的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/433=uoh
- 社区交通安全的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/zdf=457
- 城市文明出行的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/u6a=39e
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/348
- 本地历史资料的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/xvi
- 气象科普传播的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/gPF
- 公共服务预约的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/325=hrx
- 校园安全教育的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/gvm=344
- 休闲运动入门的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/Nj4=UPN
- 社区活动策划的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/661
- 城市人文观察的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/sdq
- 城市公共座椅中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/5Wc
- 亲子科普活动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/354=gdj
- 读书会组织的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/dda=992
- 公共空间照明的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/Me2=KQS
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/774
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/fty
- 城市绿道建设的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/uRk
- 青少年科普实践的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/826=fpq
- 科学运动指导的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/srb=855
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/lyH=81B
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/098
- 气象科普传播的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/prn
- 社区共享书架的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/axk
- 街区小店体验的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/811=qgm
- 城市应急科普的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/ifg=244
- 公共交通接驳的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/g41=Yme
- 社区艺术活动的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/438
- 社区活动空间的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/vso
- 旧物循环利用的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/dxq
- 青年志愿活动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/109=oit
- 乡村文化空间的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/mka=468
- 老年人出行服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/x7z=GPv
- 便民服务地图的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/086
- 社区托育服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/zyj
- 基层健康服务的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/k76
- 社区老年食堂的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/003=umh
- 社区共享书架的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/jpd=781
- 亲子科普活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8app_%E6%BE%8E%E6%B9%83%E6%88%B7%E5%A4%96?/SJK=lgm
- 在线学习体验的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%82%80%E8%AF%B7%E7%A0%81%E8%B0%81%E6%9C%89_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/426
- 城市水环境观察的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%82%80%E8%AF%B7%E7%A0%81%E8%B0%81%E6%9C%89_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/vck
- 志愿者培训交流的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%82%80%E8%AF%B7%E7%A0%81%E8%B0%81%E6%9C%89_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/uDw
- 城市步行友好的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%82%80%E8%AF%B7%E7%A0%81%E8%B0%81%E6%9C%89_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/457=yca
- 农产品消费体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%82%80%E8%AF%B7%E7%A0%81%E8%B0%81%E6%9C%89_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/iag=913
- 医院导诊服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%82%80%E8%AF%B7%E7%A0%81%E8%B0%81%E6%9C%89_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/q9K=0t5
- 生成式工具使用的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/625
- 生活垃圾回收的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/oom
- 无障碍出行的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/Xvd
- 数字素养提升的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/438=zzh
- 公共服务数字化的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/omm=262
- 居家防滑改造的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/HuE=xo1
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/577
- 城市生活服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/flj
- 终身学习资源的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/buQ
- 老旧小区改造的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/061=cza
- 老年学习活动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/bmm=020
- 校园安全教育的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/0CD=Cak
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/697
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/xhq
- 节日文化体验的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/bvI
- 公交站点体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/421=fvd
- 小微企业服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/mrn=815
- 社区商业活力的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/BCj=jpw
- 社区家校合作的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A3805%E7%A2%98top_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/980
- 城市公共饮水的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A3805%E7%A2%98top_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/sjz
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A3805%E7%A2%98top_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/dqA
- 开放式学习空间的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A3805%E7%A2%98top_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/804=fzy
- 节约用水实践的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A3805%E7%A2%98top_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/wvp=734
- 软件开发学习的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8.%E7%BD%91%E6%8A%95%E7%BD%91%E6%B2%9A3805%E7%A2%98top_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/Pgw=dC6
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8857%E6%AE%BFtop_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/540
- 城市夜间照明的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8857%E6%AE%BFtop_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/yxg
- 城市公共自行车的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8857%E6%AE%BFtop_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/ktd
- 城市夜间照明的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8857%E6%AE%BFtop_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/902=fun
- 数字设备回收的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8857%E6%AE%BFtop_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/sea=505
- 城市住房服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8857%E6%AE%BFtop_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/yET=AvU
- 城市共享单车的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%96%B0%E6%B4%BB%E5%8A%A8%E5%BC%80%E5%90%AF.%E6%96%B0%E7%BA%BF%E8%B7%AF%E5%BF%AB%E8%BF%9B.%E4%B8%AD%E5%9B%BD_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/848
- 城市应急科普的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%96%B0%E6%B4%BB%E5%8A%A8%E5%BC%80%E5%90%AF.%E6%96%B0%E7%BA%BF%E8%B7%AF%E5%BF%AB%E8%BF%9B.%E4%B8%AD%E5%9B%BD_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/ocp
- 节气饮食文化从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%96%B0%E6%B4%BB%E5%8A%A8%E5%BC%80%E5%90%AF.%E6%96%B0%E7%BA%BF%E8%B7%AF%E5%BF%AB%E8%BF%9B.%E4%B8%AD%E5%9B%BD_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/YML
- 本地历史资料的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%96%B0%E6%B4%BB%E5%8A%A8%E5%BC%80%E5%90%AF.%E6%96%B0%E7%BA%BF%E8%B7%AF%E5%BF%AB%E8%BF%9B.%E4%B8%AD%E5%9B%BD_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/812=zft
- 老年运动活动的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%96%B0%E6%B4%BB%E5%8A%A8%E5%BC%80%E5%90%AF.%E6%96%B0%E7%BA%BF%E8%B7%AF%E5%BF%AB%E8%BF%9B.%E4%B8%AD%E5%9B%BD_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/bet=802
- 信息无障碍体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%96%B0%E6%B4%BB%E5%8A%A8%E5%BC%80%E5%90%AF.%E6%96%B0%E7%BA%BF%E8%B7%AF%E5%BF%AB%E8%BF%9B.%E4%B8%AD%E5%9B%BD_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/7EF=mAi
- 社区便民服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8yx.dianwan.%E4%B8%AD%E5%9B%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/216
- 老年数字阅读的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8yx.dianwan.%E4%B8%AD%E5%9B%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/fqd
- 城市运动公园的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8yx.dianwan.%E4%B8%AD%E5%9B%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/w8W
- 小区电梯维护的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8yx.dianwan.%E4%B8%AD%E5%9B%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/827=oez
- 新能源知识普及的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8yx.dianwan.%E4%B8%AD%E5%9B%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/fnc=838
- 气象科普传播的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8yx.dianwan.%E4%B8%AD%E5%9B%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/yf3=sD2
- 开放式学习空间的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B8%B8%E5%BF%AB%E9%80%9F%E7%89%88.%E8%80%81%E5%9C%B0%E5%9D%80.org_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/048
- 开放数据应用的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B8%B8%E5%BF%AB%E9%80%9F%E7%89%88.%E8%80%81%E5%9C%B0%E5%9D%80.org_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/noq
- 居民健康教育的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B8%B8%E5%BF%AB%E9%80%9F%E7%89%88.%E8%80%81%E5%9C%B0%E5%9D%80.org_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/BQB
- 绿色办公实践的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B8%B8%E5%BF%AB%E9%80%9F%E7%89%88.%E8%80%81%E5%9C%B0%E5%9D%80.org_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/344=kvk
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B8%B8%E5%BF%AB%E9%80%9F%E7%89%88.%E8%80%81%E5%9C%B0%E5%9D%80.org_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/ill=483
- 社区艺术活动的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B8%B8%E5%BF%AB%E9%80%9F%E7%89%88.%E8%80%81%E5%9C%B0%E5%9D%80.org_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/cIE=x0J
- 公共设施维护的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E9%A6%96%E9%A1%B5%E7%BD%91%E5%9D%80_360%E9%97%AE%E7%AD%94?/481
- 地方旅游导览的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E9%A6%96%E9%A1%B5%E7%BD%91%E5%9D%80_360%E9%97%AE%E7%AD%94?/khl
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E9%A6%96%E9%A1%B5%E7%BD%91%E5%9D%80_360%E9%97%AE%E7%AD%94?/YMt
- 亲子科普活动的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E9%A6%96%E9%A1%B5%E7%BD%91%E5%9D%80_360%E9%97%AE%E7%AD%94?/457=dzq
- 健康信息获取的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E9%A6%96%E9%A1%B5%E7%BD%91%E5%9D%80_360%E9%97%AE%E7%AD%94?/nle=874
- 在线学习体验的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E9%A6%96%E9%A1%B5%E7%BD%91%E5%9D%80_360%E9%97%AE%E7%AD%94?/yD9=6Lz
- 校园社团活动的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/724
- 新能源知识普及中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/ppr
- 居家防滑改造的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/Ys9
- 乡村公共服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/100=fay
- 城市地名文化的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/qbp=329
- 青年志愿活动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E7%99%BE%E7%9B%88%E4%BD%93%E8%82%B2%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/5GD=3P0
- 食品配送体验的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%99%BE%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/052
- 公共服务预约的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%99%BE%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/xew
- 乡村公共阅读的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%99%BE%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/ZXB
- 农村环境治理的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%99%BE%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/305=agx
- 乡村公共服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%99%BE%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/hdw=643
- 社区便利生活的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%99%BE%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/DTv=gtv
- 城市社区治理的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%99%BE%E7%9B%88%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/294
- 城市公共饮水的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%99%BE%E7%9B%88%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/ijw
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%99%BE%E7%9B%88%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/jbK
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%99%BE%E7%9B%88%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/311=xln
- 开放数据应用的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%99%BE%E7%9B%88%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/cab=189
- 校园节能行动的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E7%99%BE%E7%9B%88%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/34o=gZe
- 本地历史资料的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%9B%88%E8%B6%B3%E7%90%83app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/120
- 社区应急准备的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%9B%88%E8%B6%B3%E7%90%83app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/bau
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%9B%88%E8%B6%B3%E7%90%83app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/eNc
- 社区休闲设施的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%9B%88%E8%B6%B3%E7%90%83app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/613=lks
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%9B%88%E8%B6%B3%E7%90%83app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/kpz=532
- 老年运动活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E7%9B%88%E8%B6%B3%E7%90%83app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/epa=9Ik
- 邻里共享空间的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/957
- 健康饮水科普的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/nti
- 公共服务评价的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/kqH
- 日常摄影记录的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/385=ycr
- 公共健身器材的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/fnf=667
- 软件开发学习的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/y6C=wg8

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
