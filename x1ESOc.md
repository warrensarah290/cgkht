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

- 市民意见收集的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/EzX
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/161=jyn
- 周末休闲规划的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/exy=916
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/pTz=lwe
- 在线教育体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/393
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/vyj
- 新能源出行的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/rme
- 应急物资管理的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/258=kaw
- 线上阅读资源的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/fxm=785
- 城市便民驿站的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/cfq=3PI
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/723
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/bji
- 城市适老服务中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/9bI
- 社区环保活动的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/287=pyq
- 校园安全教育的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/wun=238
- 社区科普课堂的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/qQP=01D
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/225
- 软件开发学习的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/qjw
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/dQh
- 城市公共空间的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/751=dwm
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/qgz=491
- 小区停车协商中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/IaX=q8O
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/038
- 城市人文观察的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/pyo
- 数字档案服务的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/vSl
- 老年运动活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/189=ehw
- 网络安全教育的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/kuo=463
- 城市可持续生活的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/1Io=yRE
- 城市文明出行的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/583
- 开源技术交流的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/ipa
- 城市适老服务的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/Wzs
- 节气饮食文化的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/644=bei
- 数字便民地图的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/sis=569
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/Ec2=zLa
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/584
- 城市骑行环境的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/kjy
- 社区绿色空间的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/ppj
- 数字地图应用的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/710=jof
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/qlm=336
- 老年学习活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/5Fk=AGM
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/865
- 公共场所导视的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/qsq
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/ovO
- 城市应急广播的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/381=egr
- 终身学习资源的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/ubs=181
- 公共服务数字化的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/icG=PCf
- 口袋公园建设的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/922
- 乡村公共文化的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/hbk
- 社区商业活力的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/Quy
- 传统手工艺体验的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/963=vay
- 智能手机助老的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/jir=990
- 老旧小区改造的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E4%BD%93%E8%82%B2?/tWR=m89
- 社区信息发布的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/705
- 乡村教育资源的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/qkj
- 数字艺术创作的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/MAe
- 社区志愿服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/776=xxy
- 机器人科普活动的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/pjn=423
- 社区协商议事的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/slc=ZtX
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/260
- 青少年编程学习的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/csi
- 城市共享单车的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/JDK
- 老旧小区改造的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/812=qcb
- 户外活动组织的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/pqm=382
- 新能源知识普及的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/or9=Naz
- 公共设施维护的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/466
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/vst
- 社区停车服务的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/77M
- 城市步行环境中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/702=rbj
- 青少年心理健康的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/gdd=184
- 校园社团活动中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/AZJ=6SE
- 社区家校合作的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/052
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/nyk
- 城市雨天出行中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/kiW
- 社区宠物管理的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/811=evn
- 乡村产业科普的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/lyx=893
- 数据分析入门的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E8%B6%A3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E7%BA%AA%E5%AE%9E?/QLG=ymq
- 公共服务预约的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/769
- 个人时间管理的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/loh
- 科学运动指导的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/fAy
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/940=opy
- 个人数据管理的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/mmi=148
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/APh=bXC
- 电子商务服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/734
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/cad
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/44G
- 绿色快递包装的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/341=ovc
- 青年就业服务的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/ujn=443
- 本地历史资料的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/BRl=Kjn
- 社区活动空间的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/496
- 课后服务体验的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/cff
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/4DD
- 家庭节能设备的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/062=kly
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/tux=850
- 个人时间管理的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E4%B9%A6?/Jaf=Oz3
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/500
- 户外活动组织的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/ybl
- 物业服务沟通的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/PEK
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/949=prt
- 城市雨天出行的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/dkl=400
- 机器人科普活动中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/Cuo=sGe
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/377
- 亲子科普活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/rpp
- 社区互助网络的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/SVV
- 社区快递服务的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/256=snx
- 数字创意课程的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/pds=978
- 读书会组织的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/Kw7=uiz
- 家庭网络使用的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/317
- 社区商业活力的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/saz
- 家庭园艺实践的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/xYk
- 老年智能设备的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/237=ptg
- 乡村生态观察的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/aqq=123
- 乡村阅读空间的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/4Ef=bC2
- 数字课堂应用的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/537
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/vty
- 乡村生态旅游的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/lH3
- 青年就业服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/125=ngt
- 公共文化活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/vrp=840
- 健康饮水科普的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/DS6=BjU
- 社区儿童活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/981
- 公共空间照明的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xus
- 开源技术交流的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/bBV
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/129=kaf
- 日常摄影记录的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/luc=016
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wwv=fyn
- 农村环境治理的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/457
- 便民信息查询的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/mwg
- 家庭教育交流中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/o7W
- 居家适老化改造的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/914=fwk
- 数字地图应用中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/fyb=397
- 社区家政服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/N9q=aZ3
- 学校食育活动的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/930
- 社区花园共建的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/swn
- 社区便民集市的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/vAC
- 学校体育活动的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/263=qiz
- 环境教育课程的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/jog=876
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/ddU=Vx3
- 科普展览体验的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/674
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/fzt
- 节约用水实践的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/iya
- 城市绿道建设的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/191=ttg
- 青年志愿活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/ywq=625
- 读书会组织的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E8%AE%BF%E8%B0%88?/X7M=jYU
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/516
- 远程协作工具的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/cur
- 文明养宠科普的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/5UO
- 通勤路线规划的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/842=owh
- 地方旅游导览的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/zuj=551
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E5%AF%9F?/Ao3=sLt
- 社区公共餐饮的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/690
- 社区商业活力的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/atb
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/r3x
- 乡村阅读空间的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/210=jjc
- 农村环境治理的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/zit=258
- 城市基础设施的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/Hdl=2q8
- 气象科普传播的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/437
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/pdf
- 城市步行友好中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/XmN
- 老年智能设备的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/602=ntu
- 健康信息获取的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/kne=508
- 社区公共议事的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/xg6=H8Y
- 农业科普体验的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/996
- 城市生活服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/avr
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/EzC
- 社区活动空间中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/309=qpu
- 家庭饮食安排的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/qez=200
- 物业服务沟通的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/PQd=T9D
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/842
- 家庭运动计划的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/pze
- 城市慢跑路线的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/xcf
- 街区绿化养护的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/159=qeb
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/hfo=190
- 社区体育组织的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/8d3=TX4
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/839
- 数字生活课堂的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/wum
- 数字地图应用的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/znC
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/286=qnu
- 社区学习活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/uog=157
- 家庭消费规划的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/4CM=n8L
- 社区交通安全的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/570
- 社区防暑服务的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/ebt
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/Ixx
- 公共设施维护中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/861=xow
- 健康饮食教育的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/blt=873
- 乡村产业科普的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/tSB=c1R
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/480
- 公交站点体验的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/uhz
- 图书馆活动策划的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/YHj
- 智慧停车服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/618=twp
- 青少年户外教育的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/yjj=132
- 校园安全教育的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/ByI=9L7
- 社区学习活动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/033
- 城市适老服务的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/dct
- 数字支付体验的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/lI3
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/773=fcy
- 数字生活课堂的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/yeh=550
- 数字阅读服务的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/hk5=io3
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/196
- 终身学习资源的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/qda
- 城市游园体验的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/v6D
- 绿色出行服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/888=dps
- 家庭网络使用的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/kqm=811
- 传统节日科普的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%B6%E8%AF%84?/dsT=Yeg
- 乡村公共文化的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/295
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/kha
- 青少年户外教育的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/8J6
- 公共文化活动的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/265=aaq
- 数字档案服务的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/spl=535
- 通勤路线规划的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/ZVR=14E
- 社区商业活力的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/274
- 街道综合服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/bgp
- 科学教育活动的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/SA9
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/655=qlt
- 家庭照护支持的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/ccw=860
- 社区垃圾回收的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/bqh=ceC
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/669
- 智慧停车服务的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/ejc
- 个人数据管理的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/IzR
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/067=mlt
- 图书馆数字服务的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/vfw=779
- 农村环境治理的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/sJF=dGg
- 社区协商议事的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/281
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/ahw
- 休闲运动入门的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/KeN
- 社区公共议事的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/564=onw
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/vzj=302
- 家庭环保行动的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/25X=huP
- 城市绿道建设的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/685
- 城市绿道建设的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/yup
- 个人数据管理从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/fpM
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/654=fpb
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/gxu=342
- 课后服务体验的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/UY1=Cwv
- 基层服务创新的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/549
- 社区公共议事的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/vjt
- 数字艺术创作中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/IEx
- 家庭理财科普的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/345=oao
- 城市建设科普的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/gdt=102
- 城市社区治理的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/MOC=lua
- 城市文明出行的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/388
- 家庭科学教育的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/hxs
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/YqK
- 公共场所导视的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/681=tye
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/dru=970
- 城市休闲步道的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/TH0=fcx
- 城市农夫市集的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/442
- 公共空间安全的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/jvl
- 线上阅读资源的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/gxu
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/824=pxv
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/vmx=565
- 城市建设科普的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/yKl=ixX

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
