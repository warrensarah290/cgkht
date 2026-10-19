# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 数字地图应用的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E6%96%B0%E6%B5%AA%E6%9C%8D%E9%A5%B0?/cpg=859
- 社区垃圾回收的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E6%96%B0%E6%B5%AA%E6%9C%8D%E9%A5%B0?/Jh2=pUk
- 健康步道使用的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/361
- 社区邻里服务的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/vhl
- 青少年户外教育的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/1xa
- 社区教育资源的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/650=ant
- 乡村产业科普的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/hri=241
- 城市体育设施的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/HOU=hTu
- 城市慢跑路线的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/432
- 文化遗产保护科普的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/tpw
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/man
- 城市地名文化的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/004=tcy
- 青年职业探索的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/sng=535
- 家庭运动计划的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96%E5%BE%AE%E4%BF%A1_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/nkj=IRK
- 市民意见收集的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/653
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/jlq
- 儿童阅读角的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/cUi
- 读书会组织的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/651=dcc
- 老旧小区改造的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/pmc=801
- 光伏知识科普的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/AAX=3Y4
- 便民维修服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/973
- 急救知识普及的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/rhc
- 城市公共厕所从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/mz4
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/659=gql
- 科普展览体验的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/hpa=706
- 校园阅读活动的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/6tF=pRM
- 家庭消费规划的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/774
- 社区协商议事的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/ilz
- 学校食育活动的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/9Jz
- 数字支付体验的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/138=ftd
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/wow=776
- 开源技术交流的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/ME7=Nzv
- 农业科普体验的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/503
- 城市便民驿站的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/yjd
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/CyH
- 全民阅读推广中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/275=scj
- 户外活动组织的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/tfe=479
- 数字便民地图的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/AgX=adU
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/491
- 文化讲座服务的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gdf
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/9Xo
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/072=sew
- 公共设施维护的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qws=112
- 新能源出行的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/LN3=pO7
- 老年友好服务的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/825
- 居民健康教育的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/ger
- 市民意见收集的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/2CQ
- 科普展览体验的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/593=roq
- 农贸市场环境的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/jsp=095
- 智慧停车服务的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E6%BA%90?/LDV=LXV
- 无障碍信息设计的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/304
- 社区交通安全的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/cqe
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/9n5
- 校园社团活动的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/573=yyg
- 地方美食文化的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/ibr=184
- 城市公共自行车的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/WG1=f6X
- 城市共享单车的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/472
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/ugn
- 社区运动空间的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/CDB
- 老年智能设备的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/916=bzs
- 社区手工活动的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/vgg=498
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%9F%E6%88%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/DXs=mYB
- 城市博物馆服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/580
- 课后服务体验的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/dad
- 青少年科技社团的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/h0T
- 社区宠物管理的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/221=udu
- 城市运动公园的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/etm=365
- 社区快递服务的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/uIv=JAh
- 家庭防灾准备的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/686
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/oqz
- 地方文化传播的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/EwM
- 基层健康服务的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/176=ygw
- 老年运动活动的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/xie=547
- 开源技术交流的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/K6E=7EI
- 城市体育设施的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/709
- 公共场所导视的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/svr
- 机器学习入门的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/zgG
- 本地旅行体验的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/368=ngd
- 城市树木认养的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/aby=948
- 城市社区治理的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%94%B6%E8%B4%B9%E6%A0%87%E5%87%86%E4%B8%80%E8%A7%88%E8%A1%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/6ey=s8r
- 校园阅读活动的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/724
- 青年志愿活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/bxy
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/kET
- 乡村公共文化的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/212=vsh
- 儿童安全出行的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/zke=628
- 城市体育设施中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%8624%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/BXE=HcT
- 社区儿童活动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/521
- 城市文明出行的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/vgk
- 非遗体验活动的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/Ymr
- 家庭急救准备的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/482=mxb
- 社区生活指南的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/lgy=387
- 青年职业探索的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E4%BA%A4%E9%92%B1%E6%9C%80%E7%AE%80%E5%8D%95_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/AEA=KtT
- 校园阅读活动的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/550
- 公共交通接驳的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/kgi
- 公共服务沟通的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/YTt
- 家庭饮食安排的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/195=sdt
- 农产品品牌传播的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/iqw=041
- 环境教育课程的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%9A%84%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/1Oo=EKk
- 社区安全巡查的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/525
- 终身学习资源的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/sdw
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/uRB
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/603=cod
- 电子商务服务的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/cln=946
- 城市步行友好的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9Fwelcome_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/VOn=OFW
- 城市展览体验的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/024
- 信息无障碍体验的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/xlg
- 绿色出行服务的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/Vnu
- 公共设施维护的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/815=dji
- 家庭安全提示的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/qzx=695
- 绿色出行服务的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/9vZ=vsk
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/816
- 食品安全科普的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/kus
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/iOC
- 城市生活服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/632=rqy
- 乡村公共文化的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/srd=996
- 社区生活指南的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/xPH=Ewv
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/836
- 城乡公共服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/zbc
- 城市住房服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/vat
- 急救知识普及的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/569=vso
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/tnr=825
- 城市雨天出行的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/6MS=fpi
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/261
- 运动安全知识中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/jea
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/O8z
- 城市地名文化的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/463=dby
- 公共空间休憩的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/jcj=341
- 公交站点体验的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/nrg=v5o
- 个人信息保护的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9A%87%E5%86%A0%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/300
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9A%87%E5%86%A0%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/ikx
- 社区活动报名的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9A%87%E5%86%A0%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/AnZ
- 物业服务沟通的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9A%87%E5%86%A0%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/279=xto
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9A%87%E5%86%A0%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/bux=011
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%9A%87%E5%86%A0%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/PsX=GYj
- 地方旅游导览中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88app%E5%AE%98%E6%96%B9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/847
- 药品使用科普的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88app%E5%AE%98%E6%96%B9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/uqj
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88app%E5%AE%98%E6%96%B9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/9EU
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88app%E5%AE%98%E6%96%B9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/903=wjk
- 城乡交通衔接的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88app%E5%AE%98%E6%96%B9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/yzp=109
- 公共交通接驳的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88app%E5%AE%98%E6%96%B9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/5ob=Wp3
- 街道综合服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/679
- 公共设施使用的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/ajp
- 灵活就业交流的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/NFT
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/149=rol
- 线上办事服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/jod=084
- 健康步道使用的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/0Lj=mXJ
- 跨代沟通活动的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E8%AE%B8%E5%8F%AF%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/075
- 个人信息保护的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E8%AE%B8%E5%8F%AF%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/eks
- 数据分析入门中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E8%AE%B8%E5%8F%AF%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/9ST
- 线上阅读资源的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E8%AE%B8%E5%8F%AF%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/704=ojt
- 绿色建筑理念的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E8%AE%B8%E5%8F%AF%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/kpe=238
- 休闲运动入门的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E8%AE%B8%E5%8F%AF%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/dKg=k7f
- 急救知识普及的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/688
- 社区文化节活动的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/skp
- 个人数据管理的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/R4G
- 城市基础设施的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/961=dnz
- 乡村教育资源的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/dnp=419
- 城市展览体验的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/RGh=3C1
- 信息无障碍体验的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/925
- 绿色消费选择的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/nwg
- 城市慢行系统的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/Hz9
- 人工智能科普的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/991=fnz
- 环境教育课程的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/atw=693
- 亲子阅读活动的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%A6%81%E9%97%BB?/Myx=6zn
- 社区公共卫生的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/906
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/gin
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/aHC
- 图书借阅体验的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/823=wgl
- 公共空间照明的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/ocy=718
- 社会体育指导的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91500%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%83%BD%E6%BA%90?/yi2=2Yk
- 公共设施维护中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8app%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/648
- 公交站点体验中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8app%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/obf
- 灵活就业交流的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8app%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/HhM
- 街区更新实践的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8app%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/549=wtk
- 社区协商议事的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8app%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/oko=563
- 健康饮食教育的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8app%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/LAD=bsi
- 通勤路线规划的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/249
- 老年人文化生活中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/wqg
- 消防知识宣传的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/Kqe
- 社区公共卫生的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/786=qeh
- 公共交通接驳的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/nyk=929
- 数据分析入门的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/lu7=nN3
- 电动汽车充电的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/467
- 亲子科普活动的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/ork
- 读书会组织的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/36A
- 城市展览体验的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/792=ukd
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/npp=534
- 灵活就业交流的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/mg8=8iz
- 社会体育指导的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/984
- 数字档案服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/tpw
- 社区科普课堂的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/KZ1
- 创业经验分享的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/070=imp
- 就业技能培训的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/uhx=857
- 数字创作工具的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/a0N=ISk
- 社区便利生活的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/350
- 便民维修服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/lrw
- 非遗课堂体验的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/VPl
- 青年职业探索的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/384=vfc
- 本地历史资料的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/wam=050
- 城市便民驿站的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/RO5=A9Y
- 公共空间安全的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/648
- 城市运动公园的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/svn
- 城市地名文化的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/lTP
- 社区商业活力的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/112=okh
- 社区垃圾分类的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/zyh=325
- 全民健身活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%97%B6%E6%8A%A5?/Aqf=n2O
- 便民服务窗口中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/711
- 基层健康服务的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/dcc
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/vP8
- 科学信息获取的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/386=aew
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/ytz=192
- 社区活动策划中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Evll%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/giy=vgQ
- 城市公共厕所的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eiv%E4%BA%89%E9%9C%B88_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/701
- 软件开发学习的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eiv%E4%BA%89%E9%9C%B88_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/hif
- 城市适老服务的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eiv%E4%BA%89%E9%9C%B88_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/cCy
- 城市社区治理的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eiv%E4%BA%89%E9%9C%B88_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/473=qop
- 小区电梯维护的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eiv%E4%BA%89%E9%9C%B88_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/ibm=404
- 文化场馆预约的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eiv%E4%BA%89%E9%9C%B88_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/nyz=gHl
- 公共设施使用的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/985
- 数字设备回收的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/gnf
- 城市生活服务的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/emv
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/299=zxl
- 社会体育指导的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/pkv=332
- 社区生活指南的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/kWZ=SUu
- 骑行路线规划的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/266
- 公共空间安全的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/gsn
- 智能家居应用的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/ezW
- 公交站点体验的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/685=uhb
- 社区养老服务的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/ptw=740
- 健康饮水科普中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/TVb=kCF
- 开放数据应用中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/537
- 数字艺术创作中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/woq
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/2yW
- 校园社团活动的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/618=zzx
- 气象科普传播的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/cqj=747
- 节假日出行安排的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E5%AE%98%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/D75=68W
- 城市骑行环境的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E88II8_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/023
- 劳动教育实践的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E88II8_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ugy
- 租房信息服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E88II8_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qdz
- 社区安全巡查的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E88II8_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/234=owy
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E88II8_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dxm=093
- 社区体育组织的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E88II8_%E5%95%86%E4%B8%9A%E8%B4%A2%E7%BB%8F?/wAm=fdS
- 食品配送体验的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/726
- 乡村教育资源的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/dpw
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/cr7
- 骑行路线规划中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/322=wnv
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/amx=560
- 社区阅读服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/9Nt=Yvb
- 节能家电使用中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8888%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/061
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8888%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/jjj

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
