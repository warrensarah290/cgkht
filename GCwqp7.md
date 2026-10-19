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

- 职业技能学习的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/7F5
- 社区托育服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/706=aja
- 本地旅行体验的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/nmv=450
- 城市展览体验的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/RL2=8tV
- 科普展览体验的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/589
- 城市基础设施的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/nao
- 城市建设科普的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/MCd
- 健康饮水科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/276=bfw
- 智慧城市体验的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/oar=149
- 家庭饮食安排的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/FxB=Xjc
- 科学观察活动的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/072
- 城市文明实践的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/ujr
- 文明养宠科普的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/ytv
- 在线学习体验的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/409=vne
- 基层医疗预约的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/uah=184
- 公共服务评价的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/PsU=ueM
- 应急物资管理的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/634
- 数字档案服务的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/zbr
- 儿童友好空间的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/pIk
- 城市空气科普的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/257=gpr
- 课后服务体验的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/tce=247
- 医院导诊服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/TZD=Cvy
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/487
- 本地消费场景的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/bhu
- 数字档案服务的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/Z86
- 城市游园体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/040=twy
- 社区活动报名的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/ypr=322
- 社区消防演练的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/BEi=jJk
- 城乡公共服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/175
- 城市应急科普的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/zei
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/kHZ
- 社区公共卫生的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/056=gnh
- 远程协作工具的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/cer=535
- 城市公共饮水的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%AF%8D%E5%A9%B4?/7JW=M7r
- 线上阅读资源的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/889
- 乡村生活观察的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/uwh
- 健康步道使用的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/VK4
- 城市体育设施的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/804=gei
- 家庭安全提示的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/bvl=572
- 公园亲子设施的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/LFV=YMH
- 社区快递服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/047
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/qea
- 在线学习体验的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/Ldg
- 社区公共卫生的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/354=rju
- 农产品消费体验的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/htd=953
- 城市慢行系统的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/CcW=t3j
- 医院导诊服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/408
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/tpv
- 公共设施维护的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/KAb
- 乡村文化空间的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/852=dho
- 科技馆参观体验的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/slp=462
- 儿童安全出行的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%B9%96%E5%8C%97%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/vB4=J2e
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/978
- 公园亲子设施的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/axg
- 家庭食品保存的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/hdP
- 社区教育资源的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/308=byw
- 城市微更新实践的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/lky=525
- 乡村文化空间的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/UNS=TaI
- 社区故事采集的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/865
- 社区心理支持中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/djr
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/YGn
- 科技馆参观体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/318=lyi
- 社区家政服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/jzb=389
- 老年人日常照护的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/zKo=GBA
- 绿色出行服务的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/968
- 气象科普传播的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/zbf
- 城市骑行环境的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/bTx
- 社会体育指导的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/300=lfa
- 家庭网络使用的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/qqk=642
- 市民热线服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E8%B5%9A%E9%92%B1_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/Nw1=fX6
- 节日文化体验的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/103
- 公共服务沟通的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/ejr
- 社区应急准备的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/XC2
- 社区公共议事的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/560=onb
- 社区读书角建设的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/ydo=409
- 街区绿化养护中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/Uc5=bkO
- 社区垃圾分类的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/249
- 社区协商议事的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/zeq
- 社区体育组织的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/cFF
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/288=lfc
- 城市可持续生活的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/dur=358
- 市民热线服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/boe=Qt3
- 城市应急科普的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/887
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/gse
- 老年人文化生活的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/0dG
- 人工智能科普的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/132=okb
- 社区便民集市的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/vns=719
- 社区教育资源的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E5%A6%82%E4%BD%95%E7%9B%88%E5%88%A9_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/68p=kWP
- 城市博物馆服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/984
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/sdp
- 非遗体验活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/WRb
- 社区生活指南的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/978=lwo
- 个人数据管理的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/hez=726
- 食品配送体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%B8%93%E9%A2%98?/11S=1E7
- 城市体育设施的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/216
- 邻里互助活动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/aqz
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/ct9
- 社区安全巡查的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/033=qbq
- 城市游园体验的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/ied=214
- 家庭养老规划的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/MUE=xAS
- 科学信息获取的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/964
- 家庭饮食安排的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/mxe
- 城市雨天出行的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/vYz
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/558=vqu
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/pge=313
- 骑行路线规划的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9B%E8%BD%A6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/Vsv=UWt
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/292
- 城市骑行环境的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/pdf
- 本地旅行体验的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/cA4
- 公共设施使用的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/635=ezk
- 数字创意课程的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/kaz=356
- 家庭理财科普的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%B5%9B%E8%BD%A6%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/Syr=zOA
- 休闲运动入门的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/092
- 城市公共自行车的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/ztj
- 城市住房服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/Tdz
- 农产品品牌传播的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/011=trm
- 食品配送体验的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/xhy=749
- 科技馆参观体验的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/WWi=rHV
- 城市运动公园的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/284
- 社区家校合作的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/wxb
- 社区互助网络的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/ePk
- 个人信息保护的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/625=pzz
- 节气饮食文化的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/gmr=571
- 城市步行友好的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/qVy=zSt
- 本地消费场景的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/737
- 基层服务创新的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/bfj
- 开源技术交流的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/It1
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/837=ciq
- 线上办事服务的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/pkr=973
- 校园阅读活动的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/Jto=7wN
- 便民信息查询的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/006
- 社区垃圾分类的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/yyt
- 社区体育组织的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/j3q
- 终身学习资源的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/646=blf
- 城市骑行环境的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/kwo=896
- 光伏知识科普的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/0K1=hPR
- 社区养老服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/337
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/jrr
- 无障碍出行的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/e2J
- 科学观察活动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/508=tha
- 青年志愿活动的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/nkg=890
- 公共设施使用的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/zwf=ecF
- 城市便民驿站中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/007
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/uqt
- 社区家校合作的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/hlp
- 志愿服务平台的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/337=iyr
- 创业经验分享的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/ejf=532
- 青少年科技社团的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/vit=r9M
- 运动安全知识的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/712
- 开放数据应用的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/mqk
- 乡村公共服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/tBX
- 绿色快递包装中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/013=kkd
- 城市便民驿站的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/efc=274
- 家庭消费规划的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/Wur=mIv
- 城市文化路线的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/981
- 社区公共卫生的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/nxa
- 城市微更新实践的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/5y3
- 社区应急准备的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/154=ter
- 社区设施共享的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/gfo=152
- 小区停车协商的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%BC%AB%E8%AF%84?/YnC=zgh
- 儿童友好空间的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/992
- 家庭节能实践的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/xul
- 城市博物馆活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/lsH
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/549=zai
- 城市适老服务的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/udk=755
- 家庭健康科普的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/lvU=Bue
- 城乡交通衔接的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/517
- 文化讲座服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/mdd
- 口袋公园建设的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/iHp
- 社区活动空间的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/774=hxx
- 社区读书角建设的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/ktz=106
- 家庭教育交流的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%B3%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/hru=KDh
- 数字阅读服务的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E4%B8%8A%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/800
- 传统节日科普的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E4%B8%8A%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/hfo
- 数字政务体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E4%B8%8A%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/Duc
- 在线学习体验的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E4%B8%8A%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/641=iwy
- 社区宠物管理的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E4%B8%8A%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/axi=073
- 小区停车协商的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E4%B8%8A%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/l8G=UF3
- 农业科普体验的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/941
- 公园无障碍服务的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/lkv
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/3jJ
- 就业技能培训的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/596=unm
- 地方民俗记录的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/wjt=913
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E9%99%86%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/aSg=iAd
- 家庭环保行动的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/342
- 乡村教育资源的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/zim
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/5S7
- 绿色快递包装的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/798=adt
- 环境监测科普的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/zva=086
- 社区环保活动的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/BD3=eCq
- 地方民俗记录的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/109
- 新能源出行的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/hlv
- 社区活动策划的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/MF0
- 绿色校园实践的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/769=qhm
- 气象科普传播的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/yqm=506
- 城市公共自行车的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%80%E5%88%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/TQk=Fls
- 城市公共标识的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/437
- 线上阅读资源的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/wlw
- 城市空气科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/qhy
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/008=bqy
- 地方美食文化的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/kym=523
- 公交无障碍服务的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/A9M=9JH
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E7%94%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/256
- 骑行路线规划的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E7%94%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/qne
- 城乡交流活动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E7%94%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/pVW
- 亲子阅读活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E7%94%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/549=uqy
- 城市夜间生活中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E7%94%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/coi=809
- 个人数据管理的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E7%94%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/JYJ=y2I
- 社区商业活力的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/834
- 社区公共餐饮的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/gki
- 城市公共空间的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/pQz
- 社区科普课堂的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/461=nij
- 安全出行教育的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/usw=526
- 家庭志愿活动的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/7ae=mWk
- 食品配送体验的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/403
- 家庭运动计划的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/eti
- 运动安全知识的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/icD
- 数字公共文化的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/800=wtd
- 新能源知识普及中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/qmi=790
- 城市运动公园的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/m2m=YEE
- 社区共享书架的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/712
- 社区艺术活动的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/zpp
- 生活技能分享的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/0ao
- 社区活动报名的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/725=ghz
- 本地历史资料的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/snk=292
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/DpR=Swp
- 终身学习资源的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/630
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/shf
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/HU2
- 安全出行教育的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/928=bkx
- 机器学习入门的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/vsn=290
- 城市公共艺术的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/atz=5QK
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%9C%A8%E5%93%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/456
- 开源技术交流的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%9C%A8%E5%93%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/qie
- 街区小店体验的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%9C%A8%E5%93%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/6wd
- 环境教育课程的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%9C%A8%E5%93%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/526=gyi
- 科学信息获取的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%9C%A8%E5%93%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/mbw=789
- 图书馆活动策划的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%9C%A8%E5%93%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/3PH=Oic
- 社区活动策划的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/190
- 社区应急准备的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/czd
- 社区阅读服务的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/Z9l
- 城市公共艺术的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/882=mzx
- 青少年户外教育的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ypd=234
- 家庭网络使用的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%B8%B8%E6%88%8F_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/kV4=DHb
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_360%E6%9C%8D%E9%A5%B0?/028
- 节日文化体验的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_360%E6%9C%8D%E9%A5%B0?/ler
- 节能生活方式的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_360%E6%9C%8D%E9%A5%B0?/sRt
- 城市树木认养的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_360%E6%9C%8D%E9%A5%B0?/216=wdn
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_360%E6%9C%8D%E9%A5%B0?/jhn=262
- 户外活动组织的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_360%E6%9C%8D%E9%A5%B0?/Evh=MZ6

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
