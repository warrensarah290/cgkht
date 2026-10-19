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

- 社区托育服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E8%A7%84%E5%BE%8B_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/125
- 非遗体验活动的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E8%A7%84%E5%BE%8B_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/tao
- 社区停车服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E8%A7%84%E5%BE%8B_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/mE3
- 公共卫生设施的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E8%A7%84%E5%BE%8B_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/838=aqt
- 乡村文化空间的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E8%A7%84%E5%BE%8B_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/lvb=206
- 网络安全教育的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E8%A7%84%E5%BE%8B_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/RaL=4oH
- 急救知识普及的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%A7%91%E6%8A%80?/844
- 社区便民集市的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%A7%91%E6%8A%80?/bdj
- 健康饮水科普的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%A7%91%E6%8A%80?/XlY
- 城市公共空间的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%A7%91%E6%8A%80?/206=mes
- 城市生活记录的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%A7%91%E6%8A%80?/kld=372
- 传统节日科普的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E7%A7%91%E6%8A%80?/UDf=4Zq
- 图书馆活动策划的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/929
- 市民热线服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/mhk
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/KRw
- 青少年心理健康的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/086=ynw
- 儿童友好空间的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/dzy=972
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/JoX=vBu
- 健康信息获取的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8C%9C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/730
- 社区老年食堂的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8C%9C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/dia
- 生活垃圾减量的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8C%9C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/JBJ
- 乡村公共服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8C%9C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/227=vdv
- 城市文明出行的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8C%9C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/fwu=588
- 网络安全教育的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8C%9C%E5%92%8C%E5%80%BC_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BD%AC%E8%BD%BD?/GYO=t6g
- 社区养老服务的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/096
- 公共服务沟通的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/smh
- 城市慢行系统的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/LlC
- 城乡交通衔接的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/739=rqd
- 学校食育活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/nmb=947
- 公共文化活动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8D%8F?/d4Z=JE3
- 绿色出行服务的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E6%9C%89%E4%B8%89%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/313
- 消防知识宣传的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E6%9C%89%E4%B8%89%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/rbr
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E6%9C%89%E4%B8%89%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/hLp
- 城市基础设施的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E6%9C%89%E4%B8%89%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/335=gof
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E6%9C%89%E4%B8%89%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/wvm=400
- 公共健身器材的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E6%9C%89%E4%B8%89%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/4zO=wZH
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/460
- 非遗体验活动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/mfa
- 低碳社区实践的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/Jz5
- 乡村文化活动的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/467=ocu
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/ahk=943
- 城市体育设施的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/bie=rMC
- 市民热线服务的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/299
- 城市噪声观察的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/ddr
- 线上办事服务的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/cmu
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/739=yqk
- 城市生活服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/rwk=837
- 城市运动公园的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/Tvy=d3S
- 读书会组织的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%BA%94%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_360%E5%A8%B1%E4%B9%90?/929
- 城市公共空间的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%BA%94%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_360%E5%A8%B1%E4%B9%90?/lso
- 社区设施共享的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%BA%94%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_360%E5%A8%B1%E4%B9%90?/aM1
- 软件开发学习的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%BA%94%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_360%E5%A8%B1%E4%B9%90?/395=vxm
- 社区艺术活动的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%BA%94%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_360%E5%A8%B1%E4%B9%90?/cxj=784
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%8E%92%E5%88%97%E4%BA%94%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_360%E5%A8%B1%E4%B9%90?/SH4=FWG
- 智慧停车服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%90%E5%85%AB%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/973
- 家庭网络使用的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%90%E5%85%AB%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/ycx
- 城市可持续生活的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%90%E5%85%AB%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/t3P
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%90%E5%85%AB%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/225=dwj
- 急救知识普及的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%90%E5%85%AB%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/ygi=292
- 家庭园艺实践的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%90%E5%85%AB%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/43D=Duv
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/437
- 传统手工艺体验从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/qeo
- 家庭饮食安排的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/uxf
- 社区健康讲座的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/880=rht
- 城市文化路线的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/ypn=599
- 老年运动活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/mEs=idu
- 城市应急科普的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_5%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E9%98%B6%E6%A2%AF%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%96%B9%E6%A1%88_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/113
- 农产品消费体验的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_5%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E9%98%B6%E6%A2%AF%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%96%B9%E6%A1%88_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/zvb
- 公共交通信息服务的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_5%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E9%98%B6%E6%A2%AF%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%96%B9%E6%A1%88_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/VxF
- 家庭环保行动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_5%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E9%98%B6%E6%A2%AF%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%96%B9%E6%A1%88_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/959=ixx
- 社区活动报名的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_5%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E9%98%B6%E6%A2%AF%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%96%B9%E6%A1%88_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/rop=353
- 数字公共文化的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_5%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E9%98%B6%E6%A2%AF%E5%80%8D%E6%8A%95%E6%9C%80%E4%BD%B3%E6%96%B9%E6%A1%88_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/iC1=2sm
- 城市可持续生活的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95%E5%92%8C%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/962
- 公共文化活动的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95%E5%92%8C%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/yvf
- 城市水环境观察的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95%E5%92%8C%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/JFZ
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95%E5%92%8C%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/100=txd
- 城市公共标识的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95%E5%92%8C%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/cpr=626
- 公交站点体验的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95%E5%92%8C%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/T1K=Gqf
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_2%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/093
- 邻里互助活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_2%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/wlu
- 乡村产业科普的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_2%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/CR2
- 数字课堂应用的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_2%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/348=vft
- 社区心理支持的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_2%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/vti=631
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_2%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/QG1=jP0
- 城市文明实践的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A?/925
- 数字学习资源的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A?/qrx
- 本地消费场景的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A?/E6J
- 家庭安全提示的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A?/392=ycf
- 智慧城市体验的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A?/mni=786
- 地方戏曲体验的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A?/vpB=KjV
- 社区共享书架的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/923
- 城市应急科普的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/ytp
- 青年职业探索的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/xXz
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/817=ogy
- 街区更新实践的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/lrm=544
- 物业服务沟通的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/jeC=uII
- 家庭阅读计划的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AB%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/833
- 医院导诊服务的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AB%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/mmk
- 社区运动空间的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AB%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/r9H
- 个人信息保护的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AB%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/116=vtr
- 骑行路线规划的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AB%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/xnz=966
- 本地消费场景的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AB%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/Q7m=CR1
- 社区商业活力的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87%E5%A4%A7%E5%85%A8_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/263
- 社区故事采集的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87%E5%A4%A7%E5%85%A8_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/mdz
- 气象科普传播的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87%E5%A4%A7%E5%85%A8_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/upl
- 文化讲座服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87%E5%A4%A7%E5%85%A8_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/053=ioj
- 家庭志愿活动的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87%E5%A4%A7%E5%85%A8_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/upt=586
- 基层健康服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87%E5%A4%A7%E5%85%A8_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/6LD=fXq
- 社区养老服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/306
- 在线教育体验的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/xqo
- 数字档案服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/cBR
- 社区活动策划的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/516=gnc
- 智能家居应用的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/djn=674
- 家庭防灾准备的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/BXx=Om7
- 城市文明出行的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/373
- 儿童安全出行的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/zcg
- 科学运动指导的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/JvN
- 城市夜间照明的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/640=xzy
- 绿色生活实践的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/jmr=544
- 智慧城市体验的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%9B%88%E5%88%A9%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/M3W=hUn
- 城市农夫市集的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/609
- 节日文化体验的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/nur
- 小微企业服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/b70
- 数字学习资源的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/239=faf
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/kli=989
- 老旧小区改造的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E5%A6%86?/WiK=5Oz
- 线上阅读资源的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/702
- 科普展览体验的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/env
- 社区文化节活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/b9f
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/197=dxp
- 地方戏曲体验的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/tvy=899
- 社区应急准备的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/3NN=HMj
- 城市游园体验中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/183
- 家庭环保习惯的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/lnz
- 在线教育体验的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/R6q
- 家庭科学教育的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/221=urf
- 街头绿植养护的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/kfv=943
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/rdN=Y5M
- 儿童运动体验的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BB%80%E4%B9%88%E7%B2%BE%E5%87%86%E5%BC%95%E6%B5%81%E7%9A%84%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/137
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BB%80%E4%B9%88%E7%B2%BE%E5%87%86%E5%BC%95%E6%B5%81%E7%9A%84%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/scg
- 农村环境治理的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BB%80%E4%B9%88%E7%B2%BE%E5%87%86%E5%BC%95%E6%B5%81%E7%9A%84%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/Epz
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BB%80%E4%B9%88%E7%B2%BE%E5%87%86%E5%BC%95%E6%B5%81%E7%9A%84%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/788=sow
- 社区儿童活动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BB%80%E4%B9%88%E7%B2%BE%E5%87%86%E5%BC%95%E6%B5%81%E7%9A%84%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/moi=833
- 社区阅读服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BB%80%E4%B9%88%E7%B2%BE%E5%87%86%E5%BC%95%E6%B5%81%E7%9A%84%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E4%BC%97%E6%B5%8B?/2XE=8rf
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/132
- 科学健身方法的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/lki
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/3Iz
- 新能源出行的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/901=csf
- 健康饮水科普的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/ogl=330
- 青少年科普实践的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/Ok2=HHe
- 社区快递服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/192
- 健康信息获取的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/vqk
- 公共卫生宣传的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/GAk
- 地方旅游导览的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/891=tzt
- 地方民俗记录的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/muf=734
- 城市应急科普的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E4%B9%A6?/fKZ=wDI
- 社区公共议事的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/192
- 休闲运动入门的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/eka
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/Iy1
- 青少年科普实践的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/929=yzy
- 文化场馆预约的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/spc=402
- 社区家政服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/BqT=M2O
- 老年人出行服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/391
- 本地消费场景的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/ogs
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/ks3
- 户外活动组织中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/978=rlj
- 远程协作工具的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/imd=142
- 青少年科普实践的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%98%AF%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/2gv=6H4
- 老年数字阅读的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/449
- 智能手机助老中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/ode
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/hI8
- 城市绿色交通的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/303=zye
- 公共设施维护的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/uyd=452
- 校园社团活动的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/hRN=ZWe
- 城市绿色交通中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%9C%A8%E7%BA%BF%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/752
- 老年数字阅读中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%9C%A8%E7%BA%BF%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/bil
- 家庭食品保存的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%9C%A8%E7%BA%BF%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/jpR
- 地方民俗记录的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%9C%A8%E7%BA%BF%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/145=rrd
- 社区公共卫生的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%9C%A8%E7%BA%BF%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/mcy=832
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%9C%A8%E7%BA%BF%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/ojo=Gkx
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%959%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/434
- 社区共享书架中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%959%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/hzq
- 老年数字阅读的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%959%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/MNJ
- 机器人科普活动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%959%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/375=ngz
- 课后服务体验的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%959%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/enl=407
- 公共服务沟通的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%959%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/pN0=gMA
- 课后服务体验中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E7%9A%84%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%9C%9F%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97__%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/451
- 公共空间导览的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E7%9A%84%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%9C%9F%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97__%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/pwy
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E7%9A%84%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%9C%9F%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97__%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/Q7t
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E7%9A%84%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%9C%9F%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97__%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/283=vop
- 光伏知识科普的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E7%9A%84%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%9C%9F%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97__%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/ylw=910
- 开放式学习空间的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E7%9A%84%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E7%9C%9F%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97__%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/M19=sm4
- 租房信息服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E8%B5%9B%E8%BD%A6%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/898
- 老年友好服务的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E8%B5%9B%E8%BD%A6%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/fsi
- 农产品消费体验的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E8%B5%9B%E8%BD%A6%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/odX
- 便民服务窗口的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E8%B5%9B%E8%BD%A6%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/392=thk
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E8%B5%9B%E8%BD%A6%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/zow=387
- 食品配送体验的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E8%B5%9B%E8%BD%A6%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/mFs=zgx
- 健康饮食教育的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/882
- 个人信息保护的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/vrz
- 家庭教育交流的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/rsc
- 急救知识普及的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/925=gqq
- 社区老年食堂的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/evj=081
- 小区电梯维护的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/VqJ=GY1
- 绿色办公实践的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%A5%BD_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/817
- 社区快递服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%A5%BD_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/wht
- 社区协商议事的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%A5%BD_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/J64
- 乡村文化活动的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%A5%BD_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/230=caf
- 儿童安全出行的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%A5%BD_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/zkl=031
- 城市社区治理的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A65%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E5%A5%BD_%E8%8A%92%E6%9E%9C%E8%AE%BA%E5%9D%9B?/TUY=nSR
- 绿色快递包装的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%917%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/143
- 城市公共厕所的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%917%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/ijv
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%917%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/n3n
- 社区休闲设施的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%917%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/330=udh
- 社区故事采集的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%917%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/dzl=694
- 科学信息获取的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%917%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/Mct=QfB
- 社区协商议事的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8C%97%E4%BA%ACp10%E8%B5%9B%E8%BD%A6%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/848
- 市民意见收集的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8C%97%E4%BA%ACp10%E8%B5%9B%E8%BD%A6%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/ojk
- 城市休闲步道的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8C%97%E4%BA%ACp10%E8%B5%9B%E8%BD%A6%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/rl5
- 公共服务数字化的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8C%97%E4%BA%ACp10%E8%B5%9B%E8%BD%A6%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/422=ula
- 运动安全知识的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8C%97%E4%BA%ACp10%E8%B5%9B%E8%BD%A6%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/rbm=766
- 公共服务评价的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8C%97%E4%BA%ACp10%E8%B5%9B%E8%BD%A6%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/0Lm=HSO
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E6%89%93%E6%B3%95_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/868
- 社区宣传栏更新的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E6%89%93%E6%B3%95_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/uyi
- 药品使用科普的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E6%89%93%E6%B3%95_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/jHI
- 就业技能培训的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E6%89%93%E6%B3%95_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/088=fuz
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E6%89%93%E6%B3%95_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/plb=008
- 城乡公共服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E6%89%93%E6%B3%95_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/kvZ=6nv
- 机器人科普活动的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8778%E7%A0%81%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%94%BF%E7%AD%96?/385
- 城市展览体验的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8778%E7%A0%81%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%94%BF%E7%AD%96?/yro
- 城市空气科普的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8778%E7%A0%81%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%94%BF%E7%AD%96?/H5n
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8778%E7%A0%81%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%94%BF%E7%AD%96?/221=otl
- 儿童友好空间的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8778%E7%A0%81%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%94%BF%E7%AD%96?/qoo=790
- 数字资源检索的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%8778%E7%A0%81%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%94%BF%E7%AD%96?/0kx=52E
- 公交无障碍服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%958%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/842
- 公园休闲体验从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%958%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/ebe
- 小微企业服务的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%958%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/EoW
- 社区环保活动的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%958%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/429=pti
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%958%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/wmm=791
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A67%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%958%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%97%B6%E5%B0%9A?/aX9=FsP
- 社区交通安全的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A63%E7%A0%8110%E6%9C%9F%E5%80%8D%E6%8A%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/761
- 老年人出行服务的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A63%E7%A0%8110%E6%9C%9F%E5%80%8D%E6%8A%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/cgi
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A63%E7%A0%8110%E6%9C%9F%E5%80%8D%E6%8A%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/nJP
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A63%E7%A0%8110%E6%9C%9F%E5%80%8D%E6%8A%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/804=fol
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A63%E7%A0%8110%E6%9C%9F%E5%80%8D%E6%8A%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/lhh=014
- 社区学习活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A63%E7%A0%8110%E6%9C%9F%E5%80%8D%E6%8A%95%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AF%BB%E6%8A%A5?/8g5=Bor
- 城市雨天出行的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A64%E7%A0%81%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/013
- 公共场馆服务的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A64%E7%A0%81%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/jyy
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A64%E7%A0%81%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/bQs
- 乡村教育资源的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A64%E7%A0%81%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/573=jdu

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
