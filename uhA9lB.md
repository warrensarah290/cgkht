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

- 校园阅读活动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/ald=300
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/2jQ=2dV
- 农业科普体验的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/699
- 职业技能学习的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/zng
- 物业服务沟通中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/uWa
- 户外活动组织的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/482=rdg
- 健康饮食教育的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/ajq=571
- 社区家政服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/2cf=1dg
- 城市基础设施的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/093
- 城市公共空间的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/jve
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/2ll
- 地方旅游导览的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/933=ccr
- 智能家居应用中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/htm=559
- 城市雨天出行的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/2Wt=OGk
- 城市骑行环境的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/854
- 日常摄影记录的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/qxc
- 公共空间导览的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/dn2
- 小区停车协商的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/338=gsh
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/xtv=165
- 城市住房服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/L0p=n3H
- 非遗课堂体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/928
- 乡村文化活动的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/lsf
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/efb
- 老年运动活动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/226=gqr
- 生活服务数字化的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/ixc=275
- 公共空间休憩的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/N8G=iZW
- 城市慢行系统的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/428
- 社区应急准备的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/dyk
- 城市微更新实践的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/BIY
- 城乡交流活动的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/169=zea
- 数字学习资源的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/jrx=883
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/2L4=1VN
- 医院导诊服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/437
- 城市绿色交通的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/gbf
- 公共卫生宣传的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/0nF
- 数字课堂应用的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/725=upj
- 城市步行友好的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/nxe=698
- 药品使用科普的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/dLu=DIu
- 城市树木认养的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/811
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/iku
- 绿色办公实践的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/57Q
- 社区阅读服务的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/123=qsk
- 开源技术交流的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/smu=868
- 家庭养老规划的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/VW9=xjt
- 社区文化节活动的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/122
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/mpg
- 城市夜间照明的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/r51
- 本地旅行体验的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/873=lyw
- 城乡交通衔接的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/ngw=355
- 本地消费场景的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/EYi=T8D
- 青少年科普实践的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/374
- 社区健康讲座的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/moh
- 在线教育体验的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/8DN
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/331=psm
- 城市应急科普的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/jft=813
- 网络信息辨识的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/i9O=WET
- 社区绿色空间的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/797
- 街区小店体验的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/qjn
- 街道综合服务的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/Xu9
- 公共服务数字化的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/058=wae
- 城市公共座椅的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/aek=947
- 老年智能设备的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/y2p=tVp
- 家庭安全提示的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/332
- 开放数据应用的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/slp
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/z7v
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/266=bin
- 城市公共艺术的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/xfa=349
- 在线学习体验的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/ynv=zpi
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/523
- 全民健身活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/lhk
- 地方旅游导览从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/XJe
- 开源技术交流的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/057=tdq
- 绿色生活实践中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/qcb=042
- 邻里互助活动的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/xCV=WxZ
- 本地历史资料的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/379
- 社区科普课堂的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/mjs
- 儿童友好空间的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/P4D
- 小微企业服务的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/510=dtd
- 数字支付体验的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/zmz=750
- 小区公共照明中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/eIy=7pT
- 健康信息获取的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/575
- 文化场馆预约的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/nuh
- 基层健康档案的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/mFY
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/017=jim
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/evg=175
- 街道综合服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/6Iw=KOd
- 科学运动指导的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/886
- 健康信息获取的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/lyx
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/Xgn
- 乡村文化活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/860=uqh
- 文化场馆预约的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/wwa=802
- 开放式学习空间的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91ll%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/qoq=BMt
- 社区家校合作的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/842
- 社区托育服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/zkp
- 社区垃圾分类的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/ode
- 学校食育活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/588=gbb
- 公共服务沟通的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/kqq=997
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%88%BF%E4%BA%A7?/UgM=XuD
- 本地历史资料的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/898
- 节约用水实践的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/ijv
- 公园无障碍服务的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/6MV
- 乡村产业科普的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/865=ckn
- 无障碍出行的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/pex=208
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/Mth=FOx
- 灵活就业交流的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/999
- 青少年科技社团的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/wjf
- 数字生活课堂的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/EJl
- 社区文化传播中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/728=dth
- 城市社区治理的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/vus=783
- 无障碍出行的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/rfS=aOG
- 老年数字阅读的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/522
- 校园社团活动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/use
- 城市生活服务的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/Yx4
- 公共文化活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/551=ted
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/fkl=847
- 非遗体验活动的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/xHV=bYY
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/315
- 垃圾分类指导的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/gjt
- 社区共享书架的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/jrC
- 线上办事服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/206=kfk
- 数据分析入门的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/uim=364
- 创业经验分享的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/xK0=OOR
- 社区安全巡查的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/482
- 数字学习资源的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/nrl
- 公共空间安全的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/eLy
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/955=oct
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/dkk=842
- 健康饮水科普的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/N7v=sOX
- 校园节能行动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/563
- 在线学习体验的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/djy
- 绿色出行服务的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/yvx
- 数字便民地图的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/151=bkp
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/tlr=904
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/Bsp=fze
- 开源技术交流的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/267
- 志愿者培训交流的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/lwe
- 图书借阅体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/ig7
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/010=zdp
- 校园安全教育的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/fed=539
- 城市社区治理的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B8%AD%E4%B8%9C%E8%B4%A2%E7%BB%8F?/FPJ=kVO
- 租房信息服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/982
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/qow
- 城市体育设施的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/bew
- 居家适老化改造的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/354=ifo
- 城乡公共服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/sio=854
- 骑行路线规划的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/VrW=emC
- 乡村生态观察的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/558
- 读书会组织的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/wkz
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/zAb
- 社区阅读服务的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/543=qii
- 非遗体验活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/gzz=181
- 电子商务服务的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/WTw=rJ1
- 公共文化活动的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/588
- 文化场馆预约的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/ooe
- 城市步行友好的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/7n1
- 本地消费场景的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/583=azq
- 社区公共卫生的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/ugu=277
- 数字阅读服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/1vn=ylL
- 社区儿童活动的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/924
- 老年人出行服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/zjm
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/UK0
- 社区运动空间的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/838=nuy
- 城市绿道建设的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/xfk=100
- 社区垃圾分类的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/HUZ=57l
- 城市公共饮水的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/948
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/iac
- 节约用水实践的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/ITt
- 城市体育设施的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/724=qsq
- 社区绿色空间的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/ghv=369
- 农业科普体验的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/uoT=H9E
- 城市地名文化的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/423
- 公共设施维护中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/uug
- 公共服务咨询的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/XLV
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/624=yai
- 社区老年食堂的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/yvl=638
- 线上办事服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/OTV=D6H
- 数字政务体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/638
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/zpr
- 乡村产业科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/vEt
- 家庭安全提示的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/442=hnx
- 青少年心理健康的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/ypr=283
- 乡村产业科普的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/ZOA=Ven
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/125
- 乡村产业科普的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/svh
- 家庭养老规划的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/Wiu
- 社区便民集市的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/129=bms
- 城市公共厕所的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/dae=282
- 数字政务体验的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/hCz=z7E
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/984
- 乡村生活观察的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/jyt
- 社区活动空间的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/1qZ
- 校园安全教育的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/231=eau
- 数据分析入门的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/frx=801
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/c8h=rV3
- 城市公共饮水的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A?/206
- 城市可持续生活的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A?/cac
- 儿童友好空间的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A?/64u
- 数字生活课堂的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A?/841=lsy
- 文化讲座服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A?/dvc=720
- 居家适老化改造的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A?/gV6=eIm
- 社区运动空间的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/153
- 街区绿化养护的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/ukp
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/0ry
- 城市公共厕所的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/433=hup
- 远程协作工具的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/tbs=679
- 居民健康教育的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/ugG=NN7
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/655
- 急救知识普及的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/ppi
- 家庭健康管理中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/CcV
- 骑行路线规划中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/846=kdd
- 社会体育指导的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/udo=574
- 城市文明出行的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%94%BE?/JQ0=33u
- 绿色校园实践的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/991
- 校园阅读活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/djy
- 志愿者培训交流的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/XYz
- 公共文化活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/073=hea
- 终身学习资源的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/mao=407
- 基层健康服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%94%BF%E5%8A%A1?/GDw=00p
- 家庭饮食安排的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/170
- 数字创意课程的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/yjl
- 线上阅读资源的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/bUh
- 非遗体验活动的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/702=sdb
- 食品配送体验的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/nir=377
- 社区心理支持的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/jpj=FPQ
- 智能手机助老的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/573
- 开放数据应用的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/pye
- 城市体育设施的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/vqK
- 城市休闲步道的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/854=icb
- 社区消防演练的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/ynj=089
- 软件开发学习的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/kmO=k0h
- 公共服务预约的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/222
- 社区便利生活的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/nom
- 社区知识分享的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/rM2
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/342=mah
- 公共健身器材的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/hfa=306
- 创业经验分享的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/JR3=bBK
- 城市公共饮水的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/084
- 个人信息保护的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/mec
- 终身学习资源的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/hrx
- 青年职业探索中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/527=qol
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/kai=841
- 数字创作工具的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/3yn=CKw
- 数字政务体验的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/871
- 智慧城市体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/jtt
- 邻里互助活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/dE8
- 家庭节能实践的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/764=fde
- 城市树木认养的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/ksh=941
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/UlW=2Qw
- 社区儿童活动的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/468
- 城市公共标识的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/uvb

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
