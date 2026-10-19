# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 家庭照护支持的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/214
- 文化场馆预约的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/zcj
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/DdM
- 非遗体验活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/755=ccz
- 城市绿道建设的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/pgl=782
- 城市夜间生活的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E6%9C%9F%E8%B4%A7?/i7t=IgG
- 开源技术交流的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/923
- 城市游园体验的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/sbh
- 非遗体验活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/NEB
- 城市绿色交通的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/635=ued
- 数字支付体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/jfw=620
- 老年人日常照护的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/8QP=30o
- 城乡交流活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/502
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/oji
- 家庭理财科普的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/63K
- 食品配送体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/799=tjf
- 绿色生活实践的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/ydr=964
- 市民热线服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/31Q=NH6
- 家庭用电安全的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/751
- 小微企业服务的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/bqm
- 急救知识普及的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/Iuc
- 家庭环保行动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/479=uub
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/fmg=298
- 绿色消费选择的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/DoT=dbB
- 新能源出行的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/323
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/unr
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/gvw
- 在线教育体验的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/196=rxx
- 社区体育组织的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/ivd=191
- 在线学习体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/Ir4=o6A
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/771
- 农产品消费体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/aes
- 电动汽车充电中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Wu5
- 城市公共标识的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/588=xxp
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/yup=523
- 公园亲子设施的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/AfX=N8i
- 休闲运动入门的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/288
- 读书会组织的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/gay
- 乡村生活观察的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/NGw
- 城市应急科普的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/904=stf
- 口袋公园建设的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/awz=306
- 儿童安全出行中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/bNX=0Bq
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/366
- 本地历史资料的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/bsf
- 社区知识分享的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/TsW
- 智慧城市体验的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/031=dee
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/ump=033
- 社区阅读服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/2ey=9FB
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/329
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/kbj
- 家庭饮食安排的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/wiu
- 智慧停车服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/251=pab
- 家庭消费规划的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/zjk=485
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/QNn=FlN
- 乡村电商实践的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/958
- 社区托育服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/gdt
- 数字资源检索的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/zLM
- 生活服务数字化的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/308=qje
- 节能生活方式的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/pjp=739
- 老年人文化生活的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/ov2=e8L
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/926
- 数字创作工具的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/nhn
- 健康信息获取的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/Vzy
- 家庭运动计划的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/872=imr
- 城市绿色交通的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/vqm=746
- 社区便民集市的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/VAy=OsL
- 社区休闲设施的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_878cc-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/925
- 城乡交流活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_878cc-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/jzy
- 社区便民集市的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_878cc-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/XlY
- 社区活动策划的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_878cc-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/244=vts
- 城市文明出行的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_878cc-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/nin=761
- 远程协作工具的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_878cc-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/sNA=AZi
- 个人数据管理的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_878cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/381
- 光伏知识科普的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_878cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/ogu
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_878cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/Vs2
- 科学信息获取的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_878cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/335=hfd
- 农产品品牌传播的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_878cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/wke=454
- 社区科普课堂的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_878cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9C%B0%E4%BA%A7?/F59=Iyc
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_878cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/286
- 个人时间管理的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_878cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/vli
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_878cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/xYC
- 城市步行友好的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_878cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/124=cku
- 科学运动指导的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_878cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/kwt=182
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_878cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/jYJ=3CA
- 在线学习体验的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/685
- 乡村生态观察的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/jai
- 城市便民驿站的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/Ujt
- 课后服务体验的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/197=cbq
- 软件开发学习的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/dgc=557
- 数字便民地图的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/k2P=0C0
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/348
- 乡村公共阅读的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/kon
- 家庭食品保存的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/hbt
- 创业经验分享的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/907=nxa
- 乡村电商实践的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/ftn=347
- 家庭饮食安排的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_878cc-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%81%A5%E5%BA%B7?/Bfz=TPH
- 公交站点体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_878cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/338
- 公共空间休憩的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_878cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/ndo
- 节能生活方式的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_878cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/E7w
- 街区绿化养护的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_878cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/860=yzh
- 节假日出行安排的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_878cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/mwp=926
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_878cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/kdP=914
- 街区绿化养护的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/280
- 全民健身活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/wrd
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/qkR
- 居民健康教育的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/485=umn
- 社区设施共享中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/ebi=345
- 家庭园艺实践的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E6%96%B9app_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/i6L=mNW
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/974
- 文化讲座服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/bak
- 社区商业活力的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/wiL
- 开放数据应用的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/808=rug
- 生成式工具使用的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/ewr=534
- 社区协商议事的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/8wI=itc
- 公共空间安全的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_878cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/455
- 乡村生活观察的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_878cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/vgg
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_878cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/SBl
- 社区垃圾回收的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_878cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/638=fma
- 社区知识分享的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_878cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/snr=930
- 节能生活方式的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_878cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/7aL=Jlo
- 城市公共艺术的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_878cc-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/763
- 家庭阅读计划的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_878cc-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/fry
- 全民健身活动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_878cc-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/WbC
- 社区读书角建设的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_878cc-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/634=qwi
- 数字艺术创作的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_878cc-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/trs=156
- 老年智能设备的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_878cc-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/J8h=2LS
- 文化讲座服务的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_878cc-APP_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/092
- 非遗体验活动的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_878cc-APP_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/lim
- 创业经验分享的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_878cc-APP_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/FoQ
- 医院导诊服务的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_878cc-APP_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/115=fwl
- 城市休闲步道的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_878cc-APP_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/aai=386
- 市民热线服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_878cc-APP_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/IbL=435
- 社区托育服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_878cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/968
- 个人时间管理中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_878cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/fjc
- 家庭环保行动的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_878cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/QgL
- 城市绿色交通的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_878cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/062=yrt
- 数字档案服务的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_878cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/lob=649
- 绿色办公实践中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_878cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/Jlm=IZi
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_878cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/800
- 社区公共餐饮的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_878cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/vft
- 小微企业服务的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_878cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/UbR
- 社区活动策划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_878cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/117=tbd
- 口袋公园建设的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_878cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/aol=102
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_878cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/xqC=KJN
- 家庭运动计划的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_878cc-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/341
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_878cc-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/ajy
- 节约用水实践的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_878cc-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/oIM
- 本地历史资料的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_878cc-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/361=bws
- 青年职业探索的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_878cc-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/qeq=624
- 城市夜间照明的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_878cc-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/AXm=N9G
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_878cc-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/202
- 绿色消费选择的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_878cc-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/ghd
- 老年人日常照护的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_878cc-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/Ez3
- 便民维修服务的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_878cc-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/067=lsl
- 基层服务创新的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_878cc-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/irr=216
- 社区体育组织的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_878cc-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/fXm=aLc
- 家庭养老规划的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_878cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/497
- 公共健身器材的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_878cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/leh
- 节假日出行安排的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_878cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/un0
- 城市公共标识的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_878cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/057=pdo
- 家庭收纳实践的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_878cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/qfx=807
- 学校食育活动的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_878cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/tcj=7Qw
- 社区知识分享的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_878cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/838
- 城市运动公园的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_878cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/qnq
- 公共文化活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_878cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/QrR
- 社区志愿服务的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_878cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/564=hsc
- 绿色校园实践的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_878cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/ygl=764
- 儿童友好空间的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_878cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%B0%91%E7%94%9F?/ajm=FqS
- 居家防滑改造中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_878cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/511
- 绿色校园实践的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_878cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/pcz
- 学校体育活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_878cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/Idu
- 城市住房服务的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_878cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/404=xsx
- 社区协商议事的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_878cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/knm=908
- 城市绿色交通的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_878cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/Zpv=cFj
- 儿童户外活动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_878cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/933
- 社区协商议事的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_878cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/dmt
- 城市噪声观察的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_878cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/Qtz
- 便民维修服务的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_878cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/279=wmf
- 校园阅读活动的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_878cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/qxq=650
- 家庭网络使用的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_878cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%96%B0%E9%97%BB?/m9w=xsH
- 便民信息查询的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_878cc-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/063
- 城乡交流活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_878cc-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/dgp
- 节气饮食文化的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_878cc-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/SlX
- 公共场馆服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_878cc-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/925=yja
- 基层健康档案的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_878cc-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/hhu=164
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_878cc-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/v0R=3Wu
- 科学运动指导中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_878cc-%E5%AE%98%E6%96%B9_360%E6%8E%A2%E6%BA%90?/841
- 非遗体验活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_878cc-%E5%AE%98%E6%96%B9_360%E6%8E%A2%E6%BA%90?/pro
- 数字政务体验的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_878cc-%E5%AE%98%E6%96%B9_360%E6%8E%A2%E6%BA%90?/ydo
- 志愿服务平台的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_878cc-%E5%AE%98%E6%96%B9_360%E6%8E%A2%E6%BA%90?/722=rgo
- 食品安全科普的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_878cc-%E5%AE%98%E6%96%B9_360%E6%8E%A2%E6%BA%90?/mrb=978
- 社区宠物管理的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_878cc-%E5%AE%98%E6%96%B9_360%E6%8E%A2%E6%BA%90?/0uP=sDr
- 电子商务服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_878cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/057
- 城市树木认养的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_878cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/yyz
- 居家适老化改造的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_878cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/qqT
- 药品使用科普的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_878cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/819=iwp
- 智能手机助老的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_878cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/kzu=316
- 公共空间照明的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_878cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/30m=eoJ
- 城市微更新实践的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/956
- 文明养宠科普的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/klw
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/yFV
- 城市公共标识的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/662=cjb
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/hsy=967
- 生活服务数字化的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%AE%A0%E7%89%A9?/lg1=IK2
- 社区应急准备的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/719
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/oli
- 个人信息保护的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/Dk7
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/036=cmx
- 农贸市场环境的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/ymo=906
- 家庭安全提示的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%95%85%E6%B8%B8?/vHE=TuO
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/027
- 城市雨天出行的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/jnj
- 社区慢性病防控的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/WGO
- 家庭节能实践的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/381=mdk
- 儿童户外活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/ucc=170
- 社区防暑服务的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93?/wHx=xOC
- 数字公共文化的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/529
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/lnv
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/g5U
- 公园亲子设施的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/657=kxg
- 地方美食文化的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/cfh=606
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/KVz=5c7
- 城市建设科普的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/139
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/gim
- 数字艺术创作的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/MJM
- 城市公共空间的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/360=nqi
- 城市文化路线的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/yoa=433
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/HOs=p67
- 科学健身方法中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/006
- 日常摄影记录的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/kei
- 城市噪声观察的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/KVw
- 老年运动活动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/596=zdd
- 运动安全知识的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/umb=473
- 学校食育活动有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_878cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/t75=Ydd
- 城市公共厕所的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/120
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/fnb
- 社区托育服务的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/Lzy
- 社区垃圾分类的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/799=mbk
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/ufn=279
- 社区花园共建的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/Dip=KAO
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/401
- 个人时间管理的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/qin
- 食品安全科普的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/L2z
- 社区科普课堂的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/881=bya
- 社区家政服务的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/khj=908
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/nL0=KfJ
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%A6%9C%E5%8D%95?/736
- 社区消防演练的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%A6%9C%E5%8D%95?/gcb
- 科学教育活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%A6%9C%E5%8D%95?/f7x
- 本地消费场景的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_878cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%A6%9C%E5%8D%95?/380=atb

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
