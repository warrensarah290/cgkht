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

- 乡村文化活动的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/maq=677
- 数字阅读服务的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/Y1y=Hqu
- 通勤路线规划的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/868
- 非遗体验活动的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/orj
- 城市慢跑路线的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/GEX
- 城市公共饮水的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/123=epn
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/nsm=899
- 乡村文化空间的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/PPo=cDP
- 城乡交流活动的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/005
- 社区公共卫生的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/ajz
- 数字学习资源的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/1Uy
- 社区花园共建的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/335=psc
- 文明养宠科普的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/lgc=719
- 城市基础设施的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/e0a=i3Z
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/578
- 灵活就业交流的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/lij
- 社区学习活动的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/3Sg
- 儿童运动体验的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/204=qdp
- 就业技能培训的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/hhz=247
- 节假日出行安排的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/f7c=koI
- 社区艺术活动的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/918
- 智慧城市体验的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/fiy
- 亲子科普活动中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/bLj
- 公园亲子设施的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/297=fpi
- 在线学习体验的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/ofa=674
- 城市公共自行车的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/eEB=m65
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9C%B0%E4%BA%A7?/682
- 小区停车协商的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9C%B0%E4%BA%A7?/uii
- 新能源出行的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9C%B0%E4%BA%A7?/cqs
- 城市步行环境的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9C%B0%E4%BA%A7?/860=dsp
- 公园休闲体验的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9C%B0%E4%BA%A7?/rcu=969
- 居家适老化改造的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9C%B0%E4%BA%A7?/GC3=0VX
- 社区菜市场服务的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/593
- 数字档案服务的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/yta
- 节日文化体验的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/TAB
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/944=yxn
- 城市步行友好中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/hwt=560
- 地方戏曲体验的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/kdj=MXT
- 智能家居应用的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/220
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/amh
- 骑行路线规划的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/vEb
- 社区设施共享的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/412=poh
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/knp=654
- 数字创意课程的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/pKS=Lf2
- 安全出行教育的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/439
- 本地旅行体验的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/fvd
- 数字政务体验的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/MQa
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/677=ssi
- 数字公共文化的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/aqz=838
- 文明养宠科普中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BD%E5%86%85?/5Zy=tfF
- 儿童安全出行的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/419
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/qcu
- 社区共享书架的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/B5H
- 小区公共照明的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/994=wiv
- 城市基础设施的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/cyh=929
- 开放式学习空间的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/JUp=k9U
- 数字艺术创作的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/367
- 小微企业服务的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/jty
- 社区儿童活动的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/XFV
- 生活技能分享的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/416=qit
- 开源技术交流的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/omf=362
- 市民热线服务的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/UXb=LuV
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/113
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/lax
- 生成式工具使用的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/IwJ
- 街区小店体验的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/511=nef
- 公共卫生设施的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/vys=704
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/WuR=WGj
- 社区家政服务的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/396
- 社区活动空间的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/wpu
- 城市生活服务的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/led
- 公共服务预约的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/610=tte
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/xvu=670
- 社区应急准备的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/55p=0wJ
- 志愿服务平台的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/174
- 城市休闲步道的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/jmg
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/68d
- 本地历史资料的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/746=mbb
- 市民热线服务的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/qzi=771
- 图书借阅体验的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/gr1=V9F
- 街区更新实践的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/480
- 老年数字阅读的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/glz
- 城市便民驿站的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/21Q
- 城乡交流活动的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/830=azo
- 节约用水实践的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/ooo=048
- 数字设备回收的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/8fa=5VP
- 便民信息查询的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/034
- 老年学习活动的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/tgh
- 食品配送体验的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/jqP
- 老年人日常照护的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/336=szy
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/xny=564
- 老年友好服务的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/PKO=XZB
- 社区体育组织中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/297
- 城市生活记录的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/tiv
- 社区健康讲座的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/hWj
- 乡村文化空间的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/651=nzr
- 老年人日常照护的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/sxu=334
- 安全出行教育的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_8719%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%85%E6%B8%B8?/JCd=Jxy
- 健康饮水科普的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/925
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/avl
- 健康信息获取的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/HNy
- 生活垃圾减量的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/207=hcd
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/ssf=440
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/Ete=br7
- 节能家电使用的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/104
- 城市公共标识的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/top
- 家庭阅读计划的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/zZg
- 医院导诊服务的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/067=vbp
- 终身学习资源的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/jvk=268
- 老年人出行服务的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/bVb=Aa0
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/492
- 街道综合服务的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/xsd
- 社区养老服务的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/EIf
- 青年志愿活动的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/442=bts
- 节气饮食文化的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/sil=945
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/ozM=HYh
- 图书馆活动策划的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/165
- 社区垃圾分类的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/iih
- 公共服务数字化的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/lMQ
- 老年智能设备的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/587=apy
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/kls=450
- 市民意见收集的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/iZG=TAk
- 亲子科普活动的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/543
- 城乡交通衔接的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/gbu
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/98b
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/247=epb
- 文化场馆预约的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/rid=381
- 软件开发学习的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_8818%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/oBN=zly
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/633
- 乡村电商实践中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/avy
- 食品安全科普的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/WW4
- 机器人科普活动的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/716=lta
- 家庭环保行动的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/akf=360
- 社区科普课堂的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/1ya=K3m
- 街区绿化养护的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/219
- 数字设备回收的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/wds
- 社区阅读服务的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/AUc
- 网络信息辨识的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/339=ith
- 便民服务地图的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/nmm=300
- 城市住房服务的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/73A=wK8
- 智慧停车服务的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/353
- 科普展览体验的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/bjg
- 社区体育组织的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/Aqq
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/642=ori
- 乡村文化活动的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/jwx=571
- 社区心理支持的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/H1L=oUP
- 邻里互助活动的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/828
- 老年智能设备的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/ibn
- 青年志愿活动的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/Grb
- 家庭园艺实践的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/774=ixb
- 在线学习体验中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/ohz=192
- 儿童安全出行中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_8818%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/TX2=x3Q
- 社区菜市场服务的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_8818%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/963
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_8818%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/sia
- 城市绿色交通的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_8818%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/N3E
- 个人时间管理的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_8818%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/489=jbs
- 社区便利生活的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_8818%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/zal=713
- 环境教育课程的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_8818%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/8qr=1fM
- 居家适老化改造的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_8818%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/122
- 文明养宠科普的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_8818%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/jdo
- 校园安全教育的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_8818%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/QKB
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_8818%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/296=sdp
- 软件开发学习的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_8818%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/vku=234
- 城市文化路线的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_8818%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/L2z=IEs
- 文明养宠科普的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/883
- 环境教育课程的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/xyr
- 公共服务预约的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/gUj
- 街头绿植养护的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/821=ejv
- 乡村文化空间的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/ywb=003
- 社区家政服务的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/UUn=QRP
- 通勤路线规划的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/209
- 社区便民服务的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/jla
- 社区垃圾分类的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/NUw
- 城市展览体验的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/169=ktd
- 城乡交流活动的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/bbh=129
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/yq1=sXg
- 公交站点体验的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_8818%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/321
- 旧物循环利用的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_8818%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/wow
- 数字支付体验的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_8818%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/wWr
- 社区花园共建的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_8818%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/466=lgd
- 口袋公园建设的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_8818%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/abo=778
- 社区环保活动的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_8818%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/0UM=MtF
- 城市微更新实践的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_8818%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/380
- 校园阅读活动的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_8818%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/cqa
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_8818%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/SZF
- 农产品消费体验的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_8818%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/569=ztn
- 社区慢性病防控的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_8818%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/oku=018
- 全民健身活动的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_8818%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/x5A=wnH
- 公共卫生宣传的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/296
- 节能家电使用的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/ssm
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/hYh
- 公共场所导视的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/093=bqs
- 城市骑行环境的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/mmn=567
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8818%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%A9%E7%A5%A8?/9G5=E7S
- 乡村文化活动的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/267
- 生成式工具使用的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/bfc
- 非遗体验活动的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/QvD
- 儿童友好空间的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/401=owo
- 市民意见收集的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/nqg=437
- 社区共享书架的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_8818%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/ckc=qP7
- 城市步行环境的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/950
- 社区养老服务的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/xfo
- 街区道路维护的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/7iD
- 绿色建筑理念的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/529=tpq
- 公共服务预约的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/toc=057
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_8818%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/6Fq=Hst
- 社区休闲设施的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/596
- 公共空间安全的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/hpf
- 城市运动公园的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/avR
- 家庭消费规划的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/455=ugp
- 低碳社区实践的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/qql=613
- 城市文明出行的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_8818%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/Q3T=aGa
- 城市树木认养的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9123%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/432
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9123%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/tge
- 食品配送体验的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9123%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/Jej
- 乡村生态观察的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9123%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/811=kxg
- 老年人文化生活的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9123%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/mua=329
- 本地历史资料的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_9123%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/pVx=ILd
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_9123%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/890
- 本地历史资料的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_9123%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/xqz
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_9123%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/YzT
- 城市地名文化的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_9123%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/659=aei
- 公共设施使用的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_9123%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/fdz=969
- 城市噪声观察的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_9123%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/W08=v6H
- 图书借阅体验的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/270
- 校园社团活动的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/idh
- 老年数字阅读的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/jNr
- 创业经验分享的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/858=gyn
- 数字创意课程的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/jfv=489
- 老年数字阅读的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/k74=oSv
- 课后服务体验的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/437
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/deh
- 城市公共空间的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/uvs
- 社区艺术活动的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/082=jtg
- 劳动教育实践的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/ibc=338
- 基层健康服务的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_9123%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/yuV=lMI
- 青年职业探索的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/496
- 应急物资管理的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/gvw
- 生成式工具使用的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/Lbq
- 家庭网络使用的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/358=gcq
- 城市绿色交通的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/hbk=013
- 本地消费场景的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/ug7=HtN
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/069
- 绿色办公实践的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/rwb
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/Lb2
- 环境教育课程的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/979=qxp
- 地方旅游导览的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/qwj=649
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9123%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/q45=hAL
- 物业服务沟通的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/752
- 科学健身方法的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_9123%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/ugt

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
