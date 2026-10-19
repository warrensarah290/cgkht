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

- 老年友好服务的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/917
- 信息无障碍体验的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/gik
- 邻里互助活动的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/cLK
- 城市社区治理的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/249=fzf
- 节能家电使用的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/sii=308
- 数字课堂应用的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/hiW=UtH
- 周末休闲规划的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A500_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/449
- 节气饮食文化的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A500_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/dkq
- 街区小店体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A500_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/dop
- 亲子科普活动的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A500_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/384=yra
- 青年志愿活动的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A500_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/uah=489
- 社区便利生活的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A500_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/h9m=D0t
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/216
- 社区家校合作的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/nrs
- 终身学习资源的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/uBO
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/025=dnv
- 社区庭院绿化的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/vvk=816
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/AfA=A9p
- 乡村文化活动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/635
- 社区文化传播的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/xep
- 农产品品牌传播的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/mw6
- 劳动教育实践的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/382=qqz
- 公园亲子设施的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/rzm=602
- 城市绿道建设的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/uHj=5hC
- 城市文化路线的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/149
- 光伏知识科普的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/klf
- 公共健身器材的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/mrP
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/370=afu
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/gvp=273
- 社区垃圾分类的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/Z4d=IWA
- 社区老年食堂的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/286
- 社区垃圾回收的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/eda
- 节能家电使用的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/i1X
- 城市公共自行车的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/956=rne
- 公共设施使用的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/duk=932
- 科学运动指导中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/FRe=kif
- 数字地图应用的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8A%A0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/328
- 小区公共照明的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8A%A0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/ywe
- 社区菜市场服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8A%A0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/bim
- 环境教育课程的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8A%A0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/690=tzs
- 城市生活服务的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8A%A0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/zdq=056
- 软件开发学习的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%8A%A0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/WBO=jVv
- 个人时间管理的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%8A%95%E8%B5%8436%E5%85%83%E6%AF%8F%E5%A4%A9%E8%B5%9A200%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/395
- 终身学习资源的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%8A%95%E8%B5%8436%E5%85%83%E6%AF%8F%E5%A4%A9%E8%B5%9A200%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/jrz
- 公共空间照明的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%8A%95%E8%B5%8436%E5%85%83%E6%AF%8F%E5%A4%A9%E8%B5%9A200%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/2SQ
- 家庭阅读计划的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%8A%95%E8%B5%8436%E5%85%83%E6%AF%8F%E5%A4%A9%E8%B5%9A200%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/735=xkv
- 新能源出行从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%8A%95%E8%B5%8436%E5%85%83%E6%AF%8F%E5%A4%A9%E8%B5%9A200%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/kdg=951
- 网络信息辨识的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E6%8A%95%E8%B5%8436%E5%85%83%E6%AF%8F%E5%A4%A9%E8%B5%9A200%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/HCw=4NP
- 开放数据应用的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/404
- 街区道路维护的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/tkt
- 城市水环境观察的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/zWG
- 乡村产业科普的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/154=pwu
- 开源技术交流的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/pnk=820
- 城市人文观察的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%BC%BA%E7%9A%84%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E6%96%B9%E6%A1%88%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/HcS=ezo
- 新能源知识普及的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%AF%BC%E5%B8%88%E6%9B%9D%E5%85%89_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/039
- 社区环保活动的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%AF%BC%E5%B8%88%E6%9B%9D%E5%85%89_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/jty
- 老年人日常照护的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%AF%BC%E5%B8%88%E6%9B%9D%E5%85%89_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/MkN
- 数字政务体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%AF%BC%E5%B8%88%E6%9B%9D%E5%85%89_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/576=jsa
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%AF%BC%E5%B8%88%E6%9B%9D%E5%85%89_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/ryz=771
- 机器人科普活动的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%AF%BC%E5%B8%88%E6%9B%9D%E5%85%89_%E7%9F%A5%E4%B9%8E%E6%9C%8D%E9%A5%B0?/00r=Ksb
- 网络信息辨识的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/071
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/xps
- 软件开发学习的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/LgI
- 家庭收纳实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/587=lmp
- 信息无障碍体验的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/omk=840
- 乡村公共文化的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E5%BF%85%E5%BA%94%E6%92%AD%E6%8A%A5?/llx=dlJ
- 社区便利生活的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%9F%E6%AD%A3%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/183
- 食品安全科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%9F%E6%AD%A3%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/dqw
- 在线教育体验的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%9F%E6%AD%A3%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/peS
- 节能家电使用的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%9F%E6%AD%A3%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/744=gra
- 本地旅行体验的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%9F%E6%AD%A3%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/fkl=720
- 开放数据应用的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9C%9F%E6%AD%A3%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/PVr=GYk
- 居民健康教育的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0?/972
- 公园亲子设施的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0?/voj
- 全民阅读推广的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0?/5Ji
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0?/515=ext
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0?/xht=376
- 城市骑行环境的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0?/qQQ=Val
- 学校体育活动的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%803%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/922
- 公共健身器材的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%803%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/abc
- 绿色办公实践的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%803%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/jqx
- 非遗体验活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%803%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/786=lsq
- 节日文化体验的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%803%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/xss=100
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%803%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/CkX=NCX
- 数字阅读服务的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/471
- 社区手工活动的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/kca
- 青少年编程学习的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/eHI
- 电动汽车充电的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/495=rgx
- 生成式工具使用的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/qmb=107
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/JRm=BLM
- 垃圾分类指导的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/779
- 绿色快递包装的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/pgt
- 家庭网络使用的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/2AB
- 城市游园体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/660=utv
- 绿色生活实践的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/qin=482
- 社区垃圾回收的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%A1%88_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/oKO=rRt
- 公共交通接驳的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/042
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/xgv
- 儿童运动体验的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/Jcw
- 健康信息获取的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/798=lrt
- 数字学习资源的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/pjx=931
- 社区家校合作的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/nkm=Eub
- 公共文化活动的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%B0%8F%E4%BB%BB%E5%8A%A1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/571
- 邻里互助活动的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%B0%8F%E4%BB%BB%E5%8A%A1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/old
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%B0%8F%E4%BB%BB%E5%8A%A1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/Bvi
- 节约用水实践的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%B0%8F%E4%BB%BB%E5%8A%A1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/348=ble
- 生活技能分享中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%B0%8F%E4%BB%BB%E5%8A%A1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/qfs=396
- 儿童友好空间的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%B0%8F%E4%BB%BB%E5%8A%A1%E4%B8%80%E5%8D%95%E4%B8%80%E7%BB%93_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/zAN=Tsh
- 运动安全知识中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/835
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/cjr
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/2Is
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/642=yoj
- 青少年科技社团的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/yqp=070
- 家庭环保行动的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/1sb=1or
- 社区便民服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%89%9B%E7%89%9B24%E5%B0%8F%E6%97%B6%E5%85%91%E6%8D%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/296
- 城市农夫市集的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%89%9B%E7%89%9B24%E5%B0%8F%E6%97%B6%E5%85%91%E6%8D%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/yzp
- 乡村电商实践的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%89%9B%E7%89%9B24%E5%B0%8F%E6%97%B6%E5%85%91%E6%8D%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/z5k
- 绿色快递包装的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%89%9B%E7%89%9B24%E5%B0%8F%E6%97%B6%E5%85%91%E6%8D%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/345=fki
- 青年志愿活动的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%89%9B%E7%89%9B24%E5%B0%8F%E6%97%B6%E5%85%91%E6%8D%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/nwc=079
- 老年运动活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%89%9B%E7%89%9B24%E5%B0%8F%E6%97%B6%E5%85%91%E6%8D%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/7u4=YtK
- 乡村教育资源的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E5%BD%A9%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E7%A8%B3_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/107
- 创业经验分享的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E5%BD%A9%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E7%A8%B3_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/gxd
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E5%BD%A9%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E7%A8%B3_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/iIX
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E5%BD%A9%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E7%A8%B3_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/954=ugv
- 社区公共议事的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E5%BD%A9%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E7%A8%B3_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/gsw=864
- 乡村生态观察的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E5%BD%A9%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E7%A8%B3_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/Dmd=r2t
- 家庭环保习惯的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B0%B7%E6%AD%8C?/835
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B0%B7%E6%AD%8C?/xfn
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B0%B7%E6%AD%8C?/Vx7
- 儿童阅读角的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B0%B7%E6%AD%8C?/735=fmb
- 消防知识宣传的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B0%B7%E6%AD%8C?/xsw=483
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E5%8C%85%E8%B5%9A%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B_%E8%B0%B7%E6%AD%8C?/h8P=cTp
- 公共卫生设施的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/040
- 文化讲座服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/ebm
- 城市步行友好的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/IxT
- 生活服务数字化的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/797=oqo
- 公共健身器材的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/twg=174
- 农村环境治理的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/X38=7QF
- 城市公共自行车的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/690
- 数字学习资源的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/zwh
- 公共空间照明的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/F7Q
- 城市微更新实践的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/302=adj
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/mij=982
- 数字支付体验的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/tvF=rh8
- 社区生活指南的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E6%8A%95%E8%B5%840%E5%85%83%E6%8C%A3300_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/090
- 科普展览体验的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E6%8A%95%E8%B5%840%E5%85%83%E6%8C%A3300_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/olt
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E6%8A%95%E8%B5%840%E5%85%83%E6%8C%A3300_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/4YI
- 社区健康讲座的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E6%8A%95%E8%B5%840%E5%85%83%E6%8C%A3300_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/981=vhs
- 老旧小区改造的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E6%8A%95%E8%B5%840%E5%85%83%E6%8C%A3300_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/rvd=905
- 农村环境治理的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E6%8A%95%E8%B5%840%E5%85%83%E6%8C%A3300_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/60Q=dqp
- 基层医疗预约的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/257
- 社区交通安全的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/khf
- 市民热线服务的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/tne
- 儿童安全出行的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/429=nsf
- 社区花园共建的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/mlm=869
- 社区知识分享的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/ajn=hjI
- 城市共享单车的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/900
- 学校食育活动的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/htc
- 药品使用科普的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/qLj
- 便民维修服务的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/067=xpj
- 通勤路线规划的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/rew=913
- 社区学习活动的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9F%E8%A7%88?/h5q=UfF
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/448
- 街头绿植养护的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/try
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/lj8
- 社区法律科普的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/903=txn
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/hip=142
- 社区活动报名的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/Dxd=25V
- 青少年户外教育的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/277
- 城乡交流活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/kqd
- 社区共享书架的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/diT
- 城市微更新实践的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/625=gqg
- 便民信息查询的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/xqb=003
- 公共交通信息服务的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E8%BE%9F%E8%B0%A3?/4br=i1q
- 公共空间照明的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/778
- 城市应急广播的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/fcp
- 线上办事服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/U8D
- 乡村公共阅读的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/293=wvc
- 城市空气科普的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/byo=745
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/MiF=AMx
- 家庭收纳实践的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/519
- 城市公共标识的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/wud
- 数字学习资源的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/Sl8
- 就业技能培训中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/191=rkg
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/kvp=697
- 智慧城市体验中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/7V4=M8L
- 网络信息辨识的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E9%9D%A0%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/371
- 创业经验分享的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E9%9D%A0%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/nzo
- 校园节能行动的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E9%9D%A0%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/8yI
- 远程协作工具的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E9%9D%A0%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/045=zgq
- 老年友好服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E9%9D%A0%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/ofe=098
- 青少年心理健康中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E9%9D%A0%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/UGe=Pw2
- 街区绿化养护的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/402
- 家庭急救准备的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/mnr
- 社区交通安全的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/xtn
- 社区绿色空间的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/671=ooj
- 在线学习体验的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/ouj=448
- 药品使用科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E8%85%BE%E8%AE%AF%E7%99%BE%E7%A7%91?/FWp=0Sx
- 城市住房服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/517
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/chm
- 数字创意课程的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/A5Y
- 社区互助网络的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/034=dbf
- 社区设施共享的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/jxm=473
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B4%A2%E6%8A%A5?/8PB=uMR
- 公交无障碍服务的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/613
- 城市游园体验的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/thw
- 地方旅游导览的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/1tA
- 社区垃圾分类的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/814=qck
- 校园安全教育的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/hhs=548
- 公共卫生宣传的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E8%B7%91%E8%B7%AF_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/jSR=0ck
- 社区公共餐饮的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E9%87%8C%E9%9D%A2%E7%9A%84%E5%BD%A9%E7%A5%A8%E9%92%B1%E8%83%BD%E5%8F%96%E5%90%97_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/542
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E9%87%8C%E9%9D%A2%E7%9A%84%E5%BD%A9%E7%A5%A8%E9%92%B1%E8%83%BD%E5%8F%96%E5%90%97_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/dgt
- 图书馆活动策划的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E9%87%8C%E9%9D%A2%E7%9A%84%E5%BD%A9%E7%A5%A8%E9%92%B1%E8%83%BD%E5%8F%96%E5%90%97_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/tUY
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E9%87%8C%E9%9D%A2%E7%9A%84%E5%BD%A9%E7%A5%A8%E9%92%B1%E8%83%BD%E5%8F%96%E5%90%97_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/810=dde
- 生活服务数字化的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E9%87%8C%E9%9D%A2%E7%9A%84%E5%BD%A9%E7%A5%A8%E9%92%B1%E8%83%BD%E5%8F%96%E5%90%97_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/tlb=389
- 城市地名文化的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E9%87%8C%E9%9D%A2%E7%9A%84%E5%BD%A9%E7%A5%A8%E9%92%B1%E8%83%BD%E5%8F%96%E5%90%97_%E9%9B%85%E8%99%8E%E8%AF%BB%E6%8A%A5?/DvV=VdX
- 乡村公共文化的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/597
- 城市公共厕所的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/val
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/bLH
- 生活垃圾回收的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/830=xyj
- 社区文化传播的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/vhv=336
- 城市建设科普的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/ci0=5vw
- 城市水环境观察的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/532
- 社区养老服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/ath
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/GA4
- 科学观察活动的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/266=jbc
- 市民热线服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/dyy=393
- 家庭园艺实践的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%91%8A?/OEm=VYF
- 老年数字阅读的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/885
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/ztp
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/JX4
- 青少年心理健康的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/369=mqp
- 社区公共议事中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/qnf=909
- 老年人文化生活的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_36%E6%B0%AA%E5%81%A5%E8%BA%AB?/B0L=Qu6
- 家庭防灾准备的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/942
- 本地历史资料的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/ozb
- 社区体育组织的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/4cN
- 开放式学习空间的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/298=vjl
- 老年智能设备的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/lrr=101
- 社区休闲设施的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%83%BD%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/kP6=jF4
- 图书馆活动策划的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/118
- 城市共享单车的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/sja
- 无障碍出行的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/JU2
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/422=hzj
- 环境教育课程的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/kyt=647
- 数字便民地图的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%9C%80%E5%90%8E%E8%A1%80%E6%9C%AC%E6%97%A0%E5%BD%92_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/RQE=2x3
- 城市公共标识的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/231
- 老年友好服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/sak
- 基层健康档案的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/UyK
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/420=enw

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
