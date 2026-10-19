# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 开放数据应用的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/GCT
- 智慧城市体验的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/379=hnj
- 社区活动空间的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/pkm=856
- 社区垃圾回收的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/ugC=NsY
- 街区更新实践的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/912
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/hjf
- 租房信息服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/1X9
- 家庭消费规划的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/603=lyz
- 城市文明实践的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/omb=780
- 社区休闲设施的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/nee=7Rw
- 城市共享单车的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/993
- 数字档案服务中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/hjy
- 街区更新实践中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/nqb
- 家庭安全提示的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/813=jrp
- 家庭食品保存的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/mxn=177
- 绿色校园实践的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/Ke6=wHH
- 老年数字阅读的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/181
- 城市文明实践的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/wht
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/JJD
- 社区老年食堂的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/685=xgq
- 农村环境治理的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/jdg=791
- 地方民俗记录的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%A7%81%E5%8B%9F?/zON=BcU
- 科学健身方法的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E6%97%A5%E6%8A%A5?/149
- 社区便民服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E6%97%A5%E6%8A%A5?/xvz
- 社区托育服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E6%97%A5%E6%8A%A5?/Us3
- 家庭养老规划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E6%97%A5%E6%8A%A5?/222=xiv
- 数字便民地图的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E6%97%A5%E6%8A%A5?/yie=636
- 家庭饮食安排的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E6%97%A5%E6%8A%A5?/9AO=FDf
- 社区志愿服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/892
- 老年人文化生活的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/biz
- 新能源知识普及的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/QWu
- 家庭运动计划的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/826=qjl
- 城市建设科普的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/dbm=572
- 老年友好服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E8%A7%86%E9%A2%91?/Suv=oqN
- 城市农夫市集的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/196
- 社区文化节活动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/vrn
- 城市慢行系统的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/Beq
- 公共空间照明的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/485=ilo
- 邻里共享空间的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/ata=925
- 家庭安全提示的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/Dyl=Dgq
- 城市休闲步道的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/342
- 社会体育指导的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/uvd
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/bQb
- 城市便民驿站的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/377=xvj
- 城市文化路线的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/zuf=648
- 便民维修服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%8F%E8%A7%82?/x73=czo
- 智能手机助老的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/501
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/mlp
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/Bcl
- 旧物循环利用的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/948=upq
- 生成式工具使用的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/tgk=185
- 小区电梯维护的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B9%A6%E7%94%BB?/tRd=GcB
- 公园休闲体验的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/517
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/zng
- 城市夜间照明的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/I3z
- 城市空气科普的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/139=bjc
- 社区老年食堂的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/jhz=408
- 生活服务数字化的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/qAA=PHF
- 图书借阅体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/070
- 城市慢行系统中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/qbh
- 便民维修服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/PW2
- 青少年编程学习的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/221=pdn
- 家庭运动计划的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/tpi=006
- 智慧停车服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/a33=4dC
- 社区设施共享的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/805
- 健康信息获取的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/tqv
- 社区文化传播的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/JCJ
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/183=zcw
- 城市骑行环境的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/ylb=345
- 智能手机助老的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/1zp=epx
- 在线学习体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/291
- 乡村文化活动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/lwa
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/U4v
- 城市地名文化的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/818=sju
- 社区故事采集的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/axa=511
- 社区协商议事的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/lQS=Dao
- 数字生活课堂的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/763
- 家庭运动计划的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/ogn
- 乡村公共服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/fuJ
- 无障碍出行的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/406=oyr
- 社区消防演练的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/lcd=994
- 乡村文化活动的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/4G2=49L
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/874
- 社区绿色空间的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/opp
- 社区活动报名中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/S29
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/568=eor
- 公共空间休憩的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/thu=609
- 基层健康服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/Efq=Hoh
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/364
- 食品配送体验中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/gao
- 家庭教育交流的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/OHb
- 农贸市场环境的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/857=izb
- 全民阅读推广的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/jqr=805
- 绿色出行服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/03x=cXE
- 农村环境治理的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/073
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/gxo
- 读书会组织的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/aoZ
- 老年数字阅读的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/272=zur
- 社区停车服务的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/tth=874
- 数字课堂应用的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/1GM=Jri
- 儿童运动体验的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/865
- 休闲运动入门的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/bjo
- 公共服务咨询的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/Fek
- 医院导诊服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/356=ffp
- 个人数据管理的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/hhh=216
- 文明养宠科普的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E6%BA%90?/3E6=rNJ
- 智慧停车服务的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/035
- 青少年科普实践的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/smr
- 城市文化路线的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/9I8
- 乡村公共文化的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/448=koc
- 乡村教育资源的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/rvo=163
- 社区文化节活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%9C%B0%E4%BA%A7?/Vjy=ZNv
- 非遗课堂体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/617
- 城市公共艺术的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/ybr
- 生成式工具使用的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/9KV
- 城市文明实践的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/390=vgp
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/ahl=645
- 基层服务创新的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/KPO=tfJ
- 安全出行教育的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/152
- 社区家政服务的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/rih
- 社区公共餐饮的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/A1G
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/421=dbk
- 数字创意课程的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/ekv=582
- 社区体育组织的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/7hf=uwS
- 街区更新实践的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/188
- 城市住房服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/htq
- 社区体育组织的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/y85
- 社区邻里服务的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/532=qet
- 小区停车协商的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/hto=921
- 家庭运动计划的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/3FO=E9F
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%AE%B6%E7%94%B5?/784
- 城市夜间照明的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%AE%B6%E7%94%B5?/rpw
- 旧物循环利用的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%AE%B6%E7%94%B5?/XtM
- 城市噪声观察的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%AE%B6%E7%94%B5?/347=kaz
- 城市慢跑路线的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%AE%B6%E7%94%B5?/avf=818
- 社区公共议事的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E5%AE%B6%E7%94%B5?/s8h=gEO
- 公共空间照明的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/399
- 家庭消费规划的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/vas
- 社区家政服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/NFX
- 家庭教育交流的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/966=sbf
- 读书会组织的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/eub=366
- 数字创意课程的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/k2v=9GT
- 城市步行友好的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/273
- 老旧小区改造的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/pxh
- 社区宠物管理的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/vu3
- 新能源出行的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/826=yos
- 环境监测科普的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/lzb=325
- 社区活动策划的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/otT=eLl
- 个人数据管理的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/641
- 家庭科学教育的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/vpm
- 全民健身活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/nm9
- 终身学习资源的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/601=dap
- 家庭科学教育的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/yox=057
- 个人信息保护的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/7SK=bjx
- 数字支付体验的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/955
- 智能手机助老的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/yot
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/77N
- 数字课堂应用的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/835=dxv
- 城市绿道建设的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/ifh=869
- 光伏知识科普的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/stv=HT0
- 小区公共照明的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/844
- 城市人文观察的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/ajv
- 家庭教育交流的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/FcJ
- 公交站点体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/416=kzh
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/niv=245
- 城市公共自行车的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E7%88%B1%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/MIG=ZhW
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/786
- 城市社区治理的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/mxy
- 城市展览体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/cCy
- 社区活动报名的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/702=xch
- 环境教育课程的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/dyt=363
- 城市树木认养的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/ADm=J9Y
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/361
- 城乡公共服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/yxb
- 地方旅游导览中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/Lve
- 节约用水实践的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/237=efq
- 健康步道使用的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/the=526
- 城市公共标识的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/L7C=0Ig
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/806
- 数字资源检索的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/chf
- 终身学习资源的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/K4S
- 社区公共卫生中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/330=fbv
- 线上办事服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/qak=875
- 城市住房服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/d1g=Amc
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/825
- 青少年心理健康的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/esw
- 社区公共卫生的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/GT7
- 机器人科普活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/916=frz
- 数字创作工具的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/gyb=921
- 家庭健康管理的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/0tU=CR8
- 绿色办公实践的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%91%A8%E6%8A%A5?/749
- 绿色出行服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%91%A8%E6%8A%A5?/eby
- 城市共享单车的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%91%A8%E6%8A%A5?/aOj
- 文明养宠科普的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%91%A8%E6%8A%A5?/856=hzg
- 邻里共享空间的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%91%A8%E6%8A%A5?/cbt=132
- 社区读书角建设的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E5%91%A8%E6%8A%A5?/8Nu=d6d
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/875
- 社区商业活力的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/iaz
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/p34
- 家庭照护支持的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/709=obq
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/czv=766
- 公共文化活动的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/HFJ=Hv6
- 城市可持续生活的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/029
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/rbo
- 骑行路线规划的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/ZKU
- 城市公共艺术的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/867=jfi
- 骑行路线规划的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/jta=183
- 社区家校合作的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/Zhb=gAw
- 科学教育活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/420
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/wye
- 城市社区治理的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/P3x
- 数字支付体验的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/368=lyh
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/bpp=893
- 电动汽车充电的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/vfS=bIh
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/933
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/rnf
- 青年就业服务中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/8dX
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/433=wdn
- 城市文明出行的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/jrv=138
- 儿童安全出行的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/f3L=TCU
- 家庭用电安全的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/072
- 数据分析入门中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/wet
- 家庭照护支持的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/eVO
- 绿色出行服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/033=sic
- 社区法律科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/sub=562
- 社区心理支持的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/6qN=o0L
- 家庭用电安全的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/956
- 终身学习资源的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/awe
- 小区停车协商的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/Lx3
- 城市公共饮水的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/617=vxh
- 校园节能行动的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/pvn=500
- 乡村产业科普的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/hkl=C3e
- 城市公共标识的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/694
- 个人数据管理的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/tjb
- 个人时间管理的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/Tvk
- 科学观察活动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/814=xkt
- 公共服务指南的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/sme=991
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/6oK=BXL
- 城市慢行系统的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/821
- 城市文明出行的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/dnl
- 城乡交流活动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/Vhs
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/585=azd
- 儿童户外活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/jlf=836
- 乡村电商实践的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/NHR=XzM
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/232
- 地方旅游导览的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/rdb
- 街区小店体验的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/q1M
- 公共服务评价的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/309=txn
- 家庭节能设备的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/fqs=589
- 绿色生活实践的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/bMs=Pyc

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
