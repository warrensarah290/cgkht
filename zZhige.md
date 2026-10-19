# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 街区更新实践的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/610
- 社区便利生活的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/urn
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/PR5
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/359=azf
- 公共服务数字化的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/bvo=980
- 老年学习活动的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/YjW=iXI
- 绿色建筑理念的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/960
- 公交站点体验的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/mxf
- 远程协作工具的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/ete
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/990=ycb
- 城市生活服务的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/dhg=993
- 健康饮食教育的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/ntQ=Db6
- 城市基础设施的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/793
- 节气饮食文化的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/kfo
- 城市运动公园的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/yzn
- 课后服务体验的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/700=anx
- 基层健康档案的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/ryi=248
- 科学教育活动的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/2I3=tEB
- 乡村生态观察中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/980
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/vbu
- 户外活动组织的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/ylF
- 家庭陪伴活动的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/753=haj
- 科技馆参观体验的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/wme=347
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/pXT=n5g
- 公共服务评价的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/684
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/vqe
- 家庭节能实践的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/O1I
- 乡村阅读空间的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/921=aev
- 便民服务窗口的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/yvf=232
- 远程协作工具的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BF%85%E5%BA%94%E5%B9%B6%E8%B4%AD?/U9J=kg3
- 科学健身方法的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/623
- 家庭用电安全的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/wta
- 社区便民服务的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/cYq
- 小区停车协商的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/195=bdo
- 儿童户外活动的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/zsb=659
- 儿童阅读角中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%BE%9F%E8%B0%A3?/TyY=4KO
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/304
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/mcf
- 农村环境治理的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/cmp
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/122=mkb
- 社区宠物管理的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/xzq=113
- 本地消费场景的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/y7o=hQ4
- 在线学习体验的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/853
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/jmm
- 创业经验分享的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/3e9
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/280=mxq
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/rxf=472
- 校园社团活动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/BJA=jEP
- 数字支付体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/966
- 青少年科普实践的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/juu
- 公共健身器材的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/1wM
- 乡村文化活动的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/254=xqi
- 社区快递服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/cho=534
- 校园社团活动的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E6%9C%AD%E8%AE%B0?/vmq=Qf3
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/776
- 数字创作工具的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/bjl
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/vOu
- 社区安全巡查的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/761=vaw
- 绿色办公实践的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/ibj=338
- 家庭急救准备的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/2xH=nQX
- 本地消费场景的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/387
- 乡村阅读活动的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/npw
- 城市微更新实践的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/hUk
- 医院导诊服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/212=iua
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ihz=181
- 城市文明出行的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Gp1=Pqi
- 社区家校合作的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/242
- 社区故事采集的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/dqu
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/ZT9
- 户外活动组织的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/731=zyx
- 城市可持续生活的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/xqs=302
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/q4Z=cHh
- 老年人日常照护的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/552
- 急救知识普及的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/kpq
- 健康信息获取的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/OF3
- 图书借阅体验的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/646=aem
- 绿色校园实践的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/xbu=443
- 骑行路线规划的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/M2U=da0
- 居民健康教育的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/424
- 社区便利生活中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/ean
- 数字素养提升的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/6uY
- 地方民俗记录的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/046=ueq
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/gid=162
- 社区公共卫生的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/ffT=y0g
- 城市便民驿站的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/983
- 乡村文化活动的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/nys
- 气象科普传播的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/dqh
- 乡村公共阅读的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/455=muk
- 农村环境治理的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/lij=251
- 社区交通安全的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E7%89%B9%E7%A8%BF?/0Ij=SQ7
- 软件开发学习的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/489
- 城市体育设施的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/nqh
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/MHC
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/354=zox
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/fbs=391
- 城市绿色交通中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/12L=AcK
- 社区垃圾回收的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/944
- 生成式工具使用的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/ler
- 城市社区治理的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/aNS
- 社区文化传播的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/917=bao
- 小区停车协商的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/aob=803
- 街区绿化养护的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/miK=3d0
- 数字课堂应用的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/942
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/ckr
- 学校食育活动的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/vdI
- 社区庭院绿化的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/015=ulu
- 口袋公园建设的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/inu=326
- 软件开发学习的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/w6L=XWY
- 城市地名文化的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/451
- 数字素养提升的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/nrt
- 社区艺术活动的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/TeL
- 城市文化路线的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/826=ane
- 课后服务体验的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/olm=113
- 小微企业服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/a4F=Nlk
- 公共卫生宣传的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/844
- 生活技能分享的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/jwo
- 乡村阅读空间的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/ANe
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/857=hin
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/elx=391
- 家庭用电安全的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/sYD=PTs
- 邻里共享空间的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/432
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/aln
- 绿色消费选择的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/MLa
- 老年人出行服务的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/807=jcc
- 数字政务体验的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/zwt=174
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/0sU=fTs
- 读书会组织的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/997
- 老年学习活动的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/onv
- 社区手工活动的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/8G5
- 家庭消费规划的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/877=sko
- 城市展览体验的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/qdw=220
- 青年志愿活动的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/iUZ=1yL
- 校园社团活动的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/872
- 环境教育课程的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/vwd
- 城市绿道建设的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/h53
- 公共空间照明的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/346=rqf
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/tnq=998
- 城市文明实践的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/ZkF=I0i
- 线上阅读资源的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/494
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/dqx
- 线上办事服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/3WC
- 城市游园体验的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/434=kuv
- 节能家电使用的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/epa=720
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/u6g=kxf
- 社区互助网络的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A92023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/764
- 城市公共厕所的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A92023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/shw
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A92023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/ntz
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A92023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/672=vxm
- 家庭节能实践的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A92023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/iqu=702
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A92023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/I8t=Q63
- 儿童友好空间的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/349
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/xfv
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/TIP
- 数据分析入门的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/537=nrc
- 社区托育服务的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/jjx=025
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/88o=HVF
- 生活服务数字化的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/750
- 基层健康档案的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/qbh
- 个人信息保护的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/QAI
- 老年学习活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/855=fjt
- 网络安全教育的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/wvc=999
- 农贸市场环境的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/Qc7=q3r
- 环境教育课程的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/317
- 智能手机助老的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/dvv
- 社区艺术活动的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/Ls2
- 应急物资管理的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/886=vmf
- 社区环保活动的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/cdn=193
- 在线教育体验的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/zXR=Z6C
- 节能生活方式的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/653
- 社区设施共享的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/qjl
- 乡村文化空间的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/gVL
- 社区快递服务的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/932=bwl
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/ech=233
- 城市步行环境的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/nP2=BtW
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/304
- 线上阅读资源的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/zby
- 网络信息辨识有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/nNs
- 社区公共议事的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/496=php
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/ast=458
- 社区安全巡查的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/I7d=08E
- 就业技能培训的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/564
- 科技馆参观体验的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/mzj
- 健康饮水科普的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/zgF
- 社区学习活动的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/565=cqu
- 生活技能分享的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/krb=486
- 社区文化传播的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/pSX=ygR
- 社区运动空间的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/844
- 社会体育指导的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/mxf
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/rEa
- 家庭园艺实践的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/871=jus
- 社区养老服务的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/mkb=350
- 健康饮水科普的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/A1d=xFZ
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/690
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/wle
- 节气饮食文化的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/041
- 数字艺术创作的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/493=ocd
- 社区信息发布的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/jma=146
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/bbm=pCa
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/814
- 青少年心理健康的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/ioh
- 公共空间安全的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/HSE
- 社区艺术活动的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/928=qwn
- 社区便民集市的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/pfd=861
- 智能家居应用的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/UKT=XI8
- 老年人出行服务的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/599
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/pjj
- 青年职业探索的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/Hm1
- 地方文化传播的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/130=ver
- 人工智能科普的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/lhy=710
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/n21=pep
- 智能手机助老的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/693
- 社会体育指导的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/scd
- 生成式工具使用的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/xYJ
- 校园安全教育的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/001=shl
- 城市公共艺术的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/cdl=731
- 社区运动空间的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/8Bq=ob2
- 城市骑行环境的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/483
- 环境监测科普的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/nmi
- 软件开发学习的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/Gl8
- 老年运动活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/618=nho
- 家庭消费规划的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/kyy=394
- 基层健康服务的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/OKY=6Os
- 城市公共厕所的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/360
- 社区停车服务的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/vrx
- 公共空间照明的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/rJ5
- 城市公共厕所的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/855=yni
- 社区老年食堂的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/dxt=607
- 社区艺术活动的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/yKA=NMR
- 家庭收纳实践的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/086
- 日常摄影记录的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/ach
- 个人时间管理的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/LYP
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/140=nbg
- 周末休闲规划的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/ghh=870
- 老年人出行服务的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/WAH=fpx
- 老年友好服务的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/878
- 传统节日科普的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/vmn
- 线上办事服务的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/yFD
- 智慧城市体验的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/903=ehe
- 家庭网络使用的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/arv=213
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/84Y=STV
- 儿童安全出行的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/733
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/iwl
- 小微企业服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/Kke
- 城市骑行环境的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/218=bzx
- 儿童安全出行的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/omj=334
- 全民健身活动的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/DAv=BQm
- 校园社团活动的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/646
- 地方旅游导览的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/nqj
- 基层健康档案的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/d51
- 城市博物馆服务的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/789=ysf

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
