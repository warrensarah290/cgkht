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

- 小区公共照明中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/112
- 社区便利生活的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/cmj
- 个人信息保护的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/uDK
- 城市水环境观察的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/030=dbg
- 城市文化路线的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/vwi=300
- 青少年科普实践的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/gDu=wyP
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/732
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/dec
- 社区花园共建中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/1be
- 食品安全科普的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/402=lda
- 公共健身器材的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/dgl=020
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%85%AD%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/D7t=Q5u
- 社区托育服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/265
- 创业经验分享的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/rrc
- 乡村文化活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/exL
- 健康饮食教育中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/188=vmq
- 就业技能培训的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/xpo=406
- 电动汽车充电的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/KgP=cdt
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/404
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/iyi
- 电动汽车充电的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/Wk0
- 城市体育设施的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/124=xvu
- 社区科普课堂的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/itt=559
- 物业服务沟通的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/QfX=ExN
- 公共场馆服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/254
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/oam
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/Akm
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/060=lzm
- 家庭志愿活动的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/fwg=089
- 机器学习入门的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%88%9B%E6%8A%95?/nN7=4Kk
- 家庭收纳实践的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/670
- 家庭教育交流的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/yry
- 城市步行友好的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/I0D
- 社区宠物管理的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/801=jmp
- 本地历史资料的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/rsa=499
- 医院导诊服务的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%95%85%E6%B8%B8?/ofr=VC2
- 线上办事服务的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/312
- 家庭理财科普的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/wde
- 农业科普体验的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/FGV
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/906=jbr
- 垃圾分类指导的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/umn=438
- 公共服务沟通的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/Sn3=1ag
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/238
- 城市建设科普的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/onh
- 家庭养老规划的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/7jE
- 社区公共议事的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/942=jzp
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/oig=728
- 在线教育体验的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/2DQ=g0a
- 家庭收纳实践的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/434
- 青年职业探索的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/oot
- 社区公共卫生的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/JLM
- 农产品品牌传播的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/224=hlv
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/pue=100
- 公共服务数字化的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/2e2=cq0
- 便民服务窗口中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/857
- 网络信息辨识的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/zhf
- 城市应急广播的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/wYG
- 城市生活记录的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/994=aov
- 通勤路线规划的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/dui=194
- 健康步道使用的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%9F%B3%E4%B9%90?/hNm=Ejq
- 社区便民集市的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/992
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/aqi
- 健康饮食教育的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/qvS
- 数字素养提升的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/061=hmq
- 公共服务数字化的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/pgw=006
- 传统手工艺体验的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/yz0=09f
- 社区互助网络的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/030
- 社区环保活动的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/dah
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/vmb
- 社区家校合作的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/149=hfe
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/grm=583
- 便民服务地图的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/8QO=r4h
- 数字政务体验的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/286
- 青年就业服务的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/bun
- 老年运动活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/3Vy
- 传统节日科普的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/297=kve
- 开放数据应用的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/wcq=891
- 城市共享单车的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E8%AE%BA?/9IY=UQs
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/334
- 绿色办公实践的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/hen
- 公共服务沟通的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/ygp
- 乡村文化空间的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/408=jnz
- 骑行路线规划的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/bat=343
- 社区志愿服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/bFi=J96
- 地方旅游导览的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/187
- 公交站点体验的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/uto
- 数字创作工具的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/ysl
- 基层医疗预约的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/633=dpt
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/eft=116
- 开放式学习空间的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/F1U=RMM
- 老年人日常照护的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/320
- 家庭环保行动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/koc
- 社区志愿服务的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/6cc
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/709=ymn
- 基层服务创新的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/zqx=474
- 公共交通接驳的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/Fjj=35F
- 家庭环保习惯的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/068
- 线上阅读资源的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/neg
- 街区更新实践的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/yWo
- 城市体育设施的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/646=etb
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/gqi=310
- 图书馆数字服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/ybF=Q2Y
- 城市文化路线的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/561
- 健康信息获取的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/yzr
- 家庭环保行动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/9A7
- 城市微更新实践的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/541=tlj
- 社区科普课堂的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/baw=027
- 城市展览体验的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/rsB=3jN
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/467
- 基层健康档案的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/bie
- 社区协商议事的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/aXj
- 旧物循环利用的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/522=njm
- 乡村电商实践的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/lgc=717
- 城市住房服务的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/6tl=HbG
- 户外活动组织的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/136
- 智能手机助老的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/zio
- 家庭收纳实践的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/6pl
- 药品使用科普的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/114=hke
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/yyl=398
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/I6S=Mwk
- 非遗课堂体验的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/740
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/bgj
- 节能生活方式的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/9at
- 全民阅读推广的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/561=smj
- 街区道路维护的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/akf=661
- 图书馆数字服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%96%87%E6%91%98?/YbX=ejb
- 公园亲子设施的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/539
- 节日文化体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/kve
- 城乡交通衔接的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/4ni
- 数字支付体验的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/632=erl
- 城乡交流活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/fwj=792
- 社区手工活动的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BE%99%E8%85%BE%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/QD7=SCu
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/061
- 青少年科技社团的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/scc
- 青年志愿活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/36r
- 城市住房服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/166=zjz
- 家庭环保习惯的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/pwi=622
- 小区公共照明的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/e9x=Inj
- 健康步道使用的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/972
- 老旧小区改造的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/lcs
- 社区活动策划的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/iDp
- 绿色办公实践的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/046=sks
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/mpm=114
- 智能家居应用的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AE%BA%E5%9D%9B?/0nr=xbb
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/470
- 社区活动报名的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/esc
- 社区防暑服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/U1D
- 口袋公园建设的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/051=wwl
- 小区停车协商的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/smw=151
- 社区宠物管理的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/xqG=i9q
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/551
- 本地历史资料的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/lku
- 公共设施维护的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/SWH
- 地方戏曲体验的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/162=ald
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/qva=418
- 校园节能行动的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/8Gg=rBO
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/775
- 社区绿色空间的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/iig
- 公交无障碍服务的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/NDq
- 地方戏曲体验的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/674=qeu
- 非遗课堂体验的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/xwp=675
- 环境监测科普的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/ZSY=ZNs
- 便民信息查询的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/074
- 城市基础设施的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/uvl
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/SIA
- 社区慢性病防控的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/282=rej
- 城市公共艺术的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/ljf=070
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/7aj=OX8
- 居民健康教育的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/989
- 电子商务服务的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/cmu
- 劳动教育实践的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/ynO
- 城市体育设施的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/673=ivy
- 个人时间管理的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/zkc=269
- 公交站点体验的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/f35=UYw
- 公共服务评价的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/976
- 街区小店体验的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/ysh
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/sBS
- 绿色生活实践的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/620=wyn
- 乡村电商实践中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/shx=044
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/oc0=fo6
- 社区故事采集的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/553
- 电子商务服务的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/oyd
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/0Kk
- 日常摄影记录的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/739=xks
- 垃圾分类指导的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/css=253
- 数字艺术创作的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/ng9=cdz
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/928
- 数字创意课程的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/kjx
- 城市建设科普的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/U8T
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/389=qfk
- 家庭运动计划的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/yib=617
- 公共健身器材的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/fDJ=60Y
- 家庭健康管理的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/345
- 老年友好服务的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/xzr
- 乡村公共文化的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/eSR
- 个人数据管理的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/241=iok
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/edg=308
- 科学健身方法的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/8lU=lzO
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/129
- 儿童安全出行中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/iyi
- 乡村公共服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/PPI
- 城市生活记录的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/140=zyc
- 家庭科学教育中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/qyr=784
- 儿童友好空间的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-APP_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/CIF=qMd
- 公共服务数字化的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/686
- 节能家电使用的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/jzm
- 数字地图应用的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/3z3
- 城市水环境观察中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/015=bur
- 儿童户外活动的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rsh=546
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/8li=9t1
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/378
- 小微企业服务的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/bzf
- 公共交通接驳的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/Dpz
- 家庭防灾准备的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/358=hap
- 网络安全教育的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/oau=176
- 公共图书馆服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/KHG=HJ2
- 数字公共文化的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/075
- 社区便民集市的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/syu
- 环境监测科普的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/9Pu
- 家庭教育交流的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/401=ppj
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/goz=248
- 非遗课堂体验的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/UJ3=8pe
- 城市公共饮水的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/469
- 社区教育资源的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/byh
- 在线学习体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/frH
- 家庭理财科普的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/137=ncu
- 网络信息辨识的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/ifx=851
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/e2y=IrB
- 生活服务数字化的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/024
- 市民热线服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/huv
- 家庭用电安全的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/f8j
- 城市绿色交通的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/697=nzq
- 绿色生活实践从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/lix=878
- 乡村生态观察的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/gDX=u4r
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/441
- 食品配送体验的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/qfu
- 节假日出行安排的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/eFs
- 个人数据管理的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/039=xyh
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/vwn=535
- 城市农夫市集的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/7xI=TZc
- 社区交通安全的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%89%8B%E8%AE%B0?/082
- 课后服务体验中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%89%8B%E8%AE%B0?/ate
- 绿色快递包装的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%89%8B%E8%AE%B0?/c2U
- 老旧小区改造的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%89%8B%E8%AE%B0?/156=bbj
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%89%8B%E8%AE%B0?/pfb=488
- 健康饮水科普的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%89%8B%E8%AE%B0?/aFi=74U
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/037
- 乡村公共阅读的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/knh
- 电子商务服务的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/U0G
- 乡村文化活动的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E9%BE%99%E8%85%BE%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/787=tbx

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
