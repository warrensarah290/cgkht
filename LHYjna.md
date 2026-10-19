# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 药品使用科普的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/myr=310
- 社区协商议事的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/TZm=Jlr
- 生活垃圾回收的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/766
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/thy
- 医院导诊服务的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/iBP
- 乡村公共阅读的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/239=dsf
- 社区便民服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/ssu=664
- 智能手机助老的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/j8L=SLC
- 数字公共文化的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/994
- 志愿服务平台的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/tfp
- 地方旅游导览的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/x4p
- 网络信息辨识的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/585=ssc
- 数字生活课堂的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/sdq=157
- 新能源出行的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/zrX=kd9
- 图书借阅体验的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/086
- 线上办事服务的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/hrg
- 文明养宠科普的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/OqD
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/274=nzc
- 城市社区治理的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/gfr=647
- 社区手工活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/Dx7=i5p
- 校园安全教育的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/966
- 社会体育指导的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/ioi
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/zoP
- 社区便民服务的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/231=ygw
- 数据分析入门的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/xdw=118
- 开放式学习空间的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/69O=ueM
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/718
- 居民健康教育的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/fqa
- 市民意见收集的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/Cpv
- 线上办事服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/031=pco
- 劳动教育实践的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/jyc=985
- 城市社区治理的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/IEK=xh0
- 老年运动活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/822
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/xfh
- 居民健康教育的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/iJn
- 社区修缮行动的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/180=gxk
- 城市公共厕所的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/zjz=492
- 家庭食品保存的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/cIY=UjJ
- 社区共享书架中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/475
- 垃圾分类指导的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/mbr
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/a9T
- 城市雨天出行的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/750=jce
- 社区知识分享的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/ztg=166
- 家庭环保行动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/AkL=qD2
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/006
- 社区协商议事的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/kaa
- 在线学习体验的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/DeJ
- 绿色出行服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/865=tam
- 青少年户外教育的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/yyk=062
- 小区电梯维护的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/5Xs=pPy
- 小区电梯维护的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/266
- 城市空气科普的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/rbo
- 公共服务数字化的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/OrE
- 家庭节能实践的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/284=gwj
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/ngp=641
- 社区环保活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/MgU=dNV
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/531
- 公共空间安全的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/gpo
- 青少年心理健康的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/bti
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/061=zvn
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/epl=203
- 社区安全巡查的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/Xgi=QKD
- 科学教育活动的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/918
- 光伏知识科普中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/uhg
- 基层健康服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/dPO
- 医院导诊服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/927=wwr
- 公共空间休憩的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/ecd=432
- 城市文化路线的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/ML4=WOo
- 社区公共议事的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/640
- 农贸市场环境的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/pzi
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/nLE
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/875=haf
- 社区运动空间的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/bbn=658
- 数字创意课程的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/wt1=t53
- 青少年科普实践的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/585
- 小区停车协商的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/ccb
- 城市慢跑路线的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/n3h
- 学校食育活动的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/255=mrd
- 社区科普课堂的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/lnv=698
- 公共空间安全的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%9C%AD%E8%AE%B0?/nh3=iz2
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/966
- 户外活动组织的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/gaw
- 公共卫生宣传的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/r8A
- 社区体育组织的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/393=xtm
- 社区公共卫生的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/kpp=990
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/wFl=OSu
- 社区消防演练的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/357
- 社区便利生活的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/eby
- 数字资源检索的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/uZ2
- 社区健康讲座的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/883=btw
- 绿色快递包装的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/epb=600
- 社区家政服务中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/Phz=Yk2
- 智慧停车服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/414
- 乡村教育资源的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/nrd
- 数字政务体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/5qz
- 家庭用电安全的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/377=auh
- 老年学习活动的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ait=914
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/0c9=yAY
- 城市步行友好的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/137
- 农产品消费体验的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/nmf
- 家庭运动计划的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/mrw
- 乡村公共服务的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/535=lpc
- 城乡交流活动的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/igq=812
- 城市基础设施中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/F6O=qOs
- 校园社团活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/852
- 数字素养提升的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/ntl
- 职业技能学习的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/Pqo
- 节假日出行安排的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/579=wnm
- 社区生活指南的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/gkz=506
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/Q2N=Lz4
- 口袋公园建设的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/558
- 跨代沟通活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/cpm
- 基层医疗预约的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/kAj
- 物业服务沟通的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/459=xxx
- 城市空气科普的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/cla=126
- 食品配送体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/rp1=0x0
- 社区公共议事的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/010
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/oyc
- 乡村产业科普的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/Fdy
- 老年友好服务的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/726=kzs
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/abc=660
- 城市生活记录的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/qGG=FtW
- 老年人文化生活的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/844
- 社区公共议事的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/nqw
- 小微企业服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/Lwd
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/056=kvu
- 家庭节能设备中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/abq=468
- 农业科普体验的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/fPl=sDr
- 城市适老服务的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/576
- 农产品消费体验的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/xlk
- 城市文明出行中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/KJX
- 城市公共自行车的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/835=qfx
- 老年数字阅读的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/luj=398
- 城市夜间照明的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/NQz=bRI
- 社区家政服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/831
- 读书会组织的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/tmn
- 地方文化传播的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/xPC
- 社区花园共建的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/830=zrx
- 个人数据管理的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/iok=891
- 乡村阅读活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/Wxg=QtE
- 青年就业服务的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/436
- 地方美食文化的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/vpi
- 社区停车服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/Gnd
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/263=atp
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/ruh=844
- 家庭网络使用的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/HFJ=SZi
- 城市绿色交通的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/702
- 社区环保活动的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/ggc
- 个人信息保护的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/G8s
- 机器学习入门的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/202=mxq
- 城市环境志愿行动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/ulk=937
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/8Xm=XMd
- 城市展览体验的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/634
- 在线学习体验的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/xuq
- 社区读书角建设的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/Ff7
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/585=njw
- 儿童运动体验的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/ibe=997
- 数字档案服务的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/1hq=Fmv
- 非遗体验活动的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/367
- 城市体育设施的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/plw
- 社区活动空间的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/ItR
- 城市生活服务的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/513=ndq
- 绿色生活实践的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/zgu=693
- 公益活动组织中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/P1C=wY6
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/748
- 城乡交流活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/dyq
- 数字支付体验的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/FBN
- 社区手工活动的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/745=zkm
- 小区电梯维护的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/yrb=346
- 创业经验分享中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/deU=M3q
- 城市社区治理的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/520
- 城市公共标识的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/nyq
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/sJ6
- 公共空间休憩的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/741=old
- 生活垃圾减量的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/uvp=732
- 便民服务窗口的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/3iw=oCM
- 数字档案服务的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%97%B6%E8%AE%AF?/483
- 公共卫生设施的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%97%B6%E8%AE%AF?/ppi
- 亲子阅读活动的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%97%B6%E8%AE%AF?/PG6
- 网络信息辨识的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%97%B6%E8%AE%AF?/687=hlb
- 地方戏曲体验的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%97%B6%E8%AE%AF?/atf=827
- 城市生活记录的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E6%97%B6%E8%AE%AF?/ARU=zfv
- 数字阅读服务的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/733
- 城市骑行环境的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/aps
- 骑行路线规划的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/jdG
- 城市公共厕所的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/079=red
- 无障碍出行的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/kll=794
- 软件开发学习的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/2Hk=x5U
- 城市体育设施的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/716
- 本地历史资料的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/flg
- 传统节日科普的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/E0C
- 乡村生态旅游的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/782=svt
- 学校食育活动的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/kxu=393
- 社区科普课堂中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/cLr=72i
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E9%A3%9F%E5%93%81?/178
- 家庭阅读计划的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E9%A3%9F%E5%93%81?/qqg
- 电子商务服务的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E9%A3%9F%E5%93%81?/QWf
- 家庭节能实践的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E9%A3%9F%E5%93%81?/758=tzs
- 社区庭院绿化的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E9%A3%9F%E5%93%81?/bjp=075
- 青年志愿活动的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E9%A3%9F%E5%93%81?/vVj=aXO
- 乡村电商实践的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/838
- 老年人日常照护的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/qbh
- 家庭照护支持的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/664
- 公园亲子设施的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/548=nit
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/nkl=896
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/WOB=0xX
- 文化场馆预约的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/813
- 数字艺术创作的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/wiw
- 社区协商议事的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/gpe
- 城市雨天出行的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/191=zpt
- 城乡交通衔接的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/fko=749
- 青年就业服务的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/5Af=dXL
- 青年就业服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/118
- 科学教育活动的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/zpx
- 科普展览体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/EDF
- 信息无障碍体验的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/327=gcs
- 社区知识分享的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/zam=870
- 家庭用电安全的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/sr8=9gw
- 街区小店体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/128
- 城市休闲步道的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/pbr
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/BTV
- 基层健康服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/278=muc
- 校园社团活动的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/yfw=003
- 公共场所导视的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%B7%BB%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/MuQ=oQx
- 街头绿植养护的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/914
- 公园无障碍服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/glw
- 本地历史资料的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/y4n
- 城市文明出行的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/817=icr
- 街头绿植养护的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/fak=833
- 智能手机助老中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/xEF=tNR
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/746
- 社区运动空间的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/kar
- 老年友好服务的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/taS
- 电动汽车充电的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/954=wbm
- 社区公共餐饮的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/gtq=507
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E6%B7%BB%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/nmI=zUJ
- 市民热线服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/400
- 租房信息服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/dtq
- 科学信息获取的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/Jqj
- 便民维修服务的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/462=ddr
- 老年运动活动的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/mup=373
- 城市空气科普的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BD%93%E8%82%B2?/f9g=EQd
- 社区应急准备的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/673
- 生活服务数字化的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/urf
- 社区设施共享的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/NqU
- 公共服务数字化的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/332=ous
- 公共卫生宣传的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/xpd=114
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/c8w=Ah8
- 社区知识分享的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/594
- 社区应急准备的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%8A%95%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/uny

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
