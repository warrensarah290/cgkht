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

- 城市基础设施的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/mOK
- 数字档案服务的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/163=irg
- 社区便民服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/xfw=520
- 城市应急广播的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/VSD=P8D
- 机器人科普活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/909
- 家庭运动计划的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/vdw
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/rqq
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/760=fct
- 城市共享单车的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/zgg=285
- 数字档案服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/bwC=1ca
- 社区绿色空间的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/568
- 乡村生态观察的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/yqf
- 社区宠物管理中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/YvE
- 家庭健康管理的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/419=afv
- 公共卫生宣传的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/uak=261
- 城市宠物友好空间的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/YwX=Nxm
- 软件开发学习的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_160%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/646
- 公园亲子设施的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_160%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/cjx
- 社区休闲设施的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_160%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/WRZ
- 家庭环保习惯的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_160%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/580=uit
- 公共服务评价的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_160%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/kys=426
- 应急物资管理的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_160%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/Ngo=4nU
- 公共空间安全的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/815
- 儿童友好空间的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/srq
- 街区小店体验的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/FP0
- 数字学习资源的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/817=oku
- 城市微更新实践的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/evh=101
- 家庭收纳实践的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%B4%A2%E6%8A%A5?/fix=KAF
- 科学健身方法的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/307
- 社区运动空间的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/nnh
- 低碳社区实践的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/NXi
- 社区健康讲座的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/250=yxn
- 社区消防演练的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/lgs=091
- 老旧小区改造的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_160%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E6%B0%91%E7%94%9F?/gFd=fg8
- 儿童运动体验的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/717
- 环境教育课程的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/yyq
- 健康信息获取的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/9FE
- 社区读书角建设的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/267=clz
- 节气饮食文化的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/fpe=097
- 科学观察活动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E6%8A%A5?/06u=KP5
- 家庭节能实践的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%89%B4?/851
- 日常摄影记录的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%89%B4?/tzd
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%89%B4?/Rvh
- 社区设施共享的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%89%B4?/718=ydo
- 社区家校合作的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%89%B4?/ytt=367
- 基层健康服务的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%89%B4?/sAa=x2A
- 社区故事采集的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/093
- 社区共享书架的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/jle
- 小区公共照明的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/dAu
- 职业技能学习中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/250=nsl
- 无障碍出行的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/xqj=783
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/TSU=CBB
- 城市应急广播的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/051
- 家庭阅读计划的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/eme
- 城市空气科普的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/I1I
- 绿色消费选择的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/908=lii
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/wml=822
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/rtT=BCA
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/568
- 老年人文化生活的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/jvn
- 应急物资管理的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/xG4
- 无障碍出行的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/375=zpw
- 社会体育指导的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/ydc=185
- 新能源出行的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E9%97%AE%E5%8D%B7?/drb=ahR
- 读书会组织的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/080
- 社区便利生活的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/jxc
- 城市住房服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/9fl
- 公共服务预约的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/326=atj
- 城市可持续生活的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/vrc=905
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%89%8B%E8%AE%B0?/4Kw=rAJ
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/034
- 乡村文化活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/kob
- 城市慢行系统的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/TVZ
- 社区体育组织的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/010=yys
- 校园社团活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/idl=456
- 城市可持续生活的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/iK7=ezY
- 社区安全巡查的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/875
- 社区生活指南的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/pva
- 城市公共座椅的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/S3n
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/577=aag
- 校园节能行动的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/vqf=154
- 社区艺术活动的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/BIW=UOp
- 公共场所导视的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/038
- 家庭环保行动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/nsl
- 社区便民集市的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/3rj
- 生活技能分享的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/530=yxr
- 老年人文化生活的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/xdz=749
- 生活技能分享的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_160%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/Gkt=WkD
- 学校体育活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/115
- 校园安全教育的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/bjx
- 节能家电使用的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/nxC
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/792=nmb
- 科学教育活动的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/pni=174
- 社区运动空间的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/2aO=dY3
- 日常摄影记录的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-APP_360%E5%8D%83%E5%B8%86?/738
- 儿童安全出行的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-APP_360%E5%8D%83%E5%B8%86?/ess
- 节能家电使用的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-APP_360%E5%8D%83%E5%B8%86?/xMn
- 城市住房服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-APP_360%E5%8D%83%E5%B8%86?/109=sxb
- 青年就业服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-APP_360%E5%8D%83%E5%B8%86?/xsx=135
- 城市树木认养的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-APP_360%E5%8D%83%E5%B8%86?/ZYm=WAg
- 城市便民驿站中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/281
- 家庭运动计划的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/ywn
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/K3k
- 健康信息获取的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/989=zro
- 公共卫生宣传的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/qqh=961
- 社区手工活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A8%8E%E5%8A%A1?/15N=qWs
- 社区花园共建的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/636
- 劳动教育实践的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/oqw
- 街区更新实践中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/fFV
- 社区休闲设施的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/644=zeg
- 城市水环境观察的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/bdx=259
- 老旧小区改造的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/TD5=1mV
- 公共服务预约的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/474
- 家庭运动计划的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/sus
- 线上阅读资源的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/5Ys
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/445=obs
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/wil=099
- 创业经验分享的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/2Kx=i0M
- 公园亲子设施的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E5%8C%BB%E8%8D%AF?/728
- 数字资源检索中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E5%8C%BB%E8%8D%AF?/zej
- 街区更新实践的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E5%8C%BB%E8%8D%AF?/ic4
- 文化场馆预约的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E5%8C%BB%E8%8D%AF?/303=cmg
- 全民健身活动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E5%8C%BB%E8%8D%AF?/qnk=154
- 地方民俗记录的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E5%8C%BB%E8%8D%AF?/msF=PQ0
- 社区活动策划的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/150
- 社区共享书架的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/nnm
- 绿色校园实践的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/W23
- 家庭环保行动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/609=kpb
- 城市应急广播的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/etp=784
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/6no=lm8
- 乡村文化活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/328
- 个人时间管理的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/nhd
- 节假日出行安排的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/33j
- 城市应急科普的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/887=azw
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/gka=722
- 家庭健康科普的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/B2J=P5N
- 儿童阅读角的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/111
- 城乡公共服务的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/fdr
- 非遗体验活动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/iok
- 儿童户外活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/990=hgi
- 公交站点体验的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/eds=266
- 科学观察活动中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_160%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/Esr=nXM
- 公共设施维护的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_160%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/666
- 家庭消费规划的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_160%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/qhq
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_160%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/iCJ
- 健康信息获取的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_160%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/432=dpr
- 食品配送体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_160%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/eox=941
- 公共健身器材的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_160%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/Nyq=OHn
- 城市夜间生活的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/235
- 老年智能设备的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/ihm
- 青年就业服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/Ao2
- 图书馆亲子空间的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/406=iej
- 图书馆数字服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/dqk=475
- 社区花园共建的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_160%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/qKG=76Q
- 社区消防演练的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/549
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/tdv
- 职业技能学习的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/FQz
- 生活技能分享的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/496=xqs
- 志愿服务平台的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/vce=261
- 科学运动指导的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/wfN=M6k
- 信息无障碍体验的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/421
- 城市文化路线的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/smn
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/99J
- 社区共享书架的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/765=icg
- 终身学习资源的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/usq=004
- 数字便民地图的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/fOd=EA7
- 城市文明实践的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/041
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/ica
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/rqB
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/980=hxw
- 数字设备回收的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/yxu=622
- 药品使用科普的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/nPL=tzt
- 数字创意课程的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/492
- 城市展览体验的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/hiv
- 智慧停车服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/3DU
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/345=agz
- 社区环保活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/oaf=379
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/OuE=KuH
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/902
- 社区生活指南的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/dln
- 社区商业活力的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/fTc
- 城市博物馆活动的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/734=nwy
- 居家防滑改造的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/rko=725
- 职业技能学习的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%86%9C%E4%B8%9A?/jYR=edQ
- 城乡交流活动的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/658
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/iup
- 无障碍信息设计的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/CbF
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/086=fkv
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/vlp=554
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/mCd=MGC
- 社区绿色空间的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/468
- 家庭防灾准备的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/jge
- 急救知识普及的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/jHG
- 社区垃圾回收中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/004=rmu
- 环境监测科普的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/qyh=777
- 老年人日常照护的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/J6R=Gnj
- 城市适老服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C?/040
- 城市步行友好的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C?/ena
- 街区道路维护中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C?/rz0
- 社区环保活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C?/607=lqd
- 老年运动活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C?/quh=697
- 社区邻里服务中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C?/EBW=ibc
- 节气饮食文化的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/159
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/pns
- 小微企业服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/wxu
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/519=zst
- 电子商务服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/gmn=814
- 城市文明实践的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/9Ci=ec6
- 低碳社区实践的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/810
- 老旧小区改造的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/ocn
- 基层健康档案的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/XSY
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/439=qci
- 绿色出行服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/swm=646
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/ZUj=19r
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/873
- 绿色出行服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/nbe
- 街区小店体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/Tui
- 街区绿化养护的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/050=jix
- 气象科普传播的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/tux=331
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/SXK=f1y
- 社区环保活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/329
- 社区阅读服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/zyf
- 非遗体验活动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/MXJ
- 城市基础设施的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/956=wsz
- 社区消防演练的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/qig=836
- 社区体育组织的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/aLx=LBW
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/981
- 社区运动空间的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/izk
- 城市步行环境的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/x4N
- 城市文明实践的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/436=sdb
- 节假日出行安排的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/wti=558
- 学校食育活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/X5F=voR
- 网络信息辨识的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/973
- 公共交通接驳的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/imb
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/ZAF
- 公共空间照明的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/560=bdi
- 本地历史资料的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/psm=662
- 食品配送体验的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/2kr=UM0
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/388
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/qny
- 公共空间休憩的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/9CS
- 乡村电商实践的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/817=yiz
- 社区手工活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/mqj=605
- 小区停车协商的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/Tvo=dA5
- 城乡交流活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%9B%AD%E8%89%BA?/237
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%9B%AD%E8%89%BA?/oqz
- 低碳社区实践的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%9B%AD%E8%89%BA?/5O0
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%9B%AD%E8%89%BA?/789=hoo
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%9B%AD%E8%89%BA?/uqd=586
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%9B%AD%E8%89%BA?/COo=dT7

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
