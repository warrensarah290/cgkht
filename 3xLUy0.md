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

- 网络信息辨识的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_pk10%E7%8E%A9%E6%B3%95%E7%BB%9D%E6%8B%9B_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/Wde
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_pk10%E7%8E%A9%E6%B3%95%E7%BB%9D%E6%8B%9B_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/231=hit
- 公园亲子设施的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_pk10%E7%8E%A9%E6%B3%95%E7%BB%9D%E6%8B%9B_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/iwa=930
- 农贸市场环境的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_pk10%E7%8E%A9%E6%B3%95%E7%BB%9D%E6%8B%9B_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/nd8=EZk
- 电动汽车充电的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/660
- 低碳社区实践的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/aib
- 科学教育活动的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/fPr
- 绿色生活实践的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/102=wtr
- 数字设备回收的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/mkl=093
- 社区艺术活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E7%85%A7%E8%A1%A8_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/0Be=L8m
- 传统节日科普的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/235
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/riz
- 社区垃圾回收的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/R37
- 社区活动策划的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/155=zbq
- 城市公共厕所的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/uvq=367
- 农产品品牌传播的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A11%E6%BC%8F%E6%B4%9E%E8%AF%A6%E7%BB%86%E8%A7%A3%E6%9E%90_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/HDQ=67O
- 公共空间休憩的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/875
- 开源技术交流的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/sji
- 公交无障碍服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/oeU
- 家庭用电安全的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/909=fzk
- 信息无障碍体验的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/nzq=261
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E4%B8%83%E7%A0%81%E4%B8%80%E6%9C%9F%E5%B9%B3%E5%88%B7%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/CAB=l4s
- 日常摄影记录的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/143
- 校园社团活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/jvm
- 家庭健康管理的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/HgO
- 乡村生态观察的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/843=dws
- 数字政务体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/xgf=371
- 农村环境治理的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E6%95%99%E7%A8%8B_%E8%B1%86%E7%93%A3%E5%81%A5%E5%BA%B7?/S7U=6P8
- 社区活动空间的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/028
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/was
- 人工智能科普的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/sns
- 社区设施共享的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/750=tdp
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/ruq=025
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/dks=SDU
- 全民健身活动的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/054
- 城市生活服务的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/yzz
- 通勤路线规划的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/Hjo
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/560=pvr
- 数字档案服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/tud=882
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%AE%A1%E7%AE%97%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/LyQ=iz8
- 家庭照护支持的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/731
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/jfc
- 乡村电商实践的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/z36
- 数字档案服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/391=vgh
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/uqz=225
- 开放数据应用的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/4MP=kzo
- 社区环保活动的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/215
- 地方美食文化的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/fyg
- 骑行路线规划的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/8Jx
- 社区商业活力的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/830=qzx
- 家庭收纳实践的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/jkw=225
- 数字便民地图的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC11%E7%AE%97%E5%B0%8F%E5%A5%97%E5%88%A9_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/zYy=TEC
- 数字艺术创作的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/230
- 城市空气科普的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/jpm
- 跨代沟通活动的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/sMK
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/242=gqi
- 城市公共自行车的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/paw=450
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/qox=O1o
- 课后服务体验的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/399
- 日常摄影记录中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/vvb
- 低碳社区实践中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/geJ
- 社区宠物管理的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/695=slc
- 儿童阅读角的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/mgt=991
- 城市公共厕所的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%85%A8%E5%A4%A9pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%A0%B4%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/AXA=iMw
- 绿色校园实践的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/862
- 节能家电使用的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/rmm
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/dYL
- 社会体育指导的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/466=hrg
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/hwn=125
- 城市慢行系统的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%8A%95%E8%B5%84?/3oq=7SQ
- 乡村生态观察的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/352
- 社区活动策划的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/gyo
- 应急物资管理的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/aMi
- 街区绿化养护的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/620=gfj
- 数字阅读服务的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/kve=757
- 社区老年食堂的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E5%AF%B9%E5%88%B7%E6%80%8E%E4%B9%88%E6%8A%95%E6%B3%A8_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/7Sv=fXA
- 家庭理财科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/881
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/ewq
- 城市基础设施的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/46s
- 乡村教育资源的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/015=pit
- 老年人文化生活的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/wxb=015
- 家庭食品保存的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%A4%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%B9%E6%89%93%E5%A5%97%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/QvL=1lQ
- 公共服务数字化的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/210
- 家庭安全提示的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/jjh
- 城市空气科普的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/ZED
- 数字地图应用的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/247=toy
- 城市空气科普的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/wcl=266
- 家庭阅读计划的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E9%BE%99%E8%99%8E%E6%80%8E%E4%B9%88%E4%B8%8B%E8%B5%A2%E6%A6%82%E7%8E%87%E5%A4%A7_%E8%99%8E%E6%89%91%E5%AE%B6%E7%94%B5?/0Eb=d4h
- 数字设备回收的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/710
- 社区活动策划的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/arj
- 网络信息辨识的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/XLN
- 数字艺术创作的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/946=mzs
- 社区活动报名的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/ouy=403
- 居民健康教育的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%E8%87%B319%E5%85%A8%E5%8C%85%E6%B3%95_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/fO6=yeL
- 职业技能学习的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/482
- 城市社区治理的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/ejr
- 城市可持续生活的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/IHu
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/077=yqt
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/jap=346
- 地方旅游导览的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/Gki=krJ
- 创业经验分享的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/713
- 社区生活指南中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/oqk
- 城市应急广播的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/uYq
- 健康饮水科普的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/471=lnv
- 数字支付体验的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/quy=278
- 家庭饮食安排的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/bwM=U2A
- 基层健康服务的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/301
- 城乡公共服务的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/usa
- 城市公共厕所的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/mBG
- 城乡公共服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/657=nzh
- 社区安全巡查的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/mut=757
- 城市噪声观察的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E4%BB%A5%E4%B8%8A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/5UQ=qib
- 文化讲座服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/912
- 农产品消费体验的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/ytq
- 公共服务评价的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/NRW
- 社区修缮行动的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/003=pzf
- 数字学习资源的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/jhr=271
- 亲子科普活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/3Lz=Qzb
- 职业技能学习的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/238
- 社区便利生活的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/ich
- 公共服务沟通的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/m6C
- 社区共享书架的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/708=xsd
- 乡村阅读活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/zor=992
- 家庭防灾准备的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88_%E8%84%89%E8%84%89%E6%9C%8D%E9%A5%B0?/Nay=W6Y
- 公共空间休憩的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/604
- 校园阅读活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/hhx
- 社区文化传播的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/cxW
- 社区便利生活的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/079=wec
- 城市骑行环境的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/rqj=935
- 城市运动公园的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/gQG=e8X
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/059
- 学校食育活动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/zoj
- 公共空间照明的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/VcX
- 老年智能设备的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/463=iku
- 公共空间照明的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/sew=124
- 日常摄影记录的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B__%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/Frt=j0P
- 在线学习体验的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/823
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/lyz
- 校园节能行动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/P7A
- 城市游园体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/852=rrj
- 创业经验分享的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/ikb=083
- 数字档案服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%89%E5%87%A0%E7%A7%8D%E7%BB%84%E5%90%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/K2i=1A5
- 城市住房服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/451
- 图书馆活动策划的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/dad
- 城市农夫市集的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/MO9
- 数字资源检索的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/740=spt
- 健康饮水科普的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/rxa=933
- 地方美食文化的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%9C%BA%E7%90%86_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/qcC=ybp
- 个人信息保护的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/332
- 城市住房服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/wtk
- 志愿服务平台的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/tIx
- 创业经验分享的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/340=dpz
- 公共文化活动的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/ugo=264
- 社区托育服务的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%97%B6%E9%97%B4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/3TE=KEz
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/787
- 户外活动组织的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/odz
- 街区绿化养护的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/8MH
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/151=hvf
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/xmj=970
- 农产品消费体验从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%AF%8D%E5%A9%B4?/J7A=IdC
- 文化讲座服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.85%E4%BB%A5%E4%B8%8A%E7%9A%84%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/299
- 社区应急准备的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.85%E4%BB%A5%E4%B8%8A%E7%9A%84%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/hde
- 物业服务沟通的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.85%E4%BB%A5%E4%B8%8A%E7%9A%84%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/Jgs
- 家庭消费规划的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.85%E4%BB%A5%E4%B8%8A%E7%9A%84%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/593=fqe
- 家庭志愿活动的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.85%E4%BB%A5%E4%B8%8A%E7%9A%84%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/fdu=615
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC1.85%E4%BB%A5%E4%B8%8A%E7%9A%84%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/2H5=q1i
- 地方旅游导览的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC2.38%E4%BB%A5%E4%B8%8A%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/991
- 线上办事服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC2.38%E4%BB%A5%E4%B8%8A%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/elr
- 社区消防演练的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC2.38%E4%BB%A5%E4%B8%8A%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/SQC
- 数字生活课堂的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC2.38%E4%BB%A5%E4%B8%8A%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/260=ysc
- 在线教育体验的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC2.38%E4%BB%A5%E4%B8%8A%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/mna=596
- 科学观察活动的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC2.38%E4%BB%A5%E4%B8%8A%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%9B%86?/w2Z=54R
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/589
- 基层健康档案的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/eqs
- 智慧停车服务的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/nqb
- 城市地名文化的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/176=zaa
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/ezd=126
- 家庭节能实践的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%A4%BE%E8%AE%BA?/bPG=xnM
- 社区交通安全的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88%E7%8E%A9%E7%9A%84_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/856
- 乡村文化活动的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88%E7%8E%A9%E7%9A%84_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/mta
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88%E7%8E%A9%E7%9A%84_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/wzu
- 城市公共空间的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88%E7%8E%A9%E7%9A%84_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/235=fxy
- 亲子阅读活动的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88%E7%8E%A9%E7%9A%84_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/aef=968
- 城市可持续生活的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%98%AF%E4%BB%80%E4%B9%88%E7%8E%A9%E7%9A%84_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/qZi=85T
- 老年智能设备中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E6%89%93%E9%83%BD%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/899
- 数字创意课程的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E6%89%93%E9%83%BD%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ykv
- 城市慢行系统的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E6%89%93%E9%83%BD%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/pI1
- 社区设施共享的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E6%89%93%E9%83%BD%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/219=sov
- 数字支付体验的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E6%89%93%E9%83%BD%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ynd=643
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E6%89%93%E9%83%BD%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/bUl=8xb
- 节日文化体验的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B4%B4%E5%90%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/881
- 城市雨天出行的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B4%B4%E5%90%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/goz
- 全民健身活动的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B4%B4%E5%90%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/alC
- 城市绿道建设的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B4%B4%E5%90%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/562=ile
- 城市噪声观察的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B4%B4%E5%90%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/oya=826
- 乡村公共文化中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B4%B4%E5%90%A7_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/ES9=OXg
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/498
- 城市绿色交通的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/afh
- 公园无障碍服务的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/TP7
- 生活技能分享的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/515=opt
- 家庭网络使用的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/rcg=997
- 家庭养老规划的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F1.9%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/wrp=Vee
- 社区读书角建设的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/878
- 城市共享单车的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/vuk
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/pA8
- 社区信息发布的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/028=kno
- 老年友好服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/aaf=202
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%89%93%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/T0k=hnJ
- 非遗体验活动的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/789
- 城市微更新实践的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/lmy
- 本地消费场景的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/wkt
- 家庭科学教育的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/803=uyf
- 公益活动组织的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/pbv=344
- 应急物资管理的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/3f4=DTn
- 城市步行环境的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/852
- 生活服务数字化的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/fbd
- 电动汽车充电的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/g9L
- 家庭健康管理的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/354=jve
- 街道综合服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/drw=158
- 健康饮水科普的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/dz5=8zn
- 非遗课堂体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%B9%E5%8F%8C%E5%A5%97%E5%88%A9_%E5%8D%B3%E5%88%BB%E6%B6%88%E8%B4%B9?/108
- 公共健身器材的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%B9%E5%8F%8C%E5%A5%97%E5%88%A9_%E5%8D%B3%E5%88%BB%E6%B6%88%E8%B4%B9?/nzu
- 居家适老化改造的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%B9%E5%8F%8C%E5%A5%97%E5%88%A9_%E5%8D%B3%E5%88%BB%E6%B6%88%E8%B4%B9?/TF1
- 节能生活方式的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%B9%E5%8F%8C%E5%A5%97%E5%88%A9_%E5%8D%B3%E5%88%BB%E6%B6%88%E8%B4%B9?/757=xgm
- 社区手工活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%B9%E5%8F%8C%E5%A5%97%E5%88%A9_%E5%8D%B3%E5%88%BB%E6%B6%88%E8%B4%B9?/bkl=188
- 数字公共文化的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%B9%E5%8F%8C%E5%A5%97%E5%88%A9_%E5%8D%B3%E5%88%BB%E6%B6%88%E8%B4%B9?/gz9=srI
- 急救知识普及的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%95%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/134
- 周末休闲规划的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%95%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/vif
- 食品安全科普的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%95%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/OhT
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%95%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/785=xji
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%95%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/yps=680
- 通勤路线规划的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%95%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/RET=6UR
- 城乡交通衔接的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E8%B0%81%E6%9C%89%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.9%E5%80%8D%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/106
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E8%B0%81%E6%9C%89%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.9%E5%80%8D%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/kah
- 乡村教育资源的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E8%B0%81%E6%9C%89%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.9%E5%80%8D%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/YHt
- 绿色消费选择中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E8%B0%81%E6%9C%89%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.9%E5%80%8D%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/238=ful
- 老年人出行服务的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E8%B0%81%E6%9C%89%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.9%E5%80%8D%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/dpn=706
- 乡村教育资源的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E8%B0%81%E6%9C%89%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%B0%8F%E5%8D%951.9%E5%80%8D%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/ZFY=R9N
- 地方民俗记录的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%8D%95%E5%B0%8F2%E5%80%8D_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/802
- 社区家政服务的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%8D%95%E5%B0%8F2%E5%80%8D_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/znl
- 软件开发学习的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%8D%95%E5%B0%8F2%E5%80%8D_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/qFJ
- 网络信息辨识中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%8D%95%E5%B0%8F2%E5%80%8D_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/157=cxg
- 公交站点体验的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%8D%95%E5%B0%8F2%E5%80%8D_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/hio=857
- 数字创作工具的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%8D%95%E5%B0%8F2%E5%80%8D_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/OxZ=aSF
- 数字资源检索中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/002
- 社区养老服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/ime
- 老年运动活动的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/HiL
- 社区公共议事的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/463=hmp
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/szl=410
- 节能家电使用的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E8%BE%9F%E8%B0%A3?/4S2=6Id

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
