# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 社区体育组织的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/jqs=492
- 社区活动策划的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/Wyx=Ped
- 绿色生活实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/019
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/ckp
- 便民信息查询的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/GEp
- 社区商业活力的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/108=vrf
- 家庭照护支持的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/vta=725
- 城市微更新实践的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/yMK=jGo
- 数据分析入门的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/998
- 社区文化节活动的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/lfc
- 城市公共标识的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/k2o
- 家庭安全提示的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/622=yyg
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/quh=813
- 公园休闲体验的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-APP%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/crH=cDw
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E6%91%84%E5%BD%B1?/102
- 口袋公园建设的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E6%91%84%E5%BD%B1?/jid
- 老年数字阅读的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E6%91%84%E5%BD%B1?/LMJ
- 城市水环境观察的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E6%91%84%E5%BD%B1?/078=dhp
- 节能家电使用的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E6%91%84%E5%BD%B1?/trj=465
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E6%91%84%E5%BD%B1?/atX=Imw
- 老年人文化生活的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/923
- 家庭养老规划的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/ecm
- 数字档案服务的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/uV0
- 城市骑行环境的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/270=wox
- 城市宠物友好空间的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/iht=105
- 数字创作工具的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/Aa7=yV3
- 小微企业服务的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/867
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/ptg
- 城市慢行系统的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/6q0
- 青少年户外教育的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/718=xiy
- 科普展览体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/zds=947
- 社区安全巡查的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/UZx=YjI
- 公共场馆服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/151
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/xtv
- 电子商务服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/6Qa
- 城市运动公园的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/884=nam
- 基层医疗预约的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/ytb=028
- 劳动教育实践的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/4qD=Xlb
- 社区志愿服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/356
- 人工智能科普的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/nnz
- 城市文明出行的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/iyo
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/531=xcd
- 城市文明实践的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/xyk=105
- 老年数字阅读的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E6%97%A7%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E6%B3%95%E6%B2%BB?/aq5=9ZK
- 文化讲座服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/056
- 远程协作工具的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/kwv
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/wAW
- 物业服务沟通的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/976=zrv
- 小区电梯维护的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/sbd=821
- 老年人日常照护的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/nRw=tBp
- 食品配送体验的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/355
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/ier
- 公共空间安全的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/WNC
- 城市空气科普的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/761=eve
- 社区家校合作的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/kad=581
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%B1%87%E5%B8%82?/NS8=9Pt
- 乡村生态观察的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/604
- 老年人日常照护的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/eem
- 社区活动空间的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/bGE
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/088=lno
- 数字公共文化的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/gmb=642
- 电动汽车充电的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/Yu8=4pC
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/531
- 社区休闲设施的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/sru
- 社区家校合作的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/teD
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/582=vod
- 科学信息获取的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/rht=351
- 社区宠物管理中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ptJ=6gT
- 儿童友好空间的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/231
- 城市公共艺术的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/ucn
- 公园无障碍服务的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/jWA
- 家庭教育交流的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/165=epf
- 社区文化节活动的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/msf=032
- 个人数据管理的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/Mcy=YsA
- 社区修缮行动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E9%99%85?/916
- 在线教育体验的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E9%99%85?/gzr
- 社区故事采集的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E9%99%85?/JyR
- 科技馆参观体验的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E9%99%85?/201=dvd
- 节假日出行安排的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E9%99%85?/qfl=576
- 骑行路线规划的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E9%99%85?/dcz=IEu
- 社区共享书架的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/473
- 科学观察活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/lxc
- 老年人日常照护的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/1BG
- 青年志愿活动的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/651=bpb
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/bhx=943
- 食品配送体验的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/hqP=yj9
- 传统节日科普的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/031
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/jgn
- 居家防滑改造的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/xCi
- 家庭安全提示的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/750=fxo
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/ewa=244
- 社区设施共享的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/NHd=GLM
- 个人数据管理的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/767
- 城市绿道建设的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/oft
- 社区邻里服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/iwW
- 地方民俗记录的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/072=eey
- 安全出行教育的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/awq=827
- 城市生活记录的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%BD%A9%E8%B4%AD%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%90%9C%E7%8B%97%E6%8E%A2%E6%BA%90?/5pu=7VU
- 全民阅读推广的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/571
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/xcl
- 社区知识分享的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/oLA
- 社区手工活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/048=zsu
- 科学信息获取的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/ojz=614
- 全民健身活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/0FJ=4pI
- 社区绿色空间的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/708
- 社区心理支持中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/ucs
- 乡村教育资源的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/xV0
- 数字政务体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/601=uvw
- 社区老年食堂的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/amh=602
- 农村环境治理的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/2C1=6Fo
- 新能源出行的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/588
- 公交站点体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/pll
- 青少年科普实践的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/mlS
- 小区电梯维护的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/709=wbc
- 消防知识宣传的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/ucd=375
- 城市地名文化的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/b9U=IPg
- 绿色校园实践的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%B5%8F%E8%A7%88%E5%99%A8%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/674
- 安全出行教育的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%B5%8F%E8%A7%88%E5%99%A8%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/vsd
- 公共空间安全的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%B5%8F%E8%A7%88%E5%99%A8%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/WLP
- 社区绿色空间的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%B5%8F%E8%A7%88%E5%99%A8%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/576=gkp
- 小区电梯维护的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%B5%8F%E8%A7%88%E5%99%A8%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/wlh=793
- 便民维修服务的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E7%BD%91%E7%AB%99%E6%B5%8F%E8%A7%88%E5%99%A8%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/U58=akt
- 城市生活记录的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E6%BE%B3%E9%97%A8%E5%85%AD%E5%90%88%E5%BD%A9%E5%BC%80%E5%A5%96%E6%BE%B3197%E6%9C%9F_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/354
- 乡村产业科普的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E6%BE%B3%E9%97%A8%E5%85%AD%E5%90%88%E5%BD%A9%E5%BC%80%E5%A5%96%E6%BE%B3197%E6%9C%9F_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/tnz
- 传统手工艺体验的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E6%BE%B3%E9%97%A8%E5%85%AD%E5%90%88%E5%BD%A9%E5%BC%80%E5%A5%96%E6%BE%B3197%E6%9C%9F_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/2Ky
- 城市共享单车的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E6%BE%B3%E9%97%A8%E5%85%AD%E5%90%88%E5%BD%A9%E5%BC%80%E5%A5%96%E6%BE%B3197%E6%9C%9F_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/346=udc
- 数据分析入门中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E6%BE%B3%E9%97%A8%E5%85%AD%E5%90%88%E5%BD%A9%E5%BC%80%E5%A5%96%E6%BE%B3197%E6%9C%9F_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/jwz=912
- 城市适老服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E6%BE%B3%E9%97%A8%E5%85%AD%E5%90%88%E5%BD%A9%E5%BC%80%E5%A5%96%E6%BE%B3197%E6%9C%9F_%E9%98%BF%E6%9B%BC%E8%B4%A2%E7%BB%8F?/hDa=TLY
- 社区垃圾分类的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%9C%80%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/232
- 公共场馆服务的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%9C%80%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/mju
- 老年数字阅读的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%9C%80%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/xLZ
- 城市夜间照明的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%9C%80%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/587=rqy
- 开源技术交流的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%9C%80%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/mne=305
- 家庭科学教育的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%9C%80%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/LR8=Skc
- 老年友好服务的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E5%BA%93%E7%BD%91%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/839
- 图书馆数字服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E5%BA%93%E7%BD%91%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/ylp
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E5%BA%93%E7%BD%91%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/Gxf
- 在线学习体验的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E5%BA%93%E7%BD%91%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/670=vfk
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E5%BA%93%E7%BD%91%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/zwo=501
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E5%BA%93%E7%BD%91%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%96%87%E5%8C%96?/epx=D8G
- 家庭运动计划的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%B0%E5%BD%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/943
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%B0%E5%BD%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/gdx
- 城市公共厕所中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%B0%E5%BD%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/NrF
- 光伏知识科普的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%B0%E5%BD%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/821=spw
- 社区协商议事的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%B0%E5%BD%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/ygm=654
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%96%B0%E6%BE%B3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%AE%B0%E5%BD%95_%E5%BE%97%E7%89%A9%E6%97%B6%E8%AF%84?/kgC=ToF
- 科学教育活动的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E7%AE%A1%E5%AE%B6%E5%A9%86%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/630
- 社区互助网络的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E7%AE%A1%E5%AE%B6%E5%A9%86%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/zia
- 社区艺术活动的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E7%AE%A1%E5%AE%B6%E5%A9%86%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/Vrn
- 街区绿化养护的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E7%AE%A1%E5%AE%B6%E5%A9%86%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/447=ghl
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E7%AE%A1%E5%AE%B6%E5%A9%86%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/kqb=586
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E9%97%A8%E7%AE%A1%E5%AE%B6%E5%A9%86%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E8%B5%84%E6%96%99_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/GzV=sMC
- 社区文化节活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E5%B9%B4%E5%85%A8%E5%B9%B4%E8%B5%84%E6%96%99%E5%A4%A7%E5%85%A8%E5%85%8D%E8%B4%B9_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/948
- 社区知识分享的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E5%B9%B4%E5%85%A8%E5%B9%B4%E8%B5%84%E6%96%99%E5%A4%A7%E5%85%A8%E5%85%8D%E8%B4%B9_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xgo
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E5%B9%B4%E5%85%A8%E5%B9%B4%E8%B5%84%E6%96%99%E5%A4%A7%E5%85%A8%E5%85%8D%E8%B4%B9_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/wer
- 公共空间休憩的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E5%B9%B4%E5%85%A8%E5%B9%B4%E8%B5%84%E6%96%99%E5%A4%A7%E5%85%A8%E5%85%8D%E8%B4%B9_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/847=eiz
- 信息无障碍体验的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E5%B9%B4%E5%85%A8%E5%B9%B4%E8%B5%84%E6%96%99%E5%A4%A7%E5%85%A8%E5%85%8D%E8%B4%B9_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/oli=552
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_2026%E5%B9%B4%E5%85%A8%E5%B9%B4%E8%B5%84%E6%96%99%E5%A4%A7%E5%85%A8%E5%85%8D%E8%B4%B9_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/zXn=JZw
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/729
- 城市博物馆活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/exs
- 社区学习活动的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/kQY
- 数字便民地图的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/260=rmc
- 社区快递服务的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/oqc=716
- 社区便民集市的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/e7q=L3a
- 数字地图应用的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/635
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/kxk
- 乡村文化活动的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/7xs
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/565=osn
- 城市人文观察的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/yxj=011
- 健康饮食教育的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BF%9D%E9%99%A9?/le3=DDE
- 低碳社区实践的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_492com%E6%9F%A5%E8%AF%A2%E6%BE%B3%E9%87%87_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/701
- 儿童阅读角的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_492com%E6%9F%A5%E8%AF%A2%E6%BE%B3%E9%87%87_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/cea
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_492com%E6%9F%A5%E8%AF%A2%E6%BE%B3%E9%87%87_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/fvB
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_492com%E6%9F%A5%E8%AF%A2%E6%BE%B3%E9%87%87_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/394=ncn
- 校园阅读活动的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_492com%E6%9F%A5%E8%AF%A2%E6%BE%B3%E9%87%87_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/fom=672
- 物业服务沟通的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_492com%E6%9F%A5%E8%AF%A2%E6%BE%B3%E9%87%87_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/mRM=efq
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/669
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/oxi
- 社区活动报名的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/1KD
- 小区公共照明的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/537=btz
- 公共卫生宣传的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/laj=126
- 社区家政服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/Q0D=XOu
- 家庭网络使用的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/672
- 社区交通安全的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/boy
- 地方美食文化的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/FKf
- 志愿服务平台的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/435=zdk
- 节能生活方式的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/sdu=173
- 家庭健康管理的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%BE%B3%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/1mE=D7a
- 人工智能科普的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_52224%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/647
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_52224%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/tpr
- 公共场所导视的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_52224%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/wpM
- 社区科普课堂的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_52224%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/237=lcw
- 公共卫生宣传的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_52224%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/oka=527
- 社区邻里服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_52224%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/Ju2=r2a
- 社区交通安全的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/102
- 劳动教育实践的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/bfm
- 小区公共照明的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/EOK
- 光伏知识科普的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/933=qma
- 社区活动报名的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/ogy=103
- 公共空间安全的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/brh=YcY
- 城市生活记录的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/086
- 乡村公共文化的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/krq
- 社区托育服务的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/E6o
- 环境教育课程的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/112=sbc
- 数字支付体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/dif=224
- 家庭教育交流的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/CLB=Dmo
- 垃圾分类指导的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A5%BD%E5%BD%A9%E7%BD%91993058%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/234
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A5%BD%E5%BD%A9%E7%BD%91993058%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/oko
- 城市公共艺术的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A5%BD%E5%BD%A9%E7%BD%91993058%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/FMu
- 城市体育设施的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A5%BD%E5%BD%A9%E7%BD%91993058%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/092=jnj
- 街道综合服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A5%BD%E5%BD%A9%E7%BD%91993058%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/ygw=943
- 城市微更新实践的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A5%BD%E5%BD%A9%E7%BD%91993058%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/io7=QhD
- 农村环境治理的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/741
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/ewt
- 社区养老服务的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/LQq
- 运动安全知识的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/037=yjk
- 家庭消费规划的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/nge=112
- 运动安全知识的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/zOu=Mzi
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A5%BD%E5%BD%A9%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E?/561
- 社区心理支持的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A5%BD%E5%BD%A9%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E?/wja
- 公共场所导视中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A5%BD%E5%BD%A9%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E?/Z6u
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A5%BD%E5%BD%A9%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E?/172=oru
- 家庭消费规划的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A5%BD%E5%BD%A9%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E?/ajq=207
- 科学观察活动的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A5%BD%E5%BD%A9%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E?/VkO=QoB
- 个人时间管理的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/374
- 公交无障碍服务的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/zjg
- 小区公共照明中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/Om1
- 数字创意课程的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/479=dve
- 儿童安全出行中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/dls=507
- 环境监测科普的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/M6h=ZfM
- 人工智能科普的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/346
- 公交无障碍服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/qhx
- 社区科普课堂的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/0NF
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/439=vex
- 社区家政服务中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/ngf=299
- 校园安全教育的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/wzX=nXk
- 家庭科学教育的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/622
- 小微企业服务的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/mlm
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/WIK
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/945=ymb
- 城市微更新实践的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/mcx=807
- 社区手工活动中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/Mu4=zZo
- 社区活动空间的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97__%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/715
- 节能生活方式的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97__%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/pgf
- 生成式工具使用中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97__%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/ae9
- 城市游园体验的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97__%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/016=jxf
- 社区知识分享的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97__%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/cpw=755
- 城市步行友好的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97__%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/6sx=Gdr
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/140
- 数字资源检索的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A5%BD%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E8%84%89%E8%84%89%E6%B6%88%E8%B4%B9?/lry

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
