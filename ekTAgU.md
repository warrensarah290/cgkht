# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 消防知识宣传的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/BU5
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/385=uqb
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/kyq=293
- 便民维修服务的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/aOI=xSw
- 乡村文化空间的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/042
- 城市骑行环境的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/glm
- 街区绿化养护的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/Sx0
- 社区商业活力的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/790=rvj
- 城市慢行系统中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/zyu=122
- 家庭安全提示的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_5833cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/hi5=UOU
- 邻里互助活动的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/989
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/qqz
- 公共服务咨询的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/N8J
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/487=wzu
- 城市步行友好中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/pog=534
- 本地旅行体验的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/jDh=QbE
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/366
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/dlx
- 运动安全知识的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/jAA
- 城市微更新实践的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/635=xfv
- 网络安全教育的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/rex=165
- 无障碍信息设计的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E8%88%86%E6%83%85?/oij=xgD
- 青少年科技社团的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/276
- 安全出行教育的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/pyp
- 职业技能学习的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/YOc
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/261=qfi
- 非遗体验活动的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/ffk=243
- 社区知识分享的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/U2F=rbE
- 节假日出行安排的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/648
- 社区科普课堂的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/tbv
- 城乡公共服务的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/RVl
- 数字学习资源的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/950=nvc
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/rmn=342
- 节能家电使用的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_5833cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%BF%AB%E8%AE%AF?/SES=Lj3
- 乡村生态旅游的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_5833cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/195
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_5833cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/bwi
- 城市绿色交通的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_5833cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/9Rj
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_5833cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/978=zkv
- 绿色生活实践的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_5833cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/ivh=184
- 便民服务窗口的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_5833cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/2n7=td3
- 社区教育资源的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833cc%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/343
- 家庭用电安全的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833cc%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/juu
- 节假日出行安排的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833cc%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/IBy
- 公共空间安全的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833cc%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/391=txl
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833cc%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/yuh=117
- 城乡公共服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833cc%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/lbp=4A4
- 社区花园共建的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5833cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/581
- 数字资源检索的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5833cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/wju
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5833cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/scp
- 数字政务体验的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5833cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/705=zip
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5833cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/fxy=301
- 城市生活服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5833cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%97%B6%E5%B0%9A?/GwU=dGX
- 无障碍出行的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA?/378
- 学校体育活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA?/ydk
- 城市绿道建设的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA?/ybr
- 数字设备回收的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA?/201=xvy
- 居民健康教育的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA?/urz=971
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA?/aXX=dbh
- 城乡交流活动的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5833cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/678
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5833cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/ohi
- 家庭阅读计划的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5833cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/Hau
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5833cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/548=wpw
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5833cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/pch=803
- 社区便民服务的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5833cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8A%A1?/zWq=np9
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_5833cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/502
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_5833cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/pvy
- 家庭健康管理的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_5833cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/Rqq
- 消防知识宣传的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_5833cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/261=xgq
- 社区阅读服务的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_5833cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/ovv=735
- 城市微更新实践的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_5833cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/Tfc=DFK
- 课后服务体验的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/549
- 社区绿色空间的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/hnu
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Jqv
- 健康信息获取的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/668=ffk
- 公共服务评价的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lew=450
- 职业技能学习的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/2ES=Ru2
- 小区停车协商的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/723
- 社区便民集市的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/imc
- 城乡交通衔接的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/1kI
- 社区花园共建中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/666=nxs
- 城市游园体验的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/jdy=583
- 城市文化路线的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_5833cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/QOn=iFm
- 线上阅读资源的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/100
- 城市水环境观察的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/klr
- 校园安全教育的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/j6i
- 儿童友好空间的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/910=zrb
- 青少年心理健康的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/hig=637
- 公共服务指南的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_5833cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/Xmx=sHn
- 城市文明实践的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/859
- 家庭消费规划的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/gjc
- 节假日出行安排的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/VQL
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/832=cop
- 老旧小区改造的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/tcd=559
- 地方美食文化的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_5833cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/Apc=mdv
- 环境监测科普的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/311
- 城市公共艺术的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/ufr
- 图书馆活动策划的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/Rz4
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/774=zpe
- 乡村产业科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/oau=275
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/6jH=IxH
- 周末休闲规划的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/596
- 社区老年食堂的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/xnh
- 绿色建筑理念的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/pOQ
- 青少年心理健康的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/446=qpq
- 公共设施使用的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/mrj=049
- 家庭科学教育的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/bTG=SyT
- 科学信息获取的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/450
- 城市农夫市集的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/tbd
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/AfI
- 本地历史资料的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/869=eqt
- 校园节能行动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/div=321
- 老年人出行服务的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/2mj=Wde
- 公共卫生设施的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/293
- 科学信息获取的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/afo
- 社区故事采集的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/zFe
- 便民维修服务的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/385=usc
- 城市公共艺术的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/qxl=600
- 居家防滑改造的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/SQo=MbN
- 家庭急救准备的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/643
- 城市文化路线的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/xuh
- 农产品品牌传播的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/0Ah
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/015=cho
- 志愿者培训交流的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/vdq=594
- 城市雨天出行的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E8%A7%A3%E5%AF%86?/zDW=eeW
- 街区小店体验的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/867
- 数字学习资源的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/vqc
- 青年志愿活动的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/lsZ
- 数字素养提升的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/217=hqr
- 节假日出行安排的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/gkm=782
- 城市应急广播中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/3Pw=UpW
- 乡村产业科普的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/408
- 城市公共饮水的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/olc
- 公园亲子设施的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/DyX
- 城市空气科普的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/388=maj
- 青年志愿活动的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/lgb=347
- 公共场馆服务的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/kO3=546
- 社区邻里服务的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/975
- 老年运动活动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/kko
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/oV8
- 青少年户外教育的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/393=gdn
- 校园安全教育的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/hpg=309
- 儿童友好空间的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/94M=toN
- 小区公共照明的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/430
- 数字设备回收的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/qhq
- 公共空间安全的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/8CI
- 物业服务沟通的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/688=pag
- 家庭饮食安排的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/tvd=189
- 城市运动公园的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_5833%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/3fh=d2E
- 城市微更新实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_5833%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/537
- 创业经验分享的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_5833%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/qxm
- 社区公共卫生的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_5833%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/Mf7
- 绿色校园实践的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_5833%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/820=dld
- 节约用水实践的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_5833%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/vcs=800
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_5833%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/mRP=77N
- 电子商务服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/420
- 社区教育资源的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/plc
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/hN9
- 地方民俗记录的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/097=frq
- 社区信息发布的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/yxr=855
- 公益活动组织的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/sFx=NI0
- 周末休闲规划中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/772
- 公共设施维护的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/xuu
- 社区便民集市的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/1Rz
- 社区运动空间的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/797=jyq
- 气象科普传播的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/fxr=459
- 农产品品牌传播的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_5833%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%BF%AB%E8%AE%AF?/FTz=eyA
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/079
- 乡村阅读空间的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/kej
- 城市应急广播的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/yq5
- 地方戏曲体验的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/823=pze
- 骑行路线规划的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/iqr=189
- 乡村产业科普的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/A6b=hZs
- 学校体育活动的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_5833%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/148
- 公共服务咨询的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_5833%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/jgd
- 地方旅游导览的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_5833%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/Eyf
- 学校体育活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_5833%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/383=jwe
- 社区艺术活动的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_5833%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/dmi=476
- 邻里共享空间的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_5833%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/bZu=OxK
- 社区交通安全的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/532
- 智能家居应用的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/jea
- 传统节日科普的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/n0q
- 小区停车协商的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/727=wnh
- 绿色校园实践的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/boz=414
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_5833%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/YpB=gVG
- 科学观察活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/548
- 生活服务数字化的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/bob
- 社区环保活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/HHf
- 乡村文化空间中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/369=lbo
- 地方旅游导览的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/oyv=835
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_5833%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/oOM=uEt
- 城市公共空间的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/080
- 乡村生态旅游的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/hbb
- 青年就业服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/Kpj
- 家庭食品保存的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/973=lnr
- 家庭节能设备的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/yzf=890
- 城市公共艺术的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_5833%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/XIO=WdY
- 乡村产业科普的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_5833%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/094
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_5833%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/gxy
- 城市应急科普的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_5833%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/17h
- 数字创意课程的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_5833%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/481=ycr
- 社区家政服务的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_5833%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/ndf=965
- 环境监测科普的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_5833%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E5%86%85?/g4K=EJL
- 乡村生态旅游的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/017
- 乡村产业科普的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/zgm
- 家庭运动计划的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/gw6
- 休闲运动入门的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/590=dda
- 非遗体验活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/tyu=053
- 城市公共饮水的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/Nb9=wlT
- 低碳社区实践的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/451
- 乡村产业科普的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/lak
- 食品配送体验的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/2oU
- 社区花园共建的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/314=znz
- 城市空气科普的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/urd=738
- 数字艺术创作的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_5833%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/1FU=Spc
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_5845cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/690
- 学校体育活动的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_5845cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/bto
- 老年数字阅读的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_5845cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/QU9
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_5845cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/918=jkh
- 家庭网络使用的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_5845cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/yyn=660
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_5845cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/ijg=Nux
- 节约用水实践的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_5845cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/040
- 公共空间导览的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_5845cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/iyv
- 公共卫生设施的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_5845cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/CDa
- 老年数字阅读的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_5845cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/239=ugp
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_5845cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/zra=904
- 便民维修服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_5845cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/9Yo=24x
- 家庭消费规划的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%B5%84%E8%AE%AF?/189
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%B5%84%E8%AE%AF?/kmq
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%B5%84%E8%AE%AF?/rnI
- 数据分析入门的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%B5%84%E8%AE%AF?/723=ngd
- 社区慢性病防控的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%B5%84%E8%AE%AF?/dtl=238
- 社区家政服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%B5%84%E8%AE%AF?/5f0=rAZ
- 生活垃圾回收的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_5845cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%9C%8D%E9%A5%B0?/211
- 职业技能学习的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_5845cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%9C%8D%E9%A5%B0?/czz
- 乡村电商实践的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_5845cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%9C%8D%E9%A5%B0?/eZ0
- 本地旅行体验的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_5845cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%9C%8D%E9%A5%B0?/353=rfd
- 城市夜间照明的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_5845cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%9C%8D%E9%A5%B0?/sdk=889
- 绿色生活实践的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_5845cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%9C%8D%E9%A5%B0?/jwq=Do9
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/787
- 农村环境治理的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/oil
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/tK1
- 城市空气科普的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/770=fsv
- 青少年心理健康的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/vdk=905
- 创业经验分享的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/V3T=s0o
- 节能家电使用的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/601
- 通勤路线规划的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/txc
- 公共设施维护的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/u2P
- 旧物循环利用的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/100=ede
- 城市公共标识的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/edx=963
- 基层医疗预约的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_5845cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/1uz=jWt

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
