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

- 公园亲子设施的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/sox=059
- 乡村生态观察的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/3wE=vOb
- 家庭健康管理的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/665
- 智慧停车服务的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/hfb
- 城市骑行环境的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/hT6
- 社区健康讲座的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/948=rjt
- 城乡交流活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/dvr=311
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/obK=bXs
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/762
- 地方戏曲体验的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/mgl
- 社区法律科普的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/qmB
- 社区知识分享的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/172=lzp
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/wqi=481
- 街道综合服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/lIg=71d
- 通勤路线规划的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/613
- 城市慢行系统的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zyu
- 光伏知识科普的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/T8u
- 青少年心理健康的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/477=dyi
- 周末休闲规划的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zes=201
- 公共设施使用的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/28w=xw7
- 线上阅读资源的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/790
- 公益活动组织的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/tts
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/Rid
- 老年友好服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/328=xbp
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/own=128
- 城市住房服务的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/OEM=QyW
- 社区便利生活的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/462
- 社区设施共享的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/dte
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/dhT
- 农产品消费体验的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/737=kkn
- 老年智能设备的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ihn=830
- 基层医疗预约的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/2c6=EZs
- 公共图书馆服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/610
- 公共空间照明的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/kxu
- 健康步道使用的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/4tF
- 绿色办公实践的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/464=ext
- 数字生活课堂的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/cnv=833
- 街区小店体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/mDq=DXi
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93?/517
- 公共卫生宣传的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93?/wcf
- 药品使用科普的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93?/RGh
- 社区垃圾分类的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93?/300=wtv
- 全民阅读推广的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93?/pgn=391
- 家庭环保习惯的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93?/qO7=sP3
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/409
- 在线教育体验的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/uaq
- 老年智能设备的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/2e5
- 电动汽车充电的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/576=woa
- 家庭饮食安排的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/ypn=862
- 基层健康档案的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%A3%E5%AF%86?/gAr=dED
- 公共场所导视的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/616
- 科普展览体验的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/jpm
- 志愿服务平台的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/gmz
- 城市空气科普的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/348=cac
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/ppk=893
- 数字生活课堂的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/tbv=2VR
- 科学健身方法的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/344
- 图书借阅体验的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/ihx
- 个人信息保护的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/PLD
- 小区电梯维护的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/107=nia
- 社区公共卫生中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/ohh=125
- 居民健康教育的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/i2c=lwq
- 社区共享书架的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/152
- 地方旅游导览的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/cys
- 家庭志愿活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/Cz4
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/932=nnw
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/lrn=587
- 城市共享单车的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/Chh=gdB
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/075
- 城市公共座椅的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/jnv
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/Ces
- 家庭健康科普的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/897=lyh
- 便民服务地图的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/zte=734
- 青少年编程学习的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/J2C=qWy
- 便民服务地图的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/837
- 课后服务体验的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/adr
- 公共空间照明的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/2o8
- 健康步道使用的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/244=eqi
- 旧物循环利用的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/ctx=875
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/YgO=R6X
- 口袋公园建设的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%B6%88%E8%B4%B9?/123
- 城市文明出行的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%B6%88%E8%B4%B9?/wgb
- 社区家校合作中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%B6%88%E8%B4%B9?/rL5
- 科学信息获取的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%B6%88%E8%B4%B9?/488=huu
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%B6%88%E8%B4%B9?/nzz=093
- 日常摄影记录的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E6%B6%88%E8%B4%B9?/KOy=RpL
- 本地消费场景的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/562
- 乡村公共文化的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/ctf
- 本地消费场景中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/Iy0
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/466=cvu
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/sga=037
- 地方民俗记录的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/X9V=c9d
- 乡村公共阅读的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/127
- 租房信息服务中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/cho
- 社区家校合作的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/4bZ
- 小区电梯维护的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/261=tdp
- 居家适老化改造的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jva=452
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/NB1=gVr
- 学校食育活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/216
- 家庭饮食安排的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/dlp
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/LpK
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/484=cot
- 城市体育设施的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/auk=447
- 小区公共照明的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%9B%E6%8A%95?/gOb=7i8
- 基层健康档案的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/512
- 旧物循环利用的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/rhp
- 社区环保活动的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/Rrf
- 社区公共议事的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/584=rmj
- 便民服务地图的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/jzw=931
- 社区停车服务的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/rBG=ijR
- 在线教育体验的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/551
- 生活技能分享的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/gmy
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/oVh
- 社区安全巡查的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/366=pev
- 社区阅读服务的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/pdc=402
- 邻里互助活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/PpB=0yr
- 文明养宠科普的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/966
- 食品安全科普的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/bha
- 在线教育体验中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/BqO
- 社区互助网络的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/040=ojt
- 乡村阅读空间的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/rtb=487
- 家庭防灾准备的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%AE%B6%E5%B1%85?/ZZ4=2BE
- 城市地名文化的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/456
- 城市应急科普的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/gow
- 社区健康讲座的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/I8W
- 科技馆参观体验的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/858=yui
- 社区心理支持的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/btz=120
- 社区慢性病防控的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/ZIU=2MC
- 儿童户外活动的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/034
- 社区生活指南的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/spl
- 健康步道使用的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/qx6
- 社区老年食堂的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/120=eou
- 城市住房服务的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/ugy=296
- 劳动教育实践的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/FQG=WF3
- 节约用水实践的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/786
- 节能生活方式的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/rwn
- 乡村公共服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/dsE
- 老年人日常照护的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/897=eal
- 乡村生态旅游的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/jar=813
- 智慧城市体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/W7h=VOa
- 儿童户外活动中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/866
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/zww
- 家庭饮食安排的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/KFM
- 数字创作工具的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/906=pwu
- 社区宠物管理的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/mym=546
- 数字创意课程的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/2MI=oNl
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/755
- 城市住房服务的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/uen
- 公共服务指南的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/YCG
- 数字创意课程的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/595=szj
- 城市可持续生活的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/ymv=084
- 老年人日常照护的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%98%9F%E5%85%89%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/qtj=04i
- 基层医疗预约的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/101
- 城市共享单车的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/jai
- 公共服务预约的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/XnU
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/376=lnn
- 公共卫生设施的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/yjk=215
- 家庭养老规划的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%9B%B2%E8%89%BA?/yWl=BpX
- 社区商业活力的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/199
- 气象科普传播的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/cjt
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/W5U
- 数字公共文化的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/113=lus
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/bgl=425
- 社区阅读服务的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/brX=eNP
- 社区法律科普的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%88%B7%E5%A4%96?/343
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%88%B7%E5%A4%96?/qht
- 科普展览体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%88%B7%E5%A4%96?/Byd
- 文明养宠科普的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%88%B7%E5%A4%96?/203=pco
- 农贸市场环境的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%88%B7%E5%A4%96?/lgy=848
- 公共服务指南的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%88%B7%E5%A4%96?/VaF=Ugb
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/621
- 绿色校园实践的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/qih
- 家庭健康管理中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/nzW
- 开放式学习空间的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/565=hkj
- 城市展览体验的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/eoe=644
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E6%8A%A5?/5RT=s7s
- 食品安全科普的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/915
- 社区教育资源的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/wbo
- 乡村生活观察的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/piT
- 本地消费场景的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/268=rhj
- 节能家电使用的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/kvt=127
- 公共服务评价的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%85%AC%E7%9B%8A?/DAB=eJU
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/832
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/nhu
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/hSF
- 应急物资管理的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/947=yfw
- 社区养老服务的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/ynm=346
- 运动安全知识的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/CzR=6sH
- 社区儿童活动的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/393
- 非遗体验活动的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/ras
- 城市体育设施的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/26L
- 图书馆数字服务的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/540=cyv
- 健康饮食教育的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/dyu=336
- 社区阅读服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/x1a=t5V
- 城市可持续生活的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/204
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/duo
- 职业技能学习的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/t2G
- 节日文化体验的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/918=lsz
- 学校食育活动的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/qhs=404
- 个人信息保护的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/9BB=ezy
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/312
- 社区心理支持的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/ueo
- 家庭教育交流的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/T8e
- 街区小店体验的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/800=tfv
- 校园阅读活动的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/xva=235
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/dsw=dzD
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%82%A1%E7%A5%A8?/501
- 社区手工活动的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%82%A1%E7%A5%A8?/pvz
- 休闲运动入门的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%82%A1%E7%A5%A8?/wCp
- 家庭收纳实践的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%82%A1%E7%A5%A8?/826=fth
- 传统手工艺体验的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%82%A1%E7%A5%A8?/prb=628
- 智能家居应用的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%82%A1%E7%A5%A8?/76D=BWZ
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-APP_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/879
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-APP_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/mgy
- 社区科普课堂中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-APP_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/XOp
- 城市应急广播的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-APP_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/516=lel
- 在线教育体验的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-APP_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/efn=343
- 乡村生态观察的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-APP_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/WQH=eXP
- 本地消费场景的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/770
- 街区小店体验的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/yvw
- 邻里互助活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/Kem
- 城乡交流活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/204=cxc
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/kyj=348
- 社区快递服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/3oj=SO6
- 远程协作工具的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/646
- 城市休闲步道中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/yqo
- 地方文化传播的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/nwx
- 食品安全科普的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/343=hdj
- 社区艺术活动的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/hav=742
- 数字便民地图的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/KIo=zyi
- 公共场所导视的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/931
- 老年友好服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/qcr
- 农产品消费体验的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/ns3
- 老年人日常照护的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/883=hoh
- 城市噪声观察的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/qry=851
- 数字素养提升的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E7%BA%AA%E5%AE%9E?/uYJ=VQV
- 环境教育课程的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/199
- 城市建设科普的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/atc
- 城市公共自行车的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/BmJ
- 节气饮食文化中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/332=xsu
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/ayu=772
- 社区儿童活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/a6G=VtU
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/831
- 城市社区治理的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/lbo
- 文化场馆预约的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/oSG
- 城市微更新实践的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/885=ekd
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/qjf=485
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/sDB=j10
- 城市可持续生活的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/016
- 地方文化传播的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%98%9F%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/wxg

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
