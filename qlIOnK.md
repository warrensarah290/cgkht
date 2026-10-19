# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 小区电梯维护的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-APP_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/rxu=702
- 公共空间休憩的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-APP_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/k7q=DTZ
- 药品使用科普的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/583
- 传统节日科普的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/byr
- 农贸市场环境中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/j1f
- 城市公共厕所的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/856=rpl
- 城市基础设施的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/cmi=726
- 便民维修服务的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/7j5=U9u
- 儿童友好空间的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/847
- 家庭安全提示的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/jqn
- 课后服务体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/X61
- 老年运动活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/485=peo
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/xrk=127
- 社区便民集市的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/589=uLC
- 社区便利生活的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/676
- 乡村生态观察的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/uiv
- 线上办事服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/10v
- 地方民俗记录的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/564=yvz
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/wzh=729
- 城市公共饮水的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/Xw2=btq
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/038
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/dlk
- 生活垃圾回收的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/SHj
- 市民意见收集的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/389=isj
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/dcz=359
- 农业科普体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/GRf=EfZ
- 乡村电商实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/992
- 线上阅读资源的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/acr
- 儿童安全出行的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/xj5
- 乡村文化空间的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/497=zax
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/ubt=747
- 环境教育课程中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/T3e=Eyl
- 社区慢性病防控的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/600
- 城市步行环境的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/mjl
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/uBv
- 青年志愿活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/890=zuw
- 邻里共享空间的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/ciq=761
- 智能家居应用的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/nVV=xac
- 公共场所导视的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/700
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/ply
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/cZS
- 城市应急科普的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/950=alg
- 市民意见收集的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/ydd=132
- 社区安全巡查的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8E%BF%E5%9F%9F?/fhl=fbb
- 家庭饮食安排的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/081
- 数字学习资源的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/now
- 传统手工艺体验的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/FKN
- 数字生活课堂的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/545=nsk
- 口袋公园建设的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/hor=116
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%BD%E8%BD%A6?/Grv=8v1
- 职业技能学习的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/656
- 乡村阅读空间的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/jep
- 创业经验分享的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/IRp
- 线上办事服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/107=hco
- 青年就业服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/lrh=600
- 环境教育课程的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/zrg=uSS
- 旧物循环利用的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/429
- 社区商业活力的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/xmk
- 社区养老服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/yaj
- 公共空间安全的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/019=ocj
- 城市便民驿站的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/lpo=478
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/0pg=UDL
- 气象科普传播的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/447
- 便民信息查询的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/nek
- 城市运动公园的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/MEV
- 电子商务服务的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/767=zfa
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/fhd=612
- 灵活就业交流的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/9Dd=Pkg
- 家庭环保行动的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/687
- 环境教育课程的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/jan
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/U6s
- 公共空间休憩的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/928=gap
- 远程协作工具的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/wsu=633
- 社区故事采集的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/Wgy=JXj
- 城市社区治理的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/627
- 基层服务创新的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/pbz
- 公共设施使用的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/t9z
- 社区托育服务的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/284=hej
- 城市基础设施的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/ovp=893
- 社区慢性病防控的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B3%95%E6%B2%BB?/SXT=nuP
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/429
- 垃圾分类指导的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/mwl
- 公共场馆服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/sK4
- 农业科普体验的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/997=niy
- 公共设施使用的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/arl=318
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/SYD=b2V
- 医院导诊服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/785
- 社区文化传播的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/bts
- 城市文明实践的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/ZYM
- 社区协商议事中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/455=jqr
- 社区家校合作的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/bkn=126
- 家庭饮食安排的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%9B%B2%E8%89%BA?/MRz=1qX
- 城市绿色交通的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/870
- 数字便民地图的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/nzz
- 社区儿童活动的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/lql
- 儿童户外活动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/348=bpk
- 智慧停车服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/gco=919
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/gkJ=Oyl
- 智能家居应用的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/443
- 远程协作工具的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/ksh
- 无障碍信息设计的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/UHU
- 社区防暑服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/745=ugz
- 街道综合服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/qxa=665
- 社区知识分享的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/C0c=lCG
- 公共空间休憩的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/506
- 家庭安全提示的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/ytf
- 小区停车协商的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/Vr3
- 农业科普体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/477=zzm
- 急救知识普及的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/ngr=315
- 城市公共饮水的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/OAm=Am9
- 城市树木认养的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/219
- 城市应急科普的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/npq
- 安全出行教育中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/omU
- 老年友好服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/880=xgs
- 科学信息获取的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/hqd=258
- 老年智能设备的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/0vO=ayZ
- 社区商业活力的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/628
- 本地历史资料的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/mmg
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/4rx
- 数字学习资源的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/227=ckl
- 乡村生活观察的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/hbb=621
- 地方美食文化中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%B9%A6%E7%94%BB?/0Ae=H0N
- 节能生活方式的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/327
- 公共服务指南的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/lkz
- 公共服务沟通的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/i7C
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/669=jfn
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/yek=380
- 老年数字阅读的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/cds=8Mk
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/125
- 乡村产业科普的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/gre
- 街区绿化养护的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/DmH
- 公共文化活动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/909=ytw
- 市民热线服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/olx=499
- 街道综合服务的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/xG3=rqa
- 数字政务体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/619
- 地方文化传播的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/avk
- 绿色生活实践的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/4i0
- 公共服务数字化的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/093=cyq
- 地方旅游导览的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/xie=207
- 儿童友好空间的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/rhz=WmS
- 校园安全教育的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/630
- 城市步行环境的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/mdm
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/5qp
- 城市慢跑路线的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/215=huu
- 休闲运动入门的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/tkp=533
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/gJ2=A4H
- 农业科普体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/248
- 青年职业探索的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/udn
- 志愿服务平台的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/iIs
- 城市展览体验的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/838=txj
- 非遗体验活动的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/pyv=809
- 老年智能设备的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/ILr=j1N
- 城市步行友好的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/506
- 社区花园共建的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/fxj
- 城市夜间生活的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/2Hr
- 社区信息发布的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/199=abo
- 灵活就业交流的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/spd=473
- 绿色出行服务的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/Ejz=zzk
- 消防知识宣传的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/996
- 老旧小区改造的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/jzq
- 医院导诊服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/iNG
- 城市社区治理的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/424=bqq
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/yst=427
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%97%85%E6%B8%B8?/Kti=Xex
- 节假日出行安排的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/333
- 社区环保活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/owx
- 社区体育组织的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/PPw
- 市民热线服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/090=ceu
- 生活技能分享的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/iyn=757
- 职业技能学习的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/uHP=ZFA
- 公交站点体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/090
- 应急物资管理的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/ubs
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/uyE
- 社区便利生活的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/858=ujx
- 在线学习体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/kbi=563
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/U7o=7Mj
- 社区手工活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/705
- 家庭志愿活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/jkc
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/gDS
- 城市生活服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/381=zca
- 数字学习资源的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/siz=444
- 食品安全科普的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/JcF=CLi
- 公共卫生宣传的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/646
- 智能家居应用的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/fcc
- 青少年编程学习的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/bSk
- 公共文化活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/623=ajf
- 社区修缮行动的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/xua=467
- 数字政务体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/cqm=RkD
- 学校食育活动的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/330
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/bwk
- 家庭陪伴活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/vBy
- 公园休闲体验的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/927=yep
- 物业服务沟通的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/zvp=196
- 社区绿色空间的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/FpB=aiP
- 城市文明出行的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/226
- 社区故事采集的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/mpc
- 学校食育活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/IBB
- 公园无障碍服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/553=fvt
- 跨代沟通活动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/cpf=745
- 生活垃圾减量的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/DgF=Wln
- 社区心理支持的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/105
- 健康饮水科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/cnv
- 人工智能科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/H9J
- 社区志愿服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/684=lpz
- 志愿服务平台的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/axd=933
- 软件开发学习的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/2nH=bPN
- 城市公共厕所的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/343
- 绿色消费选择的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/grc
- 乡村文化活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/aiL
- 社区便民服务的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/452=wky
- 社区邻里服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/dyl=424
- 家庭网络使用的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/yUn=d3w
- 光伏知识科普的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/914
- 儿童户外活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/iww
- 社区学习活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/EOn
- 本地消费场景的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/733=hks
- 节假日出行安排的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/ofb=065
- 城市基础设施的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/TFv=yW6
- 社区健康讲座的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/252
- 城市适老服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/uke
- 个人数据管理的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/ZuW
- 社区活动空间的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/193=qsq
- 城市基础设施的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/cjb=790
- 校园社团活动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/qk6=rLg
- 节能家电使用的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/408
- 在线学习体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/ohy
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/01E
- 志愿服务平台的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/210=mmm
- 社区共享书架的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/hkg=626
- 家庭理财科普的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/jW1=LuJ
- 家庭健康科普的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/587
- 乡村阅读活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/lrj
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/f14
- 家庭养老规划的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/445=ogf
- 科学观察活动中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/mzo=307
- 市民意见收集的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/L7c=xJY
- 数字创作工具的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/014
- 志愿服务平台的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/yst
- 青少年科技社团从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/WQW
- 社区学习活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/020=krk
- 公共服务沟通的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/nxc=331
- 公共服务指南的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/VVX=mNg
- 家庭照护支持的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/925
- 城市文化路线的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/ucx
- 城乡公共服务的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/YEA
- 志愿者培训交流的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/328=vzd
- 城市水环境观察的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/hpx=430
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/vP6=f3R
- 家庭环保习惯的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/756
- 家庭照护支持的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E7%B2%BE%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/hni

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
