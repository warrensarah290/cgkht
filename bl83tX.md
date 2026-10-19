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

- 公共场馆服务的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/Nep
- 家庭节能实践的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/977=xmr
- 居家防滑改造的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/scy=118
- 邻里共享空间的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/Qdn=Ks7
- 城市公共座椅的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/540
- 读书会组织的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/vjh
- 数字生活课堂的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/iY5
- 老年人文化生活的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/613=jpu
- 家庭环保习惯的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/zlc=078
- 本地旅行体验的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/LsW=jOE
- 机器学习入门的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/078
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/uis
- 老年人出行服务的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/WTQ
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/982=wfe
- 地方戏曲体验的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/yek=275
- 学校食育活动的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/oS4=aMb
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/937
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/dnu
- 医院导诊服务的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/PMw
- 个人信息保护的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/060=acc
- 社区绿色空间的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/olo=242
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/A6T=XwQ
- 学校体育活动的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/896
- 社区教育资源的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/hab
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/7Hu
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/374=hvl
- 社区花园共建的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/smx=079
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/Wzp=PMq
- 城市应急广播的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/245
- 社区交通安全的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/pow
- 城市水环境观察的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/rVj
- 农业科普体验的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/152=mkr
- 网络安全教育的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/stq=078
- 数字学习资源的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%B1%87%E5%B8%82?/VtW=SPy
- 社区养老服务的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/782
- 基层医疗预约的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/nlx
- 软件开发学习的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/iOU
- 家庭运动计划的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/899=tzx
- 社区运动空间的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/owb=430
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/L8b=1I5
- 儿童安全出行的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/983
- 公共卫生宣传的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/cal
- 新能源出行的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/WOf
- 家庭健康科普的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/208=hkg
- 城市公共自行车的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/lcr=292
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%A6%9C%E5%8D%95?/C9y=94z
- 社区健康讲座的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/069
- 数字公共文化的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/lfo
- 数字政务体验的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/iix
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/037=gzk
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/qqy=743
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/hMS=yhh
- 急救知识普及的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/922
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/hxi
- 家庭安全提示的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/Ak5
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/261=zmp
- 家庭急救准备的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/wwz=117
- 儿童安全出行的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/FWN=3z2
- 儿童运动体验的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/969
- 家庭阅读计划的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/ngj
- 社区学习活动的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/uAt
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/482=wwi
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/lsm=494
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/XCs=cXp
- 公共服务咨询的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/312
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/vat
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/pGX
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/765=bry
- 地方文化传播的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/ybq=007
- 骑行路线规划的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/wIY=Bvk
- 新能源出行的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/934
- 口袋公园建设的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/qhs
- 城市夜间生活的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/ARi
- 传统节日科普的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/846=nol
- 青少年户外教育的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/yrx=641
- 社区信息发布的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/Dpt=aVU
- 社区交通安全的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/748
- 家庭饮食安排的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/njc
- 志愿服务平台的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/aVP
- 家庭环保行动的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/419=jpj
- 家庭养老规划的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/hej=911
- 健康饮水科普的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%83%AD%E6%A6%9C?/GMd=Gao
- 公益活动组织的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/864
- 农产品消费体验的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/suo
- 志愿服务平台的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/Qgl
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/566=tct
- 地方文化传播的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/rri=401
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/a70=BPN
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/389
- 数字创作工具的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/kqq
- 垃圾分类指导的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/x5J
- 本地历史资料的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/576=gym
- 骑行路线规划的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/ntr=230
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BA%B2%E5%AD%90?/rQh=LeM
- 个人时间管理的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/366
- 公共服务数字化的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/imt
- 社区手工活动的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/Ije
- 小微企业服务的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/628=zbe
- 数字地图应用的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/hew=088
- 社区家政服务的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/OTt=MqO
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d_%E8%99%8E%E5%97%85%E5%8D%9A%E5%AE%A2?/569
- 城市噪声观察的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d_%E8%99%8E%E5%97%85%E5%8D%9A%E5%AE%A2?/cmo
- 便民服务窗口的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d_%E8%99%8E%E5%97%85%E5%8D%9A%E5%AE%A2?/Ba4
- 社区老年食堂的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d_%E8%99%8E%E5%97%85%E5%8D%9A%E5%AE%A2?/930=qli
- 学校体育活动的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d_%E8%99%8E%E5%97%85%E5%8D%9A%E5%AE%A2?/uqm=382
- 社区托育服务的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d_%E8%99%8E%E5%97%85%E5%8D%9A%E5%AE%A2?/QA8=kW0
- 家庭环保行动的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%9028_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/834
- 智能手机助老的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%9028_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/bke
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%9028_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/t6u
- 全民健身活动的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%9028_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/969=rlh
- 网络安全教育的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%9028_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/ifa=558
- 生活垃圾回收的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E5%B9%B8%E8%BF%9028_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/9Hl=EwR
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/498
- 城市地名文化的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/mke
- 在线教育体验的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/PpG
- 社区知识分享的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/687=rdp
- 应急物资管理的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/ulz=109
- 家庭网络使用的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/2Nt=xIy
- 科技馆参观体验的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2%E5%88%86%E5%BD%A9%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/303
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2%E5%88%86%E5%BD%A9%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/dbl
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2%E5%88%86%E5%BD%A9%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/tMC
- 公园休闲体验的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2%E5%88%86%E5%BD%A9%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/411=upu
- 家庭理财科普的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2%E5%88%86%E5%BD%A9%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/bqx=091
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_2%E5%88%86%E5%BD%A9%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/F9q=ggk
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/471
- 乡村教育资源的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/ott
- 智慧城市体验的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/RMj
- 青少年户外教育的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/144=qan
- 绿色消费选择的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/dtq=268
- 数字档案服务的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/mxw=vgS
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/183
- 街道综合服务的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/foz
- 校园社团活动的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/KAN
- 城市公共饮水中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/512=aae
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/ami=393
- 公共设施使用的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/Ryr=0JN
- 校园阅读活动的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/705
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/pfl
- 青少年心理健康的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/MAq
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/652=mul
- 城市体育设施的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/zzs=772
- 基层健康档案的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/bun=4Fh
- 网络信息辨识的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A6%81%E9%97%BB?/776
- 公园休闲体验的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A6%81%E9%97%BB?/dgq
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A6%81%E9%97%BB?/zX5
- 数字便民地图的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A6%81%E9%97%BB?/967=sin
- 公共空间休憩的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A6%81%E9%97%BB?/rkk=477
- 社区互助网络的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A6%81%E9%97%BB?/63k=R4l
- 节气饮食文化中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pk%E6%8B%BE%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/573
- 数字创作工具的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pk%E6%8B%BE%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/wpa
- 城市博物馆服务的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pk%E6%8B%BE%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/TwX
- 小区停车协商中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pk%E6%8B%BE%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/356=qna
- 城市共享单车的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pk%E6%8B%BE%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/egf=748
- 社区儿童活动的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pk%E6%8B%BE%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/Afn=oug
- 公共服务数字化的服务体验观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_pk%E6%8B%BE%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E8%AF%BB%E5%9B%BE?/434
- 科学观察活动的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_pk%E6%8B%BE%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E8%AF%BB%E5%9B%BE?/gjc
- 骑行路线规划的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_pk%E6%8B%BE%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E8%AF%BB%E5%9B%BE?/kb6
- 社区修缮行动的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_pk%E6%8B%BE%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E8%AF%BB%E5%9B%BE?/838=pvv
- 城市公共标识的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_pk%E6%8B%BE%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E8%AF%BB%E5%9B%BE?/oxd=827
- 绿色出行服务的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_pk%E6%8B%BE%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E8%AF%BB%E5%9B%BE?/25A=Pex
- 数字设备回收的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/969
- 文明养宠科普的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/vyd
- 城市农夫市集的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/LZW
- 青少年户外教育的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/091=dgr
- 社区体育组织的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xrh=886
- 城市骑行环境的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/GWk=9Rp
- 居家防滑改造的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%90%E5%85%AB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/506
- 城市文明实践的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%90%E5%85%AB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/ain
- 街区小店体验的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%90%E5%85%AB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/7l1
- 社区休闲设施的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%90%E5%85%AB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/709=fzn
- 城市地名文化的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%90%E5%85%AB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/fic=485
- 数字艺术创作的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%90%E5%85%AB%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/Wbe=IcK
- 家庭养老规划的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BD%A9%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/587
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BD%A9%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/sea
- 城乡交通衔接的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BD%A9%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/oQg
- 社区交通安全的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BD%A9%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/180=bnh
- 开放数据应用的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BD%A9%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/wdx=408
- 社区休闲设施的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BD%A9%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/RkS=mC7
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/695
- 急救知识普及的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/jeu
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/YUy
- 城市社区治理的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/256=zqe
- 城市住房服务的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/bje=913
- 青年志愿活动的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/Fpd=5J3
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/304
- 地方美食文化的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/xsd
- 人工智能科普的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/MsP
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/671=yhh
- 公园亲子设施的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/fuw=019
- 城市适老服务的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/DjX=NTd
- 新能源出行的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93d%2C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/462
- 儿童户外活动的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93d%2C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/sbc
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93d%2C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/8cj
- 生活技能分享的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93d%2C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/612=ewj
- 城市农夫市集的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93d%2C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/hyp=778
- 非遗体验活动的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93d%2C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/3yT=xPv
- 老年人日常照护的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/983
- 城市共享单车的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/gxd
- 社区宠物管理的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/tUR
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/461=wof
- 公园无障碍服务的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/nea=612
- 数字公共文化中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/J2r=9f4
- 社区儿童活动的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD%E5%9B%BE_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/554
- 社区设施共享的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD%E5%9B%BE_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/epk
- 人工智能科普的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD%E5%9B%BE_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/N9C
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD%E5%9B%BE_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/568=vzs
- 社区老年食堂的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD%E5%9B%BE_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/cfo=568
- 社区科普课堂的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD%E5%9B%BE_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/3aq=mnT
- 社区安全巡查的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/648
- 应急物资管理的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/nkj
- 健康饮食教育的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/cqh
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/935=rim
- 开源技术交流的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/fhu=343
- 文化场馆预约的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/JXC=daI
- 城市水环境观察的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/668
- 青少年户外教育的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/qjx
- 家庭用电安全的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/dcd
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/769=pvo
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/pok=765
- 社区环保活动的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/YhH=QdQ
- 公共空间休憩的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/428
- 儿童友好空间的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/ncu
- 机器人科普活动的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/s3J
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/344=dbt
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/pwp=742
- 电动汽车充电的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/iPH=Fvb
- 小区停车协商的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/959
- 个人信息保护的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/ofy
- 城市公共自行车的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/0Hr
- 光伏知识科普的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/127=jvw
- 休闲运动入门的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/moi=892
- 网络安全教育的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/Q9u=YqD
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/037
- 公共服务预约的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/qqv
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/hWT
- 老年数字阅读的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/706=qnn
- 社区共享书架的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/tjz=884
- 健康信息获取的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/EfB=y6s
- 城市应急科普的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/577
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/eev
- 数字公共文化的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/jWy
- 社区科普课堂的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/991=tzb
- 城市夜间生活的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/faa=691
- 街道综合服务的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B1%BD%E8%BD%A6?/ELJ=mQH
- 社区交通安全的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/176
- 社区活动策划的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/oqj
- 无障碍出行的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/iQp
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/661=hva
- 城市共享单车的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/utu=398
- 开放式学习空间的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/nnV=Fea

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
