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

- 公益活动组织的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/MEy
- 软件开发学习的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/444=atg
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/nhy=294
- 城市基础设施的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/eFT=NAg
- 社区设施共享中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/391
- 文化场馆预约的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/qzi
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/ZkC
- 城市树木认养的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/738=myv
- 旧物循环利用的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/cbu=039
- 城市雨天出行的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/4Bx=nNv
- 家庭节能实践的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/890
- 便民服务窗口的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/tjk
- 数字生活课堂的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/Kb0
- 社区老年食堂的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/978=ucm
- 开放式学习空间的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/ksx=850
- 城市水环境观察的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/F8o=Iaj
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/918
- 地方戏曲体验的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/mdw
- 数字创作工具的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/C3a
- 城市地名文化的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/445=suj
- 城市休闲步道的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/vmf=252
- 老旧小区改造的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/Ts0=5lG
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/389
- 数据分析入门的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/xya
- 软件开发学习的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/TGd
- 公共文化活动的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/626=lbv
- 医院导诊服务的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/fof=550
- 电子商务服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/mN2=UgH
- 城市地名文化的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/439
- 城市文化路线的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/hsp
- 儿童户外活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/FuS
- 市民热线服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/009=lxc
- 全民健身活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/fqz=878
- 生活技能分享的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/88d=HA6
- 家庭食品保存的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/726
- 城市绿色交通的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/qom
- 生成式工具使用的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/lcb
- 居家防滑改造的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/157=raf
- 社区艺术活动的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/oja=121
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_355%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/tzL=Ey5
- 农业科普体验的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/903
- 街区更新实践的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/uqu
- 绿色出行服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/7Hp
- 创业经验分享的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/438=hcu
- 城市公共厕所的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/eql=782
- 公共场馆服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/fuI=Wt2
- 社区活动报名的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/888
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/qxa
- 农业科普体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/7xb
- 校园社团活动的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/510=hri
- 公共健身器材的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/czz=472
- 本地消费场景的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-APP_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/xDl=vw1
- 创业经验分享的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/412
- 老年人日常照护的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/onu
- 社区科普课堂的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/n99
- 农产品消费体验的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/145=eej
- 灵活就业交流的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/ytg=547
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_355%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/xrT=zZL
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/559
- 城市公共自行车的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/baz
- 城市适老服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/NJD
- 社区宣传栏更新的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/654=dkx
- 开源技术交流的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/cdk=369
- 青年职业探索的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/bT4=dny
- 文明养宠科普中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/432
- 社区家政服务的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/eby
- 科技馆参观体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/k5r
- 社区协商议事的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/666=uhf
- 校园阅读活动的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/sxj=069
- 公共场所导视的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_355%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/os9=hFO
- 开放数据应用的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/423
- 非遗体验活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/gbf
- 健康信息获取的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/hHM
- 志愿服务平台的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/464=jmp
- 城市公共标识的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/zrh=328
- 城市基础设施的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/L3T=ugi
- 城市公共厕所的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/652
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/cxv
- 小微企业服务中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/Hde
- 地方戏曲体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/057=hol
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/hbl=195
- 光伏知识科普中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_355%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/438=e9x
- 城市公共空间的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/400
- 城乡交流活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/jer
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/lSe
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/708=yne
- 公共交通接驳的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/bgg=597
- 环境监测科普的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_355%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/YD8=Hu3
- 绿色办公实践的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/973
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/dpt
- 医院导诊服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/f2J
- 个人信息保护的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/361=yly
- 青年职业探索的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/txt=525
- 数字档案服务的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_355%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/qic=HPR
- 家庭科学教育的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/059
- 城市建设科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/vmf
- 社区安全巡查的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/Zi4
- 城市公共艺术的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/281=lrb
- 志愿服务平台的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/xcp=770
- 社区设施共享的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_355%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/0Gt=v4A
- 物业服务沟通的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_360%E4%B9%A6%E7%94%BB?/010
- 城市共享单车的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_360%E4%B9%A6%E7%94%BB?/vks
- 老年人日常照护的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_360%E4%B9%A6%E7%94%BB?/bon
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_360%E4%B9%A6%E7%94%BB?/538=jjx
- 社区垃圾分类的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_360%E4%B9%A6%E7%94%BB?/ycu=417
- 社区邻里服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_355%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_360%E4%B9%A6%E7%94%BB?/s9g=tlN
- 老年学习活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/523
- 公共设施维护的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/glf
- 社区停车服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/APj
- 校园社团活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/226=ulm
- 食品安全科普的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/sbf=170
- 数字地图应用中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_355%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/WSu=1fc
- 街区更新实践的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/156
- 社区宠物管理的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/kmm
- 亲子科普活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/9li
- 城市绿道建设的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/225=aud
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/xkf=243
- 街区更新实践的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/vwt=b0C
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/064
- 科学观察活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/prm
- 数字生活课堂的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/gzw
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/673=txl
- 家庭照护支持的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/pge=906
- 运动安全知识的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/Yrm=zZk
- 小区停车协商的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%99%BE%E7%A7%91?/046
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%99%BE%E7%A7%91?/vud
- 乡村电商实践的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%99%BE%E7%A7%91?/Pxl
- 公共设施维护的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%99%BE%E7%A7%91?/250=twa
- 城市社区治理的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%99%BE%E7%A7%91?/smc=571
- 家庭网络使用的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%99%BE%E7%A7%91?/UOI=0u5
- 街区小店体验中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/697
- 家庭运动计划的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/yxk
- 环境监测科普的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/bmi
- 城市住房服务的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/690=fky
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/pyu=782
- 就业技能培训的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/Ttl=fLb
- 图书馆活动策划的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/117
- 公园无障碍服务的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/xfh
- 社区法律科普的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/bwL
- 家庭收纳实践的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/947=lvy
- 农贸市场环境的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/xvf=852
- 农业科普体验的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/9OA=xph
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/689
- 城市公共艺术中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/bzq
- 城市应急科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/dub
- 机器人科普活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/422=lkt
- 节日文化体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/gxc=069
- 数字支付体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/usI=V4R
- 家庭健康管理的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/364
- 农村环境治理的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/wkh
- 绿色校园实践的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/L5h
- 社区活动空间的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/267=eim
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/lmd=087
- 社区科普课堂的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/bmb=bsL
- 社区设施共享的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/267
- 数字资源检索的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/yvo
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/y0D
- 居家防滑改造的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/160=nck
- 校园节能行动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/vyi=355
- 公共卫生设施的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/9tD=kkV
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/417
- 城市文明出行的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/qul
- 家庭节能实践的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/jHR
- 儿童友好空间的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/671=hfw
- 公园亲子设施的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/oeo=723
- 社区活动策划的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/obk=LQG
- 老年人文化生活的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/530
- 街区小店体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/gry
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/lfE
- 亲子科普活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/583=wzk
- 老年智能设备的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/rxs=564
- 城市地名文化的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/UcS=2Fp
- 城市文明出行的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_357%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/082
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_357%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/wou
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_357%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/c5H
- 居家适老化改造的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_357%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/106=tjh
- 城市应急科普的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_357%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/vja=392
- 青年就业服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_357%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/BF0=RP3
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/889
- 基层健康服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/jqx
- 社区停车服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/wDR
- 图书馆数字服务的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/495=gwv
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/ups=619
- 机器学习入门的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/B2f=G8J
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/771
- 城市公共艺术的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/inj
- 社区垃圾回收的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/IN4
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/634=xcw
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/ayo=338
- 社区商业活力的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/LWL=C5i
- 社区生活指南的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/167
- 老年友好服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/adj
- 城市微更新实践的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/m46
- 城市公共饮水的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/462=fhi
- 亲子科普活动的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/qgk=670
- 城市公共空间的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BD%AC%E8%BD%BD?/UBQ=nW9
- 公共服务数字化的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/058
- 学校食育活动的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/ptz
- 儿童户外活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/5od
- 垃圾分类指导的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/890=spa
- 科技馆参观体验的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/vjo=366
- 街头绿植养护的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/LtP=t47
- 公共文化活动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/433
- 居家适老化改造的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ccv
- 城市文明实践的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Gbn
- 社区宠物管理的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/569=rnx
- 城市博物馆活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mpn=057
- 城市共享单车的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/fzE=fW9
- 公共健身器材的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/970
- 地方美食文化的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/cof
- 就业技能培训的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/WWS
- 家庭网络使用的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/244=qrt
- 乡村生态观察的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/ifl=103
- 邻里共享空间的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_357%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/LxX=Ite
- 社区科普课堂的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/073
- 图书馆数字服务的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/jdw
- 邻里共享空间的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/tkF
- 城市运动公园的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/158=qtl
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/iws=662
- 通勤路线规划的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_357%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/MyB=4Gc
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/797
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/aov
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/bjP
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/090=uwn
- 城市公共艺术的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/aok=468
- 乡村公共文化的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_357%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/v2W=vQz
- 地方旅游导览的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/138
- 公共空间休憩中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/ldx
- 数字创作工具的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/NEf
- 基层服务创新的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/972=kgx
- 老年人文化生活的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/cvb=585
- 城市噪声观察的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_357%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/Luq=iKN
- 灵活就业交流的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/779
- 日常摄影记录的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/upj
- 家庭养老规划的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/RsM
- 城市便民驿站的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/406=qnw
- 全民健身活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/jbo=176
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_357%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/hp5=UcX
- 科学教育活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_360%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/527
- 老旧小区改造的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_360%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/jrd
- 社区商业活力的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_360%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/TUW
- 消防知识宣传的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_360%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/898=ijf
- 社区公共议事的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_360%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/xrc=262
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_360%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/UC4=Sxi
- 老旧小区改造的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/949
- 终身学习资源的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/kuu
- 地方美食文化的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/eK6
- 科学信息获取的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/274=ozo
- 户外活动组织中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/buq=460
- 社区绿色空间中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_360%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E6%91%98?/3zG=fzw

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
