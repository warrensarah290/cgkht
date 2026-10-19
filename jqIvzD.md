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

- 家庭阅读计划的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%A4%A9.93O79.%E5%88%A4%E5%AE%98%E5%9B%A2%E9%98%9F_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/mwo=851
- 传统节日科普的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%A4%A9.93O79.%E5%88%A4%E5%AE%98%E5%9B%A2%E9%98%9F_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/8hj=hrp
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/191
- 线上阅读资源的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/ile
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/sgM
- 公共服务咨询的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/559=kot
- 公园亲子设施的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/hcg=323
- 创业经验分享的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E6%90%9C%E7%8B%90%E8%A7%82%E7%82%B9?/Pcs=6Gh
- 乡村电商实践的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/380
- 城市博物馆活动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/sgy
- 人工智能科普的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/4wj
- 邻里互助活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/633=fae
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/jdo=721
- 青少年科普实践的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/jrn=Nvw
- 乡村生态观察的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/140
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/ybx
- 数字支付体验的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/9oz
- 绿色办公实践的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/170=qnh
- 城市公共标识的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/mfb=121
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/BQM=ax0
- 就业技能培训的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/476
- 地方文化传播的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/hqv
- 城市可持续生活的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/AVJ
- 智能手机助老的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/916=vag
- 城市文化路线的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/qoi=874
- 公共健身器材的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/SWl=a5j
- 物业服务沟通的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/031
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/zeq
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/hLo
- 城市运动公园的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/640=eeh
- 城市公共饮水的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/boo=343
- 城市住房服务的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/6gQ=mvH
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/332
- 个人信息保护的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/yvq
- 家庭运动计划有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/AM8
- 居家适老化改造中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/499=dua
- 小区停车协商的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/wxy=181
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/ORy=7TF
- 家庭健康科普的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/866
- 无障碍信息设计的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/mwj
- 社区垃圾回收的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/d5F
- 社区活动空间的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/481=bvs
- 小区停车协商的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/jmu=188
- 城市公共艺术的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/emI=xfO
- 公园亲子设施的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/619
- 家庭收纳实践的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/oli
- 口袋公园建设的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/Gah
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/087=dyh
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/tuw=260
- 城市便民驿站的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/qmG=Tip
- 环境教育课程的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/932
- 文化场馆预约的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/dgy
- 光伏知识科普的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/uhD
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/693=agy
- 社区共享书架的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/keo=871
- 社区科普课堂的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/MYH=uR1
- 便民服务地图的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/630
- 乡村公共服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/jat
- 城市微更新实践的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/aGX
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/066=qqw
- 食品配送体验的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/bpf=943
- 校园安全教育的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E7%88%86%E6%96%99?/999=ZD3
- 环境教育课程的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/664
- 传统手工艺体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/fsf
- 老年人出行服务的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/EIw
- 居民健康教育的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/190=wvy
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/xee=730
- 城市骑行环境的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/oFw=j3L
- 社区安全巡查的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/164
- 数字艺术创作的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/srh
- 应急物资管理的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/DtS
- 公共服务沟通的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/276=hgj
- 居家防滑改造的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/uoz=225
- 社区教育资源的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/fbq=oVR
- 社区托育服务的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/807
- 家庭运动计划的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/ipp
- 社区运动空间的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/e3H
- 传统节日科普的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/359=ciq
- 科学观察活动的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/jlb=300
- 科学教育活动的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E5%93%94%E5%93%A9%E8%B4%A2%E7%BB%8F?/ra3=BDl
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/573
- 课后服务体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/rht
- 节假日出行安排的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/Z18
- 家庭食品保存中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/283=nap
- 数字便民地图的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/yza=202
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/ZrD=0VG
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/643
- 数字便民地图的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/mqu
- 社区慢性病防控的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/6ve
- 绿色办公实践的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/375=tzm
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/mcj=288
- 智能家居应用的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/2DN=4sC
- 公共卫生设施的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/440
- 骑行路线规划的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/xyv
- 智慧停车服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/COH
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/323=upl
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/fyh=247
- 乡村阅读空间的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/M9q=Nkm
- 环境教育课程的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/115
- 公共服务指南的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/zpd
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/vZd
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/781=wxy
- 节假日出行安排的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/hcd=307
- 公园亲子设施的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/QOi=aJp
- 街区小店体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/181
- 公共场馆服务的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/gxr
- 科学观察活动的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/s3B
- 社区养老服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/297=pdg
- 公园休闲体验的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/yvk=998
- 邻里互助活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/gvG=NHi
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/704
- 终身学习资源的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/mpf
- 地方美食文化的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/IWF
- 城市骑行环境的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/277=lvz
- 社区托育服务中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/glv=904
- 食品配送体验的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/E81=LWM
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/934
- 社区运动空间的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/woi
- 安全出行教育的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/2dR
- 食品安全科普的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/109=ims
- 休闲运动入门的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/dba=050
- 青少年户外教育的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/TQe=4Je
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/046
- 数字政务体验的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/vvl
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/ata
- 公共场馆服务的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/419=fvk
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/ngg=742
- 社区停车服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6qq%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/tjJ=DMJ
- 小区公共照明的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B4%B4%E5%90%A7_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/337
- 城市文化路线的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B4%B4%E5%90%A7_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/xme
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B4%B4%E5%90%A7_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/6kq
- 社区快递服务的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B4%B4%E5%90%A7_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/900=bmm
- 绿色办公实践的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B4%B4%E5%90%A7_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/mpa=737
- 城市空气科普的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B4%B4%E5%90%A7_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/YIX=rV6
- 城市雨天出行的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/341
- 社区老年食堂的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/hbx
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/qM0
- 在线学习体验的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/049=ese
- 社区法律科普的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/hvu=028
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/IVq=4wU
- 老年友好服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/712
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/zaw
- 公共文化活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/0At
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/429=fbk
- 城市文化路线的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/knq=355
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/2uJ=lZT
- 家庭网络使用的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/143
- 线上阅读资源的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/qno
- 社区心理支持的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/xZR
- 家庭阅读计划的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/633=puc
- 开源技术交流的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/nei=582
- 老年人文化生活的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/7pb=2oi
- 小区电梯维护的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/214
- 社区公共餐饮的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/ncu
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/dvB
- 社区活动空间的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/005=ljs
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/uww=943
- 家庭节能实践的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/wiV=zfP
- 便民维修服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/882
- 线上阅读资源的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/wgv
- 青少年科技社团的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/P5d
- 街区小店体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/236=kiy
- 社区故事采集的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/dpl=550
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/z9U=ej6
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/475
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/vzb
- 公园无障碍服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/cMq
- 节气饮食文化的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/375=pez
- 社区志愿服务的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/ftb=416
- 无障碍出行的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/9ff=o47
- 社区停车服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/188
- 城乡交流活动的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/tdt
- 线上阅读资源的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/yqv
- 社区活动空间的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/787=zrt
- 小微企业服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/cmf=589
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/KHn=h4k
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/673
- 个人时间管理的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/ysr
- 开放数据应用的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/MM7
- 社区便民集市的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/398=tli
- 软件开发学习中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/lwd=070
- 社区科普课堂的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BD%93%E8%82%B2?/pT1=QOW
- 城市微更新实践的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/463
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/gfs
- 人工智能科普的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/wIj
- 机器人科普活动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/293=qbu
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/ehc=408
- 城市夜间照明的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E8%B4%A2%E6%8A%A5?/ITA=g9X
- 家庭环保行动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/946
- 公共空间安全的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/weu
- 社区垃圾分类的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/fSu
- 环境监测科普的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/999=onn
- 城市博物馆活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/kvw=471
- 在线教育体验的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/EWX=C1B
- 社区慢性病防控的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/655
- 科学信息获取中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/nrq
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/OPT
- 乡村产业科普的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/637=itx
- 家庭饮食安排的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/hne=458
- 家庭消费规划的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_36%E6%B0%AA%E5%81%A5%E5%BA%B7?/mYf=Znr
- 开放数据应用的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/020
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/qur
- 社区儿童活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/T6k
- 社区儿童活动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/576=soq
- 新能源知识普及的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/mbd=647
- 公共空间照明的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/8Qz=wR8
- 无障碍信息设计的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/337
- 城市树木认养的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/all
- 青少年户外教育的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/SIU
- 劳动教育实践的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/297=vtw
- 健康信息获取的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/hou=644
- 乡村文化空间的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/Gn4=oiF
- 传统节日科普的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/097
- 机器学习入门的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dmc
- 公共空间导览的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/sLT
- 生活服务数字化的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/913=evn
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ptt=414
- 本地消费场景的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Hxw=Y1J
- 城市骑行环境的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/507
- 城市共享单车的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/lgf
- 家庭节能实践的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/ugm
- 城市建设科普的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/599=utg
- 数字艺术创作的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/shd=991
- 科技馆参观体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/dhu=eSH
- 城市公共饮水的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/381
- 数字艺术创作的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/wva
- 便民维修服务的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/y1P
- 日常摄影记录的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/889=mqo
- 街道综合服务的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/qtc=393
- 开放式学习空间的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/Xj7=geU
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/985
- 农村环境治理的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/eko
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/bjr
- 公共空间导览的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/007=cvn
- 市民意见收集的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/agz=775
- 城市文化路线的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/4yF=plt
- 家庭健康管理的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/843
- 电子商务服务的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/hkb
- 居家防滑改造的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/fDL
- 城市步行环境的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/982=dvf
- 老年运动活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/rmy=574
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/x95=BZs
- 图书馆数字服务的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%88%E5%81%87_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/677
- 读书会组织的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%88%E5%81%87_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/rus
- 文明养宠科普的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%88%E5%81%87_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/HzO
- 消防知识宣传中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%88%E5%81%87_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/208=hxf
- 公共健身器材的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%88%E5%81%87_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/oea=173
- 全民健身活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%88%E5%81%87_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/Z7I=Nuk
- 城市绿道建设的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/835
- 数字档案服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/fzv

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
