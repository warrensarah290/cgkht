# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 公交站点体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_978cc-%E5%AE%98%E6%96%B9app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/642
- 城市公共厕所的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_978cc-%E5%AE%98%E6%96%B9app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/olo
- 城市便民驿站的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_978cc-%E5%AE%98%E6%96%B9app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/pDo
- 城乡交流活动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_978cc-%E5%AE%98%E6%96%B9app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/745=iwb
- 社区便民集市的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_978cc-%E5%AE%98%E6%96%B9app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/iqk=977
- 骑行路线规划的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_978cc-%E5%AE%98%E6%96%B9app_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/QHv=ABF
- 绿色出行服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_978cc-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/474
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_978cc-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/gxt
- 社区休闲设施的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_978cc-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/0D9
- 传统手工艺体验的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_978cc-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/138=kdp
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_978cc-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/wly=506
- 地方文化传播的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_978cc-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/7lT=Ijr
- 节气饮食文化的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/960
- 社区体育组织的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/gid
- 乡村文化空间的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/WaD
- 智能手机助老的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/738=lkz
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/nxw=377
- 家庭安全提示的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E8%AF%BB%E4%B9%A6?/YxU=dp1
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/080
- 社区托育服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/xvt
- 城市运动公园的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/QXl
- 家庭急救准备的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/836=ogz
- 小区停车协商的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/qkt=707
- 周末休闲规划的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/tS2=bbu
- 街区道路维护的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_978cc-APP_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/300
- 市民意见收集的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_978cc-APP_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/ini
- 社区休闲设施的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_978cc-APP_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/xg1
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_978cc-APP_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/343=mrm
- 创业经验分享的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_978cc-APP_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/ssd=862
- 乡村文化空间的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_978cc-APP_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/bb0=FK9
- 灵活就业交流的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_978cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/075
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_978cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/dsy
- 社区共享书架的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_978cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/H6T
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_978cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/858=ufm
- 老年运动活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_978cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/sxd=686
- 社区休闲设施的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_978cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/BhE=nc4
- 社区阅读服务的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_978cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/822
- 城市公共标识的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_978cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/ycv
- 公共服务沟通的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_978cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/kul
- 社区信息发布中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_978cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/687=joo
- 骑行路线规划的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_978cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/wsn=340
- 志愿者培训交流的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_978cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BD%93%E8%82%B2?/knA=SVc
- 社区垃圾回收的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/688
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/gwd
- 社区应急准备的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/VNU
- 社区体育组织的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/180=bek
- 社区公共餐饮的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/dfy=591
- 社区防暑服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_978cc-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/qP6=a4b
- 低碳社区实践的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_978cc-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/917
- 小微企业服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_978cc-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/dqw
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_978cc-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/Pgu
- 图书馆亲子空间的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_978cc-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/092=zds
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_978cc-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/bxo=818
- 家庭园艺实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_978cc-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/20q=rVl
- 本地历史资料的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/309
- 数字生活课堂的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/bpk
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/pV7
- 城市公共标识的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/165=kio
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/xwz=797
- 节能家电使用的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/w77=pEu
- 城市慢行系统的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_978cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/893
- 校园社团活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_978cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/gue
- 线上办事服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_978cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/r8v
- 社区应急准备的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_978cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/429=ghg
- 生活垃圾减量的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_978cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xry=279
- 数字阅读服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_978cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/El5=YFn
- 电子商务服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_978cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/953
- 远程协作工具的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_978cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/rsu
- 数字资源检索的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_978cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/5bf
- 青少年科普实践的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_978cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/346=gwc
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_978cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/odu=579
- 老年人文化生活的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_978cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/oH2=UiS
- 公共卫生设施的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_978cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/458
- 城市公共艺术的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_978cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/elw
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_978cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/JJn
- 文化讲座服务中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_978cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/404=omt
- 社区老年食堂的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_978cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/dnr=166
- 家庭节能实践的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_978cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/7Rp=Erp
- 乡村阅读空间的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_978cc-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/531
- 节能家电使用的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_978cc-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/psj
- 城乡交通衔接的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_978cc-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/Lkg
- 城市适老服务的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_978cc-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/675=emc
- 公益活动组织的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_978cc-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/cql=914
- 骑行路线规划的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_978cc-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/YdD=c13
- 生成式工具使用的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_978cc-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/495
- 城市公共自行车的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_978cc-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/dgh
- 社区学习活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_978cc-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/8f3
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_978cc-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/718=wda
- 基层服务创新的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_978cc-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/jes=209
- 音乐欣赏活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_978cc-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/KCP=dUz
- 公共服务咨询的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/343
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/nnx
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/MCF
- 公共服务咨询的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/460=aqx
- 乡村文化空间的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/hup=091
- 数字艺术创作的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/aoQ=1Gp
- 青年职业探索的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/996
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/whw
- 老年友好服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/XeS
- 社区家校合作的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/092=ole
- 科学信息获取的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/sss=474
- 社区手工活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/XFn=7Sf
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/801
- 数字资源检索的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/wwn
- 城市便民驿站的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/2K6
- 地方文化传播的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/597=gbe
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/oum=382
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%9B%86?/ZEm=L6A
- 公共设施维护的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/889
- 物业服务沟通的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/gvm
- 社区休闲设施的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/mk4
- 社区信息发布的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/622=xko
- 邻里共享空间的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/yil=035
- 社区绿色空间的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/rLu=AAm
- 开放数据应用的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/537
- 家庭收纳实践的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/tpy
- 城乡公共服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/wFq
- 小区公共照明的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/900=upo
- 健康信息获取的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/kso=988
- 乡村文化空间的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/jlt=qnx
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/468
- 城市体育设施中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/was
- 绿色快递包装的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/0fk
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/120=gob
- 运动安全知识的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/lot=093
- 城市夜间照明的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/XuX=Bax
- 城市骑行环境的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/172
- 网络安全教育的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/fvk
- 社区垃圾分类的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/KI7
- 城市运动公园的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/533=fqg
- 社区快递服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/rnv=618
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%BD%B1%E8%A7%86?/Rpc=TKP
- 网络信息辨识的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/414
- 老年学习活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/prv
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/GO8
- 公共空间安全的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/383=yha
- 公共服务沟通的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/wdr=980
- 农贸市场环境的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/aFu=Zg6
- 城市绿道建设的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/576
- 线上阅读资源的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/lif
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/1sp
- 公共场馆服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/920=zlx
- 城市建设科普的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/sdl=955
- 数字设备回收的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E9%97%AE%E7%AD%94?/VaF=54t
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/899
- 家庭环保习惯的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/kce
- 老旧小区改造的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/V7e
- 线上办事服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/566=rll
- 日常摄影记录的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/sbw=225
- 节能生活方式的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AE%AF?/Ql4=YH7
- 日常摄影记录的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/901
- 乡村电商实践的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/tgx
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/nyt
- 城市基础设施中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/073=oak
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/qvs=153
- 社区科普课堂的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/Ofa=3Ml
- 老年智能设备的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/711
- 人工智能科普的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/pih
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/eDY
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/651=weh
- 城市雨天出行的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/dwl=495
- 全民健身活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/jWT=R9i
- 社区法律科普中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/846
- 家庭阅读计划的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/aqy
- 城市展览体验的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/ikb
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/749=yfx
- 校园安全教育的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/hqj=176
- 绿色快递包装的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_978cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/BJz=Kpv
- 光伏知识科普的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/796
- 城市生活记录的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/kqd
- 社区手工活动的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/Fzi
- 环境教育课程的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/566=ttd
- 公共卫生设施的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/iek=192
- 家庭收纳实践的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/Bca=p7W
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/938
- 社区活动报名的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/dar
- 社区花园共建的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/1Vk
- 口袋公园建设的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/467=man
- 社区垃圾分类的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/wbt=316
- 街区更新实践的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_978cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/HjK=ys5
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/808
- 社区协商议事的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/buo
- 城市公共自行车的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/XqX
- 公共卫生宣传的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/074=zhk
- 无障碍出行的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/hoo=877
- 数字地图应用的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_978cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/oHO=wDo
- 生成式工具使用中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/960
- 科学观察活动的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/uzx
- 消防知识宣传中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/JV9
- 城市文明出行的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/444=dpb
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/xdi=250
- 家庭网络使用的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_978cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/gyw=Wxl
- 乡村教育资源的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/165
- 本地消费场景的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/yfn
- 校园节能行动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/qDO
- 社会体育指导的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/899=oeg
- 科学观察活动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/drr=804
- 家庭健康管理的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/GRt=3ho
- 学校体育活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/654
- 生活技能分享的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/zwk
- 绿色出行服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/alI
- 城市应急科普的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/246=hqb
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/zuy=694
- 绿色快递包装的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_978cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/8eZ=EkP
- 社区健康讲座的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_978cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/337
- 老年运动活动的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_978cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ukl
- 家庭饮食安排的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_978cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/QyV
- 公共服务评价的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_978cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/738=qkw
- 乡村文化活动的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_978cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/wbk=529
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_978cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/jzN=fpm
- 智能家居应用的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_978cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/198
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_978cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/nug
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_978cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/LYT
- 家庭志愿活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_978cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/248=ops
- 老年人日常照护的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_978cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/brg=449
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_978cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/Mzc=3L9
- 绿色校园实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/396
- 城市便民驿站的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/ubt
- 公共服务咨询的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/IWR
- 城市文明出行的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/059=jdd
- 药品使用科普的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/mmk=115
- 校园安全教育的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_978cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/0fw=7xg
- 旧物循环利用的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_978%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/665
- 社区志愿服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_978%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/pgx
- 城市应急广播的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_978%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/he8
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_978%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/842=gkj
- 社区安全巡查的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_978%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/oba=128
- 数字资源检索的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_978%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%BD%B1%E8%A7%86?/ZRR=EGy
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/790
- 软件开发学习的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/heo
- 青少年科技社团的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/Nfl
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/255=jwq
- 城市水环境观察从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/jbi=893
- 城乡公共服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/UGi=Wc3
- 社区停车服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_978%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/573
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_978%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/faf
- 家庭志愿活动的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_978%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/KQ7
- 运动安全知识的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_978%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/088=shg
- 家庭节能实践的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_978%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/eot=247
- 智能手机助老的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_978%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/g79=A9u
- 节能生活方式的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/596
- 青少年编程学习的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/iwr
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/zl3
- 城乡公共服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/850=bjw
- 环境教育课程的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/fpu=959
- 读书会组织的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/5Mf=aPD
- 校园阅读活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_978%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/562
- 就业技能培训的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_978%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/eer
- 数字学习资源的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_978%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/Yhn
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_978%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/134=rox

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
