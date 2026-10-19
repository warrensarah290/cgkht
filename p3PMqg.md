# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 城市公共自行车的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9028%E6%B5%8B%E8%AF%84%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/t70
- 创业经验分享的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9028%E6%B5%8B%E8%AF%84%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/774=yij
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9028%E6%B5%8B%E8%AF%84%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/jij=565
- 科学运动指导的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9028%E6%B5%8B%E8%AF%84%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/7xP=hIF
- 乡村产业科普的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51_%E9%9B%85%E8%99%8E%E6%B1%87%E5%B8%82?/893
- 居民健康教育的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51_%E9%9B%85%E8%99%8E%E6%B1%87%E5%B8%82?/fwx
- 农贸市场环境中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51_%E9%9B%85%E8%99%8E%E6%B1%87%E5%B8%82?/cDS
- 社区互助网络的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51_%E9%9B%85%E8%99%8E%E6%B1%87%E5%B8%82?/678=weo
- 本地消费场景的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51_%E9%9B%85%E8%99%8E%E6%B1%87%E5%B8%82?/udu=029
- 城乡交通衔接的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51_%E9%9B%85%E8%99%8E%E6%B1%87%E5%B8%82?/pdo=lPT
- 社区设施共享的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/391
- 远程协作工具的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/obj
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/77v
- 家庭消费规划的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/265=vio
- 社区教育资源的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/zjz=866
- 公益活动组织的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E6%89%91%E6%88%BF%E4%BA%A7?/5BF=kxG
- 城市公共自行车的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/849
- 城市文明出行的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/lxb
- 社区环保活动的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/Qis
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/018=kzq
- 家庭环保行动的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/tqs=517
- 志愿服务平台的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/IEu=RGz
- 开放数据应用的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/710
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/rcv
- 开源技术交流的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/64Z
- 生活垃圾减量的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/826=hwx
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/bht=721
- 公共健身器材的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/DDq=aq9
- 城市可持续生活的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/397
- 社区垃圾分类的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/kfp
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/7F0
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/413=tuk
- 家庭环保行动的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/zdf=915
- 公共服务指南的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/3d4=Bns
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/660
- 通勤路线规划的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/gzv
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/fru
- 健康饮食教育的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/751=bbh
- 数字地图应用的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/rgn=944
- 户外活动组织的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/njh=ii9
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/387
- 创业经验分享的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/kdj
- 环境教育课程的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/12z
- 城市农夫市集的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/823=wzm
- 文化场馆预约的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/xoi=675
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/vff=db3
- 个人时间管理的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/187
- 公共场所导视的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/kug
- 街区绿化养护中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/v6w
- 城市步行友好的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/745=qtn
- 公共文化活动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/yck=759
- 社区阅读服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/kac=bla
- 家庭运动计划的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/521
- 消防知识宣传中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/dbs
- 老年友好服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/jvt
- 远程协作工具的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/692=laa
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/plr=337
- 城市微更新实践的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/eO2=q29
- 公共设施使用的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/859
- 乡村公共文化中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/vat
- 校园阅读活动的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/t0Q
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/031=lhg
- 科普展览体验的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/srr=191
- 便民信息查询的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/wv1=Ggz
- 开放式学习空间的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/370
- 城市可持续生活的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/zwa
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/22Q
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/445=kjf
- 数据分析入门的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/bsz=035
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88_36%E6%B0%AA%E6%94%BF%E5%8D%8F?/Fym=yNa
- 新能源知识普及的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/023
- 志愿服务平台的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/ewd
- 家庭园艺实践的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/PMe
- 文明养宠科普的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/459=mvy
- 口袋公园建设的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/ajd=107
- 数字阅读服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%AE%BF%E8%B0%88?/ml5=LVu
- 急救知识普及的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/035
- 居家防滑改造的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/hpr
- 城市建设科普的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/09e
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/212=nxo
- 文化场馆预约的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/opu=939
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/Iwq=LgV
- 社区艺术活动的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/554
- 骑行路线规划的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/sih
- 社区邻里服务的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/Fyx
- 儿童户外活动的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/031=acj
- 绿色出行服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/gvt=486
- 社区信息发布的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/LfC=GYQ
- 新能源出行的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/629
- 公园亲子设施的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/jte
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/Jqp
- 科学健身方法的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/650=eud
- 社区公共卫生的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/yjm=457
- 青少年心理健康的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/R4r=yar
- 智能手机助老的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/282
- 家庭节能实践的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/uun
- 家庭健康科普的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/27k
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/823=pds
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/ktv=426
- 农贸市场环境的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BF%B0%E8%AF%84?/2bo=mx8
- 城市游园体验的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/627
- 校园节能行动的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/tts
- 城市展览体验的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/XHt
- 城市骑行环境的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/214=uoq
- 街道综合服务的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/bjt=502
- 基层服务创新的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/Gp3=6ie
- 社区儿童活动的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E6%B5%8B%E7%BD%9128_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/134
- 志愿者培训交流的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E6%B5%8B%E7%BD%9128_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/gez
- 食品配送体验的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E6%B5%8B%E7%BD%9128_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/STg
- 社区体育组织的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E6%B5%8B%E7%BD%9128_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/018=mki
- 生活技能分享的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E6%B5%8B%E7%BD%9128_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/arc=290
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E6%B5%8B%E7%BD%9128_%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/sj7=fCh
- 公共场所导视的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_pc%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%9699%E9%A2%84%E6%B5%8B_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/172
- 公共场所导视的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_pc%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%9699%E9%A2%84%E6%B5%8B_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/tvk
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_pc%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%9699%E9%A2%84%E6%B5%8B_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/3jk
- 智慧城市体验的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_pc%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%9699%E9%A2%84%E6%B5%8B_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/178=wdq
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_pc%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%9699%E9%A2%84%E6%B5%8B_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/qyv=875
- 城市文明出行的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_pc%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%9699%E9%A2%84%E6%B5%8B_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/ijL=yET
- 公共空间照明的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/384
- 乡村公共服务的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/eqz
- 城市步行友好的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/svu
- 节日文化体验的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/374=bwu
- 青少年户外教育的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/byk=991
- 公共服务预约的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/g9l=p6m
- 社区菜市场服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8A%A0%E6%8B%BF%E5%A4%A7100%25%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/656
- 家庭用电安全的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8A%A0%E6%8B%BF%E5%A4%A7100%25%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/wis
- 本地历史资料的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8A%A0%E6%8B%BF%E5%A4%A7100%25%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/UNg
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8A%A0%E6%8B%BF%E5%A4%A7100%25%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/868=hil
- 通勤路线规划的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8A%A0%E6%8B%BF%E5%A4%A7100%25%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/hua=068
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8A%A0%E6%8B%BF%E5%A4%A7100%25%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/5uj=Zbl
- 社区生活指南的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_pc28%E5%A4%A7%E7%A5%9E%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/504
- 城市农夫市集的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_pc28%E5%A4%A7%E7%A5%9E%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/ocd
- 儿童友好空间的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_pc28%E5%A4%A7%E7%A5%9E%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/Yex
- 社区垃圾分类的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_pc28%E5%A4%A7%E7%A5%9E%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/579=gyj
- 社区健康讲座的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_pc28%E5%A4%A7%E7%A5%9E%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/gtx=685
- 城市可持续生活的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_pc28%E5%A4%A7%E7%A5%9E%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/MMW=kBl
- 社区信息发布的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B%E7%BD%91PC%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/251
- 公共服务沟通的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B%E7%BD%91PC%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/nzn
- 公共服务指南的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B%E7%BD%91PC%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/kPj
- 志愿服务平台的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B%E7%BD%91PC%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/439=ept
- 基层健康档案的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B%E7%BD%91PC%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/bfu=562
- 社区环保活动的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B%E7%BD%91PC%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/b66=VHz
- 网络信息辨识的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%AF%94%E7%89%B92.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/335
- 生活垃圾回收的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%AF%94%E7%89%B92.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/ykt
- 家庭消费规划的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%AF%94%E7%89%B92.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/TrH
- 非遗体验活动的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%AF%94%E7%89%B92.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/066=ptd
- 家庭理财科普的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%AF%94%E7%89%B92.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/fmi=927
- 社区健康讲座的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%AF%94%E7%89%B92.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/s1y=CAS
- 社区快递服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/426
- 社区健康讲座的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/etz
- 周末休闲规划的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/T2i
- 儿童友好空间的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/209=khu
- 邻里互助活动的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/fdj=061
- 开放数据应用的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/V3a=7hJ
- 公共空间休憩的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/566
- 物业服务沟通的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/qei
- 网络安全教育的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/Ey9
- 街区小店体验中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/633=qjx
- 社区科普课堂的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/ckb=974
- 城市农夫市集的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%AF%94%E7%89%B928%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/OG5=MWD
- 城乡公共服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928.2.0%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/369
- 城市人文观察的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928.2.0%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/div
- 药品使用科普的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928.2.0%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/Jqk
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928.2.0%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/955=zdd
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928.2.0%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/tnl=258
- 城市可持续生活的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928.2.0%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/bpe=mPB
- 家庭网络使用的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E9%97%AE%E9%BC%8Ewd28%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/574
- 乡村公共文化的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E9%97%AE%E9%BC%8Ewd28%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/anq
- 环境监测科普的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E9%97%AE%E9%BC%8Ewd28%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/iaX
- 社区手工活动的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E9%97%AE%E9%BC%8Ewd28%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/181=wwb
- 社区养老服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E9%97%AE%E9%BC%8Ewd28%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/obg=956
- 城市雨天出行的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E9%97%AE%E9%BC%8Ewd28%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/xre=euh
- 社区信息发布的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928-2.0%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/585
- 城市微更新实践的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928-2.0%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/llb
- 城市公共厕所的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928-2.0%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/yX6
- 公共设施维护的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928-2.0%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/151=urh
- 数字创作工具的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928-2.0%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/bfc=674
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928-2.0%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/fAH=29N
- 低碳社区实践的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%28%E9%9D%9E%E5%B8%B8%E5%87%86%29_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/494
- 公共健身器材的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%28%E9%9D%9E%E5%B8%B8%E5%87%86%29_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/klq
- 在线教育体验的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%28%E9%9D%9E%E5%B8%B8%E5%87%86%29_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/mkS
- 城市文明出行的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%28%E9%9D%9E%E5%B8%B8%E5%87%86%29_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/464=jgc
- 公共图书馆服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%28%E9%9D%9E%E5%B8%B8%E5%87%86%29_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/xjv=004
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%28%E9%9D%9E%E5%B8%B8%E5%87%86%29_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/Drk=ro5
- 邻里互助活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/862
- 家庭科学教育的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/dzz
- 文明养宠科普的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/AIw
- 儿童友好街区的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/456=tso
- 老年人出行服务的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/xog=501
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/Ba1=GQU
- 街区绿化养护的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%AF%94%E7%89%B92.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/191
- 基层健康服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%AF%94%E7%89%B92.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/cbc
- 社区公共餐饮的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%AF%94%E7%89%B92.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/ZNR
- 健康饮水科普的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%AF%94%E7%89%B92.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/781=abu
- 节约用水实践的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%AF%94%E7%89%B92.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/ybc=850
- 青少年编程学习的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%AF%94%E7%89%B92.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/FN3=7a2
- 乡村文化活动的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%AF%94%E7%89%B928%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/864
- 社区科普课堂的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%AF%94%E7%89%B928%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/oal
- 地方文化传播的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%AF%94%E7%89%B928%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/Rfy
- 家庭用电安全的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%AF%94%E7%89%B928%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/534=age
- 创业经验分享的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%AF%94%E7%89%B928%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/yen=886
- 基层医疗预约的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E6%AF%94%E7%89%B928%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/vMA=fGV
- 职业技能学习的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928-2.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/958
- 城市建设科普的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928-2.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/xub
- 社区环保活动的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928-2.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/AGt
- 社区商业活力的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928-2.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/679=nrg
- 数字公共文化的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928-2.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/kzp=061
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%AF%94%E7%89%B928-2.8%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/LKC=mE1
- 城市公共自行车的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/614
- 老年人文化生活的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ygu
- 开放数据应用的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/dJF
- 地方文化传播的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/876=guc
- 社区修缮行动的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/kis=056
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/i3u=5fe
- 家庭环保习惯的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/139
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/pmp
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/3Ms
- 开源技术交流的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/362=dfo
- 社区商业活力的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/qvy=236
- 社区故事采集的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%AF%94%E7%89%B928%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%AE%BF%E8%B0%88?/WWA=jzN
- 城市树木认养的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-3.2%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/639
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-3.2%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/cnz
- 邻里共享空间的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-3.2%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/UmA
- 数字阅读服务的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-3.2%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/735=qwp
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-3.2%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/lmo=144
- 绿色生活实践的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928-3.2%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/k3G=9hP
- 乡村文化空间中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_360%E5%9F%8E%E4%BA%8B?/049
- 家庭网络使用的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_360%E5%9F%8E%E4%BA%8B?/tlp
- 安全出行教育的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_360%E5%9F%8E%E4%BA%8B?/VzB
- 儿童友好空间的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_360%E5%9F%8E%E4%BA%8B?/832=foo
- 公共服务预约的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_360%E5%9F%8E%E4%BA%8B?/ugz=100
- 志愿者培训交流的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AF%94%E7%89%B928%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_360%E5%9F%8E%E4%BA%8B?/S0R=U39
- 数字学习资源的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AF%94%E7%89%B928cc_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/939
- 城市生活服务的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AF%94%E7%89%B928cc_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/xjv
- 儿童阅读角的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AF%94%E7%89%B928cc_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/HnK
- 数字艺术创作的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AF%94%E7%89%B928cc_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/633=htp
- 家庭健康管理的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AF%94%E7%89%B928cc_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/kfq=350
- 家庭食品保存的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E6%AF%94%E7%89%B928cc_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/M4R=Ex1
- 公交站点体验的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/959
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/lbm
- 城市文化路线的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/He6
- 在线教育体验的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/109=ldz
- 乡村教育资源的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/zwo=694
- 在线学习体验的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/btb=0kI
- 社区体育组织的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928-2.8_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/955
- 健康饮水科普的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928-2.8_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/tql
- 老年人出行服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928-2.8_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/OA2
- 绿色出行服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928-2.8_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/811=kal
- 便民信息查询的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928-2.8_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/spc=259
- 无障碍出行的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AF%94%E7%89%B928-2.8_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/IdC=FYI

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
