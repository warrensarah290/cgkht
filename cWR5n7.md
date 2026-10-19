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

- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%95%B5%E4%B9%90%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/Sdp
- 便民维修服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%95%B5%E4%B9%90%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/149=lpp
- 劳动教育实践的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%95%B5%E4%B9%90%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/ofa=423
- 公共健身器材的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%95%B5%E4%B9%90%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/7wR=O6N
- 城市公共艺术的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%B4%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/107
- 学校食育活动的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%B4%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/jir
- 儿童友好空间的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%B4%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/Fkj
- 老年人文化生活的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%B4%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/220=dep
- 社区活动空间的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%B4%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/xss=317
- 家庭收纳实践的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%B4%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/l2w=EcT
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/313
- 开源技术交流的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/lis
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/36f
- 城市公共饮水的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/325=kjt
- 青少年心理健康中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/tlv=776
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/QBz=fxE
- 社区阅读服务的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B9%90%E8%A7%86app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/900
- 节约用水实践的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B9%90%E8%A7%86app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/jje
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B9%90%E8%A7%86app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/s5w
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B9%90%E8%A7%86app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/618=wvd
- 城市基础设施的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B9%90%E8%A7%86app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/cuh=303
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E4%B9%90%E8%A7%86app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/YE0=AfN
- 社区公共卫生的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AFapp%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/077
- 城市公共厕所的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AFapp%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/ppf
- 城市公共艺术的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AFapp%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/qyv
- 终身学习资源的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AFapp%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/583=kbf
- 电子商务服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AFapp%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/ycy=935
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AFapp%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/JI9=l9q
- 社区绿色空间的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8A%A8-app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/783
- 公共服务沟通的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8A%A8-app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/bev
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8A%A8-app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/1hd
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8A%A8-app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/116=mns
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8A%A8-app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/ono=565
- 在线学习体验的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8A%A8-app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/1Bg=a3q
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/634
- 乡村生活观察的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/rki
- 社区活动报名的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/knc
- 社区庭院绿化的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/225=jua
- 家庭用电安全的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/lar=968
- 家庭环保行动的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/NzI=rt9
- 家庭园艺实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/262
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/aju
- 跨代沟通活动的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/1Zn
- 传统手工艺体验的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/211=ifm
- 社区科普课堂的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/jlh=961
- 公共场所导视的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/baA=BuL
- 社区便民服务的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/463
- 社区庭院绿化的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/gdf
- 公共图书馆服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/kp4
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/184=cwk
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/vfn=952
- 乡村公共文化的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E4%BC%98%E9%85%B7%E5%BD%B1%E8%A7%86?/96z=nFO
- 社区健康讲座的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/212
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/xcc
- 社区快递服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/SI3
- 城市体育设施的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/877=urp
- 乡村文化活动的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/zdd=798
- 社区花园共建的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88%E6%9C%AC_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/u5d=d5i
- 数字支付体验的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/265
- 公益活动组织的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/iho
- 社区志愿服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/2Ye
- 公共服务数字化的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/942=gpu
- 社区快递服务的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/tne=678
- 课后服务体验的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B9%90%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/76W=jzY
- 城市树木认养的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%BE%E7%A4%BA%E9%93%B6%E8%A1%8C%E6%9C%AA%E7%9F%A5%E5%BC%82%E5%B8%B8_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/218
- 老年人出行服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%BE%E7%A4%BA%E9%93%B6%E8%A1%8C%E6%9C%AA%E7%9F%A5%E5%BC%82%E5%B8%B8_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/pph
- 绿色出行服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%BE%E7%A4%BA%E9%93%B6%E8%A1%8C%E6%9C%AA%E7%9F%A5%E5%BC%82%E5%B8%B8_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/I5E
- 城市公共标识的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%BE%E7%A4%BA%E9%93%B6%E8%A1%8C%E6%9C%AA%E7%9F%A5%E5%BC%82%E5%B8%B8_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/414=otm
- 地方民俗记录的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%BE%E7%A4%BA%E9%93%B6%E8%A1%8C%E6%9C%AA%E7%9F%A5%E5%BC%82%E5%B8%B8_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/mcu=581
- 青少年户外教育的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%BE%E7%A4%BA%E9%93%B6%E8%A1%8C%E6%9C%AA%E7%9F%A5%E5%BC%82%E5%B8%B8_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/4yg=jIs
- 城市社区治理的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/216
- 公共空间休憩的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/ntk
- 公共交通信息服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/Jjd
- 城乡交流活动的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/627=bch
- 社区共享书架的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/emy=358
- 地方旅游导览的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/DsU=y0Q
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E6%96%B9?/829
- 绿色生活实践的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E6%96%B9?/wuw
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E6%96%B9?/kd4
- 基层健康服务的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E6%96%B9?/489=cgn
- 公园休闲体验的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E6%96%B9?/kzf=550
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%A0%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E6%96%B9?/g6f=4TQ
- 城市树木认养的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/366
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/xhq
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/leN
- 环境监测科普的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/548=vso
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/gvj=060
- 数字公共文化的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/OaY=Pe6
- 社区托育服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/546
- 社区托育服务的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/psw
- 城市建设科普的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/Png
- 公共服务数字化的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/468=hjs
- 智慧城市体验的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/zkx=987
- 数字支付体验的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8IIIapp%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/v7L=gI1
- 新能源出行的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/803
- 社区活动策划的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/zvc
- 公共服务指南的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/ctd
- 城市公共厕所的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/363=tnq
- 城市公共座椅的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/pid=516
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/MI3=3bp
- 乡村生活观察的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%8F%91v%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80APP%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/744
- 智能手机助老的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%8F%91v%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80APP%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/xeq
- 校园节能行动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%8F%91v%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80APP%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/neT
- 节能家电使用的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%8F%91v%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80APP%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/036=txm
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%8F%91v%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80APP%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/ctf=116
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%90%E5%8F%91v%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80APP%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/elk=WBc
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/982
- 儿童运动体验的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/itz
- 节日文化体验的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/3iZ
- 校园社团活动的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/403=ynx
- 城市住房服务的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/xvd=038
- 老年人文化生活的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/ABr=wfv
- 机器学习入门的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%911_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/469
- 在线教育体验的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%911_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/fkd
- 家庭网络使用的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%911_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/W9i
- 无障碍出行的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%911_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/028=wes
- 社区公共卫生的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%911_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/xbs=348
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%911_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/nV2=gDN
- 城市地名文化的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/586
- 社区花园共建的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/uwa
- 城市夜间照明的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/s8c
- 公共卫生宣传的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/519=arv
- 社区活动报名的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/dnb=258
- 城市公共标识的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BF%AB%E6%8A%A5?/btg=KDu
- 文明养宠科普的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/371
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/egs
- 电子商务服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/53f
- 节能家电使用的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/489=dtu
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/maa=169
- 家庭节能设备的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/5QG=OQP
- 家庭照护支持的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91%E2%85%A2_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/275
- 便民信息查询的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91%E2%85%A2_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/yid
- 本地旅行体验的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91%E2%85%A2_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/07P
- 基层健康档案的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91%E2%85%A2_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/024=ftl
- 绿色生活实践的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91%E2%85%A2_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/jin=761
- 社区生活指南的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91%E2%85%A2_%E5%A4%B4%E6%9D%A1%E8%A1%8C%E6%83%85?/yBE=TFm
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/965
- 休闲运动入门的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/hqi
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/DAz
- 数字支付体验的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/311=ark
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/sdw=653
- 安全出行教育的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/iGx=avr
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/397
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/vnd
- 便民维修服务的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/xT9
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/355=kwk
- 终身学习资源的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/cpl=185
- 社区活动策划的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/KUp=3Sh
- 家庭用电安全的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/321
- 数字生活课堂的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/gld
- 智慧停车服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/C0r
- 社区艺术活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/812=usy
- 社区共享书架的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/uxn=631
- 城市生活记录的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/8Lb=U0s
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BF%A1%E4%B8%8D_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/663
- 个人数据管理的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BF%A1%E4%B8%8D_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/ack
- 社区活动报名的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BF%A1%E4%B8%8D_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/RLe
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BF%A1%E4%B8%8D_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/547=hkh
- 线上办事服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BF%A1%E4%B8%8D_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/clx=527
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BF%A1%E4%B8%8D_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/fId=4Sx
- 小区停车协商的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/785
- 绿色出行服务的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/ubo
- 垃圾分类指导的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/eOY
- 科普展览体验的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/007=wmb
- 城市可持续生活的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/mck=329
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/3rf=bQf
- 公共健身器材的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%87%BA%E6%9D%A5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/117
- 公共空间照明的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%87%BA%E6%9D%A5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/zjs
- 乡村阅读空间的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%87%BA%E6%9D%A5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/BZG
- 城市应急广播的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%87%BA%E6%9D%A5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/332=ods
- 电动汽车充电的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%87%BA%E6%9D%A5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/qtc=236
- 社区法律科普的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%87%BA%E6%9D%A5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/A7f=60u
- 网络信息辨识的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_998%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/501
- 节气饮食文化中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_998%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/eja
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_998%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/vGY
- 家庭园艺实践的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_998%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/707=met
- 医院导诊服务的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_998%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/oun=411
- 农产品品牌传播的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_998%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/gHX=j4e
- 无障碍信息设计的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AF%8F%E5%A4%A9%E8%83%BD%E8%B5%9A30%E2%80%9450%E5%85%83%E7%9A%84%E6%8D%95%E9%B1%BC_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/381
- 社区读书角建设的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AF%8F%E5%A4%A9%E8%83%BD%E8%B5%9A30%E2%80%9450%E5%85%83%E7%9A%84%E6%8D%95%E9%B1%BC_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/mhu
- 气象科普传播的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AF%8F%E5%A4%A9%E8%83%BD%E8%B5%9A30%E2%80%9450%E5%85%83%E7%9A%84%E6%8D%95%E9%B1%BC_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/BtZ
- 线上办事服务的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AF%8F%E5%A4%A9%E8%83%BD%E8%B5%9A30%E2%80%9450%E5%85%83%E7%9A%84%E6%8D%95%E9%B1%BC_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/512=fqp
- 社区文化传播的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AF%8F%E5%A4%A9%E8%83%BD%E8%B5%9A30%E2%80%9450%E5%85%83%E7%9A%84%E6%8D%95%E9%B1%BC_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/opp=118
- 公益活动组织的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%AF%8F%E5%A4%A9%E8%83%BD%E8%B5%9A30%E2%80%9450%E5%85%83%E7%9A%84%E6%8D%95%E9%B1%BC_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/MyI=QMJ
- 基层健康服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/274
- 社区商业活力的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/des
- 社区花园共建的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/GYH
- 文化讲座服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/002=mhb
- 儿童运动体验的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/cgu=223
- 数字课堂应用的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/TXZ=bz3
- 家庭消费规划的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B610%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B7%E5%A4%96?/969
- 健康步道使用的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B610%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B7%E5%A4%96?/jwi
- 城市公共饮水的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B610%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B7%E5%A4%96?/cTo
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B610%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B7%E5%A4%96?/274=esj
- 科技馆参观体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B610%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B7%E5%A4%96?/zmq=982
- 青年职业探索的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B610%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9_%E9%A1%BA%E4%B8%B0%E5%8F%B7%E5%A4%96?/lVJ=zD6
- 城市文化路线的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/124
- 市民意见收集的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/cix
- 城市社区治理的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/T74
- 地方旅游导览的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/643=bso
- 社区健康讲座的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/jjd=165
- 街区道路维护的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/sjM=Gii
- 城市体育设施的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/987
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/rxe
- 个人数据管理的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/1Ap
- 科学信息获取的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/293=lkh
- 开放数据应用的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/svu=489
- 市民意见收集的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E9%82%80%E8%AF%B7%E7%A0%81_%E4%BC%98%E9%85%B7%E9%97%AE%E7%AD%94?/5Je=s9f
- 社区花园共建的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%9F%B3%E4%B9%90?/968
- 社区艺术活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%9F%B3%E4%B9%90?/twj
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%9F%B3%E4%B9%90?/XIo
- 公共空间休憩的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%9F%B3%E4%B9%90?/425=xcb
- 老年运动活动的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%9F%B3%E4%B9%90?/yup=563
- 乡村阅读空间的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%9F%B3%E4%B9%90?/6sM=vXA
- 公共场所导视的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/722
- 绿色生活实践的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/pnn
- 邻里共享空间的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/wF3
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/585=tma
- 数字创意课程的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/ehy=134
- 科普展览体验的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/YKX=CmT
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%B4%E8%A7%A3%E5%99%A8app_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/410
- 城市社区治理的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%B4%E8%A7%A3%E5%99%A8app_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/hfw
- 城市噪声观察的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%B4%E8%A7%A3%E5%99%A8app_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/PRI
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%B4%E8%A7%A3%E5%99%A8app_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/880=omj
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%B4%E8%A7%A3%E5%99%A8app_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/cfl=998
- 社区设施共享的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%B4%E8%A7%A3%E5%99%A8app_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/tda=5Kd
- 老年人日常照护的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_360%E5%85%AC%E7%9B%8A?/246
- 读书会组织的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_360%E5%85%AC%E7%9B%8A?/ugy
- 创业经验分享的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_360%E5%85%AC%E7%9B%8A?/i0N
- 城市运动公园的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_360%E5%85%AC%E7%9B%8A?/382=qvq
- 社区安全巡查的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_360%E5%85%AC%E7%9B%8A?/qzw=973
- 职业技能学习的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_360%E5%85%AC%E7%9B%8A?/Idu=i81
- 城市运动公园的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E6%AF%93_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/222
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E6%AF%93_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/fgi
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E6%AF%93_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/kAs
- 老年智能设备的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E6%AF%93_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/620=phf
- 节气饮食文化的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E6%AF%93_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/xuk=125
- 社区环保活动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E6%AF%93_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/hc9=zzo
- 城市农夫市集的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/879
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/png
- 乡村阅读活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/wmN
- 数字课堂应用的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/961=sow
- 地方戏曲体验的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/flt=029
- 课后服务体验的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/CVb=h0f
- 节气饮食文化的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/102
- 老年数字阅读中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/vne
- 小微企业服务的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/75M
- 数字课堂应用的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/326=din
- 乡村公共服务的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/uvl=328
- 数字便民地图的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E6%96%B0_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/OKw=2VG

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
