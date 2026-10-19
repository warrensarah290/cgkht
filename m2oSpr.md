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

- 小区公共照明的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/4Rp
- 社区信息发布的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/654=kys
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/ymx=193
- 城市住房服务的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/h6x=IcV
- 基层健康服务的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/780
- 本地消费场景的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/kkn
- 青少年科普实践的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/Ire
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/749=cmo
- 社区环保活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/apv=057
- 老年友好服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/JzW=sbd
- 便民服务地图的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/103
- 社区心理支持的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/aqg
- 在线学习体验的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/fHs
- 社区体育组织的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/334=svs
- 家庭急救准备的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/uov=839
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E6%AF%8D%E5%A9%B4?/5mQ=dmc
- 数字政务体验的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/474
- 居家适老化改造的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/yqi
- 科学健身方法的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/zLR
- 新能源出行的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/264=blo
- 校园社团活动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/asm=135
- 周末休闲规划的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/SjH=1DP
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/227
- 健康步道使用中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/wfm
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/GXb
- 老旧小区改造的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/585=hvu
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/cno=627
- 医院导诊服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/Ead=Jeu
- 地方文化传播的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/126
- 城市微更新实践的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/cvv
- 科学教育活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/Vid
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/868=tiq
- 家庭收纳实践的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/emm=743
- 智能手机助老的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/Haf=eiF
- 校园阅读活动的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/450
- 个人数据管理的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/kfh
- 基层医疗预约的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/lxa
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/928=csh
- 便民服务窗口的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/vsi=383
- 街区道路维护的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/vgW=Krf
- 城市公共标识的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/837
- 健康饮水科普的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/ubh
- 乡村产业科普的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/6Qm
- 城市空气科普的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/500=nvs
- 数字艺术创作中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/ngd=576
- 家庭网络使用的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/zoM=WxU
- 信息无障碍体验的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/221
- 城市住房服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/icj
- 社区庭院绿化的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/hM4
- 乡村生态旅游的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/867=zmw
- 地方文化传播的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/waq=293
- 儿童运动体验的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/gdg=Cso
- 城市步行环境的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/128
- 青少年编程学习的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/osy
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/dtw
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/066=jtf
- 城市夜间生活的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/yqv=526
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/ne7=Rfl
- 家庭健康科普的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/801
- 老年智能设备中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/plk
- 节约用水实践的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/FhG
- 公共健身器材的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/042=bqb
- 家庭用电安全的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/qyb=751
- 老年人日常照护的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/tKp=JJL
- 家庭急救准备的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/283
- 城市树木认养的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/zzn
- 公共交通接驳的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/bH0
- 社区共享书架的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/762=vzt
- 学校食育活动的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/xod=565
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/4CR=YNp
- 小微企业服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/201
- 城市步行环境的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/zwu
- 社区公共卫生的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/QJt
- 个人信息保护的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/639=phy
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/yfm=895
- 公共服务咨询的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/Pjq=Ffx
- 健康信息获取的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/032
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/rir
- 职业技能学习的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/8Sc
- 学校食育活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/141=rkl
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/mcr=870
- 社区运动空间的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/Wn2=69m
- 便民服务地图的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/068
- 城市雨天出行的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/bib
- 家庭饮食安排的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/EeN
- 通勤路线规划的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/179=ejq
- 家庭急救准备的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/lzd=830
- 家庭饮食安排的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/qAs=cEg
- 居家防滑改造的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/416
- 远程协作工具的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/ltg
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/sNU
- 社区消防演练的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/774=eec
- 志愿者培训交流的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/nbo=322
- 公共场所导视的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/cUy=NyC
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/607
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/xnk
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/tEg
- 家庭网络使用的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/800=xpc
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/juw=652
- 城市步行环境的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/xvz=eFy
- 社区公共议事的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/120
- 社区便民集市的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/moy
- 社区生活指南的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/T59
- 老旧小区改造的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/775=haa
- 人工智能科普的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/zam=028
- 家庭照护支持的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/ANR=jhk
- 乡村生态旅游的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/914
- 城市游园体验的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/dry
- 安全出行教育的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/tHp
- 老年友好服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/326=zft
- 社区修缮行动的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/zbf=056
- 城市人文观察的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/yne=jOW
- 城市夜间照明的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/691
- 生成式工具使用的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/dpz
- 社区安全巡查的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/V4y
- 本地历史资料的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/923=fuo
- 城市夜间生活的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/rlt=413
- 课后服务体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/N7e=iTF
- 儿童友好街区的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/045
- 社区公共卫生的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/ynk
- 数字便民地图的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/DKz
- 图书借阅体验的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/704=yvn
- 光伏知识科普的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/mps=463
- 科技馆参观体验的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/ITo=w1m
- 家庭用电安全中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/228
- 公共设施使用的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/ksz
- 无障碍信息设计的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/r93
- 城市体育设施的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/400=lqe
- 智慧停车服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/yyc=486
- 旧物循环利用的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/Iyh=cNC
- 社区艺术活动的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/992
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/yql
- 城市体育设施的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/wq0
- 城市社区治理的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/768=tjt
- 社区家政服务的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/jez=913
- 便民维修服务的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/5nw=5Cf
- 网络安全教育的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/469
- 科学运动指导的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/ags
- 城市游园体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/XPB
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/672=yva
- 家庭收纳实践的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/mnn=854
- 公益活动组织的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E5%BC%80%E8%AF%BE?/pKW=uO8
- 乡村文化空间的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/943
- 家庭健康管理的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/qcc
- 基层健康服务的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/hqz
- 农产品消费体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/865=hcn
- 城市展览体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/jax=255
- 社区交通安全的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/b83=fWR
- 灵活就业交流的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/163
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/wbn
- 家庭园艺实践的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/CuS
- 城市休闲步道的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/463=hlu
- 学校体育活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/jnx=550
- 市民热线服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/qBP=JG7
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/230
- 在线教育体验的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/pgd
- 校园安全教育的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/okM
- 文化讲座服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/733=quy
- 创业经验分享的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/tgn=061
- 公园亲子设施中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/5mW=zQw
- 乡村教育资源的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/372
- 电子商务服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/vnb
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/G3G
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/456=kdt
- 社区老年食堂的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/jaf=925
- 地方旅游导览的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/QyQ=yDq
- 青年职业探索的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/391
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/edw
- 居家防滑改造的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/0QJ
- 社区活动空间的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/926=qka
- 社区科普课堂的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/cjb=079
- 社区花园共建的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/Rub=yaD
- 终身学习资源的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/668
- 公共设施使用的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/qct
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/Rfu
- 城市公共空间的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/441=jzp
- 数字公共文化的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/dym=308
- 社区协商议事的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/yVf=NZH
- 应急物资管理的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/272
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/prv
- 社区教育资源的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/OyW
- 新能源出行的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/373=eyz
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/zkd=456
- 城市社区治理的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/Sns=NHb
- 创业经验分享的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/939
- 数字创作工具的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/led
- 在线学习体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/fev
- 数字创意课程的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/115=mof
- 城市便民驿站的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/lyj=096
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%9E%E5%BD%95?/GNu=chZ
- 社区应急准备的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/372
- 城市共享单车的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/qrn
- 儿童阅读角的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/ECf
- 城市公共标识的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/162=fkj
- 社区文化节活动的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/bjj=855
- 青少年心理健康的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9app_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/VVY=bGq
- 家庭照护支持的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/737
- 数字资源检索的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/log
- 物业服务沟通的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/xtk
- 就业技能培训的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/335=teq
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/dcl=826
- 劳动教育实践的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/mhr=wnP
- 街道综合服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%A1%8C%E6%83%85?/733
- 光伏知识科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%A1%8C%E6%83%85?/iid
- 小微企业服务的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%A1%8C%E6%83%85?/OPx
- 线上阅读资源的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%A1%8C%E6%83%85?/967=lxe
- 传统节日科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%A1%8C%E6%83%85?/ogo=191
- 社区健康讲座的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B9%B3%C2%B7%E5%8F%B0_360%E8%A1%8C%E6%83%85?/f2e=by2
- 社区设施共享的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/137
- 城市游园体验的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/cgi
- 社区便利生活的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/ho1
- 食品配送体验的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/763=eii
- 智慧城市体验的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/nbx=490
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/ySW=yAf
- 个人时间管理的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/988
- 便民信息查询中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/wtb
- 数字创意课程的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/o1O
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/520=thy
- 科学健身方法的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/iwf=151
- 数字地图应用的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/TRp=TJi
- 本地消费场景的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/642
- 环境监测科普的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/jri
- 老年人出行服务的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/lFM
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/905=gms
- 休闲运动入门的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/fxk=285
- 公共服务数字化的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/2UB=jg5
- 智慧城市体验的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/934
- 终身学习资源的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/azo
- 就业技能培训的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/1Hj
- 药品使用科普的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/365=wlw
- 生活服务数字化的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/tqb=242
- 个人信息保护的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/lJh=hHO
- 城市步行环境的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/517
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/tfc
- 街区绿化养护中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/qef
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/890=dav
- 节气饮食文化的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/juw=344
- 文化场馆预约的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/WCy=lBv
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/930
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/sku
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/uyi
- 社区老年食堂的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/273=zgs
- 家庭环保行动的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/mdd=884
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E4%B8%93%E6%A0%8F?/CJB=P1E
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/379
- 绿色消费选择中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/ftt
- 社区设施共享的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/04c
- 城市空气科普的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/722=xka
- 药品使用科普的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/ins=362
- 城市共享单车的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/x7p=ZgG

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
