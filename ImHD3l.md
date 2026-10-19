# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 职业技能学习的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/Xmx
- 家庭急救准备的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/769=qcg
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/brg=152
- 节假日出行安排的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/S5h=Gft
- 传统节日科普的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/164
- 公共服务沟通的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/hgi
- 科学观察活动的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/QCK
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/065=seg
- 软件开发学习的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/mca=422
- 社区公共卫生的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/HJi=b1v
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/318
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/bzn
- 家庭健康科普的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/Pjd
- 社区互助网络的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/226=lvi
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/coz=118
- 线上办事服务的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/bSM=YZQ
- 城市建设科普的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/185
- 城市绿色交通的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/uqj
- 智能家居应用的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/bad
- 网络信息辨识的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/170=wvi
- 科学教育活动的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/qmu=101
- 周末休闲规划的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/XWj=CBB
- 全民健身活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/204
- 社区快递服务的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/eik
- 社区体育组织的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/sY4
- 老年学习活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/701=aqv
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/bno=660
- 城市博物馆服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/ojN=lgk
- 医院导诊服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/365
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/hbg
- 小区公共照明的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/6t4
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/036=wjl
- 乡村电商实践的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/phv=900
- 城市生活记录的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/7kS=dcB
- 线上办事服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/951
- 节日文化体验的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/pyl
- 儿童阅读角的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/yYe
- 地方文化传播的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/860=fhd
- 食品安全科普的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/jsb=296
- 城市噪声观察的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/bsD=jOi
- 低碳社区实践的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/942
- 城市噪声观察的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/qlj
- 社区信息发布的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/G99
- 社区应急准备的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/544=bwm
- 老年数字阅读的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/cyo=251
- 线上办事服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/pSH=LOO
- 急救知识普及的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/930
- 青少年科普实践的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/bcf
- 应急物资管理的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/NCu
- 数字支付体验的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/888=reo
- 地方旅游导览的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/ebw=712
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/W2R=gzj
- 社区休闲设施的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/328
- 数字课堂应用的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/nmp
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/g55
- 城市游园体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/906=zbi
- 城市夜间照明的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/mar=114
- 家庭健康管理的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/sl1=oLy
- 城市文明出行的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/469
- 乡村教育资源的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/utd
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/anU
- 食品安全科普的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/077=law
- 跨代沟通活动的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/bcv=564
- 城市公共空间的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/nua=pVZ
- 节能生活方式的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/832
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/ozs
- 便民服务地图的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/Ziq
- 地方美食文化中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/378=odc
- 环境监测科普的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/gna=363
- 校园阅读活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/2GW=75C
- 科学教育活动的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/409
- 读书会组织的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/wmq
- 数字公共文化的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/n41
- 家庭环保习惯的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/603=isa
- 家庭环保习惯的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/iuk=501
- 小微企业服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/PG4=er5
- 绿色出行服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/451
- 城市运动公园的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/hrd
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/huC
- 街区绿化养护中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/149=bqr
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/eeu=346
- 社区设施共享的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/E9k=SDR
- 本地旅行体验的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/853
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/yor
- 公共服务沟通的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/tMQ
- 小微企业服务的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/216=pkc
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/ksh=408
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/2UY=wPM
- 社区活动策划的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/278
- 社区教育资源的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/cfh
- 乡村生活观察的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/9Hv
- 城市水环境观察的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/457=zym
- 城市绿色交通的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/xbi=924
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/vzH=iuB
- 城市基础设施的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/518
- 社区托育服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/aoc
- 应急物资管理的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/Ki7
- 城市展览体验的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/981=dct
- 公园休闲体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/sgr=364
- 社区科普课堂的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/t1N=A9f
- 数字支付体验的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/482
- 智慧城市体验的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/zel
- 社区文化节活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/XU0
- 公共场馆服务的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/148=iwj
- 节能家电使用的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/hjo=450
- 文化场馆预约的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/JOE=Kjm
- 城市社区治理的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/346
- 机器人科普活动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/ily
- 家庭阅读计划的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/ZxJ
- 乡村公共文化的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/838=ybb
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/nax=787
- 骑行路线规划的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/J6I=geM
- 无障碍出行的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/524
- 城市生活记录的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/xav
- 校园安全教育的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/GYD
- 公共卫生设施的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/125=eda
- 公交站点体验的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/vnq=337
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/8Qn=7Xp
- 市民意见收集的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/162
- 社区公共卫生的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/xwa
- 非遗体验活动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/76i
- 开放式学习空间的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/037=obb
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/ecv=824
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/Udy=Fq6
- 数字资源检索的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/328
- 城市文化路线的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/dee
- 老年学习活动的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/dhg
- 社区垃圾回收的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/867=hbu
- 公共场所导视的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/yma=833
- 图书借阅体验的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/iLT=Lkl
- 智慧停车服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/122
- 地方旅游导览的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/bft
- 农业科普体验的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/7FS
- 全民健身活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/675=hkf
- 软件开发学习的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/qlh=829
- 数字创作工具的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E6%96%B0%E6%B5%AA%E7%9E%AD%E6%9C%9B?/uET=AFj
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/610
- 城市便民驿站的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/fqk
- 乡村产业科普的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/nNd
- 社区体育组织中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/521=ded
- 乡村生态旅游的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/nos=404
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/C80=EdI
- 社区体育组织的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_360%E5%9B%BE%E9%9B%86?/942
- 通勤路线规划的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_360%E5%9B%BE%E9%9B%86?/dqm
- 网络信息辨识的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_360%E5%9B%BE%E9%9B%86?/xcU
- 城市文明实践的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_360%E5%9B%BE%E9%9B%86?/590=wfd
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_360%E5%9B%BE%E9%9B%86?/xuz=616
- 农村环境治理的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_360%E5%9B%BE%E9%9B%86?/uph=t0E
- 便民服务窗口的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/195
- 老年友好服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/cba
- 课后服务体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/S43
- 城市公共艺术的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/038=ywj
- 儿童友好空间的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/plr=269
- 城市公共座椅的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/9T8=vMG
- 城市慢行系统的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/631
- 数据分析入门的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/vei
- 个人信息保护的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/0Jl
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/085=kjv
- 应急物资管理的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/rss=663
- 老年人文化生活的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/jMB=DzQ
- 数字学习资源的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/503
- 家庭志愿活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/aoy
- 社区设施共享的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/VAH
- 城市公共标识的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/746=fbc
- 信息无障碍体验的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/qfv=125
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/7bO=SVI
- 数字生活课堂的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/524
- 社会体育指导的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/cyb
- 城市公共标识的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/LBf
- 休闲运动入门的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/493=skq
- 旧物循环利用的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/rsg=753
- 科技馆参观体验的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/3em=mvc
- 社区消防演练的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/452
- 社区交通安全的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/lbq
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/Olm
- 城市应急广播的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/824=sdr
- 社区科普课堂中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/evt=992
- 城市休闲步道的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/tcs=86Q
- 健康饮水科普的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/648
- 社区便利生活的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/keg
- 公益活动组织的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/Gzl
- 家庭教育交流的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/091=brg
- 数字素养提升的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/vsr=587
- 城市夜间照明的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/Ant=4Nl
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/318
- 公共设施维护的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/skx
- 城市建设科普的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/LUH
- 城市雨天出行的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/633=odz
- 图书馆活动策划的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/jaj=002
- 街区小店体验的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/IkO=ZGT
- 物业服务沟通的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/716
- 数字课堂应用的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/lcx
- 城市文明实践的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/YJZ
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/845=dvm
- 社区便利生活的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/vix=870
- 线上阅读资源的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/by1=zTM
- 城乡交流活动的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/654
- 城市步行环境的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/yoi
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/ZEP
- 街区绿化养护的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/252=nny
- 在线教育体验的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/lgk=814
- 社区商业活力的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/Y3i=Ol1
- 节约用水实践的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/181
- 城市文明出行的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/rne
- 社区休闲设施的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/cLc
- 个人数据管理的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/154=inx
- 本地旅行体验的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/lcx=556
- 青年志愿活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/vET=pvm
- 公交站点体验的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/811
- 数字艺术创作的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/nzg
- 城市农夫市集的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/UHg
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/800=khr
- 社区宠物管理的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/npx=970
- 社区养老服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/Ee1=0c0
- 科普展览体验的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/104
- 全民健身活动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/fdr
- 休闲运动入门的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/57Q
- 城市水环境观察的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/094=rjw
- 乡村文化空间的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/nfm=455
- 公共卫生宣传的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/oGl=GXb
- 社会体育指导的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/659
- 智能手机助老的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/pzz
- 社区活动空间的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/tAe
- 城市便民驿站的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/640=dci
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/sww=682
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/7NH=Na8
- 社区垃圾回收的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/166
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/asf
- 城市社区治理的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/Di9
- 城市雨天出行的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/434=fpd
- 街区更新实践的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/ucc=850
- 城市绿色交通的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/ths=BQr
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/845
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/bnj
- 街区小店体验的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/SSl
- 城市公共厕所的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/494=htd
- 社区垃圾回收的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/yfx=072
- 老年智能设备的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/MKf=Efn
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/589
- 数字档案服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/nmj
- 校园节能行动的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/C8B
- 老旧小区改造的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/922=bzk
- 街区小店体验的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/dwp=646
- 公共设施维护的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/VUh=j7S
- 社区教育资源的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/390
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/neo
- 社区垃圾分类的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/I2L
- 本地历史资料中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/493=msd
- 青少年科普实践的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/rav=554
- 居家适老化改造的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/BrI=Izk

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
