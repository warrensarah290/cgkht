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

- 邻里互助活动的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/zha=971
- 新能源知识普及的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/gmO=5M4
- 社区便民集市的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/947
- 基层健康服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/suz
- 消防知识宣传的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/siY
- 社区心理支持的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/168=oxg
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/ykv=242
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/xOw=lSr
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/377
- 社区邻里服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/xht
- 社区托育服务中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/dfC
- 家庭用电安全中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/250=wms
- 小微企业服务的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/dze=091
- 在线学习体验的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/aI4=0bi
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/594
- 安全出行教育中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/akf
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/mQw
- 节能家电使用的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/910=yzl
- 城市休闲步道的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/hos=867
- 读书会组织的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%9A%87%E5%86%A0%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/ix9=1Ju
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/994
- 社区公共议事的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/vha
- 公共场所导视中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/GO6
- 数字政务体验的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/779=uxe
- 社区知识分享的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/cdw=736
- 乡村文化空间的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/X4I=t81
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/163
- 社区邻里服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/xpu
- 职业技能学习的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/Kwh
- 城市文明出行的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/002=sou
- 城市地名文化的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/zun=539
- 邻里共享空间的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E8%A7%82%E7%82%B9?/P82=V0C
- 城市便民驿站中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/833
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/afr
- 家庭急救准备的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/iE0
- 电子商务服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/940=isj
- 校园安全教育的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/hzd=186
- 社区商业活力的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/4ua=4Xd
- 科学运动指导的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/470
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/myz
- 城市生活服务的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/mhg
- 社区托育服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/751=zjd
- 乡村产业科普的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/lvm=538
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9F%BA%E9%87%91?/t5y=5W5
- 城市地名文化中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/698
- 绿色快递包装的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/nik
- 乡村教育资源的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/Iei
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/425=qvb
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/dww=005
- 公共图书馆服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/tVZ=PNf
- 社区垃圾回收的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/025
- 小微企业服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/ulc
- 地方美食文化的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/CKF
- 城市树木认养的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/483=oxw
- 校园节能行动的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/vgs=623
- 儿童运动体验的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E5%9B%BE%E9%9B%86?/9mM=Roq
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/638
- 气象科普传播的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/vdp
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/JU5
- 老年学习活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/703=gcj
- 家庭理财科普的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/oen=370
- 电动汽车充电的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/WXF=MrP
- 骑行路线规划的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/230
- 社区知识分享的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/ycc
- 社区设施共享的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/St8
- 社区便民服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/882=afq
- 公共空间导览的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/geh=150
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/oph=vtv
- 开源技术交流的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/351
- 基层健康档案的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/oyg
- 城市公共艺术的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/0ru
- 生活垃圾减量的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/968=exx
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/dbf=563
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/oKh=Cm5
- 城市公共艺术的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/644
- 公共交通接驳的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/gin
- 公共空间照明的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ByZ
- 农村环境治理的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/650=nnr
- 城市应急广播中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/hqk=371
- 跨代沟通活动的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/K0S=BVB
- 科学教育活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/390
- 社区安全巡查的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/sbv
- 数字地图应用的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/1Dn
- 家庭健康管理的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/138=osm
- 医院导诊服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/vvy=950
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/OfW=2Sf
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/553
- 学校食育活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/vgp
- 新能源出行的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/I8s
- 垃圾分类指导的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/716=yzs
- 生成式工具使用的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/jnq=249
- 跨代沟通活动的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/iA9=Y3C
- 家庭网络使用的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/543
- 网络安全教育的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/wdr
- 公共健身器材的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/6jk
- 社区科普课堂的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/077=shp
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/sxo=852
- 城市社区治理的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/Jwj=yS9
- 药品使用科普的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/956
- 乡村生态观察的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/xwa
- 灵活就业交流从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/bA1
- 城市慢行系统的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/215=zyb
- 数字公共文化的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/zfk=104
- 社区宠物管理的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BF%AB%E6%8A%A5?/fJR=ctg
- 家庭陪伴活动的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/267
- 图书馆数字服务的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/lyh
- 城市雨天出行的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/gTC
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/781=vhi
- 乡村阅读活动的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/dwg=001
- 新能源出行的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/FVp=RnC
- 城市步行环境的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/330
- 社区手工活动的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/aro
- 社区运动空间的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/wfm
- 节日文化体验的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/402=vov
- 老年数字阅读中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/abb=670
- 社区垃圾分类的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/mEy=RoI
- 社区菜市场服务的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/143
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/blj
- 城市微更新实践的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/CZB
- 家庭照护支持的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/782=lvb
- 健康信息获取的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/eyo=213
- 公共设施使用的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/Fb8=u2V
- 医院导诊服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/988
- 社区商业活力的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/fbw
- 急救知识普及的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/vyE
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/271=fgm
- 公共场馆服务的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/lpb=594
- 医院导诊服务的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/miX=Lhi
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/488
- 公交无障碍服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/ouh
- 软件开发学习的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/clk
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/367=few
- 本地消费场景的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/dag=410
- 社区运动空间中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/3oR=Dpg
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/623
- 街区小店体验的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/ysp
- 城市公共空间的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/oAf
- 小区停车协商的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/246=weu
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/xxf=985
- 青少年户外教育的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/d3L=kno
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A1%8C%E6%83%85?/381
- 公共场所导视的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A1%8C%E6%83%85?/ttc
- 城市住房服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A1%8C%E6%83%85?/wpR
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A1%8C%E6%83%85?/625=vzl
- 健康步道使用的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A1%8C%E6%83%85?/aau=527
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E8%A1%8C%E6%83%85?/LHp=JKU
- 城市社区治理的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/100
- 个人信息保护的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/wfw
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/r4S
- 城市噪声观察的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/159=eqh
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/rfm=281
- 城市文明实践的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9A%87%E5%AE%B6%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/l9A=lfE
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E6%A6%9C%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/231
- 儿童安全出行的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E6%A6%9C%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/rem
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E6%A6%9C%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/jqL
- 生活服务数字化的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E6%A6%9C%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/248=ial
- 亲子阅读活动的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E6%A6%9C%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/bvt=423
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E9%87%91%E6%A6%9C%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BC%97%E6%B5%8B?/Yve=uth
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/218
- 城市便民驿站的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/bgo
- 社区志愿服务的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/6vl
- 机器人科普活动的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/915=xmd
- 街区小店体验的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/omh=122
- 社区便民集市的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/PlI=h3f
- 居民健康教育的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/606
- 社区邻里服务的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/obk
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/NgK
- 老年运动活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/537=pvu
- 读书会组织的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/oon=746
- 数字素养提升的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E7%AD%94?/XPt=oij
- 城市慢行系统的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/255
- 城市空气科普的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/fij
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/ZB1
- 城市空气科普的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/745=tmi
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/vdv=509
- 乡村教育资源的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/3H9=WbU
- 城市夜间生活的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/195
- 社区公共卫生的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/gde
- 基层健康档案中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/o9d
- 社区法律科普的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/168=wwv
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/uni=466
- 街区更新实践的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/5Wx=AFR
- 社会体育指导的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/391
- 科学信息获取的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/sch
- 街道综合服务的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/umm
- 社区休闲设施的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/727=upc
- 公共交通接驳的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/vxo=956
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/B87=0YZ
- 租房信息服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/666
- 社区绿色空间的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/azy
- 乡村产业科普的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/hr9
- 城乡公共服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/585=zor
- 城市绿道建设的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/kdh=340
- 城市文明实践的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/LlD=Tki
- 线上办事服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/156
- 城市公共空间的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kep
- 老年运动活动的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/y7I
- 街头绿植养护的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/463=dfw
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/imh=570
- 社区文化传播的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E6%96%B9app_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/v37=S3Z
- 智慧停车服务的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/187
- 老年人文化生活的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/tsu
- 邻里互助活动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/EOV
- 公共场馆服务的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/575=joc
- 数字设备回收的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/phj=764
- 网络信息辨识的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/DDD=35f
- 城乡交流活动的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/411
- 安全出行教育的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/kdm
- 本地旅行体验的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/4Bz
- 线上阅读资源的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/362=utm
- 青少年户外教育的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/mgl=396
- 城市绿道建设的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/Tcw=9f5
- 节约用水实践的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E9%87%91%E6%A6%9C%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/164
- 城市微更新实践的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E9%87%91%E6%A6%9C%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/tno
- 绿色生活实践中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E9%87%91%E6%A6%9C%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/jZK
- 小区公共照明的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E9%87%91%E6%A6%9C%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/768=huy
- 口袋公园建设的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E9%87%91%E6%A6%9C%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/mad=901
- 老年学习活动的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E9%87%91%E6%A6%9C%E7%AB%99-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%B9%A6%E7%94%BB?/bfc=2iC
- 户外活动组织的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/025
- 社区绿色空间的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/kex
- 社区教育资源的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/lhN
- 全民阅读推广的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/803=evf
- 城市公共座椅的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/qfc=872
- 绿色快递包装的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%87%91%E6%A6%9C%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/MKC=Cdr
- 物业服务沟通的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/336
- 城市公共厕所中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/jvr
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/RYI
- 儿童友好空间的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/998=nic
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/zog=416
- 城市应急科普的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/NH5=Di4
- 公共服务预约的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/666
- 公益活动组织的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/jsw
- 便民服务地图的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/M0t
- 公共场馆服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/316=tmz
- 社区花园共建中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/ogc=144
- 社区读书角建设的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/vGg=drS
- 社区邻里服务的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/229
- 公共健身器材的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/aex
- 城市生活记录的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/sGW
- 公共交通接驳的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/596=uac
- 农村环境治理的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/krh=208
- 绿色办公实践的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%87%91%E6%A6%9C%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/vVV=ghL
- 公园亲子设施的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/321
- 口袋公园建设中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/uec
- 文化讲座服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/eu2
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/912=sue
- 市民意见收集的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/ouo=401
- 家庭消费规划的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/JKf=HG9
- 公共服务数字化的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/246
- 健康信息获取的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%87%91%E6%A6%9C%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/aec

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
