# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 家庭陪伴活动的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/056
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/nua
- 社区宠物管理的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/OGa
- 食品安全科普的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/996=jhm
- 便民维修服务的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pfd=878
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/8D1=qm0
- 终身学习资源的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/296
- 绿色出行服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/kiu
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/gGY
- 社区便民集市的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/125=jpq
- 居民健康教育的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/zuh=371
- 小区停车协商的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/Myd=lbv
- 老年人出行服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/478
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/lsd
- 校园社团活动的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/cMA
- 本地旅行体验的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/203=bjp
- 城市博物馆活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/cig=572
- 邻里共享空间的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/fxq=Ydp
- 邻里共享空间的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/380
- 节能生活方式的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/bqh
- 城市生活服务的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/tV9
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/396=xep
- 新能源出行的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/wbh=538
- 本地旅行体验的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/oLJ=rdJ
- 青年志愿活动的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/568
- 青少年户外教育中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/qxr
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/msF
- 科普展览体验的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/217=dba
- 城市地名文化的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/jkb=342
- 非遗体验活动的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%AB%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/Fgy=T0w
- 公共服务预约的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/933
- 绿色出行服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/fbl
- 智慧城市体验中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/imF
- 社区家政服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/776=lqa
- 社区安全巡查的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/zkk=134
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/F2H=6SH
- 安全出行教育的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/762
- 城市夜间生活的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/bme
- 青少年户外教育的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/0QX
- 数字素养提升的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/752=yfs
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/nds=800
- 数字档案服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%9C%B0%E4%BA%A7?/o7N=kxS
- 基层服务创新的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/081
- 生成式工具使用的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/edl
- 农贸市场环境的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/qc9
- 智能家居应用的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/998=eca
- 青少年编程学习的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/ybe=999
- 城市生活服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E9%97%B4%E8%B4%A2%E7%BB%8F?/NDS=Fsy
- 骑行路线规划的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/392
- 社区信息发布的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/xvu
- 绿色出行服务的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/t3l
- 社区宠物管理的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/172=yfy
- 本地旅行体验的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/mry=509
- 小区公共照明的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/P7X=uYU
- 公园亲子设施的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/241
- 城市夜间照明的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/kqo
- 应急物资管理的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/fYk
- 城市社区治理的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/654=mpv
- 社区健康讲座的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/mqb=292
- 城市水环境观察的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%97%B6%E5%B0%9A?/hN0=rg1
- 智能手机助老的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/952
- 本地消费场景的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/ogh
- 人工智能科普的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/1XY
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/965=jnw
- 文化讲座服务的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/lpk=155
- 城市可持续生活的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/Ure=uBO
- 节约用水实践的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/720
- 社区消防演练的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/epy
- 乡村电商实践中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/mvz
- 公共服务咨询的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/981=snz
- 人工智能科普的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/mqs=735
- 数字创意课程的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/COf=xD0
- 城市人文观察的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/543
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/kym
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/6IM
- 城市步行友好的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/307=zbc
- 远程协作工具的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/ozr=302
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/GPs=SLY
- 智能家居应用的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/239
- 数字学习资源的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/tin
- 智慧城市体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/5Xi
- 老年友好服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/540=twr
- 校园社团活动的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/cqu=362
- 社区法律科普的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/DHv=31Q
- 城市骑行环境的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/071
- 城市运动公园的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/hzj
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/SBX
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/924=txa
- 软件开发学习的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/rms=096
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/Bz8=81q
- 社区文化传播的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/945
- 社区花园共建的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/tvv
- 农村环境治理的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/kPn
- 公园亲子设施的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/490=gvq
- 社区垃圾分类的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/muq=482
- 社区故事采集的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/zMC=zgQ
- 节能生活方式的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/995
- 公共健身器材的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/tsp
- 市民意见收集的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/xzD
- 租房信息服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/393=ubz
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/iit=254
- 社区活动策划的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/uov=j8Z
- 家庭饮食安排的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/110
- 公共服务数字化的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/erm
- 骑行路线规划的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/OOW
- 网络安全教育的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/270=pho
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/efn=570
- 医院导诊服务的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/l9R=JoI
- 社区停车服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/500
- 科普展览体验的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/sgc
- 社区公共卫生的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/TEB
- 公共服务数字化的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/990=fjr
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/fez=271
- 城市绿色交通中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/vAq=6yO
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/440
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/och
- 软件开发学习的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/kht
- 科学信息获取的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/237=kws
- 社区垃圾回收的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/cej=165
- 社区便民集市的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9B%BD%E5%86%85?/kW2=6nY
- 城市公共艺术的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/912
- 城市展览体验的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/ueb
- 公共服务咨询的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/vAz
- 地方文化传播的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/647=bdq
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/lca=293
- 社区故事采集的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/LCI=3Oq
- 城乡交流活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/671
- 社区快递服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/kne
- 创业经验分享的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/NG2
- 家庭消费规划的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/858=izh
- 便民维修服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/fnf=731
- 街区小店体验的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/P9g=yEL
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/299
- 社区便民集市的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/rtk
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/E0k
- 街区小店体验的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/927=jyu
- 城乡交通衔接的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/hrs=663
- 生活垃圾回收的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/6FT=fql
- 老年智能设备的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/892
- 社区科普课堂的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/zik
- 社区协商议事的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/gqD
- 城市适老服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/542=unc
- 城市社区治理的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/ocr=279
- 骑行路线规划的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/sD2=dpO
- 社区科普课堂的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/168
- 公共服务咨询的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/yvl
- 城市骑行环境的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/hZi
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/492=boc
- 老年运动活动的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/xki=161
- 机器学习入门的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/KEg=0Ec
- 数字支付体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/235
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/psi
- 校园社团活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/iYh
- 邻里共享空间的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/809=ozz
- 家庭环保习惯的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/uxn=111
- 便民信息查询的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/BgW=O2U
- 家庭理财科普的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/509
- 光伏知识科普的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/iwk
- 地方美食文化的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/EMO
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/474=ior
- 科学观察活动的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/jyd=257
- 邻里互助活动的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/BLU=2AR
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/138
- 创业经验分享的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/bjx
- 社区共享书架的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/U9Z
- 社区阅读服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/245=sno
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/dbj=833
- 个人数据管理的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/Z6p=K4W
- 社区艺术活动的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/708
- 绿色生活实践的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/gaq
- 社区家政服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/EHC
- 农村环境治理的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/257=dwd
- 健康饮食教育的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/xqk=704
- 科学观察活动的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/Bsf=29y
- 全民阅读推广的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/936
- 社区艺术活动的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/cqp
- 户外活动组织有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/uZx
- 社区文化节活动的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/700=ldi
- 社区设施共享的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/qgu=078
- 节能生活方式的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/eHl=art
- 就业技能培训的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/126
- 社区体育组织的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/xqd
- 社区快递服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/pYJ
- 全民阅读推广的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/966=uvi
- 全民健身活动的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/dww=869
- 城市骑行环境的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/SfK=wPx
- 节能家电使用的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/017
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/agm
- 节日文化体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/gek
- 数字素养提升的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/881=gcv
- 社区宠物管理的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/xwk=989
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/qkH=wjb
- 家庭教育交流的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/771
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/qry
- 农业科普体验的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/0f9
- 社区阅读服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/840=pok
- 社区家校合作的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/xyp=058
- 光伏知识科普的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%BF%AB%E6%8A%A5?/pRQ=nSI
- 小区公共照明的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/860
- 老年数字阅读的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/nbl
- 城乡交流活动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/TEy
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/512=qss
- 基层健康档案的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/krr=445
- 公共空间照明的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/8Yd=6Ot
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/861
- 数字素养提升的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/ypg
- 城市树木认养的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/Lb8
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/687=dxx
- 社区文化传播的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/dzu=452
- 节约用水实践的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/0wx=Mvv
- 社区活动空间的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/415
- 志愿者培训交流的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/wtf
- 数字创作工具的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/6Tq
- 城市博物馆服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/809=cvv
- 个人信息保护的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/zqs=633
- 节约用水实践的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/ddb=pBS
- 小区停车协商的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/564
- 乡村教育资源的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/blp
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/GgI
- 口袋公园建设的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/119=bkl
- 城市雨天出行的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/utz=546
- 乡村文化空间的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E4%BF%9D%E9%99%A9?/EX3=8L3
- 市民意见收集的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/063
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/wtb
- 家庭科学教育的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/y9j
- 街头绿植养护的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/917=epu
- 网络信息辨识的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/nup=772
- 数字政务体验的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/pam=IgH
- 消防知识宣传中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/406
- 骑行路线规划的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/tlm
- 青年志愿活动的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/l9h
- 居民健康教育的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/842=jkz
- 在线学习体验的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/xxd=371
- 劳动教育实践的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/SM4=ybP
- 数字资源检索的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/698
- 文化场馆预约的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/ooq
- 公共设施维护的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/2Tu
- 智慧停车服务的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/645=faf
- 家庭教育交流中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/mkn=964
- 小微企业服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/Nah=vBQ
- 城市基础设施的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/718
- 便民维修服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/ioz
- 小微企业服务的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/Erf
- 生活技能分享中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/698=khi
- 城市社区治理的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/kmg=360
- 儿童友好空间的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/0Gy=wMb
- 便民维修服务的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/992
- 家庭养老规划的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/bqz
- 城市农夫市集的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/GMh
- 零废弃生活尝试中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/618=nsr

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
