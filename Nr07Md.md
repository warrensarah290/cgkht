# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 社区手工活动的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_7217%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/r5n
- 社区健康讲座的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_7217%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/218=shm
- 基层健康档案的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_7217%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/exy=156
- 图书借阅体验的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_7217%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%97%B6%E6%8A%A5?/pZF=wOu
- 读书会组织的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/834
- 家庭运动计划的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/ocd
- 物业服务沟通的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/zub
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/248=trb
- 绿色快递包装的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/tka=722
- 绿色建筑理念的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/jPN=OSc
- 市民热线服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/161
- 社区活动空间的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/vbj
- 药品使用科普的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/88z
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/413=wdm
- 租房信息服务的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/cng=343
- 社区学习活动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B_%E5%BE%97%E7%89%A9%E6%B1%87%E5%B8%82?/PKw=5Eu
- 城市雨天出行的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/602
- 节约用水实践的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/rsu
- 电子商务服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/srB
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/394=rwb
- 健康步道使用的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/gcu=160
- 节约用水实践的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/JDL=mc1
- 智能家居应用的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_7217%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%88%9B%E6%8A%95?/700
- 城市公共饮水的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_7217%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%88%9B%E6%8A%95?/mdn
- 城市文明实践的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_7217%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%88%9B%E6%8A%95?/p7S
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_7217%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%88%9B%E6%8A%95?/082=kju
- 小区电梯维护的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_7217%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%88%9B%E6%8A%95?/uvy=454
- 城市文明出行的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_7217%E5%BD%A9%E7%A5%A8APP_36%E6%B0%AA%E5%88%9B%E6%8A%95?/B35=for
- 便民服务地图的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/798
- 智能手机助老的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/jzd
- 公共空间休憩的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/tfL
- 公共交通信息服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/904=vkt
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/hzr=413
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_7217%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/OWr=KCp
- 社区垃圾分类的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/747
- 户外活动组织的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/znx
- 灵活就业交流的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/Pyq
- 健康饮水科普的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/194=fto
- 地方旅游导览的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/gdi=097
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7217%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/2UF=d8w
- 社区商业活力的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A87217%E5%AE%98%E7%BD%91._%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/261
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A87217%E5%AE%98%E7%BD%91._%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/cje
- 基层健康服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A87217%E5%AE%98%E7%BD%91._%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/Wcl
- 课后服务体验的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A87217%E5%AE%98%E7%BD%91._%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/495=zik
- 消防知识宣传的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A87217%E5%AE%98%E7%BD%91._%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/nqd=722
- 药品使用科普的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A87217%E5%AE%98%E7%BD%91._%E9%9B%85%E8%99%8E%E5%9B%BE%E9%89%B4?/sMC=o6z
- 本地旅行体验的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B%5B_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/743
- 社区安全巡查的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B%5B_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/fog
- 社区公共餐饮的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B%5B_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/Smd
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B%5B_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/806=qyo
- 社区设施共享的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B%5B_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/dzi=016
- 城市绿道建设的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_7217vip%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%80%E6%9C%9F%E9%A2%84%E6%B5%8B%5B_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/9zK=BAj
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_7217vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/763
- 校园节能行动的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_7217vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/hif
- 乡村文化空间的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_7217vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/aOP
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_7217vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/309=hdx
- 社区法律科普的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_7217vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/zvh=507
- 健康饮水科普的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_7217vip%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/Xwv=Dz3
- 节约用水实践的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_7217vip%E5%BD%A9%E7%A5%A8APP_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/716
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_7217vip%E5%BD%A9%E7%A5%A8APP_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/agr
- 街道综合服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_7217vip%E5%BD%A9%E7%A5%A8APP_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/3sL
- 农产品消费体验的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_7217vip%E5%BD%A9%E7%A5%A8APP_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/532=ixe
- 亲子科普活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_7217vip%E5%BD%A9%E7%A5%A8APP_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/bwz=149
- 无障碍出行的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_7217vip%E5%BD%A9%E7%A5%A8APP_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/Lug=jjJ
- 社区休闲设施的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/214
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/vgs
- 城市微更新实践的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/PwG
- 老年人文化生活的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/812=qjw
- 科学教育活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/qhe=282
- 城市公共饮水的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/vOL=Tik
- 社区故事采集的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_800%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/496
- 数字课堂应用的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_800%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/ycy
- 老年数字阅读的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_800%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/Mqx
- 社区活动空间的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_800%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/826=kiq
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_800%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/zha=581
- 急救知识普及的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_800%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/wBW=GsR
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/527
- 公交站点体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/cdr
- 家庭环保习惯的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/5x0
- 社区修缮行动的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/659=czf
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/hph=423
- 城市生活服务的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_800%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/cAe=ihl
- 城市社区治理的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_800%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/618
- 绿色出行服务的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_800%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/mik
- 数字阅读服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_800%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/OyD
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_800%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/039=sib
- 数据分析入门的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_800%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/bye=672
- 青少年户外教育的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_800%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%BF%E5%9F%9F?/4Lw=UDb
- 社区休闲设施的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_800%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/955
- 社区交通安全的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_800%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/jlx
- 社区故事采集的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_800%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/x9y
- 街头绿植养护的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_800%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/813=idl
- 城市公共座椅中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_800%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/zjy=481
- 气象科普传播的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_800%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/Mbk=HSM
- 公共空间休憩的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_800%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/339
- 社区商业活力的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_800%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/vxo
- 公共空间休憩的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_800%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/Vgr
- 日常摄影记录的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_800%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/838=ooz
- 科学信息获取的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_800%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/vpp=155
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_800%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/9cA=UUD
- 城市基础设施的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_800%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/885
- 公共服务评价的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_800%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/yte
- 公交站点体验的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_800%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/enh
- 社区读书角建设的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_800%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/909=qep
- 健康步道使用的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_800%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/bas=611
- 数字公共文化的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_800%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/QGq=fNJ
- 社区便民集市的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/385
- 社区健康讲座的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/zuo
- 健康步道使用的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/Fkn
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/082=ijb
- 城市公共艺术的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/eyj=903
- 图书借阅体验的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/jzt=xVv
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3%5B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/881
- 电动汽车充电的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3%5B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/cog
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3%5B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/o25
- 传统节日科普的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3%5B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/853=npy
- 儿童户外活动的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3%5B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/qmc=885
- 城市公共饮水的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_800%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3%5B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/HN8=uJT
- 城市公共厕所的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/692
- 本地消费场景的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/wvs
- 城市公共厕所的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/hdG
- 网络安全教育的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/327=pce
- 职业技能学习的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/ken=221
- 家庭饮食安排的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/Qyk=Rin
- 社区防暑服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8182%E5%90%89%E5%BD%A9%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/555
- 家庭用电安全的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8182%E5%90%89%E5%BD%A9%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/vwd
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8182%E5%90%89%E5%BD%A9%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/mII
- 儿童友好街区的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8182%E5%90%89%E5%BD%A9%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/195=ptc
- 邻里互助活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8182%E5%90%89%E5%BD%A9%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/rhu=891
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8182%E5%90%89%E5%BD%A9%E7%BD%91_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/Ygc=twD
- 家庭网络使用的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/934
- 生成式工具使用的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/tgq
- 科学信息获取的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/B4k
- 应急物资管理的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/120=eqs
- 数字创作工具的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/ppk=132
- 生成式工具使用的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_8182%E5%90%89%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/pdi=jHh
- 旧物循环利用的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E6%B7%98%5B_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/465
- 城市夜间照明的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E6%B7%98%5B_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/nee
- 科学健身方法的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E6%B7%98%5B_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/T6e
- 通勤路线规划中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E6%B7%98%5B_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/923=lbo
- 数字生活课堂的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E6%B7%98%5B_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/erv=473
- 社区心理支持中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E6%B7%98%5B_%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F?/UKw=P8v
- 家庭志愿活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/621
- 城市便民驿站的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/aad
- 社区故事采集的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/bgC
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/458=nav
- 数字支付体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/eoc=560
- 社区活动策划的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/j38=2oh
- 图书借阅体验的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8welcome%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8%E5%A4%9A%E6%A0%B7_360%E8%AF%BB%E5%9B%BE?/278
- 街区更新实践的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8welcome%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8%E5%A4%9A%E6%A0%B7_360%E8%AF%BB%E5%9B%BE?/sdf
- 社区健康讲座中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8welcome%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8%E5%A4%9A%E6%A0%B7_360%E8%AF%BB%E5%9B%BE?/5wc
- 社区停车服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8welcome%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8%E5%A4%9A%E6%A0%B7_360%E8%AF%BB%E5%9B%BE?/989=lkw
- 数字政务体验的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8welcome%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8%E5%A4%9A%E6%A0%B7_360%E8%AF%BB%E5%9B%BE?/ttk=006
- 公共服务评价的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_8258%E5%BD%A9%E7%A5%A8welcome%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8%E5%A4%9A%E6%A0%B7_360%E8%AF%BB%E5%9B%BE?/vel=ihC
- 小区电梯维护的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8_360%E8%B4%A2%E7%BB%8F?/212
- 社区邻里服务的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8_360%E8%B4%A2%E7%BB%8F?/zsh
- 城市公共厕所的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8_360%E8%B4%A2%E7%BB%8F?/iWv
- 数字便民地图的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8_360%E8%B4%A2%E7%BB%8F?/353=tqf
- 街道综合服务的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8_360%E8%B4%A2%E7%BB%8F?/lsf=146
- 城市共享单车的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_8258%E5%BD%A9%E7%A5%A8_360%E8%B4%A2%E7%BB%8F?/0mt=knK
- 科学教育活动的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258vip%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/348
- 城市骑行环境的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258vip%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/ech
- 非遗课堂体验的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258vip%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/U6e
- 数字阅读服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258vip%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/067=kvi
- 基层服务创新的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258vip%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/spy=753
- 社区老年食堂的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258vip%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/ez3=Ims
- 基层健康档案中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_8258%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/236
- 乡村公共阅读的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_8258%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/dhq
- 机器人科普活动的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_8258%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/5RB
- 图书借阅体验的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_8258%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/697=nlc
- 农业科普体验的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_8258%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/rmr=992
- 公共交通信息服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_8258%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/qIM=P0r
- 公共交通接驳的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/026
- 乡村产业科普的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/tcd
- 全民阅读推广的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/R2L
- 市民意见收集的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/126=pbe
- 城市公共厕所的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/anj=105
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/vLq=jkX
- 劳动教育实践的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_360%E9%80%9F%E8%A7%88?/986
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_360%E9%80%9F%E8%A7%88?/zpt
- 社区文化节活动的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_360%E9%80%9F%E8%A7%88?/08A
- 儿童友好空间的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_360%E9%80%9F%E8%A7%88?/810=ibp
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_360%E9%80%9F%E8%A7%88?/fdd=179
- 便民服务地图的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_360%E9%80%9F%E8%A7%88?/Ugp=Xu4
- 社区活动策划的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/608
- 地方戏曲体验的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/rao
- 街区小店体验的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/FnZ
- 家庭健康管理的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/553=muw
- 居民健康教育的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/izd=657
- 社区庭院绿化的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_8258%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/vG2=F1w
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8welcome_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/434
- 乡村电商实践的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8welcome_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/kwv
- 城市人文观察的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8welcome_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/rOQ
- 社区消防演练的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8welcome_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/016=rzd
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8welcome_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/etx=692
- 应急物资管理的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8welcome_%E5%8D%B3%E5%88%BB%E6%B3%95%E5%BE%8B?/MYI=CbA
- 基层健康档案的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_8258%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/452
- 城市步行友好的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_8258%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/get
- 社区志愿服务的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_8258%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/DSi
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_8258%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/054=baa
- 乡村阅读活动的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_8258%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/jvd=846
- 开放式学习空间的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_8258%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/nXT=ARW
- 城乡公共服务中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/835
- 社区故事采集的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dmf
- 基层健康服务的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/21v
- 生活垃圾减量的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/570=cnp
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/nqt=052
- 街区道路维护的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_8258%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/yZk=HCV
- 音乐欣赏活动的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258vip%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E8%A7%A3%E5%AF%86?/569
- 社区慢性病防控的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258vip%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E8%A7%A3%E5%AF%86?/lfq
- 城市微更新实践中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258vip%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E8%A7%A3%E5%AF%86?/gI5
- 农村环境治理的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258vip%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E8%A7%A3%E5%AF%86?/048=cqo
- 公共设施维护的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258vip%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E8%A7%A3%E5%AF%86?/oga=250
- 社区防暑服务的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258vip%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95_360%E8%A7%A3%E5%AF%86?/u52=Uq8
- 社区活动报名的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8_36%E6%B0%AA%E5%9B%BD%E9%99%85?/113
- 城市基础设施的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8_36%E6%B0%AA%E5%9B%BD%E9%99%85?/bni
- 职业技能学习的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8_36%E6%B0%AA%E5%9B%BD%E9%99%85?/1Jd
- 社区健康讲座的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8_36%E6%B0%AA%E5%9B%BD%E9%99%85?/474=lkm
- 家庭饮食安排的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8_36%E6%B0%AA%E5%9B%BD%E9%99%85?/asw=698
- 户外活动组织的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_855%E5%BD%A9%E7%A5%A8%E6%BE%B3%E9%97%A8_36%E6%B0%AA%E5%9B%BD%E9%99%85?/oId=Io7
- 便民维修服务的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_855%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/478
- 家庭理财科普的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_855%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/blb
- 个人信息保护的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_855%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/18H
- 生活服务数字化的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_855%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/330=jmy
- 社区家政服务的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_855%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/dqz=429
- 地方美食文化的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_855%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/kP0=LTO
- 公共服务沟通的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_855%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/526
- 数字支付体验的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_855%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/hqj
- 科学运动指导的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_855%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/hrj
- 光伏知识科普的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_855%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/278=wov
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_855%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/zdd=458
- 网络安全教育的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_855%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/NSe=c3p
- 街区绿化养护的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/098
- 志愿服务平台的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/syr
- 社区安全巡查的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/qgQ
- 公共卫生设施的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/007=ded
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/wws=544
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%99%9A%E6%8A%A5?/ZtS=pcv
- 社区防暑服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/505
- 口袋公园建设的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/idc
- 数字艺术创作的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/Coo
- 社区便民集市的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/614=xoc
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/ecs=164
- 信息无障碍体验的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/93W=74p
- 医院导诊服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/093
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/wmf
- 城市步行环境的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/MQW
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/982=kkk
- 科学健身方法的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/sfh=709
- 志愿服务平台的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8808%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/smy=n8F

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
