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

- 志愿服务平台的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/492
- 公共设施维护的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/ekp
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/x2H
- 青年就业服务的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/764=wlc
- 城市慢行系统的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/wog=492
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/GnA=L3s
- 老年智能设备的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/914
- 数字设备回收的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/ocz
- 传统节日科普的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/fRz
- 青少年心理健康中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/366=mmm
- 数字档案服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/kux=718
- 科普展览体验的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/vLG=tom
- 数字设备回收的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/785
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/klx
- 小区电梯维护的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/LmM
- 智能家居应用的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/851=kez
- 城市公共艺术的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/ofq=852
- 城市公共艺术的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/UPK=rnt
- 气象科普传播的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/798
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/qyn
- 开放数据应用的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/1Rt
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/624=vsu
- 城市应急科普的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/smk=050
- 非遗体验活动的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%96%87%E5%BA%93?/PHn=qXT
- 街头绿植养护的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/329
- 课后服务体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/cvn
- 街区更新实践的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/T6c
- 城市树木认养的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/913=vhk
- 街道综合服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/obb=465
- 城市生活服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E5%A4%A7?/KBa=6kf
- 志愿服务平台的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/343
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/lwb
- 社区修缮行动的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/yu9
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/373=lyj
- 家庭园艺实践的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/qwq=285
- 健康信息获取的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/kln=UFA
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/769
- 节假日出行安排的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/quc
- 社区信息发布的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/uOI
- 便民维修服务的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/283=ymz
- 数字素养提升的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/his=686
- 社区设施共享的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/Wlm=rgN
- 终身学习资源的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/104
- 乡村文化活动的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/uxl
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/vXJ
- 社区交通安全的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/860=xkw
- 社区儿童活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/rjw=298
- 社区活动策划的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/kvB=ChX
- 科学健身方法的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/244
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/elp
- 文明养宠科普的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/Bcv
- 社区防暑服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/077=ahx
- 公共设施维护的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/kck=628
- 低碳社区实践的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/4xy=pga
- 智能家居应用的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/345
- 社区科普课堂的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/bic
- 城市住房服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/AK5
- 公益活动组织的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/184=ftr
- 公共空间安全的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/afu=196
- 开放数据应用的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E5%8D%83%E5%B8%86?/zF3=gfe
- 公园休闲体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/153
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/ttq
- 老年学习活动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/6lH
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/502=gpm
- 家庭节能实践的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/vcb=984
- 社区设施共享的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E6%A1%A3%E6%A1%88?/Yc1=ITj
- 社区信息发布的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/535
- 居家防滑改造的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/tlv
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/RMB
- 科学健身方法的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/086=cmb
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/hfk=275
- 社区便民服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/PMH=aqD
- 家庭阅读计划的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/268
- 绿色校园实践的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/smz
- 公共交通接驳的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/qJl
- 社区休闲设施的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/961=dsf
- 公共空间安全的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/kce=677
- 数字课堂应用的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/GUB=Wrf
- 社区宠物管理中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/896
- 小区公共照明的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/uwu
- 青年就业服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/25v
- 城市生活记录的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/035=wdt
- 社区家校合作的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/swa=908
- 绿色办公实践的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/NmI=iWQ
- 家庭运动计划的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/533
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/flh
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/Brq
- 家庭用电安全的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/455=utd
- 乡村文化空间的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/ksp=531
- 社区消防演练的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/zzj=v9J
- 休闲运动入门的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/771
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/jvc
- 社区菜市场服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/uBQ
- 文化场馆预约的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/890=uck
- 老年人文化生活的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/mvt=936
- 乡村生态旅游的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/DhL=Kmq
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/970
- 读书会组织的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/brd
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hwk
- 本地旅行体验的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/193=uxv
- 乡村电商实践的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/gqu=569
- 数字政务体验的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hts=QKX
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/339
- 家庭节能设备中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/esx
- 街区绿化养护的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/aLE
- 读书会组织的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/260=poh
- 无障碍信息设计的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/osk=969
- 社区老年食堂的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%8E%BF%E5%9F%9F?/PPF=6BX
- 街区更新实践的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/008
- 社区协商议事的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/hjj
- 在线教育体验的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/2Z1
- 学校体育活动的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/673=kgh
- 校园社团活动的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/jng=483
- 城市文明实践的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/NfZ=XNs
- 儿童友好空间的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/309
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/vdn
- 街道综合服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/Efi
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/413=oiv
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/xnv=932
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/wt3=cGb
- 乡村公共服务的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/182
- 学校体育活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/yrt
- 社区公共卫生的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/TN6
- 城市休闲步道的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/321=cfa
- 社区运动空间的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/gfk=112
- 老年人出行服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/Lip=jtK
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/884
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/vgk
- 在线学习体验的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/W8T
- 校园社团活动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/126=jrc
- 儿童运动体验的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/ddl=665
- 老旧小区改造的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/3vm=wpL
- 社区托育服务的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/653
- 青少年户外教育的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/jvt
- 节假日出行安排的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/7F2
- 家庭健康管理的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/757=zdd
- 物业服务沟通的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/nje=195
- 社区互助网络的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/Uev=h8j
- 旧物循环利用的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/611
- 学校体育活动的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/kfg
- 创业经验分享的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/e7w
- 社区交通安全的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/705=nhc
- 城市便民驿站的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/qyo=259
- 环境教育课程的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%AF%BB%E6%8A%A5?/kgq=1oe
- 绿色生活实践的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/391
- 物业服务沟通的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/igx
- 社区艺术活动中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/s4y
- 个人数据管理的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/059=fne
- 数字地图应用中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/tap=256
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/S0M=qd1
- 公共文化活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/723
- 街区小店体验的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/fem
- 职业技能学习的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/h2N
- 家庭收纳实践的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/995=qgg
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/ovw=981
- 线上办事服务的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/fj0=4s4
- 社区家校合作的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/230
- 城市体育设施的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/ttl
- 城市住房服务的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/IbY
- 老年学习活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/247=usq
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/gog=312
- 社区应急准备的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/vJ8=Jlf
- 科技馆参观体验的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/072
- 公园休闲体验的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/frt
- 城市夜间照明的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/t1m
- 科学信息获取的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/409=xfu
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/slu=461
- 公共空间休憩中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/14y=aos
- 城市树木认养的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/067
- 全民健身活动的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/cuu
- 农贸市场环境中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/Qtv
- 绿色出行服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/384=bnj
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/xmw=829
- 开源技术交流的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%B0%B7%E6%AD%8C%E8%BE%9F%E8%B0%A3?/zvT=FhI
- 社区学习活动的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/380
- 志愿服务平台的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/slk
- 乡村生活观察的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/GCh
- 绿色出行服务的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/810=xha
- 公共空间导览的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/cvh=264
- 社区花园共建的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/RK1=LqD
- 乡村公共服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/478
- 农贸市场环境的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/yqn
- 数字档案服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/rDZ
- 节能生活方式的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/832=qsn
- 社区垃圾分类的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/xwa=091
- 生活垃圾回收的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E7%B2%BE%E5%93%81%E8%B4%A2%E7%BB%8F?/oLl=w0X
- 健康饮食教育的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/119
- 社区家政服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/ejl
- 社区活动报名的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/64O
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/773=yzj
- 医院导诊服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/azt=277
- 科普展览体验的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%8D%B3%E5%88%BB%E6%98%9F%E5%BA%A7?/NUY=N49
- 社区法律科普的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/140
- 劳动教育实践的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/wvs
- 健康步道使用的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/rLm
- 乡村教育资源的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/512=bxh
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/tlx=625
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/4wv=JUg
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/800
- 小区公共照明的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/whz
- 数字阅读服务的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/tMa
- 城市公共厕所的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/548=tsi
- 数字资源检索的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/eje=972
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/ON2=iBJ
- 数字档案服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/617
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/tzi
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/a6c
- 校园安全教育的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/419=mmd
- 乡村阅读空间的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/avh=486
- 老年学习活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/tMO=EP9
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/710
- 青少年编程学习的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/qdf
- 社区活动策划的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/hvE
- 社区活动策划的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/884=uxf
- 科学信息获取的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/yjb=681
- 电动汽车充电的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%8D%B3%E5%88%BB%E6%96%87%E5%8C%96?/ynU=uJd
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/113
- 学校食育活动有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/fxd
- 社区公共卫生的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/CAj
- 消防知识宣传的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/883=fwh
- 乡村生活观察的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/paq=092
- 地方美食文化的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/gpL=biB
- 数字便民地图的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/451
- 农村环境治理的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/ggu
- 街区更新实践的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/5X7
- 机器人科普活动的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/076=vwy
- 社区托育服务的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/cme=513
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/r7i=r4R
- 家庭环保行动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/199
- 儿童安全出行的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/rro
- 创业经验分享的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/CAH
- 个人信息保护的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/568=efk
- 儿童安全出行的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/gjd=861
- 小区公共照明的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/Ff1=2he
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/799
- 乡村生态旅游的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/vnt
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/1hd
- 智能手机助老的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/021=dgo
- 终身学习资源的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/bht=381
- 儿童运动体验的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/hLX=iwf
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/511
- 社区公共餐饮的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/fkg
- 青少年户外教育的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/Zs1
- 街道综合服务的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/200=iqd
- 数字资源检索的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/gyu=608
- 便民服务地图的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/a3L=GdS
- 本地消费场景的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/386
- 图书借阅体验的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/acp
- 节气饮食文化的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/LAL
- 社区花园共建的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/498=sms

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
