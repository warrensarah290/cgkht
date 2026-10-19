# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 街区小店体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ipq=964
- 社区设施共享的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Uz5=A6g
- 科学教育活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/819
- 农村环境治理的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/kcq
- 城市应急广播的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/fBS
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/628=zrp
- 灵活就业交流的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/yxz=025
- 公共空间休憩的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/h3K=EII
- 青年就业服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/407
- 开放数据应用的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/dpx
- 数字阅读服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/JNP
- 社区体育组织的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/228=vwn
- 公共服务评价的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/bzl=423
- 城市便民驿站的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/Oo4=ceF
- 社区文化节活动的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E7%99%BE%E7%A7%91?/774
- 机器学习入门的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E7%99%BE%E7%A7%91?/wya
- 无障碍出行的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E7%99%BE%E7%A7%91?/dGR
- 公共空间照明的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E7%99%BE%E7%A7%91?/839=gom
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E7%99%BE%E7%A7%91?/zdg=472
- 社区艺术活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E7%99%BE%E7%A7%91?/Gar=3t1
- 社区生活指南的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/323
- 公园亲子设施的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/zno
- 社区科普课堂的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/2l5
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/846=lwc
- 公共服务指南的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/adv=217
- 数字设备回收的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/umw=Ifp
- 社区生活指南的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/624
- 乡村公共服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/xcu
- 科学教育活动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/jAy
- 老年友好服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/124=fuu
- 便民服务地图的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/bfo=393
- 课后服务体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/tHT=lV1
- 公交无障碍服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/499
- 社区垃圾回收的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/zbe
- 垃圾分类指导的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/rX4
- 科学教育活动的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/606=gkq
- 城市应急广播中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/xkf=045
- 地方旅游导览的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/cfg=e1n
- 绿色消费选择的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/783
- 健康步道使用的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/dzp
- 租房信息服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/7zj
- 城市雨天出行的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/127=kdq
- 网络安全教育的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/djw=728
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/Htd=0Vj
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/431
- 小区停车协商的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/xol
- 乡村产业科普的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/4bO
- 城市骑行环境的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/151=ksh
- 社区便民集市的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/idm=419
- 城市地名文化的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/o7Q=itP
- 数字资源检索的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/451
- 非遗体验活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/uij
- 地方文化传播的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/xMe
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/095=kmy
- 口袋公园建设的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/dzc=801
- 社区公共卫生的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/1H8=W5u
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/531
- 城市公共艺术的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/chl
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/QjV
- 社区环保活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/009=xqa
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/tnt=492
- 社区阅读服务的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/okY=zWr
- 城市应急科普的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/868
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/you
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/zuh
- 数字支付体验的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/543=ehk
- 社区老年食堂的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/pzs=373
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/7Ym=eLK
- 市民意见收集的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/345
- 地方戏曲体验的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/hio
- 儿童运动体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/Plx
- 地方民俗记录的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/250=daz
- 公益活动组织的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/spt=381
- 老年人日常照护的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/qO7=xER
- 城市公共座椅的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/582
- 急救知识普及的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/mtv
- 公共交通接驳的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/AB7
- 基层服务创新的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/036=fpd
- 机器学习入门的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/cwx=274
- 城市便民驿站中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/x7a=Zhc
- 周末休闲规划的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/755
- 社区协商议事的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/vqz
- 数字学习资源的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/XaZ
- 社区便利生活的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/639=bub
- 家庭防灾准备的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/elu=309
- 市民热线服务的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/SOi=DER
- 文化讲座服务的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/898
- 社区共享书架的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/imr
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/nT2
- 在线学习体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/235=fhh
- 市民热线服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/bnm=351
- 社区家政服务的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8F%A3%E5%B2%B8%E8%B4%A2%E7%BB%8F?/Zja=3Ka
- 公共卫生宣传的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/628
- 农村环境治理的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/mlk
- 城市微更新实践的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/XTm
- 居家适老化改造的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/502=hqo
- 课后服务体验的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/yon=488
- 亲子科普活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%B8%93%E9%A2%98?/2TD=NhJ
- 便民信息查询的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%83%BD%E6%BA%90?/010
- 家庭环保习惯的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%83%BD%E6%BA%90?/rbj
- 数字资源检索的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%83%BD%E6%BA%90?/sbK
- 社区互助网络的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%83%BD%E6%BA%90?/779=izf
- 数字政务体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%83%BD%E6%BA%90?/uix=269
- 居民健康教育的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%83%BD%E6%BA%90?/kgV=YMu
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/521
- 读书会组织的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/pdk
- 绿色消费选择的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/ycV
- 街道综合服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/612=svg
- 社区家校合作的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/fzm=607
- 城乡交通衔接的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/XGS=fpi
- 电动汽车充电的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/964
- 城市展览体验的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/kxt
- 城市应急科普的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/0mN
- 老年友好服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/343=vbg
- 小区停车协商的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/uig=841
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_365%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/5RV=6tY
- 城市体育设施中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/916
- 节假日出行安排的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/sst
- 运动安全知识的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/NNU
- 老年友好服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/578=clc
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/tui=971
- 休闲运动入门的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/vdF=LJp
- 社区公共议事的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/403
- 公共服务预约的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/cbv
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/bT2
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/165=qkl
- 社区环保活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/pkw=446
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5?/TEx=X6A
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/134
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/wct
- 社区菜市场服务的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/v0i
- 生成式工具使用的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/718=qhc
- 城市夜间照明的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/rbn=366
- 老年数字阅读的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/VXt=LaG
- 社区手工活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/057
- 科学信息获取中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/tpt
- 公共空间安全中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/XgU
- 数字设备回收的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/230=ivu
- 社区阅读服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/wrp=208
- 社区互助网络的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/hs4=QXg
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/182
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/xqf
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/WA4
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/063=mvd
- 街道综合服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/dls=020
- 社区休闲设施的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/6JV=NBx
- 家庭运动计划的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/746
- 城市适老服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/jwv
- 城市住房服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/bvj
- 智能家居应用的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/070=ieh
- 地方文化传播的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/wty=686
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/Vxo=pqo
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/215
- 社区教育资源的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/hax
- 线上阅读资源的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/RiA
- 社区学习活动的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/129=jcw
- 电子商务服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/ydk=702
- 城乡交通衔接的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/Elp=365
- 节能生活方式的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/187
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/bvg
- 小区公共照明的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/tQw
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/996=ipl
- 社区修缮行动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/ibi=550
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/iKr=D09
- 通勤路线规划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/669
- 便民服务窗口的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/fbs
- 社区故事采集的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/kr4
- 药品使用科普的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/570=hei
- 社区儿童活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/vco=840
- 全民健身活动的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/0V8=jC5
- 社区文化节活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/210
- 社区生活指南的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/jjw
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/FVU
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/558=cwl
- 城市展览体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/sit=333
- 家庭用电安全的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/Ppo=d5F
- 社区活动策划的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/706
- 社区安全巡查的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/cnc
- 青年就业服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/97x
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/240=iev
- 社区垃圾分类的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/hwj=453
- 社区停车服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/fEt=1A4
- 农产品品牌传播的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/730
- 公共空间休憩的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/xxo
- 青少年户外教育的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/8ak
- 校园节能行动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/066=bam
- 社区环保活动的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/hci=203
- 社区公共卫生的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/wlw=bG0
- 骑行路线规划的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/896
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/qbi
- 学校食育活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/fDE
- 城市展览体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/675=xqc
- 社区菜市场服务的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/zwe=737
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/4to=m3R
- 社区心理支持的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/268
- 在线教育体验的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/eas
- 青年就业服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/XQe
- 城市噪声观察的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/054=kun
- 小区停车协商的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/pkg=704
- 节日文化体验的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/mWD=6n2
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/728
- 急救知识普及的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/ixd
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/RvO
- 电动汽车充电的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/994=snz
- 社区文化节活动的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/drx=836
- 乡村产业科普的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/mPo=Rb5
- 城市适老服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/316
- 农业科普体验的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/wda
- 科学教育活动的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/O5Z
- 数字生活课堂的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/902=hdl
- 社区休闲设施的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/him=127
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/FZy=EZi
- 家庭健康科普的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/187
- 科学健身方法的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/lgy
- 社区艺术活动的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/Z80
- 乡村阅读空间的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/475=gqu
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/icp=907
- 邻里共享空间的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/hkA=CNb
- 绿色生活实践的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/806
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/gio
- 青少年心理健康的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/7lW
- 街区绿化养护的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/649=dwc
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/swn=765
- 光伏知识科普的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/Hpb=dI7
- 城市住房服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%B1%E8%A7%86?/786
- 终身学习资源的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%B1%E8%A7%86?/bwm
- 读书会组织的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%B1%E8%A7%86?/tiz
- 社区文化传播的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%B1%E8%A7%86?/477=qpx
- 社区学习活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%B1%E8%A7%86?/ezi=786
- 租房信息服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BD%B1%E8%A7%86?/Fn4=TxB
- 家庭消费规划的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/087
- 环境教育课程的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/ijx
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/DjA
- 城市步行环境的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/504=xyr
- 数字课堂应用的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/pce=804
- 老年人出行服务的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-welcome%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%A1%A3%E6%A1%88?/TDr=8jU
- 社区商业活力的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/889
- 科学健身方法的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/qan
- 无障碍出行的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/gY9
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/398=fej
- 社区便民集市的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/cqj=667
- 户外活动组织有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/y6f=YEV
- 老年友好服务的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/508
- 社区共享书架的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/saj
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/uSU
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/815=bca
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/ztm=177
- 校园节能行动的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/fSZ=6O2
- 城乡交流活动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/861
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%9B%BD%E9%99%85vip-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/csn

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
