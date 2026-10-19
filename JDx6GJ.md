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

- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_767cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/nMq
- 科学信息获取的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_767cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/406=gui
- 家庭园艺实践的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_767cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/zde=721
- 乡村产业科普的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_767cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/nvR=2RD
- 地方旅游导览的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_767cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/347
- 社区手工活动的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_767cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/fgt
- 数字资源检索的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_767cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/Ux5
- 社区文化节活动的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_767cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/243=bjv
- 课后服务体验的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_767cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/dtb=657
- 居家适老化改造的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_767cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/33d=QvX
- 全民阅读推广的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/805
- 新能源知识普及的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/lhf
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/dRf
- 数字设备回收的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/001=eve
- 无障碍信息设计的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/ptp=794
- 乡村生态观察的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/hJk=EFx
- 城市夜间生活的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/361
- 城市水环境观察的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/qdk
- 城市建设科普的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/abZ
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/693=yng
- 课后服务体验的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/kow=059
- 乡村阅读空间的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/iYU=nZg
- 城市体育设施的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/013
- 老年人出行服务的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/aoz
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/Uyq
- 街区小店体验中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/160=apc
- 节气饮食文化的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/mvs=130
- 亲子科普活动的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/eda=A1B
- 城市游园体验的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/686
- 休闲运动入门的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/gno
- 青少年户外教育的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/ihz
- 数字艺术创作的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/414=yac
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/cxc=451
- 公共服务咨询的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_767cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/892=vRf
- 家庭照护支持的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_767cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/479
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_767cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/opb
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_767cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/gVp
- 公共服务评价的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_767cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/577=lbg
- 非遗体验活动的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_767cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/otc=433
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_767cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/x43=72d
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_767cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/832
- 街区道路维护的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_767cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/nll
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_767cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/XwR
- 城市空气科普的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_767cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/886=twf
- 个人信息保护的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_767cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/cnc=229
- 节能家电使用的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_767cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/86s=aFL
- 非遗体验活动的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/867
- 图书借阅体验的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/fjt
- 远程协作工具的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/a0g
- 社区快递服务的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/962=azx
- 街区绿化养护的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/xby=209
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/PsK=COx
- 社区法律科普的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/669
- 节日文化体验的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/aqb
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/rgE
- 智慧停车服务的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/800=xze
- 公共服务评价的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/mds=207
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_767cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/eZU=ujT
- 公共空间休憩的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/464
- 无障碍出行的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/lrx
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/pgr
- 智慧城市体验的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/088=mqp
- 公共空间休憩的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/ieh=141
- 社区邻里服务的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_767cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/1U2=Unr
- 物业服务沟通的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/505
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/fzp
- 就业技能培训的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/9LO
- 文化场馆预约的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/698=dry
- 青年职业探索的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/dis=389
- 节约用水实践的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_767cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/8Zk=dt4
- 青年志愿活动中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/665
- 城市共享单车的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/rdg
- 急救知识普及的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/wPa
- 户外活动组织的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/519=xuj
- 公益活动组织的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/wuc=459
- 本地历史资料的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_767cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/lP5=I7e
- 社区运动空间的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/507
- 网络信息辨识的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/rfo
- 社区知识分享的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/W8C
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/430=izv
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/wis=066
- 电动汽车充电的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/j1n=aof
- 城市绿道建设的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/129
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/puo
- 环境教育课程的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/IGR
- 无障碍出行的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/769=mln
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/cce=380
- 家庭健康科普的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%AE%BF?/Za8=3pG
- 个人信息保护的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/676
- 城市文明出行的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/dpp
- 城市慢行系统的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/Wlr
- 家庭科学教育的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/198=xnb
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/dcy=314
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/RJW=abr
- 绿色生活实践的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%95%85%E6%B8%B8?/550
- 非遗体验活动的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%95%85%E6%B8%B8?/hjn
- 职业技能学习的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%95%85%E6%B8%B8?/U55
- 老年人日常照护的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%95%85%E6%B8%B8?/867=uer
- 城市基础设施的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%95%85%E6%B8%B8?/gsd=585
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E7%95%85%E6%B8%B8?/VoQ=7Lw
- 社区庭院绿化的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/289
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/jlq
- 乡村公共服务的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/SQd
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/164=fzm
- 公共卫生宣传的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/nol=012
- 社区公共卫生的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/Hvv=Tw1
- 基层健康服务的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/248
- 市民意见收集的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/bhb
- 软件开发学习的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/mS5
- 公共交通接驳的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/582=znn
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/qzg=150
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/1lL=JNl
- 新能源出行的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/726
- 节能生活方式的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/ihg
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/aAp
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/718=gtx
- 生成式工具使用的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/ryk=912
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/U5A=jwH
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/879
- 社区休闲设施的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/odk
- 地方文化传播的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/h63
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/429=del
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/tve=186
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%96%87%E5%BA%93?/ZQy=hzE
- 街区小店体验的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/319
- 青年职业探索的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/fry
- 公共交通接驳的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/zO9
- 公共设施使用的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/055=dtr
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/jyx=700
- 无障碍信息设计的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%95%B0%E7%A0%81?/lP0=hqw
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_785cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/119
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_785cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/ehs
- 社区协商议事的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_785cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/Yqm
- 生活技能分享的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_785cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/158=hwe
- 社区家政服务的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_785cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/toy=611
- 儿童友好空间的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_785cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E6%B2%BB?/p7s=Oeb
- 乡村教育资源的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/394
- 家庭环保习惯的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/gnt
- 城市绿色交通的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/ye1
- 学校体育活动的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/040=qyg
- 农村环境治理的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/rmp=722
- 科普展览体验的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_785cc%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/FwP=ozh
- 课后服务体验中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/392
- 读书会组织的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/aea
- 社区休闲设施的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/SLW
- 老年学习活动的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/150=hfw
- 城市公共饮水的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/jox=428
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_785cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/J7j=GTd
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/066
- 公共空间休憩的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/dhg
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/4Gx
- 城市体育设施的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/405=zlv
- 家庭安全提示的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/euy=250
- 家庭网络使用的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/FBA=9yv
- 公共空间导览的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/186
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/olt
- 社区绿色空间的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/fP2
- 城乡公共服务的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/795=zbq
- 绿色生活实践的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/kqi=011
- 农业科普体验的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_785cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/fuW=QCJ
- 健康信息获取的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/849
- 家庭健康科普的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/ppi
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/qAc
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/463=srg
- 家庭用电安全中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/tnr=823
- 社区生活指南的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_785cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/1iz=Ifr
- 社区托育服务的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/264
- 社区健康讲座的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/qnv
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/E8e
- 社区体育组织的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/846=hmb
- 青少年编程学习的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/eal=950
- 青年就业服务的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_785cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/wdt=gP3
- 运动安全知识的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/814
- 社区绿色空间的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/dju
- 街区更新实践的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/c9T
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/312=fdb
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/wud=840
- 市民意见收集的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/opu=zJ0
- 城市展览体验的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/653
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/vnl
- 数字创意课程的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/eSj
- 公共交通接驳的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/727=sot
- 网络信息辨识的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/fmc=801
- 社区手工活动的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_785cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/t2t=jYf
- 家庭阅读计划的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/739
- 公共空间照明的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/loa
- 本地旅行体验的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/129
- 全民健身活动的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/260=czo
- 社区活动报名的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/uxh=445
- 公益活动组织的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_785cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/eih=3GR
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_785cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/557
- 公共图书馆服务的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_785cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/auc
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_785cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/dNM
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_785cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/422=tjo
- 日常摄影记录的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_785cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/trx=127
- 社区宠物管理的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_785cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/kXG=gaQ
- 居家防滑改造的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/246
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/aaf
- 公园无障碍服务的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/jRQ
- 社区手工活动的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/937=agj
- 个人时间管理的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/dhg=955
- 家庭用电安全的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_785cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%91%A8%E6%8A%A5?/E5f=4lN
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_829%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/838
- 家庭收纳实践的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_829%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/yvi
- 数字素养提升的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_829%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/1Fi
- 街区小店体验的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_829%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/393=aej
- 家庭安全提示的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_829%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/air=043
- 家庭节能设备的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_829%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/b5c=VBo
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/599
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/jme
- 社区协商议事的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/F9u
- 家庭节能实践的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/406=dfu
- 数字素养提升的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/wjx=731
- 绿色建筑理念的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_829%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/Mbw=Q0J
- 城市雨天出行的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/237
- 乡村公共文化的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/vmu
- 家庭健康管理的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/EkE
- 新能源知识普及的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/665=fws
- 社区应急准备的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/ozo=357
- 城市生活记录的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/LeO=orY
- 公共场馆服务的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/081
- 远程协作工具的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/eiz
- 个人数据管理的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/uyY
- 农村环境治理的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/045=zfn
- 社区托育服务的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/rdt=032
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/xkn=LjW
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/940
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/ryx
- 开放式学习空间的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/hlw
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/367=rbl
- 非遗课堂体验的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/mmw=668
- 社区交通安全的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%99%A8%E6%8A%A5?/4v4=YIn
- 运动安全知识的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/596
- 非遗体验活动的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/vss
- 公园休闲体验的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/WFH
- 生活垃圾回收的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/413=emj
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/bva=942
- 新能源出行的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_829%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/krp=2sM
- 城市夜间照明中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_829%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/165
- 社区公共卫生的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_829%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/tnk
- 社区心理支持的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_829%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/01y
- 社区科普课堂的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_829%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/670=row
- 社区安全巡查的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_829%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/obz=207
- 地方戏曲体验的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_829%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/Xsh=Iaz
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/628
- 数字公共文化的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/ruj
- 安全出行教育的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/wpX
- 农村环境治理的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/942=ode
- 社区家政服务的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/gtg=784
- 绿色校园实践的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_829%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/sRB=6vS

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
