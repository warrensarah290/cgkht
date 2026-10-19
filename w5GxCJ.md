# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/173
- 地方美食文化的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/zcs
- 城市慢行系统中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/Y3V
- 社区托育服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/401=kzu
- 家庭园艺实践的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/pdo=481
- 无障碍出行的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/KqA=BW0
- 城市住房服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/629
- 社区文化节活动的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/sys
- 数字创作工具的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/Jny
- 城市休闲步道的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/803=zlv
- 城市应急科普的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/jua=537
- 节气饮食文化的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/GeE=kra
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/924
- 地方文化传播的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/ecn
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/10w
- 家庭环保习惯的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/982=xrc
- 社区教育资源的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/lme=319
- 老年数字阅读的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%AF%E8%82%A1?/LY4=Suj
- 日常摄影记录的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/541
- 节约用水实践的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/ddt
- 社区设施共享的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/bht
- 家庭收纳实践的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/910=qzh
- 社区活动报名的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/ddk=559
- 乡村公共文化的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/GTy=eqG
- 小区停车协商的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/307
- 周末休闲规划的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/ldv
- 机器人科普活动的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/CTg
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/290=hfn
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/wqn=811
- 邻里互助活动的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%9C%AD%E8%AE%B0?/C3V=nWH
- 公共设施使用的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/292
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/kvm
- 公共空间导览的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/9l7
- 街区道路维护的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/841=feu
- 城市农夫市集的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/qma=765
- 公共服务评价的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/eJz=7av
- 街头绿植养护的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/656
- 基层健康服务的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/dhn
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/aDU
- 公共卫生宣传的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/896=xtj
- 传统节日科普的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/bif=627
- 创业经验分享的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Rmu=dEJ
- 公共图书馆服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/536
- 节日文化体验的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/xrn
- 城市步行环境的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/keF
- 生活服务数字化的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/017=pdw
- 周末休闲规划的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/uft=215
- 老年学习活动的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%BD%A9%E7%A5%A8?/NVW=zIJ
- 社区科普课堂的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/613
- 基层健康档案的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/gkj
- 乡村生活观察的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/nd6
- 社区快递服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/080=zhu
- 数字学习资源的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/rde=665
- 小微企业服务的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/yM8=jeR
- 家庭阅读计划的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/447
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/ool
- 老年学习活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/A1j
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/273=iju
- 社区健康讲座的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/brj=614
- 电子商务服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/BEb=XJU
- 物业服务沟通的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/402
- 无障碍出行的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/gfv
- 社区邻里服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/dfc
- 图书馆数字服务的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/673=hxu
- 通勤路线规划的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/elr=144
- 城乡交流活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/6Li=PtJ
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/473
- 青年志愿活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/cfe
- 家庭急救准备的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/Tog
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/246=ork
- 市民意见收集的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/rgq=973
- 智能手机助老的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/Fhv=bxT
- 城市公共饮水的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/558
- 公共空间照明的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/ixa
- 网络安全教育的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/eHo
- 城市公共艺术的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/852=owo
- 城市体育设施的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/jjb=882
- 电子商务服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/lX0=Pxb
- 社区故事采集的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/175
- 社区文化传播的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/wbo
- 基层服务创新的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/LIm
- 青少年编程学习的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/817=cpp
- 数字创意课程的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/yrp=116
- 学校食育活动的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AE%B2%E5%9D%9B?/iis=e4h
- 传统节日科普的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/995
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/bdd
- 社区共享书架的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/slK
- 本地消费场景的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/257=ghz
- 街区道路维护中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/czi=163
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E6%9C%8D%E9%A5%B0?/Ytu=LSL
- 科学教育活动的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/929
- 社区邻里服务的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/ajq
- 儿童安全出行的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/quP
- 社区运动空间的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/899=yeh
- 数字阅读服务的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/gyf=858
- 文化场馆预约的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/DZ8=1zL
- 市民热线服务的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/368
- 城市绿道建设的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/dfs
- 社区手工活动的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/WXq
- 公共交通接驳的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/086=zzv
- 终身学习资源的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/rpl=980
- 跨代沟通活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/Yj9=GbU
- 乡村公共服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/119
- 图书馆数字服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/hav
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/K3A
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/784=qzx
- 数字创作工具的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/vtn=591
- 老年智能设备的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%9C%9F%E8%B4%A7?/0DO=Qm2
- 数字便民地图的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/220
- 科普展览体验的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/qdf
- 数字政务体验的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/9RL
- 老年人文化生活的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/082=tab
- 农贸市场环境的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/chz=734
- 社区文化节活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/qD3=blW
- 全民阅读推广的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/086
- 青年职业探索的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/aad
- 城市应急科普的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/vX5
- 社区公共卫生的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/649=blj
- 便民信息查询中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/tgi=768
- 城市公共空间的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/Uzx=LKD
- 个人信息保护的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/256
- 软件开发学习的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/vcw
- 环境教育课程的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/DPJ
- 无障碍出行的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/188=mhv
- 城市社区治理的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/qwp=833
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/rQb=Sx7
- 数字公共文化的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/872
- 社区学习活动的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/mkr
- 社区便利生活中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/CmV
- 数字设备回收的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/118=fmp
- 居家适老化改造的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/yky=001
- 公共设施维护的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%81%A5%E5%BA%B7?/O7S=lO6
- 公共图书馆服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/108
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/irt
- 学校体育活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/PYI
- 公共空间导览的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/676=xux
- 城市休闲步道的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/lpc=708
- 基层服务创新的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/XUF=DeT
- 市民热线服务的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/596
- 文化场馆预约的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/fou
- 公共服务沟通的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/nSm
- 公益活动组织的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/616=nff
- 城市农夫市集的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/orm=181
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/Hip=hRV
- 公园休闲体验的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/931
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/wdo
- 乡村阅读活动的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/MKC
- 市民热线服务的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/672=lmc
- 城市步行友好的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/ywy=234
- 非遗体验活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/FCx=lRE
- 节能家电使用的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/855
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/chj
- 本地旅行体验的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/KXU
- 城市便民驿站的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/146=qex
- 公共设施维护的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/afd=803
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/4U9=uMT
- 环境教育课程的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/736
- 基层健康服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/xro
- 绿色快递包装的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/jC7
- 儿童友好空间的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/336=brz
- 乡村电商实践的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/nkn=854
- 社区宠物管理的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/2LH=fWc
- 节假日出行安排的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_360%E4%BF%9D%E9%99%A9?/016
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_360%E4%BF%9D%E9%99%A9?/hur
- 家庭节能设备的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_360%E4%BF%9D%E9%99%A9?/AEM
- 公共空间照明的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_360%E4%BF%9D%E9%99%A9?/373=wxc
- 灵活就业交流的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_360%E4%BF%9D%E9%99%A9?/pvt=836
- 垃圾分类指导的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_360%E4%BF%9D%E9%99%A9?/5Nx=xt5
- 科学信息获取的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/877
- 社区商业活力的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/nry
- 城市公共自行车的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/Xw5
- 城市慢行系统的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/926=ttg
- 公园休闲体验的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/xwj=805
- 城乡交流活动的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/4zx=Agn
- 家庭理财科普的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%AE%9E%E5%BD%95?/294
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%AE%9E%E5%BD%95?/xmt
- 公共空间安全的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%AE%9E%E5%BD%95?/R4l
- 街头绿植养护的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%AE%9E%E5%BD%95?/456=tqc
- 城市慢行系统的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%AE%9E%E5%BD%95?/vtb=164
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%AE%9E%E5%BD%95?/tyj=E5h
- 居家适老化改造的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/380
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/xxy
- 儿童友好空间的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/hZW
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/471=lno
- 读书会组织的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/mqp=975
- 网络信息辨识的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/ePV=9gS
- 城市夜间照明的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/063
- 节日文化体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/tvo
- 气象科普传播的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/OkY
- 地方旅游导览的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/754=ksy
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/wyq=985
- 社区健康讲座的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/ixB=Kuz
- 电子商务服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/913
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/pji
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/TpB
- 城市便民驿站的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/655=dyn
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/yup=721
- 老年人出行服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/ahd=QyW
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/763
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/hes
- 智慧城市体验的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/GV0
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/575=knl
- 创业经验分享的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/ndf=525
- 文明养宠科普的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/d2Y=3KR
- 小区电梯维护的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/109
- 家庭运动计划的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/ogb
- 网络信息辨识的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/UAo
- 社区学习活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/502=yqr
- 社区应急准备的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/nys=393
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/rzP=0fS
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/035
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/ymf
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/lST
- 城乡交流活动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/104=cbx
- 网络信息辨识的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/tva=493
- 老年人日常照护的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/89d=fVn
- 基层健康服务的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/867
- 城市雨天出行的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/wlw
- 学校体育活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/6i0
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/934=jsj
- 在线学习体验的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/iqr=258
- 城市游园体验的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E4%BF%A1%E6%89%98?/Y3H=Ns3
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/294
- 城乡交通衔接的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/qug
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/JXS
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/017=fch
- 便民维修服务的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/ksf=511
- 社区停车服务的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/yI3=RIi
- 社区法律科普的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/798
- 公共服务数字化的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/lrs
- 社区手工活动的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/HNa
- 气象科普传播的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/915=oqy
- 社区公共卫生的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/nia=462
- 老年友好服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/wpd=6Cw
- 无障碍出行的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/035
- 城市文明实践中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/eow
- 社区快递服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/7rl
- 地方美食文化的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/118=zqo
- 乡村电商实践的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/wkx=703
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/CnG=sfJ
- 老年运动活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/511
- 乡村电商实践的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/xfq
- 校园安全教育的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/LCA
- 家庭环保行动的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/051=xzx
- 运动安全知识的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/utg=143
- 社区防暑服务的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/l6C=EUY
- 社区活动报名中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/679
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/czx
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/hmA
- 居家防滑改造的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/341=kfl

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
