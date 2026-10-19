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

- 街道综合服务的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365-APP_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/848
- 街区小店体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365-APP_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/rup
- 社区共享书架的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365-APP_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/jVW
- 本地旅行体验的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365-APP_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/927=mmj
- 城市共享单车的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365-APP_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/znn=557
- 人工智能科普的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8365-APP_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/SKT=XyX
- 便民服务窗口的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/979
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/ttc
- 儿童运动体验的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/PcX
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/597=llc
- 乡村生态旅游的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/agx=268
- 机器学习入门的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/Ony=l0O
- 数字便民地图的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/717
- 街道综合服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/ynu
- 个人时间管理的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/ugN
- 生活技能分享的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/921=hym
- 乡村产业科普的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/yll=398
- 健康饮食教育的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/0xQ=yON
- 地方旅游导览的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8365-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/907
- 城市适老服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8365-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/nup
- 数字资源检索的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8365-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/L7m
- 数据分析入门中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8365-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/787=izf
- 老年数字阅读的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8365-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/vjz=899
- 农业科普体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8365-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/Y3e=YRj
- 全民阅读推广的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/647
- 城市应急广播的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/stq
- 基层健康档案的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/ImN
- 老旧小区改造的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/702=ocb
- 社区知识分享的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/pbs=065
- 社区协商议事的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/XL0=agG
- 社区共享书架的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/900
- 健康饮食教育的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/xay
- 城市公共厕所的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/Uvc
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/454=pwk
- 数字支付体验的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/miy=072
- 地方民俗记录的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B1%87%E5%B8%82?/ysO=l8I
- 家庭节能实践的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/944
- 开放式学习空间的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/zuv
- 居家适老化改造的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/wQl
- 城乡交通衔接的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/488=veg
- 创业经验分享的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/vth=983
- 数字艺术创作的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/43F=1Vi
- 社区体育组织的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/241
- 数字学习资源的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/rdl
- 家庭饮食安排的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/qnz
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/558=uyw
- 城市地名文化中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/itv=646
- 社区商业活力的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/TS9=EXU
- 乡村公共文化的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/225
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/yah
- 农产品消费体验的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/gRD
- 城市空气科普的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/370=sjv
- 网络安全教育的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/uhx=952
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/zR4=Zbf
- 环境监测科普的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/532
- 科学教育活动的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/kmh
- 药品使用科普的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/85b
- 社区共享书架的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/455=myv
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/cdg=854
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8365-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/R6f=gRU
- 数字公共文化的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%98%E6%96%B9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/645
- 社区停车服务的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%98%E6%96%B9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/joh
- 家庭运动计划的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%98%E6%96%B9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/lw1
- 在线教育体验的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%98%E6%96%B9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/963=zgc
- 街区道路维护的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%98%E6%96%B9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/lnn=613
- 城市应急科普的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8365-%E5%AE%98%E6%96%B9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/iQq=xQc
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8777-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/390
- 乡村产业科普的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8777-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/hzt
- 节日文化体验的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8777-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/Dp2
- 信息无障碍体验的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8777-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/512=ido
- 人工智能科普的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8777-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/tqe=690
- 老年友好服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8777-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/PFp=O7X
- 无障碍出行的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/785
- 公交无障碍服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/bqn
- 乡村公共文化的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/yYu
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/432=dyr
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/otx=140
- 健康信息获取的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/iWJ=CvJ
- 公共空间照明的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/237
- 社区运动空间的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/fji
- 公园休闲体验的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/7Fv
- 城市休闲步道的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/435=xyq
- 网络安全教育的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/oip=398
- 医院导诊服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/DuV=BHB
- 公共健身器材的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/788
- 老年友好服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/sgy
- 社区志愿服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/3sI
- 老年人文化生活的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/190=mtw
- 城市骑行环境的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/yyd=746
- 科学健身方法的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/nvG=iXR
- 城市可持续生活的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/720
- 绿色校园实践的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/kqo
- 家庭照护支持的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/yLi
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/569=eqv
- 科普展览体验的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/guh=710
- 儿童户外活动的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/QGv=Gwk
- 城市微更新实践的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/747
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/twa
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/fOM
- 数字政务体验的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/957=uhf
- 社区慢性病防控的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/xaf=792
- 城市公共饮水的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95welcome_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/3OV=NL5
- 学校体育活动的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/117
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/gsj
- 城市水环境观察的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/0at
- 数字政务体验的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/132=wgs
- 城乡公共服务的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/eye=929
- 数字课堂应用的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/Ezi=Dfc
- 节假日出行安排的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/383
- 数字学习资源的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/lmv
- 学校体育活动的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/vAv
- 图书馆数字服务的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/628=pwe
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/ugg=026
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/dw1=dey
- 街道综合服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/083
- 小区公共照明的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/rmo
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/tj5
- 公交站点体验的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/710=yef
- 老年学习活动的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/suy=954
- 绿色建筑理念的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/4he=cmq
- 社区设施共享的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/055
- 公共空间导览的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/wmr
- 职业技能学习的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/GKo
- 社区便利生活的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/960=hgm
- 公共服务咨询的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/wzu=449
- 社区快递服务的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8777-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/biC=i89
- 社区科普课堂的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E4%B8%8B%E8%BD%BD_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/132
- 城市夜间照明的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E4%B8%8B%E8%BD%BD_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/mvx
- 社区绿色空间的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E4%B8%8B%E8%BD%BD_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/fZL
- 公园无障碍服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E4%B8%8B%E8%BD%BD_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/464=ukv
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E4%B8%8B%E8%BD%BD_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/rjm=101
- 青少年科技社团的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E4%B8%8B%E8%BD%BD_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/80l=Dg9
- 生活服务数字化的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/556
- 家庭健康管理中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/djn
- 社区知识分享的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/xR4
- 家庭食品保存的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/357=gjr
- 乡村生态观察的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/zfg=124
- 社区便利生活的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/L1W=Qwk
- 旧物循环利用的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/892
- 乡村产业科普的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/qmo
- 地方美食文化的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/Q6B
- 绿色校园实践的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/946=xqv
- 本地历史资料的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/adi=396
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8777-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/rq0=sDS
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/028
- 公共空间休憩的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/edq
- 科普展览体验的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/2D5
- 青年职业探索的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/266=kpu
- 节能家电使用的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/qgq=121
- 运动安全知识的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/9L0=9ii
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/476
- 城市适老服务的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/wjv
- 社区故事采集的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/P5e
- 公共空间休憩的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/094=hfx
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/gso=913
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8777-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/qRr=z0G
- 终身学习资源的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/645
- 开源技术交流的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/usc
- 城市噪声观察的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/SZS
- 信息无障碍体验的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/434=qri
- 智能家居应用的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/pya=222
- 市民意见收集的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%B0%E8%AF%BB?/bR7=1Qn
- 公共服务沟通的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/365
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/afa
- 生成式工具使用的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/IwQ
- 家庭安全提示的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/915=wrp
- 公共服务沟通的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/xtu=475
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8777-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/zqk=G9L
- 城市绿色交通的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8777-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/038
- 创业经验分享的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8777-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/ayb
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8777-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/tdC
- 城市社区治理的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8777-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/362=zqo
- 城市生活记录的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8777-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/rve=561
- 青少年科普实践的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8777-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/Oor=sQb
- 街道综合服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/817
- 社区公共餐饮的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/osm
- 家庭急救准备的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/IFy
- 家庭理财科普的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/367=xhf
- 城市公共座椅的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/yfg=195
- 生活技能分享的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/n4j=zzM
- 街区更新实践中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/160
- 社区故事采集的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/myc
- 数字便民地图的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/eH5
- 社区商业活力的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/599=qbu
- 科技馆参观体验的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/iao=266
- 学校体育活动的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8777-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/Wmw=3ZV
- 青年职业探索的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/093
- 城市游园体验的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/lvx
- 智能家居应用的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/5J1
- 老年人文化生活的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/944=dbz
- 地方旅游导览的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/vlf=850
- 公共场所导视的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8777-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/5N2=fkp
- 儿童友好空间的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/804
- 基层服务创新中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/uyz
- 居家适老化改造中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/Ku1
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/378=hli
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/hjg=489
- 数字地图应用的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/JAP=mdc
- 小区电梯维护的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/065
- 城市建设科普的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/dib
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/XTn
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/808=uem
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/kve=585
- 数字阅读服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/npp=Ghl
- 校园阅读活动的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%9E%E6%94%BE?/662
- 城市社区治理的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%9E%E6%94%BE?/nua
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%9E%E6%94%BE?/pn5
- 公共服务沟通的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%9E%E6%94%BE?/256=xis
- 公共场所导视的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%9E%E6%94%BE?/qeu=149
- 公共卫生设施的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%9E%E6%94%BE?/7Xp=aJj
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/448
- 社区设施共享的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/nro
- 小微企业服务的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/oHc
- 青少年户外教育的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/757=mih
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/ucp=873
- 便民维修服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/w68=cuH
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/053
- 社区宠物管理的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/yxx
- 智能手机助老的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/hWm
- 城市夜间照明的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/220=vpi
- 街道综合服务的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/tvz=757
- 街头绿植养护的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/Uew=KHp
- 便民服务窗口的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/446
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/lad
- 社区安全巡查的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/8YN
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/435=hyp
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/awi=170
- 社区生活指南的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/wrc=ZF7
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%AE%B6%E5%B1%85?/297
- 城市体育设施的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%AE%B6%E5%B1%85?/qxt
- 城市运动公园的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%AE%B6%E5%B1%85?/R8r
- 老旧小区改造的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%AE%B6%E5%B1%85?/090=qyn
- 城市共享单车的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%AE%B6%E5%B1%85?/ddn=843
- 灵活就业交流的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%AE%B6%E5%B1%85?/ooo=tCG
- 公共空间导览的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/301
- 邻里互助活动的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ucq
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/NmK
- 儿童运动体验的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/236=ukb
- 社区停车服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/xaw=374
- 城市骑行环境的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/k83=PGs
- 科学信息获取的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/825
- 便民服务地图的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/hru
- 小微企业服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/82x
- 社区健康讲座的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/416=qgd
- 社区修缮行动的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/fbp=734
- 节能家电使用的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/vGL=07f
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/460
- 公共服务咨询的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/wcf
- 城市公共空间的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/gt7
- 家庭消费规划的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/203=tlw

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
