# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 数字政务体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/053
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/sxx
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/kUc
- 家庭防灾准备的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/134=krj
- 电动汽车充电的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/nqi=147
- 终身学习资源的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/WbP=6hg
- 药品使用科普的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_55%E4%B8%96%E7%BA%AAAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/830
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_55%E4%B8%96%E7%BA%AAAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/vgp
- 电动汽车充电的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_55%E4%B8%96%E7%BA%AAAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/ZG5
- 生活服务数字化的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_55%E4%B8%96%E7%BA%AAAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/698=ecm
- 老年人日常照护的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_55%E4%B8%96%E7%BA%AAAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/ter=137
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_55%E4%B8%96%E7%BA%AAAPP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/7ft=zkm
- 公共空间休憩的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-welcome%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/453
- 物业服务沟通的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-welcome%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/fpm
- 社区生活指南的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-welcome%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/fIl
- 家庭运动计划的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-welcome%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/823=sqj
- 公共服务数字化的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-welcome%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/zon=237
- 数字学习资源的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_55%E4%B8%96%E7%BA%AA-welcome%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/vOu=XPE
- 数字公共文化的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/963
- 家庭环保行动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/wen
- 电子商务服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/ZS6
- 居家适老化改造的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/359=vaj
- 地方文化传播的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/ihi=493
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/p4g=fkP
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/379
- 数字创意课程的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/myf
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/APC
- 小微企业服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/956=aki
- 公益活动组织的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/vkv=155
- 青少年编程学习的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BC%97%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%A7%91%E6%8A%80?/U4s=4pY
- 全民阅读推广的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/414
- 社区儿童活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/roo
- 无障碍出行的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/JG6
- 城市应急广播的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/477=giy
- 乡村文化活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/emd=770
- 终身学习资源的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E4%BC%97%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/51Z=VAL
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/015
- 社区便民集市的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/ecs
- 乡村阅读空间的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/ZZC
- 学校食育活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/188=zni
- 城市生活记录的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/ibr=152
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/zUX=Cqe
- 社区心理支持的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/121
- 线上办事服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/qji
- 城市社区治理的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/JJx
- 乡村文化空间的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/938=ums
- 绿色快递包装的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/zfp=231
- 社区运动空间的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_886%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/tPy=XLp
- 数字便民地图的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/880
- 社区故事采集的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/hwe
- 城市建设科普的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/53w
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/819=oyl
- 青少年户外教育的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/bsm=911
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_886%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/T1B=9lM
- 社区志愿服务的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/995
- 社区健康讲座的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/gpx
- 读书会组织的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/lD1
- 城市博物馆活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/175=cgz
- 跨代沟通活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/qtj=907
- 公共空间照明的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%89%B4?/G6P=IzW
- 社区商业活力的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/552
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/xtp
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/DZ3
- 地方文化传播的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/281=jir
- 智慧停车服务的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/bsr=369
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E4%BC%97%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/wfC=Crf
- 儿童友好空间的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/965
- 全民健身活动的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/tgw
- 新能源出行的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/xvb
- 城市空气科普的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/676=kyk
- 社区生活指南的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/hrg=927
- 老年学习活动的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/nVN=d0V
- 城市水环境观察的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E9%A6%96%E9%A1%B5%E5%AE%A2%E6%9C%8D_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/522
- 家庭教育交流的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E9%A6%96%E9%A1%B5%E5%AE%A2%E6%9C%8D_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/cwd
- 城市夜间照明中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E9%A6%96%E9%A1%B5%E5%AE%A2%E6%9C%8D_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/eXk
- 科学观察活动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E9%A6%96%E9%A1%B5%E5%AE%A2%E6%9C%8D_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/502=zxg
- 乡村生态观察的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E9%A6%96%E9%A1%B5%E5%AE%A2%E6%9C%8D_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/clh=135
- 全民阅读推广的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E5%BD%A9%E6%B1%87welcome%E9%A6%96%E9%A1%B5%E5%AE%A2%E6%9C%8D_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/PpU=Ru2
- 城市应急广播中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/588
- 医院导诊服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/elg
- 地方民俗记录的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/k1U
- 光伏知识科普的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/294=mey
- 城市夜间照明的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/jmn=670
- 急救知识普及的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/5QV=BRi
- 智慧停车服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B6%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/002
- 全民健身活动的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B6%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/oyg
- 社区设施共享的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B6%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/7R4
- 生成式工具使用的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B6%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/912=zdc
- 节日文化体验的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B6%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/per=174
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87-%E7%94%A8%E6%88%B6%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/7SL=QVn
- 社区便利生活的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/461
- 科学健身方法的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/uyh
- 家庭健康科普的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/4RK
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/503=vth
- 公共设施使用的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/bwh=745
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/E9F=D1G
- 公园休闲体验的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/427
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/qbc
- 公共服务沟通的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/uvM
- 医院导诊服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/160=hzb
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/jml=864
- 城市夜间照明的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A6%81%E9%97%BB?/J6T=D3R
- 科普展览体验的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/316
- 无障碍出行的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/anb
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/Dh9
- 数字课堂应用的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/059=fib
- 城乡交流活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/ooe=738
- 青年职业探索的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/e0W=kzu
- 社区互助网络的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/307
- 数字档案服务的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/ydg
- 社区商业活力的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/4B5
- 青少年户外教育的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/750=lge
- 家庭健康管理中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/bug=763
- 城市夜间生活的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/I8d=0wf
- 公共空间安全的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/846
- 物业服务沟通的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/tat
- 公共服务沟通的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/UL5
- 社区安全巡查的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/548=zus
- 城市人文观察的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/yhh=088
- 应急物资管理的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A8%BF?/asg=nL8
- 智慧停车服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/220
- 社区协商议事的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/uyv
- 居家防滑改造的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/mOU
- 社区停车服务的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/211=xaa
- 乡村文化空间的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/olj=239
- 家庭收纳实践的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/ra6=yRP
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/514
- 健康饮水科普的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/kzx
- 公园无障碍服务的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/qwK
- 邻里共享空间的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/055=gpk
- 社区信息发布的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/iss=173
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%93%B6%E6%B2%B3%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/PgM=HiO
- 乡村公共服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/978
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/vef
- 城市共享单车的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/v5H
- 城市生活记录的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/258=dlj
- 个人时间管理的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/chm=522
- 小区电梯维护的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/4VX=gzk
- 农业科普体验的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/616
- 节日文化体验的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/ohe
- 绿色校园实践的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/QGZ
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/478=rtx
- 城市文化路线的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/szu=359
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/PpF=ZBc
- 环境教育课程的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/986
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/nur
- 科技馆参观体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/F4Q
- 公共服务指南的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/481=nzd
- 社区阅读服务的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/iaz=402
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/zjR=lym
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A98app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/457
- 乡村产业科普的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A98app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/yak
- 传统节日科普的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A98app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/B6A
- 社区安全巡查的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A98app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/983=ixf
- 青少年科技社团的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A98app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/cod=859
- 城市体育设施的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%88%B1%E5%BD%A98app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/1uF=Qka
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A98%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/120
- 街区道路维护的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A98%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/diq
- 青年职业探索的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A98%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/R2n
- 老年人日常照护的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A98%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/087=kuh
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A98%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/aai=215
- 数字创作工具的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A98%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/37D=mcE
- 健康信息获取的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%9C%B0%E6%96%B9?/082
- 社区读书角建设的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%9C%B0%E6%96%B9?/gky
- 市民意见收集的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%9C%B0%E6%96%B9?/rTA
- 志愿者培训交流的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%9C%B0%E6%96%B9?/375=hmu
- 乡村公共服务的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%9C%B0%E6%96%B9?/ryc=773
- 社区共享书架的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%88%B1%E5%BD%A98%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E5%9C%B0%E6%96%B9?/PI9=mYz
- 城市生活服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/935
- 乡村教育资源的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/kzg
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/pss
- 生活垃圾回收的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/886=yzc
- 社区邻里服务的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/dnf=329
- 节能生活方式的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/OUE=2WM
- 休闲运动入门的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/633
- 数字生活课堂的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/osl
- 社区宠物管理的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/fGV
- 家庭照护支持的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/885=tnp
- 公共交通接驳中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/ewv=733
- 城市公共空间的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A98%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/T1i=AR3
- 社区休闲设施的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A98IOS_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/361
- 地方民俗记录的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A98IOS_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/fko
- 城市公共艺术的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A98IOS_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/ApQ
- 非遗体验活动的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A98IOS_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/335=ujo
- 科普展览体验的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A98IOS_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/wnl=432
- 城市空气科普的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A98IOS_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/BLw=1if
- 社区协商议事的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%88%B1%E5%BD%A98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/674
- 居家防滑改造的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%88%B1%E5%BD%A98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/kvo
- 青少年科普实践的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%88%B1%E5%BD%A98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/aR2
- 社区便民集市的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%88%B1%E5%BD%A98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/805=crg
- 志愿服务平台的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%88%B1%E5%BD%A98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/tkj=793
- 课后服务体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%88%B1%E5%BD%A98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/pmW=1sR
- 数字政务体验的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/785
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/gdo
- 社区休闲设施的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/sMT
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/932=tqm
- 科学观察活动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/vlz=458
- 绿色消费选择的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/lLC=Ky5
- 数字阅读服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/710
- 街区小店体验中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/yqa
- 城市绿色交通的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/ZU6
- 社区教育资源的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/349=den
- 乡村文化活动的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/msa=951
- 青年就业服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/FCm=CjL
- 社区活动空间的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%918719_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/100
- 街头绿植养护的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%918719_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/nnu
- 基层服务创新的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%918719_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/Gyb
- 校园节能行动的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%918719_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/187=bax
- 生活垃圾减量的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%918719_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/onb=439
- 数字设备回收的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BD%918719_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/9uM=cHw
- 社区公共餐饮的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/723
- 数字艺术创作的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/xdn
- 公共空间导览的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/y6L
- 科学观察活动的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/317=qku
- 社区庭院绿化的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/lbq=519
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/Nd9=Odj
- 数字支付体验的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/474
- 社区阅读服务的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/jiz
- 城市便民驿站的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/7UY
- 社区防暑服务的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/368=bst
- 社区公共卫生的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/xbx=926
- 城市文明出行的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/5ZD=c2j
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/183
- 传统节日科普的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/spb
- 乡村生态观察的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/WLv
- 家庭节能设备中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/197=ofu
- 公交站点体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/bsv=592
- 农产品品牌传播的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/yNx=iqJ
- 便民维修服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%9B%BD%E9%99%85?/629
- 非遗课堂体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%9B%BD%E9%99%85?/trb
- 儿童户外活动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%9B%BD%E9%99%85?/r7s
- 基层医疗预约的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%9B%BD%E9%99%85?/260=aku
- 数字公共文化的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%9B%BD%E9%99%85?/jsj=959
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%8F%B7%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%9B%BD%E9%99%85?/ngN=97W
- 远程协作工具的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/350
- 城市雨天出行的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/bjk
- 城市可持续生活的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/rBX
- 市民意见收集的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/944=pgh
- 邻里共享空间的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/lkw=923
- 数字课堂应用的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/kMO=QlK
- 劳动教育实践的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/715
- 城市微更新实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/fsr
- 数字创作工具的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/Ph1
- 社区法律科普的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/323=xfp
- 公园无障碍服务的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/bqd=526
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/92V=tMC
- 青少年科普实践的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%88%B1%E5%BD%A9%E4%B9%90_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/541
- 社区停车服务的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%88%B1%E5%BD%A9%E4%B9%90_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/usn
- 市民意见收集的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%88%B1%E5%BD%A9%E4%B9%90_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/Hsr
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%88%B1%E5%BD%A9%E4%B9%90_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/253=abi

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
