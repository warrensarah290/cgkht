# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 食品配送体验从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/496
- 老年友好服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/paa
- 老年人文化生活的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/9kK
- 生活服务数字化中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/154=iax
- 周末休闲规划的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/bpf=479
- 社区垃圾回收的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/yt4=oKa
- 智慧城市体验的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/705
- 城市慢行系统的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/fuj
- 社区消防演练的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/UA9
- 文化讲座服务的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/399=yra
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/vbj=704
- 物业服务沟通的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/VZ2=wwH
- 志愿者培训交流的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/172
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/puf
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/UQc
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/788=scs
- 安全出行教育的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/fxh=672
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/1LF=HNy
- 家庭用电安全的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/100
- 社区停车服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/wzo
- 生成式工具使用的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/NlR
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/338=tjw
- 生活垃圾减量的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/atz=451
- 社区活动报名的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/TQ7=ekc
- 城市共享单车的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/127
- 街区道路维护的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/zca
- 社区菜市场服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/Jnw
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/065=vrf
- 社区设施共享的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/vvb=233
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%96%B0%E6%B5%AA%E9%97%AE%E7%AD%94?/Mdr=rUN
- 数字课堂应用的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/933
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/kvk
- 公共空间休憩的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mQ5
- 数字生活课堂的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/241=ijp
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/qjh=845
- 社区家校合作的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/FuN=tdQ
- 社区垃圾回收的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/401
- 文明养宠科普的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/xew
- 社区知识分享的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/dy1
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/389=ecx
- 乡村生态观察的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/pyh=097
- 老年友好服务的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/SHe=Vup
- 运动安全知识的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/448
- 老年智能设备的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/czn
- 软件开发学习的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/GAZ
- 社区休闲设施的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/294=djp
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/lqc=542
- 本地历史资料的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/lTj=tva
- 城市休闲步道的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/998
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/fig
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/ZOV
- 本地历史资料的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/799=gkw
- 本地历史资料中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/gve=198
- 城市夜间照明的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/whi=Hpk
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/604
- 安全出行教育的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/kje
- 儿童安全出行的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/Psf
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/297=rnk
- 终身学习资源的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/yfh=116
- 城市公共座椅的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/S0B=Pxl
- 家庭园艺实践的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/251
- 数字课堂应用的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/ccr
- 社区便民服务的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/510
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/827=izd
- 家庭健康管理的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/yia=706
- 农贸市场环境的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/Y1p=Eyc
- 基层健康服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E8%BD%AC%E8%BD%BD?/464
- 社区法律科普中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E8%BD%AC%E8%BD%BD?/mdx
- 读书会组织的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E8%BD%AC%E8%BD%BD?/zpo
- 物业服务沟通的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E8%BD%AC%E8%BD%BD?/476=sib
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E8%BD%AC%E8%BD%BD?/tif=098
- 城市空气科普的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_360%E8%BD%AC%E8%BD%BD?/ZT9=hI2
- 社区庭院绿化的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/279
- 公共卫生宣传的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/rnc
- 城乡公共服务的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/2GQ
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/999=pic
- 科学信息获取中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/bbw=028
- 生活技能分享的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Eoo=fip
- 便民服务地图的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/379
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/anj
- 公共服务沟通的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/A1i
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/922=ajy
- 乡村产业科普的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/gvq=508
- 乡村文化空间中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/h7e=yLq
- 社区养老服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/269
- 城市绿道建设的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/fts
- 公共服务指南的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/HxV
- 传统手工艺体验从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/009=sor
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/qfm=797
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/Ora=O6N
- 乡村公共文化的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/111
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/tei
- 社区家校合作的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/VK5
- 城市生活服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/106=drk
- 节约用水实践的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/inr=318
- 医院导诊服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/IIM=8lW
- 消防知识宣传的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/827
- 基层服务创新的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/hye
- 街区绿化养护的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/IKL
- 城市骑行环境的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/310=emk
- 居民健康教育的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/oyj=988
- 个人数据管理的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/xjT=LOo
- 社区公共卫生的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/937
- 儿童户外活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/goe
- 公共服务预约的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/o1J
- 社区志愿服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/241=hbr
- 创业经验分享的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/qsu=139
- 城市应急广播的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/frQ=HSS
- 社区协商议事的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/016
- 光伏知识科普的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/atz
- 文化讲座服务的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/C2U
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/847=jkg
- 安全出行教育的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/eiy=841
- 社区健康讲座的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/gCo=xzP
- 科学教育活动的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/740
- 儿童友好街区的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/nuu
- 绿色出行服务的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/bPz
- 食品安全科普的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/887=ait
- 电动汽车充电的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/cui=544
- 城市运动公园的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%96%87%E5%BA%93?/2BJ=Rgg
- 无障碍信息设计的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/563
- 公共空间照明的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/ebq
- 社区健康讲座的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/xeR
- 科学运动指导的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/767=kdv
- 社区科普课堂的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/uli=985
- 网络信息辨识的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/nLm=3Hb
- 社区交通安全的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/910
- 城市文明实践的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/alr
- 城市骑行环境的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/zO2
- 公共设施使用的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/810=nxb
- 社区艺术活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/wao=311
- 公益活动组织的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E9%97%AE%E5%8D%B7?/p1x=iA0
- 无障碍信息设计的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/413
- 家庭教育交流的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/zuz
- 老年运动活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/W3l
- 科学信息获取的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/974=ave
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/fjm=813
- 社区环保活动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E9%80%89%E5%8F%B7_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/Wcu=13X
- 数字学习资源的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/131
- 学校体育活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/rms
- 周末休闲规划的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Rh3
- 乡村公共阅读的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/657=fpo
- 在线教育体验的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/yet=641
- 城市便民驿站的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8A%E5%B2%B8_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/v3O=cHZ
- 公共空间休憩的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/788
- 小区电梯维护的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/tgs
- 青少年户外教育的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/DOm
- 城市运动公园的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/983=jzh
- 家庭志愿活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/awy=723
- 社区防暑服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%95%99%E8%82%B2?/2ir=CGq
- 家庭健康科普的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/771
- 乡村电商实践的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/bjg
- 数字创作工具的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/b4M
- 绿色生活实践的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/275=oso
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/jnf=030
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/UJi=rGQ
- 在线学习体验的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/293
- 乡村公共服务的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/zko
- 街道综合服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/fg8
- 乡村教育资源的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/775=ctm
- 社区公共议事中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/cbj=246
- 非遗体验活动的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/UUo=l55
- 社区公共餐饮的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/034
- 公共健身器材的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/tml
- 社区公共卫生的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/LZc
- 公共文化活动的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/613=yep
- 城市基础设施的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/tvc=356
- 数字生活课堂的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/R8Q=kO1
- 社区艺术活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8IV_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/441
- 社区活动报名的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8IV_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/sbq
- 社区信息发布的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8IV_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/ImY
- 社区活动策划的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8IV_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/095=xcy
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8IV_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/ylv=323
- 智能家居应用的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8IV_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/ITE=LSV
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E6%95%B0%E7%A0%81?/602
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E6%95%B0%E7%A0%81?/fna
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E6%95%B0%E7%A0%81?/fGY
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E6%95%B0%E7%A0%81?/564=ppl
- 公共服务数字化的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E6%95%B0%E7%A0%81?/zla=867
- 城乡交流活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E6%95%B0%E7%A0%81?/txy=8kW
- 家庭环保行动的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/185
- 公共空间安全的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/wym
- 社区商业活力的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/gdr
- 社区协商议事的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/945=sik
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/wtq=288
- 个人时间管理的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%95%99%E8%82%B2?/JOU=pk7
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/532
- 健康信息获取的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/rxr
- 数字素养提升的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/dEL
- 乡村文化空间的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/375=uol
- 城市慢跑路线的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/zgy=020
- 校园社团活动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/oMI=Fob
- 校园社团活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/162
- 租房信息服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/yuf
- 城市游园体验的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/msi
- 城市公共饮水的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/586=ewv
- 公共空间导览的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/iyq=083
- 科技馆参观体验的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/QTi=2yB
- 社区协商议事的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_3%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/408
- 图书借阅体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_3%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/mug
- 邻里共享空间的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_3%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/6ZU
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_3%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/454=gkt
- 家庭科学教育的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_3%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/inq=865
- 老年人文化生活的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_3%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/c8x=Wl2
- 儿童阅读角的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/453
- 社区生活指南的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/aqz
- 社区运动空间的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/GtH
- 公共场馆服务的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/882=fsk
- 社区活动报名的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/ydy=849
- 校园节能行动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/ivm=1ah
- 数字支付体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/304
- 乡村教育资源的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/mew
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/YoD
- 城市基础设施的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/010=dql
- 文化讲座服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/gvl=189
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/rns=9i6
- 在线教育体验的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/110
- 青年就业服务的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/dxl
- 个人时间管理的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/Jjg
- 网络安全教育的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/227=yjp
- 家庭园艺实践的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/mcq=502
- 乡村文化活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/8XI=Uu4
- 公共服务咨询的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/038
- 公共空间休憩的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/hjo
- 城市树木认养的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/quz
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/391=gsq
- 线上阅读资源的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/lzm=068
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%B0%91%E7%94%9F?/626=Rfm
- 城市文明实践的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/816
- 乡村生态观察中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/qpb
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/lgl
- 家庭节能设备的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/384=byz
- 家庭阅读计划的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/fms=909
- 街区小店体验的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/qZz=gCx
- 软件开发学习的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_5%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/539
- 科技馆参观体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_5%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/jyb
- 健康信息获取的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_5%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/Rgv
- 城市噪声观察的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_5%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/936=wnn
- 安全出行教育的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_5%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/yvw=180
- 公共健身器材的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_5%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%96%B0%E9%97%BB?/lSl=Wml
- 城市步行友好的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%91%8A?/423
- 机器人科普活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%91%8A?/jex
- 城市文明出行的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%91%8A?/jRB
- 老年人日常照护的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%91%8A?/742=qyr
- 电动汽车充电的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%91%8A?/bmp=890
- 数字设备回收的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%91%8A?/1t2=ceL
- 社区设施共享的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3welcome_360%E6%8A%95%E7%A8%BF?/445
- 无障碍出行的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3welcome_360%E6%8A%95%E7%A8%BF?/smg
- 骑行路线规划的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3welcome_360%E6%8A%95%E7%A8%BF?/fXE
- 数字设备回收的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3welcome_360%E6%8A%95%E7%A8%BF?/110=gxr

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
