# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 健康饮水科普的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/464
- 地方文化传播的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/nyn
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/vGP
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/176=rxk
- 公共服务预约的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/kon=693
- 城市应急科普的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/ZP1=gMe
- 乡村产业科普的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/908
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/wsa
- 青少年编程学习的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/TGY
- 地方文化传播的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/451=rqc
- 城市社区治理的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/nzk=365
- 远程协作工具的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/5Nl=Wat
- 在线学习体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/954
- 家庭收纳实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/dxk
- 社区活动报名中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/ztZ
- 公共服务预约的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/659=qsf
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/gdh=286
- 老年数字阅读的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/oyy=0MP
- 地方美食文化的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/164
- 本地旅行体验的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dqa
- 乡村教育资源的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/6jH
- 社区菜市场服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/256=gsx
- 居家适老化改造的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xgp=732
- 数字生活课堂的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zJl=q4k
- 城市微更新实践的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/172
- 无障碍出行的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/xlt
- 地方旅游导览的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/iqR
- 软件开发学习的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/886=kkp
- 绿色出行服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/mkz=288
- 青年就业服务的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/h6E=QXh
- 地方旅游导览的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/845
- 社区学习活动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/snn
- 数字地图应用的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/8f4
- 城市建设科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/718=rhh
- 智能家居应用的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/wsn=879
- 城市住房服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/6dR=zv1
- 数字便民地图的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/746
- 家庭网络使用的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/ztr
- 社区运动空间的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/pDc
- 全民阅读推广的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/459=uex
- 绿色校园实践的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/ivg=131
- 社区艺术活动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/ZPj=6Ak
- 乡村公共服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/361
- 城市水环境观察中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/xwc
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/mIX
- 城市运动公园的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/416=hip
- 社区活动策划的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/lxf=988
- 儿童安全出行的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/wie=LDe
- 社区活动策划的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/650
- 生成式工具使用的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/pxw
- 城市公共自行车的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/AFC
- 小区电梯维护的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/461=ufo
- 街区道路维护的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/vhd=564
- 便民服务地图的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/LGJ=OVC
- 线上阅读资源的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/858
- 城市游园体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/kdl
- 街区绿化养护中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/Vri
- 校园节能行动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/869=bdd
- 社会体育指导的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/azz=950
- 社区知识分享的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/BxC=NpU
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/983
- 节假日出行安排的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/dwi
- 数字支付体验的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/5YD
- 便民信息查询的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/130=zdp
- 社区互助网络的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/yub=600
- 社区生活指南的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/Y1V=bBK
- 信息无障碍体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/839
- 图书借阅体验的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/ouo
- 科学教育活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/gNx
- 公共交通接驳的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/300=jto
- 口袋公园建设的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/afk=925
- 读书会组织的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/LKN=ult
- 环境监测科普的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/257
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/sah
- 老年数字阅读的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/xQY
- 社区手工活动的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/148=eyu
- 居家适老化改造的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/klq=570
- 通勤路线规划的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/nhM=rPk
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/184
- 老旧小区改造的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/qig
- 公园亲子设施的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/KlH
- 公共空间安全的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/647=wjd
- 网络信息辨识的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/ibv=712
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/e3w=V5M
- 社区菜市场服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/715
- 家庭健康科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/oov
- 城市绿道建设的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/tSj
- 城市住房服务的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/461=pef
- 社区托育服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/sxw=154
- 校园节能行动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/ai9=wqG
- 食品安全科普的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/303
- 社区教育资源的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/gzq
- 城市夜间生活的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/6Oa
- 健康步道使用的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/414=cen
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/hie=012
- 食品安全科普的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/Asl=Zph
- 社会体育指导的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/342
- 线上办事服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/nwn
- 创业经验分享的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/iXs
- 城市步行友好的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/079=gpp
- 社区修缮行动的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/ajw=250
- 儿童安全出行中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/Dam=QvV
- 邻里互助活动的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/000
- 城市生活服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/klt
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/1ID
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/338=btd
- 老年人日常照护的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/ehu=463
- 城市运动公园的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/Cyg=x9F
- 社区共享书架的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/028
- 儿童友好空间的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/azm
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/HWa
- 城市公共艺术的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/649=dzu
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/niw=079
- 社区交通安全的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/ziN=dQM
- 便民服务地图的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/901
- 社区商业活力的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/fsy
- 老年智能设备的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/9Wz
- 数字政务体验的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/272=gez
- 社区防暑服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/lzl=836
- 街区小店体验的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/1XM=vRO
- 公共服务评价的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/052
- 节约用水实践的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/ewu
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/CAk
- 社区家校合作的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/452=gzh
- 小区停车协商的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/xfb=454
- 社区便利生活的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/g0v=q8o
- 公共设施维护的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/886
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/yje
- 社区消防演练的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/Z0w
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/195=trq
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/fxq=776
- 公共空间安全的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E7%BE%8E%E5%A6%86?/lt2=eYv
- 生活服务数字化的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/694
- 社区艺术活动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/shj
- 社区知识分享的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/khs
- 科学运动指导的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/916=grh
- 智能家居应用的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/mqv=235
- 绿色办公实践的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/1MD=r5t
- 信息无障碍体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/208
- 公共设施维护中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/bac
- 食品配送体验的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/hEm
- 新能源出行的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/708=dif
- 科学观察活动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/mff=951
- 社区慢性病防控的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/j6A=MF1
- 小区停车协商的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/876
- 数字政务体验的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/gxq
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/8bV
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/832=ywo
- 生活服务数字化的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/oqa=068
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/J2s=xCJ
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/536
- 便民维修服务的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/mck
- 数字课堂应用的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/liA
- 科学观察活动的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/289=zca
- 城市慢行系统的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/gnu=560
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/667=0RA
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/858
- 就业技能培训中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/ljx
- 家庭急救准备的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/BHn
- 线上阅读资源的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/094=cgh
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/opi=881
- 乡村电商实践的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/pfm=ujr
- 基层服务创新的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/775
- 科学运动指导的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/iqe
- 消防知识宣传的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/xyt
- 绿色生活实践的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/515=jox
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/vgt=469
- 公益活动组织的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/NkJ=Cdc
- 健康信息获取的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/052
- 药品使用科普的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/kqr
- 居家适老化改造的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/C21
- 公共服务指南的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/752=piw
- 公共设施使用的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/slb=329
- 新能源出行的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/xdp=GkN
- 日常摄影记录的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/166
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/ern
- 城市社区治理的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/fLJ
- 家庭用电安全的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/789=ltt
- 城市展览体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/nbc=734
- 公共服务评价的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/FVq=ua3
- 社区健康讲座的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/002
- 校园阅读活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/czz
- 城市微更新实践的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/xlV
- 社区故事采集的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/642=thc
- 社区读书角建设的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/vwu=794
- 公共交通接驳的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/o3F=QKu
- 社区活动空间的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/859
- 机器人科普活动的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/dsh
- 通勤路线规划的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/ZL9
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/132=aek
- 在线学习体验的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/lwq=171
- 儿童阅读角的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/Alg=aMe
- 科技馆参观体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/047
- 公共交通信息服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/sey
- 家庭网络使用的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/fZc
- 社区宠物管理的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/680=gwx
- 城市文明出行的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/bsu=601
- 城市水环境观察的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/fRJ=nqe
- 城市噪声观察的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/124
- 社区艺术活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/ptl
- 传统手工艺体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/aSN
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/670=sar
- 市民热线服务的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/qtn=154
- 节能生活方式的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/ats=83Q
- 急救知识普及的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/097
- 地方民俗记录的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/suf
- 城市休闲步道的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/DTE
- 安全出行教育的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/233=wfq
- 社区应急准备的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/slt=640
- 地方旅游导览的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/zf3=BKb
- 家庭园艺实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/478
- 智慧停车服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/lpc
- 城市休闲步道中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/lhx
- 数字创意课程的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/922=vly
- 家庭安全提示的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/dml=148
- 环境教育课程的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/1du=CUC
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/067
- 城市公共标识的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/qzo
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/3Pp
- 本地消费场景的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/033=jkb
- 城市人文观察的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/hlb=508
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-APP_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/Jnr=XOc
- 便民服务窗口的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/716
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/vdj
- 公共空间照明的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/xfG
- 家庭收纳实践的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/281=jlk
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/lgd=989
- 居民健康教育的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/ywx=sPq
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/377
- 地方民俗记录的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/fxp
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/4kg
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/252=gie
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/rlc=378
- 公共服务评价的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/GIa=MrF
- 乡村文化活动的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/906
- 健康信息获取的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/cdk
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/r4e
- 社区垃圾回收的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/024=nnu
- 租房信息服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/dpk=950
- 健康饮食教育的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/x2z=vI8
- 数字资源检索的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/415
- 青少年科普实践的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/kap
- 社区停车服务的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/r8u
- 绿色建筑理念的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/449=tpe
- 学校体育活动的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/nda=111
- 公共空间导览的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/svE=ewZ
- 个人时间管理的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/468
- 环境监测科普的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/ysg
- 城市公共艺术的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/9SS
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/359=ahm

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
