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

- 公共交通接驳的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/wke=890
- 科学健身方法的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/B2q=rrM
- 传统节日科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/922
- 智能手机助老的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/ata
- 节能家电使用的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/UHW
- 社区艺术活动的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/741=aok
- 城市公共厕所的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/wml=730
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E%E4%BA%89%E9%94%8B%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/Eie=MmM
- 家庭网络使用的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88II%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/185
- 儿童运动体验的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88II%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/oiz
- 劳动教育实践的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88II%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/Ghh
- 城市公共座椅的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88II%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/217=qay
- 城市空气科普的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88II%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/rzi=160
- 老旧小区改造的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88II%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/D7Q=kT5
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/721
- 居民健康教育的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/fer
- 地方文化传播的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/XO2
- 城市绿色交通中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/569=ahq
- 社区知识分享的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mpm=628
- 线上办事服务中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9EII%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/19P=Q15
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9Ev8_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/121
- 城市公共标识的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9Ev8_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/hun
- 职业技能学习的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9Ev8_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/nIS
- 城市可持续生活的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9Ev8_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/982=dhz
- 老年人出行服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9Ev8_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/kle=152
- 家庭食品保存的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%9Ev8_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/JAp=hUF
- 跨代沟通活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/414
- 节气饮食文化的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/keh
- 学校体育活动的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/IlU
- 安全出行教育的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/383=kfj
- 城市博物馆服务的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/nfw=412
- 社区活动报名的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/YAv=RIu
- 社区阅读服务的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/121
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/wug
- 城市骑行环境的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/aFt
- 乡村文化空间的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/306=iew
- 信息无障碍体验的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/lfy=276
- 家庭科学教育的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/Y7S=yBy
- 家庭急救准备的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/710
- 社区体育组织的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/hhn
- 节假日出行安排的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/N0n
- 生成式工具使用的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/542=epf
- 城市骑行环境的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/hfv=426
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/QlJ=m2S
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/604
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/qyv
- 家庭用电安全的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/ZQT
- 节气饮食文化的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/685=miq
- 农村环境治理的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/tho=073
- 便民维修服务的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/M7q=6Ew
- 公园休闲体验中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/835
- 老年人出行服务的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/mnj
- 农村环境治理的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/3NS
- 科普展览体验的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/793=ysb
- 城市噪声观察的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/bpy=023
- 城市夜间照明的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/ET3=AXu
- 居家适老化改造的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/347
- 社区活动策划的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/bih
- 社区交通安全的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/0HE
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/490=jjb
- 生活技能分享的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/epe=811
- 城市应急科普的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/aNK=1Zl
- 家庭健康管理的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91pk%E4%B8%80%E5%88%86%E4%B8%80%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/331
- 乡村生态观察的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91pk%E4%B8%80%E5%88%86%E4%B8%80%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/cqx
- 基层医疗预约的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91pk%E4%B8%80%E5%88%86%E4%B8%80%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/T3T
- 乡村阅读空间的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91pk%E4%B8%80%E5%88%86%E4%B8%80%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/659=vgm
- 智能手机助老的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91pk%E4%B8%80%E5%88%86%E4%B8%80%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/dlk=811
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91pk%E4%B8%80%E5%88%86%E4%B8%80%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/V8Z=DjB
- 社区教育资源的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk%E6%8B%BE%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/651
- 网络信息辨识的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk%E6%8B%BE%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/kvm
- 社区协商议事的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk%E6%8B%BE%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/CUh
- 就业技能培训的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk%E6%8B%BE%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/952=ypd
- 城乡公共服务的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk%E6%8B%BE%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/yao=013
- 公共设施使用的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk%E6%8B%BE%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/hf7=o3p
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/053
- 社区环保活动的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/piz
- 乡村文化空间的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/3yx
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/667=wls
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/zok=086
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/kjj=7ix
- 传统手工艺体验的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E4%BA%9A%E5%86%9B%E5%92%8C%E6%80%8E%E4%B9%88%E4%B9%B0_36%E6%B0%AA%E5%9B%BD%E5%86%85?/814
- 生活技能分享的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E4%BA%9A%E5%86%9B%E5%92%8C%E6%80%8E%E4%B9%88%E4%B9%B0_36%E6%B0%AA%E5%9B%BD%E5%86%85?/vku
- 城市游园体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E4%BA%9A%E5%86%9B%E5%92%8C%E6%80%8E%E4%B9%88%E4%B9%B0_36%E6%B0%AA%E5%9B%BD%E5%86%85?/mHA
- 社区托育服务的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E4%BA%9A%E5%86%9B%E5%92%8C%E6%80%8E%E4%B9%88%E4%B9%B0_36%E6%B0%AA%E5%9B%BD%E5%86%85?/850=gyk
- 社区公共议事的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E4%BA%9A%E5%86%9B%E5%92%8C%E6%80%8E%E4%B9%88%E4%B9%B0_36%E6%B0%AA%E5%9B%BD%E5%86%85?/ryy=483
- 科学运动指导的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E4%BA%9A%E5%86%9B%E5%92%8C%E6%80%8E%E4%B9%88%E4%B9%B0_36%E6%B0%AA%E5%9B%BD%E5%86%85?/LPt=tLI
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/811
- 绿色快递包装的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/deh
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/tG7
- 数字课堂应用的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/089=rjy
- 智慧城市体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/qrf=328
- 乡村公共服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91pk10%E5%86%A0%E5%86%9B%E5%8D%95%E5%8F%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/BOC=bvo
- 乡村文化空间的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91pk10%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/512
- 物业服务沟通中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91pk10%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/gaz
- 节约用水实践的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91pk10%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/a3Q
- 数字课堂应用的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91pk10%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/462=udo
- 社区协商议事的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91pk10%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/mng=043
- 数字学习资源的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91pk10%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%85%A7%E7%9C%BC?/QUA=62w
- 城市体育设施的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91pk10%E6%98%AF%E4%BB%80%E4%B9%88_%E6%BE%8E%E6%B9%83%E5%9F%8E%E4%BA%8B?/849
- 个人信息保护的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91pk10%E6%98%AF%E4%BB%80%E4%B9%88_%E6%BE%8E%E6%B9%83%E5%9F%8E%E4%BA%8B?/npy
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91pk10%E6%98%AF%E4%BB%80%E4%B9%88_%E6%BE%8E%E6%B9%83%E5%9F%8E%E4%BA%8B?/Nf6
- 智能手机助老的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91pk10%E6%98%AF%E4%BB%80%E4%B9%88_%E6%BE%8E%E6%B9%83%E5%9F%8E%E4%BA%8B?/068=ewf
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91pk10%E6%98%AF%E4%BB%80%E4%B9%88_%E6%BE%8E%E6%B9%83%E5%9F%8E%E4%BA%8B?/sot=915
- 图书借阅体验的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91pk10%E6%98%AF%E4%BB%80%E4%B9%88_%E6%BE%8E%E6%B9%83%E5%9F%8E%E4%BA%8B?/iNO=A2c
- 数字素养提升的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/943
- 健康步道使用的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/cgl
- 青少年科技社团的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/Esp
- 科学信息获取的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/893=vih
- 线上阅读资源的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/ros=643
- 青少年户外教育中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/UH1=9r9
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E6%A0%B7%E8%BF%BD%E4%B8%A4%E7%A0%81_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/793
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E6%A0%B7%E8%BF%BD%E4%B8%A4%E7%A0%81_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/bsg
- 非遗体验活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E6%A0%B7%E8%BF%BD%E4%B8%A4%E7%A0%81_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/nG0
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E6%A0%B7%E8%BF%BD%E4%B8%A4%E7%A0%81_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/906=bul
- 老年人文化生活的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E6%A0%B7%E8%BF%BD%E4%B8%A4%E7%A0%81_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/nqf=106
- 社区法律科普的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E6%80%8E%E6%A0%B7%E8%BF%BD%E4%B8%A4%E7%A0%81_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/p6z=F61
- 城市公共自行车的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E6%80%8E%E4%B9%88%E7%8E%A9_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/712
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E6%80%8E%E4%B9%88%E7%8E%A9_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/vac
- 城市雨天出行的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E6%80%8E%E4%B9%88%E7%8E%A9_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/LrE
- 家庭运动计划的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E6%80%8E%E4%B9%88%E7%8E%A9_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/550=zzv
- 生活垃圾回收的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E6%80%8E%E4%B9%88%E7%8E%A9_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/uph=227
- 城市应急科普的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E6%80%8E%E4%B9%88%E7%8E%A9_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/7dN=nf7
- 乡村阅读空间的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%868%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/482
- 社区家校合作的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%868%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/ear
- 校园节能行动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%868%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/IAI
- 乡村电商实践的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%868%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/579=zjs
- 绿色快递包装的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%868%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/mpe=364
- 无障碍出行的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%868%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/jW1=ecK
- 城市应急广播的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%BA%94%E7%A0%81_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/279
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%BA%94%E7%A0%81_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/pau
- 家庭安全提示的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%BA%94%E7%A0%81_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/618
- 社区科普课堂的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%BA%94%E7%A0%81_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/674=vxq
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%BA%94%E7%A0%81_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/eny=167
- 环境监测科普的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%BA%94%E7%A0%81_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/2Yq=PGs
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD5%E7%A0%81_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/168
- 节能生活方式的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD5%E7%A0%81_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/qpi
- 城市绿道建设的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD5%E7%A0%81_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/kqL
- 街道综合服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD5%E7%A0%81_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/416=ifq
- 社区便民集市的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD5%E7%A0%81_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/hxy=760
- 家庭运动计划的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD5%E7%A0%81_%E8%B1%86%E7%93%A3%E6%88%BF%E4%BA%A7?/Us8=xLM
- 家庭理财科普的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%AD%E4%B8%80%E4%B8%AA%E5%8F%B7%E8%83%BD%E5%9B%9E%E6%9C%AC%E9%87%91%E5%90%97_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/287
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%AD%E4%B8%80%E4%B8%AA%E5%8F%B7%E8%83%BD%E5%9B%9E%E6%9C%AC%E9%87%91%E5%90%97_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/fea
- 城市运动公园的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%AD%E4%B8%80%E4%B8%AA%E5%8F%B7%E8%83%BD%E5%9B%9E%E6%9C%AC%E9%87%91%E5%90%97_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/qBN
- 社区运动空间的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%AD%E4%B8%80%E4%B8%AA%E5%8F%B7%E8%83%BD%E5%9B%9E%E6%9C%AC%E9%87%91%E5%90%97_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/142=pwf
- 家庭节能实践的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%AD%E4%B8%80%E4%B8%AA%E5%8F%B7%E8%83%BD%E5%9B%9E%E6%9C%AC%E9%87%91%E5%90%97_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/gys=697
- 生成式工具使用的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%AD%E4%B8%80%E4%B8%AA%E5%8F%B7%E8%83%BD%E5%9B%9E%E6%9C%AC%E9%87%91%E5%90%97_%E5%A4%AE%E8%A7%86%E5%86%9C%E4%B8%9A?/3E3=idj
- 城市公共饮水的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD4%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/329
- 社区科普课堂的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD4%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/awn
- 城市运动公园的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD4%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/mgI
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD4%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/089=gqd
- 公共服务数字化的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD4%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/tdk=093
- 科技馆参观体验的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E4%B8%87%E8%83%BD4%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/NdF=uYv
- 租房信息服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%87%A0%E6%B3%A8_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/534
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%87%A0%E6%B3%A8_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/rzu
- 小区电梯维护的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%87%A0%E6%B3%A8_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/wD2
- 图书借阅体验的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%87%A0%E6%B3%A8_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/294=rnj
- 个人信息保护的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%87%A0%E6%B3%A8_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/ptw=732
- 智能手机助老的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91pk10%E5%AE%9A%E4%BD%8D%E8%83%86%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%87%A0%E6%B3%A8_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/Ti0=144
- 读书会组织的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDAPP_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/780
- 家庭节能设备的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDAPP_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/efs
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDAPP_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/nxh
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDAPP_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/273=udc
- 气象科普传播的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDAPP_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/yuc=451
- 市民热线服务的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91pk10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BDAPP_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/te8=NmL
- 校园社团活动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6_%E6%8A%96%E9%9F%B3%E5%AE%9E%E5%BD%95?/302
- 课后服务体验中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6_%E6%8A%96%E9%9F%B3%E5%AE%9E%E5%BD%95?/mkk
- 家庭环保习惯的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6_%E6%8A%96%E9%9F%B3%E5%AE%9E%E5%BD%95?/woE
- 城市公共艺术的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6_%E6%8A%96%E9%9F%B3%E5%AE%9E%E5%BD%95?/924=orz
- 城市空气科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6_%E6%8A%96%E9%9F%B3%E5%AE%9E%E5%BD%95?/eth=200
- 城市便民驿站的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6_%E6%8A%96%E9%9F%B3%E5%AE%9E%E5%BD%95?/cuR=Kk4
- 社区菜市场服务的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/299
- 公共场馆服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/uyz
- 城市树木认养的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/HmK
- 社区养老服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/243=fln
- 节约用水实践的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/puc=837
- 城市慢行系统中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/GgX=QJ7
- 家庭消费规划的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/916
- 公共文化活动的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/irf
- 家庭消费规划的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/Lf3
- 社区修缮行动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/831=yek
- 数字创作工具的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/ofq=517
- 环境监测科普的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/l0W=jIs
- 科学信息获取的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/219
- 数字支付体验的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/dff
- 乡村教育资源的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/Ojg
- 课后服务体验的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/909=kmp
- 社区防暑服务的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/eiz=877
- 生活垃圾减量的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/WGw=3dI
- 城市适老服务的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/238
- 乡村生态观察的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/ywh
- 便民服务窗口的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/9cq
- 家庭照护支持的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/507=tka
- 健康饮食教育的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/dtu=877
- 城市共享单车的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/BeJ=fJ5
- 科学健身方法的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/545
- 社区科普课堂中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/san
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/iNI
- 老年友好服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/300=erh
- 家庭健康管理的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/efj=680
- 社区教育资源的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/qvL=nEN
- 青少年科普实践的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/667
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/sbm
- 公共场所导视的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/PVT
- 数字支付体验的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/936=uqs
- 数字素养提升的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/xce=874
- 青年职业探索的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/VGG=i7v
- 终身学习资源的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/455
- 青年职业探索的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/ufy
- 家庭消费规划的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/ZvA
- 青少年户外教育的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/139=mmc
- 公共设施维护的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/jbk=962
- 家庭节能实践的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E8%BE%9F%E8%B0%A3?/ifW=8KO
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/418
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/jzu
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/hJ5
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/333=kqg
- 线上办事服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/trc=578
- 乡村生活观察的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/eFM=b3V
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/385
- 家庭节能实践的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/jkx
- 公共卫生宣传的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/3q0
- 城乡交流活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/003=gdt
- 乡村公共阅读的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/nae=314
- 社区环保活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/jpf=1YO
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/933
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/ddj
- 智慧停车服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/yBS
- 居家适老化改造的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/050=mvt
- 人工智能科普的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/mqo=432
- 社区家政服务的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/EIq=PZK
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/841
- 便民信息查询的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/lqc
- 低碳社区实践的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/T2P
- 公交站点体验的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/375=duj
- 社区生活指南的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/xqw=830
- 城市人文观察中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/WND=zcU
- 青年职业探索的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/175
- 远程协作工具的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/mye
- 家庭安全提示的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/pJD
- 城市步行友好的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/689=rrk
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/viq=641
- 健康步道使用的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/C35=S0b
- 老年人出行服务的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/232
- 家庭健康科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/gic
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/8QX
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/194=gje
- 儿童安全出行的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/goj=502
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E5%BE%97%E7%89%A9%E8%AF%BB%E4%B9%A6?/bPk=C9w
- 社区共享书架的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E5%AD%A6_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/351
- 社区花园共建的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E5%AD%A6_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/old

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
