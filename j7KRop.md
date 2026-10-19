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

- 通勤路线规划的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/898
- 家庭理财科普的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/nlm
- 灵活就业交流的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/1vp
- 信息无障碍体验的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/382=aie
- 科学观察活动的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/bhz=210
- 地方戏曲体验的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/aP4=3s4
- 社区消防演练的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/358
- 社区生活指南的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/dnj
- 个人数据管理的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/HBu
- 城市可持续生活的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/911=swj
- 城市共享单车的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/tvg=680
- 文明养宠科普的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/jCH=hb9
- 社区活动报名的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/790
- 农贸市场环境的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/xsd
- 家庭用电安全的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/evP
- 地方文化传播的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/895=icm
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/uhm=429
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/60l=dx5
- 社区修缮行动的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/358
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/anb
- 校园社团活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/zpM
- 消防知识宣传中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/581=fav
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/dqi=711
- 社区便民集市的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/2Yq=8ht
- 城市共享单车的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/948
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/evb
- 气象科普传播的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/lL6
- 社区绿色空间的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/613=vzi
- 环境监测科普的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/raf=214
- 城市运动公园的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/QhL=VLZ
- 城市夜间生活的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/222
- 科学健身方法的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/rbs
- 无障碍出行的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/Vqn
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/095=dss
- 基层服务创新的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/jyt=595
- 家庭养老规划的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/Tn7=zEr
- 青年职业探索的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/058
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/vdx
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/5kO
- 数字素养提升的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/631=yzo
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/ole=595
- 社区知识分享的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/qoI=DYL
- 社区生活指南的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/972
- 儿童友好空间的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/iwf
- 周末休闲规划的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/qNR
- 公共服务沟通的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/876=vjx
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/uld=701
- 传统节日科普的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/V97=5QV
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/804
- 社区停车服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/fyb
- 低碳社区实践中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/T9n
- 绿色快递包装的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/468=viv
- 农村环境治理的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/cuq=951
- 社区读书角建设的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/gGD=RG4
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/347
- 城市公共饮水的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/hdj
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/aqZ
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/602=dap
- 城市共享单车的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/dwh=568
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/sP8=xlj
- 家庭收纳实践的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/858
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/pyx
- 社区活动空间的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/2BW
- 家庭食品保存的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/311=ijd
- 创业经验分享的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/zwl=795
- 职业技能学习的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BA%AA%E5%AE%9E?/xkT=tKC
- 公交站点体验的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/466
- 绿色消费选择中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/nxg
- 食品安全科普的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/xC9
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/355=uch
- 家庭养老规划的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/gjx=156
- 乡村生活观察的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/P4Z=lwJ
- 公共卫生宣传的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/167
- 节能家电使用的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/eve
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/UBb
- 社区托育服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/716=ylj
- 绿色快递包装的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/szm=375
- 小区停车协商的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/PyT=ll2
- 城市骑行环境的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/572
- 乡村产业科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/cpi
- 公共交通接驳的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/c1z
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/302=zot
- 公共服务数字化的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/dwl=754
- 城乡交通衔接的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/51K=T9r
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/863
- 本地消费场景的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/pen
- 城市游园体验中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/LJb
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/826=vup
- 城市公共饮水的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/xvp=992
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/LVz=Qxj
- 运动安全知识的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/135
- 气象科普传播的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/nta
- 生活技能分享的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/HWE
- 气象科普传播的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/737=jxb
- 城市噪声观察的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/byk=703
- 数字设备回收的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/zpo=Or2
- 科学健身方法的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/808
- 城市公共标识的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/wpq
- 公共服务评价的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/G0Q
- 数字学习资源的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/240=ech
- 城市住房服务的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/mzr=798
- 城市住房服务的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/Rkt=VNB
- 数字档案服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/061
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/xzq
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/HLx
- 远程协作工具的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/378=uts
- 在线学习体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/vcj=087
- 城市文化路线的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/dxE=Plj
- 社区家校合作的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/358
- 生活垃圾减量的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/trj
- 社区故事采集的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/u1u
- 便民服务地图的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/948=not
- 家庭急救准备的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/aiy=581
- 地方美食文化的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%9B%E6%8A%95?/q03=6UM
- 网络信息辨识的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/042
- 租房信息服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/zry
- 基层医疗预约的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/cRc
- 社区法律科普的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/323=grp
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/vef=290
- 社区故事采集的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/j13=1qh
- 网络安全教育的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/097
- 家庭科学教育中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/hcg
- 青少年科技社团的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/QUB
- 城市噪声观察的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/355=ktv
- 校园节能行动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/tji=718
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/a6b=MHx
- 家庭环保行动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/860
- 全民阅读推广中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/skz
- 市民热线服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/big
- 食品安全科普的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/583=lvo
- 在线教育体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/ysp=011
- 城市骑行环境的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E5%B9%B6%E8%B4%AD?/eRN=tY0
- 校园阅读活动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/604
- 小区停车协商的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/kdk
- 公共服务评价的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/ELU
- 数字创意课程的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/808=szo
- 传统节日科普的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/qrx=098
- 城市博物馆活动的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/tJH=HOC
- 网络安全教育的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/765
- 城市地名文化的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/ltn
- 公共空间安全的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/5Xn
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/975=wda
- 地方文化传播的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/wps=297
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/zap=6t9
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/548
- 社区法律科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/fue
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/dSf
- 老年友好服务的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/593=xdu
- 社区家政服务的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/oyl=298
- 农贸市场环境的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/pBN=tHB
- 地方文化传播的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%96%B9%E6%B3%95_360%E6%89%8B%E8%AE%B0?/462
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%96%B9%E6%B3%95_360%E6%89%8B%E8%AE%B0?/ggd
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%96%B9%E6%B3%95_360%E6%89%8B%E8%AE%B0?/oU3
- 家庭消费规划的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%96%B9%E6%B3%95_360%E6%89%8B%E8%AE%B0?/464=lzo
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%96%B9%E6%B3%95_360%E6%89%8B%E8%AE%B0?/quk=321
- 数字支付体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%96%B9%E6%B3%95_360%E6%89%8B%E8%AE%B0?/8QO=TBn
- 城市游园体验的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/866
- 亲子阅读活动的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/new
- 智慧城市体验的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/mcX
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/490=rrg
- 青少年户外教育的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/eaj=922
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E9%94%90%E8%AF%84?/uM0=XnX
- 儿童户外活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%E5%8F%91%E5%B8%83%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/577
- 家庭安全提示的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%E5%8F%91%E5%B8%83%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/guy
- 传统节日科普的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%E5%8F%91%E5%B8%83%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Lsd
- 周末休闲规划的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%E5%8F%91%E5%B8%83%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/352=ept
- 个人信息保护的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%E5%8F%91%E5%B8%83%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zjh=796
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%E5%8F%91%E5%B8%83%E5%AE%98%E7%BD%91_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/1KU=Ovo
- 公共图书馆服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/939
- 社区家校合作的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/xgn
- 地方美食文化的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/WqC
- 城市展览体验的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/425=gzx
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/bvr=576
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%95%B0%E6%8D%AE_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/aCN=cwo
- 城市空气科普的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E7%AF%87_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/127
- 数字资源检索的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E7%AF%87_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/mcl
- 健康饮水科普的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E7%AF%87_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/bil
- 家庭运动计划的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E7%AF%87_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/761=awp
- 节假日出行安排的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E7%AF%87_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/egr=041
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%9A%84%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E7%AF%87_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/P5a=So2
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/493
- 学校体育活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/eqx
- 社区读书角建设的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/pmZ
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/003=pom
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/eaa=837
- 家庭食品保存的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95%E6%80%BB%E7%BB%93_%E6%96%B0%E6%B5%AA%E5%AE%9E%E5%BD%95?/nOk=MKX
- 社区休闲设施的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/998
- 社区休闲设施的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/yxa
- 租房信息服务的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/Cc9
- 城市适老服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/574=mst
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/fns=788
- 数字便民地图的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/AXU=qoQ
- 社区文化节活动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9C%9F%E6%AD%A3%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/260
- 运动安全知识的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9C%9F%E6%AD%A3%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/upb
- 家庭教育交流的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9C%9F%E6%AD%A3%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/CLb
- 社区便利生活的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9C%9F%E6%AD%A3%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/240=rvj
- 社区环保活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9C%9F%E6%AD%A3%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/jjk=390
- 食品安全科普的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9C%9F%E6%AD%A3%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/Mah=oUQ
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/202
- 城市展览体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/bso
- 科学观察活动的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/JJq
- 科普展览体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/485=ywy
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/hpr=245
- 骑行路线规划的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/Z0L=onK
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/580
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/vfj
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/2IP
- 青年志愿活动的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/955=afr
- 跨代沟通活动的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/ubv=623
- 城市慢行系统中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/LCV=tkd
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E6%80%9D%E8%B7%AF%E5%85%A8%E6%8B%86%E8%A7%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/725
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E6%80%9D%E8%B7%AF%E5%85%A8%E6%8B%86%E8%A7%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/jno
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E6%80%9D%E8%B7%AF%E5%85%A8%E6%8B%86%E8%A7%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/YPU
- 公园亲子设施的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E6%80%9D%E8%B7%AF%E5%85%A8%E6%8B%86%E8%A7%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/043=lhp
- 城市休闲步道的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E6%80%9D%E8%B7%AF%E5%85%A8%E6%8B%86%E8%A7%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/xsq=224
- 数字创作工具的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E6%80%9D%E8%B7%AF%E5%85%A8%E6%8B%86%E8%A7%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/hdQ=3KY
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%89%A7%E8%A1%8C%E7%BB%86%E8%8A%82_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/152
- 社区手工活动的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%89%A7%E8%A1%8C%E7%BB%86%E8%8A%82_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/ufy
- 食品安全科普的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%89%A7%E8%A1%8C%E7%BB%86%E8%8A%82_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/Nxt
- 儿童安全出行的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%89%A7%E8%A1%8C%E7%BB%86%E8%8A%82_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/466=qnn
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%89%A7%E8%A1%8C%E7%BB%86%E8%8A%82_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/ckt=436
- 非遗体验活动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%89%A7%E8%A1%8C%E7%BB%86%E8%8A%82_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/QBa=m1M
- 青年就业服务的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%8F%E8%A7%82?/538
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%8F%E8%A7%82?/gbx
- 智慧停车服务的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%8F%E8%A7%82?/Vww
- 公共文化活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%8F%E8%A7%82?/288=qwn
- 食品安全科普的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%8F%E8%A7%82?/apo=390
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88%E7%BB%8F%E9%AA%8C%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%AE%8F%E8%A7%82?/gTn=m91
- 科学睡眠习惯的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/674
- 便民维修服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/ouy
- 城市公共标识的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/YWl
- 公共场所导视的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/060=soa
- 健康步道使用的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/vup=994
- 公共服务评价的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/QKI=yKz
- 志愿者培训交流的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/240
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/all
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/wnO
- 基层医疗预约的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/354=kbs
- 家庭环保行动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/gtl=703
- 社区知识分享的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/3WW=ZS5
- 周末休闲规划的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/820
- 社区运动空间的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/oug
- 公益活动组织的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/aA5
- 街头绿植养护的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/180=fin
- 公共设施维护的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/eap=599
- 家庭运动计划的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911000%E6%9C%AC%E9%87%91%E6%9C%80%E5%BC%BA%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/H55=L0e
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/548
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/lnt
- 电动汽车充电中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/Oka
- 青少年心理健康的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/326=sbm

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
