# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 绿色消费选择的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D24%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1%E5%86%85%E5%AE%B9_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/bja=597
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D24%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1%E5%86%85%E5%AE%B9_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/E4P=UO7
- 非遗体验活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/112
- 公共服务指南的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/rnu
- 休闲运动入门的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/x9t
- 线上办事服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/428=ouf
- 社区防暑服务的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/btv=263
- 乡村生活观察的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%BC%AB%E8%AF%84?/rMb=vA1
- 老年人日常照护的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/876
- 全民健身活动的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/kez
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/81C
- 乡村公共文化的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/573=gsb
- 远程协作工具的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/baz=309
- 城市雨天出行的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/SUZ=yoF
- 科技馆参观体验的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/023
- 数字阅读服务的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/ucl
- 社区学习活动的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/bLn
- 节假日出行安排的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/195=gun
- 科学教育活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/vyc=722
- 社区法律科普的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E7%99%BE%E5%BA%A6%E7%88%86%E6%96%99?/Nnl=MRM
- 智能家居应用的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/712
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/bly
- 社区庭院绿化的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/rmF
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/601=eeu
- 社区停车服务的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/pdh=733
- 城市公共饮水的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/38v=lIv
- 社区活动空间的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/166
- 乡村生态观察的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/swv
- 乡村生态旅游的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/sEe
- 智慧停车服务的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/284=fka
- 个人信息保护的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/vzl=295
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%B1%87%E5%B8%82?/hFH=42C
- 城市基础设施的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/603
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/lsn
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/1vp
- 小区公共照明的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/537=xgu
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/pqm=172
- 绿色生活实践中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/vMO=JZS
- 公交无障碍服务的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/944
- 城市水环境观察中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/ypc
- 社区互助网络的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/rWN
- 社区体育组织的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/832=wel
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/yhe=732
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/YXT=tkc
- 便民维修服务的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/124
- 数字学习资源的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/fzj
- 城市社区治理的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/oSx
- 社区协商议事的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/341=wik
- 城市步行友好的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/sef=352
- 数字档案服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/lmn=i06
- 传统节日科普的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/040
- 公共场所导视的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/eat
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/kgb
- 城市农夫市集的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/628=nmy
- 家庭运动计划的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/mdq=346
- 城市展览体验的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/JCC=Bdd
- 本地旅行体验的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/052
- 乡村生态旅游的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/aos
- 电子商务服务的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/P3C
- 青年职业探索的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/284=ork
- 远程协作工具的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/sia=721
- 城市公共艺术的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/4A7=kt0
- 城市公共座椅的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/957
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/fqk
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/hpy
- 儿童运动体验的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/304=zpt
- 城市公共艺术的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/lsc=868
- 绿色校园实践的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/aRx=DrB
- 公共空间照明的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-welcome_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/991
- 乡村公共阅读的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-welcome_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/baq
- 文化讲座服务的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-welcome_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/ODj
- 机器人科普活动的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-welcome_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/520=uma
- 读书会组织的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-welcome_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/jva=923
- 开放数据应用的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-welcome_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%89%B4?/Vbz=R87
- 职业技能学习的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/715
- 社区教育资源的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/keq
- 城市建设科普的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/aky
- 城市雨天出行的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/837=hdc
- 数字素养提升的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/zbc=333
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E6%90%9C%E7%8B%97%E6%B3%95%E6%B2%BB?/6N4=Gy9
- 城市公共座椅的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/327
- 城市绿道建设的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/lre
- 社区花园共建的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/KHs
- 社区公共议事的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/120=wqp
- 老年数字阅读的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/cjx=641
- 便民服务地图的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/zYu=n5P
- 社区阅读服务的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/412
- 课后服务体验的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/gdn
- 图书馆活动策划的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/X9G
- 城市文明出行的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/473=msl
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/hvq=006
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/D8D=jvO
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%2C%E8%B5%84%E9%87%91%E4%B9%9F%E6%B2%A1%E9%80%80%E5%9B%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/070
- 基层健康服务中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%2C%E8%B5%84%E9%87%91%E4%B9%9F%E6%B2%A1%E9%80%80%E5%9B%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/zny
- 个人时间管理的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%2C%E8%B5%84%E9%87%91%E4%B9%9F%E6%B2%A1%E9%80%80%E5%9B%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/lW1
- 公共交通信息服务的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%2C%E8%B5%84%E9%87%91%E4%B9%9F%E6%B2%A1%E9%80%80%E5%9B%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/839=klf
- 数字生活课堂的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%2C%E8%B5%84%E9%87%91%E4%B9%9F%E6%B2%A1%E9%80%80%E5%9B%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/ppd=823
- 家庭节能实践的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%2C%E8%B5%84%E9%87%91%E4%B9%9F%E6%B2%A1%E9%80%80%E5%9B%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/Y55=qeu
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/185
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/lec
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/rA8
- 乡村公共阅读的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/454=hrc
- 乡村产业科普的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/dwa=230
- 社区活动空间的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%94%90%E8%AF%84?/3PW=M1M
- 青年职业探索的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/832
- 数字地图应用的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/yqm
- 绿色消费选择的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/RHR
- 生活技能分享的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/208=uwu
- 城市生活服务的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/hid=287
- 儿童运动体验的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/NJD=y2q
- 公共空间导览的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/607
- 本地消费场景的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/sso
- 无障碍信息设计的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/Z5s
- 乡村公共服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/692=ois
- 社区安全巡查的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/uxp=224
- 城市建设科普的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85Welcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/yT4=lSL
- 社区商业活力的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/612
- 社区阅读服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/zgz
- 公园休闲体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/alB
- 便民维修服务的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/885=jzt
- 社区菜市场服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/ajo=926
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/TFr=f2a
- 软件开发学习的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BA%B8%E7%94%B5%E5%AD%90%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/004
- 社区家校合作的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BA%B8%E7%94%B5%E5%AD%90%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/tsp
- 小微企业服务的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BA%B8%E7%94%B5%E5%AD%90%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/NUO
- 社区活动策划的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BA%B8%E7%94%B5%E5%AD%90%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/728=aen
- 老年人文化生活的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BA%B8%E7%94%B5%E5%AD%90%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/fyr=348
- 社区便利生活的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BA%B8%E7%94%B5%E5%AD%90%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/Zbr=Re2
- 数字艺术创作的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%95%B0%E5%AD%97%E6%8A%A5%E7%BA%B8_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/302
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%95%B0%E5%AD%97%E6%8A%A5%E7%BA%B8_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/ocr
- 城市生活服务的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%95%B0%E5%AD%97%E6%8A%A5%E7%BA%B8_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/n7i
- 社区家校合作的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%95%B0%E5%AD%97%E6%8A%A5%E7%BA%B8_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/216=wuc
- 数字便民地图的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%95%B0%E5%AD%97%E6%8A%A5%E7%BA%B8_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/mdo=140
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%95%B0%E5%AD%97%E6%8A%A5%E7%BA%B8_%E4%BC%98%E9%85%B7%E6%B3%95%E6%B2%BB?/z82=S0r
- 生活技能分享的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/276
- 休闲运动入门的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ruo
- 街道综合服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/1HG
- 社区防暑服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/477=lei
- 社区手工活动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/uml=491
- 运动安全知识的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/eX1=LS2
- 社区便利生活的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%96%B0_360%E6%97%B6%E8%AF%84?/595
- 城市慢跑路线的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%96%B0_360%E6%97%B6%E8%AF%84?/gnz
- 绿色出行服务的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%96%B0_360%E6%97%B6%E8%AF%84?/1QO
- 社区托育服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%96%B0_360%E6%97%B6%E8%AF%84?/826=olo
- 社区庭院绿化的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%96%B0_360%E6%97%B6%E8%AF%84?/ffw=202
- 节日文化体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%96%B0_360%E6%97%B6%E8%AF%84?/4zX=gHm
- 便民维修服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%A5%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/334
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%A5%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/yiv
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%A5%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/ty1
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%A5%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/248=kni
- 节能生活方式的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%A5%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/xkd=418
- 农贸市场环境的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%8A%A5%E5%BD%A9%E7%A5%A8%E7%BD%91_%E6%90%9C%E7%8B%97%E8%A7%82%E7%82%B9?/f1n=qsf
- 公园亲子设施的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/048
- 城市文明实践的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rwx
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/du7
- 数字素养提升的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/738=dyr
- 社区心理支持的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/dyt=686
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%AC%AC1%E5%BD%A9%E7%A5%A8%E6%8A%A5%E7%BD%91_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/GhC=VJv
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8722%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/840
- 社区休闲设施的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8722%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/iar
- 社区生活指南的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8722%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/otT
- 生活技能分享的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8722%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/574=uea
- 社区防暑服务的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8722%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/flf=713
- 公交站点体验的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8722%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/o1M=mKI
- 基层服务创新的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/435
- 家庭园艺实践的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/dgc
- 公益活动组织的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/W3d
- 灵活就业交流的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/024=vls
- 地方戏曲体验的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/rxt=993
- 绿色快递包装的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%B2%BE%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/A3O=6ZQ
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F%E7%BD%91%E5%9D%80_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/433
- 亲子科普活动的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F%E7%BD%91%E5%9D%80_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/upg
- 电动汽车充电的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F%E7%BD%91%E5%9D%80_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/w0s
- 老年人日常照护的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F%E7%BD%91%E5%9D%80_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/296=bas
- 职业技能学习的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F%E7%BD%91%E5%9D%80_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/bms=027
- 城市住房服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8F%E7%BD%91%E5%9D%80_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/JTZ=1sz
- 乡村产业科普的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/896
- 图书馆数字服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/nwp
- 本地历史资料的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/5Jm
- 数字学习资源的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/277=dcn
- 老年学习活动的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/cxr=880
- 社区托育服务的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/zI8=HqX
- 邻里共享空间的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%913.2.1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/673
- 乡村文化空间的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%913.2.1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/oan
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%913.2.1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/cJV
- 公共卫生设施的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%913.2.1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/467=ehu
- 全民健身活动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%913.2.1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/slx=288
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E7%BD%913.2.1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/sbT=jeq
- 公共空间导览的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/784
- 非遗体验活动的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/cvv
- 信息无障碍体验的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/o7m
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/605=azd
- 社会体育指导的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/lkl=670
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E5%9C%B0%E5%9D%80_%E5%87%A4%E5%87%B0%E7%BB%8F%E6%B5%8E?/oQB=f0g
- 乡村生态观察的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/497
- 应急物资管理的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/sxu
- 传统节日科普的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/ai2
- 社区活动报名中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/898=ony
- 非遗体验活动的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/wwa=677
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/qgE=zhr
- 老年人日常照护的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_6861vip%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/067
- 城乡交流活动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_6861vip%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/gck
- 农产品消费体验的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_6861vip%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/c18
- 市民意见收集的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_6861vip%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/110=cha
- 社区消防演练的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_6861vip%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/esp=674
- 城市水环境观察的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_6861vip%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/Mc8=MQs
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/243
- 家庭收纳实践的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/wnk
- 家庭健康科普的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/HMd
- 非遗体验活动的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/538=muj
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/bec=570
- 地方戏曲体验的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B9%9D%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/NWc=IRD
- 数字公共文化的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/853
- 应急物资管理的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/sum
- 社区运动空间的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/JUe
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/229=zyp
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/mqm=341
- 城市公共厕所的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/by6=J75
- 课后服务体验中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/955
- 全民阅读推广中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/kew
- 机器人科普活动的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/f8M
- 数字设备回收的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/310=ban
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/vcg=725
- 环境教育课程的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/IQY=Os6
- 城市博物馆活动的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/756
- 数字资源检索的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/vlo
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/zO7
- 老年人文化生活的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/754=rkm
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/ffy=939
- 社区设施共享的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/ca4=0Wm
- 应急物资管理的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/294
- 居民健康教育的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/mab
- 地方民俗记录的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/lMi
- 家庭网络使用的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/086=jxr
- 健康步道使用的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/rln=805
- 文化场馆预约的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/u30=oZQ
- 地方文化传播的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/472
- 公共服务咨询的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/ufj
- 社区环保活动的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/40f
- 城市应急科普的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/713=aro
- 公共空间休憩的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/ktc=566
- 安全出行教育的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%8E%96%E8%88%AA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/fjj=8R7
- 青年职业探索的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%9D%E6%B4%B2%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/235
- 家庭科学教育的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%9D%E6%B4%B2%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/tdn
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%9D%E6%B4%B2%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/vfn
- 生活服务数字化的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%9D%E6%B4%B2%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/423=gbk
- 公共设施维护的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%9D%E6%B4%B2%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/mxo=099
- 生活技能分享的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%9D%E6%B4%B2%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/LBP=Xt8
- 老年运动活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E6%8A%95%E7%BD%914036%E7%82%B9top_360%E6%95%99%E8%82%B2?/492
- 农产品消费体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B9%9D%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E6%8A%95%E7%BD%914036%E7%82%B9top_360%E6%95%99%E8%82%B2?/dff

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
