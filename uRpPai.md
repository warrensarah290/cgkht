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

- 家庭陪伴活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/tkq=908
- 绿色出行服务的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/6uy=f3n
- 家庭饮食安排的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/610
- 气象科普传播的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/lbk
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/mKo
- 环境教育课程的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/697=txt
- 家庭照护支持的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/yne=504
- 节约用水实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8C%BB%E8%8D%AF?/Kjy=JaJ
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/911
- 城市夜间照明的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/cnl
- 城市文明实践的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/LCd
- 城市公共饮水的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/612=hjs
- 街区道路维护的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/qcv=068
- 非遗体验活动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/ddd=MCE
- 老旧小区改造的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_360%E8%B5%84%E8%AE%AF?/452
- 光伏知识科普的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_360%E8%B5%84%E8%AE%AF?/vhc
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_360%E8%B5%84%E8%AE%AF?/xUa
- 社区艺术活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_360%E8%B5%84%E8%AE%AF?/019=czr
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_360%E8%B5%84%E8%AE%AF?/mmg=214
- 家庭用电安全的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_360%E8%B5%84%E8%AE%AF?/M5O=Ust
- 城市地名文化的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/424
- 环境教育课程的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/okx
- 电动汽车充电的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/UI4
- 远程协作工具的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/355=ajg
- 社区互助网络的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/qde=533
- 城市慢跑路线的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/BF0=hAV
- 公共文化活动的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/401
- 社区手工活动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/aww
- 城市步行环境的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/hbo
- 社区公共卫生的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/086=xqc
- 城市休闲步道的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/qce=530
- 在线学习体验的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/Obi=0R2
- 个人时间管理的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/415
- 社区公共议事的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/yqv
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/349
- 地方美食文化的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/747=cwp
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/vny=874
- 家庭用电安全的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/mNB=gKg
- 社区养老服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/149
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/opu
- 读书会组织的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/QBS
- 社区体育组织的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/696=vzc
- 城市文明出行的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/jhn=006
- 青年就业服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E9%9B%85%E8%99%8E%E6%94%BF%E7%AD%96?/s49=8Hs
- 街区更新实践的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/869
- 城市公共座椅的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/jri
- 乡村产业科普的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/Ysn
- 智慧停车服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/424=rvc
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/mga=063
- 跨代沟通活动的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/K5p=uzh
- 社区修缮行动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/958
- 网络安全教育的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/ocr
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/0n0
- 节能生活方式的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/418=btr
- 城市建设科普的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/rrm=024
- 公共设施使用中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/txT=1W5
- 职业技能学习的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/942
- 家庭健康科普的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/zfk
- 环境监测科普的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/HCG
- 本地旅行体验的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/769=rgk
- 人工智能科普的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/mjz=285
- 校园阅读活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/ZsU=Llr
- 乡村电商实践的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/322
- 公共服务预约的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/aio
- 远程协作工具的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/EL4
- 城市便民驿站的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/760=kmv
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/omf=927
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/Zhi=aJ0
- 邻里共享空间的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/546
- 公共场所导视的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/cpb
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/RpQ
- 青年志愿活动的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/993=nuj
- 远程协作工具的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/nvg=610
- 垃圾分类指导的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/plo=CJ5
- 生成式工具使用的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/927
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/dni
- 城市应急广播的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/meI
- 便民维修服务的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/718=xij
- 本地旅行体验的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/ker=363
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/D1s=EcE
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/405
- 城市公共标识的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/kkw
- 社区托育服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/tkf
- 急救知识普及的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/462=drj
- 城市公共艺术中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/umr=108
- 地方旅游导览的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/3ta=Vff
- 本地消费场景的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_360%E5%9F%8E%E4%BA%8B?/236
- 本地旅行体验的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_360%E5%9F%8E%E4%BA%8B?/unm
- 城市公共饮水的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_360%E5%9F%8E%E4%BA%8B?/g5T
- 社区法律科普中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_360%E5%9F%8E%E4%BA%8B?/158=wou
- 食品配送体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_360%E5%9F%8E%E4%BA%8B?/ase=209
- 城市骑行环境的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_360%E5%9F%8E%E4%BA%8B?/nHj=7Bd
- 公共空间照明的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/479
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/fcg
- 老旧小区改造的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/zec
- 便民服务地图的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/402=tpd
- 地方文化传播的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/atn=065
- 社区快递服务的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/5mt=sxI
- 社区修缮行动的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/378
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/enh
- 口袋公园建设的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/hm4
- 社区便利生活的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/060=fth
- 物业服务沟通中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/qhb=893
- 无障碍出行的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/K8n=dSR
- 城乡公共服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/287
- 社区公共卫生的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/kfn
- 节假日出行安排的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/Gyl
- 社区设施共享的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/038=iim
- 青少年编程学习的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/dpv=410
- 物业服务沟通的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/xdS=ViK
- 数字政务体验的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/315
- 家庭饮食安排的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/eby
- 生活垃圾减量的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/e3l
- 街头绿植养护的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/301=lay
- 家庭养老规划的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/xzx=664
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/yqF=N84
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/562
- 数字学习资源的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/tam
- 社区手工活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/VIp
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/842=zqc
- 口袋公园建设的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/uzo=261
- 居家适老化改造的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/b05=5ut
- 智能手机助老的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/177
- 城市建设科普的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/oca
- 城市噪声观察的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/cRj
- 社区学习活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/019=imq
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/sqq=021
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8--%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/TUV=Z1r
- 公共服务预约的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/233
- 数字生活课堂的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/tcv
- 城市展览体验的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/XxR
- 城市步行友好的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/766=wlm
- 科普展览体验的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/ler=098
- 城乡公共服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/0H9=Fxc
- 数字创作工具的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%BE%88%E5%A5%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/960
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%BE%88%E5%A5%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/der
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%BE%88%E5%A5%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/ulu
- 公园亲子设施的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%BE%88%E5%A5%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/347=eia
- 地方美食文化的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%BE%88%E5%A5%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/zuz=615
- 数字艺术创作的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BF%A1%E8%AA%89%E5%BE%88%E5%A5%BD_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/JdS=E5h
- 健康信息获取的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/389
- 公共空间导览的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/dgz
- 青少年心理健康的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/ltQ
- 城市公共厕所的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/274=nto
- 小区电梯维护的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/xuu=324
- 社区文化传播的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%9C%88%E5%AD%90?/d53=MHm
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/885
- 市民意见收集的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/dqj
- 社区文化传播的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/ppX
- 数字生活课堂的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/517=qml
- 公共服务咨询的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/doh=682
- 社区互助网络的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%91%A8%E6%8A%A5?/SLe=tXl
- 社区故事采集的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/318
- 传统节日科普的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/ugr
- 乡村教育资源的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/cZZ
- 口袋公园建设的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/330=uao
- 气象科普传播的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/mai=503
- 城市应急科普的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%8F%90%E7%8E%B0%E5%BE%88%E5%BF%AB_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/iUT=iMz
- 城乡交通衔接的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/923
- 街区道路维护的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/dpp
- 亲子阅读活动的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/ndA
- 城市应急科普的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/105=exz
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/jtc=335
- 家庭节能实践的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/c7n=bno
- 环境教育课程的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/126
- 城市雨天出行的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/ywd
- 社区托育服务的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/evX
- 社区修缮行动的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/388=pia
- 公共空间休憩的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/jlv=652
- 农业科普体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/QL1=oC7
- 智慧城市体验的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/503
- 城市文明出行的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/nqg
- 社区活动空间的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/D7t
- 数字学习资源的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/732=gjg
- 公共服务咨询的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/kld=123
- 本地历史资料的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/2Rh=n6F
- 社区消防演练的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%90%88%E6%B3%95%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/423
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%90%88%E6%B3%95%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/xeo
- 文化讲座服务的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%90%88%E6%B3%95%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/W7F
- 儿童阅读角的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%90%88%E6%B3%95%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/596=nvk
- 传统节日科普的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%90%88%E6%B3%95%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/edn=492
- 小区公共照明的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%90%88%E6%B3%95%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/esj=pEe
- 社区便民集市的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/566
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/rav
- 社区生活指南的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/u7G
- 青少年心理健康的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/694=qjr
- 环境教育课程的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/lda=483
- 数字艺术创作的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/0wX=WtK
- 小区电梯维护的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/560
- 乡村公共文化的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/ekj
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/ekj
- 校园节能行动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/328=ota
- 邻里互助活动的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/iib=924
- 机器学习入门的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/czp=j40
- 公园休闲体验的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/775
- 家庭节能实践的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/awm
- 城市人文观察的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/Xrv
- 口袋公园建设的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/349=bux
- 数字学习资源的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/yfz=412
- 创业经验分享的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/EF4=6Wm
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/866
- 青少年科普实践的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/sax
- 户外活动组织的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/y0N
- 社区协商议事中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/096=vlb
- 家庭节能实践的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/xur=549
- 志愿服务平台的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/ia5=DZb
- 家庭网络使用的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/240
- 节气饮食文化的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/evy
- 终身学习资源的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/8DR
- 城市公共厕所的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/870=qfj
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/wkg=572
- 公共服务评价的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/e8c=Gst
- 公共设施使用的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E8%80%81%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/565
- 公共服务指南的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E8%80%81%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/vmn
- 地方文化传播的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E8%80%81%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/BJH
- 智能家居应用的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E8%80%81%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/544=uhc
- 街道综合服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E8%80%81%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/ihz=794
- 物业服务沟通的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E8%80%81%E5%B8%88_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/mCI=xAB
- 健康信息获取的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/010
- 社区故事采集的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/qis
- 社区环保活动的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/uW3
- 机器学习入门的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/175=zpd
- 社区垃圾回收的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/bcu=465
- 乡村公共阅读的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/omG=52C
- 传统手工艺体验的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E8%83%BD%E7%89%88%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/878
- 数字公共文化的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E8%83%BD%E7%89%88%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/uer
- 社区便民服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E8%83%BD%E7%89%88%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/bS1
- 公共空间照明的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E8%83%BD%E7%89%88%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/334=njf
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E8%83%BD%E7%89%88%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/kfw=449
- 乡村文化活动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E8%83%BD%E7%89%88%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/mOO=sBx
- 城市便民驿站中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/379
- 运动安全知识的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/hya
- 公共健身器材的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/sbA
- 创业经验分享的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/751=qvu
- 老年学习活动的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/bmu=705
- 乡村公共文化的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/Q8r=T8A
- 老年数字阅读的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/050
- 家庭消费规划的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hcg
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/clx
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/784=hyl
- 基层健康档案的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xbd=007
- 数字生活课堂的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/GKO=199
- 基层健康服务的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E9%A1%B5%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/909
- 健康饮水科普的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E9%A1%B5%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/avj
- 家庭安全提示的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E9%A1%B5%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/47u
- 儿童友好空间的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E9%A1%B5%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/113=dgu
- 居家防滑改造的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E9%A1%B5%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/zlp=085
- 公共服务预约的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E9%A1%B5%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/hyg=8zo
- 社区运动空间的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/178
- 绿色校园实践的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/dur

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
