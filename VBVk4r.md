# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 医院导诊服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/vbw=615
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/fR4=K2U
- 城市夜间生活的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/122
- 社区读书角建设的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/ukh
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/3X4
- 节能生活方式的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/904=lah
- 信息无障碍体验的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/ehr=246
- 社区读书角建设的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/4YM=01f
- 环境教育课程的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/568
- 社区文化传播的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/oqs
- 食品配送体验的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/5j8
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/242=vql
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/qjh=821
- 社区文化节活动的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/jDX=ZaH
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/793
- 公共服务沟通的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/kqj
- 公共服务数字化的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/VNf
- 公共文化活动的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/443=bjf
- 邻里共享空间的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/qkf=350
- 校园安全教育的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/MgQ=Gr0
- 消防知识宣传的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/940
- 数字支付体验的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/jyt
- 家庭健康科普的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/dDc
- 公共空间安全的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/947=vsq
- 职业技能学习的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/rnz=703
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/lmB=pnS
- 智能手机助老的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89?/759
- 市民热线服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89?/amz
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89?/y9D
- 城市基础设施的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89?/098=srw
- 社区公共卫生的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89?/uim=364
- 城市骑行环境的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89?/FJb=WUp
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/042
- 社区设施共享的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/oet
- 儿童阅读角的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/l2Z
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/683=njd
- 物业服务沟通的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/cbq=165
- 社区互助网络的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/DPg=OG2
- 劳动教育实践的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/480
- 家庭网络使用的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/srd
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/asj
- 节假日出行安排的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/516=ktv
- 无障碍出行的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/mkt=326
- 读书会组织的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/ksP=GFr
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/733
- 小微企业服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/ezn
- 城市微更新实践的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/cBA
- 城市文明出行的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/767=wqf
- 社区协商议事的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/bml=083
- 数字阅读服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/n9e=2Ia
- 社区菜市场服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/656
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/gci
- 社区停车服务中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/ldB
- 便民维修服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/988=mtl
- 绿色快递包装的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/ocy=429
- 市民热线服务的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/nIg=d29
- 家庭消费规划的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/314
- 食品安全科普的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/mib
- 城市树木认养的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/00O
- 非遗体验活动的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/016=lyv
- 家庭健康管理的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/mbg=204
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/U7j=fsg
- 儿童运动体验的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/510
- 新能源出行的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/bzk
- 城市文明实践的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/hMx
- 城市步行环境中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/244=syr
- 城市文化路线的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/ulm=917
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/3Tv=j0z
- 开源技术交流的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/647
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/mog
- 健康信息获取的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/RqO
- 租房信息服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/786=cyx
- 农村环境治理的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/jwd=661
- 公共服务咨询的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/ncR=63h
- 非遗课堂体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/272
- 城市生活服务的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/yji
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/uR1
- 日常摄影记录中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/636=ajp
- 休闲运动入门的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/dpl=143
- 社区阅读服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/SrU=bxu
- 公共空间休憩的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/777
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/wad
- 公交站点体验的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/wrV
- 新能源出行的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/029=yyg
- 乡村文化活动的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/ano=405
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/cXe=BLA
- 社区便民服务的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/568
- 乡村教育资源的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/sna
- 课后服务体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/cQp
- 家庭节能实践的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/810=cft
- 社区环保活动的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/vzd=573
- 邻里共享空间的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/2WT=ipJ
- 数字课堂应用的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/301
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/vae
- 青少年编程学习的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/ooP
- 城市骑行环境的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/831=omp
- 生活垃圾回收的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/otc=656
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E7%BA%AA%E5%AE%9E?/2iZ=QmJ
- 户外活动组织的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/412
- 农贸市场环境的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/qhf
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/zOQ
- 社区健康讲座的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/106=epk
- 街区道路维护的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/ujj=871
- 社区公共卫生的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/vz5=N3w
- 数字资源检索的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/775
- 节日文化体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/gvd
- 数据分析入门中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/z3U
- 家庭健康管理的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/772=ccd
- 数字艺术创作的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/vng=017
- 终身学习资源的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/v6W=tuF
- 地方民俗记录的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/736
- 安全出行教育的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/omc
- 职业技能学习的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/Xiq
- 网络安全教育中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/806=rmx
- 机器人科普活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/hnk=517
- 数字地图应用的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/XAj=dKf
- 环境监测科普的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/881
- 创业经验分享的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/xto
- 社区活动报名的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/4kt
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/315=tdp
- 开放数据应用的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/ris=497
- 传统手工艺体验的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%9E%AD%E6%9C%9B?/hEt=YVR
- 公共服务评价的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/726
- 城市文化路线的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/sir
- 城乡公共服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/mwM
- 社区共享书架的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/722=tuk
- 社区法律科普的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/loo=844
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/xJJ=49m
- 老年数字阅读的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/796
- 社区垃圾回收的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/uqx
- 科学观察活动的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/lP0
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/443=cuj
- 家庭理财科普的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/vzl=772
- 文化讲座服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/AGI=DEj
- 校园安全教育的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/578
- 家庭园艺实践的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/rbx
- 健康饮食教育中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/tnl
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/737=smz
- 社区文化节活动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/rrh=298
- 乡村文化空间中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/BJI=wow
- 老年人文化生活的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/776
- 家庭健康管理的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/vdx
- 电动汽车充电的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/rRG
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/037=pvg
- 乡村电商实践的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/zqy=153
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/mv8=lAs
- 社区读书角建设的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/184
- 公共场馆服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/lmg
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/SW0
- 图书借阅体验的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/387=qkj
- 气象科普传播的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/yiw=058
- 城市公共标识的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/gtB=B0w
- 城市文明实践的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/620
- 乡村文化空间的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/jhk
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/8A9
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/196=cvp
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/wnu=826
- 数字地图应用的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/Biw=NA0
- 市民热线服务的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/273
- 社区共享书架的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/yyj
- 绿色办公实践的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/D9P
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/165=peq
- 社区知识分享的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/okr=307
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/SNE=X0v
- 市民意见收集的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/040
- 城市公共自行车的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/yxb
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/kEj
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/454=smi
- 青少年科普实践的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/cji=225
- 开放式学习空间的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%94%90%E8%AF%84?/sTT=nPa
- 文化讲座服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/721
- 城市住房服务的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/zpu
- 青年志愿活动的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/GjD
- 农村环境治理的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/092=vxx
- 开放式学习空间的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/csk=898
- 小区公共照明的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/NyQ=Sj9
- 公共服务咨询的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97?/518
- 文化讲座服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97?/ymt
- 药品使用科普的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97?/UBx
- 老年智能设备的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97?/946=rae
- 志愿服务平台的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97?/hgp=916
- 儿童安全出行中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E6%90%9C%E7%8B%97?/EnX=voD
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/233
- 公共空间休憩的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/sod
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/JjC
- 节能生活方式的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/518=lll
- 城市可持续生活的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/wxi=974
- 环境监测科普的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/JZn=3jZ
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/747
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/vyl
- 老年人日常照护的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/VgG
- 老年友好服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/359=pft
- 全民健身活动的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/diw=066
- 物业服务沟通的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/qYJ=oOG
- 口袋公园建设的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/374
- 智慧城市体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/ayg
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/KoS
- 社区法律科普的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/079=xsz
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/iny=193
- 社区交通安全的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/OjR=rDG
- 文化场馆预约的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/417
- 数字创作工具的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/jgp
- 社区老年食堂的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/3bg
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/201=pik
- 社区菜市场服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/enx=515
- 在线教育体验的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/50a=ejy
- 乡村教育资源的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/017
- 公共图书馆服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/dsd
- 软件开发学习的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/Aub
- 数字创作工具的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/026=ahg
- 邻里互助活动的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/les=029
- 科学运动指导的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/Q3T=txZ
- 日常摄影记录的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/814
- 老年人出行服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/lok
- 地方文化传播的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/tjT
- 公共服务指南的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/851=kem
- 线上阅读资源的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/eeg=439
- 社区家校合作的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/a6L=o1u
- 本地历史资料的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/557
- 生成式工具使用的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/lry
- 开放数据应用的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/B6z
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/359=nrj
- 急救知识普及的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/xko=960
- 新能源出行的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/n0e=byf
- 城市夜间照明的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/074
- 职业技能学习的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/pgh
- 家庭收纳实践的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/0IC
- 职业技能学习的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/133=xps
- 城市步行友好的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/wwy=181
- 校园社团活动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/Mmh=w4o
- 社区健康讲座的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/557
- 智慧停车服务的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/uat
- 地方旅游导览的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/RPV
- 学校食育活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/459=avw
- 网络安全教育的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/xwg=108
- 智能手机助老的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/S79=MFe
- 社区生活指南的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/839
- 老年人出行服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/wnn
- 食品安全科普的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/Hu0
- 社区花园共建的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/604=lpx
- 社区家校合作的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/uvd=033
- 城市便民驿站的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/r1f=HRn
- 老年人日常照护的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/437
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/bpv
- 校园节能行动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/puv
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/695=ohi
- 家庭阅读计划的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/ekq=518
- 图书馆数字服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/Rmu=JZp
- 社区儿童活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/434
- 老年人文化生活的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/qun

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
