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

- 个人时间管理的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/hVQ
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/429=hyi
- 农村环境治理中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/qxx=786
- 城市休闲步道的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/iFW=d1I
- 小微企业服务的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/749
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ten
- 开放数据应用的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/GkH
- 就业技能培训的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/869=ulj
- 乡村公共服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ybl=998
- 城市展览体验的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/hji=0UN
- 数字创作工具的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_87%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/561
- 全民健身活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_87%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/gif
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_87%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/qAj
- 社区绿色空间的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_87%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/637=dbo
- 在线学习体验的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_87%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/how=510
- 绿色办公实践的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_87%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/OC0=aKo
- 个人信息保护的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/351
- 课后服务体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/sap
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/f2H
- 运动安全知识的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/906=qts
- 城市树木认养的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/ltz=477
- 城市绿道建设的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/jIl=GM4
- 市民热线服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/059
- 生活垃圾减量的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/car
- 绿色消费选择的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/DF0
- 公共服务沟通的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/047=hwq
- 公共空间照明的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/hup=637
- 社区公共餐饮的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E9%80%9A%E4%BF%A1?/TZK=7BT
- 街区小店体验中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/930
- 数字政务体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/hiv
- 乡村公共阅读的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/i9m
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/919=aja
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/eao=101
- 公共交通接驳的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/JYL=TqN
- 城市人文观察的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/183
- 地方旅游导览的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/mlj
- 健康信息获取的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/vK3
- 市民意见收集的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/247=neu
- 休闲运动入门的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/pfv=568
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/8n0=nK0
- 乡村生活观察的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/357
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/nin
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/meq
- 社区安全巡查的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/896=ayr
- 气象科普传播的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/dau=769
- 安全出行教育的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/kr3=Afb
- 城市公共标识的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%8A%95%E7%A5%A8?/997
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%8A%95%E7%A5%A8?/rwo
- 节日文化体验的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%8A%95%E7%A5%A8?/JVL
- 社区家政服务的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%8A%95%E7%A5%A8?/884=ots
- 乡村文化活动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%8A%95%E7%A5%A8?/vfq=167
- 科学观察活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%8A%95%E7%A5%A8?/LLq=KIp
- 街道综合服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/799
- 数字学习资源的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/ycg
- 社区生活指南中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/Rlq
- 社区交通安全的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/059=enm
- 城市公共自行车的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/gio=112
- 家庭园艺实践的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/OaT=svD
- 社区志愿服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/725
- 家庭节能实践的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/owc
- 儿童友好空间的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/8dW
- 科学健身方法的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/849=gof
- 青少年科普实践中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/hvv=473
- 口袋公园建设的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/204=UOp
- 社区手工活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/283
- 城市水环境观察的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/olp
- 公益活动组织的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/ipw
- 城市步行环境的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/281=jrz
- 家庭照护支持的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/lww=811
- 节气饮食文化的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/oZs=oMW
- 绿色生活实践的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/722
- 科普展览体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/noc
- 志愿者培训交流的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/Gbz
- 社区快递服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/591=gei
- 社区设施共享的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/ltq=403
- 绿色快递包装的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%89%B9%E7%A8%BF?/gpL=vFJ
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/716
- 公共服务沟通的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/tkq
- 社区活动空间的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/NZg
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/093=ewg
- 节日文化体验的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/lup=786
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/GBY=HP9
- 就业技能培训的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/073
- 青少年户外教育的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/yvo
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/19W
- 家庭运动计划的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/347=ujy
- 社区互助网络的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/chf=068
- 智能家居应用的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%83%AD%E6%A6%9C?/mj0=oJE
- 数字设备回收的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/857
- 劳动教育实践的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/brq
- 节约用水实践的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/qnd
- 生活垃圾回收的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/052=leo
- 公共服务数字化的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/dew=180
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/UMx=f1y
- 社区快递服务中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/312
- 社区商业活力的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/mdz
- 家庭食品保存的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/E6A
- 城市水环境观察的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/485=cir
- 基层服务创新的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/srl=588
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/rAy=TPx
- 公园无障碍服务的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/175
- 节能家电使用的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/cik
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/lTC
- 城市夜间照明的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/907=eai
- 家庭饮食安排的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/tlm=647
- 非遗体验活动中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/wAy=c3r
- 城市噪声观察的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/077
- 社区学习活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/zrw
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/oiI
- 公共服务沟通的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/984=qzb
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/irf=524
- 家庭健康管理从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/jXO=b2z
- 城市公共饮水的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/638
- 乡村阅读活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/awf
- 数字课堂应用的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/V9R
- 家庭用电安全的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/165=vxb
- 开放数据应用的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/xvt=719
- 乡村阅读活动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/Vnl=zFM
- 绿色建筑理念的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/359
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/coo
- 图书馆数字服务的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/xww
- 家庭消费规划的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/905=tmz
- 生成式工具使用的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/rnz=322
- 城市公共标识的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_8808%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/Djo=4qr
- 居民健康教育中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_8808%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/370
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_8808%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/gen
- 城市公共标识的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_8808%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/GFZ
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_8808%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/493=nmh
- 城市雨天出行的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_8808%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/tkz=547
- 社区垃圾分类的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_8808%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/XzF=BXK
- 劳动教育实践的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8808%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/432
- 家庭健康科普的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8808%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/pqn
- 农业科普体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8808%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/edc
- 城市文明出行的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8808%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/262=orr
- 公共空间休憩的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8808%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/xlc=184
- 社区托育服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8808%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/ebm=b5T
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/668
- 在线教育体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/zus
- 人工智能科普的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/PjL
- 街区小店体验的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/837=erl
- 小区电梯维护的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/ncd=015
- 小区停车协商的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_8808%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/w9d=bCA
- 数字资源检索的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/907
- 低碳社区实践的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/kzs
- 城市夜间照明的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/7Y3
- 公共设施使用的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/445=htt
- 创业经验分享的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/eqc=399
- 基层服务创新的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/nPg=bQ0
- 远程协作工具的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/222
- 社区交通安全的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/xsx
- 便民信息查询的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/iBh
- 乡村生态观察的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/070=gmo
- 乡村产业科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/eqg=046
- 节能生活方式的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_8808%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%94%B6%E8%97%8F?/2g2=ZfD
- 科学信息获取的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8808%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/415
- 公益活动组织的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8808%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/thw
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8808%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/9H5
- 在线学习体验的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8808%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/031=tfb
- 社区体育组织的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8808%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/avg=354
- 城市可持续生活的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_8808%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/rH4=kah
- 城市绿色交通的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/752
- 城市骑行环境的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/gbr
- 乡村公共服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/VBV
- 数字政务体验的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/993=gfk
- 公共健身器材的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/xyv=052
- 地方旅游导览的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%91%A8%E6%8A%A5?/7bz=vor
- 户外活动组织的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/279
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/uxv
- 城市夜间照明的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/M2T
- 社区养老服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/434=qos
- 绿色校园实践的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/xio=936
- 居民健康教育的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/jAU=IZm
- 在线学习体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/979
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/gfy
- 街头绿植养护的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/6Ic
- 农业科普体验的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/670=xwf
- 公共服务评价的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/chj=173
- 青年就业服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8808%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/mMy=auc
- 社区老年食堂的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_8808%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/050
- 家庭用电安全的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_8808%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/umo
- 周末休闲规划的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_8808%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/xR3
- 开放式学习空间的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_8808%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/156=nfl
- 社区知识分享的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_8808%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/cju=523
- 城市应急科普的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_8808%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/8gP=8MV
- 社区艺术活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/246
- 志愿服务平台的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/cfw
- 社区体育组织的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/i90
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/597=wzg
- 绿色出行服务的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/laj=436
- 在线学习体验的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_8808%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/ZGe=EAW
- 便民维修服务的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_8818cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/376
- 健康饮水科普的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_8818cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/lpy
- 生成式工具使用的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_8818cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/lKs
- 城市绿色交通的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_8818cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/036=wbh
- 城市博物馆活动的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_8818cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/hsh=754
- 劳动教育实践的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_8818cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/MPL=Dld
- 学校体育活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_8818cc-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/361
- 社区信息发布的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_8818cc-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/jkq
- 公交站点体验中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_8818cc-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/Jj7
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_8818cc-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/743=mur
- 图书借阅体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_8818cc-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/kfc=582
- 社区便民集市的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_8818cc-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/tRJ=QWs
- 公共设施使用的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/172
- 节能家电使用的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/pku
- 家庭环保行动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/71E
- 绿色校园实践的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/459=esl
- 城市微更新实践中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/wdv=786
- 非遗课堂体验的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/Es5=yBK
- 科普展览体验的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_8818cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/952
- 社会体育指导的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_8818cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/krx
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_8818cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/TgG
- 社区快递服务的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_8818cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/032=fho
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_8818cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/sld=490
- 社区生活指南中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_8818cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/bMi=hRj
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8818cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/407
- 传统节日科普的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8818cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/kzw
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8818cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/MQ4
- 街区道路维护的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8818cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/346=nxe
- 城市文化路线中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8818cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/fsv=986
- 乡村产业科普的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8818cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/2fc=m8S
- 家庭运动计划的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_8818cc-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/642
- 家庭食品保存的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_8818cc-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/qin
- 消防知识宣传的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_8818cc-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/4EB
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_8818cc-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/180=rfi
- 城市公共饮水的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_8818cc-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/ihb=399
- 低碳社区实践的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_8818cc-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/vTO=3qu
- 社区心理支持的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/626
- 骑行路线规划的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/auu
- 社区家政服务的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/zHD
- 医院导诊服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/932=xpz
- 社区安全巡查的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/xoa=771
- 便民服务地图的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/DpN=TlT
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_8818cc-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/078
- 智慧停车服务的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_8818cc-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/ixz
- 公共交通信息服务中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_8818cc-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/bFe
- 数字素养提升的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_8818cc-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/943=tlw
- 基层服务创新的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_8818cc-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/zwi=327
- 生活垃圾回收的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_8818cc-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/PhU=QAq
- 绿色消费选择的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E5%AE%98%E7%BD%91_360%E7%A7%91%E6%8A%80?/812
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E5%AE%98%E7%BD%91_360%E7%A7%91%E6%8A%80?/lwl
- 老年人日常照护的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E5%AE%98%E7%BD%91_360%E7%A7%91%E6%8A%80?/1nI
- 家庭健康科普的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E5%AE%98%E7%BD%91_360%E7%A7%91%E6%8A%80?/084=tvx
- 社区活动策划的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E5%AE%98%E7%BD%91_360%E7%A7%91%E6%8A%80?/ncr=248
- 城市公共空间的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8818cc-%E5%AE%98%E7%BD%91_360%E7%A7%91%E6%8A%80?/aJS=59J
- 本地历史资料的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/599
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/nbc
- 周末休闲规划的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/R8G
- 健康饮水科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/324=vqx
- 儿童安全出行的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/hgf=547
- 老年运动活动的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8818cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/Mpc=JU2

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
