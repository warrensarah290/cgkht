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

- 家庭收纳实践的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/uYm
- 志愿服务平台的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/351=ibv
- 城市农夫市集的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/diz=827
- 健康饮食教育的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%98%93%E5%BD%A9%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/Hdh=0YB
- 智慧城市体验的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/578
- 城乡交流活动的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/pld
- 基层健康服务的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/RpM
- 全民健身活动的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/079=rkc
- 基层医疗预约的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/boa=705
- 青少年科普实践的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%85%AC%E5%BC%80%E8%AF%BE?/44o=qoo
- 公园无障碍服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/999
- 社区设施共享的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/ecd
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/YwI
- 开放数据应用的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/978=fxm
- 机器学习入门的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/lwp=908
- 居家防滑改造的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/VPG=lNg
- 家庭健康科普的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/730
- 租房信息服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/pcn
- 家庭节能实践的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/EHR
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/117=plv
- 家庭运动计划的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/yxx=136
- 乡村教育资源的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E6%8E%8C%E6%9F%9C-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/MuN=uuU
- 家庭阅读计划的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/914
- 城市步行友好的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/lra
- 社区消防演练的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/fK3
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/909=bff
- 节能生活方式的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/dnw=038
- 社区共享书架的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/gw5=5ZL
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/376
- 本地旅行体验的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/rkh
- 绿色出行服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/6AF
- 乡村电商实践的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/025=jnl
- 城市社区治理的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/eef=824
- 城市博物馆服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%AE%98%E6%96%B9app%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/0OF=ZbI
- 社区停车服务的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/743
- 社区志愿服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/jgf
- 社区消防演练的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/oMp
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/510=hly
- 便民服务窗口的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/rxi=638
- 居家防滑改造的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/9ie=nRE
- 社区文化节活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%97%85%E6%B8%B8?/289
- 安全出行教育的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%97%85%E6%B8%B8?/uoz
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%97%85%E6%B8%B8?/Oe0
- 传统节日科普的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%97%85%E6%B8%B8?/106=jlo
- 街区绿化养护的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%97%85%E6%B8%B8?/ifr=205
- 个人数据管理的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E6%97%85%E6%B8%B8?/3uV=wHU
- 全民阅读推广的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/581
- 公园无障碍服务的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/fdv
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/IYC
- 家庭环保行动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/872=fpe
- 文明养宠科普的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/fcn=653
- 软件开发学习的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/ZXj=1fl
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%85%9A%E5%BB%BA?/886
- 乡村生态观察中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%85%9A%E5%BB%BA?/jkq
- 城市水环境观察的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%85%9A%E5%BB%BA?/8rb
- 社区故事采集的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%85%9A%E5%BB%BA?/070=gru
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%85%9A%E5%BB%BA?/cvb=075
- 职业技能学习的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E6%8E%8C%E6%9F%9C-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%85%9A%E5%BB%BA?/Km1=CBu
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/176
- 绿色生活实践的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/pux
- 节假日出行安排的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/3G6
- 社区休闲设施的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/155=icx
- 城市农夫市集的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/srv=359
- 环境监测科普的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/4RD=f7O
- 社区花园共建的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/367
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/xvi
- 开放数据应用的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/ZWM
- 社区应急准备的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/938=kun
- 社区交通安全的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/wcf=414
- 城市绿道建设的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/Zzg=S4o
- 文化场馆预约的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/856
- 家庭环保行动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/ndz
- 软件开发学习的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/qkk
- 校园社团活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/951=eaq
- 社区生活指南的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/ksn=812
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E6%8E%8C%E6%9F%9Cwelcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/0XE=71L
- 电动汽车充电的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/011
- 数据分析入门的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/cqq
- 职业技能学习的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/0g7
- 居家防滑改造的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/017=emd
- 乡村公共文化的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/ekv=517
- 城乡公共服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%95%B0%E7%A0%81?/6TE=moa
- 社区邻里服务的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/214
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/zmp
- 市民意见收集的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/u1G
- 城市骑行环境的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/389=coe
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/hvm=062
- 图书馆活动策划的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E6%96%87%E5%BA%93?/ndu=Zdb
- 城市绿道建设的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/667
- 学校体育活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/vcr
- 公共空间照明的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/NDw
- 公共场所导视的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/568=wzh
- 城市骑行环境的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/xdy=462
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/dFX=rnc
- 社区修缮行动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/971
- 地方戏曲体验的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/xkr
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/mJi
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/137=lck
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/smr=904
- 数字便民地图的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/2pN=gxO
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/011
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/cta
- 老年人出行服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/3pP
- 街区绿化养护的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/892=xil
- 城市慢行系统的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/wgy=108
- 个人数据管理的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BE%AE%E8%81%8A%28I%E6%97%A5%E7%89%88%E6%9C%AC%29_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/ozg=2El
- 公共服务评价的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_518588%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/907
- 公共服务数字化的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_518588%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/kbx
- 城市绿道建设的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_518588%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/Tnj
- 街区道路维护中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_518588%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/601=dwf
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_518588%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/gbi=990
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_518588%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/FxL=PjP
- 社区科普课堂的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_518588%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/258
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_518588%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/ozc
- 公园亲子设施的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_518588%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/ukd
- 电动汽车充电的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_518588%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/369=swe
- 校园阅读活动的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_518588%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/sdj=430
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_518588%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/nvE=fxT
- 生活技能分享的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_518588%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E5%BA%97?/808
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_518588%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E5%BA%97?/gbr
- 青年职业探索的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_518588%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E5%BA%97?/snP
- 城市骑行环境的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_518588%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E5%BA%97?/539=fxs
- 志愿者培训交流的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_518588%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E5%BA%97?/eie=458
- 地方文化传播的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_518588%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%8E%A2%E5%BA%97?/ttZ=El6
- 老年人文化生活的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_518588%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/537
- 电动汽车充电的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_518588%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/xbf
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_518588%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/pKQ
- 公共空间安全的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_518588%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/474=ozl
- 公共服务评价的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_518588%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/omb=822
- 科学运动指导的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_518588%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/xoy=HR0
- 城市生活记录的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_518588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/512
- 骑行路线规划的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_518588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/wut
- 家庭养老规划的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_518588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/j7l
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_518588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/798=sxy
- 城市步行环境的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_518588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/wiw=895
- 社区文化传播的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_518588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/Kkg=pvR
- 急救知识普及的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_518588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/206
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_518588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/vkr
- 公共卫生设施的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_518588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/uIz
- 城市游园体验的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_518588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/879=lep
- 户外活动组织的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_518588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/hzp=584
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_518588%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/Alq=qV0
- 软件开发学习的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/998
- 城市社区治理的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/ena
- 社区阅读服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/VtK
- 数字学习资源的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/182=nok
- 社区绿色空间的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/rld=201
- 街区道路维护的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%9C%A8%E7%BA%BF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/Cdo=Rtn
- 软件开发学习的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66%E8%B4%AD%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/833
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66%E8%B4%AD%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/jcd
- 软件开发学习的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66%E8%B4%AD%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/520
- 家庭志愿活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66%E8%B4%AD%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/199=avl
- 城市应急广播的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66%E8%B4%AD%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/dez=100
- 社区公共卫生的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66%E8%B4%AD%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E9%94%90%E8%AF%84?/L52=nR8
- 社区设施共享的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/520
- 社区志愿服务的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/qab
- 志愿服务平台的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/cDN
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/743=iop
- 软件开发学习的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/zzr=916
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/Oqt=OW2
- 公园亲子设施的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/734
- 城市文明出行的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/bqd
- 社区便民服务的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/Zci
- 基层健康服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/080=lzi
- 社区老年食堂的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/soj=454
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/tSE=jRe
- 旧物循环利用的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/385
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/qgn
- 城市适老服务的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/i55
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/975=ptk
- 家庭运动计划的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/paq=201
- 老年数字阅读的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9welcome%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/tn2=iD4
- 街区绿化养护的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/909
- 城市人文观察的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/xps
- 无障碍出行的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/qEq
- 传统节日科普的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/970=fbx
- 社区快递服务的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/meu=691
- 科学信息获取的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/Hqo=oKB
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/179
- 在线学习体验的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/dsi
- 社区故事采集的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/8zg
- 周末休闲规划的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/372=xgy
- 老年运动活动的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/elm=147
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/jCz=qYj
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/904
- 社区活动报名的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/adc
- 家庭急救准备的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/iki
- 城乡交通衔接的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/048=jhn
- 社区教育资源的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/knd=645
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/RlN=G4J
- 智能手机助老的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85APP_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/638
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85APP_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/dxa
- 城市夜间照明的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85APP_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/NRr
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85APP_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/971=duq
- 图书馆数字服务的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85APP_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/xdv=752
- 城市生活服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E5%BD%A9%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85APP_%E9%A1%BA%E4%B8%B0%E7%BB%BC%E8%89%BA?/NYD=uYt
- 节能家电使用的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/620
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/hxm
- 街区绿化养护的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/akM
- 社区读书角建设的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/034=lwc
- 在线教育体验的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/cba=427
- 社区垃圾回收的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/kzJ=3nl
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/066
- 个人时间管理的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/ipb
- 社区停车服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/Joy
- 食品配送体验的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/968=gnf
- 街头绿植养护的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/ahb=821
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%94%BF%E7%AD%96?/aHS=oHl
- 地方旅游导览的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%BA%BF%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%AE%89%E5%85%A8_36%E6%B0%AA?/760
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%BA%BF%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%AE%89%E5%85%A8_36%E6%B0%AA?/sth
- 城市体育设施的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%BA%BF%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%AE%89%E5%85%A8_36%E6%B0%AA?/vH9
- 青少年户外教育的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%BA%BF%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%AE%89%E5%85%A8_36%E6%B0%AA?/439=fdh
- 在线教育体验的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%BA%BF%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%AE%89%E5%85%A8_36%E6%B0%AA?/ihx=187
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E7%BA%BF%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%93%AA%E4%B8%AA%E6%9C%80%E5%AE%89%E5%85%A8_36%E6%B0%AA?/mLW=6AV
- 老旧小区改造的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/199
- 城市公共座椅的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/qoa
- 科学观察活动的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/eWr
- 运动安全知识的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/094=fin
- 健康步道使用的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/cyl=139
- 公共空间安全的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA%E9%87%8C_%E6%90%9C%E7%8B%90%E6%88%B7%E5%A4%96?/iaf=LP2
- 城市游园体验的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/279
- 数字政务体验的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/mzm
- 城市社区治理的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/tD9
- 绿色生活实践中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/549=mtj
- 运动安全知识的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/rzm=799
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E7%9B%9B%E4%B8%96%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/1v8=P3f
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/769
- 药品使用科普的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/sxb
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/ta2
- 社区绿色空间的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/524=iqh
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/mvz=297
- 社区家校合作的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%97%B6%E5%B0%9A?/iKb=ttE
- 家庭急救准备的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_633%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/189
- 食品配送体验的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_633%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/pjp
- 城市应急科普的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_633%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/ybU
- 电动汽车充电的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_633%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/866=glg
- 城乡交通衔接的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_633%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/wag=291
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_633%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/sYX=YVp
- 城市骑行环境的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/449
- 环境教育课程的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/mmi
- 小区公共照明的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/Ux4
- 数据分析入门的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/317=dkd
- 本地历史资料的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/uyf=200
- 科学健身方法的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/GYN=Ubx
- 节气饮食文化的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/752
- 公共卫生设施的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/sqn
- 公共设施维护的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/kd4
- 就业技能培训的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/518=brr
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/emy=137
- 创业经验分享的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/Iri=BY9

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
