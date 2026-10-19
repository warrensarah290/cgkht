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

- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E5%AF%9F?/qlw=596
- 健康饮食教育的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E5%AF%9F?/1Fa=yvr
- 休闲运动入门的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/979
- 街区道路维护的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/nmt
- 公园休闲体验的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/9PJ
- 家庭网络使用的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/678=mvs
- 城市文明出行的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/vha=942
- 社区停车服务的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/y7t=ocy
- 药品使用科普的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/036
- 乡村公共文化的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/zfq
- 儿童运动体验的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/qOG
- 小区停车协商的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/409=txt
- 社区学习活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/cqz=916
- 线上阅读资源的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/GAy=v5y
- 数字艺术创作中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/345
- 健康信息获取的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/okx
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/5D0
- 公交无障碍服务的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/109=pud
- 城市社区治理的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/cfs=878
- 数字创意课程的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/mIy=Mvg
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/122
- 社区菜市场服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/xmr
- 社区文化传播的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/8jX
- 在线学习体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/921=kda
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/dqq=617
- 乡村生态观察的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/xrM=nSN
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/941
- 家庭安全提示的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/imb
- 公园休闲体验的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/7RO
- 读书会组织的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/196=iuc
- 街头绿植养护的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/lwl=355
- 城市公共厕所中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%A4%AE%E8%A7%86%E5%B9%B6%E8%B4%AD?/Xf2=vjR
- 远程协作工具的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/325
- 居家适老化改造的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/fvj
- 个人数据管理的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/LS1
- 科学运动指导的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/960=omt
- 基层健康服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/ije=219
- 消防知识宣传的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/SAZ=5G4
- 小微企业服务的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/838
- 社区儿童活动中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/zgk
- 城市博物馆服务的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/osZ
- 个人时间管理的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/568=cpk
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/noa=231
- 街道综合服务的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/mHM=tPJ
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/397
- 个人数据管理从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/hlt
- 城市便民驿站的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/TA8
- 软件开发学习的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/655=pmx
- 城市公共空间的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/jjy=115
- 城市游园体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/2x1=npP
- 线上办事服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/149
- 社区艺术活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/yaf
- 志愿服务平台的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/62m
- 青年职业探索中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/527=tfy
- 本地旅行体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/pnp=053
- 数字学习资源的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/B0Z=IOH
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/324
- 家庭科学教育的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/zui
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/26I
- 节能生活方式的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/650=mxv
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/cko=435
- 城市雨天出行的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/qdg=Aa2
- 人工智能科普的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/164
- 儿童运动体验的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/vtv
- 通勤路线规划的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/pYN
- 家庭健康科普的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/054=gxx
- 健康信息获取的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/wqd=947
- 城市公共标识的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%BF%85%E5%BA%94%E7%A7%91%E6%8A%80?/ah2=wnp
- 亲子阅读活动的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/122
- 街区更新实践中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/yrg
- 社区防暑服务的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/koZ
- 城市文明出行的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/265=qif
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/syq=979
- 全民健身活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/EAE=pcq
- 科学教育活动的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/467
- 儿童友好空间的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/cvb
- 周末休闲规划的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/cqm
- 社区体育组织的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/424=wcr
- 公共服务咨询的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/lrp=153
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/BXw=pDp
- 城市文明实践的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/473
- 老年人文化生活的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/noy
- 通勤路线规划的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/b11
- 数字学习资源的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/830=krf
- 城市生活服务的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/wli=332
- 机器学习入门的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%85%A7%E7%9C%BC?/YXS=2Jq
- 城市运动公园的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/246
- 家庭节能实践的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/yfl
- 便民信息查询的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/EJE
- 数字创意课程中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/896=zjg
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/dgn=193
- 便民服务窗口的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%85%AC%E5%91%8A?/K5U=QsD
- 社区防暑服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/202
- 城市地名文化的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/tzq
- 个人数据管理的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/knH
- 社区文化传播的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/889=sst
- 乡村生活观察的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/feo=829
- 非遗课堂体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/MbN=HTS
- 城市共享单车的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/094
- 节假日出行安排中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/azg
- 安全出行教育的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/c8M
- 家庭节能设备的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/809=kpq
- 社区儿童活动的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/wfx=643
- 开放式学习空间的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/5bw=9HI
- 街头绿植养护的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/808
- 在线学习体验的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/pxv
- 本地消费场景的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/RHl
- 骑行路线规划的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/798=teq
- 家庭阅读计划的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/njs=675
- 校园社团活动中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/Yxu=6HA
- 社区老年食堂中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/092
- 网络信息辨识的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/mpv
- 社区设施共享的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/UM4
- 社区垃圾分类的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/523=cdq
- 职业技能学习的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/gpu=192
- 城乡交流活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E8%BA%AB?/moD=NI3
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/552
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/her
- 城市休闲步道的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/X97
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/695=hrg
- 老年人文化生活的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/suo=990
- 社区停车服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/ZcP=9lg
- 乡村生活观察的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/024
- 城市住房服务的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/xwu
- 社区垃圾分类的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/XQR
- 校园安全教育的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/275=uyk
- 街区绿化养护的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/scl=938
- 乡村产业科普的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/SfT=l35
- 家庭饮食安排的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/924
- 社区商业活力的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/quz
- 读书会组织的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/1Im
- 社区知识分享的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/604=nfk
- 社区艺术活动的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/mcv=171
- 创业经验分享的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E8%84%89%E8%84%89%E5%8D%9A%E5%AE%A2?/pFG=RgI
- 气象科普传播的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/607
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/wlx
- 社区法律科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/lB1
- 街区更新实践的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/366=tai
- 信息无障碍体验的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/gof=422
- 便民信息查询中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/du2=m2C
- 数字艺术创作的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/004
- 老旧小区改造的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/iga
- 机器学习入门的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/zpL
- 城市文化路线的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/934=gmk
- 读书会组织的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/uxy=311
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E4%BA%B2%E5%AD%90?/PNP=RPE
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/400
- 节约用水实践的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/ive
- 数字阅读服务的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/HGO
- 乡村文化活动的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/325=fnw
- 社区心理支持中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/vhn=484
- 城市可持续生活的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/ben=Pte
- 休闲运动入门的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/120
- 家庭急救准备的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/taw
- 城市公共标识的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/VLI
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/192=pcr
- 通勤路线规划的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/rti=661
- 城市公共饮水的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/WxN=c3j
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E6%88%BF%E4%BA%A7?/053
- 乡村电商实践的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E6%88%BF%E4%BA%A7?/bop
- 城乡公共服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E6%88%BF%E4%BA%A7?/zSy
- 基层医疗预约的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E6%88%BF%E4%BA%A7?/816=yjn
- 周末休闲规划的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E6%88%BF%E4%BA%A7?/tzf=231
- 食品配送体验的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E6%88%BF%E4%BA%A7?/w24=5Ql
- 社区便民集市的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E7%A8%8E%E5%8A%A1?/591
- 家庭消费规划的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E7%A8%8E%E5%8A%A1?/heb
- 乡村文化活动的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E7%A8%8E%E5%8A%A1?/2Hi
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E7%A8%8E%E5%8A%A1?/947=sfn
- 城市体育设施的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E7%A8%8E%E5%8A%A1?/qut=606
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E7%A8%8E%E5%8A%A1?/CQy=Xrc
- 社区体育组织的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/027
- 灵活就业交流的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/bhg
- 地方文化传播的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/9GK
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/279=xsz
- 环境监测科普的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/cel=805
- 健康饮水科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/UTU=vQ4
- 光伏知识科普的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/977
- 城市公共艺术的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/dho
- 青年职业探索的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/uKW
- 城乡公共服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/914=xep
- 本地消费场景的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/che=078
- 线上阅读资源的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%93%E4%B8%9A%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/ZxO=ZDg
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%96%BD%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/849
- 城市公共艺术的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%96%BD%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/dat
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%96%BD%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/3Ni
- 网络信息辨识的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%96%BD%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/934=odv
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%96%BD%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/kkl=807
- 小区公共照明的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%AE%9E%E6%96%BD%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/qtd=itU
- 安全出行教育的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/801
- 家庭急救准备的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/gnq
- 开放数据应用的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/efd
- 社区养老服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/090=mbq
- 个人信息保护中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/oam=848
- 公共服务沟通的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/25e=r1b
- 老年智能设备的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/512
- 气象科普传播的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/pau
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/rA7
- 公共空间照明的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/595=dcp
- 社区养老服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/wjf=157
- 街区小店体验的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/LKy=XA9
- 社区教育资源的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E6%97%B6%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/188
- 本地消费场景的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E6%97%B6%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/spa
- 小微企业服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E6%97%B6%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/Qsu
- 应急物资管理的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E6%97%B6%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/637=adc
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E6%97%B6%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/bai=975
- 城市文化路线的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E6%97%B6%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%92%AD%E6%8A%A5?/EQF=YVq
- 机器人科普活动的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/966
- 老年人日常照护的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/hno
- 城市社区治理的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/sFh
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/672=sey
- 绿色建筑理念的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/eot=648
- 家庭健康科普的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/p0I=kcn
- 物业服务沟通的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/687
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/teq
- 数字公共文化的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/4IA
- 智能手机助老的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/026=btc
- 乡村文化空间的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/nms=527
- 青年志愿活动的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/4pg=zQn
- 老年友好服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%80%BA%E5%B8%82?/023
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%80%BA%E5%B8%82?/chx
- 文明养宠科普的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%80%BA%E5%B8%82?/Czd
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%80%BA%E5%B8%82?/986=www
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%80%BA%E5%B8%82?/rwp=991
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%80%BA%E5%B8%82?/1mw=Ykn
- 生活服务数字化的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/071
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/sqn
- 智能手机助老的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/aAt
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/060=abt
- 青少年户外教育中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/wxa=426
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E7%BB%8F%E6%B5%8E?/mO7=9Ux
- 城市社区治理的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86PK10%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/838
- 邻里互助活动的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86PK10%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/yjg
- 个人时间管理的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86PK10%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/FHz
- 环境监测科普的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86PK10%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/903=uyq
- 食品安全科普的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86PK10%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/lzd=883
- 社区停车服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86PK10%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/9fD=KqI
- 低碳社区实践的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/418
- 数字艺术创作的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/kls
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/Hf2
- 灵活就业交流中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/978=dnq
- 社区应急准备的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/qli=965
- 劳动教育实践的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%86%E5%8F%B2?/qmZ=AkK
- 学校食育活动的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/100
- 食品安全科普的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/tlq
- 城市建设科普的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/WRV
- 社区读书角建设的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/471=hwh
- 老旧小区改造的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/tim=857
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/M0i=XFK
- 社区教育资源的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/987
- 绿色校园实践的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/zvf

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
