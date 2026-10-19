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

- 公共服务数字化的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/677
- 公共场所导视的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/bef
- 街头绿植养护的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/sGZ
- 乡村休闲旅游的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/865=yvj
- 城市体育设施的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/ndj=920
- 数字生活课堂的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%96%87%E6%91%98?/Cch=K0Q
- 城市住房服务的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/803
- 数字档案服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/xah
- 健康信息获取的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/obn
- 社区科普课堂的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/579=gik
- 小区电梯维护的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/uuw=807
- 社区便民集市的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%88%90%E9%83%BD%E5%BD%A9%E7%A5%A8%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/4Qx=kZo
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/124
- 传统节日科普的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/zew
- 急救知识普及的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/lZC
- 乡村电商实践的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/815=zom
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/qrd=720
- 街区小店体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%83%BD%E8%A2%AB%E5%BA%84%E5%AE%B6%E6%8E%A7%E5%88%B6%E5%90%97_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/KSx=5h7
- 周末休闲规划的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/091
- 地方美食文化的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/jgr
- 家庭网络使用的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/jZF
- 便民服务地图的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/135=dpo
- 生活垃圾减量的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/zqk=766
- 社区垃圾回收的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%87%BA%E5%8F%B7%E6%9C%89%E8%A7%84%E5%BE%8B%E5%9B%BE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A8%8E%E5%8A%A1?/dlo=2zT
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/153
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/pva
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/OCJ
- 城市夜间照明的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/258=vsv
- 社区安全巡查的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xtj=773
- 社区家政服务的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/K9r=2bA
- 公共空间安全的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/064
- 城市公共标识的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/mrv
- 公共场所导视的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/33y
- 数字艺术创作的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/194=jur
- 公共服务预约的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/jgd=407
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/VDb=hOI
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/286
- 志愿服务平台的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/ycx
- 非遗体验活动的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/EY5
- 公共健身器材的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/944=rag
- 城市骑行环境的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/vze=984
- 公共空间休憩的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99qq%E7%BE%A4%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92app_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/qzS=KbG
- 软件开发学习的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/944
- 社区商业活力的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/tdo
- 社区生活指南的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/RXe
- 社区互助网络的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/869=ley
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/vwl=322
- 乡村教育资源的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/fBv=cfH
- 家庭急救准备的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/682
- 社区活动策划的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/fuj
- 图书馆数字服务的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/0wL
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/842=qzq
- 创业经验分享的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/lev=174
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/g1x=Wf9
- 线上办事服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/307
- 城市应急广播的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/dvx
- 家庭环保行动的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/2iV
- 社区休闲设施的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/462=nga
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/ojd=954
- 科学运动指导的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/4Ze=h5H
- 科学健身方法的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/270
- 社区故事采集的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gjj
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Ek0
- 电子商务服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/136=fks
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ewn=211
- 信息无障碍体验的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/sCZ=xiu
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/218
- 社区消防演练的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/kad
- 基层健康档案的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/jwm
- 城市夜间照明的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/814=vae
- 数字支付体验的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/loa=408
- 社区公共议事中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92f1_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8A%A1?/ODX=8g0
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/202
- 绿色消费选择的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/snb
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/E1P
- 公共服务咨询的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/027=qex
- 公共服务指南的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/vfv=090
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AF%BC%E5%B8%88QQ_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/Yoh=YAG
- 社区文化传播的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/741
- 社区停车服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/ycx
- 绿色生活实践的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/ALS
- 社区防暑服务的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/471=cgx
- 绿色办公实践的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/gbe=947
- 安全出行教育的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%93%A67286688_%E5%87%A4%E5%87%B0%E5%9F%8E%E4%BA%8B?/LEb=m42
- 街区绿化养护中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/207
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/rto
- 公共设施使用的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/EX9
- 城市夜间生活的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/428=aho
- 口袋公园建设的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/act=934
- 便民信息查询的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/EvX=vtZ
- 读书会组织的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/074
- 节能生活方式的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/qdr
- 安全出行教育的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/9VV
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/988=hxl
- 城市公共厕所的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/rcw=147
- 科学运动指导中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E6%8C%BA%E8%AE%A1%E5%88%92%E7%BE%A4%E7%97%AA%E5%BE%98_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/5oL=Ub6
- 数字设备回收的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/915
- 公共设施使用的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/xgv
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/p5Q
- 消防知识宣传的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/367=saa
- 人工智能科普的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mdp=076
- 数字地图应用的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B4%B4%E5%90%A7_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/z0j=bib
- 农村环境治理的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/315
- 社区生活指南的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/jec
- 家庭用电安全的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/y6O
- 传统节日科普的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/049=hlr
- 街区更新实践的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/qhp=039
- 社区便民集市的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/n7a=hWC
- 绿色生活实践中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9B%BE%E7%89%87_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/042
- 骑行路线规划的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9B%BE%E7%89%87_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/lqd
- 亲子科普活动的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9B%BE%E7%89%87_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/ZKt
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9B%BE%E7%89%87_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/754=ptd
- 健康步道使用的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9B%BE%E7%89%87_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/wnf=525
- 家庭安全提示的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BE%A4%E5%9B%BE%E7%89%87_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/Kid=fDm
- 城市微更新实践的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E7%BE%A4_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/627
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E7%BE%A4_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/scg
- 数字支付体验的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E7%BE%A4_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/ud1
- 城市人文观察的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E7%BE%A4_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/637=vic
- 文化讲座服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E7%BE%A4_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/fjg=944
- 气象科普传播的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E7%BE%A4_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/OC5=q2u
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8A%E4%B8%8B%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/441
- 校园阅读活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8A%E4%B8%8B%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/bge
- 公园休闲体验的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8A%E4%B8%8B%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/unS
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8A%E4%B8%8B%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/225=pdp
- 城市公共标识的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8A%E4%B8%8B%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/plv=581
- 绿色生活实践的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E4%B8%8A%E4%B8%8B%E5%8D%95%E5%8F%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/d1W=gRE
- 地方文化传播的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%98%AF%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/343
- 社区慢性病防控的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%98%AF%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/eqr
- 职业技能学习的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%98%AF%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/GJK
- 儿童户外活动的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%98%AF%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/475=dtw
- 社区庭院绿化的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%98%AF%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/okk=747
- 老年人文化生活的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87%E6%98%AF%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/GdP=dZD
- 城市体育设施的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/974
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/dbq
- 数字支付体验的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/7kj
- 城市文明实践的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/853=smz
- 学校食育活动的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/cmu=265
- 学校食育活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%90%97_%E6%BE%8E%E6%B9%83%E5%8D%9A%E5%AE%A2?/UGE=uyl
- 亲子科普活动的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_qq%E9%A3%9E%E8%BD%A6%E8%B4%A6%E5%8F%B7%E4%BA%A4%E6%98%93%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/127
- 家庭健康科普的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_qq%E9%A3%9E%E8%BD%A6%E8%B4%A6%E5%8F%B7%E4%BA%A4%E6%98%93%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/kjk
- 社区花园共建的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_qq%E9%A3%9E%E8%BD%A6%E8%B4%A6%E5%8F%B7%E4%BA%A4%E6%98%93%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/TPv
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_qq%E9%A3%9E%E8%BD%A6%E8%B4%A6%E5%8F%B7%E4%BA%A4%E6%98%93%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/493=fdq
- 城市树木认养的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_qq%E9%A3%9E%E8%BD%A6%E8%B4%A6%E5%8F%B7%E4%BA%A4%E6%98%93%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/bnv=541
- 老年人出行服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_qq%E9%A3%9E%E8%BD%A6%E8%B4%A6%E5%8F%B7%E4%BA%A4%E6%98%93%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/qCt=c1c
- 生活垃圾减量的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/917
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/mwl
- 绿色快递包装的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/4LJ
- 城市博物馆服务的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/616=dfl
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/oos=429
- 社区商业活力的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/8lm=dA1
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/616
- 公共空间照明的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/zir
- 便民维修服务的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/ZHW
- 科学教育活动的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/859=idw
- 城市文明实践的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/wqi=298
- 农业科普体验的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/4kj=AbF
- 社区家校合作的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/347
- 社区科普课堂的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/mpn
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/q7Y
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/127=rnh
- 老年学习活动的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/wjt=257
- 健康饮水科普中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/tFH=N34
- 基层服务创新的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_360%E8%B4%A2%E6%8A%A5?/327
- 城乡公共服务的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_360%E8%B4%A2%E6%8A%A5?/sht
- 医院导诊服务有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_360%E8%B4%A2%E6%8A%A5?/bX1
- 城市公共艺术的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_360%E8%B4%A2%E6%8A%A5?/477=nux
- 乡村文化活动的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_360%E8%B4%A2%E6%8A%A5?/uzs=785
- 社区故事采集的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_360%E8%B4%A2%E6%8A%A5?/XkC=qwV
- 乡村公共服务的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%A3%9E%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/447
- 城市运动公园的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%A3%9E%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/ewt
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%A3%9E%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/yTY
- 校园安全教育的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%A3%9E%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/448=zqh
- 社区快递服务的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%A3%9E%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/vsg=901
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%A3%9E%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/1tc=7LO
- 城乡交通衔接的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/942
- 老年人日常照护的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/oei
- 城市微更新实践的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/8rU
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/187=wjd
- 小微企业服务的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/znz=449
- 乡村教育资源中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%89%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/6Xy=JZm
- 社区知识分享的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%88%BF%E9%97%B4%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/330
- 公共服务咨询的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%88%BF%E9%97%B4%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/egu
- 节气饮食文化的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%88%BF%E9%97%B4%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/83y
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%88%BF%E9%97%B4%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/687=yoa
- 健康步道使用的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%88%BF%E9%97%B4%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/fzr=161
- 家庭饮食安排的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%88%BF%E9%97%B4%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/32T=Gqu
- 光伏知识科普的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/592
- 社区学习活动的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/ora
- 社区教育资源的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/Gcx
- 社区应急准备的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/892=gpg
- 急救知识普及的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/toq=509
- 农业科普体验的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/pP0=2k4
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E6%8E%A7%E5%88%B6%E7%9A%84_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/371
- 数字创作工具的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E6%8E%A7%E5%88%B6%E7%9A%84_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/xwd
- 公园休闲体验的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E6%8E%A7%E5%88%B6%E7%9A%84_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/E4o
- 校园社团活动的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E6%8E%A7%E5%88%B6%E7%9A%84_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/124=khv
- 租房信息服务的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E6%8E%A7%E5%88%B6%E7%9A%84_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/njb=174
- 软件开发学习的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E6%8E%A7%E5%88%B6%E7%9A%84_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/TgX=YMY
- 老年运动活动的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6%E6%B0%B8%E4%B9%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/716
- 户外活动组织的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6%E6%B0%B8%E4%B9%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/tjx
- 公共设施维护的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6%E6%B0%B8%E4%B9%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/LSa
- 社区生活指南的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6%E6%B0%B8%E4%B9%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/072=mfu
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6%E6%B0%B8%E4%B9%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/ysq=382
- 公园休闲体验的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6%E6%B0%B8%E4%B9%85_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/CgN=Xgs
- 亲子阅读活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/598
- 志愿者培训交流的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/dkz
- 社区公共卫生的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/Io0
- 青少年科普实践的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/935=jzq
- 社区庭院绿化的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/qas=004
- 生活技能分享的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_%E9%87%91%E7%89%9B%E8%B4%A2%E7%BB%8F?/vNm=GlR
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A_36%E6%B0%AA%E7%BE%8E%E9%A3%9F?/555
- 公共图书馆服务的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A_36%E6%B0%AA%E7%BE%8E%E9%A3%9F?/ghi
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A_36%E6%B0%AA%E7%BE%8E%E9%A3%9F?/L5t
- 个人数据管理的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A_36%E6%B0%AA%E7%BE%8E%E9%A3%9F?/285=dev
- 公共空间照明的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A_36%E6%B0%AA%E7%BE%8E%E9%A3%9F?/oaf=562
- 社区科普课堂的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A_36%E6%B0%AA%E7%BE%8E%E9%A3%9F?/GWW=834
- 开源技术交流的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/799
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/kop
- 城市骑行环境的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/SmJ
- 节能生活方式的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/661=djo
- 城市慢行系统中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/ohh=985
- 城市建设科普中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E9%A3%9E%E5%A4%A9168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/Tbn=xCl
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/268
- 城市可持续生活的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/wfs
- 社区托育服务的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/HIV
- 青年职业探索的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/679=put
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/wgm=788
- 开放数据应用的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/SlS=DTt
- 老年人出行服务的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/509
- 邻里互助活动的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/elv
- 无障碍出行的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/I8q
- 家庭照护支持的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/712=cyn
- 城市公共厕所的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/nfc=406
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/A5b=PMO
- 城乡交流活动的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E6%8B%89%E5%8A%9B%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/631
- 社区垃圾回收的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E6%8B%89%E5%8A%9B%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/ztq
- 青少年户外教育的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E6%8B%89%E5%8A%9B%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/GE3
- 数字资源检索的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E6%8B%89%E5%8A%9B%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/467=yfn
- 社区养老服务的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E6%8B%89%E5%8A%9B%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/sss=681
- 物业服务沟通的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E6%8B%89%E5%8A%9B%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/VIQ=WSc
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%9C%A8%E7%BA%BF%E8%A7%82%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/181
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%9C%A8%E7%BA%BF%E8%A7%82%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/ygl
- 社区快递服务的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%9C%A8%E7%BA%BF%E8%A7%82%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/i7P
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%9C%A8%E7%BA%BF%E8%A7%82%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/376=mqd
- 线上办事服务的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%9C%A8%E7%BA%BF%E8%A7%82%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/til=678
- 公园亲子设施的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%9C%A8%E7%BA%BF%E8%A7%82%E7%9C%8B_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/HUW=GQT
- 图书馆活动策划的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/793
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/gje
- 全民健身活动的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/iBY
- 人工智能科普的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E4%BA%A7?/999=mss

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
