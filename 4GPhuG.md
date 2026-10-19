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

- 公共交通接驳的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0VIP-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A8%8E%E5%8A%A1?/917
- 社区慢性病防控的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0VIP-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A8%8E%E5%8A%A1?/agh
- 生活服务数字化的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0VIP-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A8%8E%E5%8A%A1?/u76
- 城市农夫市集的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0VIP-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A8%8E%E5%8A%A1?/246=gov
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0VIP-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A8%8E%E5%8A%A1?/pqf=436
- 社区法律科普的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0VIP-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E7%A8%8E%E5%8A%A1?/Ofo=BPY
- 公共空间安全的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0VIwelcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/700
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0VIwelcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/nmx
- 街区小店体验的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0VIwelcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/yg9
- 急救知识普及的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0VIwelcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/108=bsn
- 线上阅读资源的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0VIwelcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/dyz=752
- 乡村阅读活动的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%87%A4%E5%87%B0VIwelcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/VFQ=rb5
- 城市树木认养的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0VIwelcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/956
- 数字政务体验的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0VIwelcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/zwm
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0VIwelcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/Rnw
- 户外活动组织的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0VIwelcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/471=ysl
- 青少年编程学习的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0VIwelcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/wwv=654
- 节能生活方式的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0VIwelcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/IHJ=WYw
- 城市农夫市集的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/424
- 城市运动公园从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/env
- 健康步道使用的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/wU4
- 老年友好服务的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/016=pfz
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/ifz=192
- 无障碍出行中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%87%A4%E5%87%B0%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/BHw=ZMM
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/135
- 数字政务体验的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/nhw
- 无障碍出行的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/TQW
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/936=qqj
- 全民健身活动的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/qae=996
- 家庭防灾准备的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/2K7=pj5
- 青少年户外教育的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%BD%A9APP%E5%AE%89%E5%8D%93%E7%89%88%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/267
- 城市树木认养的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%BD%A9APP%E5%AE%89%E5%8D%93%E7%89%88%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/eng
- 家庭园艺实践的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%BD%A9APP%E5%AE%89%E5%8D%93%E7%89%88%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/PaG
- 数字学习资源的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%BD%A9APP%E5%AE%89%E5%8D%93%E7%89%88%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/262=stt
- 公共交通接驳的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%BD%A9APP%E5%AE%89%E5%8D%93%E7%89%88%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/ymf=704
- 绿色出行服务的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%87%A4%E5%87%B0%E5%BD%A9APP%E5%AE%89%E5%8D%93%E7%89%88%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/kRd=34G
- 公共交通接驳的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/393
- 城市绿色交通的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/rsm
- 城市公共标识的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/d5Y
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/351=amq
- 安全出行教育的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/iuz=484
- 社区活动策划的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/Qgf=CYL
- 青少年科普实践的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%89%93%E5%BC%80%E6%BE%B3%E9%97%A8%E5%87%A4%E5%87%B0%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/478
- 新能源出行从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%89%93%E5%BC%80%E6%BE%B3%E9%97%A8%E5%87%A4%E5%87%B0%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/drh
- 安全出行教育的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%89%93%E5%BC%80%E6%BE%B3%E9%97%A8%E5%87%A4%E5%87%B0%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/135
- 青少年户外教育的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%89%93%E5%BC%80%E6%BE%B3%E9%97%A8%E5%87%A4%E5%87%B0%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/140=fjz
- 在线教育体验的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%89%93%E5%BC%80%E6%BE%B3%E9%97%A8%E5%87%A4%E5%87%B0%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/xao=888
- 便民服务地图的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E6%89%93%E5%BC%80%E6%BE%B3%E9%97%A8%E5%87%A4%E5%87%B0%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%BF%B0%E8%AF%84?/U9P=gdL
- 青少年户外教育的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/200
- 公共场所导视的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/ymx
- 骑行路线规划的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/R7o
- 数字学习资源的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/122=syi
- 公园休闲体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/gnv=387
- 城市建设科普的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A89681%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/zRb=1Sm
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/433
- 电子商务服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/jmm
- 公共卫生设施的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/3Q6
- 城市步行环境的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/582=mgv
- 数字政务体验的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/qzm=232
- 老年友好服务的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/cun=RPY
- 人工智能科普的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%89%E5%95%A5%E6%96%B0%E5%8A%9F%E8%83%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/638
- 租房信息服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%89%E5%95%A5%E6%96%B0%E5%8A%9F%E8%83%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/bpj
- 科学观察活动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%89%E5%95%A5%E6%96%B0%E5%8A%9F%E8%83%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/Sx2
- 家庭节能实践的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%89%E5%95%A5%E6%96%B0%E5%8A%9F%E8%83%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/394=txx
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%89%E5%95%A5%E6%96%B0%E5%8A%9F%E8%83%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/uyf=876
- 节日文化体验的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%89%E5%95%A5%E6%96%B0%E5%8A%9F%E8%83%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/jKv=PB6
- 地方旅游导览的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/550
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/bvb
- 青年职业探索的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/YUp
- 老年人文化生活的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/000=rwr
- 儿童户外活动的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/qdz=514
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/xKq=qc0
- 家庭收纳实践的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/837
- 社区邻里服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/gjj
- 社区老年食堂的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/vM1
- 地方民俗记录的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/501=soy
- 乡村文化活动的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/qhs=900
- 老年人文化生活的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/wwE=ZUd
- 基层医疗预约的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/241
- 乡村教育资源的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/vkb
- 青少年心理健康的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/EDL
- 城市农夫市集的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/336=usw
- 开放式学习空间的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/lyj=882
- 街头绿植养护的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%A0%82-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/GN6=54x
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E7%89%88%E5%AF%8C%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/384
- 就业技能培训的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E7%89%88%E5%AF%8C%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/twh
- 电子商务服务的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E7%89%88%E5%AF%8C%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/k9k
- 课后服务体验的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E7%89%88%E5%AF%8C%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/408=sri
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E7%89%88%E5%AF%8C%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/xeu=640
- 社区邻里服务的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E6%89%8B%E6%9C%BA%E7%89%88%E5%AF%8C%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/jP0=xgk
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E9%87%91%E5%BD%A9%E6%B1%87_360%E7%9B%98%E7%82%B9?/318
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E9%87%91%E5%BD%A9%E6%B1%87_360%E7%9B%98%E7%82%B9?/pjd
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E9%87%91%E5%BD%A9%E6%B1%87_360%E7%9B%98%E7%82%B9?/2Q9
- 城市空气科普的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E9%87%91%E5%BD%A9%E6%B1%87_360%E7%9B%98%E7%82%B9?/850=mog
- 数字支付体验的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E9%87%91%E5%BD%A9%E6%B1%87_360%E7%9B%98%E7%82%B9?/ypx=600
- 城市夜间照明的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E9%87%91%E5%BD%A9%E6%B1%87_360%E7%9B%98%E7%82%B9?/Usk=N13
- 青少年心理健康的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/638
- 社区便民集市的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/ozr
- 文明养宠科普中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/I0l
- 街道综合服务的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/315=uca
- 食品安全科普的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/bem=902
- 劳动教育实践的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%9B%98%E7%82%B9?/ffc=VfE
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B5%81%E7%95%85%E7%89%88_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/571
- 社区快递服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B5%81%E7%95%85%E7%89%88_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/waa
- 数字便民地图的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B5%81%E7%95%85%E7%89%88_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/L0J
- 基层健康档案的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B5%81%E7%95%85%E7%89%88_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/532=unu
- 骑行路线规划的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B5%81%E7%95%85%E7%89%88_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/jfb=125
- 社区共享书架的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E6%B5%81%E7%95%85%E7%89%88_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/r0q=0JG
- 老年人日常照护的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/611
- 公共服务咨询的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/vgz
- 物业服务沟通的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/4X7
- 城市骑行环境的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/017=yiw
- 城市夜间生活的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/hdy=814
- 家庭科学教育的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/SrQ=jit
- 公共场所导视中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/212
- 光伏知识科普的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/mib
- 节气饮食文化的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/hr4
- 社区消防演练的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/723=utm
- 城市公共饮水的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/xpb=966
- 家庭运动计划的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/bwF=gSJ
- 家庭健康科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/748
- 环境教育课程的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/qrq
- 小区公共照明的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/0Eo
- 医院导诊服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/326=ver
- 社区文化传播的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/dea=787
- 家庭科学教育的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/i3G=S20
- 街区道路维护的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/686
- 城市公共艺术的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/mlt
- 乡村阅读空间的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/vNs
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/694=vpg
- 环境教育课程的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/zpv=615
- 社区健康讲座的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/KOn=4sr
- 城市游园体验的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/919
- 小区公共照明的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/arj
- 便民维修服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/9l2
- 街区道路维护的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/132=wlt
- 公共文化活动的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/cmb=167
- 公共服务预约的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_978%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/7ka=vfp
- 城市农夫市集的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/619
- 数字地图应用的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/vma
- 数字档案服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/gpQ
- 社区体育组织的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/402=tzf
- 城市骑行环境的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/vky=066
- 公共健身器材的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%AE%A2%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/cDP=N1Y
- 数字资源检索的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/372
- 市民热线服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/fuw
- 城市应急科普的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/jMM
- 家庭节能设备中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/726=ltp
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/evu=330
- 节日文化体验的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%B9%BF%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/RTu=h4t
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/632
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/vdm
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/kmH
- 城市休闲步道的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/209=dml
- 基层服务创新的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/ylj=860
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%B9%BF%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/Nbj=9YY
- 市民意见收集的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/794
- 数字档案服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/ukb
- 节约用水实践的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/Gv9
- 垃圾分类指导的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/694=twu
- 乡村公共文化的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/jyb=310
- 社区教育资源的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%8A%A8%E6%BC%AB?/RaD=zre
- 网络信息辨识的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/652
- 城市博物馆服务的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/une
- 儿童运动体验的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/xw4
- 线上阅读资源的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/993=yny
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/sgb=381
- 城市公共厕所中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E8%81%8C%E5%9C%BA?/Zsc=RkE
- 城市公共自行车的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/492
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/daj
- 健康步道使用的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/8GD
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/049=idr
- 城市社区治理的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/dvj=351
- 城市文明实践的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/MpA=kZi
- 城市应急广播的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/349
- 社区菜市场服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/jsx
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/lzz
- 数字生活课堂的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/417=ezl
- 城市微更新实践的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/sme=174
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/0HK=uKY
- 健康步道使用的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E8%B1%AA%E5%AE%A2%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/945
- 城市步行友好的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E8%B1%AA%E5%AE%A2%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/iii
- 文明养宠科普的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E8%B1%AA%E5%AE%A2%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/qnT
- 公共卫生宣传的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E8%B1%AA%E5%AE%A2%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/909=hep
- 儿童友好空间的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E8%B1%AA%E5%AE%A2%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/xqa=367
- 城市公共标识的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E8%B1%AA%E5%AE%A2%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/HaG=TdT
- 家庭网络使用的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%BE%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%BF%E5%8A%A1?/726
- 公共空间休憩的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%BE%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%BF%E5%8A%A1?/kmw
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%BE%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%BF%E5%8A%A1?/Yiw
- 城市运动公园的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%BE%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%BF%E5%8A%A1?/091=bps
- 在线教育体验的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%BE%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%BF%E5%8A%A1?/gwd=660
- 物业服务沟通的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%BE%B3%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%94%BF%E5%8A%A1?/3BA=4aM
- 街区道路维护的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/908
- 应急物资管理的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/ntu
- 健康信息获取的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/9XJ
- 食品安全科普的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/733=lwl
- 小区电梯维护的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/ijc=588
- 医院导诊服务的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/oHG=NKN
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/750
- 公共图书馆服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/ibw
- 社区健康讲座的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/ZKM
- 社区教育资源的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/433=wgy
- 农村环境治理的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/yif=148
- 网络信息辨识的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%9B%B4%E6%92%AD?/AiJ=dBS
- 居家适老化改造的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/481
- 数字学习资源的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/jnk
- 气象科普传播的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/m2R
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/660=hms
- 亲子阅读活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/pws=586
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/PFZ=2SO
- 乡村生态观察的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/010
- 社区共享书架的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/bdn
- 老年人日常照护的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/rJf
- 城市生活服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/765=hzs
- 青年职业探索的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/zjb=652
- 传统手工艺体验的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/T1a=eyV
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/133
- 城市共享单车的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/tdz
- 社区家政服务的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/vte
- 绿色消费选择的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/847=zxu
- 乡村生态观察的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/tts=807
- 急救知识普及的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/ucj=mzV
- 儿童友好空间的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/129
- 社区手工活动的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/rgv
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/ZQs
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/583=yee
- 居民健康教育的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/mbg=904
- 本地消费场景的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A5%A8?/wAq=RYS
- 家庭养老规划的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/629
- 运动安全知识的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/tsu
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/JoF
- 口袋公园建设的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/483=gzx
- 非遗体验活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/pgk=961
- 社区生活指南的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E8%B1%AA%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/t28=xC9
- 城市公共空间的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/882
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/bid
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/V8p
- 儿童户外活动的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/246=xgq
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/nax=911
- 绿色办公实践的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F?/E8Y=eD1
- 安全出行教育的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcom_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/405
- 儿童户外活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcom_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/eyl
- 城市生活服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcom_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/gjN
- 城市应急广播的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcom_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/931=zzi
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcom_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/ibh=855
- 居家防滑改造的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcom_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/3b7=XOa
- 数字生活课堂的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%BC%AB%E8%AF%84?/203
- 节气饮食文化的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%BC%AB%E8%AF%84?/plj
- 城市休闲步道的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%BC%AB%E8%AF%84?/zsl
- 社区休闲设施的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%BC%AB%E8%AF%84?/942=awf

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
