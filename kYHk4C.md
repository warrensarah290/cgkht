# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 小区停车协商的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA?/asr=510
- 城市体育设施中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA?/m1M=OaH
- 社区商业活力的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/152
- 校园安全教育的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/zes
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/P5e
- 智慧城市体验的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/916=egi
- 家庭安全提示的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/kpl=219
- 绿色办公实践的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/Vhi=muL
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/726
- 社区文化节活动的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/fup
- 数字素养提升的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/bnV
- 户外活动组织的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/525=jme
- 农业科普体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/cee=406
- 户外活动组织的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/k0i=nCK
- 生活垃圾减量的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/290
- 生活垃圾回收的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/wsq
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/bU5
- 消防知识宣传的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/600=dyz
- 社区消防演练的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/xsi=148
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/4cF=oWf
- 老年智能设备的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/650
- 智慧城市体验的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/bke
- 数字公共文化的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/MzU
- 农产品品牌传播的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/009=ukp
- 市民热线服务的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/xsk=225
- 社区庭院绿化的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/kcp=TgE
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_360%E6%B3%95%E6%B2%BB?/985
- 公共卫生宣传的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_360%E6%B3%95%E6%B2%BB?/mvs
- 街头绿植养护的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_360%E6%B3%95%E6%B2%BB?/uKY
- 公共服务咨询的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_360%E6%B3%95%E6%B2%BB?/981=pjf
- 社区交通安全的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_360%E6%B3%95%E6%B2%BB?/yfh=575
- 社区快递服务的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_360%E6%B3%95%E6%B2%BB?/FOC=SSk
- 社区共享书架的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/940
- 应急物资管理的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/usb
- 公共空间导览的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/MaD
- 节日文化体验的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/828=aui
- 青少年编程学习的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/pmn=222
- 社区商业活力的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/Q00=uUI
- 乡村公共服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/460
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/mlb
- 骑行路线规划的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/HRO
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/360=ejq
- 社区共享书架的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/qhg=670
- 地方民俗记录的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/apJ=sCN
- 数字创作工具的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/730
- 老年数字阅读的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/hpo
- 家庭节能设备的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/UZ5
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/731=ioz
- 儿童友好空间的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/emt=088
- 青少年户外教育的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/4t4=bTv
- 社区科普课堂的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/104
- 老年人出行服务的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/ndw
- 全民健身活动的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/ziC
- 社区家校合作的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/173=gde
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/ltt=512
- 城市公共自行车的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/HGF=fXm
- 本地旅行体验的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/063
- 创业经验分享的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/fsq
- 城市建设科普的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/wPU
- 城市便民驿站的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/739=qni
- 线上阅读资源的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/jqe=345
- 社区儿童活动的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E6%A5%BC%E5%B8%82?/glz=mao
- 青少年户外教育的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/033
- 骑行路线规划的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/rnr
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/F7w
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/005=fjb
- 社区文化节活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/djs=323
- 城市公共艺术的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/VIy=j1i
- 公共设施使用的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/063
- 绿色校园实践的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/ukj
- 气象科普传播的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/St9
- 家庭阅读计划的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/983=lcd
- 医院导诊服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/gcf=199
- 软件开发学习的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/R0K=vKI
- 社区协商议事的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/489
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/llc
- 数字支付体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/ToU
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/243=fre
- 儿童阅读角的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/naz=334
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/6gW=ztR
- 志愿者培训交流的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/159
- 社区活动策划的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/bpk
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/W08
- 社区绿色空间的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/900=zvw
- 城市绿道建设中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/rgz=777
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/1gz=FZb
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%AE%B6%E5%B1%85?/917
- 家庭网络使用的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%AE%B6%E5%B1%85?/euq
- 乡村公共文化的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%AE%B6%E5%B1%85?/L0P
- 通勤路线规划的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%AE%B6%E5%B1%85?/885=eaw
- 绿色建筑理念的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%AE%B6%E5%B1%85?/ory=700
- 亲子阅读活动的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%AE%B6%E5%B1%85?/6T8=aMS
- 公共交通接驳的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/679
- 图书馆活动策划的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/uab
- 公共空间照明的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/zqB
- 环境监测科普的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/479=mck
- 线上办事服务的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/xea=347
- 儿童运动体验的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/02g=kk4
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/004
- 数字创作工具的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/fab
- 周末休闲规划的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/Kob
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/342=kru
- 生活技能分享的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/wxn=672
- 城市文明出行的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/4nz=AE3
- 乡村公共文化的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/803
- 劳动教育实践的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/tbv
- 老年友好服务的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/AtE
- 城市公共标识的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/718=oql
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/jbd=314
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/0z2=oYn
- 家庭环保行动的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/052
- 社区快递服务的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/nxm
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/FxY
- 地方旅游导览的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/033=dde
- 社区法律科普的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/pbs=654
- 亲子科普活动的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/EoJ=MKy
- 节约用水实践的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/835
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/xxx
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/XhN
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/886=ihy
- 城市展览体验的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/ixz=807
- 社区商业活力的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A4%BE%E5%8C%BA?/26U=E5j
- 校园社团活动的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/650
- 社区阅读服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/lde
- 全民健身活动的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/XpG
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/593=ezn
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/niw=251
- 非遗课堂体验的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/N2U=LiU
- 地方民俗记录的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/391
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/aat
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/Z6g
- 环境教育课程的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/997=ngj
- 城市博物馆服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/vcm=163
- 城乡交通衔接的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E9%80%9A%E4%BF%A1?/SdD=y9P
- 应急物资管理的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/517
- 乡村文化空间的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/hlr
- 城市展览体验的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/wbI
- 社区生活指南的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/645=bap
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/slt=328
- 社区手工活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/Stb=nHn
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/436
- 绿色办公实践的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/mrq
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/ZNN
- 公交无障碍服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/148=vkw
- 社区防暑服务的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/blw=348
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/Zx6=TkV
- 城市公共座椅的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/189
- 儿童阅读角的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/gsg
- 便民服务地图的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/L4d
- 健康饮食教育的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/951=gwg
- 数字素养提升的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/cel=742
- 家庭防灾准备的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%8A%A8%E6%BC%AB?/XGd=mEU
- 社区儿童活动的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/009
- 文化场馆预约的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/vmx
- 公共服务咨询的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/Za8
- 公共卫生设施的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/941=mzt
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/mfp=964
- 社区便民集市的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/gzB=B2j
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/107
- 乡村文化活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/yyu
- 校园节能行动的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/Zgs
- 社区读书角建设的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/445=jhr
- 开放数据应用的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/etp=095
- 儿童户外活动的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/H40=Bdy
- 家庭节能设备的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/622
- 骑行路线规划的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/zpa
- 社区手工活动的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/vtr
- 乡村文化活动的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/119=rxo
- 租房信息服务的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/evj=016
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%8C%BB%E8%8D%AF?/tJC=N1r
- 城市雨天出行的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%8A%95%E8%B5%84?/459
- 环境教育课程的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%8A%95%E8%B5%84?/pjs
- 线上阅读资源的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%8A%95%E8%B5%84?/bwX
- 城市文明实践的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%8A%95%E8%B5%84?/386=vjm
- 青年职业探索的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%8A%95%E8%B5%84?/fop=162
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%8A%95%E8%B5%84?/gLN=omZ
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/519
- 乡村阅读空间的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/ana
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/Ixe
- 老年人出行服务的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/543=luq
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/zmt=770
- 社区文化节活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/UiR=uUO
- 数字设备回收的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/339
- 网络信息辨识的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/ozr
- 药品使用科普的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/Yn5
- 家庭收纳实践的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/509=iau
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/pir=968
- 城市微更新实践的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/UEW=5u6
- 社区快递服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/195
- 人工智能科普的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/xzc
- 城市社区治理的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/SgU
- 家庭健康管理的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/565=fjh
- 街区绿化养护中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/tzn=729
- 城市体育设施的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/TNe=Qmx
- 乡村文化活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/143
- 生成式工具使用的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/ked
- 家庭健康管理的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/a21
- 亲子科普活动的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/474=cet
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/hsa=282
- 青少年心理健康的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/B1p=WTB
- 家庭照护支持的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/106
- 节能生活方式的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/dte
- 社区健康讲座的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/1L9
- 青少年心理健康的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/868=ifj
- 生活服务数字化的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/sls=590
- 城市树木认养的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BC%80%E5%BF%83%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BA%BA%E7%89%A9?/u3D=sPC
- 市民热线服务的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/088
- 儿童户外活动的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/yde
- 公园休闲体验的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/zYs
- 社区菜市场服务的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/541=vsb
- 社区体育组织的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/ehd=572
- 老年数字阅读的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/WW1=FH7
- 租房信息服务的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%87%AF%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/121
- 家庭照护支持的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%87%AF%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/cru
- 劳动教育实践的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%87%AF%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/4J2
- 社区文化传播的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%87%AF%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/010=uap
- 老年人文化生活的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%87%AF%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/tmf=721
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%87%AF%E5%8F%91-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/8Uy=IAT
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/374
- 图书馆数字服务的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/gkc
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/MA2
- 物业服务沟通的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/235=tiw
- 生成式工具使用中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/amc=751
- 社区文化节活动的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%80%BA%E5%B8%82?/aQH=P33
- 科学观察活动的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%87%AF%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/424
- 公共文化活动的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%87%AF%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/hgr
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%87%AF%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/zmu
- 社区活动报名的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%87%AF%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/348=eok
- 社区科普课堂的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%87%AF%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/ugv=990
- 城市基础设施的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%87%AF%E5%8F%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/1fS=BdT
- 公共文化活动的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/416
- 居家适老化改造的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/ipz
- 地方文化传播的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/D8m
- 个人信息保护的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/441=mqr
- 城乡交通衔接的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/aob=272
- 城市农夫市集的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/xKe=0iN
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/156
- 公园休闲体验的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/yay
- 传统手工艺体验的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/Q9t
- 骑行路线规划的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/755=mlb
- 小区公共照明的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/sib=697
- 乡村生态观察的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%87%AF%E5%8F%91-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/iyn=Mad
- 家庭阅读计划的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/133
- 生活技能分享的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/hvl
- 青少年心理健康的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/KBv
- 社区教育资源的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/072=vee
- 生成式工具使用的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/lje=990
- 儿童安全出行的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%87%AF%E5%8F%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%AF%8D%E5%A9%B4?/wFi=vG8
- 社区便民集市的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%87%AF%E5%8F%91-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/529
- 城市文明实践的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%87%AF%E5%8F%91-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/tgi

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
