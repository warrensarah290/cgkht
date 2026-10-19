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

- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/153
- 小区公共照明的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/exm
- 居民健康教育的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/g37
- 食品安全科普的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/396=qkg
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/hti=246
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/I2w=eQb
- 开放数据应用的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/940
- 周末休闲规划的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/nwt
- 社区法律科普的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/UyM
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/136=hcb
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/atv=046
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/oDy=2B2
- 社区环保活动中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/395
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/azt
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/Nzr
- 街道综合服务的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/489=iec
- 公园休闲体验的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/kvd=925
- 街区更新实践的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/eQa=YnU
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/818
- 社区停车服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/uai
- 公共服务评价的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/BHu
- 节约用水实践的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/678=bpx
- 社区交通安全的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/tou=788
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/fyX=ZVA
- 家庭教育交流的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/761
- 社区应急准备的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/xfl
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/eu5
- 社区阅读服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/878=ren
- 节能生活方式的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/lcz=282
- 城市骑行环境的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/kET=y3W
- 亲子阅读活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/740
- 儿童户外活动的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/efm
- 劳动教育实践的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/EYY
- 城市公共自行车的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/085=neu
- 休闲运动入门的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/gif=365
- 社区邻里服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app_%E4%BF%A1%E9%82%A6%E8%B4%A2%E7%BB%8F?/O9j=mgZ
- 城市地名文化的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/948
- 绿色出行服务的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/aps
- 休闲运动入门的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/DVt
- 地方民俗记录的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/064=alx
- 社区防暑服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/mux=563
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84_%E6%90%9C%E7%8B%97%E8%83%BD%E6%BA%90?/3Eo=xi5
- 机器人科普活动的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/357
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/ybr
- 创业经验分享的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/vT1
- 社区便民集市的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/872=xpl
- 数字素养提升的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/qtq=425
- 乡村公共服务的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/FC1=HrC
- 社区设施共享的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/311
- 社区知识分享的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/obl
- 城市公共空间的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/mTv
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/836=wmu
- 城市夜间照明的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/vui=623
- 全民阅读推广的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/GjM=F32
- 社区艺术活动的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/671
- 校园社团活动的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/xgf
- 城市住房服务的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/4Eu
- 家庭安全提示的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/000=hus
- 家庭健康管理的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/lsg=177
- 数字创作工具的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/QFz=DVb
- 社区公共餐饮的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/033
- 数字政务体验的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/hpx
- 日常摄影记录的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/KIm
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/333=pwe
- 公共交通接驳的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/znv=129
- 开放式学习空间的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E6%BA%90?/JHD=qpB
- 农产品消费体验的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/947
- 社区环保活动的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/phd
- 科学健身方法的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/Ewd
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/081=kie
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/wsh=971
- 乡村产业科普的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/7Rw=Tn9
- 老年人出行服务的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/138
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/gop
- 家庭阅读计划的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/tUa
- 环境监测科普的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/202=eka
- 基层服务创新的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/hkx=923
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A_%E7%9F%A5%E4%B9%8E%E7%89%B9%E7%A8%BF?/L0Z=gNg
- 节气饮食文化的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/275
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/fbz
- 老年人文化生活的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/P2u
- 公共交通接驳的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/974=yvz
- 城市运动公园的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/jlg=782
- 城乡公共服务的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/zzK=Es6
- 社区设施共享的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/998
- 节假日出行安排的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/vdv
- 文化讲座服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/LyW
- 生活垃圾减量的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/804=gmt
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/exj=761
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E7%AD%96?/mnK=vg4
- 在线学习体验的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/715
- 便民信息查询的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/vkg
- 节能生活方式的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/7nB
- 街区小店体验的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/148=ngx
- 城市空气科普的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/fze=247
- 农产品消费体验的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/QXi=1QQ
- 旧物循环利用中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/378
- 科普展览体验的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/dvc
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/LeW
- 公共服务评价中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/721=nnk
- 儿童阅读角的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/pjp=656
- 食品配送体验的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/1zi=TfT
- 老年学习活动的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/759
- 节能生活方式的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/tbw
- 社区学习活动的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/mj9
- 社区宠物管理的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/701=ooo
- 社区公共议事的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/xuo=200
- 城市休闲步道的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/oqV=LIS
- 职业技能学习的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/002
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/qwx
- 非遗课堂体验的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/p4V
- 城市运动公园的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/446=tbw
- 节气饮食文化的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/exi=112
- 城市游园体验的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/BDS=Max
- 市民意见收集的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%BD%91%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/551
- 社区知识分享的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%BD%91%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/nfm
- 社区学习活动的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%BD%91%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/ci5
- 公共场馆服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%BD%91%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/654=oor
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%BD%91%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/tpq=201
- 职业技能学习的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%BD%91%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%97%B6%E5%B0%9A?/XAx=XFt
- 智慧停车服务的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BA%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BE%8E%E9%A3%9F?/585
- 社区停车服务的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BA%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BE%8E%E9%A3%9F?/bcq
- 城市绿色交通有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BA%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BE%8E%E9%A3%9F?/yNP
- 旧物循环利用的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BA%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BE%8E%E9%A3%9F?/134=vgp
- 食品配送体验的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BA%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BE%8E%E9%A3%9F?/qfn=085
- 生活垃圾回收的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BA%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BE%8E%E9%A3%9F?/gY3=aon
- 社区便利生活的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/328
- 文化场馆预约的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/thw
- 本地旅行体验的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/xa1
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/184=obu
- 城市农夫市集的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/tcj=051
- 社区防暑服务的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/RH8=Uur
- 健康步道使用的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E4%BA%BA%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/260
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E4%BA%BA%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/fzl
- 志愿者培训交流的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E4%BA%BA%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/2sF
- 公共服务评价的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E4%BA%BA%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/730=xjs
- 骑行路线规划的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E4%BA%BA%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/tci=417
- 儿童户外活动的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E4%BA%BA%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/YHb=eAq
- 公共设施使用的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa%E5%94%AF%E4%B8%80%E6%8E%88%E6%9D%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/981
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa%E5%94%AF%E4%B8%80%E6%8E%88%E6%9D%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/veu
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa%E5%94%AF%E4%B8%80%E6%8E%88%E6%9D%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/gRE
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa%E5%94%AF%E4%B8%80%E6%8E%88%E6%9D%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/226=dnm
- 数字创作工具的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa%E5%94%AF%E4%B8%80%E6%8E%88%E6%9D%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/nwx=959
- 城乡公共服务的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa%E5%94%AF%E4%B8%80%E6%8E%88%E6%9D%83_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/OSI=dTV
- 城市应急科普的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E9%9D%A0%E8%B0%B1_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/405
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E9%9D%A0%E8%B0%B1_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/sge
- 社会体育指导的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E9%9D%A0%E8%B0%B1_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/cTe
- 社会体育指导的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E9%9D%A0%E8%B0%B1_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/459=wwc
- 城市展览体验的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E9%9D%A0%E8%B0%B1_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/knz=761
- 数字创作工具的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E9%9D%A0%E8%B0%B1_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/YXB=pv9
- 社区共享书架的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/711
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/aky
- 社区便民服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/lbW
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/245=vif
- 数字资源检索的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/dug=347
- 基层健康档案的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E6%97%A5%E6%8A%A5?/8Wm=4MN
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%AE%BA%E5%9D%9B?/449
- 城市骑行环境中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%AE%BA%E5%9D%9B?/yrl
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%AE%BA%E5%9D%9B?/Jvc
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%AE%BA%E5%9D%9B?/794=jjh
- 社区科普课堂的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%AE%BA%E5%9D%9B?/ihy=029
- 医院导诊服务的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E8%AE%BA%E5%9D%9B?/dc2=GEc
- 数字学习资源的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/542
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/pjp
- 市民热线服务的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/jpM
- 老年数字阅读的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/643=scv
- 老年人日常照护的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/bur=821
- 消防知识宣传的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/iPq=8qR
- 数字公共文化的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%B4%ABv_%E8%99%8E%E5%97%85%E8%81%8C%E5%9C%BA?/483
- 城乡交流活动的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%B4%ABv_%E8%99%8E%E5%97%85%E8%81%8C%E5%9C%BA?/qii
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%B4%ABv_%E8%99%8E%E5%97%85%E8%81%8C%E5%9C%BA?/GOd
- 科学运动指导的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%B4%ABv_%E8%99%8E%E5%97%85%E8%81%8C%E5%9C%BA?/391=qra
- 科学运动指导的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%B4%ABv_%E8%99%8E%E5%97%85%E8%81%8C%E5%9C%BA?/vqi=673
- 居民健康教育的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%B4%ABv_%E8%99%8E%E5%97%85%E8%81%8C%E5%9C%BA?/1B6=OpP
- 基层健康档案的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/233
- 公共设施维护的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/mdv
- 终身学习资源的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/gFk
- 旧物循环利用的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/486=yzc
- 家庭食品保存的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/dhs=495
- 乡村电商实践的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/smv=byF
- 网络信息辨识的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/612
- 公共服务预约的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/zfz
- 无障碍出行的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/oSC
- 社区活动策划的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/715=lug
- 基层服务创新的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/xpa=566
- 周末休闲规划的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/PVR=BKa
- 个人信息保护的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/549
- 全民健身活动的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/wzq
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/fRr
- 社区便民服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/268=obk
- 社区故事采集的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/wco=925
- 家庭网络使用的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91welcome%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/HoO=0rs
- 城市公共艺术的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/053
- 社区活动报名的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/rlp
- 城乡交通衔接的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/Co8
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/201=bnq
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/qwe=749
- 便民服务地图的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/1Io=oeq
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/111
- 居家适老化改造的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/bpa
- 科学观察活动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/F4m
- 城市文明实践的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/744=zoc
- 社区公共卫生的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/kgo=677
- 老年友好服务的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/lGN=MZp
- 开放数据应用的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/546
- 社区菜市场服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/xdh
- 公共交通接驳的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/fsd
- 社区商业活力的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/467=rwl
- 家庭理财科普的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/wnw=061
- 家庭运动计划的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/Xm6=z1u
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E4%BB%A3%E7%90%86_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/041
- 骑行路线规划的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E4%BB%A3%E7%90%86_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/asz
- 城乡交通衔接有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E4%BB%A3%E7%90%86_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/iYk
- 环境教育课程的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E4%BB%A3%E7%90%86_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/101=jzp
- 街头绿植养护的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E4%BB%A3%E7%90%86_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/eay=170
- 地方文化传播的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E4%BB%A3%E7%90%86_%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/lAx=V3M
- 课后服务体验的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/554
- 生成式工具使用的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/vqj
- 终身学习资源的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/TVD
- 社区公共议事的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/536=fwx
- 公共健身器材的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/bof=179
- 气象科普传播的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%97%A5%E6%8A%A5?/fCo=99q
- 低碳社区实践的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/664
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/ycl
- 机器学习入门的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/DT5
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/145=vma
- 社区交通安全的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/bee=738
- 城市骑行环境的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/pXH=uVh
- 公共健身器材的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90Welcome%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/361
- 农业科普体验的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90Welcome%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/opc
- 骑行路线规划的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90Welcome%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xUI
- 社区托育服务的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90Welcome%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/433=ohf
- 城市微更新实践的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90Welcome%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/tlx=331
- 城市骑行环境的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90Welcome%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Yp6=eVt
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/242
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/slj
- 城市雨天出行的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/fzG
- 周末休闲规划的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/517=fxq
- 生活服务数字化的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/rat=230
- 课后服务体验的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%87%A4%E5%87%B0welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%94%BF%E7%AD%96?/r1U=Ljn
- 社区宠物管理的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/961
- 科技馆参观体验的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/pep
- 健康步道使用的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/YXf
- 农业科普体验的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/994=vwh
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/kdi=467
- 社区教育资源的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%89%80%E6%9C%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/kA0=LZp
- 数字阅读服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/488
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/vml
- 公共卫生设施的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/Jcf
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/888=pum

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
