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

- 绿色出行服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/vyi=634
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/BDI=NPs
- 数字设备回收的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/439
- 城市公共厕所的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/zsi
- 青年志愿活动的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/Hqf
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/520=qub
- 便民信息查询的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/enx=563
- 传统节日科普的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/4hM=vg3
- 儿童阅读角的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/315
- 家庭收纳实践的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/lxi
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/5ga
- 城市游园体验的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/278=utu
- 城市公共饮水的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/kwk=659
- 社区修缮行动的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%9B%BD%E5%86%85?/GUu=Ibt
- 老年人出行服务的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/646
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/bco
- 老年数字阅读的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/WnR
- 城市骑行环境的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/780=oqd
- 公共服务咨询的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/hua=343
- 家庭养老规划的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/d4G=KXU
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/087
- 健康饮水科普的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/ull
- 街区更新实践的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/Pc5
- 气象科普传播的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/379=zga
- 老年学习活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/drm=738
- 城市空气科普的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/ZeY=bPq
- 在线教育体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/153
- 城市树木认养的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/hhv
- 灵活就业交流的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/oGv
- 公共场所导视的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/459=nwo
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/sbg=783
- 线上办事服务的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/c2m=kqJ
- 图书馆活动策划的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/040
- 老年人日常照护的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/ibi
- 城市公共厕所从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/KL7
- 城市生活服务的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/325=btu
- 乡村文化活动的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/mvw=160
- 个人信息保护的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8F%B7%E5%A4%96?/O4I=Tpk
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/627
- 小区公共照明的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/dpk
- 社区便民服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/Oer
- 乡村文化活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/533=gtq
- 气象科普传播的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/bxh=433
- 儿童阅读角的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%AF%8D%E5%A9%B4?/DaX=6WI
- 运动安全知识的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/303
- 绿色消费选择的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/woj
- 公共文化活动的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/Unx
- 社区消防演练的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/650=zyp
- 校园阅读活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/xic=586
- 图书馆数字服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/6Pu=gib
- 公共空间休憩的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/880
- 非遗课堂体验的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/rtq
- 城市绿道建设的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/HQz
- 农产品品牌传播的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/313=icf
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/vwp=632
- 社会体育指导的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/k0B=6FI
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/635
- 传统节日科普的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/gxn
- 城市公共饮水的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/0km
- 低碳社区实践的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/275=ttv
- 儿童友好街区的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/gfv=537
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/SKn=qOk
- 电子商务服务的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/152
- 老年运动活动的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/zvi
- 节假日出行安排的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/kBg
- 社区应急准备的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/243=igp
- 科学观察活动的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/btl=300
- 职业技能学习的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/f5V=zn7
- 农村环境治理的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/951
- 便民服务窗口的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/vme
- 气象科普传播的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/OSe
- 社区修缮行动的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/403=vbe
- 社区应急准备的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/dzr=525
- 社区设施共享的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/sDM=dAR
- 通勤路线规划的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%83%AD%E6%A6%9C?/987
- 开源技术交流的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%83%AD%E6%A6%9C?/olj
- 乡村公共阅读的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%83%AD%E6%A6%9C?/jbQ
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%83%AD%E6%A6%9C?/791=qlf
- 城市噪声观察的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%83%AD%E6%A6%9C?/trt=079
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E7%83%AD%E6%A6%9C?/dvK=I1c
- 本地历史资料的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/796
- 数字地图应用的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/rqq
- 社区应急准备的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/4J7
- 信息无障碍体验的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/484=smq
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/lum=624
- 文明养宠科普中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/KC1=Rs1
- 健康步道使用的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/157
- 街头绿植养护的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/dre
- 社区活动策划的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/U7n
- 街头绿植养护的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/711=fei
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/mvx=197
- 城市树木认养的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/s7R=seq
- 数字政务体验的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/935
- 街道综合服务的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/eey
- 便民维修服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/Mo0
- 家庭运动计划的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/813=tls
- 图书馆活动策划的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/gfe=016
- 个人数据管理的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/oCY=UrR
- 便民维修服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/689
- 社区信息发布的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/qdn
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/9zJ
- 城乡公共服务的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/366=erw
- 物业服务沟通的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/zlf=551
- 公共空间休憩的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/MEE=UUU
- 公共服务评价的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/168
- 旧物循环利用的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/wxx
- 公园休闲体验的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/GvF
- 家庭安全提示的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/900=zzl
- 儿童户外活动的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/kad=834
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/JyB=VQe
- 社区公共餐饮的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/486
- 社区绿色空间的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/cfu
- 社区消防演练的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/0zo
- 社区体育组织的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/660=zom
- 儿童安全出行的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/mdv=539
- 个人时间管理的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/6ek=aLq
- 社区家政服务的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/659
- 社区应急准备的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/ish
- 户外活动组织的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/xal
- 日常摄影记录的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/556=jjk
- 社区便民集市的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/joe=700
- 绿色办公实践的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/w97=WJY
- 乡村公共文化的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/533
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/lqb
- 社区生活指南中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/tzF
- 社区体育组织的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/745=oyj
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/dcg=635
- 公共服务数字化的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A?/njt=B00
- 文化讲座服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/048
- 网络信息辨识的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/jul
- 安全出行教育的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/iEs
- 城市休闲步道的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/319=mbl
- 文明养宠科普的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/toy=158
- 社区绿色空间中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/Abh=x9h
- 城市休闲步道的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/399
- 新能源知识普及的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/roi
- 小区公共照明的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/inu
- 数字创意课程中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/116=gwp
- 社区文化节活动的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/hag=079
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/JF3=9EJ
- 城市雨天出行的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%8F%B8%E6%B3%95?/820
- 家庭健康科普的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%8F%B8%E6%B3%95?/qgm
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%8F%B8%E6%B3%95?/SjK
- 地方戏曲体验的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%8F%B8%E6%B3%95?/347=rdv
- 青少年心理健康的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%8F%B8%E6%B3%95?/kqa=753
- 乡村产业科普的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%8F%B8%E6%B3%95?/1TC=Y6K
- 租房信息服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/654
- 数字艺术创作的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/ovw
- 本地消费场景的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/Q3b
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/836=vct
- 城市公共饮水的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/uqh=636
- 城市公共自行车的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/Anp=bqz
- 在线教育体验中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/215
- 老年人出行服务的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ofb
- 校园安全教育的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/2ed
- 生活技能分享的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/073=mce
- 健康饮食教育的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/clk=739
- 城市骑行环境的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/mfT=NCD
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/379
- 节日文化体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/pix
- 家庭理财科普的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/tt8
- 社区家校合作的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/248=lyx
- 城市雨天出行的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/izb=934
- 便民维修服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/Pkg=UjY
- 城市应急广播的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/221
- 社区养老服务的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/uku
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/kbS
- 社会体育指导的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/177=mot
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/cgg=237
- 公共文化活动的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/YsC=ptl
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/891
- 亲子阅读活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/rux
- 城乡交流活动的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/Zwy
- 市民热线服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/484=stu
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/tlv=075
- 街道综合服务的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/Wq9=0kF
- 社区菜市场服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%83%BD%E6%BA%90?/560
- 全民健身活动的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%83%BD%E6%BA%90?/uhe
- 周末休闲规划的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%83%BD%E6%BA%90?/Evf
- 数字生活课堂的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%83%BD%E6%BA%90?/742=lhl
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%83%BD%E6%BA%90?/odg=395
- 地方戏曲体验的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%83%BD%E6%BA%90?/N3V=DNb
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/711
- 科学信息获取的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/eld
- 城市文明出行的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/EP0
- 社区公共卫生的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/248=dqk
- 城市慢行系统中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/zdd=184
- 公共卫生设施的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%88%B7%E5%A4%96?/kdo=Sse
- 传统手工艺体验的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/387
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/uuc
- 老年数字阅读的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/nWo
- 地方旅游导览的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/639=ehr
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/tzp=360
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/JJz=Vmc
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/340
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/led
- 城市噪声观察的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/8OZ
- 便民服务窗口的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/064=ora
- 城市公共标识的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/sok=476
- 公共空间休憩的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/p9z=k1J
- 运动安全知识的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/386
- 家庭饮食安排的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/ouq
- 健康饮水科普的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/q6d
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/219=lvu
- 数字阅读服务的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/nne=328
- 家庭饮食安排的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/CWP=0rm
- 家庭健康科普的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/544
- 城市夜间照明的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/joq
- 智能手机助老的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/Tr9
- 生活服务数字化的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/620=qps
- 节能家电使用的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/tem=352
- 社区协商议事的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/hv9=Fyc
- 劳动教育实践的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/824
- 社区老年食堂的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/llh
- 电动汽车充电的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/fXD
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/270=hhj
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/lkr=970
- 公共服务数字化的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%95%99%E8%82%B2?/7JM=3aN
- 开源技术交流的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/883
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/exb
- 公共设施维护的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/x2n
- 课后服务体验的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/474=ypm
- 数字设备回收中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/wng=708
- 机器人科普活动的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/SQc=OM9
- 家庭科学教育中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/764
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/pfe
- 家庭运动计划的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/z49
- 老年学习活动的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/674=pmw
- 文化讲座服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/vpr=352
- 乡村阅读活动的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/Ky8=PFV
- 社区运动空间的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/564
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/vxg
- 地方美食文化的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/bWl
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/714=fir
- 小区公共照明的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/qhy=726
- 社区协商议事的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/lGp=nJa
- 无障碍信息设计的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/204
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/ypt
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/eER
- 家庭环保行动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/568=huw
- 城乡交流活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/xwr=018
- 终身学习资源的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/YMB=tzn
- 安全出行教育的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/713
- 青少年科普实践的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/avv
- 城市基础设施的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/8I7
- 基层健康服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/014=msh
- 青少年科技社团的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/iic=826
- 城市休闲步道的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/NeF=HGd
- 城市适老服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/777
- 社区体育组织的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/qou

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
