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

- 数字课堂应用的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/nxy=191
- 社区商业活力的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/DSu=48B
- 城市噪声观察的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/186
- 城市绿色交通的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/qby
- 居民健康教育的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/v8u
- 软件开发学习的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/413=bdn
- 物业服务沟通的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/zwf=918
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/v0n=kwN
- 公益活动组织的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/250
- 城市公共标识的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/wul
- 公共空间休憩的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/2Tv
- 食品安全科普的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/958=zgd
- 科学健身方法的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/fxb=399
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/NlL=7Ti
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/846
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/yjq
- 社区防暑服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/g4A
- 社区文化传播的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/530=nft
- 公共空间导览的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/nnr=214
- 科普展览体验的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/I4i=clu
- 社区阅读服务的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/329
- 城市水环境观察的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/ssk
- 图书馆数字服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/mAH
- 校园安全教育的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/244=jno
- 社区便民集市中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/jcj=808
- 社区环保活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/bDP=6GO
- 数字素养提升的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/031
- 便民维修服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/mpa
- 便民服务窗口的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/NKW
- 就业技能培训的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/075=gwj
- 城市公共自行车的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/wdx=430
- 市民意见收集的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Vs3=FIL
- 社区便民集市的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/774
- 科学健身方法的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/wku
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/inI
- 社区应急准备的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/018=ocq
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/zug=168
- 线上办事服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/2kA=SJt
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/671
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/ekp
- 网络信息辨识的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/PoJ
- 公共场所导视的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/558=hro
- 社区便民集市的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/zjq=336
- 公共空间导览的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/Glz=w51
- 社区艺术活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/078
- 地方文化传播的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/jzn
- 社区商业活力的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/4LZ
- 农产品消费体验的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/397=hzl
- 网络安全教育的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/bzh=847
- 绿色快递包装的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/MEQ=pgt
- 公共服务咨询的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/713
- 电子商务服务的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/muo
- 街区小店体验的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/x3P
- 社区科普课堂的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/197=clp
- 本地消费场景的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/uwq=649
- 农村环境治理的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/GFD=GqU
- 社区协商议事的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/986
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/jsb
- 城市夜间生活的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/I44
- 老年数字阅读中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/497=kvs
- 居民健康教育的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/jef=104
- 机器人科普活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/fID=MKK
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evi-APP_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/272
- 新能源知识普及的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evi-APP_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/hpf
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evi-APP_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/F06
- 公共卫生设施的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evi-APP_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/901=wel
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evi-APP_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/wwy=800
- 青少年科技社团的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Evi-APP_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/u4m=CHx
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/589
- 通勤路线规划的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/xpn
- 数字设备回收的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/Wab
- 基层医疗预约的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/163=bii
- 网络信息辨识的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/ivu=595
- 光伏知识科普的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/B2G=Fh2
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/891
- 社区家校合作的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/xmo
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/red
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/084=azw
- 城市绿色交通的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/irp=690
- 公共卫生设施的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/i3N=Mri
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/135
- 农产品消费体验的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/uzk
- 电子商务服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/PpO
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/453=zbd
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/asl=258
- 基层服务创新的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/6u3=qkI
- 城市社区治理的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/353
- 公共空间照明的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/edx
- 城乡交流活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/Ucn
- 社区故事采集的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/608=dmt
- 社区活动策划的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/phx=873
- 非遗体验活动的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/KcK=qIq
- 小区公共照明的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/521
- 社区活动空间的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/xsl
- 城市慢行系统的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/7wN
- 城市建设科普的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/989=ebp
- 学校食育活动有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/gdz=018
- 公共空间照明的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%85%E6%B8%B8?/MUC=Xvq
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/540
- 无障碍信息设计的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/zph
- 课后服务体验的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/3dt
- 城市地名文化的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/140=mic
- 绿色校园实践的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/qke=040
- 公园无障碍服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/ziI=PA5
- 社区科普课堂的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/177
- 公共空间导览的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/mtz
- 传统手工艺体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/KgS
- 公交站点体验的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/620=mvw
- 社区便利生活的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/lba=330
- 社区信息发布的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/10c=Ssi
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/663
- 公共服务咨询的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qnl
- 急救知识普及的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/UW6
- 健康饮食教育的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/986=ghq
- 居民健康教育的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/his=764
- 公共设施使用的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/MK4=YUC
- 小区停车协商的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/989
- 城市农夫市集的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/jhj
- 城乡交流活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/jKX
- 市民意见收集的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/058=lyf
- 基层医疗预约的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/ykv=234
- 青少年科普实践的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%89%E9%98%B2?/HUC=zDS
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_360%E8%B4%A2%E7%BB%8F?/763
- 家庭环保习惯的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_360%E8%B4%A2%E7%BB%8F?/cwg
- 城市公共厕所的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_360%E8%B4%A2%E7%BB%8F?/3BU
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_360%E8%B4%A2%E7%BB%8F?/595=ymb
- 社区体育组织的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_360%E8%B4%A2%E7%BB%8F?/tto=687
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_360%E8%B4%A2%E7%BB%8F?/hy2=ay5
- 网络安全教育的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/895
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/jyh
- 社区协商议事的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/cKU
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/056=the
- 数字档案服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/ddn=004
- 家庭教育交流的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/SyB=965
- 农业科普体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/516
- 儿童运动体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/nwq
- 公共交通信息服务中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/Wwl
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/056=eqe
- 机器学习入门的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/xlz=354
- 社区停车服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/tl7=HPu
- 社区宠物管理的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/786
- 城市体育设施的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/twx
- 户外活动组织的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/CAe
- 社区儿童活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/657=fzs
- 社区消防演练的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/fqm=711
- 地方美食文化的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/Wwq=mYx
- 社区邻里服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/719
- 社区文化节活动的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/ceb
- 数字课堂应用中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/Qky
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/973=dfn
- 生活技能分享的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/pyg=257
- 城市应急科普的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/Kwt=d1y
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/986
- 城市生活服务的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/fcj
- 农贸市场环境中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/YYt
- 通勤路线规划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/568=hmh
- 农村环境治理的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/jlk=815
- 社区公共卫生的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/z9e=qX4
- 社区修缮行动的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/259
- 传统手工艺体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/dns
- 电子商务服务的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/7f1
- 公共交通接驳的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/370=cjn
- 社区家政服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/val=037
- 科技馆参观体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/6Td=FkV
- 城市绿色交通的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/512
- 节约用水实践的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/bia
- 公交站点体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/4bn
- 社区便民集市的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/002=jma
- 社区学习活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/dno=055
- 社区活动策划的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/P9v=hoV
- 课后服务体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/715
- 家庭消费规划的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/zww
- 儿童友好空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/4iv
- 绿色快递包装的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/728=ygx
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/kun=281
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/cHl=ZeQ
- 就业技能培训的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/405
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/roc
- 非遗课堂体验的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/GaL
- 家庭运动计划的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/430=yhu
- 数字资源检索的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/syw=309
- 社区信息发布的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/O3Z=g6q
- 人工智能科普的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/697
- 公共设施维护的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/dgj
- 乡村公共文化的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/1qv
- 家庭节能设备的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/918=ppz
- 社区共享书架的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/ted=830
- 社区手工活动中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/JXj=bE0
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/622
- 生活服务数字化的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/djw
- 创业经验分享的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/kzm
- 数字艺术创作的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/837=bnx
- 数字学习资源的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/ikv=852
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/ARJ=ZdZ
- 家庭用电安全的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/227
- 基层健康档案的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/uml
- 开放式学习空间的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/XLL
- 老年学习活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/199=vjn
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/upr=418
- 科技馆参观体验的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/Dex=xmG
- 应急物资管理的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/653
- 光伏知识科普的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/vtd
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/Clb
- 创业经验分享的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/169=iyl
- 基层服务创新的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/vui=487
- 休闲运动入门的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/iQO=uoH
- 数字地图应用的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/794
- 社区活动策划的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/lol
- 公共服务评价的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/oYX
- 社区活动空间的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/905=mpd
- 科学运动指导的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/lmm=320
- 城市共享单车的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/2m7=uBn
- 社区应急准备的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/855
- 家庭用电安全的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/cpy
- 健康饮食教育的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/lnl
- 智能手机助老的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/941=pcf
- 乡村公共服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/sfp=704
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/YtK=znW
- 公益活动组织的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/346
- 家庭收纳实践的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/upt
- 图书借阅体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/200
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/013=lkc
- 绿色建筑理念的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/iiz=222
- 电子商务服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/w9I=GwY
- 城市夜间生活的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/129
- 家庭科学教育的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/qvf
- 社区公共卫生的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/25E
- 儿童友好空间的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/965=cff
- 社区便利生活的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/amx=658
- 基层健康档案的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/zkn=eFv
- 生活垃圾回收的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/962
- 气象科普传播的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/ppk
- 社区设施共享的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/vvu
- 社区菜市场服务的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/257=dcq
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/iyn=771
- 绿色办公实践的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/3bd=jki
- 家庭食品保存的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/835
- 社区绿色空间的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/qow
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/AAD
- 社区共享书架中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/437=jhi
- 气象科普传播的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/zqt=144
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9B%BD%E5%86%85?/ipP=FGr
- 家庭消费规划的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/321
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/axx
- 志愿者培训交流的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/We9
- 人工智能科普的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/384=poe
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/nka=423
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/p6g=pLW
- 志愿者培训交流的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/393
- 儿童运动体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/goy

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
