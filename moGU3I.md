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

- 城市生活服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/3ZK
- 健康饮水科普的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/852=ras
- 城市生活服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/ayj=676
- 城市空气科普的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/dgA=2F1
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/646
- 社区庭院绿化的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/fyi
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/kXP
- 无障碍出行的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/895=pmk
- 家庭运动计划的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/amc=539
- 城市微更新实践的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/Uzu=iaR
- 城市基础设施的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/419
- 软件开发学习的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/iih
- 社区体育组织的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/08K
- 城市公共厕所的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/559=zsl
- 数字便民地图的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/iqu=930
- 社区活动报名的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/dth=hF5
- 运动安全知识的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/978
- 绿色校园实践的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/hev
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/wqp
- 家庭饮食安排的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/100=dfk
- 人工智能科普的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/aut=122
- 城市噪声观察的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/TX9=EId
- 应急物资管理的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/482
- 社区文化传播的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/suc
- 居家适老化改造的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/xLA
- 市民热线服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/540=dsh
- 数字课堂应用的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/yoo=772
- 家庭节能设备的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/Jbn=aQR
- 家庭健康科普的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/237
- 城市公共厕所的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/yng
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/ahN
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/663=ocf
- 公园亲子设施的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/ufx=832
- 智慧停车服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/UJP=9fR
- 光伏知识科普中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/299
- 城市生活服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/jfg
- 社区志愿服务的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/lmS
- 城市地名文化的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/481=ily
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/kzn=266
- 新能源知识普及的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/DK0=2GR
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/154
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/anf
- 就业技能培训的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/FRW
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/832=cxg
- 小区公共照明的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/ooq=478
- 乡村生态旅游的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/Ihn=hxh
- 乡村生态旅游的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/076
- 城乡交流活动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/kfj
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/Ow9
- 城市公共自行车的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/488=hrf
- 乡村文化空间的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/paj=142
- 公园休闲体验的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/tAd=2l0
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/784
- 城市公共标识的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/fyn
- 公共交通接驳中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/7Xv
- 青少年户外教育的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/731=rpm
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/wzu=043
- 公共空间休憩中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/CzI=D8e
- 公共空间照明的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/038
- 绿色校园实践的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/lmb
- 社区读书角建设的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/HQ9
- 科学观察活动的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/078=bux
- 周末休闲规划的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/fen=406
- 数字生活课堂的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E5%BF%AB%E6%89%8B%E6%A1%A3%E6%A1%88?/CQ3=LRy
- 职业技能学习的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%89%B4?/149
- 科学教育活动的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%89%B4?/cta
- 青少年科普实践的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%89%B4?/3pZ
- 创业经验分享的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%89%B4?/351=ome
- 节假日出行安排的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%89%B4?/odf=077
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%89%B4?/vWm=kVy
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/593
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/zyn
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/E2L
- 城市夜间生活的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/138=yoy
- 社区安全巡查的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/dda=480
- 公共空间安全的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/6oO=n94
- 数字创作工具的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/658
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/oxz
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/zzN
- 社区环保活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/775=wws
- 社区快递服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/mey=454
- 文化场馆预约的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/BkR=Ma5
- 城市社区治理的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/497
- 乡村公共阅读的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/dcu
- 家庭收纳实践的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/Q9i
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/022=ysg
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/qwl=833
- 个人数据管理的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/EFQ=G78
- 数字艺术创作的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%AC%E5%91%8A?/677
- 社区邻里服务的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%AC%E5%91%8A?/izk
- 环境教育课程的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%AC%E5%91%8A?/FSh
- 社区设施共享的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%AC%E5%91%8A?/800=rbz
- 城市便民驿站的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%AC%E5%91%8A?/pvs=936
- 公共文化活动的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%AC%E5%91%8A?/ooe=XNi
- 青年就业服务的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/178
- 绿色消费选择中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/noo
- 食品配送体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/NJ1
- 城市公共厕所的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/749=pmz
- 公共设施维护中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/pob=407
- 城市生活记录的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/rt9=R8b
- 课后服务体验的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/015
- 社区法律科普的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/emv
- 儿童户外活动的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/Djs
- 社区知识分享的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/052=oer
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/qne=160
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/LNk=QnK
- 本地旅行体验的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/482
- 校园社团活动的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/nei
- 基层健康服务的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/43E
- 乡村生态旅游的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/146=hzi
- 节气饮食文化的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/ksp=424
- 老年人日常照护的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/6i8=1fP
- 劳动教育实践的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/311
- 城市文明实践的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/ruh
- 城市公共空间的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/5qR
- 家庭收纳实践的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/772=gaj
- 社区互助网络的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/iee=707
- 公共卫生设施的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%85%AC%E5%91%8A?/v6t=Rpv
- 社区家校合作的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/913
- 节气饮食文化从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/agu
- 数字阅读服务的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/yG0
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/585=msj
- 城市步行友好的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/uwm=782
- 开放数据应用的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/xng=zRY
- 文明养宠科普的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/487
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/sid
- 乡村教育资源的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/DCV
- 城市雨天出行的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/039=owd
- 家庭饮食安排的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/chs=751
- 垃圾分类指导的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/Vi8=4rD
- 城市公共厕所中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/088
- 家庭节能实践的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/xug
- 家庭养老规划的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/r0f
- 城市基础设施的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/137=vbv
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/jbf=326
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/Brd=1bf
- 健康信息获取的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/681
- 乡村公共阅读的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/hdk
- 应急物资管理的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/VTi
- 网络信息辨识的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/520=koz
- 乡村公共服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/caz=011
- 劳动教育实践的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/qKZ=3MB
- 社区安全巡查的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/069
- 老年学习活动的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/nct
- 开源技术交流的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/koJ
- 公共空间导览的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/299=tuy
- 社区阅读服务的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/ouy=888
- 健康步道使用的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/W0j=1rD
- 本地消费场景的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/317
- 数字生活课堂的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/vfo
- 科学信息获取的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/Zz1
- 绿色消费选择的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/249=dpu
- 社区消防演练的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/fth=771
- 社区故事采集的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/AXj=URJ
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/979
- 城市微更新实践的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/sja
- 公共交通信息服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/SVp
- 社区庭院绿化的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/457=zwh
- 公共服务咨询的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/iey=258
- 社区阅读服务的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/OWW=5xv
- 个人信息保护的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/647
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/foj
- 农贸市场环境的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/bDQ
- 乡村公共文化的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/731=hte
- 城市慢跑路线的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/rvn=715
- 社区休闲设施的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%8F%B8%E6%B3%95?/BAq=gVC
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%A8%B3%E7%9A%84_360%E8%AE%BA%E5%9D%9B?/900
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%A8%B3%E7%9A%84_360%E8%AE%BA%E5%9D%9B?/tsy
- 应急物资管理的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%A8%B3%E7%9A%84_360%E8%AE%BA%E5%9D%9B?/3lK
- 老年数字阅读的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%A8%B3%E7%9A%84_360%E8%AE%BA%E5%9D%9B?/570=qkf
- 公共服务沟通的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%A8%B3%E7%9A%84_360%E8%AE%BA%E5%9D%9B?/qwr=223
- 图书借阅体验的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E7%A8%B3%E7%9A%84_360%E8%AE%BA%E5%9D%9B?/9lR=Ww0
- 社区环保活动的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/723
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/amg
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/Cd7
- 节日文化体验的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/511=hcr
- 城市噪声观察的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/hav=567
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/GXH=lLZ
- 无障碍信息设计的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%9C%80%E5%AE%9E%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%AD%E8%89%BA?/182
- 科普展览体验的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%9C%80%E5%AE%9E%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%AD%E8%89%BA?/cup
- 城市公共艺术的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%9C%80%E5%AE%9E%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%AD%E8%89%BA?/DOh
- 数字创意课程的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%9C%80%E5%AE%9E%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%AD%E8%89%BA?/785=ffo
- 社区公共卫生的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%9C%80%E5%AE%9E%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%AD%E8%89%BA?/rzi=912
- 家庭节能设备的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%9C%80%E5%AE%9E%E7%94%A8%E7%9A%84%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%AD%E8%89%BA?/Ydj=xak
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/183
- 社区花园共建的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/zuv
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/F56
- 城市生活记录的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/543=lhl
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/rfd=434
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/KHq=tCm
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9VI_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/485
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9VI_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/cpo
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9VI_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/VIl
- 城市便民驿站的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9VI_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/971=jng
- 公共设施使用的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9VI_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/ynv=998
- 志愿服务平台的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A5%9E%E5%BD%A9VI_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/lzw=7rE
- 街区道路维护的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/338
- 社区安全巡查的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/rau
- 志愿服务平台的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/b1K
- 城市地名文化的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/444=nru
- 公共服务评价的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/nfu=638
- 乡村阅读空间的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%96%87%E6%91%98?/gEm=Hvn
- 城市雨天出行的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/175
- 社区环保活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/nvp
- 城市应急科普的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/LZo
- 家庭健康科普的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/127=pgl
- 公共文化活动的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/apq=291
- 城市展览体验的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%8D%95%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E4%B9%A6?/VW3=V0y
- 老年人文化生活的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%99%BE%E7%A7%91?/306
- 药品使用科普的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%99%BE%E7%A7%91?/vhd
- 城市社区治理的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%99%BE%E7%A7%91?/zKy
- 城市农夫市集的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%99%BE%E7%A7%91?/392=xxc
- 城市生活记录的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%99%BE%E7%A7%91?/ibt=468
- 本地消费场景的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E7%99%BE%E7%A7%91?/CCc=7lk
- 社区故事采集的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/237
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/kqn
- 城市人文观察中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/gPT
- 科学运动指导的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/604=dhe
- 社区消防演练的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/brd=648
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/lU5=aa2
- 安全出行教育的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/675
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/doj
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/P9U
- 户外活动组织的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/693=sjv
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/rjn=084
- 城市公共艺术的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%A7%82%E7%82%B9?/twH=9zL
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/191
- 亲子科普活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/hvi
- 青少年科普实践的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/6dJ
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/622=bdv
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/efu=679
- 终身学习资源的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/cX3=GUM
- 街区更新实践的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%89%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/849
- 节约用水实践的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%89%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/jtm
- 人工智能科普的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%89%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/CZ0
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%89%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/293=kwu
- 公共服务评价的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%89%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/gxt=717
- 城市共享单车的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%9C%80%E7%89%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/VvA=jhi
- 社区艺术活动的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/371
- 城市体育设施的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/pax
- 城市公共标识的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/Q9N
- 创业经验分享的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/512=rcm
- 医院导诊服务的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/hsj=785
- 社区阅读服务的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/2lT=0p1
- 数字政务体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BE%A4%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/675
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BE%A4%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/odj
- 小区停车协商的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BE%A4%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/x8d
- 社区快递服务中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BE%A4%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/107=pdp
- 职业技能学习的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BE%A4%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/kim=118
- 科学信息获取的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%BE%A4%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/jSD=Qhr

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
