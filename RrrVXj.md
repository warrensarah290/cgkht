# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 环境监测科普的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/bel=439
- 家庭教育交流的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/P4t=eio
- 数字便民地图的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/881
- 通勤路线规划的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/ary
- 社区生活指南的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/JWD
- 家庭照护支持的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/770=uft
- 社区手工活动中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/ime=636
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/sFO=0af
- 绿色出行服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/178
- 居家防滑改造的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/aqc
- 公交站点体验的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/cLK
- 线上阅读资源中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/934=jtf
- 城市慢行系统的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/jtw=866
- 社区托育服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/HeF=3nZ
- 城市文明实践的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/543
- 社区修缮行动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/ped
- 城市空气科普的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/C7H
- 市民热线服务的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/568=tml
- 小区电梯维护的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/dnl=152
- 校园阅读活动的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP_%E6%8A%96%E9%9F%B3%E5%BD%A9%E7%A5%A8?/knq=XCB
- 公共场馆服务的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/521
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/udf
- 数字便民地图的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/TyI
- 食品安全科普的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/235=vli
- 社区快递服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/cqk=803
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/bVi=zrb
- 城市慢行系统的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/963
- 数字资源检索的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/cgh
- 乡村文化空间中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/t6f
- 食品安全科普的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/773=adh
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/wew=546
- 社区艺术活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/qMt=Kgb
- 公共卫生设施的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/112
- 生活技能分享的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/ozt
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/K4Q
- 家庭教育交流的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/612=lga
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/ihy=801
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/UYg=zrt
- 青年志愿活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/529
- 数字资源检索的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/egr
- 小区电梯维护的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/LnI
- 基层健康档案的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/261=yun
- 公共健身器材的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/zfx=439
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/5is=NpB
- 基层健康服务的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/632
- 家庭防灾准备的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/wzy
- 社区教育资源的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/Y1Z
- 数字创意课程的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/798=yyv
- 城市文明实践中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/nil=229
- 社区垃圾分类的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/wFy=2Fm
- 城市公共空间的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/175
- 城市便民驿站的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/fmf
- 安全出行教育的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/Ndn
- 城市社区治理的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/636=vkk
- 儿童友好空间的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/qvr=927
- 就业技能培训的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/ZV5=pTP
- 户外活动组织的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/618
- 非遗体验活动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/rzl
- 乡村电商实践的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/3ZJ
- 青年职业探索的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/178=cne
- 运动安全知识的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/jtd=952
- 数字阅读服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/nmM=nNo
- 家庭网络使用的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/666
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/fcx
- 社区共享书架的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/Akn
- 邻里互助活动的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/808=egz
- 急救知识普及中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/beq=219
- 乡村产业科普的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/MHD=JKm
- 城市基础设施的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/854
- 社区消防演练的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/wxu
- 家庭节能实践的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/xkV
- 节假日出行安排中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/086=fud
- 机器人科普活动中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/ahc=819
- 社区休闲设施的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/Bf4=dP5
- 城市公共艺术的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/696
- 旧物循环利用的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/eqa
- 全民阅读推广的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/Ae9
- 文化场馆预约的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/688=uap
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/fxw=564
- 公交站点体验的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/exK=5cJ
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/435
- 青年志愿活动的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/eoa
- 公共服务数字化的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/yjc
- 公共空间照明的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/562=zww
- 社区垃圾回收的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/zpq=210
- 社区绿色空间的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/mRo=ybW
- 应急物资管理的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/071
- 社区文化节活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/syy
- 基层健康档案的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/CJT
- 科学运动指导的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/076=cuj
- 公共空间安全的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/kig=576
- 城乡交流活动的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/2x7=RHr
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/440
- 远程协作工具的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/wvy
- 城市微更新实践的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/Fwh
- 家庭用电安全的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/347=mva
- 邻里互助活动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/usa=106
- 城市生活服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%8F%E8%A7%82?/Pvl=FgP
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/761
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/gid
- 城市住房服务的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/haU
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/961=vpy
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dna=777
- 市民意见收集的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/hmR=GAj
- 家庭环保习惯的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%95%85%E6%B8%B8?/740
- 社区老年食堂的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%95%85%E6%B8%B8?/wif
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%95%85%E6%B8%B8?/tX4
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%95%85%E6%B8%B8?/602=szi
- 家庭消费规划的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%95%85%E6%B8%B8?/csu=561
- 家庭阅读计划的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E7%95%85%E6%B8%B8?/Xlx=TTm
- 老年人出行服务的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/015
- 通勤路线规划的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/aay
- 儿童友好空间的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/F2D
- 科学观察活动的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/758=clq
- 城市绿色交通的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/ilb=084
- 家庭节能实践的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/KWB=Nbo
- 公共空间休憩的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A4%BE%E5%8C%BA?/598
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A4%BE%E5%8C%BA?/nui
- 街道综合服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A4%BE%E5%8C%BA?/ndp
- 农产品消费体验的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A4%BE%E5%8C%BA?/513=mkw
- 社区健康讲座中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A4%BE%E5%8C%BA?/gph=528
- 社区活动空间的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E7%A4%BE%E5%8C%BA?/ddx=xQc
- 运动安全知识的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/483
- 地方美食文化中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/nvl
- 节假日出行安排的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/wER
- 城市树木认养的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/039=hsa
- 线上阅读资源的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/zjm=471
- 志愿服务平台的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%89%E9%98%B2?/vjD=oB9
- 社区公共卫生的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/970
- 地方美食文化的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/vre
- 校园社团活动中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/ZOG
- 儿童阅读角的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/046=dso
- 社区环保活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/acd=442
- 线上阅读资源的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/xoR=DvV
- 数字档案服务的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/209
- 老旧小区改造的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/qsi
- 运动安全知识的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/Nw1
- 城乡交流活动的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/297=zid
- 社区健康讲座的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/alz=608
- 社区绿色空间从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%88%86%E6%83%85?/LbD=2uX
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_360%E5%88%8A%E7%99%BB?/725
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_360%E5%88%8A%E7%99%BB?/oak
- 城市雨天出行的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_360%E5%88%8A%E7%99%BB?/1Ou
- 非遗体验活动的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_360%E5%88%8A%E7%99%BB?/979=xlk
- 开放数据应用中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_360%E5%88%8A%E7%99%BB?/dkz=727
- 地方文化传播的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_360%E5%88%8A%E7%99%BB?/V0K=rPs
- 周末休闲规划的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/745
- 小区停车协商的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/boa
- 农业科普体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/7rG
- 青年职业探索的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/112=sva
- 乡村电商实践的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/ytr=553
- 课后服务体验的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/h5S=usj
- 数字创意课程的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/704
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/lti
- 社区家政服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/XNW
- 乡村产业科普的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/325=inh
- 食品安全科普的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/mzu=487
- 网络安全教育的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/I1S=oDD
- 生成式工具使用的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/222
- 老旧小区改造的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/ffd
- 社区环保活动的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/mkD
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/476=dtp
- 图书借阅体验的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/kwm=381
- 智能家居应用的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/fpr=vdX
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/995
- 学校体育活动的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/wsh
- 社区儿童活动的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/pXy
- 文化讲座服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/995=bee
- 数字课堂应用的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/gao=487
- 社区消防演练的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/aSg=O57
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/693
- 数字素养提升的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/jdu
- 老年运动活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/nZp
- 文化讲座服务的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/801=jnd
- 老年数字阅读的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/fuq=390
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/BBW=N1O
- 城市公共自行车的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/682
- 公共空间安全的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/tml
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/Aa4
- 城市文化路线的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/709=esv
- 社区设施共享的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/xrh=167
- 数字公共文化的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/Ywg=Qq1
- 乡村公共文化的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/642
- 公共图书馆服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/bts
- 老年友好服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/kLW
- 绿色生活实践的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/527=uhz
- 数字生活课堂的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/seq=409
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/DH5=wTa
- 家庭安全提示的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/236
- 社区生活指南的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/wvb
- 公园无障碍服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/sjK
- 儿童友好空间的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/535=bkb
- 青少年科普实践的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/llc=899
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/TEJ=EWd
- 基层健康服务的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/076
- 便民服务地图的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/jpf
- 城市基础设施的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/5mt
- 社区垃圾分类的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/785=gdm
- 个人信息保护的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/jsf=303
- 便民服务地图的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/2bT=Ilz
- 数字地图应用的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/613
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/vnt
- 农业科普体验的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/4o7
- 城市运动公园的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/511=hlr
- 社区慢性病防控的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/oar=420
- 城市博物馆活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E9%BC%8E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/4bQ=O50
- 市民热线服务的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E9%97%AE%E7%AD%94?/060
- 个人时间管理的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E9%97%AE%E7%AD%94?/zeg
- 城市公共厕所的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E9%97%AE%E7%AD%94?/Xn4
- 社区体育组织的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E9%97%AE%E7%AD%94?/919=xil
- 节气饮食文化的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E9%97%AE%E7%AD%94?/lsz=048
- 家庭急救准备的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E9%97%AE%E7%AD%94?/L11=qL7
- 数字支付体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/631
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/fme
- 数字便民地图的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/sTR
- 街区小店体验中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/566=oao
- 社区应急准备的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/siz=698
- 全民阅读推广的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/Qnv=Ny7
- 农业科普体验的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/733
- 社区环保活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/gsx
- 光伏知识科普的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/TjK
- 公共卫生设施的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/808=rsh
- 在线学习体验的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/uer=985
- 社区活动空间的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/Fgb=KLB
- 创业经验分享的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/783
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/kqw
- 邻里互助活动的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/Xho
- 数字阅读服务的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/600=ina
- 家庭安全提示的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/eri=149
- 便民服务地图的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E4%BF%A1%E6%89%98?/oUV=GYK
- 农村环境治理的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/254
- 职业技能学习的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/wcj
- 家庭科学教育的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/kDF
- 环境教育课程的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/057=lbx
- 公园亲子设施的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/wtt=853
- 街区更新实践的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/x7q=h3U
- 个人数据管理的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/939
- 城市应急广播的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/kil
- 家庭急救准备的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/EeY
- 公共空间照明的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/223=zjh
- 家庭节能设备中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/qne=031
- 文明养宠科普的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/0jO=XRj
- 跨代沟通活动的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/507
- 城市水环境观察的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/fji
- 地方美食文化的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/xro
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/634=gkf
- 小区电梯维护的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/vbt=765
- 健康饮水科普的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/YhR=EsN
- 旧物循环利用的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%89%B4?/423
- 家庭健康管理的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%89%B4?/avo

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
