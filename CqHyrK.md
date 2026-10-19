# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 公共服务预约的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/ssE
- 青少年科普实践的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/889=nwa
- 社区垃圾分类的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/xmm=129
- 城乡交流活动的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E7%89%A9?/wZB=86Y
- 社区科普课堂的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%88%99_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/015
- 家庭园艺实践的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%88%99_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/bba
- 城市公共厕所的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%88%99_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/av7
- 社区养老服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%88%99_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/095=ezm
- 家庭阅读计划的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%88%99_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/oxq=521
- 数字设备回收的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%88%99_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/WVw=P6H
- 社区共享书架的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/339
- 城市体育设施的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/oqm
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/RAP
- 数字支付体验中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/805=giw
- 全民健身活动的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/fkx=648
- 乡村公共阅读的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/vEl=KTl
- 城市住房服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%A8%E5%B9%B4%E5%85%AC%E5%BC%8F%E5%BF%85%E5%87%BA%E8%82%96%E8%A7%84%E5%BE%8B_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/362
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%A8%E5%B9%B4%E5%85%AC%E5%BC%8F%E5%BF%85%E5%87%BA%E8%82%96%E8%A7%84%E5%BE%8B_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/wqr
- 信息无障碍体验的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%A8%E5%B9%B4%E5%85%AC%E5%BC%8F%E5%BF%85%E5%87%BA%E8%82%96%E8%A7%84%E5%BE%8B_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/yzz
- 社区停车服务的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%A8%E5%B9%B4%E5%85%AC%E5%BC%8F%E5%BF%85%E5%87%BA%E8%82%96%E8%A7%84%E5%BE%8B_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/987=dgf
- 乡村公共服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%A8%E5%B9%B4%E5%85%AC%E5%BC%8F%E5%BF%85%E5%87%BA%E8%82%96%E8%A7%84%E5%BE%8B_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dvr=263
- 公园休闲体验的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%A8%E5%B9%B4%E5%85%AC%E5%BC%8F%E5%BF%85%E5%87%BA%E8%82%96%E8%A7%84%E5%BE%8B_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/6tR=gVF
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%B8%89%E4%B8%AD%E4%B8%89%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/063
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%B8%89%E4%B8%AD%E4%B8%89%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/ord
- 公共服务数字化的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%B8%89%E4%B8%AD%E4%B8%89%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/Nmx
- 机器学习入门的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%B8%89%E4%B8%AD%E4%B8%89%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/252=ovx
- 公共空间休憩的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%B8%89%E4%B8%AD%E4%B8%89%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/rin=688
- 社区活动策划的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E4%B8%89%E4%B8%AD%E4%B8%89%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9B%BE_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/oqS=1MU
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E9%A1%BA%E7%9D%80%E4%B9%B0%E5%90%97_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/672
- 全民阅读推广的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E9%A1%BA%E7%9D%80%E4%B9%B0%E5%90%97_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/fwp
- 公共场所导视的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E9%A1%BA%E7%9D%80%E4%B9%B0%E5%90%97_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/osU
- 乡村生活观察的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E9%A1%BA%E7%9D%80%E4%B9%B0%E5%90%97_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/058=ovk
- 城市公共标识的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E9%A1%BA%E7%9D%80%E4%B9%B0%E5%90%97_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/cfj=619
- 乡村阅读空间的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E9%A1%BA%E7%9D%80%E4%B9%B0%E5%90%97_%E8%B1%86%E7%93%A3%E5%AE%89%E9%98%B2?/wEH=ziD
- 社区协商议事的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/041
- 城市社区治理的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/zuk
- 公共场所导视的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/XuZ
- 老年数字阅读的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/020=bkw
- 节能家电使用的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/khy=269
- 城市慢跑路线的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/x0s=ABa
- 家庭照护支持的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%BF%83%E5%BE%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/578
- 城市空气科普的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%BF%83%E5%BE%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/ixq
- 公共场馆服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%BF%83%E5%BE%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/vW9
- 在线学习体验的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%BF%83%E5%BE%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/126=pbr
- 生活服务数字化的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%BF%83%E5%BE%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/jru=454
- 社区休闲设施的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%BF%83%E5%BE%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%98%9F%E5%BA%A7?/MdU=ako
- 社区环保活动的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E7%9B%98%E7%82%B9?/566
- 基层健康服务的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E7%9B%98%E7%82%B9?/ezv
- 城市公共标识的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E7%9B%98%E7%82%B9?/Jv8
- 运动安全知识中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E7%9B%98%E7%82%B9?/184=izs
- 城市公共自行车的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E7%9B%98%E7%82%B9?/nes=554
- 乡村教育资源的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E7%9B%98%E7%82%B9?/FZg=MYk
- 公共空间导览的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/417
- 城市应急广播的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/tmr
- 城市夜间照明的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/Q6Y
- 社区健康讲座的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/198=lbh
- 城市文化路线的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/cpl=664
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%9B%B2%E8%89%BA?/oPh=ikU
- 城市公共艺术的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/189
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/lak
- 家庭运动计划的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/DVk
- 家庭饮食安排的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/664=pgj
- 市民热线服务的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/ofv=734
- 市民热线服务的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/xon=DJt
- 家庭园艺实践的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3-%E8%A7%84%E5%88%99_360%E7%BB%BC%E8%89%BA?/989
- 乡村公共服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3-%E8%A7%84%E5%88%99_360%E7%BB%BC%E8%89%BA?/crt
- 数字创作工具的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3-%E8%A7%84%E5%88%99_360%E7%BB%BC%E8%89%BA?/2Yw
- 旧物循环利用的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3-%E8%A7%84%E5%88%99_360%E7%BB%BC%E8%89%BA?/612=awj
- 社区防暑服务的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3-%E8%A7%84%E5%88%99_360%E7%BB%BC%E8%89%BA?/cbr=136
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3-%E8%A7%84%E5%88%99_360%E7%BB%BC%E8%89%BA?/BTE=DNQ
- 数字公共文化的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/315
- 社区共享书架的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/utx
- 急救知识普及的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/OzT
- 生成式工具使用的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/408=hxy
- 节日文化体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/wgr=393
- 亲子科普活动的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/1cz=Mk7
- 地方民俗记录的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%88%99%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/129
- 城市公共座椅的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%88%99%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/stm
- 租房信息服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%88%99%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/EyS
- 小区公共照明的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%88%99%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/785=tnp
- 科学运动指导的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%88%99%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/dic=222
- 骑行路线规划的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%A7%84%E5%88%99%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%8D%83%E5%B8%86?/u4L=G65
- 城市便民驿站的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1591317%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/951
- 人工智能科普的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1591317%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/rfx
- 社区休闲设施的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1591317%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/p3c
- 社区活动策划的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1591317%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/453=jov
- 科学观察活动的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1591317%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/pwn=666
- 数字支付体验的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1591317%E7%9A%84%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/FhE=IvT
- 文化遗产保护科普的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%94%A8%E5%95%86%E4%B8%8D%E5%8F%98%E7%9A%84%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/033
- 社区阅读服务的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%94%A8%E5%95%86%E4%B8%8D%E5%8F%98%E7%9A%84%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/dfe
- 环境教育课程的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%94%A8%E5%95%86%E4%B8%8D%E5%8F%98%E7%9A%84%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/YSS
- 城市绿色交通的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%94%A8%E5%95%86%E4%B8%8D%E5%8F%98%E7%9A%84%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/669=vwn
- 街区更新实践的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%94%A8%E5%95%86%E4%B8%8D%E5%8F%98%E7%9A%84%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/zlf=353
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%94%A8%E5%95%86%E4%B8%8D%E5%8F%98%E7%9A%84%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E5%A4%AE%E8%A7%86%E6%96%87%E5%8C%96?/8Zg=nyI
- 社区快递服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%89%E4%B8%AD%E4%B8%89%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/326
- 社区志愿服务中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%89%E4%B8%AD%E4%B8%89%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/igd
- 数字学习资源的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%89%E4%B8%AD%E4%B8%89%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Mnb
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%89%E4%B8%AD%E4%B8%89%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/875=ktq
- 公共空间休憩的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%89%E4%B8%AD%E4%B8%89%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/wxb=375
- 校园阅读活动的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%89%E4%B8%AD%E4%B8%89%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/FJe=xSU
- 家庭安全提示的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%AE%80%E4%BE%BF%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/490
- 社区停车服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%AE%80%E4%BE%BF%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/air
- 公共服务咨询的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%AE%80%E4%BE%BF%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/iTM
- 基层服务创新的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%AE%80%E4%BE%BF%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/235=nan
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%AE%80%E4%BE%BF%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/aru=259
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%AE%80%E4%BE%BF%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/fQ6=GkB
- 读书会组织的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%8F%B7%E7%A0%81%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/234
- 光伏知识科普的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%8F%B7%E7%A0%81%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/ikf
- 社区公共餐饮的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%8F%B7%E7%A0%81%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/pos
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%8F%B7%E7%A0%81%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/579=mmq
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%8F%B7%E7%A0%81%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/itj=337
- 骑行路线规划的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%8F%B7%E7%A0%81%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/Ljt=onM
- 公交无障碍服务的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/173
- 健康饮食教育的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/ktj
- 社区宠物管理的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/GVp
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/321=owv
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/uhe=357
- 社区健康讲座的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95%E7%BD%91%E7%AB%99%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%9B%AD%E8%89%BA?/Mq4=BAy
- 数字支付体验的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/242
- 软件开发学习的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/zdg
- 科普展览体验的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/175
- 数字学习资源的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/559=iam
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/lng=717
- 城市噪声观察的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E6%95%B0%E8%AF%BB?/m8H=99K
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/147
- 乡村产业科普的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/wbp
- 公共空间导览的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/oj4
- 信息无障碍体验的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/694=ejf
- 城市适老服务的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/hmm=253
- 智能家居应用的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/8YQ=ITD
- 个人信息保护的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/869
- 文化讲座服务的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/hxp
- 城市步行友好的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/xUQ
- 青少年编程学习的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/385=zfj
- 环境教育课程的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/wzt=002
- 在线教育体验的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/MRe=XJ9
- 公共卫生设施的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/189
- 城市展览体验的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/iqj
- 数字艺术创作的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/max
- 个人信息保护的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/704=qlb
- 低碳社区实践的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/vwu=733
- 远程协作工具的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/iqw=KFf
- 绿色办公实践的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B8%89%E5%A4%A7%E5%BF%AB%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/817
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B8%89%E5%A4%A7%E5%BF%AB%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/mfw
- 公共设施使用的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B8%89%E5%A4%A7%E5%BF%AB%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/mV1
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B8%89%E5%A4%A7%E5%BF%AB%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/858=atu
- 乡村教育资源的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B8%89%E5%A4%A7%E5%BF%AB%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/mvp=892
- 小微企业服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B8%89%E5%A4%A7%E5%BF%AB%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/xYV=ANY
- 社区手工活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9B%A8%E5%B8%A6%E6%8E%A8%E7%A7%BB%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/856
- 本地历史资料的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9B%A8%E5%B8%A6%E6%8E%A8%E7%A7%BB%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/uxg
- 家庭饮食安排的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9B%A8%E5%B8%A6%E6%8E%A8%E7%A7%BB%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/btZ
- 生活服务数字化的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9B%A8%E5%B8%A6%E6%8E%A8%E7%A7%BB%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/852=ltl
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9B%A8%E5%B8%A6%E6%8E%A8%E7%A7%BB%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/dua=997
- 健康步道使用的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9B%A8%E5%B8%A6%E6%8E%A8%E7%A7%BB%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/h2o=Ca4
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%B7%A6%E5%B0%8F%E5%B7%A6%E9%A1%BA%E5%8F%A3%E6%BA%9C_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/543
- 社区文化传播的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%B7%A6%E5%B0%8F%E5%B7%A6%E9%A1%BA%E5%8F%A3%E6%BA%9C_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/jnl
- 社区垃圾分类的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%B7%A6%E5%B0%8F%E5%B7%A6%E9%A1%BA%E5%8F%A3%E6%BA%9C_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/Ggi
- 骑行路线规划的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%B7%A6%E5%B0%8F%E5%B7%A6%E9%A1%BA%E5%8F%A3%E6%BA%9C_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/011=zmf
- 城市公共自行车的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%B7%A6%E5%B0%8F%E5%B7%A6%E9%A1%BA%E5%8F%A3%E6%BA%9C_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/vpz=161
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%B7%A6%E5%B0%8F%E5%B7%A6%E9%A1%BA%E5%8F%A3%E6%BA%9C_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/KS4=zFm
- 社区活动空间的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/298
- 健康信息获取的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/jjn
- 城市公共自行车的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/WAX
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/274=kjm
- 社区互助网络的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/fvb=408
- 社区活动空间的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%9B%86?/Hqw=xoK
- 数字艺术创作的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%AD%A5%E5%8F%A3%E8%AF%80_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/595
- 非遗体验活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%AD%A5%E5%8F%A3%E8%AF%80_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/smx
- 环境监测科普的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%AD%A5%E5%8F%A3%E8%AF%80_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/BJB
- 社区体育组织的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%AD%A5%E5%8F%A3%E8%AF%80_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/259=vey
- 公共空间导览的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%AD%A5%E5%8F%A3%E8%AF%80_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/ied=219
- 城市展览体验的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%AD%A5%E5%8F%A3%E8%AF%80_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/omO=yom
- 乡村公共文化的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/788
- 社区养老服务的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/fmg
- 食品配送体验的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/toy
- 公共空间安全的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/449=uov
- 小区电梯维护的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/xrh=510
- 乡村公共服务的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E6%90%9C%E7%8B%97%E6%8E%A2%E5%BA%97?/qGM=YPt
- 公共图书馆服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/743
- 公共卫生设施的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/pjm
- 城市文明实践的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/IlG
- 社区托育服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/371=sxp
- 数字课堂应用的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/kme=599
- 校园社团活动的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%BF%AB3_%E8%B1%86%E7%93%A3%E6%97%B6%E5%B0%9A?/zq1=VAT
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BB%91%E5%AE%A2%E7%A0%B4%E8%A7%A3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_360%E5%A8%B1%E4%B9%90?/330
- 地方民俗记录的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BB%91%E5%AE%A2%E7%A0%B4%E8%A7%A3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_360%E5%A8%B1%E4%B9%90?/awu
- 社区养老服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BB%91%E5%AE%A2%E7%A0%B4%E8%A7%A3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_360%E5%A8%B1%E4%B9%90?/Htq
- 校园节能行动的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BB%91%E5%AE%A2%E7%A0%B4%E8%A7%A3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_360%E5%A8%B1%E4%B9%90?/647=iwv
- 家庭养老规划的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BB%91%E5%AE%A2%E7%A0%B4%E8%A7%A3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_360%E5%A8%B1%E4%B9%90?/hvj=168
- 城市微更新实践的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%BB%91%E5%AE%A2%E7%A0%B4%E8%A7%A3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_360%E5%A8%B1%E4%B9%90?/2Li=27Q
- 公交无障碍服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97%E7%9F%A5%E9%81%93_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/684
- 社区协商议事的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97%E7%9F%A5%E9%81%93_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/ssc
- 居家防滑改造的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97%E7%9F%A5%E9%81%93_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/UXe
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97%E7%9F%A5%E9%81%93_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/786=nuf
- 城市地名文化的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97%E7%9F%A5%E9%81%93_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/gjw=568
- 社区邻里服务的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97%E7%9F%A5%E9%81%93_%E8%99%8E%E6%89%91%E8%AF%BB%E5%9B%BE?/yDq=mZr
- 公共健身器材的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88%E5%8E%9F%E5%9B%A0_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/979
- 青年职业探索中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88%E5%8E%9F%E5%9B%A0_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qmx
- 小区电梯维护的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88%E5%8E%9F%E5%9B%A0_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/0Ms
- 小区电梯维护的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88%E5%8E%9F%E5%9B%A0_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/855=vhi
- 家庭园艺实践的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88%E5%8E%9F%E5%9B%A0_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ibz=986
- 节日文化体验的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88%E5%8E%9F%E5%9B%A0_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/cSm=eO8
- 公共服务指南的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/891
- 市民意见收集的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/yty
- 家庭收纳实践的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/Il6
- 城市步行环境的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/504=yzg
- 机器学习入门的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/zzl=961
- 传统节日科普的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/zhB=5Qm
- 家庭节能实践的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%95%B0%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/768
- 数字便民地图的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%95%B0%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/hzc
- 市民意见收集的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%95%B0%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/UEN
- 社区快递服务中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%95%B0%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/364=paw
- 电子商务服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%95%B0%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/tyr=636
- 全民健身活动的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%95%B0%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/CVU=4lL
- 健康信息获取的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/212
- 城市休闲步道的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/wqs
- 社区知识分享的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/aeR
- 全民健身活动的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/826=ztk
- 家庭饮食安排的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/zgt=775
- 社区消防演练的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%B0%8F%E6%80%8E%E4%B9%88%E7%9C%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A6%9C%E5%8D%95?/Jbv=w8c
- 城市步行友好的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/381
- 数字便民地图的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/cym
- 社区消防演练的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/SRD
- 社区科普课堂的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/300=eot
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/fil=106
- 城市应急广播的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E7%9A%84%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E4%BA%B2%E5%AD%90?/c9V=q9v
- 社区便利生活的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%87%BA%E7%8E%B0%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/899
- 街区小店体验的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%87%BA%E7%8E%B0%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/zcm
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%87%BA%E7%8E%B0%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/oHk
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%87%BA%E7%8E%B0%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/112=gky
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%87%BA%E7%8E%B0%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/txm=205
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%95%B0%E5%AD%97%E5%87%BA%E7%8E%B0%E7%9A%84%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E5%9F%8E%E4%BA%8B?/zP3=WT0
- 数字生活课堂的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E6%AD%BB%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/887
- 光伏知识科普的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E6%AD%BB%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/eqg
- 节能家电使用的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E6%AD%BB%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/03b
- 数字创意课程的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E6%AD%BB%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/987=tnf
- 数字学习资源的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E6%AD%BB%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/wuh=356
- 城市绿色交通的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E6%AD%BB%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B0%B7%E6%AD%8C%E7%90%86%E8%B4%A2?/tpi=gjN
- 社区便民集市的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/710
- 社区手工活动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/jed
- 社区阅读服务的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/GZ8
- 城市运动公园的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/270=mmh
- 社区活动报名的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/xxw=131
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/KnF=TFp
- 智慧城市体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/710
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/fvp
- 社区家校合作的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/Zce
- 新能源出行的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/808=wnh
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/kua=495
- 医院导诊服务的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E7%90%86%E8%B4%A2?/2nY=itt

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
