# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 医院导诊服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%88%B0%E5%BA%95%E5%92%8B%E7%8E%A9%E6%89%8D%E6%8C%A3%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/091
- 基层医疗预约的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%88%B0%E5%BA%95%E5%92%8B%E7%8E%A9%E6%89%8D%E6%8C%A3%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/vrc
- 青少年科普实践的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%88%B0%E5%BA%95%E5%92%8B%E7%8E%A9%E6%89%8D%E6%8C%A3%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/1Ca
- 社区协商议事的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%88%B0%E5%BA%95%E5%92%8B%E7%8E%A9%E6%89%8D%E6%8C%A3%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/894=qqh
- 老年人日常照护的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%88%B0%E5%BA%95%E5%92%8B%E7%8E%A9%E6%89%8D%E6%8C%A3%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/oiv=246
- 绿色快递包装的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%88%B0%E5%BA%95%E5%92%8B%E7%8E%A9%E6%89%8D%E6%8C%A3%E9%92%B1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/SJC=BAO
- 农业科普体验的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8A%80%E5%B7%A7_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/299
- 智慧停车服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8A%80%E5%B7%A7_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/tsy
- 社区安全巡查的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8A%80%E5%B7%A7_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/nmR
- 青少年户外教育的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8A%80%E5%B7%A7_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/390=cra
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8A%80%E5%B7%A7_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/yxw=867
- 数字阅读服务的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8A%80%E5%B7%A7_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/cUX=6Rr
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8F%91%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/338
- 节假日出行安排的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8F%91%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/mdz
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8F%91%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/AQp
- 节能家电使用的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8F%91%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/341=wkz
- 户外活动组织的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8F%91%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/eeh=289
- 创业经验分享的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%8F%91%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E8%B0%B7%E6%AD%8C%E9%80%9F%E8%A7%88?/BUb=mkS
- 公共设施维护的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/704
- 社区公共卫生的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/gti
- 绿色快递包装中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/5jm
- 绿色办公实践的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/586=dne
- 地方民俗记录的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/otm=452
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/Nzm=U3c
- 小区停车协商的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E7%9A%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/257
- 公园亲子设施的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E7%9A%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/srs
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E7%9A%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/WB9
- 社区共享书架的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E7%9A%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/988=fca
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E7%9A%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/zad=993
- 本地历史资料的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E8%B5%9A%E9%92%B1%E7%9A%84_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/X1y=dtV
- 城市人文观察的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BA%95%E5%96%B728%E6%B3%A8%E4%B8%80%E7%AD%89%E5%A5%96_36%E6%B0%AA%E6%96%87%E5%BA%93?/918
- 家庭理财科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BA%95%E5%96%B728%E6%B3%A8%E4%B8%80%E7%AD%89%E5%A5%96_36%E6%B0%AA%E6%96%87%E5%BA%93?/nsq
- 线上办事服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BA%95%E5%96%B728%E6%B3%A8%E4%B8%80%E7%AD%89%E5%A5%96_36%E6%B0%AA%E6%96%87%E5%BA%93?/KRc
- 数字资源检索的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BA%95%E5%96%B728%E6%B3%A8%E4%B8%80%E7%AD%89%E5%A5%96_36%E6%B0%AA%E6%96%87%E5%BA%93?/585=lcc
- 地方旅游导览的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BA%95%E5%96%B728%E6%B3%A8%E4%B8%80%E7%AD%89%E5%A5%96_36%E6%B0%AA%E6%96%87%E5%BA%93?/hlt=788
- 科学健身方法的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BA%95%E5%96%B728%E6%B3%A8%E4%B8%80%E7%AD%89%E5%A5%96_36%E6%B0%AA%E6%96%87%E5%BA%93?/Mjy=TRN
- 日常摄影记录的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%B9%90%E9%80%8F%E5%A4%B4%E5%A5%96%E7%88%8628%E6%B3%A8_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/455
- 城市便民驿站的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%B9%90%E9%80%8F%E5%A4%B4%E5%A5%96%E7%88%8628%E6%B3%A8_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/sqq
- 校园阅读活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%B9%90%E9%80%8F%E5%A4%B4%E5%A5%96%E7%88%8628%E6%B3%A8_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/Fer
- 节约用水实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%B9%90%E9%80%8F%E5%A4%B4%E5%A5%96%E7%88%8628%E6%B3%A8_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/438=psv
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%B9%90%E9%80%8F%E5%A4%B4%E5%A5%96%E7%88%8628%E6%B3%A8_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/zds=287
- 线上阅读资源中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E4%B9%90%E9%80%8F%E5%A4%B4%E5%A5%96%E7%88%8628%E6%B3%A8_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/3IY=yMM
- 职业技能学习的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B6%85%E5%87%86%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/896
- 非遗体验活动的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B6%85%E5%87%86%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/uvq
- 城乡公共服务的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B6%85%E5%87%86%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/QxO
- 家庭食品保存的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B6%85%E5%87%86%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/926=wee
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B6%85%E5%87%86%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/jvc=925
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B6%85%E5%87%86%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/wv4=cVV
- 环境教育课程的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/670
- 环境教育课程的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/bff
- 老年数字阅读的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/4ST
- 全民健身活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/786=rtt
- 物业服务沟通的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/iys=245
- 节日文化体验的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%AB%98%E6%89%8B%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/WSD=dSG
- 科学健身方法的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB31%E5%88%86%E9%92%9F%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%A7%86%E9%A2%91?/496
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB31%E5%88%86%E9%92%9F%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%A7%86%E9%A2%91?/rdt
- 公共卫生设施中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB31%E5%88%86%E9%92%9F%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%A7%86%E9%A2%91?/Wmv
- 城市公共艺术的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB31%E5%88%86%E9%92%9F%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%A7%86%E9%A2%91?/386=dyi
- 家庭健康管理的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB31%E5%88%86%E9%92%9F%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%A7%86%E9%A2%91?/ygu=783
- 社区公共卫生的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB31%E5%88%86%E9%92%9F%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%A7%86%E9%A2%91?/fMP=XZT
- 公共场馆服务的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/823
- 农业科普体验的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/rvf
- 数字便民地图的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/vIQ
- 本地旅行体验的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/632=hyw
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/vgj=991
- 街区更新实践中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/3wB=W63
- 儿童安全出行的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/746
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/zjr
- 社区托育服务中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/yCC
- 居家防滑改造的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/153=jbu
- 社区儿童活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/rlf=582
- 老旧小区改造的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%8A%E5%B2%B8%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/BRM=UZZ
- 家庭志愿活动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B0%8F%E8%AF%B4_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/383
- 公共服务沟通的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B0%8F%E8%AF%B4_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/xwu
- 青少年科技社团的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B0%8F%E8%AF%B4_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/EwD
- 城市生活服务的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B0%8F%E8%AF%B4_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/521=fch
- 城乡公共服务的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B0%8F%E8%AF%B4_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/efb=302
- 数字地图应用的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B0%8F%E8%AF%B4_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/coe=Afg
- 城乡交流活动的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/826
- 城市共享单车的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/jve
- 便民服务地图的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/Rfc
- 数字艺术创作的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/656=qfk
- 家庭安全提示的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/ghr=331
- 城市文明实践的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/4hT=mxj
- 社区文化节活动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%BE%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/948
- 生活垃圾减量的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%BE%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/axm
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%BE%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/vnF
- 家庭科学教育的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%BE%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/077=htz
- 公交无障碍服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%BE%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/dnd=053
- 社区托育服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%BE%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%A4%A7%E7%A5%9E%E5%B8%A6%E6%88%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/2XN=SY2
- 小区停车协商的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9C%9F%E5%AE%9E%E5%A4%A7%E7%A5%9E_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/391
- 数字创意课程中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9C%9F%E5%AE%9E%E5%A4%A7%E7%A5%9E_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/cek
- 开源技术交流的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9C%9F%E5%AE%9E%E5%A4%A7%E7%A5%9E_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/yi6
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9C%9F%E5%AE%9E%E5%A4%A7%E7%A5%9E_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/685=mvf
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9C%9F%E5%AE%9E%E5%A4%A7%E7%A5%9E_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/ipq=005
- 无障碍出行的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9C%9F%E5%AE%9E%E5%A4%A7%E7%A5%9E_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/jcl=pdb
- 老旧小区改造的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%A2%E9%98%9F%E5%B8%A6%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/548
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%A2%E9%98%9F%E5%B8%A6%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/jzd
- 灵活就业交流的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%A2%E9%98%9F%E5%B8%A6%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/YzB
- 信息无障碍体验的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%A2%E9%98%9F%E5%B8%A6%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/692=new
- 社区读书角建设的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%A2%E9%98%9F%E5%B8%A6%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/jhr=087
- 公共设施使用的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E5%9B%A2%E9%98%9F%E5%B8%A6%E4%BA%BA_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/75z=8jG
- 社会体育指导的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8D%E7%BB%99%E5%87%BA%E6%AC%BE_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/422
- 青少年科技社团的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8D%E7%BB%99%E5%87%BA%E6%AC%BE_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/ehr
- 农业科普体验的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8D%E7%BB%99%E5%87%BA%E6%AC%BE_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/Fxj
- 乡村文化空间的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8D%E7%BB%99%E5%87%BA%E6%AC%BE_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/112=jke
- 小微企业服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8D%E7%BB%99%E5%87%BA%E6%AC%BE_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/wja=764
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8D%E7%BB%99%E5%87%BA%E6%AC%BE_%E7%99%BE%E5%BA%A6%E6%B6%88%E8%B4%B9?/6A9=USy
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/077
- 社区安全巡查的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/jnd
- 文明养宠科普的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/X6m
- 社区垃圾分类的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/467=dik
- 公共交通信息服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/wuj=705
- 新能源出行的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/40u=Wgw
- 城市休闲步道的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%BB%91%E6%AC%BE_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/968
- 食品配送体验的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%BB%91%E6%AC%BE_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/oax
- 生活技能分享的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%BB%91%E6%AC%BE_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/fOV
- 城市社区治理的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%BB%91%E6%AC%BE_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/245=omm
- 本地旅行体验的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%BB%91%E6%AC%BE_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/nfg=917
- 老年运动活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%BB%91%E6%AC%BE_%E9%9B%85%E8%99%8E%E9%9F%B3%E4%B9%90?/Xh9=Dko
- 老年运动活动的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%9B%98%E7%82%B9?/563
- 城市运动公园的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%9B%98%E7%82%B9?/icc
- 生活垃圾回收的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%9B%98%E7%82%B9?/Uid
- 公共文化活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%9B%98%E7%82%B9?/126=ael
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%9B%98%E7%82%B9?/tbf=075
- 公共卫生宣传的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%9B%98%E7%82%B9?/p9o=1Kl
- 乡村公共服务的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E7%A8%B3%E8%B5%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/779
- 数字课堂应用的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E7%A8%B3%E8%B5%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/jnq
- 社区公共卫生的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E7%A8%B3%E8%B5%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/nT8
- 休闲运动入门的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E7%A8%B3%E8%B5%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/852=dej
- 科学信息获取的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E7%A8%B3%E8%B5%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/cyl=975
- 通勤路线规划的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E7%A8%B3%E8%B5%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/SGy=H7Y
- 社区花园共建中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/106
- 街区更新实践的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/mcq
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/j4J
- 城市便民驿站的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/049=gmq
- 公共服务咨询的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/kuo=366
- 公共服务指南的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%9C%B0%E6%96%B9?/RMS=hrH
- 居家适老化改造的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/739
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/suq
- 食品安全科普的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/rv6
- 公共空间安全的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/735=ptq
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/aid=148
- 城市公共空间的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/obm=Jwn
- 城市公共厕所的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/042
- 垃圾分类指导的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/wgg
- 公共场所导视的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/kH6
- 乡村公共文化的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/778=kay
- 无障碍出行的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/vub=532
- 数字课堂应用的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/37W=Flh
- 城市文明实践中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/793
- 乡村阅读空间的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/pll
- 急救知识普及的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/oFY
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/204=woj
- 数字资源检索的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/omg=883
- 文明养宠科普的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/0hr=CXp
- 节约用水实践的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/715
- 开放数据应用的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/xdm
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/WQr
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/136=qfr
- 家庭收纳实践的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/gpi=341
- 节能家电使用的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/WSm=0mL
- 校园节能行动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/687
- 社区交通安全的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/ekp
- 智慧停车服务的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/Ttg
- 青年志愿活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/107=pup
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/kuw=891
- 科学信息获取的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E4%B8%8B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/xFc=Jmb
- 骑行路线规划的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%B6%E5%B1%85?/492
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%B6%E5%B1%85?/upf
- 公共空间安全的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%B6%E5%B1%85?/f4u
- 城市空气科普的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%B6%E5%B1%85?/614=okw
- 个人数据管理的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%B6%E5%B1%85?/ygg=979
- 乡村文化活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%AE%B6%E5%B1%85?/OmY=YGW
- 农产品消费体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E9%80%9A%E9%81%93_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/422
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E9%80%9A%E9%81%93_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jvk
- 公共设施维护的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E9%80%9A%E9%81%93_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/LYA
- 社区读书角建设的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E9%80%9A%E9%81%93_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/710=uzv
- 家庭用电安全的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E9%80%9A%E9%81%93_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/aoo=085
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E9%80%9A%E9%81%93_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/neo=iRN
- 乡村公共阅读的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%8D%E7%BB%99%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/025
- 社区生活指南的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%8D%E7%BB%99%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/lqu
- 小区停车协商的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%8D%E7%BB%99%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/CYF
- 家庭安全提示的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%8D%E7%BB%99%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/861=rds
- 社区志愿服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%8D%E7%BB%99%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/hsk=129
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%8D%E7%BB%99%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/Fc3=UL5
- 传统手工艺体验的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/218
- 数字创作工具的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/qsg
- 公共空间休憩的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/cLR
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/250=sfq
- 公益活动组织的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/eve=580
- 社区邻里服务的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/D9b=2eK
- 食品安全科普的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/027
- 乡村文化空间的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/bqq
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/5bJ
- 儿童运动体验的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/677=jqq
- 青年就业服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/ruk=002
- 家庭园艺实践的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/gY1=jjO
- 城市便民驿站的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/518
- 市民意见收集的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/xvr
- 社区活动报名的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/uiJ
- 机器人科普活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/334=unr
- 城市慢跑路线的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/tmp=609
- 智能家居应用的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%80%E5%88%86%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/Yq4=UjZ
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/334
- 周末休闲规划的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/zsa
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/i2G
- 家庭照护支持的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/846=rjy
- 社区交通安全的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/qnp=717
- 学校食育活动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E8%B4%A8%E8%B4%A2%E7%BB%8F?/cWY=hhX
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/152
- 数字创意课程的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/fyd
- 数字学习资源的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/Q0l
- 公共服务预约的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/290=ifh
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/cjh=718
- 农业科普体验的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8app_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/YUZ=HLo
- 社区设施共享的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/015
- 乡村生活观察的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/cox
- 城市文明出行的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/yKk
- 绿色校园实践的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/838=elq
- 街区道路维护的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/xtp=540
- 家庭环保习惯的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/M7f=Sd2
- 人工智能科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/223
- 开放式学习空间的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/glx
- 儿童友好空间的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/5ND
- 社区停车服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/821=drm
- 数字学习资源的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/let=382
- 城市基础设施的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/04P=DXv
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/537
- 社区绿色空间的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/myc
- 本地历史资料的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/AiS
- 便民服务窗口的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/358=uoo
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/kgr=441
- 信息无障碍体验的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91%E7%AB%99_%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B4%A2%E7%BB%8F?/ymh=zO0
- 电子商务服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/657
- 地方文化传播的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/wlh
- 小区公共照明的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/QjK
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/456=ezx
- 急救知识普及的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/vdv=844
- 个人时间管理的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8E%86%E5%8F%B2?/QPR=rMM
- 城市文化路线的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/727
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/fag
- 社区绿色空间中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/wVy
- 全民健身活动的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/039=cmf
- 生活技能分享的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/dwb=068
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/egn=xi7
- 社区停车服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/707
- 数字素养提升的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/apx
- 居家适老化改造的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/KdX
- 居民健康教育的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/257=dov

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
