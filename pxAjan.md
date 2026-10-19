# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 家庭健康管理中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91vll-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/MMf
- 创业经验分享的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91vll-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/217=pvf
- 节日文化体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91vll-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/piq=407
- 社区阅读服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91vll-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/Sa6=yAe
- 线上阅读资源的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91vll-APP_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/391
- 图书馆活动策划的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91vll-APP_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/fzr
- 家庭环保行动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91vll-APP_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/R45
- 社区知识分享的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91vll-APP_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/921=slr
- 人工智能科普的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91vll-APP_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/qdb=312
- 社区设施共享的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91vll-APP_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/tTS=huo
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/409
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/aai
- 社区活动空间的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/KWg
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/222=ldh
- 公共空间照明的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/grn=421
- 社区公共餐饮的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/ETk=5be
- 社区应急准备的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/113
- 家庭健康科普的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/kcf
- 城市建设科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/PJD
- 家庭防灾准备的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/120=oem
- 生活服务数字化的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/cow=671
- 公园亲子设施的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%BF%B0%E8%AF%84?/YUk=UVN
- 数字政务体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vll-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/880
- 城市可持续生活的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vll-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/kso
- 生成式工具使用的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vll-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/EJT
- 居家防滑改造的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vll-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/174=cjt
- 数字资源检索的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vll-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/rvk=486
- 社区公共议事的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vll-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/NS9=piI
- 家庭节能实践的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/372
- 社区菜市场服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/ekr
- 科学运动指导的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/Tta
- 家庭节能设备的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/477=qro
- 社区共享书架的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/nsj=441
- 社区停车服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/RxZ=n3I
- 家庭节能实践的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/234
- 生活垃圾回收的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/fuv
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/cRx
- 课后服务体验中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/517=vfn
- 图书馆活动策划的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/muc=899
- 健康步道使用的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/dM9=7Tv
- 城市共享单车的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91vll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/877
- 城市步行友好的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91vll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/eup
- 数字课堂应用的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91vll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/fUn
- 公共服务数字化的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91vll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/741=nid
- 公交站点体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91vll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/qky=819
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91vll-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/AYd=IC9
- 农产品消费体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/583
- 乡村生活观察的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/nez
- 垃圾分类指导的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/pxi
- 青少年科技社团的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/044=lym
- 老年人文化生活的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/prw=584
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91vll-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/Rw7=VGQ
- 社区志愿服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/797
- 家庭收纳实践的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/tkd
- 地方文化传播的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/UQN
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/661=ajm
- 社区消防演练的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/hle=680
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/Jqv=h0o
- 老年数字阅读的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91vll-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/989
- 科学观察活动的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91vll-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/isz
- 传统节日科普的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91vll-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/f3q
- 家庭饮食安排的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91vll-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/358=foi
- 青年志愿活动的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91vll-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/exj=770
- 数字支付体验中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91vll-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/a7q=av7
- 智慧停车服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91vll-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/860
- 亲子科普活动的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91vll-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/yrk
- 乡村产业科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91vll-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/J8r
- 科学教育活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91vll-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/205=zsy
- 绿色生活实践的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91vll-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/tal=704
- 在线教育体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91vll-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%85%AC%E5%91%8A?/YCi=u43
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/523
- 校园社团活动的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/isz
- 图书馆活动策划的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/zHp
- 家庭节能设备的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/455=cby
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/gkb=361
- 急救知识普及的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/i8B=AJc
- 乡村生活观察的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/532
- 绿色出行服务的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/vzc
- 创业经验分享的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/PPm
- 家庭网络使用的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/536=vlw
- 社区活动报名的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/ofq=864
- 新能源知识普及的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/SgR=Eag
- 家庭志愿活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/162
- 社区文化传播的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/iuq
- 社区学习活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/3Rf
- 数字便民地图的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/312=urc
- 社区安全巡查的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/scl=842
- 文明养宠科普的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/OhX=Kwd
- 社区休闲设施的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/876
- 老年学习活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/rxu
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/Afb
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/960=ixa
- 乡村公共服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/sru=482
- 社区托育服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/EFG=sjC
- 学校食育活动的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/200
- 社区便利生活的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/ujc
- 家庭饮食安排的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/35d
- 健康步道使用的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/893=hyb
- 学校体育活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/aez=216
- 数字地图应用中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/Miu=L2D
- 小区公共照明的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/190
- 社区文化传播的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tbu
- 城市公共艺术的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/U47
- 街头绿植养护的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/304=taj
- 便民服务地图的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/gzp=158
- 应急物资管理的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95welcome_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/RIG=Ira
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/568
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/xhm
- 社区健康讲座的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/iAj
- 公共服务评价的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/247=rqm
- 城市文化路线的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/akp=458
- 城市公共座椅的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/26b=cCS
- 本地消费场景的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/398
- 志愿服务平台的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/sym
- 社区共享书架的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/Ncm
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/562=zak
- 青少年科普实践的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/bcq=720
- 邻里共享空间的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/Wqj=lEx
- 社区防暑服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%912-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/088
- 学校体育活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%912-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/eqa
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%912-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/UnO
- 家庭运动计划的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%912-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/636=ocv
- 社区知识分享的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%912-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/zxe=070
- 城市游园体验的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%912-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/95R=j3d
- 乡村文化空间的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/135
- 绿色出行服务的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/orb
- 学校体育活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/zY8
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/318=pxk
- 居民健康教育的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/kda=514
- 急救知识普及的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%912-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/ZLf=oIw
- 市民热线服务的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%912-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/780
- 节约用水实践的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%912-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/sfn
- 本地消费场景的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%912-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/lul
- 数据分析入门的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%912-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/034=vas
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%912-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/pej=124
- 农贸市场环境的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%912-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/giU=H0o
- 低碳社区实践的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912-APP_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/896
- 城市地名文化的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912-APP_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/trd
- 社区花园共建的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912-APP_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/3wI
- 健康信息获取的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912-APP_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/945=iem
- 节能家电使用的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912-APP_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/bom=457
- 运动安全知识的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912-APP_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/yNk=wdd
- 健康信息获取的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/106
- 社区活动策划的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/vbj
- 数字阅读服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/gb1
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/356=uwc
- 邻里共享空间的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/vnw=042
- 网络安全教育的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%912-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/p1m=Iby
- 家庭食品保存的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/143
- 社区儿童活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/eio
- 公共图书馆服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/syV
- 健康饮食教育的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/772=mey
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/unm=884
- 城市文化路线的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/pkh=NaW
- 数字便民地图的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/382
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/nkl
- 公共图书馆服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/2Mf
- 社区消防演练的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/319=jmy
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/oec=984
- 城市可持续生活的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%912-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B?/RIF=YNr
- 小区电梯维护的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%912-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/261
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%912-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/qzq
- 社区活动空间的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%912-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/3Fw
- 街区绿化养护的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%912-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/337=wvv
- 青少年心理健康的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%912-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/esv=284
- 公益活动组织的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%912-%E6%B3%A8%E5%86%8C_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/hhP=Fw9
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/982
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/pou
- 课后服务体验的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/vDj
- 新能源知识普及的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/103=pke
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/pmp=319
- 城市慢行系统的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/6D2=ixl
- 终身学习资源的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/588
- 旧物循环利用的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/kzx
- 职业技能学习的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/wkZ
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/772=vdu
- 社区艺术活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/syv=155
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%912-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E5%BF%AB%E8%AE%AF?/AyJ=QNL
- 数字课堂应用的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/779
- 开放数据应用的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/ptn
- 青少年科普实践的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/JJJ
- 乡村公共阅读的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/358=gmq
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/cqr=454
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/Cnb=9L4
- 职业技能学习中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%912-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/964
- 开放数据应用中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%912-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/mkd
- 街区小店体验的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%912-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/z6N
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%912-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/693=jik
- 生活垃圾减量的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%912-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/ldo=012
- 社区运动空间的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%912-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/6ZO=yJl
- 城市文明出行的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/834
- 无障碍出行的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/dsn
- 气象科普传播的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/JMG
- 城市水环境观察的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/923=cex
- 城市应急广播的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/cbv=437
- 城市建设科普的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%912-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/iZC=5qY
- 数字学习资源的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/995
- 社区艺术活动的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/ggk
- 劳动教育实践的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/Vlj
- 运动安全知识的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/560=ewn
- 社区设施共享的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/woe=482
- 城市生活记录的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%912-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/IOG=zQ6
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/922
- 急救知识普及的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/iwb
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/0XO
- 社区公共卫生的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/083=jim
- 社区教育资源的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/viy=630
- 公共设施维护的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91vlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/xmc=dYI
- 绿色生活实践的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91vlll-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/411
- 课后服务体验的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91vlll-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/pqn
- 公共空间安全的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91vlll-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/xpq
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91vlll-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/266=toi
- 公交站点体验的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91vlll-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/ijh=016
- 光伏知识科普的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91vlll-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/R7R=sQs
- 旧物循环利用的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/914
- 节能生活方式的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/fcl
- 街头绿植养护的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/CyB
- 社区老年食堂的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/098=hcl
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/eqh=680
- 城市基础设施的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/2in=47L
- 绿色出行服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/790
- 社区花园共建中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/tlq
- 老年数字阅读的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/C7l
- 骑行路线规划的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/915=kzz
- 物业服务沟通的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/eef=191
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/uZr=3dh
- 社区手工活动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/863
- 安全出行教育的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/har
- 青年志愿活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/452
- 儿童友好街区的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/361=fpm
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/wle=743
- 公共交通接驳的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/1tW=jKc
- 城市空气科普的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/818
- 急救知识普及的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/nus
- 绿色出行服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/a4W
- 青少年科普实践的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/992=rjd
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/iix=837
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91vlll-%E7%99%BB%E5%BD%95welcome_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/4yI=7PA
- 药品使用科普的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/149
- 运动安全知识的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/pwr
- 社区便民集市的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/1dT
- 城市休闲步道的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/336=pxv
- 儿童友好空间的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/bgv=767
- 家庭志愿活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91vlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/OWe=02W
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/699
- 公共交通信息服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/dlq
- 数字课堂应用的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/eK7
- 乡村文化空间的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/610=qid
- 城乡交流活动的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/jhe=671
- 小区停车协商的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91vlll-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/8lw=6Xc

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
