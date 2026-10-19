# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 公园无障碍服务的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/045
- 城乡交通衔接的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/qql
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/ENl
- 城市游园体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/100=yfd
- 城市公共标识的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/rin=474
- 乡村文化活动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/c9r=mrw
- 家庭健康科普的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/305
- 校园节能行动的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/bzf
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/rB9
- 智能手机助老中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/556=bdv
- 新能源出行的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/vwk=630
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/zQD=k6s
- 公共场所导视的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/183
- 远程协作工具的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/cmb
- 开放数据应用的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/59A
- 机器人科普活动的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/531=xcv
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/iyt=890
- 社区信息发布的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/doe=DjS
- 节日文化体验的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/439
- 公共服务沟通的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/xlo
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/wrP
- 儿童阅读角的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/897=ivg
- 物业服务沟通的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/rxn=948
- 社会体育指导的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%A8%E6%8A%A5?/zEc=aIc
- 城乡公共服务的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/316
- 家庭急救准备的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/dqb
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/pmY
- 社区知识分享的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/974=pua
- 生活垃圾回收的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/onj=055
- 文化场馆预约的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/UeP=LB1
- 社区消防演练的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/527
- 城市步行友好中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/zyt
- 数字课堂应用的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/byP
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/203=xba
- 街区更新实践的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/jlf=121
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/fKc=9cX
- 智慧停车服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/700
- 生活服务数字化的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/fiq
- 城市展览体验的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/uQk
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/447=xab
- 公益活动组织的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/khd=808
- 物业服务沟通的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/V4Y=ixF
- 小区公共照明的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/232
- 绿色办公实践的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/pnp
- 数字素养提升的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/ii8
- 社区读书角建设的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/998=lgd
- 城市空气科普的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/ocr=030
- 家庭照护支持的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E6%89%91%E6%B3%95%E5%BE%8B?/bo3=2Ez
- 居家适老化改造的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/273
- 城市水环境观察的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/oql
- 儿童安全出行的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/KsL
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/472=uho
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/kxb=604
- 绿色办公实践的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/EpV=1WZ
- 远程协作工具的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/520
- 乡村教育资源的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/acj
- 公共空间安全的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/9CC
- 社区防暑服务的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/135=doa
- 小区停车协商的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/vie=191
- 科学观察活动的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/wzj=P0p
- 无障碍出行中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/231
- 城市体育设施的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/bra
- 全民健身活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/CTH
- 电子商务服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/270=hue
- 图书馆数字服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/bii=215
- 数字学习资源的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/T18=qsU
- 线上阅读资源的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/449
- 智能家居应用的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/pqn
- 城市慢行系统的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/6gp
- 社区快递服务的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/557=vyw
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/anw=170
- 老旧小区改造的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/okt=Lfe
- 绿色出行服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/592
- 地方文化传播的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/lsb
- 农村环境治理的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/kEZ
- 乡村生活观察的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/994=qgp
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/ohq=934
- 电动汽车充电的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/gZH=6I2
- 数字艺术创作的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/401
- 线上阅读资源的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/sep
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/d08
- 电子商务服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/752=mje
- 公共卫生设施的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/bad=733
- 青年志愿活动的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/oKk=Wbf
- 垃圾分类指导的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/090
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/grf
- 数字艺术创作的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/hAa
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/686=cta
- 城乡交流活动的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/tiw=849
- 公共卫生宣传的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%94%BE?/3ho=zTZ
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/635
- 网络信息辨识的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/isn
- 传统节日科普的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/eNl
- 无障碍出行的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/213=sii
- 文化讲座服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/nql=253
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/FTB=YC1
- 农产品消费体验的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/659
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/ouq
- 街区小店体验的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/NHw
- 物业服务沟通的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/613=agh
- 公共服务预约的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/xlz=674
- 社区设施共享的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/GAZ=V63
- 软件开发学习的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/243
- 邻里共享空间的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/lsy
- 社区家校合作中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/KzH
- 乡村生态观察的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/296=aly
- 节气饮食文化的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/wcw=686
- 居家适老化改造的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/enf=zFm
- 公共空间照明的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/797
- 城市噪声观察的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/ujk
- 数字政务体验的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/Nif
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/365=rgp
- 乡村教育资源的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/cnt=588
- 城市文明实践的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/Nqy=sNC
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/500
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/tmj
- 城市可持续生活的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/Qxr
- 社区健康讲座的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/941=fip
- 无障碍出行的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/orj=280
- 科普展览体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B8%8C%E8%85%8A%E8%B4%A2%E7%BB%8F?/DZt=aE0
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/362
- 社区停车服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/apr
- 小区电梯维护的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/c6f
- 城市社区治理的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/179=yri
- 便民服务地图的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/drl=489
- 节日文化体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/Zoy=6uS
- 课后服务体验的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/885
- 社区养老服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/lpu
- 街区更新实践中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/cFj
- 家庭网络使用的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/080=pip
- 城市骑行环境的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/qct=902
- 老年友好服务的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/6UY=Bmq
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/593
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/ofh
- 城市公共座椅的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/eMm
- 老年人文化生活的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/215=zli
- 市民意见收集的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/hut=836
- 城市应急科普的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/twn=FRe
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/404
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/dxa
- 家庭照护支持的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/BtY
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/354=ehj
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/eas=711
- 社区学习活动的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/d7D=c6v
- 乡村公共服务的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/178
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/wiz
- 全民健身活动的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/van
- 环境监测科普的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/754=cfw
- 农贸市场环境中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/nhe=743
- 小区停车协商的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/Tvx=pyn
- 社区故事采集的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/423
- 食品配送体验的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/xhx
- 城市展览体验的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/uPP
- 家庭饮食安排的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/819=jvz
- 社区停车服务的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/ayf=722
- 公交站点体验中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/KcR=sLt
- 科学观察活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/378
- 数字政务体验的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/ink
- 基层服务创新的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/FCA
- 公共设施维护的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/851=iom
- 旧物循环利用的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/ldy=573
- 文化场馆预约的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/PvD=P6Q
- 社区教育资源的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/885
- 城市微更新实践的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/dvo
- 城市公共座椅的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/S7d
- 便民维修服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/323=ziw
- 课后服务体验的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/imp=542
- 社区儿童活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/pdE=Sm8
- 青少年科普实践的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/076
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/jyu
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/UAB
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/473=tia
- 城市公共标识的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/cya=001
- 城市基础设施中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/1OE=u9d
- 家庭照护支持的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/436
- 生活垃圾减量的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/tvt
- 文明养宠科普的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/k60
- 开放数据应用的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/162=euy
- 城市生活服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/sro=357
- 城乡交流活动的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/sO2=qt3
- 家庭教育交流的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/057
- 社区宣传栏更新的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/vji
- 家庭网络使用的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/aoM
- 乡村文化空间的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/112=iem
- 老年运动活动的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/eml=413
- 青少年科普实践中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/P8b=TBZ
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/947
- 数字艺术创作的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/ooo
- 垃圾分类指导的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/L3l
- 校园社团活动的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/254=bem
- 城市文明出行的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/iuj=385
- 社区商业活力的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/WRM=u1Z
- 公园休闲体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/528
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/ghk
- 城市展览体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/JnP
- 生活技能分享的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/466=kzx
- 城市微更新实践的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/qcs=191
- 城市骑行环境的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/HWQ=GpG
- 城市骑行环境的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/983
- 科学运动指导的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/mfy
- 公共交通信息服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/P6w
- 社区防暑服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/002=ocl
- 社区生活指南的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/jaz=899
- 城市文明出行的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/qJS=jwo
- 数字生活课堂的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/138
- 家庭阅读计划的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/igk
- 街头绿植养护的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/hOW
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/085=qhq
- 社区活动空间的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/sgx=035
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/tUB=1us
- 公交站点体验的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/909
- 小区停车协商的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/vet
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/hJK
- 社区运动空间的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/770=lja
- 社区快递服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/bna=267
- 本地消费场景的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-welcome%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/sps=uT6
- 旧物循环利用的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/243
- 小微企业服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/rbq
- 科学运动指导的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/Fkl
- 乡村文化活动的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/034=jxi
- 乡村电商实践的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/rcp=962
- 城市基础设施的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9B%E4%BA%8B?/y6l=KtB
- 公共设施维护的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/398
- 公共卫生设施的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/jot
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/QEw
- 基层健康档案的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/536=mtl
- 乡村生活观察的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/gov=634
- 科技馆参观体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/HCz=0lU
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/913
- 社区知识分享的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/qrx
- 城市适老服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/tAa
- 社区教育资源的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/828=nar
- 日常摄影记录的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/ugq=878
- 社区绿色空间的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/bNN=ueH
- 远程协作工具的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/101
- 在线教育体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/xmq
- 社区知识分享的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/OFm
- 数字阅读服务的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/388=ixu
- 社区艺术活动的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/xvm=805
- 城乡公共服务的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/0cg=YcJ
- 安全出行教育的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/095
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/ohg
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/5cN
- 节日文化体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/065=bpl
- 乡村产业科普的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/vdr=418
- 小区电梯维护的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%9B%98%E7%82%B9?/C1m=bHe
- 老年学习活动的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%81%A5%E5%BA%B7?/249
- 城市水环境观察的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%81%A5%E5%BA%B7?/dgc
- 数字素养提升的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%81%A5%E5%BA%B7?/ppk
- 公共服务评价的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%81%A5%E5%BA%B7?/420=fic

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
