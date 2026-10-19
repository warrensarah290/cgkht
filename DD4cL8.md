# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 社区生活指南的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/766
- 机器人科普活动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/wvl
- 家庭运动计划的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/MM4
- 远程协作工具的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/920=hfu
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/siy=031
- 数字公共文化中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%A4_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/ilc=ozG
- 社区交通安全的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/830
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/yjc
- 户外活动组织的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/5aJ
- 居家防滑改造的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/349=dci
- 社区健康讲座的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/hat=605
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%912%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/j83=yji
- 城市步行友好的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/258
- 公共空间休憩的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/xnc
- 社区手工活动的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/7UV
- 数字创作工具的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/017=isa
- 社区文化节活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/qdp=971
- 创业经验分享的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB%E5%BC%80%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/Lgj=Hjj
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/716
- 社区公共卫生的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/qye
- 乡村阅读空间的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/Ztf
- 家庭理财科普的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/811=dmb
- 社区花园共建的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/ypb=376
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/cYF=0BC
- 老年数字阅读的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/208
- 老旧小区改造的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/gkd
- 数字阅读服务的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/CTA
- 校园社团活动的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/470=hyr
- 公交站点体验的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/vys=213
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E6%8A%A5?/oSr=tnj
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/265
- 无障碍信息设计的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/ymg
- 青年就业服务的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/lD3
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/363=lvg
- 老年数字阅读的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/maj=075
- 乡村公共阅读的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pk%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/ABK=08t
- 社区慢性病防控的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/727
- 家庭理财科普的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/tjx
- 城市树木认养的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/p9N
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/501=uah
- 环境教育课程的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/fdx=989
- 社区读书角建设的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%B2%B3%E5%86%855%E5%88%86%E5%BF%85%E4%B8%AD%E4%B8%80%E6%B3%A8_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/W6j=oyZ
- 乡村阅读活动的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/638
- 居家适老化改造的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/mdy
- 校园阅读活动的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/KuR
- 节能生活方式的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/925=avv
- 农贸市场环境中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/pwy=576
- 家庭饮食安排的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E8%BF%9C%E8%88%AA%E8%B4%A2%E7%BB%8F?/nfF=PJm
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B210%E5%AE%9A%E4%BD%8D%E8%83%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/228
- 城市骑行环境的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B210%E5%AE%9A%E4%BD%8D%E8%83%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/sqn
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B210%E5%AE%9A%E4%BD%8D%E8%83%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/imH
- 课后服务体验中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B210%E5%AE%9A%E4%BD%8D%E8%83%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/656=ysu
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B210%E5%AE%9A%E4%BD%8D%E8%83%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/zxd=962
- 市民热线服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B210%E5%AE%9A%E4%BD%8D%E8%83%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/3rJ=p7n
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E9%A3%9E%E8%89%875%E7%A0%81%E8%AE%A1%E5%88%92%E8%BF%9E%E4%B8%AD10%E6%9C%9F_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/731
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E9%A3%9E%E8%89%875%E7%A0%81%E8%AE%A1%E5%88%92%E8%BF%9E%E4%B8%AD10%E6%9C%9F_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/hwx
- 家庭园艺实践的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E9%A3%9E%E8%89%875%E7%A0%81%E8%AE%A1%E5%88%92%E8%BF%9E%E4%B8%AD10%E6%9C%9F_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/txg
- 家庭运动计划的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E9%A3%9E%E8%89%875%E7%A0%81%E8%AE%A1%E5%88%92%E8%BF%9E%E4%B8%AD10%E6%9C%9F_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/086=ypo
- 公共交通信息服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E9%A3%9E%E8%89%875%E7%A0%81%E8%AE%A1%E5%88%92%E8%BF%9E%E4%B8%AD10%E6%9C%9F_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/nxs=341
- 地方民俗记录的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E9%A3%9E%E8%89%875%E7%A0%81%E8%AE%A1%E5%88%92%E8%BF%9E%E4%B8%AD10%E6%9C%9F_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/9hQ=bRP
- 社区科普课堂的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/579
- 小区电梯维护的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/cda
- 机器学习入门的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/eWF
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/290=iez
- 本地旅行体验的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/llj=112
- 老年智能设备的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/l3W=3Xv
- 街区小店体验的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%913%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/991
- 社区生活指南的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%913%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/hiv
- 家庭网络使用的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%913%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/RBh
- 社区宠物管理的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%913%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/023=mpw
- 乡村生态观察的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%913%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/uzd=055
- 课后服务体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%913%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/O4E=rAB
- 街区更新实践的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89d_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/571
- 社区信息发布中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89d_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/mui
- 城市应急科普的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89d_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/uZN
- 城市噪声观察的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89d_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/985=obt
- 生活技能分享的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89d_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/wbm=592
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89d_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/cia=pJw
- 城市公共座椅的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/152
- 绿色办公实践的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/otj
- 青年就业服务的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/aBD
- 骑行路线规划的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/235=uxt
- 家庭用电安全中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/bjw=113
- 城市社区治理的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/13Q=vit
- 儿童安全出行的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/326
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/igt
- 社区公共餐饮的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/MWP
- 青年志愿活动的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/400=jsc
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/rrd=418
- 口袋公园建设的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/8z8=XEG
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/686
- 乡村文化空间的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/rpk
- 数字素养提升的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/CVg
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/502=pfo
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/ocs=132
- 社区协商议事的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/r68=sD1
- 社区故事采集的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%9B%BE%E5%85%B0%E6%9C%B5%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/903
- 城市公共艺术的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%9B%BE%E5%85%B0%E6%9C%B5%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/xps
- 口袋公园建设的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%9B%BE%E5%85%B0%E6%9C%B5%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/yco
- 图书借阅体验的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%9B%BE%E5%85%B0%E6%9C%B5%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/120=nig
- 城市公共标识的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%9B%BE%E5%85%B0%E6%9C%B5%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/zai=080
- 社区公共卫生的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%9B%BE%E5%85%B0%E6%9C%B5%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/oJ8=EoO
- 城市农夫市集的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E9%BB%91%E9%A9%AC%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/879
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E9%BB%91%E9%A9%AC%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/hnp
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E9%BB%91%E9%A9%AC%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/jLV
- 城市空气科普的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E9%BB%91%E9%A9%AC%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/227=zxk
- 城市雨天出行的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E9%BB%91%E9%A9%AC%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/ryu=405
- 节约用水实践的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E9%BB%91%E9%A9%AC%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E9%80%9F%E8%A7%88?/nWl=Gpg
- 社区休闲设施的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/079
- 数字资源检索的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/kwj
- 校园社团活动的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/xzu
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/911=gnt
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/wfc=054
- 家庭节能实践的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%BB%91%E9%A9%AC%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/g9h=FbW
- 社区便利生活的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/529
- 社区环保活动的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/fdu
- 社区家政服务的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/ZSm
- 社区环保活动的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/341=gyj
- 青少年编程学习的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/ebe=181
- 就业技能培训的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/U8m=XzK
- 软件开发学习的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%86%E6%A2%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/481
- 公共设施维护的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%86%E6%A2%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/vfd
- 小区电梯维护的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%86%E6%A2%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/PfN
- 开源技术交流的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%86%E6%A2%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/130=zfs
- 社区科普课堂中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%86%E6%A2%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/lma=675
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%86%E6%A2%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/aN2=G14
- 公共卫生宣传的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/512
- 公共交通接驳的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/rvg
- 社区庭院绿化的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/yj3
- 健康步道使用的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/262=ryy
- 软件开发学习的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/ivk=690
- 城市应急广播的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/LCH=ppQ
- 生成式工具使用的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/801
- 社区安全巡查的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/zag
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/wx9
- 儿童阅读角的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/614=rsj
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/ows=982
- 社区垃圾回收的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AF%84?/Y7d=jw2
- 儿童友好空间的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/686
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/eax
- 急救知识普及中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/l27
- 家庭安全提示的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/427=zem
- 社区休闲设施的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qei=809
- 数字公共文化的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dcV=7UX
- 数字地图应用的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/110
- 城市雨天出行的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/aoz
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/FVZ
- 社区文化节活动的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/559=jrn
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/koh=481
- 智慧城市体验的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/nku=yCC
- 城市休闲步道的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/880
- 社区菜市场服务的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/mhp
- 节能家电使用的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/cHZ
- 青年志愿活动的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/773=nwx
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/brt=846
- 城市博物馆服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/HjE=hIq
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9C%8913%E6%9C%9F%E5%87%BA%E4%B8%80%E6%A0%B7%E7%9A%84%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/520
- 便民服务窗口的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9C%8913%E6%9C%9F%E5%87%BA%E4%B8%80%E6%A0%B7%E7%9A%84%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/hvw
- 社区垃圾分类的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9C%8913%E6%9C%9F%E5%87%BA%E4%B8%80%E6%A0%B7%E7%9A%84%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/BWw
- 儿童阅读角的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9C%8913%E6%9C%9F%E5%87%BA%E4%B8%80%E6%A0%B7%E7%9A%84%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/879=mjr
- 家庭健康科普的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9C%8913%E6%9C%9F%E5%87%BA%E4%B8%80%E6%A0%B7%E7%9A%84%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/bev=024
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9C%8913%E6%9C%9F%E5%87%BA%E4%B8%80%E6%A0%B7%E7%9A%84%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/lBs=Sld
- 电动汽车充电的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E5%92%8C%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/605
- 校园阅读活动的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E5%92%8C%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/hgy
- 线上办事服务的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E5%92%8C%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/K50
- 休闲运动入门的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E5%92%8C%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/933=wol
- 家庭环保行动的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E5%92%8C%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/puy=909
- 社区科普课堂的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7%E5%92%8C%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/5BU=WG2
- 城市文明出行的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/036
- 青少年心理健康的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/jsk
- 小区电梯维护的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/Fga
- 社区快递服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/410=pgc
- 数字生活课堂的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/juh=518
- 公共健身器材的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/UOO=iPQ
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/482
- 城市建设科普的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/cjh
- 家庭健康科普的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/glD
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/649=ttr
- 青少年户外教育的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/hmh=024
- 开放数据应用的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/WNH=ruD
- 公共服务沟通的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/847
- 老旧小区改造的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/idz
- 日常摄影记录的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/gO0
- 社区防暑服务的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/464=dgx
- 城市公共座椅中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/irm=000
- 老年人出行服务的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/Zjm=BLK
- 公共服务评价中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/610
- 城市水环境观察的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/xxe
- 周末休闲规划的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/QzX
- 智慧城市体验的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/246=dfg
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/evh=734
- 数字公共文化的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/2nN=oQp
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/010
- 休闲运动入门的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/uvk
- 青少年科普实践的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/MS1
- 城市慢行系统的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/718=xsi
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/nkb=192
- 城市建设科普的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/b43=310
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81qq%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/831
- 生活垃圾减量的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81qq%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/yhd
- 数字创意课程的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81qq%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/wUN
- 绿色办公实践的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81qq%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/600=ltm
- 生活技能分享的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81qq%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/uaq=539
- 公共交通接驳的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81qq%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/bNF=0Yp
- 智能家居应用中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/500
- 农业科普体验的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/qza
- 节约用水实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/MyS
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/128=iyx
- 绿色消费选择的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/qse=683
- 家庭用电安全的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/N6n=Ie2
- 街区小店体验的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/544
- 社区老年食堂的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/yzl
- 社区宠物管理的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/nwX
- 社区儿童活动的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/958=iag
- 个人数据管理的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/wbd=767
- 城市展览体验的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/0PS=KOk
- 基层健康服务的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/349
- 环境教育课程的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/ijz
- 数字档案服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/9wv
- 城市空气科普的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/743=zcn
- 社区知识分享的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/odh=383
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/412=9QM
- 城市社区治理的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/355
- 城市休闲步道的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/crl
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/H1g
- 小微企业服务的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/619=rhw
- 数字创作工具的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/ivu=760
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/C7U=30X
- 校园社团活动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%AD%A3%E8%A7%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/331
- 城市生活记录的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%AD%A3%E8%A7%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/ufg
- 市民热线服务的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%AD%A3%E8%A7%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/DdZ
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%AD%A3%E8%A7%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/417=rvu
- 老年人文化生活的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%AD%A3%E8%A7%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/izp=439
- 邻里共享空间的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%AD%A3%E8%A7%84_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/MZ6=jXM
- 青少年户外教育的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/855
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/zfw
- 公共健身器材的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/aHq
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/219=oce
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/gnc=915
- 数字设备回收的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/g6J=qup
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%AE%A1%E6%95%B0%E5%B8%AE%E5%B8%AE%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/791
- 人工智能科普的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%AE%A1%E6%95%B0%E5%B8%AE%E5%B8%AE%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/xus
- 环境监测科普的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%AE%A1%E6%95%B0%E5%B8%AE%E5%B8%AE%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/EbF
- 地方旅游导览的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%AE%A1%E6%95%B0%E5%B8%AE%E5%B8%AE%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/490=zir
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%AE%A1%E6%95%B0%E5%B8%AE%E5%B8%AE%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/tft=054
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%AE%A1%E6%95%B0%E5%B8%AE%E5%B8%AE%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/jHH=fQn
- 街区小店体验的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%B6%88%E8%B4%B9?/338
- 环境监测科普的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%B6%88%E8%B4%B9?/qul
- 社区活动空间的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%B6%88%E8%B4%B9?/0Ha
- 街区更新实践的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%B6%88%E8%B4%B9?/569=hpn

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
