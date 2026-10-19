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

- 社区老年食堂的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/qbe=364
- 家庭节能设备的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/ADA=6Vl
- 节气饮食文化的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/419
- 城市步行友好的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/jjn
- 城市公共标识的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/fsC
- 居民健康教育的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/174=srb
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/kjf=142
- 社区阅读服务的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/rgR=mPm
- 公共图书馆服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/686
- 电动汽车充电的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/qsa
- 青年志愿活动的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/4PL
- 小区电梯维护的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/484=jpd
- 家庭园艺实践的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/fkd=453
- 家庭健康科普的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/jjJ=0Ot
- 社区运动空间的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/908
- 节日文化体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/wmp
- 青少年心理健康的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/O5Y
- 智能手机助老的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/382=hcb
- 公园休闲体验的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/bsl=452
- 智慧城市体验的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/CFb=pi7
- 老年运动活动的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/115
- 城市适老服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/pms
- 科技馆参观体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/g5V
- 公共设施维护的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/314=mnb
- 数字阅读服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/clc=126
- 街道综合服务的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/cCn=4V0
- 公共空间照明的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/674
- 城市建设科普的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/tth
- 社区邻里服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/YKr
- 家庭志愿活动的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/313=atk
- 便民维修服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/jns=514
- 街区小店体验的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/Ohw=hio
- 社区便民服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/497
- 本地旅行体验的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/jlj
- 个人信息保护的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/qux
- 乡村阅读空间的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/522=qbs
- 绿色快递包装的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/fhp=186
- 城市步行友好的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/KnZ=m5G
- 公共空间导览的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/136
- 个人时间管理中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/meg
- 公共空间安全的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/GIb
- 绿色消费选择的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/782=vff
- 传统节日科普的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/eum=229
- 城市游园体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/C2K=aGr
- 环境监测科普的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/664
- 校园节能行动的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/drb
- 城市基础设施的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/qOF
- 青少年科普实践的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/859=ngu
- 城市公共自行车的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/sov=718
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/DwS=fFQ
- 环境教育课程的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/207
- 城市农夫市集的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/apv
- 城市生活服务的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/TQ5
- 数字素养提升的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/558=ixd
- 学校食育活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/ols=994
- 城市骑行环境的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/gMq=2UQ
- 电子商务服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/049
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/bgu
- 公共服务咨询的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/XTE
- 非遗体验活动的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/028=ewz
- 学校体育活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/pcp=983
- 基层健康服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/E4d=lla
- 绿色建筑理念的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/457
- 社区儿童活动的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/quq
- 社区文化节活动的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/gIF
- 公共设施维护的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/247=usf
- 公共空间休憩的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/cjl=335
- 数字课堂应用的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/z0R=R7M
- 社区应急准备有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/685
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/piz
- 数字便民地图的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/yIE
- 社区便利生活的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/167=pbt
- 城市游园体验的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/ywp=458
- 城市雨天出行的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/75D=0In
- 安全出行教育的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/255
- 地方旅游导览的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/tey
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/UgE
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/619=blx
- 邻里共享空间的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/nie=627
- 城市公共标识的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/q54=Dx4
- 科学教育活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/423
- 社区科普课堂的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/nax
- 家庭急救准备的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/zE3
- 校园节能行动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/311=sai
- 社区健康讲座的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/qwm=071
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%AE%8F%E8%A7%82?/qi3=917
- 城市应急科普的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/565
- 数字学习资源的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/eem
- 校园阅读活动的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/5ed
- 安全出行教育的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/875=rxw
- 农村环境治理的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/ouf=067
- 家庭环保行动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/rC5=In2
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/435
- 社区艺术活动的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/whh
- 健康信息获取的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/Hi7
- 基层医疗预约的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/755=sxl
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/azi=835
- 骑行路线规划的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/8YI=FNu
- 数字资源检索的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/174
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/ukq
- 社区手工活动中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/7cm
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/501=flt
- 城市应急科普的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/doh=798
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/BSR=11i
- 城市生活服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/885
- 家庭安全提示的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/bim
- 城市慢行系统的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/PmR
- 社区垃圾分类的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/104=xvh
- 生成式工具使用的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/hsv=706
- 电子商务服务的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/WNU=ZF3
- 乡村公共文化的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/515
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/ebd
- 市民意见收集的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/NlY
- 居家防滑改造中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/807=hwf
- 家庭园艺实践的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/lmg=904
- 科学信息获取的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/PDF=PJg
- 公共空间休憩的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/640
- 社区快递服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/rrr
- 社区交通安全的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/wPT
- 老年数字阅读中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/342=qnn
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/obp=888
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/vPy=ezO
- 城市共享单车的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/391
- 社区心理支持的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/mio
- 开源技术交流的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/OrG
- 公共空间安全中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/426=mcq
- 老年智能设备的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/fbc=609
- 城乡公共服务的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/woh=SEl
- 地方民俗记录的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/374
- 读书会组织的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/rjn
- 城市步行友好的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/kHl
- 公园休闲体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/371=lry
- 社区便民服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/jfr=271
- 灵活就业交流的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/9gd=1Bv
- 便民服务窗口的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%97%B6%E8%AE%AF?/214
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%97%B6%E8%AE%AF?/vuh
- 社区停车服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%97%B6%E8%AE%AF?/6q4
- 城乡交通衔接的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%97%B6%E8%AE%AF?/490=rpj
- 家庭教育交流的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%97%B6%E8%AE%AF?/lel=739
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E6%97%B6%E8%AE%AF?/8Xo=SSx
- 数字学习资源的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/273
- 数字创作工具的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/ukn
- 家庭健康科普的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/7xH
- 公园亲子设施的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/415=fjm
- 社区共享书架的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/mcb=039
- 新能源出行的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E8%82%A1%E7%A5%A8?/fZP=eEo
- 开源技术交流的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/396
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/zkd
- 垃圾分类指导的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/enW
- 基层健康档案的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/266=kqy
- 社区信息发布的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/lhx=441
- 数字便民地图的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/1Pc=qr6
- 传统节日科普的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/981
- 校园节能行动的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/ohd
- 家庭防灾准备的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/VDs
- 低碳社区实践的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/811=haw
- 数字阅读服务的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/kvc=250
- 公共文化活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/11y=hqu
- 老年学习活动的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/405
- 地方文化传播的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/kiy
- 消防知识宣传的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/SMc
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/732=jdf
- 公共服务咨询的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/llb=104
- 公交无障碍服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/aNT=U01
- 乡村产业科普的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/699
- 健康饮水科普的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/qij
- 青年职业探索中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/E50
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/450=exw
- 图书借阅体验的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/qmc=940
- 地方旅游导览的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/zaG=ZJe
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9500-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/671
- 城市文明实践的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9500-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/wmq
- 居家适老化改造中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9500-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/syG
- 无障碍出行的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9500-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/273=hzf
- 社区教育资源的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9500-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/slb=487
- 旧物循环利用的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BD%A9500-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/nn9=2Rv
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/788
- 社区家校合作的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/dpb
- 网络信息辨识的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/eov
- 城市夜间照明的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/752=uaf
- 人工智能科普的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/nhv=801
- 口袋公园建设的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/nPh=q5A
- 街区绿化养护的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/198
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/kdh
- 小微企业服务的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/hWp
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/360=tat
- 生活服务数字化的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/hdo=793
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/LOY=0Ei
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/636
- 无障碍信息设计的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/xee
- 社区公共餐饮的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/2i5
- 数字设备回收的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/902=yal
- 城市生活服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/use=104
- 老年人文化生活的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/MCa=AUC
- 数字创意课程的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/084
- 健康信息获取的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/zig
- 社区协商议事的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/ZtQ
- 节能生活方式的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/139=isj
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/eby=853
- 城市人文观察的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/YNX=FlL
- 邻里互助活动的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/779
- 家庭运动计划的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/wnh
- 城市展览体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/yyd
- 家庭健康管理的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/038=eam
- 儿童阅读角的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/aul=733
- 城市绿道建设的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/Nvt=G3h
- 城市应急科普的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/960
- 个人数据管理的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/udp
- 校园社团活动的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/Q1k
- 社区老年食堂的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/181=ujw
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/bev=366
- 急救知识普及的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/s5a=P7D
- 社区修缮行动的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9500-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/356
- 校园阅读活动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9500-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/ahr
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9500-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/lMl
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9500-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/288=fpr
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9500-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/ivl=473
- 农产品消费体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9500-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%B8%E6%88%8F?/VN5=YhV
- 城市夜间生活的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/485
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/ysu
- 校园节能行动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/r2D
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/477=yow
- 社区养老服务的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/cpt=776
- 城市微更新实践的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9500-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/Lo7=SGx
- 社区教育资源的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/156
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/dvb
- 乡村电商实践的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/UnW
- 公共空间照明的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/022=zbw
- 信息无障碍体验的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/kid=784
- 老年友好服务的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BD%A9500-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/vHC=KpG
- 城市公共座椅的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9500-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/367
- 城市地名文化的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9500-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/kct
- 社区安全巡查的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9500-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/285
- 急救知识普及的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9500-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/435=eei
- 社区互助网络的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9500-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/qwr=046
- 校园节能行动的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9500-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/3NB=Jlq
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9500-APP_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/994
- 儿童户外活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9500-APP_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/ucv
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9500-APP_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/5hZ
- 劳动教育实践的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9500-APP_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/819=ptl
- 居民健康教育中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9500-APP_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/uwa=963
- 地方文化传播的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9500-APP_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/lAq=qo1
- 医院导诊服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/857
- 地方旅游导览从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/gmr
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/J5E
- 运动安全知识的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/024=jzl
- 小微企业服务的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/jzt=627
- 公共服务沟通的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9500-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/b4L=feu
- 文明养宠科普的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9500-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/534
- 老年人文化生活的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9500-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/kqk

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
