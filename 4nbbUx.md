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

- 校园阅读活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/223
- 图书馆活动策划的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/jlv
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/vxQ
- 生活垃圾减量的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/546=apv
- 社区健康讲座的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/xij=427
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/vPk=iLd
- 社区教育资源的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/198
- 邻里共享空间的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/gsd
- 城市慢行系统的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/cIX
- 电动汽车充电的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/233=ybm
- 校园节能行动的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/qmo=213
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%81%8C%E5%9C%BA?/4z9=hnG
- 家庭消费规划的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/802
- 城市骑行环境的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/del
- 非遗体验活动的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/xa6
- 节假日出行安排的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/238=rdi
- 城市树木认养的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/gfg=596
- 青少年科普实践的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/gAy=Usk
- 老年运动活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/503
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/bbf
- 城市文明实践的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/Hcc
- 食品安全科普的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/116=sbj
- 农贸市场环境的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/nvn=094
- 城市人文观察的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%A3%9F%E5%93%81?/TC8=uvf
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/404
- 城市应急科普的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/fyz
- 社区消防演练的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/VLg
- 气象科普传播的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/550=hhy
- 绿色出行服务的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/ewd=576
- 城市空气科普的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%AE%A2%E5%90%A7-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/gDs=STJ
- 市民意见收集的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/002
- 青少年心理健康的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/xgc
- 旧物循环利用的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/muk
- 本地消费场景的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/044=fba
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/bmy=051
- 公共设施维护的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%A7%A3%E5%AF%86?/M6S=nqz
- 社会体育指导的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/456
- 城市运动公园的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/puj
- 家庭园艺实践的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/iiu
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/530=iyx
- 社区消防演练的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/vpg=241
- 儿童友好空间的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/J7C=kgI
- 街头绿植养护的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/057
- 家庭园艺实践的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/grs
- 公共设施维护的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/Rau
- 公共卫生宣传的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/003=dmg
- 电子商务服务的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/gtg=366
- 家庭消费规划的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/Zpx=7qW
- 城市绿色交通的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/803
- 乡村文化空间的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/vlt
- 老年人文化生活的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/KeP
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/621=por
- 公共空间照明的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/mzs=583
- 全民阅读推广的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/PvY=hmG
- 运动安全知识的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/062
- 地方文化传播的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/xkq
- 社区文化节活动的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/E4J
- 儿童阅读角的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/896=wzl
- 社区学习活动的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/swz=961
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/AgU=enE
- 智慧停车服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/461
- 光伏知识科普的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/gwy
- 网络信息辨识的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/8fe
- 本地旅行体验的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/693=fdc
- 数字支付体验的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/uup=021
- 老年数字阅读的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/E4G=T36
- 本地旅行体验的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BE%8E%E9%A3%9F?/490
- 社区环保活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BE%8E%E9%A3%9F?/wnt
- 气象科普传播的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BE%8E%E9%A3%9F?/yBQ
- 社区学习活动的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BE%8E%E9%A3%9F?/047=gol
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BE%8E%E9%A3%9F?/gaz=920
- 乡村生态旅游的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BE%8E%E9%A3%9F?/BCB=6IE
- 科学健身方法的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/843
- 数字地图应用的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/mhy
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/Qny
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/231=clz
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/sok=057
- 社区修缮行动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/FQT=pEU
- 公共空间安全的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/033
- 数字设备回收的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/kew
- 数字档案服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/73Y
- 社区公共议事的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/123=nni
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/whh=006
- 软件开发学习的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/Oa2=cZr
- 儿童友好空间的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/727
- 科技馆参观体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/vdl
- 城乡交流活动中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/edy
- 数字素养提升的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/948=yhb
- 旧物循环利用的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/cbh=984
- 健康饮食教育的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/iah=s1s
- 儿童阅读角中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/295
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/niv
- 数字学习资源的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/I0X
- 科学观察活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/520=rph
- 数字创意课程的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/qhk=352
- 社区设施共享的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/d4a=d6e
- 社区法律科普的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/202
- 公园亲子设施的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/pva
- 创业经验分享的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/Wza
- 社区邻里服务的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/287=gkt
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/ujw=688
- 绿色生活实践的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/fTQ=U6V
- 数字便民地图的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/012
- 城市公共艺术的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/jzu
- 街区绿化养护的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/30X
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/870=wwb
- 家庭用电安全的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/syn=963
- 乡村公共文化的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/CSb=tKZ
- 灵活就业交流的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BA%BA%E7%89%A9?/492
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BA%BA%E7%89%A9?/qmx
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BA%BA%E7%89%A9?/fwf
- 生活垃圾减量的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BA%BA%E7%89%A9?/375=lzb
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BA%BA%E7%89%A9?/sbc=089
- 个人时间管理的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BA%BA%E7%89%A9?/Gqh=6i1
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%81%A5%E8%BA%AB?/642
- 个人时间管理的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%81%A5%E8%BA%AB?/flu
- 文明养宠科普的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%81%A5%E8%BA%AB?/7HT
- 软件开发学习的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%81%A5%E8%BA%AB?/018=zgl
- 学校食育活动的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%81%A5%E8%BA%AB?/czl=634
- 垃圾分类指导的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E5%81%A5%E8%BA%AB?/RGA=8RR
- 老年智能设备的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/902
- 城市应急广播的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/stu
- 社区邻里服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/T4E
- 社区公共议事的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/848=ubk
- 数字支付体验的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/hyv=735
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/HP5=AmA
- 家庭志愿活动的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/532
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/csb
- 街区小店体验的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/oPm
- 公共服务评价的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/253=bac
- 城市微更新实践的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/dnw=874
- 居家适老化改造的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E9%A3%9F%E5%93%81?/o0E=Xt5
- 社区公共卫生的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/249
- 公益活动组织中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/kci
- 城市共享单车的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/Vr7
- 科学观察活动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/041=pfa
- 社区信息发布的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/kqj=914
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/Gcc=iR9
- 社区家校合作的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/059
- 社区便民集市的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/pxi
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/ZYM
- 青年职业探索的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/300=ula
- 家庭安全提示的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/byw=494
- 社区协商议事的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/3pr=aKB
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/703
- 灵活就业交流的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/hpk
- 旧物循环利用的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/QVe
- 消防知识宣传的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/575=rhu
- 社区庭院绿化的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/xoe=233
- 公共空间安全的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/sA2=XDD
- 户外活动组织的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/598
- 社区快递服务的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/fzf
- 机器人科普活动的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/BPy
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/412=yvd
- 社区公共餐饮的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/vmq=901
- 绿色消费选择的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/1bz=Zj2
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/501
- 城市公共自行车的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/iyj
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/6s3
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/674=gov
- 社区知识分享的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/sbk=192
- 公共图书馆服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/x4G=1ey
- 公共服务数字化的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/749
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/uam
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/EDr
- 社区安全巡查的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/931=pbf
- 社区教育资源的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/lsb=169
- 城乡交流活动的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/qNN=t0y
- 城市夜间照明的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/851
- 课后服务体验的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/tbn
- 食品配送体验的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/ICQ
- 社区菜市场服务的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/427=ppn
- 街区更新实践的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/efh=817
- 社区科普课堂的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/3QB=b1a
- 社区绿色空间的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/418
- 城市步行友好的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/zbm
- 节假日出行安排的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/A6g
- 社区阅读服务的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/008=uqo
- 农产品品牌传播的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/ilr=418
- 社区交通安全的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/8c3=vjL
- 家庭用电安全的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/946
- 生活垃圾回收的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/auq
- 小区停车协商的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/bQx
- 乡村公共文化的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/788=fem
- 电动汽车充电的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/lml=048
- 急救知识普及的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%88%9B%E6%8A%95?/zbO=XkU
- 农村环境治理的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/227
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/kua
- 生活垃圾减量的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/P0j
- 便民服务窗口的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/570=eja
- 社区应急准备的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/xdj=862
- 安全出行教育的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/tnP=FJ1
- 新能源出行的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/259
- 公益活动组织的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/typ
- 职业技能学习的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/Qin
- 气象科普传播的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/269=uqy
- 地方民俗记录的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/eah=534
- 生成式工具使用的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/Xx3=kBQ
- 志愿者培训交流的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/078
- 数字创意课程的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/qah
- 社区法律科普的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/TFY
- 小区电梯维护的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/771=spe
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/yfr=077
- 生成式工具使用的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/obR=7my
- 街区道路维护的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/737
- 社区垃圾回收的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/pex
- 家庭健康管理的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/gKm
- 社区互助网络的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/940=hwg
- 软件开发学习的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/ywb=928
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/zbI=lp6
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/792
- 智慧城市体验的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/xov
- 社区科普课堂的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/MgM
- 公共服务评价的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/902=zyd
- 数字素养提升的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/ary=106
- 基层健康档案的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/jrj=LQi
- 节能家电使用的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/482
- 社区手工活动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/mkk
- 社区生活指南的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/Dds
- 物业服务沟通的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/830=now
- 科普展览体验的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/joa=197
- 家庭节能设备的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/zpF=Ym8
- 城市应急广播的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/962
- 食品配送体验的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/ksk
- 通勤路线规划的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/R5v
- 公共卫生宣传的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/859=rkr
- 家庭阅读计划的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/kja=002
- 开源技术交流的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/zhY=QdU
- 老年运动活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%B9%90%E5%9B%AD-APP_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/462
- 公交站点体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%B9%90%E5%9B%AD-APP_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/kkf
- 低碳社区实践的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%B9%90%E5%9B%AD-APP_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/HMK
- 公共设施维护的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%B9%90%E5%9B%AD-APP_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/721=ruw
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%B9%90%E5%9B%AD-APP_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/abb=495
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E4%B9%90%E5%9B%AD-APP_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/tBN=frc
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/421
- 城市骑行环境的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/crf
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/WPt
- 无障碍信息设计的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/338=dnk
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/sly=840
- 社会体育指导的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E4%B9%90%E5%9B%AD-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/KRn=Zkj
- 数字素养提升的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/231
- 周末休闲规划的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/owa
- 社区读书角建设的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/oX4
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/581=fae
- 公共健身器材的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/buq=360
- 租房信息服务的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/esp=5Pw
- 绿色办公实践的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/434
- 电动汽车充电的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/wwe
- 消防知识宣传的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/EOy
- 老年数字阅读的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/011=kgg

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
