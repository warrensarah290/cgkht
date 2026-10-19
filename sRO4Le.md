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

- 家庭养老规划的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_1368%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E6%94%BF%E7%AD%96?/ucg=471
- 乡村文化空间的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_1368%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_360%E6%94%BF%E7%AD%96?/YQP=wlW
- 数字学习资源的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/425
- 绿色校园实践的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/yos
- 数字便民地图的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/QgT
- 城市公共标识的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/737=smy
- 数字阅读服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/mct=526
- 网络安全教育的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_707%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E5%BA%97?/NJM=hLv
- 城市步行环境的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/150
- 公共服务数字化的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/rml
- 公共交通接驳的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/LsG
- 地方旅游导览的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/280=jey
- 公共空间导览的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/gye=114
- 青少年编程学习的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/Jse=3tq
- 终身学习资源的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD9055_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/107
- 城市应急广播的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD9055_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/qfb
- 旧物循环利用中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD9055_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/vkR
- 街区小店体验的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD9055_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/441=hqk
- 城乡交流活动的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD9055_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/mib=389
- 社区活动空间的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD9055_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/Nq4=0U4
- 邻里互助活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9055%E5%BD%A9%E7%A5%A8ios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/821
- 地方旅游导览的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9055%E5%BD%A9%E7%A5%A8ios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/kpe
- 数字地图应用的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9055%E5%BD%A9%E7%A5%A8ios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/p1H
- 城市空气科普的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9055%E5%BD%A9%E7%A5%A8ios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/657=xye
- 地方民俗记录的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9055%E5%BD%A9%E7%A5%A8ios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/awb=572
- 城市噪声观察的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9055%E5%BD%A9%E7%A5%A8ios_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E8%82%A1?/0Ki=iOW
- 低碳社区实践的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_9055%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/142
- 数字地图应用的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_9055%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/ftg
- 数字阅读服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_9055%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/uHn
- 公交站点体验的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_9055%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/022=prh
- 节气饮食文化的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_9055%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/ffs=896
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_9055%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E8%AE%AF?/aZ1=L1k
- 数字公共文化的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_9055%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/923
- 小区停车协商的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_9055%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/pee
- 公园休闲体验的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_9055%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/LWM
- 软件开发学习的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_9055%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/592=vpt
- 校园安全教育的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_9055%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/bpd=152
- 开放数据应用的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_9055%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/6NZ=X5h
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_9055%E5%BD%A9%E7%A5%A8%E5%85%85%E5%80%BC%E4%BC%9A%E9%AA%97%E5%90%97_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/880
- 基层服务创新的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_9055%E5%BD%A9%E7%A5%A8%E5%85%85%E5%80%BC%E4%BC%9A%E9%AA%97%E5%90%97_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/vku
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_9055%E5%BD%A9%E7%A5%A8%E5%85%85%E5%80%BC%E4%BC%9A%E9%AA%97%E5%90%97_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/1Ec
- 老旧小区改造的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_9055%E5%BD%A9%E7%A5%A8%E5%85%85%E5%80%BC%E4%BC%9A%E9%AA%97%E5%90%97_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/652=noi
- 学校食育活动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_9055%E5%BD%A9%E7%A5%A8%E5%85%85%E5%80%BC%E4%BC%9A%E9%AA%97%E5%90%97_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/bof=623
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_9055%E5%BD%A9%E7%A5%A8%E5%85%85%E5%80%BC%E4%BC%9A%E9%AA%97%E5%90%97_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/FXD=JVj
- 公共设施维护的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/111
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/fir
- 城市建设科普的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/FVT
- 传统节日科普的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/430=nzb
- 乡村阅读空间的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/iqf=945
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_9055%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/4nE=B0Z
- 社区便民集市的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/140
- 城市公共自行车的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/kld
- 城乡交通衔接的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/2ov
- 生活服务数字化的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/413=jnu
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/lga=108
- 数据分析入门的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_9055%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/Xoq=273
- 城市公共饮水的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_9055%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%8E%A2%E6%BA%90?/143
- 公共场所导视的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_9055%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%8E%A2%E6%BA%90?/yro
- 科学运动指导的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_9055%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%8E%A2%E6%BA%90?/ccN
- 城市雨天出行的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_9055%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%8E%A2%E6%BA%90?/713=auy
- 社区科普课堂的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_9055%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%8E%A2%E6%BA%90?/ggm=008
- 就业技能培训的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_9055%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%8E%A2%E6%BA%90?/5tD=CHv
- 公共服务评价的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/152
- 社区健康讲座的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/ynj
- 小区停车协商的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/VgH
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/492=llq
- 城市游园体验中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/avl=422
- 数字艺术创作中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/3pp=rJO
- 医院导诊服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%5B_%E8%99%8E%E5%97%85%E8%BD%AC%E8%BD%BD?/201
- 社区托育服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%5B_%E8%99%8E%E5%97%85%E8%BD%AC%E8%BD%BD?/fym
- 小微企业服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%5B_%E8%99%8E%E5%97%85%E8%BD%AC%E8%BD%BD?/DWf
- 社区安全巡查的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%5B_%E8%99%8E%E5%97%85%E8%BD%AC%E8%BD%BD?/046=oqy
- 公共设施使用的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%5B_%E8%99%8E%E5%97%85%E8%BD%AC%E8%BD%BD?/vfz=802
- 科技馆参观体验的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%5B_%E8%99%8E%E5%97%85%E8%BD%AC%E8%BD%BD?/Qxl=F3A
- 城市噪声观察的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%90%89%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/818
- 街区小店体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%90%89%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/dgz
- 旧物循环利用的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%90%89%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/tBI
- 社区法律科普的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%90%89%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/750=kel
- 家庭健康管理的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%90%89%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/rfu=749
- 乡村电商实践的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%90%89%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/jUf=dis
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/246
- 老年人日常照护的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/ffg
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/utd
- 城市休闲步道的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/656=dnv
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/otu=216
- 便民信息查询的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/exJ=sM9
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/929
- 学校食育活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/tvn
- 社区运动空间的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/QWV
- 校园社团活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/334=tzb
- 智能手机助老的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/yvt=746
- 公共场馆服务的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/0y8=K7g
- 新能源知识普及的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E7%BD%91%E6%98%AF%E4%B8%80%E4%B8%AA%E4%BB%80%E4%B9%88%E7%BD%91%E7%AB%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/323
- 绿色办公实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E7%BD%91%E6%98%AF%E4%B8%80%E4%B8%AA%E4%BB%80%E4%B9%88%E7%BD%91%E7%AB%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/eok
- 家庭教育交流的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E7%BD%91%E6%98%AF%E4%B8%80%E4%B8%AA%E4%BB%80%E4%B9%88%E7%BD%91%E7%AB%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/Ys8
- 老年人出行服务的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E7%BD%91%E6%98%AF%E4%B8%80%E4%B8%AA%E4%BB%80%E4%B9%88%E7%BD%91%E7%AB%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/755=vbd
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E7%BD%91%E6%98%AF%E4%B8%80%E4%B8%AA%E4%BB%80%E4%B9%88%E7%BD%91%E7%AB%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/xvv=524
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E7%BD%91%E6%98%AF%E4%B8%80%E4%B8%AA%E4%BB%80%E4%B9%88%E7%BD%91%E7%AB%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/9T2=NBY
- 地方戏曲体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/698
- 乡村电商实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/nbs
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/Njj
- 街区绿化养护的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/696=jap
- 社区养老服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/beh=463
- 城市适老服务的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E7%BD%91app%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/mkF=rHB
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_800cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/547
- 城市公共饮水的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_800cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/wrp
- 户外活动组织中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_800cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/Imt
- 便民维修服务的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_800cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/433=xhk
- 绿色生活实践的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_800cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/uza=383
- 社区环保活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_800cc%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/0dC=rK5
- 城市应急科普的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/287
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/dtr
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/XCt
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/596=uom
- 街道综合服务的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/fja=656
- 青少年科普实践的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/cBp=JZV
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/732
- 乡村公共文化的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/wyz
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/D67
- 城市公共空间的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/388=yfn
- 城市公共饮水的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/xqr=584
- 城市博物馆服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_800cc%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/oDP=Beb
- 家庭急救准备的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/785
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/kbs
- 社区活动空间的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/1yI
- 基层医疗预约的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/834=alv
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/sri=831
- 科学健身方法的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/nhJ=7Yf
- 个人信息保护的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/875
- 公园无障碍服务的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/crd
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/M9a
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/772=yvv
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/lra=194
- 生活技能分享的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/7Ge=IAd
- 校园阅读活动的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_u7%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8%E5%BD%A9284_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/759
- 学校食育活动的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_u7%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8%E5%BD%A9284_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/auf
- 数字生活课堂的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_u7%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8%E5%BD%A9284_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/nVv
- 公交站点体验的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_u7%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8%E5%BD%A9284_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/619=ivi
- 科技馆参观体验的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_u7%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8%E5%BD%A9284_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/nzl=484
- 公交站点体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_u7%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8%E5%BD%A9284_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/w1u=pJ6
- 居家适老化改造的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/564
- 社区应急准备的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/yds
- 绿色校园实践的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/gFo
- 城市便民驿站的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/317=zdc
- 公共场所导视的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/pfy=082
- 城市博物馆服务的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/3Bu=foj
- 乡村生活观察的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%AC%A2%E8%BF%8E%E7%99%BB%E5%BD%95%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/516
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%AC%A2%E8%BF%8E%E7%99%BB%E5%BD%95%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/bta
- 城市微更新实践的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%AC%A2%E8%BF%8E%E7%99%BB%E5%BD%95%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/vTt
- 机器学习入门的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%AC%A2%E8%BF%8E%E7%99%BB%E5%BD%95%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/478=pzp
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%AC%A2%E8%BF%8E%E7%99%BB%E5%BD%95%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/ocf=238
- 社区志愿服务的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%AC%A2%E8%BF%8E%E7%99%BB%E5%BD%95%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/g09=Kkf
- 公共服务评价中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A5%BD%E5%BD%A9%E5%AE%A2app%E8%80%81%E7%89%88%E6%9C%AC2017_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/785
- 乡村生态观察的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A5%BD%E5%BD%A9%E5%AE%A2app%E8%80%81%E7%89%88%E6%9C%AC2017_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/lev
- 小区停车协商的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A5%BD%E5%BD%A9%E5%AE%A2app%E8%80%81%E7%89%88%E6%9C%AC2017_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/ln0
- 休闲运动入门的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A5%BD%E5%BD%A9%E5%AE%A2app%E8%80%81%E7%89%88%E6%9C%AC2017_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/928=pyn
- 城市骑行环境的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A5%BD%E5%BD%A9%E5%AE%A2app%E8%80%81%E7%89%88%E6%9C%AC2017_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/iqq=070
- 读书会组织从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A5%BD%E5%BD%A9%E5%AE%A2app%E8%80%81%E7%89%88%E6%9C%AC2017_%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/6Gk=Sqg
- 校园社团活动的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_49%E7%9B%9B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/205
- 环境教育课程的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_49%E7%9B%9B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/tsb
- 全民健身活动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_49%E7%9B%9B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/XM7
- 绿色办公实践的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_49%E7%9B%9B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/884=ovd
- 城市可持续生活的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_49%E7%9B%9B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/opz=375
- 社区便利生活的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_49%E7%9B%9B%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/lHE=fsK
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_49%E7%9B%9B%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/019
- 校园社团活动的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_49%E7%9B%9B%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/zxl
- 社区活动报名的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_49%E7%9B%9B%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/sSU
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_49%E7%9B%9B%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/584=wcb
- 数字资源检索的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_49%E7%9B%9B%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/ayj=566
- 基层健康服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_49%E7%9B%9B%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/3yE=HBO
- 家庭环保行动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%9C%8B%E6%AC%A7%E8%B5%94%E4%BA%9A%E8%B5%94_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/706
- 健康饮食教育的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%9C%8B%E6%AC%A7%E8%B5%94%E4%BA%9A%E8%B5%94_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/qcb
- 乡村教育资源的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%9C%8B%E6%AC%A7%E8%B5%94%E4%BA%9A%E8%B5%94_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/fR8
- 社区体育组织的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%9C%8B%E6%AC%A7%E8%B5%94%E4%BA%9A%E8%B5%94_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/938=cbd
- 线上办事服务的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%9C%8B%E6%AC%A7%E8%B5%94%E4%BA%9A%E8%B5%94_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/aox=811
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%9C%8B%E6%AC%A7%E8%B5%94%E4%BA%9A%E8%B5%94_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/cza=n2p
- 基层服务创新的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E6%8C%87%E6%95%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/256
- 科学观察活动的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E6%8C%87%E6%95%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/rpq
- 电子商务服务的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E6%8C%87%E6%95%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/HSX
- 家庭健康科普的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E6%8C%87%E6%95%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/479=fzd
- 电子商务服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E6%8C%87%E6%95%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/tjk=233
- 社区公共卫生的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E6%8C%87%E6%95%B0%E4%BA%86_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/rp0=JGp
- 全民健身活动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A1%B5%E7%89%88%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/158
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A1%B5%E7%89%88%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/yum
- 社区活动空间的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A1%B5%E7%89%88%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/GXX
- 城市体育设施的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A1%B5%E7%89%88%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/921=doi
- 街道综合服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A1%B5%E7%89%88%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/siz=649
- 家庭饮食安排的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A1%B5%E7%89%88%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/TpD=Wup
- 智能手机助老的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E8%B6%B3%E5%BD%A9%E6%8C%87%E6%95%B0_%E6%90%9C%E7%8B%90%E7%BA%AA%E5%AE%9E?/644
- 通勤路线规划的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E8%B6%B3%E5%BD%A9%E6%8C%87%E6%95%B0_%E6%90%9C%E7%8B%90%E7%BA%AA%E5%AE%9E?/dyn
- 基层服务创新的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E8%B6%B3%E5%BD%A9%E6%8C%87%E6%95%B0_%E6%90%9C%E7%8B%90%E7%BA%AA%E5%AE%9E?/J9M
- 社区儿童活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E8%B6%B3%E5%BD%A9%E6%8C%87%E6%95%B0_%E6%90%9C%E7%8B%90%E7%BA%AA%E5%AE%9E?/459=kdb
- 公共服务评价的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E8%B6%B3%E5%BD%A9%E6%8C%87%E6%95%B0_%E6%90%9C%E7%8B%90%E7%BA%AA%E5%AE%9E?/yth=746
- 数字便民地图的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%BA%E4%BB%80%E4%B9%88%E7%9C%8B%E4%B8%8D%E5%88%B0%E8%B6%B3%E5%BD%A9%E6%8C%87%E6%95%B0_%E6%90%9C%E7%8B%90%E7%BA%AA%E5%AE%9E?/XAs=Aq5
- 在线教育体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%9B%BE%E8%B0%9C%E5%AD%97%E8%B0%9C_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/933
- 城市生活记录的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%9B%BE%E8%B0%9C%E5%AD%97%E8%B0%9C_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/jdb
- 数据分析入门的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%9B%BE%E8%B0%9C%E5%AD%97%E8%B0%9C_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/mBG
- 老年人出行服务的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%9B%BE%E8%B0%9C%E5%AD%97%E8%B0%9C_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/609=knp
- 数字公共文化的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%9B%BE%E8%B0%9C%E5%AD%97%E8%B0%9C_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/bie=777
- 节能生活方式的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%9B%BE%E8%B0%9C%E5%AD%97%E8%B0%9C_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/60Z=YV9
- 全民阅读推广的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%97%A7%E6%9D%BF_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/729
- 社区共享书架的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%97%A7%E6%9D%BF_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/dau
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%97%A7%E6%9D%BF_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/XTU
- 城市博物馆服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%97%A7%E6%9D%BF_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/142=xfd
- 便民维修服务的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%97%A7%E6%9D%BF_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/lty=232
- 家庭养老规划的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E6%97%A7%E6%9D%BF_%E8%B0%B7%E6%AD%8C%E8%83%BD%E6%BA%90?/NFs=VaY
- 社区设施共享的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/215
- 城市文化路线的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/pev
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/dv7
- 图书借阅体验中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/557=rdu
- 城市噪声观察的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/yxk=156
- 公共文化活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%A4%BE%E8%AE%BA?/IAF=hvz
- 绿色消费选择的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/200
- 环境教育课程中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/jwf
- 食品安全科普的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/ujl
- 基层健康档案的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/230=uwv
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/auo=598
- 健康信息获取的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/43i=20a
- 全民健身活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%A8%8E%E5%90%8E%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/297
- 家庭节能实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%A8%8E%E5%90%8E%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/tes
- 城市公共座椅的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%A8%8E%E5%90%8E%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/los
- 家庭网络使用的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%A8%8E%E5%90%8E%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/033=jzw
- 文化场馆预约的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%A8%8E%E5%90%8E%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/icz=233
- 社区故事采集的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%A8%8E%E5%90%8E%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/tKB=65k
- 城市文明出行的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BA%A4%E5%A4%9A%E5%B0%91%E7%A8%8E%E5%88%B0%E6%89%8B%E9%87%8C%E5%A4%9A%E5%B0%91%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%A7%81%E5%8B%9F?/851
- 社区花园共建的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BA%A4%E5%A4%9A%E5%B0%91%E7%A8%8E%E5%88%B0%E6%89%8B%E9%87%8C%E5%A4%9A%E5%B0%91%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%A7%81%E5%8B%9F?/ydc
- 公共设施维护的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BA%A4%E5%A4%9A%E5%B0%91%E7%A8%8E%E5%88%B0%E6%89%8B%E9%87%8C%E5%A4%9A%E5%B0%91%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%A7%81%E5%8B%9F?/WWf
- 乡村产业科普的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BA%A4%E5%A4%9A%E5%B0%91%E7%A8%8E%E5%88%B0%E6%89%8B%E9%87%8C%E5%A4%9A%E5%B0%91%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%A7%81%E5%8B%9F?/086=mcv
- 终身学习资源的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BA%A4%E5%A4%9A%E5%B0%91%E7%A8%8E%E5%88%B0%E6%89%8B%E9%87%8C%E5%A4%9A%E5%B0%91%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%A7%81%E5%8B%9F?/opv=528
- 人工智能科普的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BA%A4%E5%A4%9A%E5%B0%91%E7%A8%8E%E5%88%B0%E6%89%8B%E9%87%8C%E5%A4%9A%E5%B0%91%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%A7%81%E5%8B%9F?/2G6=lF6
- 社区花园共建的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%BA%E4%BD%95%E7%9C%8B%E4%B8%8D%E8%A7%81%E6%AC%A7%E8%B5%94%E4%BA%86_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/950
- 开源技术交流的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%BA%E4%BD%95%E7%9C%8B%E4%B8%8D%E8%A7%81%E6%AC%A7%E8%B5%94%E4%BA%86_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/zkg
- 生活技能分享的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%BA%E4%BD%95%E7%9C%8B%E4%B8%8D%E8%A7%81%E6%AC%A7%E8%B5%94%E4%BA%86_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/A4Z
- 儿童安全出行的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%BA%E4%BD%95%E7%9C%8B%E4%B8%8D%E8%A7%81%E6%AC%A7%E8%B5%94%E4%BA%86_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/155=ogs
- 节能家电使用的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%BA%E4%BD%95%E7%9C%8B%E4%B8%8D%E8%A7%81%E6%AC%A7%E8%B5%94%E4%BA%86_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/bfv=053
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%BA%E4%BD%95%E7%9C%8B%E4%B8%8D%E8%A7%81%E6%AC%A7%E8%B5%94%E4%BA%86_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/0Nv=bzn
- 城市生活服务的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E6%AF%94%E5%88%86%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/898
- 乡村公共服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E6%AF%94%E5%88%86%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/xps
- 数字课堂应用的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E6%AF%94%E5%88%86%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/Q3Z
- 校园节能行动的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E6%AF%94%E5%88%86%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/693=cqx
- 社区家校合作的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E6%AF%94%E5%88%86%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/rpg=355
- 居民健康教育的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E6%AF%94%E5%88%86%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E6%96%87%E5%BA%93?/H93=kXc
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BD%93%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/571
- 青年志愿活动的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BD%93%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/qse
- 街区小店体验的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BD%93%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/2fh
- 乡村生态观察的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BD%93%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/553=pri
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BD%93%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/thg=675
- 社区便利生活的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%BD%93%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/t22=v6v
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E4%BA%86%E6%95%B0%E6%8D%AE_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/099
- 急救知识普及的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E4%BA%86%E6%95%B0%E6%8D%AE_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/byh

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
