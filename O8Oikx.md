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

- 城市夜间照明的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/lep=676
- 物业服务沟通的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/tfO=AZq
- 数字创意课程的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/202
- 垃圾分类指导的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/thf
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/84L
- 乡村电商实践的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/674=son
- 社区心理支持的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/yoj=127
- 开放数据应用的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E5%AE%98%E7%BD%91%E5%BC%80%E7%9A%84%E5%90%97_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/YPf=rkk
- 城市文化路线的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_36%E6%B0%AA%E5%9B%BD%E9%99%85?/514
- 城市建设科普的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_36%E6%B0%AA%E5%9B%BD%E9%99%85?/pcj
- 城市社区治理的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_36%E6%B0%AA%E5%9B%BD%E9%99%85?/soP
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_36%E6%B0%AA%E5%9B%BD%E9%99%85?/757=txa
- 老年学习活动的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_36%E6%B0%AA%E5%9B%BD%E9%99%85?/mbl=287
- 个人时间管理的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6app_36%E6%B0%AA%E5%9B%BD%E9%99%85?/n85=4py
- 节日文化体验的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/661
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/evg
- 社区垃圾回收的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/7Xm
- 新能源出行的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/804=woe
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/tcl=816
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E8%B5%9B%E8%BD%A6%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB?/Oon=KTT
- 绿色生活实践的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/149
- 骑行路线规划的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/ymf
- 便民服务地图的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/UXs
- 儿童友好街区的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/827=xqj
- 数字公共文化的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/mxy=982
- 校园社团活动的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E9%AB%98%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/co3=LT3
- 消防知识宣传的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/874
- 社区生活指南的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/cfx
- 医院导诊服务的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/2Ue
- 街区绿化养护的基础知识问答 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/704=reo
- 社区教育资源的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/vhw=758
- 农村环境治理的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B0%91%E7%94%9F?/VDY=3x9
- 社区艺术活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/219
- 节能家电使用的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/jsz
- 城市公共厕所的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/tjT
- 家庭网络使用的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/557=fji
- 公共空间休憩的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/cul=829
- 绿色校园实践的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%AB%98%E7%BA%A7%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E7%BA%AA%E5%AE%9E?/A2Y=JgE
- 校园安全教育的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/310
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/swm
- 数字生活课堂的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/Ccb
- 环境监测科普的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/001=vku
- 社区学习活动的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/fgo=308
- 家庭收纳实践的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/c9z=Xda
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/976
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/rgx
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/8vq
- 城市住房服务的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/335=gtp
- 城市共享单车的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/eel=474
- 家庭照护支持的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%95%99%E6%8E%88_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/5HH=DxW
- 开放式学习空间的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/393
- 生活技能分享的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/ynx
- 农业科普体验的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/dM6
- 数字阅读服务的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/199=ukd
- 城市农夫市集的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/aau=463
- 家庭园艺实践的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_pk%E6%8B%BE%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/woT=kBZ
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/975
- 城市便民驿站的实际需求与回应 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/zrx
- 电子商务服务的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/aau
- 公共服务预约的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/949=lrv
- 社区庭院绿化的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/zcw=515
- 城市文明实践的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_PK%E6%8B%BE%E5%89%8D%E4%BA%8C%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/iUS=JRm
- 社区家政服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/971
- 城市文化路线的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/xwh
- 老年智能设备的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/bK4
- 儿童户外活动的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/889=zzc
- 市民意见收集的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/apj=611
- 个人时间管理中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_PK0%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/mq8=DCL
- 社会体育指导的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/290
- 健康步道使用的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/zar
- 社区快递服务中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/pKW
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/260=vgt
- 物业服务沟通的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/lkr=615
- 家庭急救准备的活动组织技巧 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/zJo=ScW
- 社区公共卫生的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/954
- 个人时间管理的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/qvb
- 农村环境治理的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/ydR
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/205=ypm
- 低碳社区实践的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/ipd=571
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9C%80%E7%A8%B3%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/p5i=ByQ
- 创业经验分享的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/022
- 灵活就业交流的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/vvc
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/rfQ
- 通勤路线规划的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/151=zhw
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/rlp=526
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%B8%93%E4%B8%9A%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/b7C=k8x
- 光伏知识科普的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3?/297
- 社区设施共享的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3?/jcl
- 气象科普传播的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3?/QQP
- 网络信息辨识的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3?/822=kug
- 乡村产业科普的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3?/vnn=633
- 社区文化节活动的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9C%80%E7%B2%BE%E5%87%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3?/3GY=xWK
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%99%8E%E5%97%85?/032
- 城市人文观察的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%99%8E%E5%97%85?/aol
- 亲子科普活动的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%99%8E%E5%97%85?/g8j
- 城市公共空间的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%99%8E%E5%97%85?/450=htw
- 科学观察活动的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%99%8E%E5%97%85?/yqk=086
- 社区学习活动的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%99%8E%E5%97%85?/9yT=IEN
- 街头绿植养护的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/707
- 灵活就业交流的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/yoq
- 科普展览体验的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/rTo
- 生活垃圾减量中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/424=bks
- 城市公共厕所的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/czh=550
- 地方文化传播的使用门槛与改进 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E7%BE%A4_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/rcN=XJj
- 家庭科学教育的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/876
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/bpm
- 社区志愿服务的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/Bfk
- 社区健康讲座的日常管理方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/530=qix
- 社区信息发布的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/duf=934
- 青少年心理健康的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/T1U=QVa
- 社区家校合作的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/618
- 无障碍出行的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/vde
- 社区运动空间中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/4eI
- 社区科普课堂的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/287=dww
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zro=926
- 家庭健康科普的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/4nN=n09
- 社区健康讲座的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/713
- 乡村生活观察的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/qwd
- 城市适老服务的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/L0b
- 家庭网络使用的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/086=yde
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/zns=640
- 社区修缮行动的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%B0%8F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/qf0=uAT
- 农村环境治理的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/734
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ytj
- 社区法律科普的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/QTB
- 生成式工具使用的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/158=xyf
- 读书会组织的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gcg=292
- 公园休闲体验的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E6%89%BE%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%B0%81%E6%9C%89_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/2cU=0fi
- 公园无障碍服务的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8D%9A%E5%AE%A2?/860
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8D%9A%E5%AE%A2?/gib
- 节约用水实践的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8D%9A%E5%AE%A2?/DKe
- 老年数字阅读的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8D%9A%E5%AE%A2?/093=bzd
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8D%9A%E5%AE%A2?/spr=109
- 小微企业服务的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%BE%E5%AE%9E%E5%8A%9B%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%8D%9A%E5%AE%A2?/hPZ=vNN
- 城乡交流活动的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/054
- 基层健康档案的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/iow
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/WSk
- 节假日出行安排的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/030=oan
- 无障碍信息设计的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/rzb=383
- 城市地名文化的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AF%9A%E4%BF%A1%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/5Ke=XDK
- 社区邻里服务的行动步骤参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/297
- 智能家居应用的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/wdn
- 城市基础设施的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/3v3
- 本地旅行体验的绿色实践方法 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/893=lfr
- 公共场所导视的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/oku=272
- 日常摄影记录中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%A8%8E%E5%8A%A1?/2JG=dWS
- 在线教育体验的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/895
- 乡村阅读空间的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/cdd
- 社区庭院绿化的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/5zq
- 新能源出行的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/844=bgw
- 街道综合服务的便民做法梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/kmk=873
- 城市应急广播的长期维护要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/Prc=j2k
- 创业经验分享的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%8F%8D%E6%B0%B4%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/172
- 数字素养提升中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%8F%8D%E6%B0%B4%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/nsv
- 绿色建筑理念的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%8F%8D%E6%B0%B4%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/IZY
- 社区志愿服务的持续改进方向 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%8F%8D%E6%B0%B4%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/702=ucl
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%8F%8D%E6%B0%B4%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/cwm=314
- 智慧停车服务的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%8F%8D%E6%B0%B4%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/Bov=XvG
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%A4%A7%E7%BE%A4_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/207
- 绿色校园实践的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%A4%A7%E7%BE%A4_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/ziq
- 社区运动空间的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%A4%A7%E7%BE%A4_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/QIT
- 乡村文化空间的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%A4%A7%E7%BE%A4_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/226=pqo
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%A4%A7%E7%BE%A4_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/xup=026
- 城市可持续生活的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%A4%A7%E7%BE%A4_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/Wz3=2WP
- 社区生活指南的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E7%BE%A4%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/888
- 科学运动指导的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E7%BE%A4%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/ote
- 社区文化节活动中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E7%BE%A4%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/3uw
- 无障碍出行的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E7%BE%A4%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/015=agj
- 城市地名文化的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E7%BE%A4%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/oud=958
- 公共设施使用的常见误区提醒 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E7%BE%A4%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/lHc=YqW
- 就业技能培训的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8D%E6%94%B9%E5%A5%96_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/328
- 日常摄影记录的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8D%E6%94%B9%E5%A5%96_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/dbx
- 城市文化路线的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8D%E6%94%B9%E5%A5%96_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/w05
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8D%E6%94%B9%E5%A5%96_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/706=wtw
- 创业经验分享的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8D%E6%94%B9%E5%A5%96_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/lcg=380
- 家庭养老规划的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8D%E6%94%B9%E5%A5%96_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/PtR=6Ba
- 志愿者培训交流的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/852
- 读书会组织的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/kbi
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/oRG
- 文明养宠科普的协商参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/280=eux
- 公共场所导视的服务细节记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/fpp=816
- 公共服务预约的协作机制梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/Cck=G5G
- 街道综合服务的公共参与指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_360%E6%A1%A3%E6%A1%88?/915
- 儿童户外活动的资源整合思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_360%E6%A1%A3%E6%A1%88?/xnm
- 邻里共享空间的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_360%E6%A1%A3%E6%A1%88?/PWp
- 家庭健康科普的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_360%E6%A1%A3%E6%A1%88?/493=jdi
- 乡村文化空间的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_360%E6%A1%A3%E6%A1%88?/qsy=045
- 社区快递服务的空间设计要点 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_360%E6%A1%A3%E6%A1%88?/aLd=bgs
- 社区菜市场服务的资源利用方法 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%8F%AF%E9%9D%A0%E7%BE%A4_360%E8%AF%BB%E6%8A%A5?/459
- 城市步行友好中的几个关键细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%8F%AF%E9%9D%A0%E7%BE%A4_360%E8%AF%BB%E6%8A%A5?/efg
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%8F%AF%E9%9D%A0%E7%BE%A4_360%E8%AF%BB%E6%8A%A5?/Yjk
- 城市住房服务的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%8F%AF%E9%9D%A0%E7%BE%A4_360%E8%AF%BB%E6%8A%A5?/148=ifx
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%8F%AF%E9%9D%A0%E7%BE%A4_360%E8%AF%BB%E6%8A%A5?/nit=989
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%8F%AF%E9%9D%A0%E7%BE%A4_360%E8%AF%BB%E6%8A%A5?/wlL=VQP
- 社区教育资源的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/372
- 老年人文化生活的安全使用提示 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/agt
- 学校食育活动的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/qhS
- 青年职业探索的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/151=nft
- 城市慢行系统的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/eis=539
- 节能家电使用的组织方法与经验 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E7%8E%A9_%E6%BE%8E%E6%B9%83%E7%9E%AD%E6%9C%9B?/ksv=03I
- 城市文明出行的日常使用指南 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/531
- 农贸市场环境的线下体验记录 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/ull
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/ucU
- 智能家居应用的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/947=guv
- 城市生活记录的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/fuj=544
- 新能源出行的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%93%AA%E9%87%8C%E6%9C%89_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/uOJ=dQk
- 家庭用电安全的家庭实践清单 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%9A%84%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/851
- 城市步行友好的服务反馈渠道 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%9A%84%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/oge
- 公园休闲体验的适老服务细节 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%9A%84%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/7pJ
- 便民服务窗口的日常记录与分享 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%9A%84%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/551=rgj
- 药品使用科普的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%9A%84%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/ghd=596
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%9A%84%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/77r=LzJ
- 城市公共座椅的居民参与机会 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E8%80%81%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/133
- 学校食育活动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E8%80%81%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/bbf
- 乡村公共服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E8%80%81%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/AS0
- 便民服务窗口的活动体验回顾 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E8%80%81%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/649=gld
- 开放式学习空间的社区行动案例 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E8%80%81%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/oxj=802
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E8%80%81%E7%BE%A4_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/oHA=yE3
- 环境教育课程的执行流程参考 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%8C%97_%E8%8A%92%E6%9E%9C%E6%B6%88%E8%B4%B9?/307
- 社区健康讲座的学习资源整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%8C%97_%E8%8A%92%E6%9E%9C%E6%B6%88%E8%B4%B9?/jnp
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%8C%97_%E8%8A%92%E6%9E%9C%E6%B6%88%E8%B4%B9?/bIZ
- 绿色校园实践的线上线下服务衔接 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%8C%97_%E8%8A%92%E6%9E%9C%E6%B6%88%E8%B4%B9?/307=hgz
- 小区电梯维护的便捷程度观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%8C%97_%E8%8A%92%E6%9E%9C%E6%B6%88%E8%B4%B9?/deo=038
- 青少年心理健康的参与方式与路径 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%8C%97_%E8%8A%92%E6%9E%9C%E6%B6%88%E8%B4%B9?/tgD=IJL
- 本地消费场景的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E8%80%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/379
- 安全出行教育的空间使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E8%80%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/eef
- 节气饮食文化的服务质量观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E8%80%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/43Z
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E8%80%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/587=jxa
- 家庭用电安全的入门知识整理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E8%80%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/bxb=115
- 城市雨天出行的活动策划思路 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E8%80%81%E7%BE%A4_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/9N4=kdr
- 乡村生态观察的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/964
- 数字艺术创作的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/cyq
- 骑行路线规划的流程优化思路 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/60i
- 社区安全巡查的设施维护观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/403=akt
- 科学信息获取的服务信息整理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/rfd=262
- 新能源出行的社区参与观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A6%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/0km=Eaq
- 社区花园共建的数字工具使用体验 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81%E6%9C%89%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/778
- 社区阅读服务的数字化应用观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81%E6%9C%89%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/wpz
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81%E6%9C%89%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/TWL
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81%E6%9C%89%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/514=htl
- 校园节能行动的基础设施观察 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81%E6%9C%89%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/bbr=187
- 公共服务咨询的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81%E6%9C%89%E7%BE%A4_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/NvZ=5Zg
- 数字学习资源的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/128
- 社区快递服务的服务范围梳理 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/tlx
- 社区艺术活动的便利性观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/CfZ
- 数字便民地图的实用信息清单 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/668=fen
- 城市夜间照明的日常实践笔记 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/xbn=819
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%9C%89%E6%B2%A1%E6%9C%89%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/k7Y=mIh
- 公共场所导视的服务体验观察 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%B1%9F%E8%8B%8F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BE%A4_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/745
- 校园节能行动的家庭参与方式 |来源：https://github.com/francispatricia463/gmli/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%B1%9F%E8%8B%8F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BE%A4_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/hhl

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
