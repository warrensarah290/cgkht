# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 城乡交流活动的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%9B%BE%E7%89%87_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/khg=988
- 传统节日科普的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%9B%BE%E7%89%87_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/mOm=hZt
- 绿色快递包装的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/857
- 城乡交流活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/ysz
- 绿色办公实践的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/ZlM
- 数字学习资源的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/291=fnh
- 个人时间管理中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/lgq=650
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/xNF=Cwi
- 青少年科普实践的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/641
- 学校体育活动的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/mpl
- 开源技术交流的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/lUD
- 社区法律科普的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/982=edw
- 文化场馆预约的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/wdf=876
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/VJK=iaX
- 社区设施共享的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/682
- 无障碍出行的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/vra
- 社区便民集市的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/UJR
- 网络信息辨识的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/510=uaw
- 校园阅读活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/pog=748
- 终身学习资源的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/f6p=dUM
- 健康步道使用的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/828
- 乡村电商实践的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/por
- 基层健康服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/xgy
- 社区协商议事中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/977=vgk
- 通勤路线规划的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/uin=805
- 社区艺术活动的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/HeZ=gDg
- 社区生活指南中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/189
- 医院导诊服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/rwm
- 地方美食文化的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/DdZ
- 城市博物馆活动的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/049=dmm
- 公共服务数字化的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/vda=809
- 地方民俗记录的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/v9R=6SH
- 节能家电使用的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/251
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/imz
- 无障碍信息设计的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/KbK
- 社区交通安全的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/969=fks
- 城市骑行环境的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/zak=688
- 地方文化传播的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/Upb=dWZ
- 社区休闲设施的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/178
- 智能手机助老的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/yua
- 老年人日常照护的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/Vir
- 居家防滑改造的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/465=ykr
- 网络安全教育的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/oqs=202
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E7%99%BE%E5%BA%A6%E6%A1%A3%E6%A1%88?/rJG=9xk
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/927
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/bjq
- 校园阅读活动的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/9LR
- 城市文明出行的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/605=lcw
- 青少年科普实践的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/lar=213
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/quT=qP9
- 口袋公园建设的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/791
- 小微企业服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/lww
- 城市应急科普的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/Egd
- 公共场所导视的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/381=bds
- 家庭节能实践的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/ngd=150
- 城市生活服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/J2w=dzh
- 社区信息发布中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/080
- 通勤路线规划的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/nlr
- 全民健身活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/2YO
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/634=daw
- 乡村文化空间的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/wce=699
- 城市运动公园的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/tKq=HUP
- 社区志愿服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/367
- 社区共享书架的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/pdp
- 传统手工艺体验的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/jtA
- 农业科普体验的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/977=xwn
- 社区花园共建的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/xnf=376
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/ley=rNK
- 公共服务评价的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/618
- 居家适老化改造的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/zsi
- 休闲运动入门的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/akt
- 街区道路维护的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/558=dso
- 城市公共厕所的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/uxb=183
- 城市慢行系统的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/9ei=KRb
- 社区环保活动的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/772
- 家庭消费规划的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/vmf
- 数据分析入门的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/PVA
- 城市可持续生活的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/496=bse
- 口袋公园建设的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/bri=078
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/22c=1Np
- 文明养宠科普的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/073
- 邻里互助活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/rmp
- 职业技能学习的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/kQH
- 食品安全科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/959=vdm
- 社区活动策划的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/wzu=275
- 乡村公共服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/xiZ=8Z2
- 社区知识分享的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/670
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/udi
- 社区快递服务的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/5Fs
- 社区交通安全的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/842=xbe
- 绿色消费选择的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/rjh=991
- 公共场所导视的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/5cA=6lq
- 家庭安全提示的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/947
- 社区绿色空间的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/mbn
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/dde
- 城市步行环境中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/499=fjz
- 节约用水实践的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/pcw=625
- 全民健身活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/OX3=2h0
- 本地旅行体验的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_360%E9%9F%B3%E4%B9%90?/660
- 老年人出行服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_360%E9%9F%B3%E4%B9%90?/mqg
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_360%E9%9F%B3%E4%B9%90?/yo0
- 青少年科技社团从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_360%E9%9F%B3%E4%B9%90?/290=bhl
- 城市应急广播的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_360%E9%9F%B3%E4%B9%90?/cgy=343
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_360%E9%9F%B3%E4%B9%90?/DaK=D2r
- 社区知识分享的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_360%E6%B8%AF%E8%82%A1?/658
- 城市地名文化的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_360%E6%B8%AF%E8%82%A1?/vuz
- 公共设施维护的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_360%E6%B8%AF%E8%82%A1?/i5t
- 家庭安全提示的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_360%E6%B8%AF%E8%82%A1?/083=udd
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_360%E6%B8%AF%E8%82%A1?/siu=973
- 周末休闲规划的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_360%E6%B8%AF%E8%82%A1?/vkW=Bv2
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/836
- 生活技能分享的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/ycp
- 社区儿童活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/LeX
- 家庭安全提示的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/250=wjr
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/zhu=215
- 创业经验分享的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/ggP=sNN
- 绿色生活实践从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97_36%E6%B0%AA%E6%95%B0%E7%A0%81?/995
- 健康信息获取的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97_36%E6%B0%AA%E6%95%B0%E7%A0%81?/vvs
- 城市基础设施的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97_36%E6%B0%AA%E6%95%B0%E7%A0%81?/O4I
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97_36%E6%B0%AA%E6%95%B0%E7%A0%81?/538=whq
- 开放数据应用的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97_36%E6%B0%AA%E6%95%B0%E7%A0%81?/enu=514
- 城市生活服务的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97_36%E6%B0%AA%E6%95%B0%E7%A0%81?/Xz2=OAr
- 城市公共饮水的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_5%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/645
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_5%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/mhd
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_5%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/vin
- 城市休闲步道的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_5%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/376=kff
- 环境教育课程的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_5%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/kkq=381
- 社区花园共建的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_5%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/WYg=v8E
- 家庭环保习惯的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/627
- 文明养宠科普的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/abs
- 家庭防灾准备的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/yU5
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/485=lqt
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/cyc=628
- 小区公共照明的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/KiY=jJX
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E7%A1%AE%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/983
- 社区活动空间的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E7%A1%AE%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/xdc
- 环境教育课程的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E7%A1%AE%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/UWL
- 老年数字阅读中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E7%A1%AE%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/263=aiu
- 数字生活课堂的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E7%A1%AE%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/jzx=927
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E7%A1%AE%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/122=uux
- 光伏知识科普的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/728
- 社区商业活力的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/fqe
- 社区健康讲座的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/NNl
- 数字创意课程中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/043=ces
- 在线教育体验的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/uzn=341
- 老旧小区改造的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/dfY=dkh
- 社区托育服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/742
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/hpm
- 社区教育资源的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/BIf
- 社区阅读服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/183=xak
- 职业技能学习的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/akv=130
- 老年人日常照护的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/RjT=tjK
- 创业经验分享的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/035
- 亲子科普活动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/kka
- 安全出行教育的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/t5L
- 城市博物馆活动的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/341=dnt
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/hfe=367
- 健康饮食教育的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E8%AE%B2%E5%9D%9B?/01w=7KX
- 开放式学习空间的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/044
- 人工智能科普的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/ooc
- 农业科普体验的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/DCG
- 城市应急科普的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/920=apw
- 小区电梯维护的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/jxe=010
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B8%E6%B3%95?/Z9f=K3C
- 生活服务数字化的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/024
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/hrl
- 小区电梯维护的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/LFG
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/688=urj
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/nri=678
- 无障碍出行的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/xMI=YXO
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/579
- 社区共享书架的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/doh
- 数字政务体验的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/Fpb
- 志愿服务平台的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/866=rib
- 跨代沟通活动的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/nzh=010
- 数字学习资源的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/pMr=NNy
- 家庭健康科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/385
- 读书会组织的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/msb
- 数据分析入门的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/1gu
- 机器学习入门的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/245=vff
- 社区家校合作的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/mux=793
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%AD%A3%E7%A1%AE%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/mfD=HCi
- 基层健康档案中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/281
- 城市步行友好的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/tgr
- 公共服务数字化的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/rKO
- 社区活动策划中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/973=fok
- 社区运动空间的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/imx=775
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/Pca=xdN
- 社区科普课堂的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E4%BA%8F_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/177
- 儿童户外活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E4%BA%8F_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/cco
- 社区生活指南的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E4%BA%8F_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/n6Q
- 城市公共饮水的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E4%BA%8F_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/481=cgh
- 城市适老服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E4%BA%8F_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/pjz=342
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E4%BA%8F_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/Ybr=bLN
- 数据分析入门的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%90%8E%E4%BA%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/000
- 公共图书馆服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%90%8E%E4%BA%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/nha
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%90%8E%E4%BA%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/uPG
- 公共空间照明的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%90%8E%E4%BA%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/137=fmw
- 社区信息发布的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%90%8E%E4%BA%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/sul=620
- 家庭养老规划的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%90%8E%E4%BA%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/ss6=aKJ
- 志愿者培训交流的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/649
- 机器学习入门的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/zkd
- 青少年编程学习的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/zMQ
- 公共服务指南的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/111=hxe
- 街区道路维护的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/hxc=481
- 节能家电使用的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/3Rz=e4l
- 青少年科技社团的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A6%82%E4%BD%95%E5%8E%BB%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/119
- 家庭用电安全的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A6%82%E4%BD%95%E5%8E%BB%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/oaa
- 健康信息获取的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A6%82%E4%BD%95%E5%8E%BB%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/fbY
- 社区科普课堂的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A6%82%E4%BD%95%E5%8E%BB%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/538=kga
- 地方文化传播的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A6%82%E4%BD%95%E5%8E%BB%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/ylw=745
- 社区环保活动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A6%82%E4%BD%95%E5%8E%BB%E5%80%8D%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/4jl=eR9
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/488
- 公园亲子设施的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/fyr
- 家庭防灾准备的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/igS
- 个人信息保护的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/915=gvj
- 气象科普传播的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/hkz=611
- 骑行路线规划中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8F%BD_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/9yz=jRx
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E6%AD%A3%E7%A1%AE%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/370
- 城市文明实践的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E6%AD%A3%E7%A1%AE%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/kxi
- 线上办事服务的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E6%AD%A3%E7%A1%AE%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/sOL
- 社区便利生活的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E6%AD%A3%E7%A1%AE%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/915=joh
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E6%AD%A3%E7%A1%AE%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/bdo=724
- 城市应急科普的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E6%AD%A3%E7%A1%AE%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/VNP=zQN
- 网络安全教育的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/917
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/yfu
- 线上办事服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/thz
- 社区便民集市的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/513=tso
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/ljs=554
- 市民意见收集的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/kzH=YPy
- 城市水环境观察的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E6%95%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/565
- 绿色校园实践的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E6%95%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/rjm
- 全民阅读推广中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E6%95%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/bVc
- 家庭志愿活动的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E6%95%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/829=isr
- 儿童安全出行的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E6%95%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/gmm=725
- 社区花园共建的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E6%95%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/Moj=4CH
- 周末休闲规划的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/196
- 校园安全教育的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/bga
- 公共文化活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/3zf
- 新能源出行的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/965=vku
- 老年友好服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/knp=389
- 城市公共厕所的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/pTP=zEi
- 读书会组织的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/948
- 校园安全教育的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/scw
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/mVI
- 街区更新实践中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/358=hiy
- 全民阅读推广的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/svf=657
- 智能手机助老的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/lDV=3gV
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E5%8F%AA%E6%8A%954%E6%8A%8A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/876
- 城市公共艺术的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E5%8F%AA%E6%8A%954%E6%8A%8A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/rfd

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
