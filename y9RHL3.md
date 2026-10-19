# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 社区老年食堂的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/h0x
- 社区设施共享的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/173=iia
- 消防知识宣传的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/ccf=301
- 城市共享单车的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/5bc=RvL
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/422
- 科普展览体验的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/hnt
- 城市公共标识的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/oHJ
- 城市休闲步道的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/261=eyc
- 药品使用科普的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/wtx=108
- 通勤路线规划的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/2RF=ZVm
- 就业技能培训中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/152
- 急救知识普及的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/cdh
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/q01
- 乡村阅读活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/432=rvm
- 家庭用电安全的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/zsp=913
- 公交站点体验的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E8%A7%86%E9%A2%91?/fFn=Y86
- 环境教育课程的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/265
- 社区儿童活动的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/ski
- 数据分析入门的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/czA
- 公共服务咨询的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/798=fqi
- 社区活动策划的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/eaj=433
- 城市建设科普的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/WVu=P2A
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/622
- 社区协商议事的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/phz
- 儿童友好街区的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/2dY
- 城市应急广播的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/383=rjg
- 绿色出行服务的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/sqp=031
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/dxk=Y6e
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/901
- 全民健身活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/qjw
- 节能家电使用的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/Yxv
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/275=nxc
- 数据分析入门的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/zqr=305
- 线上阅读资源的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/Rdz=lD1
- 家庭科学教育的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/531
- 城市应急广播的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/dxj
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/mbc
- 创业经验分享的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/812=tty
- 社区公共议事的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/iof=111
- 家庭园艺实践的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/pKN=4e7
- 城市社区治理的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/819
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/lkn
- 老年人出行服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/cZ8
- 周末休闲规划中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/928=qyo
- 社区便利生活的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/ayl=980
- 城市步行友好的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/ZVl=IzL
- 农业科普体验的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/495
- 家庭科学教育的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/xrp
- 传统节日科普的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/mEd
- 便民服务地图的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/137=qjj
- 居家防滑改造的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/yvb=272
- 基层健康档案的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_10%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/YB7=75e
- 社区学习活动的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/098
- 基层服务创新的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/ewg
- 公共卫生设施的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/vfB
- 社区家校合作的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/966=vvi
- 绿色出行服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/iup=361
- 城市空气科普的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/6ED=L8L
- 社区设施共享的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/787
- 社区便利生活的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/exu
- 校园社团活动的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/u6g
- 网络安全教育的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/822=hpx
- 老年人日常照护的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/nzm=929
- 药品使用科普的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/bCm=tjH
- 家庭网络使用的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/072
- 社区消防演练的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/yol
- 公共服务数字化的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/rMg
- 地方美食文化的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/612=odt
- 通勤路线规划的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/ufg=668
- 社区便民服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_10%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/rVH=Ib5
- 小区停车协商的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/585
- 家庭环保行动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/ako
- 社区家政服务的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/tda
- 公共服务指南的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/945=qlo
- 数字地图应用的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/urh=662
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_10%E5%88%86%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/vSm=Kee
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/820
- 社区安全巡查的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/tov
- 公共图书馆服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/oH4
- 公园亲子设施的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/449=mrm
- 数字艺术创作的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/yng=260
- 绿色消费选择的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/YuE=OWu
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_10%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/494
- 儿童运动体验中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_10%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/crt
- 乡村生态观察的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_10%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/XVq
- 城市微更新实践的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_10%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/659=vop
- 社区运动空间的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_10%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/srs=724
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_10%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/PD2=cjb
- 公共空间安全的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/051
- 社区家校合作的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/npg
- 社区菜市场服务的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/IpE
- 社区文化节活动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/026=dxw
- 儿童运动体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/twf=250
- 乡村电商实践的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%9C%80%E5%87%86%E7%9A%84_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/MXN=oFQ
- 乡村产业科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/938
- 城市文明出行的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/gji
- 地方文化传播的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/6ZP
- 城市雨天出行的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/315=ypy
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/beb=574
- 社区花园共建的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_10%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/TtQ=7vu
- 城市文化路线的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/738
- 家庭园艺实践的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/fbg
- 小微企业服务的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/EMe
- 家庭环保行动的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/970=wht
- 居民健康教育的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/cys=424
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%85%AC%E5%BC%8F_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/aGi=P1i
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/286
- 社区生活指南的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/qcd
- 公共空间休憩的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/f15
- 乡村教育资源的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/759=mqp
- 节约用水实践的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/zls=293
- 居民健康教育的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%E7%AE%97%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/yVi=8HK
- 校园社团活动的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_10%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/979
- 青少年科技社团的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_10%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/jum
- 家庭阅读计划的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_10%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/l8H
- 家庭节能实践的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_10%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/928=icr
- 低碳社区实践的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_10%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/zcx=911
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_10%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/Jh7=Qji
- 数字政务体验的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_10%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/398
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_10%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/gdu
- 节能生活方式的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_10%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/pK2
- 地方文化传播的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_10%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/699=mfi
- 节能家电使用中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_10%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/fuv=687
- 数字设备回收的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_10%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/Rci=xVw
- 社区商业活力的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/943
- 城市公共饮水的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/ltz
- 公共空间导览的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/8zK
- 城市博物馆活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/609=yip
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/bap=217
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_10%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/cqw=xoa
- 食品安全科普的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/638
- 物业服务沟通中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/fpf
- 公共场所导视的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/PPb
- 社区生活指南中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/480=qax
- 城市绿色交通的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/iql=285
- 家庭环保行动的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_10%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/c4B=p50
- 青少年心理健康的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/426
- 邻里互助活动的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/btn
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/yj4
- 健康饮食教育中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/643=jju
- 社区教育资源的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/apn=486
- 数字阅读服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_10%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/8n8=7LD
- 青少年心理健康的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/495
- 城市慢行系统的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/faf
- 家庭收纳实践的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/Won
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/834=ewf
- 公共场馆服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/dck=549
- 基层医疗预约的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/8hU=KIE
- 街区小店体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/398
- 家庭消费规划的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/byq
- 社区安全巡查的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/oI7
- 社区公共议事的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/358=dfe
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/mpr=913
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/lle=l2F
- 城市适老服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/344
- 数字生活课堂的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/ozc
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/bke
- 社区商业活力的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/272=pdw
- 公共场所导视的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/snc=115
- 文明养宠科普的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_10%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/cI6=lAW
- 家庭运动计划的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/828
- 城市可持续生活的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/etb
- 城市公共座椅的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/GSO
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/321=oup
- 城市休闲步道的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/aeo=329
- 食品安全科普的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/Awf=Sp9
- 城市空气科普的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/452
- 节假日出行安排的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/ffj
- 公共交通接驳的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/rGM
- 数字支付体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/637=jar
- 社区菜市场服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/ojl=954
- 地方美食文化的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E5%8A%A8%E6%BC%AB?/Uvk=pnl
- 地方美食文化的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/454
- 青年志愿活动的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/phs
- 公交站点体验的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/2pg
- 城市适老服务的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/912=dbu
- 数字支付体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/irb=821
- 小区电梯维护的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_10%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/xie=kdG
- 家庭健康管理从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/103
- 社区活动策划的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/suu
- 社区儿童活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/bu6
- 城市公共饮水的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/358=ccs
- 城乡交流活动的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/apx=591
- 社区手工活动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/4u4=fCW
- 社区绿色空间的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/090
- 社区便民集市的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/dmg
- 城市慢行系统的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/Z2F
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/724=zba
- 社区应急准备的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/mhh=157
- 公共交通接驳的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/OuQ=BFc
- 健康信息获取的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/832
- 青少年心理健康的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/edk
- 城市应急科普的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/hEN
- 乡村文化活动的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/309=xxg
- 绿色建筑理念的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/bhc=334
- 医院导诊服务的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/9Vc=IIP
- 城市生活记录的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/193
- 社区公共卫生的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/qqu
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/5Rm
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/103=bll
- 开放式学习空间的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/eep=473
- 地方文化传播的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/cTR=frU
- 城市生活服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/029
- 儿童户外活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/xnr
- 老年人文化生活的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/9Eq
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/440=rbz
- 城市展览体验的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/uur=273
- 老年人文化生活的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/Wt6=TQX
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/614
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/hon
- 终身学习资源的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/kyP
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/970=aio
- 街道综合服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/org=577
- 社区托育服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/AG5=MRS
- 农产品品牌传播的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/047
- 社区学习活动的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/nui
- 城市文化路线的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/ZTc
- 运动安全知识的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/260=nid
- 医院导诊服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/bri=596
- 城市博物馆服务的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/BNQ=SGf
- 城市树木认养的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/274
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/vai
- 口袋公园建设的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/A71
- 城市步行友好的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/732=zwh
- 数字资源检索的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/njw=272
- 市民意见收集的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E4%BA%A4%E6%B5%81%E7%BE%A4_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/bRo=qaT
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%9298%25%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%921_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/925
- 生成式工具使用的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%9298%25%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%921_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/zgz
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%9298%25%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%921_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/6ut
- 社区活动策划的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%9298%25%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%921_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/445=iej
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%9298%25%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%921_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/byd=989
- 城市生活服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%AE%A1%E5%88%9298%25%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%921_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/gKM=B0Y
- 社区运动空间的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/838
- 社区老年食堂的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/ozg
- 文明养宠科普的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/DEU
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/558=jxa
- 街道综合服务的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/axd=521
- 公共场馆服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/Z6h=koB
- 节气饮食文化的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E8%80%81%E5%B8%88_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/262
- 街区更新实践的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E8%80%81%E5%B8%88_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/sua
- 社区故事采集的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E8%80%81%E5%B8%88_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/tM4
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E8%80%81%E5%B8%88_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/942=ajy
- 节日文化体验的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E8%80%81%E5%B8%88_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/pwu=626
- 农村环境治理的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E8%80%81%E5%B8%88_%E8%99%8E%E5%97%85%E5%AE%A0%E7%89%A9?/aa0=gqJ
- 城市适老服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/788
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/mzi
- 城市夜间照明的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/MxS
- 社区便民集市中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/181=byv
- 社区设施共享的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/frx=466
- 在线学习体验的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/sHe=I0R

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
