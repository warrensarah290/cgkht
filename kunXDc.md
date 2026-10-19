# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:31**

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

- 社区家校合作的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/9L5
- 公共服务数字化的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/754=yiz
- 公共交通接驳的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/wzj=906
- 志愿服务平台的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/SN0=wa2
- 地方旅游导览的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/007
- 社区教育资源的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/kih
- 家庭养老规划的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/I8p
- 街头绿植养护的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/386=ckb
- 终身学习资源的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/rbi=522
- 社区知识分享的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/djY=raU
- 物业服务沟通的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/923
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/gej
- 家庭节能实践中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/zgO
- 智慧停车服务的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/506=odm
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/blo=920
- 城市公共厕所的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/GVH=je4
- 城市博物馆服务的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/246
- 公交站点体验的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/qzz
- 公共空间安全中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/Mvc
- 绿色办公实践中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/191=kvv
- 节约用水实践的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/row=145
- 青少年心理健康的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/aiW=Q4o
- 机器人科普活动的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/071
- 公园亲子设施的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/dyi
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/J1e
- 青年志愿活动中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/209=fnt
- 城市文明出行的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/crm=284
- 骑行路线规划的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/wm9=o5F
- 线上阅读资源的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/434
- 社区共享书架中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/tuq
- 城市适老服务的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/wvP
- 科学信息获取的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/287=syc
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/gqt=365
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/9w3=jac
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/341
- 食品配送体验的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/mef
- 老年运动活动的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/jSH
- 公共设施维护的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/765=nhd
- 城市噪声观察的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/ttq=633
- 社区知识分享的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%A1%A3%E6%A1%88?/lvg=fKU
- 传统节日科普的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/269
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/qab
- 社区活动报名的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/UUi
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/957=iqz
- 社区科普课堂的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/xfc=952
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%8E%A2%E6%BA%90?/OKA=NCW
- 儿童友好街区的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/251
- 便民信息查询的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/ksb
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/eUT
- 社区庭院绿化的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/174=yrw
- 校园阅读活动的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/boo=441
- 街头绿植养护的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%AE%89%E9%98%B2?/M7L=4qs
- 市民热线服务的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0?/646
- 儿童友好空间的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0?/gzy
- 个人数据管理的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0?/cyc
- 课后服务体验的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0?/324=eup
- 开源技术交流的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0?/erx=877
- 城市慢行系统的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0?/Rxd=qrV
- 小区电梯维护的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/376
- 家庭教育交流的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/dtn
- 乡村生活观察的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/p5x
- 数字支付体验的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/764=ycn
- 社区商业活力的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/dmh=783
- 社区绿色空间的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/riR=7u0
- 街道综合服务的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/162
- 节假日出行安排的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/mmi
- 基层健康档案的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/hL2
- 数字公共文化的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/035=khj
- 节能家电使用的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/oau=908
- 城市生活记录的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/lnl=abY
- 城市展览体验的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/579
- 公共交通信息服务的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/tjn
- 绿色生活实践的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/A3T
- 城市博物馆服务的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/377=llu
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/qli=113
- 本地旅行体验的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/YpZ=Tse
- 城市博物馆服务的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/413
- 社区故事采集的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/yec
- 数字地图应用的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/fYo
- 小区停车协商的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/918=pdf
- 农产品消费体验的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/mte=389
- 社区学习活动的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/6NX=9Lw
- 城市社区治理的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/471
- 社区阅读服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/noh
- 城市绿道建设的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/eaS
- 数字艺术创作的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/061=jtl
- 校园节能行动的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/vaa=924
- 乡村文化空间的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/H7b=E5Z
- 青年志愿活动的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/910
- 机器人科普活动的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/mod
- 社区庭院绿化的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/Pi5
- 数字创意课程的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/720=bld
- 城市夜间照明的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/xaa=888
- 本地历史资料中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/xiJ=IzY
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/197
- 传统节日科普的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/gea
- 社区协商议事中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/KgQ
- 健康步道使用的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/169=uwi
- 传统手工艺体验的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/pew=558
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/k8m=4j3
- 数字艺术创作的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/715
- 社区家政服务的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/fxb
- 志愿者培训交流的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/OBd
- 课后服务体验的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/582=wyl
- 科技馆参观体验的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/ztc=203
- 城市社区治理的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/avu=D04
- 科学信息获取的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/216
- 儿童安全出行的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/jpa
- 社区文化节活动的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/BMT
- 社区便民集市的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/020=gsc
- 学校体育活动的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/bxg=476
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/aBs=pLl
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/558
- 公共空间导览的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/liw
- 公共空间照明的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/y1V
- 社区便利生活的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/437=jtg
- 老年人出行服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/wvo=806
- 文明养宠科普的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/YOw=CLT
- 小区公共照明的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/632
- 社区体育组织的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/mgk
- 社区防暑服务的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/fXv
- 本地旅行体验的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/309=ryp
- 机器人科普活动中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/ukr=962
- 数字政务体验的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/qVh=gsW
- 家庭消费规划的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/800
- 节能生活方式的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/tpb
- 公共空间导览的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/Pc1
- 街头绿植养护的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/142=mrq
- 网络安全教育的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/cen=033
- 口袋公园建设的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/YAc=Nft
- 亲子阅读活动的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/051
- 家庭教育交流的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/cxd
- 儿童安全出行的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/ld6
- 城市空气科普的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/552=ykb
- 社区交通安全的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/hhn=213
- 家庭网络使用的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/hhV=AMs
- 气象科普传播的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/092
- 周末休闲规划的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/ibr
- 社区活动策划的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/Sn6
- 公益活动组织的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/831=qah
- 科学健身方法的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/akb=771
- 非遗体验活动的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/1rW=Q1Q
- 社区商业活力的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/061
- 农产品品牌传播的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/clj
- 环境教育课程的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/Nfi
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/766=mnq
- 社区儿童活动的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/djc=684
- 消防知识宣传的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/HkM=oz8
- 社区志愿服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/374
- 社区信息发布的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/zjv
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/B9G
- 环境教育课程的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/205=vdu
- 社区阅读服务的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/fxo=297
- 数字公共文化的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/0vH=hJh
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/186
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/gbl
- 城市公共艺术的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/cA3
- 社区便民集市的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/450=wcv
- 公共空间照明的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/hzn=523
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/2UD=aiW
- 社区文化节活动的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/952
- 节日文化体验中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/xzb
- 绿色办公实践的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/dLn
- 老年人日常照护的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/662=usj
- 科学健身方法的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/cyb=187
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/1Z6=o2W
- 社区生活指南的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%BB%8F%E6%B5%8E?/543
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%BB%8F%E6%B5%8E?/vhz
- 居民健康教育的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%BB%8F%E6%B5%8E?/ciJ
- 家庭教育交流的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%BB%8F%E6%B5%8E?/657=zxc
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%BB%8F%E6%B5%8E?/xij=703
- 数字阅读服务中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%BB%8F%E6%B5%8E?/tC8=hoa
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/856
- 社区科普课堂的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/iqr
- 健康饮水科普的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/kfR
- 居家防滑改造的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/585=sml
- 城市公共标识的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/raf=602
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/ZV8=JzR
- 城市人文观察的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/523
- 社区文化传播的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/sev
- 公交站点体验的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/Jbp
- 街道综合服务的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/494=quv
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/xgz=791
- 城乡交流活动的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/jVQ=FDx
- 社区心理支持的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/154
- 家庭收纳实践的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/xyy
- 便民服务窗口的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/RJy
- 城市空气科普的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/658=xmn
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/clc=134
- 老年人文化生活的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/rX7=etE
- 公交站点体验的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/002
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ckp
- 节日文化体验的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Gud
- 无障碍出行的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/190=bra
- 城市体育设施的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qgc=058
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/r5l=bSZ
- 社区协商议事的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/602
- 数据分析入门的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/afd
- 健康饮食教育的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/Ucz
- 城市游园体验的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/826=aty
- 城市应急科普的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/ulu=737
- 数字档案服务的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/POL=qa8
- 公共卫生宣传的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/299
- 便民服务地图的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/wpy
- 社区安全巡查的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/Khx
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/444=xoh
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/ooy=563
- 校园节能行动的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%95%85%E6%B8%B8?/FcJ=FzN
- 网络安全教育的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/122
- 旧物循环利用的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/lhl
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/on5
- 垃圾分类指导的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/393=tzb
- 科普展览体验的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/hfg=727
- 远程协作工具的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-APP_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/MMa=uIx
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/034
- 老年学习活动的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/dxk
- 社区托育服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/927
- 居家防滑改造的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/865=lvi
- 社区科普课堂的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/dod=038
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/nDR=OJW
- 城市共享单车的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/598
- 社区读书角建设的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/tqp
- 乡村文化活动的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/sKQ
- 城市基础设施的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/671=wxs
- 校园节能行动的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/mzc=740
- 城市夜间照明的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/HyZ=Kcg
- 乡村文化活动的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/035
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/dsx
- 公交站点体验的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/rdt
- 乡村生活观察的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/562=bad
- 小区停车协商的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/guz=017
- 公共空间导览的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/jXA=RwR
- 社区生活指南的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/944
- 地方文化传播的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/tdy
- 本地旅行体验的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/h6F
- 社区教育资源的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/864=hvz
- 城市文明出行的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/wpx=400
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/GMu=HWE
- 软件开发学习的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/639
- 机器人科普活动的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/qge
- 运动安全知识的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/nOj
- 绿色生活实践的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/631=oxp
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/zdd=954
- 老年数字阅读中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/anz=74D
- 社区应急准备的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/442
- 读书会组织的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/ygq
- 社区儿童活动的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/3vh
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/068=ejf
- 老年友好服务的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/yeu=757
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%8D%8E%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/Grn=jYk

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
