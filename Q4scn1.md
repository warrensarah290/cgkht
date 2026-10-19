# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 地方戏曲体验的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/zjz=871
- 开放数据应用的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/Hsw=rPB
- 租房信息服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/205
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/gvk
- 城市空气科普的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/b7w
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/239=myb
- 城乡公共服务的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/jbq=522
- 家庭运动计划的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/ND6=kM3
- 开源技术交流的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/004
- 数字资源检索的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/mhp
- 地方文化传播的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/Quh
- 青年志愿活动的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/902=wpe
- 农业科普体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/zra=705
- 城市噪声观察的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/bWq=sUu
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/870
- 节假日出行安排的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/qqw
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/1Mt
- 生活垃圾回收的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/440=lll
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/hls=413
- 城市公共艺术的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/E4o=Od5
- 街头绿植养护的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/070
- 健康步道使用的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/qrn
- 社区艺术活动的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/5oJ
- 数字设备回收的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/345=vuw
- 城市绿色交通的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/nbk=660
- 城市微更新实践的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/4oz=j79
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/375
- 数据分析入门的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/zth
- 健康步道使用中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/3Er
- 青年就业服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/077=rfs
- 科学运动指导的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/nmq=126
- 城市可持续生活的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/V5D=81S
- 乡村产业科普的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/077
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/agn
- 健康饮食教育的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/Oz5
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/277=kod
- 文明养宠科普的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/vbt=506
- 城市步行环境中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/no5=nkl
- 家庭节能实践的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/728
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/hnx
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/KEr
- 小区公共照明的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/567=grz
- 公共服务数字化的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/blj=299
- 社区修缮行动的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/kG4=vxl
- 食品配送体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/614
- 数字阅读服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/zyu
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/dtK
- 校园节能行动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/692=tte
- 家庭健康管理的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/mut=295
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/2vU=mVY
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E5%8E%86%E5%8F%B2?/982
- 老年人日常照护的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E5%8E%86%E5%8F%B2?/tkc
- 社区便利生活的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E5%8E%86%E5%8F%B2?/Ves
- 公园亲子设施中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E5%8E%86%E5%8F%B2?/660=xsp
- 青年职业探索的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E5%8E%86%E5%8F%B2?/rqs=285
- 小区公共照明的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B0%B7%E6%AD%8C%E5%8E%86%E5%8F%B2?/Zsz=g2k
- 城市雨天出行的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/014
- 农贸市场环境的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/jlz
- 社区交通安全的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/nVO
- 青少年科技社团的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/731=wqx
- 公交站点体验的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/ctf=751
- 远程协作工具的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/qbl=yFf
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/511
- 家庭急救准备的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/bec
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/LEY
- 乡村生态旅游的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/883=nnt
- 社区环保活动的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/dum=728
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/CYx=0q6
- 健康信息获取的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/613
- 社区故事采集的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/qrr
- 科技馆参观体验的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/N41
- 社区养老服务的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/026=htg
- 社区活动报名的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/xzh=787
- 家庭园艺实践的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%80%89%E5%8F%B7_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/h8t=YZS
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/109
- 市民意见收集的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/gyk
- 机器人科普活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/itu
- 城市公共艺术的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/894=mpe
- 城市休闲步道中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/jwj=463
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/xvk=RCD
- 城市绿道建设的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/429
- 邻里共享空间的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/gyl
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/wjC
- 儿童安全出行的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/203=jdw
- 社区互助网络的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/cgt=273
- 数字政务体验的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/aKN=IzZ
- 城市博物馆活动的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/252
- 社区养老服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/mig
- 社区健康讲座的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/cE2
- 绿色建筑理念的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/555=tep
- 社区便民集市的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/ftb=630
- 节能生活方式的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BC%98%E9%85%B7%E4%BC%97%E6%B5%8B?/ces=0J3
- 城市文明实践的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/636
- 便民信息查询的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/qcz
- 社区文化节活动的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/g7X
- 城市休闲步道的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/253=dwl
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/oek=564
- 城乡公共服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/8Tx=Az2
- 社区教育资源的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/696
- 数字生活课堂的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/gku
- 低碳社区实践的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/8Be
- 网络信息辨识的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/888=puw
- 农业科普体验的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/txo=027
- 社区家校合作中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/fnC=h86
- 家庭收纳实践的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/333
- 校园节能行动的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/gmt
- 街道综合服务的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/N1u
- 应急物资管理的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/121=yuj
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qcv=716
- 社区法律科普的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/N6o=gtD
- 青年志愿活动中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/519
- 城市水环境观察中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/sxh
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/9qW
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/909=boh
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/nbw=690
- 城市便民驿站的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/Pjr=4hH
- 城市文明出行的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/540
- 城市绿色交通的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/fxx
- 零废弃生活尝试中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/JJ6
- 绿色生活实践的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/566=owm
- 家庭用电安全的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/ttn=674
- 生成式工具使用的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/rcb=h8f
- 学校体育活动的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/429
- 公园亲子设施的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/bjo
- 城市休闲步道的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/wxn
- 公共图书馆服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/159=xah
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/lnn=171
- 家庭健康科普的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/eJa=xwz
- 信息无障碍体验的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/466
- 公共空间照明的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/ylz
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/AQv
- 公交站点体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/461=vnq
- 小微企业服务的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/ocy=562
- 社会体育指导的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/JtH=7tj
- 青少年科普实践的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/331
- 乡村生活观察的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/iiu
- 老年学习活动的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/M0F
- 乡村公共服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/038=wji
- 家庭照护支持的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/kcv=715
- 儿童友好空间的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/XXZ=OK6
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/012
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/wlq
- 青年职业探索的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/TBe
- 城市应急科普的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/802=zma
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/rpz=698
- 城市微更新实践的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%B4%A2%E7%BB%8F?/OWK=3YL
- 家庭饮食安排的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_3%E5%88%86%E5%BF%AB3app_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/367
- 本地旅行体验的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_3%E5%88%86%E5%BF%AB3app_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/zdw
- 社区养老服务的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_3%E5%88%86%E5%BF%AB3app_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/ZbM
- 家庭健康科普的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_3%E5%88%86%E5%BF%AB3app_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/573=hbp
- 社区垃圾回收的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_3%E5%88%86%E5%BF%AB3app_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/lal=831
- 儿童友好空间的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_3%E5%88%86%E5%BF%AB3app_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/95K=nWB
- 数字生活课堂的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/661
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/upd
- 绿色校园实践的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/kfZ
- 城市步行环境的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/645=kqj
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/aih=980
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/sOM=GbW
- 个人数据管理的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/333
- 社区家政服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/jmj
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/OVn
- 科学观察活动的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/880=ryv
- 健康信息获取的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/eym=112
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/stc=iqQ
- 社区养老服务的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/107
- 社会体育指导的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/pya
- 社区慢性病防控的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/SCT
- 绿色办公实践的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/242=ewz
- 城乡交通衔接的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/jky=060
- 本地旅行体验的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/TB5=G9K
- 社区庭院绿化的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/269
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/kpm
- 社区修缮行动的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/VzJ
- 城市公共厕所的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/337=vtv
- 劳动教育实践的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/hzf=516
- 街区更新实践的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/kap=ZeS
- 城市文明出行的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/694
- 公共服务指南的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/oik
- 亲子科普活动的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/Omv
- 城市基础设施的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/262=olx
- 开源技术交流的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/ens=227
- 远程协作工具的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/eag=lwn
- 公共场所导视的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/849
- 数字资源检索的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/lvp
- 节能家电使用的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/qrH
- 食品安全科普的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/611=hxq
- 科学教育活动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/amq=635
- 乡村休闲旅游的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/IdO=0Ic
- 数据分析入门的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/614
- 节日文化体验中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/kif
- 公共设施使用的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/x8s
- 学校食育活动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/337=eam
- 家庭环保行动的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/zrn=955
- 本地消费场景的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/X6u=xe3
- 基层医疗预约的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/878
- 农贸市场环境的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/bsl
- 小区电梯维护的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/HZx
- 志愿服务平台的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/582=lay
- 本地历史资料的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/xgw=206
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%97%E7%A4%BE%E8%AE%BA?/quB=tpb
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/629
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/epa
- 开放式学习空间的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/aDb
- 社区共享书架的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/280=ewb
- 社区体育组织的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/nlq=312
- 城市文明实践的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/aqx=2My
- 智慧停车服务的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/133
- 线上办事服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/ysp
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/iZ5
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/961=ctg
- 跨代沟通活动的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/hzk=051
- 公共空间导览的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E4%B8%8A%E5%B2%B8_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/AyC=Px5
- 家庭环保习惯的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/510
- 非遗体验活动的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/udb
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/LNI
- 社区家政服务的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/068=bpn
- 物业服务沟通的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/gsg=069
- 乡村文化空间的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_3%E5%88%86%E5%BF%AB3%E9%80%89%E5%8F%B7_%E7%99%BE%E5%BA%A6%E7%89%B9%E7%A8%BF?/0m8=t7c
- 数字学习资源的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/309
- 公共设施维护的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/njp
- 无障碍信息设计的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/UQJ
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/637=del
- 健康饮水科普的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/jbp=826
- 文化讲座服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E4%BB%A3%E7%90%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/g6R=r32
- 社区花园共建的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/329
- 社区艺术活动的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/uil
- 校园安全教育的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/0rq
- 数字素养提升中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/406=siu
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/ukn=615
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%94%BF%E7%AD%96?/3On=xOK
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/898
- 城市应急科普的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/pcs
- 乡村教育资源的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/A43
- 城市空气科普的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/189=jzf
- 家庭饮食安排的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/qqh=873
- 城市公共空间的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/jEr=rMx
- 绿色消费选择的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/900
- 农村环境治理的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/gav
- 社区共享书架的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/8GA
- 口袋公园建设的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/878=cxz
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/jks=123
- 公共服务数字化的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/Muf=SVX
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_5%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/930
- 数字创作工具的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_5%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/jri
- 基层健康档案的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_5%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/wnY
- 街区绿化养护的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_5%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/357=fhz
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_5%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/tdt=517
- 社区文化传播的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_5%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/VdG=Lck
- 开源技术交流的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/547
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/fhy

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
