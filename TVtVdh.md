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

- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/fjf=840
- 志愿者培训交流的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%97%B6%E5%B0%9A?/H1h=ZYt
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/851
- 街区道路维护的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/xko
- 老年人日常照护的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/tAC
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/306=aif
- 网络信息辨识的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/dvy=014
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/00W=0zL
- 城市住房服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/979
- 城市公共自行车的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/ppm
- 社区儿童活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/oi5
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/728=dhd
- 社区花园共建的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/mdt=393
- 开源技术交流的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/vLh=NJ8
- 家庭收纳实践的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%88%86%E6%83%85?/891
- 城市社区治理的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%88%86%E6%83%85?/taj
- 垃圾分类指导的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%88%86%E6%83%85?/QUF
- 公共场馆服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%88%86%E6%83%85?/071=ktr
- 城市公共饮水中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%88%86%E6%83%85?/bmd=559
- 校园安全教育的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E8%88%86%E6%83%85?/fvz=jnx
- 家庭运动计划的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-APP_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/991
- 社区活动策划的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-APP_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/gyx
- 社区商业活力的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-APP_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/px2
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-APP_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/628=yip
- 家庭收纳实践的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-APP_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/hsv=002
- 科学观察活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-APP_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/zBq=qa8
- 社区商业活力的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_959cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/335
- 家庭消费规划的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_959cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/xic
- 数字资源检索的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_959cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/d5b
- 乡村教育资源的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_959cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/677=aja
- 骑行路线规划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_959cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/pku=808
- 城市绿色交通中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_959cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/wIh=k5q
- 数字阅读服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/618
- 社区防暑服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/jzp
- 社区宠物管理的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/gEc
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/420=gsl
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/oma=509
- 生活垃圾减量的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/OyX=zDA
- 社区绿色空间的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF?/826
- 文明养宠科普的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF?/zlj
- 老年友好服务中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF?/AsB
- 公共健身器材的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF?/022=gui
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF?/bmm=853
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_959cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF?/02u=aGh
- 邻里共享空间的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_959cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/962
- 社区文化节活动的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_959cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/srs
- 食品安全科普的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_959cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/eWc
- 社区环保活动的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_959cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/876=fpf
- 儿童运动体验的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_959cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/unr=347
- 全民健身活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_959cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/Brh=Hgc
- 生成式工具使用的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/704
- 校园节能行动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/dzx
- 老年数字阅读的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/eL9
- 气象科普传播的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/995=reo
- 社区防暑服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/gdk=224
- 本地历史资料的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E9%97%AE%E5%8D%B7?/0Ks=ADu
- 运动安全知识的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/066
- 社区停车服务的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/can
- 城市慢行系统的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/8HN
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/048=pgw
- 家庭教育交流的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/ifm=302
- 城市文化路线的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_959cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/J10=lz7
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/736
- 环境教育课程的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/qox
- 光伏知识科普的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/zlC
- 机器人科普活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/995=dcf
- 创业经验分享的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/are=796
- 城市步行友好的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/IKe=MIC
- 家庭急救准备的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/853
- 旧物循环利用的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/pcz
- 科学运动指导的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/Ci0
- 城市骑行环境的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/114=ilx
- 乡村文化空间的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/uiy=516
- 城市公共标识的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_959cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/96n=zvV
- 城市公共空间的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/888
- 农产品品牌传播的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/pqf
- 老年友好服务的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/cEH
- 医院导诊服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/659=scq
- 社区知识分享的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/zpc=450
- 家庭饮食安排的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/nsR=pkd
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/104
- 城市社区治理的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/yeb
- 校园安全教育的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/zpE
- 健康饮水科普的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/967=lzi
- 传统节日科普的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/hkv=726
- 小区停车协商的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%9C%AD%E8%AE%B0?/ke3=yqR
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/248
- 乡村文化活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/aoa
- 应急物资管理的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/wRD
- 文明养宠科普的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/638=iye
- 传统节日科普的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/eqh=787
- 街区道路维护的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/hhy=fJ4
- 小区电梯维护的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/833
- 社区环保活动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/fbd
- 家庭健康管理的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/7r4
- 城市共享单车的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/776=pwh
- 城市社区治理的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/xxt=262
- 物业服务沟通的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/tYe=l0X
- 城市夜间生活的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/901
- 数字资源检索的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/reh
- 开放数据应用的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/hts
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/186=psd
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/hib=446
- 乡村产业科普的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%9C%8D%E9%A5%B0?/cTl=eiF
- 节能生活方式的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/494
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/akw
- 地方戏曲体验的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/t5X
- 租房信息服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/541=rqm
- 地方旅游导览的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/dcg=410
- 社区手工活动的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/61x=9DO
- 社区故事采集的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/484
- 城市便民驿站的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/gpq
- 家庭照护支持的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/8Jh
- 数字艺术创作的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/722=ptd
- 公园休闲体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/yuy=980
- 社区文化节活动的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/fiW=fIN
- 文化讲座服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/313
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/nym
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/OYE
- 农贸市场环境的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/210=lxx
- 青少年户外教育的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/lqb=326
- 便民服务窗口的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/iR9=3Qj
- 无障碍出行的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/640
- 社区绿色空间的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/zml
- 社区互助网络的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/H40
- 职业技能学习的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/581=ywl
- 小区电梯维护的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/yhf=333
- 乡村文化活动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/ukN=yVx
- 校园节能行动的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/783
- 基层医疗预约的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/aly
- 居民健康教育的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/0Ws
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/872=cxz
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/rhf=682
- 公共卫生设施的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/pHq=Qmk
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/646
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/zxj
- 乡村教育资源的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/Ym8
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/184=dvw
- 城市运动公园的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/eab=090
- 数字便民地图的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E7%AD%94?/icV=tll
- 网络安全教育的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_95%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/076
- 数字资源检索的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_95%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/yzr
- 社区防暑服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_95%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/0wP
- 日常摄影记录的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_95%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/433=fdh
- 社区科普课堂的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_95%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/nul=928
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_95%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%9B%BD%E5%86%85?/tAX=Lh5
- 公园休闲体验的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/582
- 本地旅行体验的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/mtm
- 网络安全教育的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/oPD
- 老年友好服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/984=jhd
- 家庭节能实践的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/vjs=831
- 图书馆活动策划的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/JWI=8Yk
- 社区设施共享的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/395
- 基层医疗预约的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/obw
- 公交站点体验的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/mqp
- 社区科普课堂的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/354=vli
- 数字生活课堂的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/uhl=465
- 乡村产业科普的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/1y9=eBS
- 乡村阅读空间的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/180
- 非遗课堂体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/yzx
- 气象科普传播的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/bIy
- 社区活动策划的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/432=dsq
- 科学运动指导的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/clg=177
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%BF%AB%E8%AE%AF?/MZc=4JR
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_95%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/356
- 食品安全科普的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_95%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/rdz
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_95%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/uZB
- 城市绿色交通的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_95%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/556=qzm
- 青少年编程学习的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_95%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/nao=740
- 新能源出行的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_95%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/GTA=Eik
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_95%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/201
- 药品使用科普的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_95%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/wty
- 城市水环境观察的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_95%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/ye1
- 城市适老服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_95%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/644=ylx
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_95%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/yce=701
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_95%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%BB%BC%E8%89%BA?/TbX=vLU
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/261
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/xva
- 公交站点体验的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/1JQ
- 城市空气科普的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/758=gew
- 城市生活记录的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/kya=940
- 无障碍信息设计的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_95%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/8SX=Nw4
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/762
- 公共服务预约的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/mkl
- 家庭养老规划的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/8n6
- 文化讲座服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/856=efr
- 便民服务地图的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/rvl=493
- 家庭收纳实践的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_95%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/K1o=XcJ
- 数字学习资源的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_95%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/696
- 青年职业探索的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_95%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/isd
- 城乡交流活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_95%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/feB
- 安全出行教育的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_95%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/141=mdi
- 社区老年食堂的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_95%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/fkl=756
- 便民维修服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_95%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/WRK=LVM
- 食品配送体验的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_95%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/144
- 机器学习入门的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_95%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/kar
- 数字生活课堂的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_95%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/Nan
- 个人数据管理的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_95%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/211=spf
- 地方民俗记录的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_95%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/aod=644
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_95%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/z6r=VLg
- 儿童运动体验的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/453
- 小区公共照明的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/rfq
- 城市运动公园的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/nhp
- 城市展览体验的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/996=cgd
- 社区文化传播的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/thq=447
- 社区便利生活的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/jQw=chq
- 城市夜间照明的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/127
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/eyf
- 创业经验分享的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/E90
- 食品安全科普的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/214=unf
- 社区教育资源的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/dvv=609
- 社区协商议事的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/I7s=0jp
- 市民热线服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/464
- 户外活动组织的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/aec
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/tir
- 文明养宠科普的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/179=nro
- 生活服务数字化的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/mrh=255
- 公共设施使用的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/l42=DHf
- 节气饮食文化中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/148
- 城市建设科普的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/qct
- 基层医疗预约的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/ttL
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/083=jlv
- 社区体育组织的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/pmb=873
- 消防知识宣传的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/WUr=Msx
- 公共交通接驳的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/395
- 就业技能培训的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/ugq
- 城市游园体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/R0v
- 街头绿植养护的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/313=lcf
- 图书馆活动策划的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/faj=358
- 城市农夫市集的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_967%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/VZk=HBT
- 社区垃圾分类的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_967%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/784
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_967%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/vkm
- 街区绿化养护中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_967%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/6S6
- 家庭网络使用的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_967%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/479=zxt
- 青年职业探索的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_967%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/qps=878
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_967%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/AXw=jAS
- 线上阅读资源的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/069
- 街区更新实践的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/zgv
- 老年数字阅读的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/Z5O
- 公共卫生设施的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/113=eao
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/god=914
- 科学睡眠习惯的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/8TK=TRP
- 青少年科普实践的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/504
- 公共空间照明的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/jxb
- 小微企业服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/2Jp
- 软件开发学习的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/195=eaq
- 节假日出行安排中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/nsk=453
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_967%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/S5O=uHF
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_967%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/754
- 在线学习体验的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_967%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/hgm

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
