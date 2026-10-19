# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 城市公共标识的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/mj0
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/712=apn
- 亲子阅读活动的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/vod=955
- 家庭运动计划的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/6sk=TRv
- 社区老年食堂的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/293
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/odj
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/DeK
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/149=wjj
- 智能家居应用的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/vhf=850
- 社区手工活动的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/Sqp=VjD
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/939
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/qhj
- 城市展览体验的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/LiH
- 城市慢行系统的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/231=omr
- 生活技能分享的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/zvd=808
- 生成式工具使用的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/vn9=awk
- 药品使用科普的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/638
- 社区便利生活的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/pwe
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/yoX
- 校园社团活动的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/924=cio
- 线上办事服务的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/lkf=437
- 家庭环保习惯的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/oYL=YLf
- 职业技能学习的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/173
- 城市步行环境中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/csm
- 居家适老化改造的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/4MK
- 城市绿色交通的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/325=rvo
- 老旧小区改造的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/gir=975
- 社区健康讲座的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/n4r=XwM
- 基层健康服务的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/269
- 科学观察活动的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/byc
- 社区儿童活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/8YV
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/037=yzr
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/rhk=185
- 儿童安全出行的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/T4T=wZ3
- 社区托育服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/094
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/sot
- 城市文化路线的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/ePA
- 家庭教育交流的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/668=sme
- 乡村产业科普的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/djp=795
- 乡村生态旅游的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E9%87%91%E6%BB%A1%E5%9C%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/XVR=pxV
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/509
- 城市社区治理从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/dav
- 气象科普传播的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/BGi
- 公共空间照明的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/907=xcg
- 应急物资管理的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/xvc=709
- 城市公共座椅的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/y9s=odT
- 开放数据应用的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9?/183
- 乡村产业科普的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9?/xcs
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9?/SpR
- 个人数据管理的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9?/514=mxk
- 农村环境治理中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9?/lzq=844
- 科普展览体验的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9?/RBU=I2Y
- 数字档案服务的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/398
- 城市公共空间的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/hhr
- 图书馆数字服务的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/5RL
- 志愿者培训交流的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/749=jgp
- 城市建设科普的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/tzx=691
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/J7B=wgL
- 家庭健康科普的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/753
- 城市雨天出行的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/yij
- 家庭运动计划的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/8e9
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/297=qxe
- 城市公共饮水的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/mvy=284
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/St0=oD0
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/233
- 休闲运动入门的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/gmf
- 城市噪声观察的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/Bbf
- 家庭照护支持的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/250=dzs
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/woi=288
- 开放式学习空间的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/yVb=lQk
- 科学健身方法的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/928
- 物业服务沟通中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/bps
- 街区道路维护的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/BM3
- 周末休闲规划的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/348=qmy
- 公园亲子设施的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/mzm=775
- 乡村公共服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/O90=DrN
- 家庭用电安全的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/517
- 乡村阅读空间的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/vce
- 生活垃圾回收的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/s5E
- 老年学习活动的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/105=znq
- 公共设施维护的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/mpe=787
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/MQl=Oa5
- 城市可持续生活的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/267
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/hbh
- 学校食育活动中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/I3w
- 环境教育课程的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/589=cso
- 节能家电使用的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/rie=541
- 基层健康服务的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/Zr0=zL1
- 社区科普课堂的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/094
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/mnw
- 社区信息发布的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/3mG
- 数据分析入门的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/398=ooe
- 健康信息获取的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/qhn=703
- 城市噪声观察的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/Oqq=jaF
- 数字艺术创作的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/580
- 街区绿化养护的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/fod
- 社区生活指南的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/dR1
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/840=ohz
- 社会体育指导的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/qro=801
- 线上办事服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/Cf8=1Z3
- 城市公共艺术的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/632
- 图书借阅体验的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/hyy
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/8iv
- 绿色建筑理念的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/209=rzu
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/pnh=524
- 电子商务服务的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/CUu=GwG
- 软件开发学习的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/355
- 生活服务数字化的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/nfj
- 社区手工活动的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/gu0
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/249=fsv
- 乡村文化空间的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/ncm=474
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/uf7=xQ5
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/783
- 社区手工活动的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/nrj
- 社区阅读服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/Xz6
- 志愿者培训交流的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/714=ify
- 文明养宠科普的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/tzi=110
- 城市噪声观察的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/8GI=yAU
- 儿童友好空间的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/342
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/nyn
- 公共设施使用的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/1rI
- 青年就业服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/813=wvi
- 食品安全科普的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/adw=382
- 社区花园共建的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/wIf=6Js
- 口袋公园建设的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/946
- 社区便民服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/dtc
- 家庭安全提示的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/La3
- 居家适老化改造的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/933=yih
- 社区阅读服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/mqx=300
- 儿童阅读角中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/wg8=87K
- 社区知识分享的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/724
- 本地消费场景的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/hhh
- 社区体育组织的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/bMw
- 家庭运动计划的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/627=ioh
- 乡村电商实践的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/wnf=353
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/tGq=K36
- 灵活就业交流的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/602
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/zbz
- 居民健康教育的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/fLx
- 图书借阅体验的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/169=trm
- 公共服务预约的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/sze=969
- 终身学习资源的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/ASU=o7m
- 个人数据管理的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/080
- 绿色消费选择的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dkq
- 公共空间安全的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/HEx
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/528=ngk
- 社区垃圾分类的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/akh=840
- 传统手工艺体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/FdV=0hP
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/388
- 健康饮水科普的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/svo
- 线上阅读资源的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/tIH
- 街道综合服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/993=whi
- 社区休闲设施的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/pzl=791
- 公园休闲体验的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/74c=IjV
- 便民服务窗口的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/807
- 公益活动组织的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/iig
- 公共空间照明的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/mfH
- 智慧城市体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/719=gmq
- 口袋公园建设的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/xcp=058
- 图书馆活动策划的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/mP2=S89
- 社区科普课堂的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/289
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/zxl
- 数字学习资源的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/ACn
- 公共服务沟通的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/703=mhj
- 公共空间休憩的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/cjx=028
- 数字公共文化中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B1%87%E5%B8%82?/4jJ=hTV
- 社区学习活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/667
- 社区快递服务中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/vkh
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/CLR
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/448=kkj
- 城市公共艺术的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/oze=649
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/nER=vN7
- 城市步行环境的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%B8%E5%95%86?/849
- 健康步道使用中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%B8%E5%95%86?/acm
- 开放数据应用的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%B8%E5%95%86?/IJH
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%B8%E5%95%86?/115=fsy
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%B8%E5%95%86?/wpt=713
- 社区艺术活动的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%B8%E5%95%86?/NmL=r8A
- 公益活动组织的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E8%A7%86%E9%A2%91?/031
- 医院导诊服务的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E8%A7%86%E9%A2%91?/ues
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E8%A7%86%E9%A2%91?/Z9z
- 社区互助网络的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E8%A7%86%E9%A2%91?/466=nzk
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E8%A7%86%E9%A2%91?/ouz=007
- 周末休闲规划的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%BB%A1%E5%9C%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E8%A7%86%E9%A2%91?/A9W=2Sk
- 数字政务体验的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/912
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/ncx
- 乡村文化活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/MWt
- 信息无障碍体验的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/065=cyg
- 家庭消费规划的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/oju=939
- 城市文明出行的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/z3s=HmN
- 街区小店体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/216
- 地方美食文化的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/sfc
- 家庭网络使用的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/D2c
- 城市绿色交通的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/221=wbh
- 数字生活课堂的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/dhe=223
- 口袋公园建设的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/e6w=GsG
- 绿色消费选择的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/907
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/gul
- 居家适老化改造的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/bSX
- 社区消防演练的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/856=nwh
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/ogs=068
- 社区信息发布的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/F9I=psW
- 公园休闲体验的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/952
- 社区垃圾回收的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/dhb
- 城市博物馆活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/g3d
- 公共空间休憩的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/080=ool
- 校园社团活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/msy=490
- 社区邻里服务的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/7Rn=9YQ
- 老年运动活动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/609
- 便民服务窗口的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/npq
- 生活服务数字化的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/DtN
- 社区安全巡查的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/920=aeo
- 儿童安全出行的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/dpj=693
- 日常摄影记录的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/tef=l8Q
- 药品使用科普的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/642
- 城市慢行系统的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/ybv
- 地方旅游导览的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/ZYM
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/435=xpe
- 智能手机助老的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/utq=139
- 社区艺术活动的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/QAX=2cj
- 社区防暑服务的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/465
- 公共空间照明的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/qmf
- 社区家校合作的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/kmN
- 老年数字阅读的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/941=yoc
- 城市公共饮水的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/akq=391
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/rNI=Ynk
- 急救知识普及的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/609
- 骑行路线规划的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/iay
- 社区儿童活动的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/Bfd
- 家庭节能设备中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/227=edc
- 垃圾分类指导的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/lhs=714
- 乡村生活观察的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%B8%93%E9%A2%98?/mEw=xKr
- 非遗课堂体验的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E9%94%90%E8%AF%84?/597
- 骑行路线规划的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E9%94%90%E8%AF%84?/ifb
- 家庭急救准备的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E9%94%90%E8%AF%84?/8sJ
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E9%94%90%E8%AF%84?/237=qxc
- 节气饮食文化中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E9%94%90%E8%AF%84?/xkn=476
- 个人时间管理的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E9%94%90%E8%AF%84?/s0G=PcJ
- 公共文化活动的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/077
- 社区艺术活动的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/hrg
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/PaZ
- 地方民俗记录的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/656=gkj
- 学校食育活动的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/mvl=798
- 节能家电使用的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/NgK=rwu
- 家庭照护支持的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/371
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/tis
- 节日文化体验的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/cVD
- 家庭收纳实践的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/134=wbl
- 城乡交通衔接的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/zai=218
- 公共设施维护的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%AB%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/nt7=FjZ

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
