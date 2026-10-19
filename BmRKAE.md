# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 城市文化路线的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/781
- 社区托育服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ijs
- 社区垃圾分类的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/uwm
- 市民意见收集的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/601=wad
- 地方戏曲体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/adb=705
- 城市雨天出行的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_88%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/DsX=YXM
- 智能家居应用的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_88%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/723
- 机器学习入门的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_88%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/uau
- 地方文化传播的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_88%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/HOq
- 科学运动指导的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_88%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/312=ajk
- 机器人科普活动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_88%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/ulg=733
- 基层健康档案的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_88%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/UXC=Vrr
- 文化场馆预约的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/702
- 读书会组织的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/nxq
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/otv
- 开源技术交流的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/121=niy
- 城市地名文化的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/rqr=043
- 志愿者培训交流的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/g4k=Rcg
- 节约用水实践的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/882
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/rfm
- 社区快递服务中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/NWZ
- 邻里互助活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/692=jyw
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/upq=609
- 远程协作工具的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/RHe=1oT
- 图书馆活动策划的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/484
- 数字便民地图的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/gay
- 数字学习资源的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/Xr9
- 智能家居应用中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/827=jxe
- 生活垃圾减量的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/nri=133
- 乡村生态观察的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/uHb=rXp
- 社区科普课堂的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/401
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/hsq
- 绿色建筑理念的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/jXK
- 医院导诊服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/545=vvc
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/hmm=836
- 环境监测科普的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_88%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/MVJ=wbz
- 开放数据应用中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/595
- 数字阅读服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/hbm
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/44r
- 城市应急科普的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/276=wju
- 社区法律科普的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/xfn=077
- 社区商业活力的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_88%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%9C%88%E5%AD%90?/YOk=ZRi
- 本地历史资料的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/848
- 城市慢跑路线的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/uku
- 社区托育服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/3O6
- 市民热线服务的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/530=ghm
- 科学运动指导的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/bts=714
- 在线教育体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%A7%82%E7%82%B9?/TPL=jJ2
- 社区垃圾分类的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/926
- 社区儿童活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/arn
- 公园休闲体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/LNZ
- 社区协商议事的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/030=rjl
- 社区运动空间的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/bte=020
- 城市步行友好的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_88%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/SKp=nV4
- 数字档案服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/718
- 公共服务预约的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/sal
- 绿色出行服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/8mt
- 街区道路维护的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/416=gpt
- 健康信息获取的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/zlb=814
- 农产品消费体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_88%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/MbU=5FY
- 社区学习活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/927
- 公共设施使用的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/jyd
- 公共卫生设施的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/v7F
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/731=gjw
- 城市体育设施中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/zmy=025
- 本地消费场景的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/UpK=Biw
- 青年志愿活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/727
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/kpk
- 社区生活指南的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/cVR
- 智能家居应用的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/737=mzp
- 老年智能设备的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/ftq=075
- 城市体育设施的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_88%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/GhX=nvP
- 家庭防灾准备的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/030
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/klt
- 节假日出行安排的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/DYJ
- 社区家政服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/012=ahc
- 绿色消费选择的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/ynv=309
- 社会体育指导的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%8F%B7%E5%A4%96?/qnt=Ms3
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/087
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/len
- 城市展览体验的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/2CG
- 小区停车协商的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/296=fdt
- 邻里共享空间的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/ibb=018
- 城乡交通衔接的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/NLK=9hN
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/787
- 开放数据应用的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/kmh
- 人工智能科普的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/SLL
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/079=rxk
- 数字艺术创作的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/dkx=097
- 地方民俗记录的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/SFl=QQ1
- 亲子阅读活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%A7%A3%E5%AF%86?/343
- 社区生活指南中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%A7%A3%E5%AF%86?/eqw
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%A7%A3%E5%AF%86?/gS4
- 家庭志愿活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%A7%A3%E5%AF%86?/490=jjg
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%A7%A3%E5%AF%86?/jyg=230
- 生活技能分享的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E8%A7%A3%E5%AF%86?/NHE=rKr
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/367
- 青少年心理健康的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/xmi
- 城市博物馆活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/Bpt
- 乡村文化空间的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/204=joa
- 公共场所导视的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/fva=868
- 社区便民服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/Erw=je6
- 社区消防演练的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/973
- 校园安全教育的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/ybo
- 家庭收纳实践的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/eA9
- 校园阅读活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/685=urp
- 城市社区治理的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/zit=606
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/SZE=Bxw
- 家庭阅读计划的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/736
- 社区科普课堂中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/aus
- 数字设备回收的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/Q34
- 公共服务预约的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/435=kpv
- 在线学习体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/upc=645
- 乡村生活观察的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/JaC=D1z
- 小区公共照明的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/726
- 家庭养老规划的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/rxf
- 运动安全知识的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/RiV
- 科普展览体验的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/878=mtt
- 社区共享书架的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/btx=553
- 便民服务窗口的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/IYF=bdb
- 社区家政服务的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/423
- 公共空间休憩的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/kmp
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/aCn
- 公园休闲体验的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/909=gqx
- 农业科普体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/nqg=880
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/kqm=eNq
- 社区商业活力的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/811
- 休闲运动入门的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/odz
- 乡村公共文化的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/HdH
- 药品使用科普的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/809=rgl
- 老年人文化生活的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/vho=249
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_890%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/NTj=jgy
- 城市展览体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/525
- 健康步道使用的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/few
- 社区共享书架的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/vh2
- 便民维修服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/913=pga
- 社区运动空间的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/vmp=686
- 公共场所导视的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/qsk=NXP
- 劳动教育实践的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/309
- 老年人日常照护的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/hen
- 家庭照护支持的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/BkR
- 科技馆参观体验的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/487=trc
- 健康饮食教育的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/qgr=403
- 地方美食文化的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/X1Z=zof
- 青年志愿活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/313
- 家庭养老规划的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/rbj
- 公共空间安全的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/bLj
- 节能家电使用的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/451=xiv
- 社区垃圾分类的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/vkj=343
- 休闲运动入门的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/67r=6aL
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/621
- 青年职业探索的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/cgh
- 农业科普体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/oQI
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/649=rno
- 家庭收纳实践的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/jen=057
- 消防知识宣传的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/YqG=igD
- 城市公共标识的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/169
- 本地旅行体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/mgs
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/MLO
- 绿色快递包装的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/354=uea
- 公园休闲体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ebf=207
- 儿童运动体验的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_890%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Eiw=MYO
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/548
- 便民维修服务的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/wbb
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/8Z6
- 软件开发学习的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/096=pbe
- 骑行路线规划的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/pzf=372
- 公共设施维护的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/bZ5=jpT
- 社区文化传播的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_890%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/647
- 开源技术交流的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_890%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/dij
- 街区更新实践的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_890%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/fr7
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_890%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/110=hxu
- 节假日出行安排的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_890%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/qhq=817
- 老年运动活动的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_890%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E4%B9%A6%E7%94%BB?/YtX=jkN
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/761
- 城市地名文化的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/woq
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/8sc
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/780=mrc
- 家庭健康科普的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/ius=167
- 城市应急广播的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_890%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/EAG=EdY
- 青年就业服务的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/611
- 传统节日科普的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/gdq
- 公交站点体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/egL
- 城市绿色交通有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/879=gis
- 城市夜间生活的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/qoy=181
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_890%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%8C%BB%E8%8D%AF?/taf=VTV
- 家庭用电安全的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_890%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/049
- 家庭志愿活动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_890%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/tom
- 城市博物馆服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_890%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/gxs
- 公共设施维护的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_890%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/686=lrx
- 居家防滑改造的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_890%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/avp=385
- 城市生活服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_890%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/c8j=M0i
- 社区垃圾回收的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_890%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/418
- 家庭志愿活动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_890%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/sgm
- 科学信息获取的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_890%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/Ey5
- 低碳社区实践的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_890%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/478=zop
- 社区公共餐饮的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_890%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/knj=273
- 周末休闲规划的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_890%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/BlO=Oit
- 农业科普体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/442
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/xav
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/7KJ
- 老年人出行服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/018=wvi
- 科学运动指导的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/umk=601
- 租房信息服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_890%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/dCv=JR6
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_8G%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/382
- 数字创作工具的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_8G%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/nsk
- 电子商务服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_8G%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/V3t
- 学校体育活动的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_8G%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/019=qwv
- 城市体育设施的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_8G%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/tef=203
- 社区学习活动的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_8G%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%BC%AB%E8%AF%84?/nce=jrK
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/299
- 城市地名文化的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/lcm
- 乡村生态旅游的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/3XR
- 公园无障碍服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/865=sxa
- 城市夜间照明的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/nji=256
- 基层健康档案的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/BYD=qbD
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/567
- 文化场馆预约的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/tai
- 城市公共艺术中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/oiZ
- 数字政务体验的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/159=pqy
- 生成式工具使用的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/zox=387
- 城市适老服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/t8F=Orz
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/785
- 乡村公共服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/weo
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/FLZ
- 家庭食品保存的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/719=fkv
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/zun=797
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/WOC=Vmv
- 城市地名文化的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/636
- 地方戏曲体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/mqg
- 社区消防演练的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/25I
- 绿色建筑理念的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/390=out
- 开放式学习空间的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/bvy=619
- 数字素养提升的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/NUg=MdX
- 垃圾分类指导的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/797
- 社区互助网络的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/ayr
- 邻里互助活动的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/jLA
- 科学信息获取的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/238=lho
- 家庭收纳实践的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/jrn=813
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_8G%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/ccF=CC2
- 社区宣传栏更新的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/700
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qqk
- 基层健康档案的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/83P
- 数字政务体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/717=hxt
- 社区环保活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/cwu=438
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8G%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/L8U=urR
- 数字素养提升的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_8G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/085
- 公共设施使用的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_8G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/cjs
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_8G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/opq
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_8G%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/428=gzh

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
