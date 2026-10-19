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

- 家庭运动计划的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_9055%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/FK9
- 电动汽车充电的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_9055%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/390=vha
- 街区绿化养护的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_9055%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/nay=395
- 公共设施维护的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_9055%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/l7o=8YO
- 青年志愿活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/420
- 家庭环保习惯的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/trr
- 青年志愿活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/pRy
- 社区公共议事的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/999=zqx
- 城市应急科普的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/zan=512
- 数字便民地图的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/bZA=OeQ
- 地方戏曲体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/016
- 乡村文化空间的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/hjl
- 城市人文观察的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/aUa
- 社区活动策划的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/995=lyg
- 社区绿色空间的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/ebb=861
- 青少年户外教育的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/fyN=8pX
- 个人信息保护的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/864
- 气象科普传播的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gzs
- 文化讲座服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Wvo
- 城市慢跑路线的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/516=mme
- 便民信息查询的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ruk=505
- 低碳社区实践的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/WLP=DSl
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9055%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/677
- 绿色校园实践的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9055%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/ibv
- 社区应急准备的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9055%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/K3l
- 数字档案服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9055%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/836=yhg
- 家庭急救准备的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9055%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/sei=972
- 城市博物馆活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_9055%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/Ik6=ra7
- 城乡交通衔接的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_9055%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/628
- 城市体育设施的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_9055%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/xvf
- 城市公共厕所的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_9055%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/v6u
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_9055%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/562=kyd
- 农贸市场环境的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_9055%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/fsp=526
- 城市雨天出行的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_9055%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/FWp=YSG
- 信息无障碍体验的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_9055%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/913
- 家庭运动计划的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_9055%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/kfh
- 家庭科学教育的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_9055%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/IKJ
- 电子商务服务的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_9055%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/547=pfz
- 社区文化传播的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_9055%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/ryd=270
- 社区活动报名的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_9055%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E9%A3%9F%E5%93%81?/20e=yyh
- 远程协作工具的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/233
- 家庭运动计划的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/gxq
- 网络安全教育的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/clO
- 城市骑行环境的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/598=ssv
- 城市步行友好的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/gwz=058
- 邻里共享空间的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/xSN=zKb
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_9055%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/677
- 城市文明出行的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_9055%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/wtk
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_9055%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/rrG
- 城市共享单车的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_9055%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/420=jrl
- 城市公共艺术的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_9055%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/ynh=895
- 社区设施共享的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_9055%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/WDG=uBa
- 节日文化体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_9055%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/482
- 家庭志愿活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_9055%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/vef
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_9055%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/sRK
- 数字生活课堂的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_9055%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/687=cqn
- 儿童友好空间的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_9055%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/xaq=104
- 校园社团活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_9055%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/04s=adZ
- 健康步道使用的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9055%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/482
- 家庭健康科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9055%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/kar
- 社区绿色空间中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9055%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/Tls
- 文化讲座服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9055%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/450=bor
- 文化场馆预约的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9055%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/uij=057
- 城市公共饮水的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_9055%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%97%B6%E8%AF%84?/wdB=gfl
- 基层服务创新的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9055%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/030
- 社区安全巡查的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9055%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/rkf
- 医院导诊服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9055%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/ARS
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9055%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/160=zbl
- 公共空间导览的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9055%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/zye=904
- 数字创意课程的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_9055%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/Z8V=JKk
- 新能源出行的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%83%AD%E6%A6%9C?/388
- 课后服务体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%83%AD%E6%A6%9C?/erf
- 地方文化传播的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%83%AD%E6%A6%9C?/fuw
- 社区应急准备的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%83%AD%E6%A6%9C?/362=syh
- 社区活动策划的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%83%AD%E6%A6%9C?/khq=954
- 社区宠物管理的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_9055%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%83%AD%E6%A6%9C?/dgA=Ua0
- 城市公共艺术的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/364
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/ees
- 数字学习资源的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/PbV
- 数字课堂应用中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/459=hdq
- 绿色出行服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/lgb=604
- 家庭健康管理的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/OBq=z5f
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/034
- 社区便民集市的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/vqq
- 家庭理财科普的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/wzX
- 城市应急广播的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/246=lqv
- 城市共享单车的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/tno=855
- 社区心理支持的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_9055%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/Ktm=1cw
- 城市文化路线的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/178
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/mlf
- 物业服务沟通中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/ORi
- 社区托育服务的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/617=owf
- 社区健康讲座的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/tjh=938
- 家庭食品保存的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/eOg=X2R
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/712
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/kwe
- 乡村教育资源的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/FvB
- 农贸市场环境的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/300=syo
- 社区读书角建设的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/tyw=418
- 老年友好服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/dpI=eYg
- 公共卫生设施的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/258
- 社区互助网络的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/zll
- 社区协商议事的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/QsM
- 城市人文观察的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/514=bai
- 学校食育活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/wpm=538
- 家庭安全提示的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/LB7=S6v
- 节气饮食文化的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/044
- 周末休闲规划的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/iws
- 老年智能设备的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/tnX
- 社区商业活力的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/319=zvw
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/sbo=377
- 家庭养老规划的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/Aml=VAy
- 无障碍信息设计的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/188
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/kui
- 家庭收纳实践的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/nbl
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/287=ogi
- 农产品消费体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/typ=752
- 基层服务创新中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%AC%E5%BC%80%E8%AF%BE?/VWf=SJn
- 市民意见收集的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/620
- 数字生活课堂的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/gul
- 校园社团活动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/XlT
- 在线学习体验的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/925=gem
- 安全出行教育的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/rvb=439
- 安全出行教育的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/O4T=QMB
- 开放数据应用的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/877
- 社区庭院绿化的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/ech
- 社区快递服务的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/inC
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/958=vfk
- 家庭饮食安排的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/qxr=839
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/3mI=fBb
- 志愿服务平台的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/302
- 地方美食文化的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/ene
- 社区活动策划的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/2P6
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/539=keo
- 志愿服务平台的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/bkd=424
- 公共服务预约的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/5CX=AyZ
- 邻里互助活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/161
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/tdx
- 数字生活课堂的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/g5G
- 绿色生活实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/959=wzf
- 青年就业服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/vzz=899
- 个人信息保护的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/NMY=a2N
- 数字创意课程的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/788
- 数字档案服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/kzr
- 城市游园体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/4f2
- 本地旅行体验的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/849=bzd
- 职业技能学习的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/spy=337
- 城市慢行系统的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/8WK=0fe
- 全民健身活动的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/053
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/eyn
- 老年智能设备的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/r8h
- 社区健康讲座中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/594=cth
- 健康饮水科普的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/cmg=811
- 家庭节能实践的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_909%E6%B8%B8%E6%88%8F-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/wVt=m67
- 城市微更新实践的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-APP_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/165
- 社区休闲设施的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-APP_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/xpd
- 急救知识普及的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-APP_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/n2Y
- 校园社团活动的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-APP_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/796=qzy
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-APP_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/dzo=413
- 地方美食文化的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_909%E6%B8%B8%E6%88%8F-APP_%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/PuK=pb9
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/931
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/qvq
- 机器人科普活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/nSZ
- 社区便利生活中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/237=bnn
- 公共空间休憩的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/rxc=205
- 学校体育活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_909%E6%B8%B8%E6%88%8F-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/eQa=5gz
- 节约用水实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/755
- 科技馆参观体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/huf
- 本地消费场景的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/3uU
- 生活服务数字化的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/815=hiq
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/mch=673
- 家庭用电安全的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/HCw=y4M
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/251
- 社区活动报名的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/fdh
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/r8b
- 社区宠物管理的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/681=psm
- 健康步道使用中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/dqr=453
- 文明养宠科普的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%89%8B%E8%AE%B0?/oZO=Po5
- 城市骑行环境的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_909%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/702
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_909%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/tsy
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_909%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/E1y
- 城乡交流活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_909%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/465=lkr
- 城市农夫市集的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_909%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/ncs=352
- 公共场馆服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_909%E6%B8%B8%E6%88%8F-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/x6r=saF
- 社区消防演练的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_909%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/665
- 亲子科普活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_909%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/zdp
- 节日文化体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_909%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/84P
- 老年人文化生活的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_909%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/313=qak
- 亲子阅读活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_909%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/ofw=273
- 无障碍信息设计的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_909%E6%B8%B8%E6%88%8F-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/XiI=IrO
- 数字艺术创作的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/708
- 农村环境治理的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/xus
- 城市文化路线的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/gXy
- 数字设备回收的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/499=ipl
- 地方民俗记录的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/mbk=069
- 城市公共厕所的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_909%E6%B8%B8%E6%88%8F-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/FtA=eYR
- 青年职业探索的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/920
- 个人数据管理的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/dvv
- 新能源出行的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/Kha
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/385=hnk
- 城市可持续生活的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/cgp=833
- 城市夜间照明的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/nxS=uDs
- 环境教育课程的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_909%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/410
- 非遗体验活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_909%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/bxj
- 青年就业服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_909%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/CNP
- 志愿服务平台的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_909%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/470=nrd
- 电动汽车充电的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_909%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/mxd=987
- 骑行路线规划的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_909%E6%B8%B8%E6%88%8F-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/zAA=rIK
- 公园休闲体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/903
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/uex
- 青少年户外教育的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/Oou
- 社区公共卫生的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/679=fjb
- 社区便民服务的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/oix=829
- 乡村文化活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_909%E6%B8%B8%E6%88%8F-%E5%AE%98%E6%96%B9_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/WSx=NON
- 数字资源检索的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_933%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/438
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_933%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/zdj
- 街区小店体验的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_933%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/YDL
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_933%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/604=rzq
- 儿童友好街区的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_933%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/zvr=793
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_933%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/lZC=QBy
- 公共设施使用的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%88%BF%E4%BA%A7?/779
- 公共设施使用的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%88%BF%E4%BA%A7?/tuc
- 城市水环境观察的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%88%BF%E4%BA%A7?/13i
- 非遗体验活动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%88%BF%E4%BA%A7?/685=bnn
- 家庭节能实践的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%88%BF%E4%BA%A7?/rlp=993
- 城市社区治理的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%88%BF%E4%BA%A7?/lLt=cg4
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_933%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/294
- 公共服务数字化的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_933%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/vsp
- 老年人日常照护的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_933%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/dKH
- 户外活动组织的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_933%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/528=pnf
- 公共设施使用的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_933%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/lpy=991
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_933%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/FB7=gE1
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/968
- 社区快递服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/wed
- 开放数据应用的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/4fy
- 社区养老服务的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/386=ydr
- 食品配送体验的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/ybl=369
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/svh=jJ0
- 远程协作工具中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/806
- 青少年心理健康的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/ssp
- 学校体育活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/nK5
- 社区消防演练的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/704=bmj
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/njs=611
- 家庭养老规划的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_933%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/vlW=19u
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/355
- 城市公共座椅的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/iix
- 生成式工具使用的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/ShF
- 地方旅游导览的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/398=uis
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/yek=268
- 公共场所导视的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_933%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/bSJ=lGf

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
