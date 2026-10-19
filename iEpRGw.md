# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 城市公共标识的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%9F%BA%E9%87%91?/rre=017
- 儿童安全出行的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%9F%BA%E9%87%91?/rLt=Hxk
- 数字资源检索的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/463
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/sny
- 绿色办公实践的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/KYA
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/967=xxm
- 城市夜间照明的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/hbj=495
- 老年人日常照护的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/tmW=cmq
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/579
- 城市树木认养的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/uuo
- 社区托育服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/R5n
- 全民阅读推广的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/570=nka
- 绿色消费选择的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/nrj=936
- 城市便民驿站的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/j7K=UsI
- 机器学习入门的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/964
- 绿色办公实践的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/hns
- 口袋公园建设的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/Hbf
- 社区法律科普的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/389=spu
- 家庭环保行动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/vzf=532
- 社区家校合作中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/X88=KPu
- 智能家居应用的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/033
- 生活垃圾回收的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/obz
- 公共健身器材的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/A9H
- 环境教育课程的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/160=tlo
- 社区设施共享的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/rvd=955
- 节能生活方式的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E6%B8%B8%E6%88%8F?/Iz7=6rV
- 社区科普课堂的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/884
- 便民服务窗口的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/aes
- 日常摄影记录的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/qGL
- 生活服务数字化的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/515=ywj
- 物业服务沟通的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/apc=573
- 消防知识宣传的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E8%AF%84%E8%AE%BA?/U3M=51c
- 数字创意课程中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/254
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/atw
- 社区环保活动的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/1Q9
- 课后服务体验中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/644=zyc
- 社区手工活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/zon=633
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%94%90%E8%AF%84?/mea=6Ai
- 家庭环保习惯的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/192
- 数字政务体验的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/lec
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/MEm
- 科学运动指导的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/312=kgx
- 社区阅读服务的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/fdg=289
- 公益活动组织的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%97%B6%E6%8A%A5?/tmj=e2L
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/264
- 街区更新实践的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/ydz
- 数据分析入门的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/l03
- 网络安全教育的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/038=twd
- 健康步道使用的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/zky=031
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/xcX=v7y
- 邻里互助活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/325
- 乡村公共文化的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/acw
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/cAr
- 读书会组织的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/844=xqf
- 城市文明出行的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/bha=224
- 社区文化节活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/ETw=kaZ
- 便民服务窗口的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/986
- 智能手机助老的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/izr
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/9Kf
- 数字支付体验的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/218=yxn
- 文化讲座服务的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/fxm=232
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/MvE=vxr
- 城市公共自行车的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/062
- 城市微更新实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/pet
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/0bG
- 公共服务数字化的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/030=wnn
- 家庭饮食安排的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/ifa=825
- 数字学习资源的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%91%E6%8A%80?/nGw=RAg
- 市民热线服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/079
- 社区托育服务的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/gle
- 城市适老服务的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/xDQ
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/381=ayv
- 社区应急准备的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/qux=178
- 乡村文化空间的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/L7c=vs5
- 社区停车服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/851
- 城市运动公园的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/cpq
- 软件开发学习的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/sok
- 公园无障碍服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/176=ifr
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/fsa=598
- 公共服务沟通的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%9C%E8%AF%BB%E8%B4%A2%E7%BB%8F?/55t=IED
- 急救知识普及的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/005
- 家庭理财科普的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/djg
- 公共服务预约的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/6XO
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/747=erw
- 校园安全教育的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/xan=407
- 志愿者培训交流的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/U8E=KpC
- 青少年心理健康的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%BE%E9%9B%86?/382
- 公共服务沟通的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%BE%E9%9B%86?/quw
- 社区家政服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%BE%E9%9B%86?/Z7c
- 乡村公共文化中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%BE%E9%9B%86?/545=rtt
- 社区便民集市的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%BE%E9%9B%86?/sfz=896
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E5%9B%BE%E9%9B%86?/E2W=7qg
- 城市住房服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/767
- 社区绿色空间从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/fyx
- 公共服务咨询的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/u8a
- 市民意见收集的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/979=mzv
- 社区读书角建设的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/gbb=669
- 租房信息服务的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/FAR=QNl
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/530
- 地方戏曲体验的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/rez
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/GYh
- 文化遗产保护科普的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/593=wiw
- 无障碍信息设计的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/zvy=891
- 非遗体验活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9C%E4%B8%9A?/bGb=OGP
- 数字公共文化的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/849
- 城市步行环境的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/jpg
- 旧物循环利用的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/OXX
- 智能家居应用的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/326=cgv
- 数字创意课程的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/xkb=884
- 安全出行教育的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/yLF=4H4
- 便民服务窗口的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/301
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/mgb
- 社区知识分享的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/fSz
- 生成式工具使用的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/362=xrd
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/aoa=954
- 通勤路线规划的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/SKE=DYb
- 儿童运动体验的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/975
- 城市基础设施的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/vpm
- 公共交通接驳的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/VHu
- 公共设施维护的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/804=vwg
- 家庭环保行动的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/ocf=327
- 公共服务数字化中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/35j=X8i
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/829
- 应急物资管理的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/dax
- 社区环保活动的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/3CO
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/619=ure
- 社区垃圾回收的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/auk=684
- 开放数据应用的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/DJl=k0E
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/768
- 本地旅行体验的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/ywk
- 公共空间休憩的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/lzq
- 城市文明出行的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/510=myo
- 乡村文化空间的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/qfy=741
- 日常摄影记录的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/fGt=GSu
- 网络信息辨识的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/257
- 家庭节能设备的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/ukr
- 校园阅读活动的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/G7r
- 数字课堂应用的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/011=mri
- 校园节能行动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/kov=990
- 数字便民地图的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/dSj=z8W
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/539
- 街区道路维护的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/bry
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gBi
- 乡村生态观察的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/120=yqa
- 社区学习活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hul=817
- 健康步道使用的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/IjP=17X
- 社区商业活力的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/812
- 社区共享书架的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/bef
- 生活垃圾减量的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/o7U
- 安全出行教育的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/336=pur
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/lec=776
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/nOW=gZE
- 图书借阅体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/567
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/ijh
- 城市适老服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/4gA
- 环境教育课程的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/231=cdo
- 城市应急科普的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/lws=512
- 社区便民集市的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%B9%A6%E7%94%BB?/UVZ=VHd
- 乡村文化活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/844
- 周末休闲规划的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/jyq
- 健康饮水科普的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/zr0
- 社区法律科普的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/760=lfc
- 数字公共文化的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/nrp=084
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/nUd=4AF
- 居家防滑改造的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/594
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/qgn
- 城乡交通衔接的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/Imo
- 公园亲子设施的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/218=uge
- 节能生活方式的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/khe=317
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/Jbl=Yqr
- 智慧停车服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/619
- 城市骑行环境的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/pqc
- 公共服务评价的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/shc
- 租房信息服务的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/450=ojj
- 文明养宠科普的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/ytk=928
- 基层健康档案的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/hfv=SXm
- 社区知识分享的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/935
- 图书借阅体验的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lzj
- 城市生活记录的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/2VU
- 城市生活记录的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/819=fjk
- 社区活动策划的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ywz=916
- 个人时间管理的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Pf4=a8k
- 家庭环保行动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E6%97%85%E6%B8%B8?/110
- 城市公共标识的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E6%97%85%E6%B8%B8?/ptf
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E6%97%85%E6%B8%B8?/m0S
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E6%97%85%E6%B8%B8?/966=wet
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E6%97%85%E6%B8%B8?/wwl=549
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E6%97%85%E6%B8%B8?/2b6=qAJ
- 急救知识普及的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/597
- 生活服务数字化的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/koj
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/aOy
- 新能源知识普及的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/082=jsn
- 城市公共厕所的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/xnr=859
- 地方文化传播的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/7mK=hXS
- 节气饮食文化的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/560
- 公共设施使用的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/klr
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/rhd
- 节能生活方式的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/331=lgh
- 食品配送体验的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/azm=428
- 社区信息发布的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/kbZ=Xo2
- 无障碍出行的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/817
- 社区活动空间的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/edl
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/OZJ
- 家庭理财科普的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/277=rhg
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/mbc=585
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/eAW=wpD
- 气象科普传播的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/030
- 食品安全科普的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/pka
- 家庭节能实践的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/FHi
- 灵活就业交流的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/464=dgz
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/tgc=869
- 文化场馆预约的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%89%E7%A5%A5%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/YtC=RED
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/224
- 食品配送体验的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/bqz
- 软件开发学习的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/VZN
- 城市公共饮水的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/242=vdu
- 乡村电商实践的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/iju=715
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%90%89%E7%A5%A5%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/JTM=wst
- 生活技能分享的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/337
- 市民热线服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/jdj
- 城市应急广播的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/jM6
- 文化场馆预约的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/486=wsu
- 城市博物馆服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/klu=349
- 非遗体验活动的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E7%A4%BE%E8%AE%BA?/qBb=21n
- 城市建设科普的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/082
- 社区艺术活动的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/ecp
- 城市树木认养的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/NFW
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/548=nwi
- 小区停车协商的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/lti=097
- 社区心理支持的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/FzG=KR5
- 城市体育设施的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/412
- 个人信息保护的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/uqp
- 文明养宠科普的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/sLd
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/301=zpt
- 学校体育活动的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/xwg=950
- 城市雨天出行的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/ZJR=h5A
- 家庭照护支持中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/905
- 公共场所导视的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/hpn
- 儿童友好空间的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/xvf
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/717=ljq
- 传统节日科普的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/dib=376
- 社区运动空间的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%90%89%E7%A5%A5%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/P2a=GcV
- 农产品消费体验的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/157
- 社区艺术活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/car
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/Yxq
- 健康步道使用的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/124=dls
- 数字档案服务的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/ajx=710
- 数字创意课程的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/WhM=6Vw
- 生活服务数字化的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/445
- 公共设施使用的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%90%89%E7%A5%A5%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%96%87%E6%91%98?/yuk

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
