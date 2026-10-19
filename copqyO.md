# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_gopay%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/483
- 基层医疗预约的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_gopay%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/uqq
- 乡村电商实践的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_gopay%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/52s
- 绿色消费选择的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_gopay%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/986=bag
- 绿色校园实践的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_gopay%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/fny=424
- 乡村公共阅读的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_gopay%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%BF%B0%E8%AF%84?/y0h=30k
- 城市公共饮水的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_gopay%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/070
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_gopay%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/fet
- 社区法律科普的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_gopay%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/Qpr
- 数字课堂应用的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_gopay%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/541=ouf
- 城市社区治理的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_gopay%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/xip=030
- 社区文化传播的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_gopay%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/TdO=arT
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_gopay%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/902
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_gopay%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/ffm
- 市民意见收集的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_gopay%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/4ve
- 数字学习资源的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_gopay%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/776=vlj
- 社区绿色空间的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_gopay%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/opn=924
- 乡村教育资源的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_gopay%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BA%B2%E5%AD%90?/6qB=XI9
- 机器人科普活动的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_gopay%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/978
- 社区休闲设施的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_gopay%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/mkx
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_gopay%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/Bnr
- 图书馆活动策划的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_gopay%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/701=ygk
- 社区家校合作的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_gopay%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/woc=970
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_gopay%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/6na=XVt
- 物业服务沟通的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_gopay%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_360%E8%A1%8C%E6%83%85?/975
- 城市步行环境的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_gopay%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_360%E8%A1%8C%E6%83%85?/orm
- 社区快递服务的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_gopay%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_360%E8%A1%8C%E6%83%85?/Ko8
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_gopay%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_360%E8%A1%8C%E6%83%85?/958=pkv
- 城市公共座椅的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_gopay%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_360%E8%A1%8C%E6%83%85?/rce=543
- 家庭节能设备的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_gopay%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_360%E8%A1%8C%E6%83%85?/q6o=xJt
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_gopay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/597
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_gopay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/ukw
- 非遗课堂体验的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_gopay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/SbD
- 智能家居应用的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_gopay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/317=xps
- 社区健康讲座的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_gopay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/pof=034
- 城市基础设施中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_gopay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/RnF=bE6
- 地方戏曲体验的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/521
- 街区道路维护的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/snp
- 生成式工具使用的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/m5M
- 乡村产业科普的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/035=tuq
- 公共空间休憩的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/vnt=198
- 城市公共自行车的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/O6A=1TQ
- 城市基础设施的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/758
- 市民意见收集的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/ynh
- 本地旅行体验的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/uPV
- 小区公共照明的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/333=iqa
- 家庭防灾准备的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/ufz=000
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/iCA=k1D
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/579
- 城市地名文化的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/rcy
- 本地消费场景的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/NUH
- 社区邻里服务的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/300=gps
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/opv=521
- 老年智能设备的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_gopay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/tL3=Kcs
- 公共设施使用的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/364
- 地方旅游导览的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/nps
- 课后服务体验的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/XBj
- 课后服务体验的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/210=zef
- 数字便民地图的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/xer=954
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_gopay%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/Qa5=3x8
- 健康步道使用的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_gopay%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81app%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/841
- 节气饮食文化的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_gopay%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81app%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/jdc
- 垃圾分类指导的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_gopay%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81app%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/eSa
- 无障碍出行的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_gopay%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81app%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/128=hge
- 城市体育设施的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_gopay%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81app%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/cbq=697
- 学校食育活动的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_gopay%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81app%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/DX7=Ts1
- 城市适老服务的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_gopay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/673
- 公益活动组织的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_gopay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/sxd
- 无障碍信息设计的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_gopay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/b3X
- 信息无障碍体验的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_gopay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/323=lbt
- 学校体育活动的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_gopay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/ysd=938
- 农产品品牌传播的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_gopay%E9%92%B1%E5%8C%85%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%90%88%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/SpV=KRL
- 社区互助网络的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_gopay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%882024_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/716
- 公交无障碍服务的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_gopay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%882024_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/usb
- 读书会组织的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_gopay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%882024_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/gyH
- 智慧城市体验的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_gopay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%882024_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/441=mby
- 家庭运动计划的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_gopay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%882024_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/ihe=453
- 儿童阅读角的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_gopay%E9%92%B1%E5%8C%85app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%882024_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/lGf=Dkp
- 社区法律科普的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/535
- 社区防暑服务的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/zzj
- 青少年户外教育的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/EXN
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/039=ras
- 医院导诊服务的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/wpc=557
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/ZU0=AN0
- 开放式学习空间的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_gopay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/111
- 地方美食文化的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_gopay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/ddm
- 公共空间照明的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_gopay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/vwU
- 环境监测科普的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_gopay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/631=cav
- 乡村产业科普的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_gopay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/kal=379
- 图书借阅体验的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_gopay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E6%96%B0%E6%B5%AA%E4%BA%B2%E5%AD%90?/3Ui=7oM
- 城市夜间照明的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_gopay%E9%92%B1%E5%8C%85%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/365
- 网络安全教育的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_gopay%E9%92%B1%E5%8C%85%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/wxt
- 街道综合服务的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_gopay%E9%92%B1%E5%8C%85%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/HJK
- 本地消费场景的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_gopay%E9%92%B1%E5%8C%85%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/420=dkw
- 图书馆亲子空间的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_gopay%E9%92%B1%E5%8C%85%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/vje=197
- 城市人文观察的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_gopay%E9%92%B1%E5%8C%85%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/D80=VMh
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_gopay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/595
- 食品安全科普的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_gopay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/sqf
- 老年数字阅读的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_gopay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/Lee
- 社区防暑服务的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_gopay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/322=oqt
- 节能生活方式的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_gopay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/xhv=866
- 社区消防演练的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_gopay%E9%92%B1%E5%8C%85%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/XiQ=glL
- 小微企业服务的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_gopay%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%95%85%E6%B8%B8?/677
- 旧物循环利用的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_gopay%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%95%85%E6%B8%B8?/hel
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_gopay%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%95%85%E6%B8%B8?/E5l
- 小区公共照明的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_gopay%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%95%85%E6%B8%B8?/249=grn
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_gopay%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%95%85%E6%B8%B8?/jiy=464
- 城市公共厕所的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_gopay%E6%94%AF%E4%BB%98%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%95%85%E6%B8%B8?/nip=v7W
- 数字便民地图的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/181
- 便民服务窗口的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/syz
- 社区公共卫生的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/j1k
- 开放式学习空间的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/764=tju
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/bgv=396
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_gopay%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/l6P=pxW
- 数字课堂应用的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_gopay%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/100
- 灵活就业交流的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_gopay%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/xjo
- 便民服务窗口的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_gopay%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/Kss
- 家庭科学教育的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_gopay%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/835=vjo
- 乡村文化活动的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_gopay%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/dvj=753
- 食品配送体验的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_gopay%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%BA%BA%E7%89%A9?/i0M=UYg
- 城市公共艺术的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_kdpay%E9%92%B1%E5%8C%85_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/401
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_kdpay%E9%92%B1%E5%8C%85_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/aai
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_kdpay%E9%92%B1%E5%8C%85_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/ExD
- 线上办事服务的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_kdpay%E9%92%B1%E5%8C%85_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/699=cir
- 儿童友好空间的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_kdpay%E9%92%B1%E5%8C%85_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/axh=743
- 健康饮水科普从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_kdpay%E9%92%B1%E5%8C%85_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AE%AF?/Fd6=P6c
- 无障碍信息设计的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_kdpay%E9%92%B1%E5%8C%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/292
- 亲子科普活动中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_kdpay%E9%92%B1%E5%8C%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/ydl
- 老年友好服务的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_kdpay%E9%92%B1%E5%8C%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/2UF
- 城市公共艺术的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_kdpay%E9%92%B1%E5%8C%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/715=ykf
- 科学信息获取的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_kdpay%E9%92%B1%E5%8C%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/dpu=395
- 家庭科学教育的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_kdpay%E9%92%B1%E5%8C%85app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/erY=xiy
- 城市适老服务的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/419
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/ygr
- 医院导诊服务的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/M3y
- 公共空间导览的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/922=gae
- 老年友好服务的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/kgt=241
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/w00=DUb
- 儿童运动体验的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/401
- 绿色快递包装的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/zgo
- 老年智能设备的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/pSp
- 无障碍出行的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/791=yve
- 社区信息发布的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/zaa=352
- 城市公共艺术的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E7%95%85%E6%B8%B8?/rsq=h4H
- 数字艺术创作的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/008
- 邻里互助活动的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/rcr
- 社区故事采集的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/Kmk
- 社区心理支持的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/826=sov
- 传统节日科普的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/xfp=320
- 城市公共饮水的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_kdpay%E9%92%B1%E5%8C%85%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/DfW=t3b
- 小区公共照明的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/398
- 公共空间导览的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/yrh
- 青年就业服务中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/zhE
- 社区养老服务的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/525=ksr
- 城市骑行环境的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/bes=019
- 地方民俗记录的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E6%80%8E%E4%B9%88%E6%89%BE%E4%B8%8D%E5%88%B0_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/dFV=77C
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%BA%A4%E6%98%93_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/337
- 邻里共享空间的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%BA%A4%E6%98%93_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/saz
- 家庭用电安全的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%BA%A4%E6%98%93_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/jlQ
- 社区阅读服务的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%BA%A4%E6%98%93_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/416=nug
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%BA%A4%E6%98%93_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/xdj=193
- 家庭用电安全的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85%E6%80%8E%E4%B9%88%E4%BA%A4%E6%98%93_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/7KL=gze
- 网络信息辨识的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85app_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/822
- 休闲运动入门的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85app_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/xfc
- 小区停车协商的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85app_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/7pA
- 智慧城市体验的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85app_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/899=kic
- 地方戏曲体验的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85app_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/hjh=786
- 电子商务服务的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_kdpay%E9%92%B1%E5%8C%85app_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/G5p=6bO
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/825
- 社区交通安全的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/adu
- 社区活动空间的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/Obp
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/012=szg
- 社区快递服务的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/xce=289
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/Y1r=eRJ
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/948
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/aqs
- 公共服务沟通的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/3aW
- 公共服务数字化的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/958=pkl
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/nvo=357
- 城市噪声观察的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/xZW=KLc
- 城市社区治理的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/620
- 城市空气科普的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/jpy
- 城市公共艺术的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/w1D
- 数字公共文化的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/816=iyp
- 青年就业服务的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/wdj=316
- 城市文明出行的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/SOZ=lWR
- 城市公共艺术的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BDios_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/516
- 社区停车服务的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BDios_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/ops
- 社区便利生活的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BDios_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/EVf
- 城市便民驿站的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BDios_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/898=ppx
- 儿童运动体验的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BDios_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/ihl=067
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BDios_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/CA0=G9p
- 绿色消费选择的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/717
- 数字生活课堂的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/lzq
- 绿色生活实践的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/vun
- 社区教育资源的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/538=esl
- 老年友好服务的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/gci=810
- 数字阅读服务的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/plG=H4N
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C?/746
- 科学教育活动的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C?/gmb
- 科学信息获取的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C?/Rax
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C?/861=jtg
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C?/eig=082
- 户外活动组织的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C?/4nM=Tm9
- 乡村阅读空间的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/666
- 个人数据管理的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/wmh
- 日常摄影记录的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/Pxt
- 社区家政服务的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/156=gxs
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/xef=945
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/DkE=85w
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/462
- 老年人文化生活的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/etz
- 社区学习活动的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/iA8
- 健康步道使用的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/482=qxx
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/ukw=882
- 家庭用电安全的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/OFg=3hA
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/974
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/dbe
- 家庭安全提示的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/me9
- 城市步行友好的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/968=uzi
- 远程协作工具的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/jjs=132
- 社区休闲设施的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_kdpay%E9%92%B1%E5%8C%85%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E6%96%B0%E9%97%BB?/RiQ=G7a
- 邻里互助活动的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_kdpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/368
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_kdpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/vzr
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_kdpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/Vr2
- 全民阅读推广的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_kdpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/254=xhs
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_kdpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/hyk=381
- 租房信息服务的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_kdpay%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/Vms=q4G
- 公共服务沟通的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_k%E8%B1%86%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/761
- 小区停车协商的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_k%E8%B1%86%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/htl
- 数字创作工具的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_k%E8%B1%86%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/9FJ
- 乡村教育资源的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_k%E8%B1%86%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/459=htf
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_k%E8%B1%86%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/hnc=813
- 数字学习资源的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_k%E8%B1%86%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E8%AE%BF%E8%B0%88?/QOw=oE1
- 科学运动指导的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_K%E8%B1%86%E9%92%B1%E5%8C%85_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/945
- 家庭节能实践中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_K%E8%B1%86%E9%92%B1%E5%8C%85_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/rgs
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_K%E8%B1%86%E9%92%B1%E5%8C%85_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/Y3m
- 社区公共议事的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_K%E8%B1%86%E9%92%B1%E5%8C%85_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/684=eco
- 社区便民集市的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_K%E8%B1%86%E9%92%B1%E5%8C%85_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/mnm=868
- 社区应急准备的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_K%E8%B1%86%E9%92%B1%E5%8C%85_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/gqW=zeG
- 公交无障碍服务的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_kdpay%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/728
- 城市体育设施的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_kdpay%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/mys
- 绿色出行服务的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_kdpay%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/zzB
- 本地消费场景的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_kdpay%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/306=uei
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_kdpay%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/fuw=823
- 城市建设科普的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_kdpay%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/HjV=FGh
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/213
- 线上阅读资源中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/dpg
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/gFO
- 绿色生活实践从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_kdpay%E9%92%B1%E5%8C%85%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/383=fui

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
