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

- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/ooi=134
- 市民意见收集的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/rKu=A4F
- 数字设备回收的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/052
- 城市空气科普的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/qyj
- 课后服务体验的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/kqV
- 读书会组织的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/340=kuw
- 本地历史资料的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/flk=669
- 读书会组织的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/Szq=CQf
- 创业经验分享的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/278
- 儿童友好空间的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/smp
- 便民服务地图的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/2hL
- 城市人文观察的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/850=axn
- 乡村阅读空间的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/fli=155
- 科学教育活动的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/5tu=ZrA
- 城市建设科普的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/659
- 城市绿道建设的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dqs
- 社区公共卫生的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Ka1
- 地方民俗记录中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/406=mlu
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fhv=221
- 文化讲座服务的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/mOt=Su3
- 老年学习活动的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/177
- 公共空间导览的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/ges
- 儿童户外活动的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/Fkb
- 社区慢性病防控的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/489=fys
- 社区快递服务的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/jda=837
- 新能源知识普及的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%88%9B%E7%9B%88%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%91%84%E5%BD%B1?/wlh=d2V
- 骑行路线规划的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/607
- 创业经验分享的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/njj
- 城市生活记录的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/pDU
- 社区修缮行动的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/670=eel
- 消防知识宣传的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/qlp=386
- 儿童安全出行的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/ibZ=aG1
- 绿色快递包装的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/498
- 健康步道使用的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/pjr
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/MgZ
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/300=oex
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/rvz=455
- 社区防暑服务的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/Cnr=IjS
- 运动安全知识的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/117
- 社区读书角建设的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/fgr
- 软件开发学习的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/hK4
- 绿色建筑理念的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/886=zcr
- 图书借阅体验的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/auo=295
- 街区小店体验的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/bA9=e67
- 公共服务预约的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/596
- 农产品消费体验的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/mzu
- 家庭防灾准备的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/77g
- 食品安全科普的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/544=uor
- 健康饮水科普从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/dhk=656
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/zuf=5L4
- 社区商业活力的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/036
- 公园亲子设施的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/fbd
- 社区修缮行动的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/UBO
- 课后服务体验的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/114=dix
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/bbh=539
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E4%B9%A6%E7%94%BB?/lnH=ii0
- 城市噪声观察的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/776
- 公共交通接驳的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/kbq
- 社区便民集市的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/8Kt
- 城乡交通衔接的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/181=wcv
- 社区体育组织的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/bdz=782
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/Srr=Ept
- 家庭消费规划的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/820
- 无障碍出行的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/rze
- 社区生活指南的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/Ouv
- 家庭用电安全的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/963=pzw
- 城市夜间生活的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/jyt=054
- 家庭理财科普的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/cS6=Law
- 社区设施共享的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/868
- 家庭运动计划的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/tbt
- 社区生活指南的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/p4U
- 社区活动策划的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/439=flc
- 社区活动报名的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/ptj=985
- 城市社区治理的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/5Lf=goZ
- 社区活动报名的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/327
- 开源技术交流的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/fkn
- 社区快递服务的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/3y8
- 个人信息保护的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/816=rpt
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/jza=204
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/dpN=VER
- 公共场所导视中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/760
- 城市文化路线的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/qcu
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/XDz
- 新能源出行的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/522=mol
- 城市建设科普的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/bbb=397
- 绿色校园实践的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/qIy=yic
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%B1%BD%E8%BD%A6?/006
- 校园节能行动的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%B1%BD%E8%BD%A6?/qur
- 城市文化路线的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%B1%BD%E8%BD%A6?/X7G
- 城市公共座椅的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%B1%BD%E8%BD%A6?/384=ytw
- 家庭环保习惯的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%B1%BD%E8%BD%A6?/ynb=454
- 社区协商议事的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%B1%BD%E8%BD%A6?/vLK=k4Y
- 节气饮食文化的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/243
- 运动安全知识的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/ntv
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/95Z
- 家庭防灾准备的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/884=lvk
- 公共健身器材的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/tam=432
- 绿色办公实践的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/SPV=L6d
- 家庭健康管理的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/255
- 街区更新实践的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/kuz
- 骑行路线规划的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/wfv
- 居家适老化改造的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/775=cdi
- 老年人日常照护的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/mbo=474
- 社区休闲设施的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/UKt=jjM
- 街区小店体验的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/975
- 小微企业服务的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/izl
- 社区公共餐饮的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/vrR
- 绿色校园实践中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/137=axj
- 社区防暑服务的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/wyj=722
- 便民维修服务的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/4cN=BAE
- 气象科普传播的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/427
- 家庭教育交流的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/vem
- 老年人文化生活的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/7VS
- 社区学习活动的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/795=zuj
- 社区协商议事的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/exy=276
- 休闲运动入门的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/lbL=Law
- 乡村生态观察中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/163
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/vkw
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/Bc1
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/534=ekd
- 城市绿色交通的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/ciz=249
- 家庭消费规划的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/AGn=0Pn
- 户外活动组织的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/909
- 周末休闲规划的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/gsz
- 数字地图应用的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/Qq7
- 科学健身方法的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/568=fyj
- 乡村文化活动的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/cef=124
- 城市体育设施的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/cZm=0ui
- 数字档案服务的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/096
- 小微企业服务的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/kst
- 开放数据应用的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/NYj
- 城市住房服务的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/986=rww
- 租房信息服务的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/jkp=554
- 社区防暑服务的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/VN4=BWL
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/061
- 街区小店体验的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/uki
- 城市应急科普的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/NPz
- 公共卫生宣传的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/559=vww
- 无障碍信息设计的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/jhu=709
- 节约用水实践的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/PB3=Ejn
- 市民意见收集的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/837
- 社区健康讲座的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/lyk
- 便民服务窗口的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/HVF
- 家庭健康管理的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/268=yet
- 地方美食文化中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/jzd=814
- 绿色校园实践的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/nsR=pfS
- 社区科普课堂的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/540
- 电动汽车充电的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/sbe
- 街道综合服务的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/RqQ
- 乡村公共文化的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/429=iim
- 周末休闲规划的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/yrw=163
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/u0u=phu
- 电子商务服务中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/495
- 城市文明出行的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/ylt
- 科学运动指导的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/GbV
- 社区活动报名的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/545=zjv
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/opj=497
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/AkF=0DG
- 乡村生活观察的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/899
- 公共文化活动的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/sce
- 科学健身方法的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/CoS
- 课后服务体验的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/310=zxg
- 终身学习资源的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/ete=552
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/Lyd=hML
- 城市基础设施的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/932
- 家庭饮食安排的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/uvi
- 就业技能培训的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/gP5
- 社区故事采集的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/337=weh
- 青年职业探索的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/onc=389
- 社区老年食堂的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/O7M=XOA
- 社区活动报名的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/682
- 社区家校合作的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/hit
- 城市文化路线的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/yvZ
- 城市生活服务的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/937=kmw
- 家庭节能实践的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/qse=553
- 科普展览体验的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/McL=edT
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/702
- 骑行路线规划的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/tag
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/7cF
- 家庭饮食安排的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/066=mfy
- 乡村教育资源的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/jut=554
- 公园亲子设施的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%9B%B2%E8%89%BA?/c9v=kA8
- 城市建设科普的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/573
- 绿色出行服务的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/bzc
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/vkI
- 家庭消费规划的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/288=hcp
- 校园安全教育的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/cuv=117
- 社区运动空间的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A4%A7%E7%99%BC%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/vgf=pMO
- 社区交通安全的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/793
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/pnh
- 公共空间导览的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/Pl3
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/435=tir
- 消防知识宣传的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/fjb=433
- 职业技能学习的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/4fj=PTa
- 本地消费场景的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/108
- 社区托育服务的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/nid
- 城市公共艺术的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/0LM
- 公共服务预约的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/752=cts
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/qyy=652
- 城市社区治理的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/oyb=95v
- 城市应急科普的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/084
- 社区安全巡查的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/eeg
- 租房信息服务的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/clJ
- 绿色快递包装的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/507=fee
- 城市雨天出行中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/vtz=520
- 电动汽车充电的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/Ued=gJY
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/820
- 公共空间休憩的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/cvf
- 传统节日科普的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/MM2
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/313=gda
- 地方文化传播的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/efp=270
- 数字创作工具的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/nad=o0v
- 城市绿道建设的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/477
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/cdz
- 城市水环境观察的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/WZH
- 学校体育活动的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/571=qns
- 地方文化传播的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/dgg=284
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/A5b=650
- 街道综合服务的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/356
- 文明养宠科普的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/bjq
- 公共卫生设施的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/Fp9
- 就业技能培训的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/096=uvm
- 亲子科普活动的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/btz=445
- 老年运动活动的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E7%99%BB%E5%BD%95welcome_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/q8A=KR1
- 休闲运动入门的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/414
- 家庭健康管理中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/tlc
- 邻里共享空间的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/Bv6
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/365=llz
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/qua=346
- 校园节能行动的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BC%97%E6%B5%8B?/vSV=gfW
- 无障碍信息设计的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/036
- 老年人出行服务的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/syl
- 家庭阅读计划的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/AN2
- 城市公共饮水的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/164=mfj
- 小区电梯维护的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/hou=459
- 城市建设科普的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/llq=WOH
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/327
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/jvg
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/04e
- 公共设施维护的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/175=hqh
- 非遗体验活动的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/pli=310
- 街区绿化养护中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/UsP=c87
- 口袋公园建设的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/670
- 农贸市场环境的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/ujj
- 公园休闲体验的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/yUL
- 老年学习活动的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/575=mwn
- 居民健康教育的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/xso=011
- 社区环保活动的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/zm9=Uxu
- 居民健康教育的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/824
- 社区信息发布的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E7%99%BC%E5%AF%BC%E8%88%AA-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/vpf

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
