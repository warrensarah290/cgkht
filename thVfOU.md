# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:31**

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

- 社区老年食堂的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/ghw=339
- 乡村教育资源的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/Cwq=AGO
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/272
- 公益活动组织的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/dxl
- 志愿者培训交流的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/2AA
- 社区手工活动的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/657=xbf
- 数字支付体验的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/obr=273
- 学校食育活动的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%9E%E6%9C%9B?/pUi=lN3
- 城市公共标识的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/332
- 家庭节能实践的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/leo
- 劳动教育实践的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/GdA
- 灵活就业交流的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/945=dpz
- 数字创作工具的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/xyj=212
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/oXL=iFB
- 乡村文化空间的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/499
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/wlb
- 数字便民地图的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/r12
- 居民健康教育的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/311=oov
- 家庭网络使用的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/znx=862
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/gNg=Wig
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/588
- 日常摄影记录的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/xvw
- 老年友好服务的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/tAa
- 智能家居应用的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/922=qii
- 青少年科技社团的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/oym=416
- 城市步行环境的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/4uA=8OI
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/803
- 公交无障碍服务的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/xhw
- 社区花园共建的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/Ee7
- 城市公共饮水的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/131=zvy
- 创业经验分享的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/ugh=125
- 城市生活服务的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/KPX=MVQ
- 城市游园体验的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/497
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/ebg
- 城市慢行系统中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/NFC
- 本地历史资料的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/002=jdj
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/tfg=948
- 志愿者培训交流的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/pOj=3td
- 青年职业探索的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/851
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/njr
- 农业科普体验的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/zua
- 城市地名文化的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/028=srm
- 终身学习资源的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/quq=364
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/8yI=CtM
- 社区庭院绿化的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/083
- 社区活动空间的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/ezn
- 家庭急救准备的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/SIW
- 社区邻里服务的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/996=hyz
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/uef=085
- 图书馆数字服务的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/oAM=Zzc
- 城市骑行环境的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/027
- 节日文化体验的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/jsj
- 社区老年食堂的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/Ksy
- 生活技能分享的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/841=qpx
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/pyx=870
- 校园节能行动的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/aN8=nZ5
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/908
- 个人时间管理的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/vip
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/ZXx
- 邻里互助活动的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/376=lrs
- 城市适老服务的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/npk=927
- 数字档案服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/vwB=SpU
- 公共设施使用的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/423
- 生成式工具使用的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/pva
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/WhT
- 数字阅读服务的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/894=rre
- 社区心理支持的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/wmy=449
- 城市空气科普的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/Tcb=woP
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/058
- 城市社区治理的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/mqu
- 软件开发学习的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/kNi
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/635=wco
- 数字政务体验的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/hal=450
- 社区信息发布中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/rZc=FSd
- 科学运动指导的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/993
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/jji
- 农贸市场环境中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/1gg
- 网络信息辨识的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/264=emp
- 社区慢性病防控的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/oyx=041
- 社区宠物管理的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/cbe=be9
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/390
- 科技馆参观体验的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/vna
- 文化讲座服务的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/GRf
- 创业经验分享的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/504=vpr
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/mal=962
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/oUx=GuZ
- 基层健康档案的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/803
- 无障碍出行的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/emh
- 城市适老服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/qEi
- 绿色出行服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/800=swr
- 老旧小区改造的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/gwq=666
- 青少年心理健康的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/PCK=5TE
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/452
- 光伏知识科普的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/tgm
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/o4r
- 公共空间休憩的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/034=qcj
- 市民热线服务的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/bfb=400
- 亲子科普活动的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/VPT=u4y
- 街头绿植养护的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/871
- 公共卫生宣传的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/bbr
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/FoF
- 光伏知识科普的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/240=ldi
- 便民维修服务的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/kpy=420
- 城市住房服务的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/yyT=DnR
- 日常摄影记录的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/351
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/vfi
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/gab
- 社区阅读服务的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/382=nit
- 社区读书角建设的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/bub=638
- 社区环保活动的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/2vP=f2S
- 绿色出行服务的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/755
- 急救知识普及的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/wrc
- 老年人日常照护的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/MOS
- 职业技能学习的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/866=fao
- 公共交通接驳的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/ixv=185
- 老年智能设备的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/emF=8wo
- 街道综合服务的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/003
- 市民热线服务的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/lsm
- 社区防暑服务的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/xq3
- 传统节日科普的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/152=hfi
- 儿童安全出行的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/kfz=784
- 社区交通安全的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/sRf=OVw
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/035
- 社区互助网络的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/rbz
- 家庭网络使用的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/R30
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/247=epm
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/qxw=221
- 社区活动策划的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/aup=ORf
- 城市博物馆活动的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/620
- 城市文化路线的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/tfd
- 乡村公共阅读的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/b3B
- 电子商务服务的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/095=lwr
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/oem=122
- 数字地图应用的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/rTR=fNI
- 街区道路维护的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/637
- 创业经验分享的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/vwx
- 城市体育设施的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/BBY
- 休闲运动入门的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/655=apo
- 数字创作工具的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/lim=043
- 社区志愿服务的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E9%97%AE%E5%8D%B7?/RSX=JQN
- 健康饮水科普的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/445
- 新能源出行的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/rdl
- 社区邻里服务的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/Duz
- 健康饮水科普的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/318=asw
- 社区消防演练的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/koo=231
- 家庭用电安全的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8?/SU4=ffY
- 垃圾分类指导的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/325
- 社区体育组织的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/bco
- 社区公共议事的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/C6f
- 社区儿童活动的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/762=jdj
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/tsl=675
- 数字创意课程中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/XhT=gTJ
- 线上阅读资源的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/593
- 家庭教育交流中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/msb
- 城市便民驿站的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/QLv
- 网络安全教育的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/734=ocu
- 小区公共照明的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/ftk=484
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/Diw=opT
- 家庭安全提示的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/343
- 青年职业探索的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/auc
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/8dr
- 科学观察活动的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/108=oiu
- 非遗课堂体验的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/jgu=391
- 低碳社区实践的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/IjV=s7E
- 农产品消费体验的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/069
- 文化场馆预约的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qpl
- 社区体育组织的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/a8Q
- 社区修缮行动的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/037=cqz
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lxz=782
- 地方美食文化的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ifU=Bwx
- 通勤路线规划的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/012
- 城市人文观察的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/yms
- 便民信息查询的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/jMN
- 图书馆活动策划的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/936=pck
- 数字档案服务的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/bsr=628
- 家庭教育交流的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/S4O=ctM
- 基层健康档案的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/542
- 公共文化活动的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/apz
- 城市绿色交通的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/nK5
- 社区防暑服务的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/262=kqe
- 儿童户外活动的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/yzt=727
- 数字地图应用的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/9uH=bHC
- 社区儿童活动的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/672
- 志愿服务平台的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/lnt
- 户外活动组织的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/xKi
- 数字支付体验的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/792=cmw
- 公共设施使用的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/twv=202
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/IjC=4AE
- 乡村生活观察的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_360%E6%99%A8%E6%8A%A5?/071
- 居民健康教育的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_360%E6%99%A8%E6%8A%A5?/xia
- 城市便民驿站的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_360%E6%99%A8%E6%8A%A5?/Tvk
- 社区环保活动的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_360%E6%99%A8%E6%8A%A5?/400=wdu
- 家庭运动计划的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_360%E6%99%A8%E6%8A%A5?/lqn=104
- 社区养老服务的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_360%E6%99%A8%E6%8A%A5?/WaJ=8Yt
- 居家适老化改造的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/662
- 城市空气科普的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/vux
- 社区设施共享的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/lHq
- 居家防滑改造的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/909=nmi
- 数字生活课堂的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/lvy=938
- 城市绿道建设的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/C8k=5r7
- 网络安全教育的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/068
- 青少年户外教育的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/nrv
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/iJg
- 生活垃圾减量的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/438=pvf
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ioq=378
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/y7u=ADr
- 社区活动空间的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/943
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/ahp
- 城市绿道建设的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/JJX
- 家庭食品保存的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/562=brd
- 城市微更新实践的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/axe=347
- 城市应急科普的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/ibr=lXt
- 文明养宠科普的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/607
- 家庭环保习惯的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/sbp
- 街区更新实践的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/BPy
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/560=ngw
- 社区志愿服务的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/rxu=110
- 绿色生活实践的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/x60=yRo
- 农产品消费体验的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/613
- 社区绿色空间的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/dco
- 便民服务地图的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/coY
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/145=wzr
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/jiu=755
- 传统节日科普的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/X4W=9z3
- 城市基础设施的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/411
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/jcw
- 远程协作工具的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/myu
- 公园无障碍服务的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/752=bdq
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/mwq=777
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/HNq=5k3
- 数字设备回收的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/641
- 电动汽车充电的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/dsc
- 城市公共座椅的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/bwL
- 城市社区治理的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/616=wol
- 创业经验分享的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/ynr=646
- 小区公共照明的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/7Ee=81u
- 数字档案服务的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/483
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xvs
- 市民意见收集的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Rpq
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/119=trz
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/cbn=009
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/cGa=frW
- 软件开发学习的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/984
- 城市公共艺术的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/niu
- 基层医疗预约的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/QzY
- 社区商业活力的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/561=udv
- 线上办事服务的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/rcv=044
- 小微企业服务的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/gmP=TLw
- 公共空间休憩的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/094
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_1516%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/hce

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
