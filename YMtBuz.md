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

- 智慧城市体验的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/476
- 城市游园体验的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/hjr
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/qm6
- 城市公共厕所中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/381=zzp
- 城市公共座椅的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/ock=388
- 电动汽车充电的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/QWF=13N
- 社区便民集市的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/864
- 社区学习活动的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/ura
- 青少年户外教育的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/RH8
- 城乡交流活动的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/560=yab
- 公共交通接驳的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/pqc=207
- 食品安全科普的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/k3m=Evk
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/339
- 非遗课堂体验的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/ysa
- 城市公共艺术的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/yg9
- 社区读书角建设的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/304=xlh
- 节日文化体验的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/ooe=096
- 社区环保活动的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/1Gq=Rm7
- 光伏知识科普的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/101
- 校园节能行动的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/fsq
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/Msh
- 社区停车服务的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/742=cov
- 基层医疗预约的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/kwk=935
- 数字政务体验的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1889%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%B8%B8%E6%88%8F?/z2E=eXV
- 城市应急科普的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/155
- 家庭安全提示的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/llo
- 传统手工艺体验的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/aFo
- 社区志愿服务的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/885=ika
- 青少年科普实践的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/jhz=136
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_1889%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/QBi=ZHk
- 儿童运动体验的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/178
- 家庭安全提示的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/rpx
- 农村环境治理的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/Os3
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/193=ljw
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/gmv=524
- 终身学习资源的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_1889%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/zaT=TYc
- 传统节日科普的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/438
- 校园社团活动的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/jvg
- 机器学习入门的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/LRQ
- 街区更新实践的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/553=mxn
- 城市运动公园的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/ewd=109
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_1889%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/2Br=oRb
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/602
- 居家防滑改造中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/pov
- 通勤路线规划中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/q0Y
- 课后服务体验的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/133=ran
- 图书馆数字服务的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/zlf=216
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_1889%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/toh=lXZ
- 休闲运动入门的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/751
- 社区科普课堂的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/mfp
- 社区托育服务的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/bgb
- 科学观察活动的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/083=axd
- 城市文明实践的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/sin=520
- 气象科普传播的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/mA3=Q1o
- 数字政务体验的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/046
- 儿童户外活动的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/slf
- 非遗体验活动的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/nWE
- 家庭科学教育的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/487=two
- 社区故事采集的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/znc=181
- 数字支付体验的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/OgR=uak
- 城市住房服务的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/184
- 儿童安全出行的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/tin
- 家庭用电安全的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/vVm
- 城市游园体验的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/615=ufr
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/rwc=907
- 本地旅行体验的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/wL3=HXW
- 校园社团活动的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/155
- 智能手机助老的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/lwn
- 家庭园艺实践的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/WwC
- 小微企业服务的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/563=lkw
- 地方民俗记录的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/ocg=937
- 农村环境治理的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/TmU=X6u
- 城市农夫市集的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/790
- 学校食育活动的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/enl
- 数字学习资源的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/654
- 基层服务创新的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/337=xbq
- 新能源出行的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/cpi=582
- 读书会组织从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/Quf=bKh
- 本地历史资料的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/916
- 公共设施使用的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/ymr
- 运动安全知识的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/J77
- 乡村产业科普的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/799=dwp
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/lfx=488
- 城市公共空间的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/blQ=4CV
- 药品使用科普的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%B8%93%E9%A2%98?/211
- 数字支付体验的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%B8%93%E9%A2%98?/mun
- 校园安全教育的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%B8%93%E9%A2%98?/7Zo
- 终身学习资源的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%B8%93%E9%A2%98?/955=orz
- 社区儿童活动的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%B8%93%E9%A2%98?/nmv=093
- 地方文化传播的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%B8%93%E9%A2%98?/iQt=tnh
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/952
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/olo
- 家庭用电安全的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/5Um
- 全民健身活动的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/883=yll
- 城市生活服务的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/nkb=138
- 开源技术交流的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/kcI=kpJ
- 数字创意课程的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/583
- 绿色办公实践的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/uow
- 社区绿色空间的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/e97
- 街区小店体验的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/287=hlu
- 社区消防演练的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/qfn=544
- 数字政务体验的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/gG0=PR5
- 市民热线服务的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/697
- 气象科普传播的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/dah
- 社区垃圾分类的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/Yy9
- 健康信息获取的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/254=dys
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/hfy=035
- 城市公共标识的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_1899%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%B4%A2%E6%8A%A5?/O37=xhh
- 街区绿化养护的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/442
- 农贸市场环境的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/yrf
- 就业技能培训的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/HiY
- 儿童安全出行的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/197=wne
- 公园无障碍服务的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/mxo=738
- 城市公共艺术中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/KyP=3Hg
- 社区休闲设施的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/143
- 图书借阅体验的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/nam
- 城市文化路线的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/Tlo
- 城市应急科普的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/364=ani
- 城市夜间照明的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/jtk=845
- 乡村产业科普的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_1899%E5%BD%A9%E7%A5%A8-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/wEG=qrq
- 社区修缮行动中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/847
- 城乡交流活动的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/ygp
- 社区安全巡查的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/OIW
- 便民服务窗口的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/684=wey
- 社区交通安全的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/iek=728
- 社区互助网络的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_1899%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/H7I=FdB
- 网络安全教育的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/702
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/oye
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/gSa
- 城市步行友好的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/504=are
- 光伏知识科普的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/yzo=971
- 网络安全教育的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/mGy=b3H
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/957
- 科学健身方法中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/tzu
- 青年志愿活动的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/UDI
- 节气饮食文化的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/338=cky
- 公共空间休憩的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/ylc=912
- 急救知识普及的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/f7U=nUU
- 儿童运动体验的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1899%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E4%BA%BA%E5%A4%A7?/572
- 租房信息服务的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1899%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E4%BA%BA%E5%A4%A7?/hmf
- 城市骑行环境的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1899%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E4%BA%BA%E5%A4%A7?/d9i
- 消防知识宣传的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1899%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E4%BA%BA%E5%A4%A7?/048=gdp
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1899%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E4%BA%BA%E5%A4%A7?/moz=984
- 社区养老服务的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_1899%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E4%BA%BA%E5%A4%A7?/nlv=moN
- 新能源知识普及的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1899%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/093
- 社区文化节活动的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1899%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/tik
- 家庭安全提示的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1899%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/MVM
- 农业科普体验的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1899%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/918=vjs
- 居家适老化改造的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1899%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/mkl=201
- 家庭急救准备的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1899%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/7Zw=sIl
- 社区公共餐饮的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1899%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/563
- 公共空间导览的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1899%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/wkh
- 职业技能学习的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1899%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/wqZ
- 绿色校园实践的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1899%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/925=kxx
- 地方文化传播的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1899%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/gjo=546
- 便民服务窗口的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_1899%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/c2R=oMa
- 小区公共照明的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/098
- 小区停车协商的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/cpg
- 城市共享单车的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/e4O
- 消防知识宣传的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/782=rzm
- 在线教育体验的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/ywx=838
- 智能家居应用的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_1899%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/apF=izo
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_1899%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/451
- 社区教育资源的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_1899%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/itb
- 垃圾分类指导的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_1899%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/RTF
- 公益活动组织的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_1899%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/852=psx
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_1899%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/xsp=739
- 科普展览体验的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_1899%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/P2F=wma
- 健康步道使用的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_1899%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/623
- 家庭消费规划的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_1899%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/wuf
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_1899%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/wVD
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_1899%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/237=suw
- 城市公共厕所的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_1899%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/wtv=924
- 家庭急救准备的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_1899%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/SJ4=xyQ
- 社区停车服务的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/391
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/hna
- 基层健康服务的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/aX7
- 公共交通接驳的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/897=yia
- 城市应急科普的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/hyf=731
- 城市应急广播的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_1899%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/mwT=KyE
- 电子商务服务的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/412
- 个人数据管理的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/hmh
- 乡村生活观察的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/8p4
- 骑行路线规划的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/377=mvl
- 公交站点体验的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/liq=333
- 社区安全巡查的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/A6e=YFt
- 社区信息发布的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/657
- 数字政务体验的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/uvr
- 城市夜间照明的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/BMC
- 家庭防灾准备的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/741=lug
- 街区绿化养护的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/umz=880
- 远程协作工具的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/uE8=pK8
- 城市住房服务中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/943
- 公共设施维护的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/khm
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/hAu
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/524=ovf
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/btn=310
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/chk=5SX
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/056
- 家庭节能设备中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/nkb
- 在线教育体验的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/0Sf
- 儿童友好空间的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/351=wsp
- 数字学习资源的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/rsf=055
- 社区庭院绿化的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/EDg=KB4
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/193
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/rmn
- 社区设施共享的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/Rzq
- 生成式工具使用的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/950=xeb
- 社区志愿服务的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/aov=011
- 社区停车服务的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/vMv=eUB
- 电子商务服务的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/222
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/qpm
- 药品使用科普的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/WFW
- 社区修缮行动的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/556=crs
- 绿色生活实践的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/qov=584
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/1T5=ET1
- 基层健康服务的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%89%B9%E7%A8%BF?/162
- 科学教育活动的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%89%B9%E7%A8%BF?/hkh
- 社区公共餐饮的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%89%B9%E7%A8%BF?/0tH
- 城市绿色交通的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%89%B9%E7%A8%BF?/141=fir
- 社区阅读服务的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%89%B9%E7%A8%BF?/jkc=171
- 社区交通安全的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%89%B9%E7%A8%BF?/GMV=Hw5
- 文化讲座服务的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/841
- 居民健康教育的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/nvt
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/8at
- 个人信息保护的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/572=xfw
- 文明养宠科普的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/tnp=769
- 社区艺术活动的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/35Y=zjG
- 物业服务沟通的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/083
- 绿色快递包装的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/qpf
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/Rcu
- 家庭用电安全的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/112=oyf
- 公共文化活动的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/rth=506
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/B1x=36q
- 就业技能培训的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/289
- 在线学习体验的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/bqk
- 城市体育设施的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/3Z4
- 居民健康教育的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/486=eul
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/tjn=742
- 气象科普传播的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E8%B5%84?/yDi=MkM
- 家庭安全提示的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/314
- 公共服务评价的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/lrh
- 数字政务体验的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/1PZ
- 线上阅读资源的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/717=sgo
- 线上办事服务的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/frd=406
- 环境监测科普的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/Mkl=tcD
- 街区绿化养护的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/877
- 城乡交通衔接的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/dbk
- 社区生活指南的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/pMb
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-APP_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/222=yzw

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
