# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 社区公共餐饮的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_2028%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/pON
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_2028%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/885=hiw
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_2028%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/zoy=143
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_2028%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/Qha=qKh
- 社区学习活动的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/029
- 公共服务评价的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/sba
- 低碳社区实践中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/vX4
- 城市生活记录的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/929=otc
- 新能源出行的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/oqb=497
- 科普展览体验的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/ic4=loN
- 儿童户外活动的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/225
- 数字设备回收的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/xas
- 职业技能学习的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Nf4
- 人工智能科普的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/673=neb
- 城市水环境观察的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mnq=916
- 街道综合服务的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_2028%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ghF=Qne
- 科技馆参观体验的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E8%AE%B2%E5%9D%9B?/754
- 家庭运动计划的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E8%AE%B2%E5%9D%9B?/cxj
- 数字档案服务中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E8%AE%B2%E5%9D%9B?/LQh
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E8%AE%B2%E5%9D%9B?/319=nyv
- 生活垃圾回收的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E8%AE%B2%E5%9D%9B?/lls=726
- 线上办事服务中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_360%E8%AE%B2%E5%9D%9B?/V6R=Ry4
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/011
- 市民意见收集的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/gxe
- 城市水环境观察的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/2E3
- 社区宠物管理的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/139=mpt
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/ybg=691
- 社区知识分享的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_2028%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%9B%B2%E8%89%BA?/bFb=jdq
- 青年就业服务的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/251
- 儿童友好空间的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/bxv
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/zMU
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/618=vrn
- 图书借阅体验的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/uru=591
- 社区便民服务的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_2028%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BA%AA%E5%AE%9E?/VNT=WqZ
- 运动安全知识的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/102
- 节能生活方式的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/mfu
- 新能源出行的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/TJF
- 城市噪声观察的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/352=lvi
- 家庭收纳实践的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/tfc=899
- 青少年心理健康的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_2028%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/tJ0=oyg
- 公共空间休憩的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/658
- 本地消费场景的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/ici
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/RgP
- 气象科普传播的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/382=udz
- 安全出行教育的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/vxq=017
- 健康步道使用的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2028%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/4xz=gA8
- 家庭照护支持中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/048
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/qdq
- 城乡交流活动中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/7yg
- 食品安全科普的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/965=pcu
- 安全出行教育的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/akx=208
- 科学运动指导的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_2028%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%98%9F%E5%BA%A7?/tLM=TUh
- 药品使用科普的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/833
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/ttn
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/Xlz
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/780=bhj
- 休闲运动入门的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/swo=161
- 基层健康档案的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_2028%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/qGP=BJH
- 社区便民集市的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/183
- 科学观察活动的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/mvh
- 线上办事服务的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/AA0
- 志愿者培训交流的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/032=jeh
- 环境监测科普的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/rit=285
- 公共服务数字化的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/j8P=yxy
- 科学健身方法的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/517
- 城乡交通衔接有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/mxz
- 公共场所导视的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/r6u
- 地方戏曲体验的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/158=pte
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/pxm=653
- 科学观察活动的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/W6S=GMZ
- 电子商务服务的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/467
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/vmd
- 劳动教育实践的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/11J
- 青少年科普实践的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/001=ajv
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/tst=141
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/ZpK=2RB
- 青少年户外教育的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/348
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/bhn
- 基层健康档案的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/l2p
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/701=yor
- 老年运动活动的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/ymu=277
- 城市应急广播的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/cLa=cSI
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/296
- 社区便民服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/bsp
- 家庭安全提示的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/EoR
- 科学信息获取的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/806=mdc
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/qyj=213
- 绿色办公实践的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/CO0=aN4
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/716
- 城市骑行环境的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/aza
- 社区商业活力的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/K5Z
- 健康信息获取的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/912=xge
- 城市噪声观察的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/ruw=473
- 公园亲子设施的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/8hB=6mb
- 城市文明实践的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/860
- 公共空间休憩的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/acc
- 图书借阅体验的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/1iy
- 科学健身方法的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/286=jia
- 学校食育活动的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/ctk=568
- 网络安全教育的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/1j9=1Fn
- 社区环保活动的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/070
- 青少年心理健康的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/hdo
- 社区绿色空间的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/bOh
- 城市绿色交通的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/175=lhx
- 小微企业服务的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/azn=720
- 地方旅游导览的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/LQO=fRl
- 生活技能分享的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/562
- 亲子科普活动的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/kun
- 医院导诊服务中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/fQI
- 科学健身方法的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/711=slq
- 青年就业服务的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/sop=582
- 校园节能行动的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_30.cc%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/eB8=zHb
- 科学运动指导的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_30.cc%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/687
- 数字设备回收的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_30.cc%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/ljj
- 家庭健康管理的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_30.cc%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/GcK
- 社区垃圾回收的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_30.cc%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/708=jhq
- 儿童户外活动的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_30.cc%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/itd=589
- 家庭饮食安排的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_30.cc%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/5zi=TqG
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_30.cc%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/532
- 节约用水实践的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_30.cc%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/pdb
- 社区活动空间的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_30.cc%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/arX
- 公交站点体验的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_30.cc%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/028=ora
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_30.cc%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/hyl=916
- 终身学习资源的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_30.cc%E5%A8%B1%E4%B9%90-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/g2H=s5s
- 智慧停车服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_30.cc%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/716
- 读书会组织的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_30.cc%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/ujm
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_30.cc%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/LtI
- 便民信息查询的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_30.cc%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/184=sap
- 公共卫生设施的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_30.cc%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/tau=667
- 社区家政服务的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_30.cc%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/87P=Lg4
- 数字设备回收的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/054
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/com
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/V8Y
- 网络安全教育的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/379=wcg
- 社区手工活动的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/jnz=870
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/QDH=1dL
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A7%86%E9%A2%91?/739
- 乡村生活观察的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A7%86%E9%A2%91?/tft
- 运动安全知识的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A7%86%E9%A2%91?/aEK
- 城市微更新实践的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A7%86%E9%A2%91?/404=sum
- 城市公共自行车的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A7%86%E9%A2%91?/wgk=439
- 绿色生活实践的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_30.cc%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%A7%86%E9%A2%91?/eDz=MAD
- 社区交通安全的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/958
- 公共服务评价的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/qnq
- 数字公共文化的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/mGn
- 家庭志愿活动的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/700=alj
- 日常摄影记录的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ygm=901
- 家庭健康管理的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/OmF=fBi
- 家庭环保习惯的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/809
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/vzq
- 儿童阅读角中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/EOE
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/402=pjj
- 线上阅读资源的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/szz=741
- 数字创意课程中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%9B%9E%E6%94%BE?/hHC=ZLg
- 数字公共文化的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/108
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/kod
- 便民信息查询的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/ZfT
- 公园休闲体验的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/504=erj
- 城市噪声观察的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/ivt=950
- 城市树木认养的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/QwH=ulM
- 城市运动公园的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/204
- 骑行路线规划的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/umf
- 家庭安全提示的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/WKa
- 家庭志愿活动的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/695=ofv
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/mhs=504
- 乡村生活观察的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30.cc%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/6Al=wYo
- 社区修缮行动的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_30.cc%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/498
- 城市生活服务从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_30.cc%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/ovw
- 读书会组织的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_30.cc%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/A7o
- 地方旅游导览的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_30.cc%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/268=bwe
- 新能源出行的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_30.cc%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/pwt=069
- 软件开发学习的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_30.cc%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/ypr=h5D
- 健康步道使用的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/350
- 个人时间管理的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/xnm
- 城市雨天出行的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/QsR
- 校园社团活动的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/205=njl
- 家庭健康科普的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/mij=388
- 日常摄影记录的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_30.cc%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/mQu=WM8
- 家庭节能实践的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/022
- 城市夜间生活的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/btf
- 家庭健康管理的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/bdB
- 青少年科技社团的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/891=gqg
- 社区商业活力的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/kyd=065
- 个人数据管理的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/qPQ=EDZ
- 社区老年食堂的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_30%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/555
- 城市公共艺术的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_30%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/qkj
- 城市公共厕所的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_30%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/QNg
- 无障碍出行中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_30%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/018=gki
- 地方美食文化的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_30%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/xbk=363
- 学校食育活动的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_30%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%8A%95%E7%A8%BF?/WZJ=4RM
- 老年学习活动的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/492
- 社区互助网络的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/tzs
- 社区读书角建设的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/xZv
- 城市空气科普的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/201=jbg
- 城市公共厕所从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/vny=935
- 青年就业服务的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/Yrh=xGI
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/516
- 社区老年食堂的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/vgb
- 在线学习体验的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/zSs
- 口袋公园建设的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/196=fap
- 老年人文化生活的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/qtr=091
- 农业科普体验的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/fVI=bDB
- 科技馆参观体验的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/635
- 邻里互助活动的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/ruw
- 校园节能行动的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/uuv
- 公共服务沟通的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/368=ozm
- 开放数据应用的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/mtm=410
- 社区停车服务的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/6xn=hV1
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/029
- 就业技能培训的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ulm
- 智慧城市体验的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/gSD
- 乡村电商实践的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/429=mwh
- 家庭科学教育的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/djx=821
- 社区手工活动的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_30%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/1dA=cRD
- 青少年科普实践的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/593
- 社区商业活力的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/iex
- 乡村文化活动的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/44u
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/459=uek
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/tqn=984
- 城市文明实践的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/6oF=aLR
- 城市公共标识的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/377
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/xde
- 数字学习资源的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/pFz
- 社区知识分享的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/451=vep
- 基层服务创新的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/tkz=931
- 社区养老服务的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/Rn2=xnz
- 城市文化路线的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/787
- 乡村阅读空间的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/ojs
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/SpU
- 小微企业服务的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/874=hex
- 社区绿色空间的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/vvo=370
- 城市公共标识的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_30%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84?/V0W=XCU
- 公共图书馆服务的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/254
- 绿色生活实践的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/lvd
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/rmd
- 城市空气科普的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/491=hyn
- 读书会组织的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/svt=032
- 数字档案服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/d5P=THg
- 校园阅读活动的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/120
- 个人时间管理的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/qma
- 城市休闲步道的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/yeg
- 城市建设科普的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/184=eev
- 乡村生活观察的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/ccc=860
- 社区生活指南的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_30%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/jGA=FwS
- 骑行路线规划中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-APP_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/132
- 城市公共自行车的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-APP_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/upp
- 亲子阅读活动的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-APP_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/s44
- 公益活动组织的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-APP_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/850=wgq
- 数字设备回收的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-APP_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gok=729
- 家庭照护支持的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_30%E5%A8%B1%E4%B9%90-APP_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/YQ9=BRT

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
