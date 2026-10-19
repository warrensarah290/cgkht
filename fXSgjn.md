# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 居民健康教育的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/4aV
- 青少年心理健康的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/673=iab
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/dlu=379
- 老年人出行服务的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/eTg=x7c
- 无障碍信息设计的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/819
- 公共卫生宣传的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/rin
- 城市文明出行的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/NrI
- 城市步行友好中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/353=kjh
- 图书借阅体验的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/gth=264
- 全民健身活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/ara=2ov
- 绿色快递包装的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/024
- 科学睡眠习惯的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/ebe
- 邻里共享空间的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/pnS
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/984=ltv
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/fbq=753
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/DrX=WLt
- 老年友好服务的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/478
- 老年智能设备的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/czy
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/TtY
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/846=fme
- 城市社区治理的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/kzd=302
- 城市骑行环境的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/pdP=WaG
- 公共图书馆服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/548
- 校园安全教育的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/lhv
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/yLW
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/578=gew
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/mbn=730
- 灵活就业交流从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/kov=soU
- 口袋公园建设的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/519
- 便民维修服务的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/bsd
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/HYZ
- 城市应急科普的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/628=lgo
- 家庭网络使用的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/dsm=008
- 农贸市场环境的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/KK4=vbj
- 社区便民集市的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/755
- 社区交通安全的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/rsc
- 社区手工活动的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/IJL
- 电子商务服务的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/467=sqa
- 非遗体验活动的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/qoq=483
- 绿色消费选择的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/n8G=x3Y
- 网络安全教育的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/311
- 社区活动策划的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/owf
- 社区儿童活动的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/umd
- 社区艺术活动的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/586=xxw
- 社区志愿服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/rlc=273
- 公共空间导览的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/lRk=9qT
- 老年友好服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/882
- 节能家电使用的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/zab
- 公共服务指南的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/mBQ
- 社区心理支持的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/961=lqm
- 社区防暑服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/jum=610
- 社区教育资源的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95welcome_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/GMf=Zge
- 远程协作工具的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/678
- 旧物循环利用的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/lgv
- 社区托育服务的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/WPG
- 社区运动空间的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/210=xjs
- 社区信息发布的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/jfv=933
- 新能源知识普及的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/3KM=lIW
- 数字支付体验的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9app_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/923
- 城市体育设施的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9app_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/tms
- 便民服务窗口的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9app_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/wkA
- 小微企业服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9app_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/679=jfe
- 社区垃圾分类的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9app_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/eft=942
- 绿色办公实践的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9app_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/zwt=gue
- 公共空间照明的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/111
- 社区绿色空间的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/ele
- 社区健康讲座的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/1uM
- 家庭健康管理的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/397=fuy
- 城市应急科普的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/kxc=471
- 公共健身器材的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/ATZ=w9b
- 公共场所导视的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/731
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/sgl
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/GLG
- 城市绿色交通的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/196=qtv
- 周末休闲规划的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/wji=168
- 社区快递服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/t0d=74w
- 新能源出行的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/055
- 青年职业探索的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/mti
- 社区共享书架的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/17R
- 社区应急准备的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/090=wpr
- 数字资源检索的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/ryk=520
- 老旧小区改造的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/BAW=VlM
- 基层健康服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/068
- 社区手工活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/ptm
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/3YU
- 智慧城市体验的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/275=dsw
- 科普展览体验的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/wev=472
- 数字生活课堂的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP_%E5%87%A4%E5%87%B0%E5%AE%89%E9%98%B2?/jo7=byl
- 公共设施维护中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/513
- 地方美食文化的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/ihn
- 公共文化活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/k2j
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/571=dcn
- 本地消费场景的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/uxc=518
- 家庭园艺实践的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/vz8=r6h
- 公共场所导视的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/741
- 社区修缮行动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/leo
- 本地历史资料的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/szr
- 地方旅游导览的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/745=ice
- 周末休闲规划的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/mbc=513
- 社区艺术活动的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/ib7=e1d
- 基层健康服务的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/903
- 公共空间休憩的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/ggf
- 图书借阅体验的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/3tH
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/944=dxi
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/tjp=401
- 网络安全教育的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/9qF=NJd
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/246
- 智慧城市体验的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/xrw
- 农贸市场环境的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/Nez
- 社区便民集市的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/087=tuf
- 乡村文化空间的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/rag=615
- 小区公共照明的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/BEQ=mLI
- 生成式工具使用的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/365
- 校园社团活动的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/ejv
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/ZVZ
- 节能生活方式的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/285=tsw
- 街区更新实践中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/ggs=973
- 老年友好服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/Tqq=OLR
- 户外活动组织有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/306
- 环境教育课程的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/dfh
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/2qy
- 家庭健康科普的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/443=vrm
- 社区公共卫生的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/fcy=202
- 社区便民集市的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/sW1=44e
- 城市基础设施的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/236
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/vtm
- 城市公共饮水的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/Qw2
- 家庭收纳实践的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/564=ynw
- 老年运动活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/tvl=784
- 乡村阅读空间的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%9C%9B?/BwX=P1Q
- 公共场馆服务的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%96%87%E5%8C%96?/859
- 数据分析入门的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%96%87%E5%8C%96?/wap
- 家庭节能设备的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%96%87%E5%8C%96?/jWm
- 个人信息保护的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%96%87%E5%8C%96?/830=yui
- 灵活就业交流的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%96%87%E5%8C%96?/nxc=024
- 城市雨天出行的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E6%96%87%E5%8C%96?/uJa=BRD
- 青年志愿活动的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E9%A6%96%E9%A1%B5_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/382
- 社区知识分享的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E9%A6%96%E9%A1%B5_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/twa
- 社区体育组织的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E9%A6%96%E9%A1%B5_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/eTS
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E9%A6%96%E9%A1%B5_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/454=epl
- 气象科普传播的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E9%A6%96%E9%A1%B5_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/ikb=915
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E9%A6%96%E9%A1%B5_%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/OGi=EFQ
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/022
- 本地消费场景的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/vdu
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/pfB
- 城市空气科普的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/277=ilo
- 读书会组织从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/mlo=927
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5-%E5%AE%98%E6%96%B9_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/LbC=1qM
- 城市基础设施的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%88%B8%E5%95%86?/938
- 便民信息查询的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%88%B8%E5%95%86?/vsg
- 老年运动活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%88%B8%E5%95%86?/SWP
- 公共设施使用的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%88%B8%E5%95%86?/055=zdr
- 新能源知识普及的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%88%B8%E5%95%86?/zdx=084
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%88%B8%E5%95%86?/Lpc=Wsw
- 开放数据应用的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/498
- 数字生活课堂的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/qay
- 家庭安全提示的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/tjX
- 劳动教育实践的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/239=dla
- 生活服务数字化的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/zbn=815
- 城市博物馆服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/mvB=RLH
- 社区科普课堂的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/795
- 社区环保活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/soy
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/K8U
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/568=ixr
- 老年智能设备的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/mro=751
- 社区快递服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/GpN=ZIQ
- 邻里互助活动的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/563
- 绿色消费选择的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/orb
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/HWk
- 食品安全科普的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/534=hcx
- 校园节能行动的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/nli=713
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/HmL=xm5
- 软件开发学习的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/537
- 日常摄影记录的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/tqp
- 数字便民地图的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/Qwn
- 全民健身活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/844=fkj
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/ywi=977
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/T7r=Tpl
- 城市文明实践的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/541
- 城市噪声观察的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/oip
- 社区家校合作的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/C52
- 公交站点体验的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/362=lna
- 安全出行教育的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/iba=440
- 开源技术交流的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/qlb=MsA
- 数字生活课堂的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/908
- 城市人文观察的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/jad
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/OF6
- 消防知识宣传的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/858=oap
- 家庭安全提示的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/mqu=013
- 青年职业探索的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/5vH=0A6
- 社会体育指导的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/728
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/eng
- 青年志愿活动的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/UOK
- 课后服务体验的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/583=hlr
- 城市夜间生活的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/iuu=819
- 城市微更新实践的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/1bB=rTq
- 线上阅读资源的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/836
- 医院导诊服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/dpy
- 社区便民服务的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/9Jp
- 街道综合服务的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/481=svz
- 社区养老服务的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/lwf=619
- 数字学习资源的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/c2K=qlK
- 公共场所导视的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/815
- 生活垃圾减量的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/cqb
- 乡村生态观察的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/pRo
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/784=ezs
- 城市住房服务的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/ujg=884
- 健康饮食教育的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/jy6=hss
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/174
- 在线学习体验的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/esf
- 老年智能设备的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/Avi
- 新能源知识普及的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/917=cqb
- 城乡公共服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/omy=149
- 市民意见收集的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/k1D=qFC
- 社区花园共建的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/035
- 图书馆活动策划的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/kqd
- 街头绿植养护的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/5Tm
- 绿色快递包装的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/603=znl
- 城市生活记录的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/kug=877
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/Oie=Tfo
- 数字阅读服务的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/615
- 城市便民驿站的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/smb
- 社会体育指导的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/Lnj
- 家庭健康管理的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/166=icg
- 社区绿色空间的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/fjb=825
- 城市雨天出行的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/zT5=ZWs
- 社区共享书架的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/976
- 社区设施共享的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/vfu
- 健康饮食教育的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/eH4
- 休闲运动入门的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/229=yqb
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/xxu=366
- 在线学习体验的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/Swz=oVm
- 线上阅读资源的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/465
- 便民维修服务的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/edg
- 地方民俗记录的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/buH
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/196=zam
- 城乡公共服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/eof=988
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/jkj=VA5
- 非遗课堂体验的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/800
- 绿色办公实践中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/zho
- 青少年科普实践的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/cVk
- 老年人文化生活的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/005=wyy
- 小区电梯维护的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/eau=503
- 街区小店体验的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/FbS=kMX
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/816
- 公共服务评价的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/aqg
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/HeK
- 市民热线服务的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/539=auj
- 社会体育指导的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/chn=101
- 城市公共空间的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/HLJ=bvx

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
