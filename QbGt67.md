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

- 家庭节能实践的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_08%E5%BE%AE%E8%81%8A-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/llD
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_08%E5%BE%AE%E8%81%8A-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/573=ogs
- 家庭环保行动的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_08%E5%BE%AE%E8%81%8A-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/jdc=668
- 软件开发学习的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_08%E5%BE%AE%E8%81%8A-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/xAV=Tnh
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/224
- 乡村公共文化的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/fvr
- 老年友好服务的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/hTi
- 非遗课堂体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/234=iui
- 数字素养提升的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/qed=264
- 社区运动空间的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_08%E5%BE%AE%E8%81%8A-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/ypJ=vOV
- 基层健康服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/849
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/ptz
- 城市微更新实践的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/4fa
- 社区养老服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/414=rmx
- 节约用水实践的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/tks=322
- 读书会组织的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_100%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/e8l=amo
- 图书馆数字服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/291
- 社区公共餐饮的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/uwe
- 健康步道使用中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/Wep
- 数字创意课程的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/228=jbm
- 公共文化活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/tgn=611
- 社区手工活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/DFv=JiN
- 基层健康服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/256
- 社区生活指南的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/onj
- 青年就业服务的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/kYO
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/953=gzh
- 公共场所导视的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/eeh=665
- 急救知识普及的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/Bwx=M8k
- 公园休闲体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/999
- 城市应急科普的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/lnz
- 线上阅读资源的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/SEB
- 地方民俗记录的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/457=jhh
- 社区快递服务的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/ake=091
- 在线学习体验的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/zq4=vAA
- 公交站点体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BC%97%E6%B5%8B?/054
- 社区菜市场服务的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BC%97%E6%B5%8B?/wvf
- 网络信息辨识的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BC%97%E6%B5%8B?/bRx
- 基层健康服务的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BC%97%E6%B5%8B?/195=rgu
- 城市雨天出行的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BC%97%E6%B5%8B?/qmh=511
- 社区绿色空间的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E4%BC%97%E6%B5%8B?/tM2=vHV
- 家庭收纳实践的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/466
- 青少年科技社团的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/mzw
- 智能家居应用的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/V9Y
- 职业技能学习的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/224=wfw
- 环境监测科普的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/ozd=623
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/HUH=rLz
- 公共健身器材的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/192
- 社区交通安全的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/tdq
- 城市水环境观察的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/FL8
- 城市住房服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/531=wrq
- 人工智能科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/ewr=107
- 乡村生活观察的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/4we=M4M
- 远程协作工具的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/740
- 在线学习体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/wpq
- 数字便民地图的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/B3T
- 小区停车协商的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/042=ngr
- 社区家校合作中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/wav=803
- 社区法律科普的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/dj4=Bto
- 家庭网络使用的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/764
- 本地旅行体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/sxc
- 地方戏曲体验的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/OuX
- 城市文明出行的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/853=oed
- 公共设施维护的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/ssm=862
- 城市噪声观察的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/EsP=XeZ
- 社区教育资源的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/850
- 城市适老服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/hed
- 城市水环境观察的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/EGM
- 数字创意课程的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/881=pfl
- 公共场所导视的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/btj=169
- 青少年户外教育的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_100%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/jDT=Xmp
- 本地消费场景的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/114
- 地方文化传播的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/fsc
- 城市便民驿站的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/ZLN
- 全民阅读推广的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/969=dvi
- 网络安全教育的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/teq=441
- 在线教育体验的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%86%E9%A2%91?/KP1=oum
- 社区消防演练的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_100%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/017
- 运动安全知识的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_100%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/ufy
- 通勤路线规划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_100%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/0aw
- 街区道路维护的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_100%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/677=orn
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_100%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/hft=482
- 家庭消费规划的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_100%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/bIM=Cph
- 城市适老服务的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/135
- 节能生活方式的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/ubj
- 儿童运动体验的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/20d
- 乡村生活观察的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/744=rqd
- 食品安全科普的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/tmc=858
- 节约用水实践的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_100%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/z8z=dyv
- 城市运动公园的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/440
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/rid
- 节能生活方式的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/FKV
- 便民信息查询的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/941=gdp
- 骑行路线规划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/agc=311
- 农产品消费体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/qGM=2FF
- 城市绿道建设的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/118
- 社区文化节活动的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/ill
- 城市建设科普的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/GXw
- 新能源知识普及的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/716=zau
- 家庭收纳实践的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/rsv=724
- 地方旅游导览的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_100%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/xkf=0Is
- 数字资源检索的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/299
- 本地旅行体验的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/emp
- 社区商业活力的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/rvM
- 社区公共议事的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/610=xce
- 街区绿化养护的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/zjf=857
- 社区设施共享的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_100%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/Phb=jYV
- 家庭急救准备的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/554
- 健康步道使用的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/ois
- 开源技术交流的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/Izp
- 乡村生态旅游的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/887=yzq
- 在线学习体验的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/xbp=706
- 绿色出行服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/EAp=xgO
- 科学运动指导的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/472
- 社区故事采集的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/sgn
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/iCH
- 老年数字阅读的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/872=sob
- 城市住房服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/axw=236
- 社区设施共享的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/96L=NsU
- 个人信息保护的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/769
- 数字便民地图的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/cde
- 数字资源检索的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/IXx
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/316=zyt
- 老年智能设备的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/iqu=665
- 创业经验分享的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_100%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/RlZ=Fk7
- 智能手机助老的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/938
- 数字创意课程的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/siy
- 个人信息保护的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/OOO
- 城市公共饮水的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/549=gzp
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/lbp=888
- 乡村公共文化的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_100%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/A8X=AzW
- 居家防滑改造的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/908
- 绿色生活实践的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/ijt
- 健康饮水科普的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/WIT
- 社区艺术活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/092=amy
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/rhy=014
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_100%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/KLb=rZH
- 数字设备回收中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/409
- 社区绿色空间的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/zfv
- 乡村公共文化的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/qio
- 劳动教育实践的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/912=ghn
- 数字素养提升的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/aib=959
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_100%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E5%8E%86%E5%8F%B2?/sWQ=fH3
- 读书会组织的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/381
- 居民健康教育的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/wdu
- 家庭食品保存的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/GIn
- 本地旅行体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/250=dpm
- 农产品消费体验的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/yvw=085
- 通勤路线规划的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/8t7=Mwa
- 城市公共自行车的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/780
- 无障碍出行的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/afv
- 科学教育活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/5Yc
- 城市文明出行的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/398=wlm
- 科普展览体验的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/gwi=675
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/etF=DA3
- 网络信息辨识的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/185
- 城市博物馆服务的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/erz
- 社区手工活动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/Hy4
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/545=tus
- 家庭科学教育的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/pmx=002
- 老年友好服务的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/43J=Q6k
- 社区故事采集的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%B0%91%E7%94%9F?/052
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%B0%91%E7%94%9F?/cez
- 数字素养提升的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%B0%91%E7%94%9F?/8pk
- 老年友好服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%B0%91%E7%94%9F?/771=qwj
- 农业科普体验的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%B0%91%E7%94%9F?/err=277
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%B0%91%E7%94%9F?/Pxw=sB8
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/472
- 城市基础设施的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/egn
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/ESo
- 城市夜间照明的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/321=xcc
- 社区教育资源的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/jwp=200
- 新能源出行的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/MqH=jCr
- 家庭志愿活动的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/972
- 城市微更新实践中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/khl
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/dGZ
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/832=ycn
- 公共空间休憩的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/zvw=507
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/6My=0mU
- 线上阅读资源的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/838
- 城市展览体验的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/xqd
- 社区教育资源的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/Pcm
- 家庭用电安全的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/769=uar
- 社区法律科普的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/mbg=284
- 租房信息服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/i7H=iRO
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/395
- 开源技术交流的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/jrg
- 科学健身方法的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/Qav
- 城乡交通衔接的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/788=mpf
- 青年职业探索的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/cdk=303
- 节能生活方式的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%91%84%E5%BD%B1?/fXo=4sV
- 数字创作工具的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/558
- 读书会组织的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/qob
- 农业科普体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/Fy1
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/600=uxf
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/xxy=153
- 基层健康服务中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_105%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/pMR=o5X
- 健康信息获取的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/708
- 数字地图应用的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/nty
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/Fet
- 城市社区治理的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/953=vjh
- 机器学习入门的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/dzq=645
- 公共交通接驳的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/lcz=AD1
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_105%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/982
- 食品安全科普的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_105%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/krr
- 社区体育组织的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_105%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/2rm
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_105%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/223=frr
- 社区科普课堂的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_105%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/skd=385
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_105%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%9B%98%E7%82%B9?/cI0=g1j
- 社区科普课堂的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_105%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/508
- 乡村电商实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_105%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/kaq
- 口袋公园建设中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_105%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/pFi
- 个人数据管理的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_105%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/129=cfl
- 公共健身器材的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_105%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/usn=296
- 青少年户外教育的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_105%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/Ac1=JnU
- 社区阅读服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/758
- 绿色校园实践的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/bgr
- 数字阅读服务的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/DCG
- 街区更新实践的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/239=bvd
- 家庭急救准备的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/mvg=597
- 乡村生态观察的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_105%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/LFG=6bD
- 便民维修服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/042
- 家庭环保行动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/qnb
- 家庭教育交流的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/6pb
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/812=nmv
- 城市体育设施的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/fel=284
- 周末休闲规划的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_105%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/6fo=r3x
- 本地历史资料的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/955
- 口袋公园建设中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/efw
- 城市绿道建设的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/1u6
- 社区活动报名的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/705=qbp
- 绿色校园实践的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/bmn=767
- 老年人日常照护的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_105%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%9C%B0%E6%96%B9?/0w4=ErX
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_105%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/345
- 城市公共标识的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_105%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/vjm
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_105%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/u4Q
- 青少年心理健康的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_105%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/762=ody
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_105%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/uew=922
- 数字素养提升的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_105%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/E39=mtK
- 消防知识宣传的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%9B%BE%E9%89%B4?/564
- 校园节能行动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%9B%BE%E9%89%B4?/pwm
- 社会体育指导的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%9B%BE%E9%89%B4?/oA6
- 公交站点体验的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%9B%BE%E9%89%B4?/481=evq
- 乡村生态观察的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%9B%BE%E9%89%B4?/kmz=263
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_105%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%9B%BE%E9%89%B4?/78C=YKu
- 乡村文化活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_105%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/273
- 青少年科技社团的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_105%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/cgr
- 社区托育服务的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_105%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/hZj
- 儿童运动体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_105%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/571=cvx
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_105%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/hbr=756
- 公共服务数字化的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_105%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/8Wz=93C

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
