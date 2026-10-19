# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 城市可持续生活的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_49m%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/FqF
- 基层医疗预约的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_49m%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/875=tti
- 急救知识普及的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_49m%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/qud=106
- 生成式工具使用的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_49m%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/J1u=EA7
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_49m%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/685
- 社区便利生活的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_49m%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/qox
- 家庭收纳实践的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_49m%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/GRO
- 社区文化节活动的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_49m%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/219=crf
- 基层健康服务的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_49m%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/noy=898
- 社区生活指南中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_49m%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/BGL=vs5
- 数字创作工具的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_4949%E6%BE%B3%E9%97%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/255
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_4949%E6%BE%B3%E9%97%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/ghz
- 数字支付体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_4949%E6%BE%B3%E9%97%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/jWR
- 老年运动活动的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_4949%E6%BE%B3%E9%97%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/496=fef
- 学校食育活动的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_4949%E6%BE%B3%E9%97%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/ywi=574
- 便民服务地图的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_4949%E6%BE%B3%E9%97%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/VRC=xon
- 社区庭院绿化的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/532
- 数字公共文化中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/mdz
- 社区活动空间的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/ofq
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/303=rap
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/dwq=110
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/LkU=zfh
- 乡村文化活动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/948
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/nck
- 乡村产业科普的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/1yu
- 农业科普体验的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/870=pot
- 农村环境治理的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/rty=156
- 安全出行教育的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/ljj=wb2
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/339
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/gmb
- 社区健康讲座的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/6gO
- 社区环保活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/041=mwh
- 物业服务沟通中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/cnl=704
- 老年人日常照护的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/SHs=5u7
- 开源技术交流的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9?/034
- 文化讲座服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9?/rej
- 城市微更新实践的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9?/geS
- 老年数字阅读的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9?/906=bwj
- 老年人文化生活的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9?/urn=285
- 绿色生活实践的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9?/VAD=cX9
- 远程协作工具的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%86%E9%A2%91?/014
- 小微企业服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%86%E9%A2%91?/nph
- 城市展览体验的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%86%E9%A2%91?/ZM5
- 乡村生态旅游的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%86%E9%A2%91?/277=cmc
- 科学信息获取中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%86%E9%A2%91?/uit=741
- 运动安全知识的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95welcome_360%E8%A7%86%E9%A2%91?/s8A=5sp
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/869
- 社区设施共享的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/hxr
- 城乡交流活动的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/yjF
- 环境监测科普的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/339=jzo
- 便民信息查询的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/tfw=688
- 口袋公园建设的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/oQ0=KWk
- 光伏知识科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/499
- 社区托育服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/eyk
- 社区交通安全的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/Wv9
- 校园社团活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/404=odu
- 网络信息辨识的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/dfp=122
- 消防知识宣传的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/lH6=ceS
- 社区互助网络的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/375
- 公益活动组织的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/nej
- 公共场所导视的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/LWu
- 城市文明实践的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/580=tsp
- 便民信息查询的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/ijb=539
- 青年职业探索的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/lkL=UW4
- 儿童友好街区的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/231
- 社区家政服务的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/fdy
- 街道综合服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/mpU
- 公共服务指南的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/602=jkv
- 家庭健康科普的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/gqv=005
- 地方美食文化的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_4949%E6%BE%B3%E9%97%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/MWo=Z74
- 城市骑行环境的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_4949%E6%BE%B3%E9%97%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/442
- 城市步行友好的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_4949%E6%BE%B3%E9%97%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/bko
- 农产品消费体验的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_4949%E6%BE%B3%E9%97%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/df5
- 社区邻里服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_4949%E6%BE%B3%E9%97%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/328=elo
- 休闲运动入门的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_4949%E6%BE%B3%E9%97%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/qfo=417
- 城市住房服务的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_4949%E6%BE%B3%E9%97%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E9%99%85?/LoI=BJd
- 机器人科普活动的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-APP_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/534
- 街区更新实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-APP_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/zqn
- 公共设施使用的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-APP_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/CbX
- 社区停车服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-APP_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/204=fth
- 农业科普体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-APP_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/uae=332
- 社区公共议事的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-APP_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/okz=hus
- 开源技术交流的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%BF%A1%E8%B4%B7?/264
- 本地旅行体验的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%BF%A1%E8%B4%B7?/lgb
- 公园休闲体验的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%BF%A1%E8%B4%B7?/emf
- 小区电梯维护的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%BF%A1%E8%B4%B7?/442=rci
- 青少年户外教育的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%BF%A1%E8%B4%B7?/hyx=691
- 生成式工具使用的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_4949%E6%BE%B3%E9%97%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%BF%A1%E8%B4%B7?/2ao=w5l
- 低碳社区实践的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/989
- 城市步行环境的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/mxb
- 生活服务数字化的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/srN
- 户外活动组织的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/212=vtv
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/qbu=052
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/Npq=spa
- 本地旅行体验的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/900
- 社区修缮行动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/yfa
- 本地历史资料的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/i1G
- 公共健身器材的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/342=umw
- 乡村教育资源的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/ajs=295
- 光伏知识科普的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_4949%E6%BE%B3%E9%97%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/G7s=UgS
- 数字设备回收中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/628
- 本地旅行体验的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/dhq
- 数字学习资源的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/ISV
- 本地旅行体验的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/481=jjd
- 社区协商议事的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/klk=348
- 老年人文化生活的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/hsJ=pgs
- 社区商业活力的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/264
- 公共场所导视的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/isy
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/Bqr
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/555=dkd
- 社区阅读服务的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/nsu=943
- 社区宣传栏更新的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_4949%E6%BE%B3%E9%97%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/7Eu=3bn
- 电动汽车充电的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/615
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/yek
- 城市生活服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/2Dd
- 城市文明出行的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/235=wks
- 在线学习体验的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/cds=089
- 社区手工活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/tEM=kZt
- 城市应急科普的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/562
- 城市空气科普的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/qlg
- 便民服务地图的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/Bav
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/936=zit
- 社区便民服务的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/hbf=849
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_4949%E6%BE%B3%E9%97%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/Dx4=HbT
- 消防知识宣传的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/406
- 社区便利生活的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/ymk
- 社区文化节活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/Jwm
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/926=ncs
- 公共场馆服务的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/ojc=350
- 儿童运动体验的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_4949%E6%BE%B3%E9%97%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/lC2=3pa
- 课后服务体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/577
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/fyt
- 公共服务数字化的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/1MW
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/000=hzn
- 家庭节能实践中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/tbn=625
- 文化场馆预约的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_4949%E6%BE%B3%E9%97%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%8E%A2%E5%BA%97?/Gz8=dyb
- 乡村公共阅读的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/387
- 绿色校园实践的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/jhb
- 青少年科技社团的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/nq5
- 家庭照护支持的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/359=hsg
- 节日文化体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/zkx=443
- 社区互助网络的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_4949%E6%BE%B3%E9%97%A8-%E5%AE%98%E6%96%B9_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/c6n=d8x
- 城市建设科普的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/919
- 文明养宠科普的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/fpp
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/tau
- 城市便民驿站的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/273=ttr
- 城市展览体验的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/osq=370
- 社区活动报名的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/OMs=0Z7
- 亲子阅读活动的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/784
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/khz
- 街头绿植养护的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/QDX
- 青年职业探索的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/704=rrr
- 城市农夫市集的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/nzn=666
- 青少年心理健康的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/NcF=kR7
- 城市共享单车的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/126
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/cxa
- 社区活动空间的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/aZK
- 城市公共空间的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/459=sgs
- 社区设施共享的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/iny=849
- 农贸市场环境的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%BA%E9%87%91?/dRK=7xh
- 校园安全教育的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/458
- 急救知识普及的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/iyg
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/CEc
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/370=hxu
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/sfk=020
- 公共交通接驳中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/0vv=2HS
- 家庭饮食安排的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/293
- 基层健康档案的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/bej
- 便民服务窗口的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/WkZ
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/284=nlz
- 开放数据应用的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/xki=592
- 绿色消费选择的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/7o1=nw0
- 公交无障碍服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/553
- 城市社区治理的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/znc
- 个人时间管理的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/Pd5
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/805=fia
- 社区文化传播的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/bea=298
- 数字课堂应用的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/mA7=hUW
- 智能家居应用的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/902
- 城市文明出行的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/bkv
- 公共服务沟通的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/7mf
- 城市应急科普的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/250=gwh
- 数字创意课程的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/nul=338
- 城乡交流活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/NGK=hw5
- 乡村生态观察的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/768
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/uqx
- 学校体育活动的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/eWK
- 社区修缮行动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/201=gdm
- 开放数据应用的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/asz=136
- 运动安全知识的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_500%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/AOi=Bh9
- 读书会组织的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_500%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/400
- 公共交通信息服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_500%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/gxe
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_500%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/uz0
- 健康步道使用中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_500%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/817=bjt
- 社区家政服务的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_500%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/jas=014
- 旧物循环利用的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_500%E5%BD%A9-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%81%A5%E8%BA%AB?/d8v=ygK
- 绿色生活实践的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/825
- 个人时间管理的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/vqe
- 家庭教育交流中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/S2r
- 家庭志愿活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/556=bvp
- 邻里互助活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/awa=349
- 社区心理支持的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_500%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/WRy=GfI
- 家庭健康科普的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_500%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/174
- 城市公共自行车的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_500%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/rzz
- 街区小店体验的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_500%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/NzB
- 社区安全巡查的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_500%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/059=qnq
- 传统节日科普的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_500%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/ahe=930
- 数字地图应用的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_500%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%A5%BC%E5%B8%82?/DsO=SgY
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_500%E5%BD%A9-APP_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/107
- 城乡交通衔接的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_500%E5%BD%A9-APP_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/zeg
- 个人数据管理的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_500%E5%BD%A9-APP_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/yzg
- 志愿服务平台的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_500%E5%BD%A9-APP_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/927=rys
- 社区学习活动的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_500%E5%BD%A9-APP_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/xcm=060
- 智慧城市体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_500%E5%BD%A9-APP_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E6%8A%A5?/WJO=ut9
- 城市文明出行的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/857
- 社区生活指南的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/qbl
- 绿色办公实践的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/BJR
- 校园节能行动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/292=jmh
- 数字公共文化的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/epg=373
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/CrU=fD1
- 图书借阅体验的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/453
- 社区邻里服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/xqv
- 社区文化传播的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/QyW
- 街区道路维护的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/211=xya
- 小区公共照明的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/ofz=948
- 城乡公共服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/kOU=Uwc
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/737
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/hvv
- 城市基础设施的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/KnA
- 无障碍信息设计的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/444=xip
- 个人信息保护的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/pbw=042
- 乡村公共服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_500%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/7Ql=U8h
- 机器学习入门的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_500%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/371
- 食品安全科普的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_500%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/lmm
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_500%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/fMS
- 本地消费场景的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_500%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/351=dxp
- 公共服务评价的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_500%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/qxu=842
- 食品安全科普的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_500%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/qbR=vZT
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%9C%AD%E8%AE%B0?/982
- 家庭健康科普的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%9C%AD%E8%AE%B0?/vgv
- 社区公共议事的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%9C%AD%E8%AE%B0?/Ymy
- 城乡交流活动的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%9C%AD%E8%AE%B0?/513=llg
- 数字便民地图的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%9C%AD%E8%AE%B0?/sgn=148
- 家庭养老规划的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%9C%AD%E8%AE%B0?/tcB=1dV
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/107
- 节能家电使用的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/fqp
- 软件开发学习中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/Gwu
- 学校体育活动的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/741=jsz
- 社区停车服务的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/vrp=027
- 居家防滑改造的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/n2K=EPc

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
