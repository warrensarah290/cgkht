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

- 城市基础设施的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%81%94%E7%9B%9F-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/qvp=460
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%81%94%E7%9B%9F-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/JJl=g1p
- 社区活动报名的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/955
- 城市公共标识的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/ewa
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/hJm
- 健康步道使用的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/930=eko
- 居民健康教育的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/xxa=228
- 基层医疗预约的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E4%B9%90%E8%B6%A3%E5%BD%A9~%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/BTm=3CA
- 城市运动公园的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/114
- 科学运动指导的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/pob
- 社区体育组织的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/mGx
- 健康信息获取的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/852=cfe
- 城市可持续生活的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/wxa=229
- 居民健康教育的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%8D%A3%E8%80%80%E8%81%94%E7%9B%9F-welcome%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/sHC=2K9
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/977
- 公益活动组织中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/grc
- 图书借阅体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/Ym8
- 开源技术交流的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/099=pdm
- 开源技术交流的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/ozj=982
- 信息无障碍体验的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app%E5%AE%A2%E6%88%B7%E7%AB%AF_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/iZA=UmI
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/406
- 社区消防演练的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/tlk
- 社区便民集市的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/xKV
- 信息无障碍体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/721=eeu
- 物业服务沟通的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/avo=028
- 家庭运动计划的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88-APP-%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/5b2=CHH
- 社区互助网络的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/916
- 本地消费场景的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/bsw
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/yyB
- 人工智能科普的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/485=lww
- 远程协作工具的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/civ=441
- 课后服务体验的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/qEY=frB
- 家庭科学教育的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/143
- 光伏知识科普的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/uzs
- 社区故事采集的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/25I
- 乡村文化活动的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/392=tsh
- 绿色校园实践的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/yxb=255
- 社区协商议事的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88500%E4%B8%AD%E5%BF%83%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/MPH=DX4
- 城市基础设施的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/575
- 城市微更新实践的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/qyz
- 社区艺术活动的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/08x
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/790=jss
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/wbn=828
- 生活垃圾回收的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app_%E8%B4%A2%E7%BB%8F%E6%99%BA%E9%80%89?/KNj=w9y
- 科学健身方法的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/261
- 城市夜间生活的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/owd
- 家庭教育交流的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/QS6
- 节能生活方式的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/911=vaz
- 社区文化传播的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/wef=900
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85app%E6%89%8B%E6%9C%BA%E7%89%88_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/h0d=2cM
- 垃圾分类指导的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/173
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/gyr
- 公交站点体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/1MH
- 图书馆活动策划的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/766=psw
- 街区更新实践的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/yih=835
- 城市运动公园的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%87%A4%E5%87%B0welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/SHz=Jv5
- 家庭急救准备的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/152
- 城市应急科普的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/zws
- 绿色校园实践的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/WB3
- 农产品品牌传播的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/935=msa
- 机器人科普活动的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/fmc=668
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/LcC=L1U
- 社区体育组织的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/053
- 公共文化活动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/rfl
- 城市游园体验的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/8FU
- 居民健康教育的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/595=ony
- 家庭用电安全的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/tmc=187
- 职业技能学习的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E9%97%A8%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/Rin=TMu
- 社区托育服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/622
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/rjq
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/Wff
- 城市文明出行的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/306=bdn
- 社区便利生活的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/kci=971
- 便民服务地图的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome_%E9%A1%BA%E4%B8%B0%E6%96%B0%E9%97%BB?/0rR=vsC
- 青少年科普实践的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/784
- 家庭消费规划的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/gkj
- 创业经验分享的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/HLk
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/506=jaa
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/aei=057
- 城市展览体验的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/5dR=j0w
- 城市游园体验中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/810
- 本地旅行体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/oog
- 社区绿色空间的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/g8a
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/721=icx
- 亲子科普活动的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/ire=445
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%8C%BA_%E4%BC%98%E9%85%B7%E7%BE%8E%E9%A3%9F?/NA7=3gl
- 乡村文化活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/236
- 城市应急广播的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/duj
- 数字生活课堂的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/XvN
- 城市空气科普的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/613=pts
- 科学健身方法中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/ndt=437
- 音乐欣赏活动的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/0T8=RbS
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/443
- 科技馆参观体验的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/ekj
- 街区小店体验的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/SSZ
- 创业经验分享的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/994=zqu
- 社区家校合作的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/lsz=162
- 小微企业服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85PG%E5%AE%98%E7%BD%91%E7%89%88_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/k1e=c28
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/108
- 家庭健康管理的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/yzd
- 志愿者培训交流的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/5Sx
- 公共卫生宣传的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/860=jcr
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/xyh=948
- 小区停车协商中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/qrV=bjJ
- 社区儿童活动的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85pg%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/867
- 社区家校合作的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85pg%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/nos
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85pg%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/t37
- 社区防暑服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85pg%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/389=ren
- 乡村阅读活动的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85pg%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/rui=664
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B7%85%E5%B3%B0%E5%9B%BD%E9%99%85pg%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/hhI=2DE
- 远程协作工具的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/136
- 城市公共空间的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/ycu
- 公益活动组织的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/m6G
- 基层健康服务的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/565=lrt
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/mqg=946
- 社区体育组织的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/Cxn=b9U
- 街区小店体验的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%B4%B7?/789
- 公园休闲体验的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%B4%B7?/tqx
- 城市公共饮水的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%B4%B7?/d3d
- 环境教育课程的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%B4%B7?/301=bxz
- 文化场馆预约的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%B4%B7?/vll=855
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E9%BC%8E%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E8%B4%B7?/qvy=2HD
- 科普展览体验的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/940
- 社区文化节活动的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/ssu
- 人工智能科普的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/pRx
- 城市适老服务的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/781=qjy
- 城市休闲步道的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/eoz=187
- 安全出行教育的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/Soh=hKx
- 家庭防灾准备的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/556
- 消防知识宣传的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/pqr
- 数字公共文化的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/JeT
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/290=err
- 青年职业探索中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/cdl=372
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/wKN=YBS
- 家庭养老规划的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%85%A5%E5%8F%A3%E5%AE%89%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/257
- 全民健身活动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%85%A5%E5%8F%A3%E5%AE%89%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/pvl
- 乡村公共文化的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%85%A5%E5%8F%A3%E5%AE%89%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/gh9
- 儿童运动体验的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%85%A5%E5%8F%A3%E5%AE%89%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/265=rtt
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%85%A5%E5%8F%A3%E5%AE%89%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/akw=124
- 家庭网络使用中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%85%A5%E5%8F%A3%E5%AE%89%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%A6%9C%E5%8D%95?/PAY=uxX
- 社区活动报名的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/683
- 城市地名文化的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/wph
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/vQA
- 在线教育体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/324=egb
- 老年学习活动的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/atm=532
- 社区商业活力的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/24B=Xss
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/273
- 城市适老服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/pvs
- 城市公共空间的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/DHS
- 科学健身方法的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/192=ggw
- 社区心理支持的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/ogs=177
- 乡村文化空间的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/7cl=cel
- 城市地名文化的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/582
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/qsh
- 社区安全巡查的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/bbh
- 地方戏曲体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/726=djm
- 城市步行友好的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/ibr=738
- 公共场馆服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/c28=LJa
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E9%97%AE%E5%8D%B7?/488
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E9%97%AE%E5%8D%B7?/dof
- 非遗体验活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E9%97%AE%E5%8D%B7?/Aok
- 小区公共照明的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E9%97%AE%E5%8D%B7?/222=erp
- 绿色办公实践中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E9%97%AE%E5%8D%B7?/pbo=400
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E9%97%AE%E5%8D%B7?/7d7=FtS
- 学校食育活动的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/397
- 社区花园共建的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/cmf
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/T0W
- 城市文明出行的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/377=obz
- 电动汽车充电的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/gbn=151
- 城市休闲步道的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/7FD=M5Q
- 社区环保活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/604
- 健康饮水科普的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/fyp
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/99y
- 无障碍信息设计的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/685=eaf
- 城市公共艺术的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/blv=576
- 家庭安全提示的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E9%BC%8E%E8%83%9C%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/rJa=JRX
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/558
- 社区消防演练的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/kwg
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/uPq
- 社区体育组织的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/003=mna
- 文化遗产保护科普的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/osl=055
- 老年智能设备的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BA%B2%E5%AD%90?/JTG=wIr
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/108
- 社区庭院绿化的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/yvb
- 社区快递服务的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/oaP
- 电动汽车充电的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/702=spa
- 老年人日常照护的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/ngt=114
- 数据分析入门的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/5Q9=IkL
- 城市体育设施的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/725
- 家庭健康科普的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/tht
- 社区运动空间的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/b1p
- 绿色校园实践的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/791=xyo
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/xmh=369
- 社区公共议事的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%9A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/xWE=cQw
- 网络信息辨识的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91welcome_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/317
- 家庭用电安全的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91welcome_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/mke
- 节能家电使用的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91welcome_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/47z
- 周末休闲规划的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91welcome_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/129=icc
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91welcome_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/qqu=574
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91welcome_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/mK8=uTn
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/876
- 数字课堂应用的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/jqr
- 社区教育资源的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/fx1
- 街区更新实践的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/226=alx
- 市民意见收集的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/ttc=219
- 城市绿色交通的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%9A%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/if7=1i5
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%91%E5%BD%A9%E7%BD%91APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/887
- 城市适老服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%91%E5%BD%A9%E7%BD%91APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/zoc
- 社区便民集市的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%91%E5%BD%A9%E7%BD%91APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/EA4
- 开源技术交流的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%91%E5%BD%A9%E7%BD%91APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/788=ccv
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%91%E5%BD%A9%E7%BD%91APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/lkx=791
- 小微企业服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%91%E5%BD%A9%E7%BD%91APP%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/DQF=lYG
- 农产品消费体验的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8F%91%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/179
- 信息无障碍体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8F%91%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/knd
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8F%91%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/u43
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8F%91%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/215=hql
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8F%91%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/hye=105
- 社区商业活力的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%8F%91%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/k7I=iHK
- 农产品品牌传播的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/750
- 生活服务数字化的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/xfd
- 老年数字阅读的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/bSV
- 社区活动报名的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/510=zxr
- 绿色生活实践的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/eol=086
- 社区教育资源的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/KOG=2n4
- 全民健身活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/711
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/hnw
- 生活技能分享的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/JHC
- 家庭节能设备的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/285=jwz
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/byp=746
- 城市农夫市集的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%8F%91%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/b0x=Mx6
- 社区文化传播的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%8F%91%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/710
- 租房信息服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%8F%91%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/gyl
- 公园亲子设施的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%8F%91%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/mQ2
- 青少年心理健康的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%8F%91%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/504=syk
- 市民热线服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%8F%91%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/nsr=616
- 生活垃圾回收的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%8F%91%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/JwT=ido
- 公共服务预约的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/245
- 城市建设科普的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/djb
- 终身学习资源的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/YgM
- 网络安全教育的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/630=yko
- 儿童运动体验的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/qlk=625
- 个人数据管理的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%8F%91%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/JTk=c4D
- 居民健康教育的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/879
- 城市适老服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/cik
- 城市公共座椅的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/0t6
- 城市公共空间的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/488=fdy
- 数字资源检索的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/hxf=158
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A1%BA%E5%8F%91%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E8%A7%82%E5%AF%9F?/Cj9=yGn
- 邻里共享空间的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%89%E8%A3%85%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/691
- 邻里共享空间的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%89%E8%A3%85%E6%8C%87%E5%8D%97_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/zzg

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
