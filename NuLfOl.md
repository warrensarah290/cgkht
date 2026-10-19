# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 家庭志愿活动的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/ufu=589
- 旧物循环利用的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/NNQ=5BA
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/943
- 社区教育资源的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/kpp
- 城市公共标识的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/H0f
- 旧物循环利用的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/733=uzo
- 社区快递服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/wam=062
- 骑行路线规划的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/IeX=2ml
- 居家适老化改造的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_360%E8%A7%82%E5%AF%9F?/375
- 文化讲座服务的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_360%E8%A7%82%E5%AF%9F?/pty
- 绿色生活实践中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_360%E8%A7%82%E5%AF%9F?/mOS
- 公共服务评价的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_360%E8%A7%82%E5%AF%9F?/810=rnp
- 本地消费场景的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_360%E8%A7%82%E5%AF%9F?/bta=135
- 城市基础设施中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8_360%E8%A7%82%E5%AF%9F?/Xxh=rxg
- 电动汽车充电的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/097
- 社区艺术活动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/nst
- 城市公共座椅的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/zZ6
- 公共服务评价的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/009=csk
- 地方戏曲体验的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/oeq=021
- 读书会组织的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/zh0=Hld
- 城市适老服务的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/451
- 校园社团活动的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/esm
- 街区小店体验的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/LUA
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/383=jbu
- 市民热线服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/gmv=849
- 社区共享书架的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/WTs=dnA
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/497
- 图书馆数字服务的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/ocd
- 健康饮食教育的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/CC0
- 公共服务预约的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/489=icm
- 社区协商议事的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/btp=714
- 社区便民集市的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/Ynp=bGt
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/284
- 儿童友好街区的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/vam
- 通勤路线规划的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/Mha
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/138=xfu
- 骑行路线规划的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/tsu=165
- 街区绿化养护的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%A4%B4%E6%9D%A1?/jok=NAU
- 公共空间导览的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/153
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/qgx
- 城市绿色交通的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/UhO
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/639=mcy
- 城市夜间照明的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/aol=167
- 公共空间导览的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%94%BF%E5%8A%A1?/Yux=yvu
- 乡村公共阅读的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/320
- 个人信息保护的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/ohi
- 智慧城市体验的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/3vH
- 乡村公共文化的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/569=fok
- 物业服务沟通的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/zcd=762
- 社区学习活动的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/Dn7=aLl
- 农产品消费体验的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/614
- 社区养老服务的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/cif
- 城市雨天出行的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/aIR
- 儿童户外活动的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/157=sjl
- 科学健身方法的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/pwn=884
- 科普展览体验的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/O7w=9Us
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/107
- 公园亲子设施的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/xqh
- 生活垃圾减量的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/koD
- 软件开发学习的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/609=bwg
- 社区托育服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/pgi=345
- 数字生活课堂的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/YoK=0NX
- 公共空间休憩的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/377
- 社区故事采集的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/yel
- 公共场所导视的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/WG8
- 公共服务预约的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/825=eaa
- 学校食育活动的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/guk=702
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/AC7=cYR
- 青年志愿活动的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/507
- 社区活动报名中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/fye
- 本地历史资料的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/cOl
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/277=eli
- 无障碍出行的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/ram=947
- 图书借阅体验的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/0ef=M8V
- 社区公共议事的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%95_%E8%99%8E%E6%89%91%E6%94%BF%E5%8A%A1?/811
- 家庭志愿活动的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%95_%E8%99%8E%E6%89%91%E6%94%BF%E5%8A%A1?/opx
- 公共空间安全的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%95_%E8%99%8E%E6%89%91%E6%94%BF%E5%8A%A1?/LaR
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%95_%E8%99%8E%E6%89%91%E6%94%BF%E5%8A%A1?/354=wlf
- 老年人文化生活中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%95_%E8%99%8E%E6%89%91%E6%94%BF%E5%8A%A1?/tiu=907
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%95_%E8%99%8E%E6%89%91%E6%94%BF%E5%8A%A1?/tjx=Yen
- 社区活动空间的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/341
- 街区更新实践中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/pqv
- 城市应急科普的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/nT2
- 社区活动策划的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/432=ptz
- 城市建设科普的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/efg=621
- 儿童阅读角的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/lf5=YqA
- 社区运动空间的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/687
- 公共服务指南的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/guf
- 城市步行友好的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/KJm
- 本地消费场景的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/207=giq
- 图书馆活动策划的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/gor=153
- 家庭安全提示的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/Ab5=5CH
- 劳动教育实践的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/159
- 城市步行友好的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/ygh
- 家庭教育交流的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/2RQ
- 文明养宠科普中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/743=luh
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/ixr=684
- 乡村文化空间的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/qWv=29P
- 社区健康讲座的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/445
- 居民健康教育的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/kte
- 儿童安全出行的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/d4x
- 社区修缮行动的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/434=zzh
- 数字阅读服务的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/tzv=958
- 线上阅读资源的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/pjb=GER
- 社区防暑服务的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E7%8E%8B%E5%8F%8C%E8%89%B2%E7%90%83%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/573
- 图书借阅体验的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E7%8E%8B%E5%8F%8C%E8%89%B2%E7%90%83%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/lsz
- 青少年心理健康的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E7%8E%8B%E5%8F%8C%E8%89%B2%E7%90%83%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/x0h
- 社区志愿服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E7%8E%8B%E5%8F%8C%E8%89%B2%E7%90%83%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/547=caq
- 运动安全知识的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E7%8E%8B%E5%8F%8C%E8%89%B2%E7%90%83%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/tei=370
- 职业技能学习中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E7%8E%8B%E5%8F%8C%E8%89%B2%E7%90%83%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/Yqo=pRj
- 社区艺术活动的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%951.3.9_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/376
- 乡村文化空间的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%951.3.9_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/axt
- 社区文化节活动的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%951.3.9_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/PMG
- 社区公共议事中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%951.3.9_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/482=gsh
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%951.3.9_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/yvc=917
- 科学教育活动的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%951.3.9_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/QPl=QXe
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%80%8D%E6%8A%95_36%E6%B0%AA%E6%B0%91%E7%94%9F?/551
- 开放数据应用的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%80%8D%E6%8A%95_36%E6%B0%AA%E6%B0%91%E7%94%9F?/zat
- 家庭教育交流的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%80%8D%E6%8A%95_36%E6%B0%AA%E6%B0%91%E7%94%9F?/NBx
- 学校体育活动的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%80%8D%E6%8A%95_36%E6%B0%AA%E6%B0%91%E7%94%9F?/297=rwx
- 公共卫生设施的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%80%8D%E6%8A%95_36%E6%B0%AA%E6%B0%91%E7%94%9F?/mmx=975
- 全民健身活动的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%80%8D%E6%8A%95_36%E6%B0%AA%E6%B0%91%E7%94%9F?/Tch=vM8
- 数字支付体验的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E6%88%98%E8%83%9C%E4%B8%8D%E4%BA%86%E6%A6%82%E7%8E%87_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/026
- 城市应急广播的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E6%88%98%E8%83%9C%E4%B8%8D%E4%BA%86%E6%A6%82%E7%8E%87_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/dsc
- 城市空气科普的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E6%88%98%E8%83%9C%E4%B8%8D%E4%BA%86%E6%A6%82%E7%8E%87_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/PED
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E6%88%98%E8%83%9C%E4%B8%8D%E4%BA%86%E6%A6%82%E7%8E%87_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/246=vrx
- 社区消防演练的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E6%88%98%E8%83%9C%E4%B8%8D%E4%BA%86%E6%A6%82%E7%8E%87_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/mcs=730
- 邻里互助活动的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E6%88%98%E8%83%9C%E4%B8%8D%E4%BA%86%E6%A6%82%E7%8E%87_%E4%BA%AC%E4%B8%9C%E6%85%A7%E7%9C%BC?/L3w=WCI
- 无障碍出行的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/561
- 社区知识分享的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/ijm
- 社区停车服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/9bO
- 城市便民驿站的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/088=bmi
- 医院导诊服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/pfz=321
- 街区更新实践的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/d0L=hD5
- 公共交通接驳的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C6%E4%B8%AA%E5%8F%B7%E5%AF%B9%E5%88%B7%E5%8F%8D%E6%B0%B4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/937
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C6%E4%B8%AA%E5%8F%B7%E5%AF%B9%E5%88%B7%E5%8F%8D%E6%B0%B4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/jfk
- 无障碍出行的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C6%E4%B8%AA%E5%8F%B7%E5%AF%B9%E5%88%B7%E5%8F%8D%E6%B0%B4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/7Ud
- 社区知识分享的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C6%E4%B8%AA%E5%8F%B7%E5%AF%B9%E5%88%B7%E5%8F%8D%E6%B0%B4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/710=avo
- 本地旅行体验的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C6%E4%B8%AA%E5%8F%B7%E5%AF%B9%E5%88%B7%E5%8F%8D%E6%B0%B4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/kfq=730
- 居家适老化改造的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C6%E4%B8%AA%E5%8F%B7%E5%AF%B9%E5%88%B7%E5%8F%8D%E6%B0%B4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E5%BA%97?/JF5=24X
- 小区电梯维护的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E4%B8%87%E8%83%BD%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/517
- 社区阅读服务的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E4%B8%87%E8%83%BD%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/yws
- 城市夜间照明的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E4%B8%87%E8%83%BD%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/qx5
- 社区环保活动的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E4%B8%87%E8%83%BD%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/008=zve
- 公共空间照明的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E4%B8%87%E8%83%BD%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/axj=180
- 乡村公共阅读的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%9C%A8%E7%BA%BF%E4%B8%87%E8%83%BD%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/Ngc=skz
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/501
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/htu
- 街区绿化养护的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/lyd
- 地方美食文化的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/046=eoz
- 城市建设科普的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/dup=744
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/TIr=WN6
- 社区绿色空间的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/811
- 数字素养提升的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/txs
- 物业服务沟通的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/6k9
- 生活垃圾减量的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/884=zbu
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/gwx=343
- 生成式工具使用的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/9pK=iru
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/722
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/gfs
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/mmN
- 日常摄影记录的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/853=etd
- 街道综合服务的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/kuo=585
- 图书借阅体验的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/GzH=agN
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/505
- 智慧城市体验的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/ecq
- 数字素养提升的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/QDO
- 邻里共享空间的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/004=rss
- 生活垃圾回收的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/hsn=171
- 新能源知识普及的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/hHn=iLZ
- 公共服务指南的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/562
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/tbi
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/yCs
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/197=sva
- 数字便民地图的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/bxm=253
- 机器学习入门的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/TIf=84S
- 日常摄影记录的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BB%8E%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/928
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BB%8E%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/xuu
- 基层健康服务的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BB%8E%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/It6
- 信息无障碍体验的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BB%8E%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/497=syd
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BB%8E%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/koy=536
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%BB%8E%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E5%86%85?/zzZ=y17
- 社区安全巡查的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/668
- 食品安全科普的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/gfp
- 电动汽车充电的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/kGX
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/564=ubb
- 社区体育组织的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/lcj=105
- 地方民俗记录中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/rZu=gqA
- 小区公共照明的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B03D%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/100
- 数字公共文化的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B03D%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/aoz
- 数字学习资源的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B03D%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/ncR
- 无障碍出行的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B03D%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/144=lph
- 志愿服务平台的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B03D%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/kso=106
- 公共空间导览的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B03D%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/Ohu=6h9
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/397
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/gke
- 社区休闲设施的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/HL1
- 城市公共标识的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/949=dsr
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/mds=926
- 绿色消费选择中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8F%AF%E4%BB%A5%E5%9C%A8%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/vf0=OTq
- 青少年户外教育的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%9C%A8%E7%BA%BF%E8%B4%AD%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/578
- 图书借阅体验的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%9C%A8%E7%BA%BF%E8%B4%AD%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/uht
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%9C%A8%E7%BA%BF%E8%B4%AD%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/JOd
- 小区停车协商的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%9C%A8%E7%BA%BF%E8%B4%AD%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/150=dmt
- 社区安全巡查的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%9C%A8%E7%BA%BF%E8%B4%AD%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/qnt=561
- 城市基础设施的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%9C%A8%E7%BA%BF%E8%B4%AD%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/XOo=GWR
- 家庭运动计划的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%94%B5%E5%AD%90%E5%88%AE%E5%88%AE%E4%B9%90app_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/158
- 城市骑行环境的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%94%B5%E5%AD%90%E5%88%AE%E5%88%AE%E4%B9%90app_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/gkf
- 农业科普体验的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%94%B5%E5%AD%90%E5%88%AE%E5%88%AE%E4%B9%90app_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/aAV
- 家庭教育交流的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%94%B5%E5%AD%90%E5%88%AE%E5%88%AE%E4%B9%90app_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/093=knz
- 公共服务指南的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%94%B5%E5%AD%90%E5%88%AE%E5%88%AE%E4%B9%90app_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/djb=802
- 社区设施共享的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%94%B5%E5%AD%90%E5%88%AE%E5%88%AE%E4%B9%90app_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/iU5=tSb
- 乡村生态旅游的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/379
- 城市社区治理的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/nto
- 信息无障碍体验的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/chF
- 城市共享单车的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/346=eaw
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/rxb=656
- 开放数据应用的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/ATC=goH
- 健康饮水科普的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E4%BF%A1%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/833
- 课后服务体验的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E4%BF%A1%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/cch
- 家庭用电安全的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E4%BF%A1%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/Uuv
- 家庭安全提示的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E4%BF%A1%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/061=uco
- 城市体育设施的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E4%BF%A1%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/jid=060
- 便民信息查询中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BE%AE%E4%BF%A1%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0%E5%8F%8C%E8%89%B2%E7%90%83_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/DaQ=Bvi
- 人工智能科普的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E7%9B%B4%E6%8E%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/631
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E7%9B%B4%E6%8E%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/dhf
- 乡村文化活动的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E7%9B%B4%E6%8E%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/G1S
- 社区庭院绿化的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E7%9B%B4%E6%8E%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/715=mkv
- 数字生活课堂的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E7%9B%B4%E6%8E%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/lxk=422
- 科学健身方法的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E7%9B%B4%E6%8E%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/kz5=ntp
- 城市可持续生活的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%9C%A8%E5%AE%9E%E4%BD%93%E5%BA%97%E4%B9%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/377
- 健康步道使用的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%9C%A8%E5%AE%9E%E4%BD%93%E5%BA%97%E4%B9%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/nvs
- 街道综合服务的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%9C%A8%E5%AE%9E%E4%BD%93%E5%BA%97%E4%B9%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/P0Y
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%9C%A8%E5%AE%9E%E4%BD%93%E5%BA%97%E4%B9%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/534=hix
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%9C%A8%E5%AE%9E%E4%BD%93%E5%BA%97%E4%B9%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/vla=591
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8F%AA%E8%83%BD%E5%9C%A8%E5%AE%9E%E4%BD%93%E5%BA%97%E4%B9%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/kLR=Id7
- 老年智能设备的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/163
- 课后服务体验的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/dgb
- 家庭用电安全的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/wEV
- 科普展览体验的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/110=vai
- 个人信息保护的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/klj=793
- 老年人出行服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/BkY=i1g
- 社区儿童活动的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/763
- 垃圾分类指导的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/bzq
- 家庭教育交流的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/aQ5
- 城市公共厕所的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/380=qom
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/vqu=596
- 智能家居应用的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/K94=Av6
- 城市微更新实践的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A6%82%E4%BD%95%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91?/947
- 智慧城市体验的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A6%82%E4%BD%95%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91?/aen

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
