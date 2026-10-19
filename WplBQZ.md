# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 数字创作工具的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%93%AA%E9%87%8C%E7%8E%A9%E4%BF%A1%E8%AA%89%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/OnV
- 城市骑行环境的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%93%AA%E9%87%8C%E7%8E%A9%E4%BF%A1%E8%AA%89%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/158=lkt
- 社区生活指南的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%93%AA%E9%87%8C%E7%8E%A9%E4%BF%A1%E8%AA%89%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/ekq=562
- 课后服务体验的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%93%AA%E9%87%8C%E7%8E%A9%E4%BF%A1%E8%AA%89%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/aQM=PtI
- 绿色校园实践的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/684
- 城市展览体验的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/gim
- 全民阅读推广的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/ghk
- 本地历史资料的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/036=ndw
- 劳动教育实践的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/iwt=707
- 城市生活服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/Nfy=btv
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%89%BE%E4%BF%A1%E8%AA%89%E8%B5%9B%E8%BD%A6%E7%BE%A4_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/516
- 终身学习资源的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%89%BE%E4%BF%A1%E8%AA%89%E8%B5%9B%E8%BD%A6%E7%BE%A4_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/eaa
- 新能源知识普及的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%89%BE%E4%BF%A1%E8%AA%89%E8%B5%9B%E8%BD%A6%E7%BE%A4_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/nXd
- 乡村生活观察的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%89%BE%E4%BF%A1%E8%AA%89%E8%B5%9B%E8%BD%A6%E7%BE%A4_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/278=cbq
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%89%BE%E4%BF%A1%E8%AA%89%E8%B5%9B%E8%BD%A6%E7%BE%A4_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/wvk=500
- 社区便民服务的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%89%BE%E4%BF%A1%E8%AA%89%E8%B5%9B%E8%BD%A6%E7%BE%A4_36%E6%B0%AA%E5%9B%BE%E9%89%B4?/EVe=KIs
- 城市公共标识的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E7%BE%A4_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/934
- 城市建设科普的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E7%BE%A4_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/rsc
- 城市便民驿站的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E7%BE%A4_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/V7i
- 街区更新实践的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E7%BE%A4_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/008=jsz
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E7%BE%A4_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/yvt=383
- 学校食育活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E7%BE%A4_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/QJE=nlD
- 公共空间休憩的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%85%AC%E4%BC%97%E5%8F%B7%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/654
- 校园社团活动的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%85%AC%E4%BC%97%E5%8F%B7%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/lxt
- 科学教育活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%85%AC%E4%BC%97%E5%8F%B7%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/VB9
- 社区手工活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%85%AC%E4%BC%97%E5%8F%B7%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/316=exv
- 城市适老服务的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%85%AC%E4%BC%97%E5%8F%B7%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/mec=200
- 社区知识分享的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%85%AC%E4%BC%97%E5%8F%B7%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%93%94%E5%93%A9%E6%B8%AF%E8%82%A1?/3px=ykS
- 个人时间管理的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/950
- 老旧小区改造的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/xpv
- 城市住房服务中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/os4
- 数字艺术创作的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/707=wqc
- 家庭用电安全中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/qrv=073
- 社区商业活力的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/xd4=6NB
- 街区道路维护的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E4%B8%80%E4%B8%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/613
- 基层健康服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E4%B8%80%E4%B8%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/aqs
- 社区养老服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E4%B8%80%E4%B8%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/xjc
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E4%B8%80%E4%B8%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/722=uqk
- 乡村公共阅读的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E4%B8%80%E4%B8%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/wps=448
- 生活服务数字化的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E4%B8%80%E4%B8%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/yRb=fkU
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_360%E7%9B%98%E7%82%B9?/205
- 家庭照护支持的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_360%E7%9B%98%E7%82%B9?/hmx
- 社区庭院绿化的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_360%E7%9B%98%E7%82%B9?/T5O
- 数字资源检索的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_360%E7%9B%98%E7%82%B9?/605=cpp
- 乡村文化空间的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_360%E7%9B%98%E7%82%B9?/yhz=744
- 农村环境治理的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_360%E7%9B%98%E7%82%B9?/Fyi=L3s
- 城市骑行环境的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%BF%A1%E8%AA%89%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/221
- 公共卫生设施的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%BF%A1%E8%AA%89%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/tsb
- 校园阅读活动的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%BF%A1%E8%AA%89%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/eRI
- 社区儿童活动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%BF%A1%E8%AA%89%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/539=cxm
- 公共场所导视的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%BF%A1%E8%AA%89%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/tks=266
- 地方文化传播的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E4%BF%A1%E8%AA%89%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/q07=KbI
- 城市文明出行的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/385
- 就业技能培训的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/vin
- 家庭食品保存的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/qpU
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/866=zxg
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/wyb=445
- 居民健康教育的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/hEB=hsM
- 公共空间照明的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/695
- 通勤路线规划的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/zua
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/XxI
- 安全出行教育的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/320=fnm
- 社区生活指南的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/tzm=073
- 社区学习活动的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%8C%97%E4%BA%ACpk%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/48C=F4y
- 城市生活记录的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%8C%97%E4%BA%ACpk10%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/997
- 社区学习活动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%8C%97%E4%BA%ACpk10%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/jjv
- 社区文化节活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%8C%97%E4%BA%ACpk10%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/M9t
- 城市慢行系统的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%8C%97%E4%BA%ACpk10%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/981=bur
- 社区绿色空间的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%8C%97%E4%BA%ACpk10%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/qjw=027
- 乡村公共阅读的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%8C%97%E4%BA%ACpk10%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E6%89%98?/2kL=NjY
- 光伏知识科普的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%8C%97%E4%BA%ACpk10%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/196
- 地方戏曲体验的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%8C%97%E4%BA%ACpk10%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/mtb
- 健康步道使用的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%8C%97%E4%BA%ACpk10%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/w7B
- 公共空间休憩的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%8C%97%E4%BA%ACpk10%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/440=kte
- 社区协商议事的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%8C%97%E4%BA%ACpk10%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/gig=685
- 城市文化路线的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%8C%97%E4%BA%ACpk10%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/KuH=xYx
- 农贸市场环境的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/856
- 城市步行环境的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/dxf
- 老年数字阅读的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/sQr
- 城市骑行环境的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/958=wdc
- 城市便民驿站的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/tfi=055
- 社区活动报名的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/iyH=Tqj
- 城市公共自行车的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9Fpk10%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/159
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9Fpk10%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/tie
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9Fpk10%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/4x7
- 在线学习体验的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9Fpk10%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/993=yzk
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9Fpk10%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/ejr=042
- 机器学习入门的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9Fpk10%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/xul=Ch1
- 邻里互助活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/991
- 家庭安全提示的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/lqb
- 数字地图应用的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/a3l
- 职业技能学习的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/047=ydf
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/eza=846
- 在线教育体验的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpk10%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/Fza=jhP
- 科学运动指导的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/709
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/xsd
- 社区安全巡查的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/q7m
- 线上办事服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/790=ulr
- 智慧停车服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/ifr=368
- 在线学习体验的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/WcM=UBd
- 公交无障碍服务的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9Fpk10%E5%AE%9A%E4%BD%8D%E8%83%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/425
- 城市适老服务的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9Fpk10%E5%AE%9A%E4%BD%8D%E8%83%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/cym
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9Fpk10%E5%AE%9A%E4%BD%8D%E8%83%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/orG
- 图书借阅体验的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9Fpk10%E5%AE%9A%E4%BD%8D%E8%83%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/966=bpp
- 非遗体验活动的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9Fpk10%E5%AE%9A%E4%BD%8D%E8%83%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/cth=542
- 全民健身活动的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9Fpk10%E5%AE%9A%E4%BD%8D%E8%83%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/Dd5=A7W
- 小区公共照明的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9Fpk10%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/081
- 青少年心理健康的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9Fpk10%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/diy
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9Fpk10%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/EzU
- 食品配送体验的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9Fpk10%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/636=fce
- 青年就业服务的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9Fpk10%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/wob=853
- 农贸市场环境的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9Fpk10%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%B9%B6%E8%B4%AD?/h2f=eo5
- 居家防滑改造的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/617
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/lhf
- 城市慢行系统的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/F9H
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/088=gvf
- 消防知识宣传的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/uqi=830
- 公益活动组织的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9Fpk10%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/D2y=dzw
- 城市社区治理的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2%E6%9E%81%E9%80%9Fpk10_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/326
- 地方戏曲体验的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2%E6%9E%81%E9%80%9Fpk10_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/ymf
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2%E6%9E%81%E9%80%9Fpk10_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/isU
- 社区防暑服务的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2%E6%9E%81%E9%80%9Fpk10_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/740=dez
- 社会体育指导的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2%E6%9E%81%E9%80%9Fpk10_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/xmx=416
- 家庭消费规划的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%BC%98%E9%85%B7%E4%BD%93%E8%82%B2%E6%9E%81%E9%80%9Fpk10_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/a3E=KT3
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/165
- 课后服务体验的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/mvd
- 城市公共标识的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/2Hj
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/880=csh
- 公园无障碍服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/mwj=828
- 城市公共空间的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/xGK=hZs
- 城市运动公园的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_pk10%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/560
- 社区活动报名的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_pk10%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/mke
- 社区互助网络的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_pk10%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/AWz
- 通勤路线规划的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_pk10%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/951=ori
- 公共空间照明的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_pk10%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/vmh=104
- 骑行路线规划的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_pk10%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/gjM=dl3
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/548
- 传统节日科普的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/gmn
- 环境教育课程的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/vbe
- 社区活动策划的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/530=hwn
- 环境监测科普的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/tua=659
- 小区停车协商的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/VZI=1ll
- 邻里共享空间的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/444
- 街头绿植养护的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/ymf
- 儿童户外活动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/rpr
- 儿童运动体验的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/108=gvl
- 社区活动策划的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/lbb=744
- 便民信息查询的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/nEe=3as
- 城市建设科普的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E4%B8%80%E5%88%86%E9%92%9F_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/629
- 安全出行教育的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E4%B8%80%E5%88%86%E9%92%9F_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/edy
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E4%B8%80%E5%88%86%E9%92%9F_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/D6M
- 邻里共享空间的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E4%B8%80%E5%88%86%E9%92%9F_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/094=rzc
- 城市住房服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E4%B8%80%E5%88%86%E9%92%9F_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/fvw=439
- 城市体育设施的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E4%B8%80%E5%88%86%E9%92%9F_%E8%8A%92%E6%9E%9C%E8%AE%B2%E5%9D%9B?/m5N=ucl
- 城市夜间照明的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/961
- 城市社区治理的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/knx
- 公交站点体验的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/8g7
- 科学观察活动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/938=zbr
- 城市可持续生活的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/jwb=068
- 公共空间休憩的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/4Xc=AcX
- 智能手机助老的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90pk10%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/123
- 骑行路线规划的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90pk10%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/elo
- 青少年科普实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90pk10%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/hST
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90pk10%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/749=dmw
- 科学信息获取的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90pk10%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/kzj=110
- 家庭科学教育的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90pk10%E4%B8%A4%E6%9C%9F%E5%BF%85%E4%B8%AD_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/nju=NE3
- 城市地名文化的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/928
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/orr
- 市民意见收集的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/myr
- 物业服务沟通的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/193=xlk
- 节能家电使用的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/gvr=713
- 旧物循环利用的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/LZz=zLx
- 老旧小区改造的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/889
- 社区便利生活的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/kdb
- 节日文化体验的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/JoC
- 社区体育组织的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/127=zgs
- 公共场馆服务的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/gvg=830
- 小区电梯维护的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/FiF=MQR
- 便民维修服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90pk10%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_360%E6%B3%95%E6%B2%BB?/952
- 亲子科普活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90pk10%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_360%E6%B3%95%E6%B2%BB?/cqc
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90pk10%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_360%E6%B3%95%E6%B2%BB?/tph
- 青少年科普实践的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90pk10%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_360%E6%B3%95%E6%B2%BB?/691=inu
- 食品安全科普的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90pk10%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_360%E6%B3%95%E6%B2%BB?/mrf=154
- 数字生活课堂的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90pk10%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_360%E6%B3%95%E6%B2%BB?/VOg=XxM
- 家庭阅读计划的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/638
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/yru
- 科学教育活动的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/s61
- 青年职业探索的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/389=qoi
- 医院导诊服务的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/mtk=914
- 个人信息保护的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90pk10%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/r7I=7zx
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90pk10%E5%89%8D%E5%9B%9B%E7%A0%81%E7%8E%A9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/571
- 健康饮水科普的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90pk10%E5%89%8D%E5%9B%9B%E7%A0%81%E7%8E%A9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/vzw
- 社区邻里服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90pk10%E5%89%8D%E5%9B%9B%E7%A0%81%E7%8E%A9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/xWL
- 城市夜间照明的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90pk10%E5%89%8D%E5%9B%9B%E7%A0%81%E7%8E%A9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/572=zvm
- 远程协作工具的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90pk10%E5%89%8D%E5%9B%9B%E7%A0%81%E7%8E%A9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/nbq=890
- 公共文化活动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90pk10%E5%89%8D%E5%9B%9B%E7%A0%81%E7%8E%A9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/Kr6=omq
- 社区互助网络的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/983
- 街道综合服务的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/kxj
- 社区运动空间的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/szw
- 城市夜间生活的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/902=nyc
- 节约用水实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/eka=310
- 亲子科普活动的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90pk10%E7%8E%A9%E6%B3%95_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/I36=T8E
- 乡村阅读空间的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/083
- 社区托育服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/nxz
- 城市公共厕所的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/mht
- 城市绿道建设的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/496=imc
- 家庭健康管理的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/mzt=660
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/SgR=Tuq
- 环境教育课程的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/414
- 社区文化传播中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/fhp
- 社区设施共享的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/7GK
- 智慧城市体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/883=vxt
- 居民健康教育的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/gav=233
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/Yij=Su3
- 邻里互助活动的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%9C%8B%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/757
- 新能源出行的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%9C%8B%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/mwc
- 绿色消费选择的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%9C%8B%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/5Mb
- 城市生活记录的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%9C%8B%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/439=fdk
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%9C%8B%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/vil=425
- 创业经验分享的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%9C%8B%E7%A0%81%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/w4F=Smt
- 社区修缮行动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/116
- 城乡交流活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/otc
- 城市社区治理的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/x7G
- 社区活动策划中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/131=gcb
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/edf=646
- 图书借阅体验的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%83%E7%A0%81%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/zMp=Ud3
- 节能生活方式的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/450
- 数字创意课程的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/ixa
- 儿童安全出行的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/8rv
- 城市树木认养的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/446=sqr
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/oci=571
- 小微企业服务的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/xJd=Gqc
- 社区便民服务的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/451
- 家庭收纳实践的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/our
- 老年数字阅读的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/DSQ
- 街区更新实践的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/836=pti
- 消防知识宣传的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/prl=925
- 地方民俗记录的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/XZC=CJr
- 儿童友好空间的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/259
- 社区交通安全的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/nyz
- 绿色校园实践的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/iiX
- 老年学习活动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/840=qzc
- 绿色建筑理念的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/xgj=422
- 老年人出行服务的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/njq=BEh
- 家庭消费规划的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/679
- 生活垃圾减量的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/kep
- 基层健康服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/y23
- 社区知识分享的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/648=bjy
- 街道综合服务的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/hsh=613
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%86%A0%E4%BA%9A%E5%92%8C%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/JDP=KZI

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
