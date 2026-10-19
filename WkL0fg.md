# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 社区心理支持的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/8qM
- 数字生活课堂的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/793=bpt
- 社区公共餐饮的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/lli=876
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/q7Q=Vzt
- 节约用水实践的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A5%E7%89%88%E7%99%BB%E5%BD%95_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/479
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A5%E7%89%88%E7%99%BB%E5%BD%95_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/nvx
- 城市便民驿站的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A5%E7%89%88%E7%99%BB%E5%BD%95_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/Fjm
- 绿色办公实践的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A5%E7%89%88%E7%99%BB%E5%BD%95_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/517=dxc
- 乡村文化活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A5%E7%89%88%E7%99%BB%E5%BD%95_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/taj=050
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E6%97%A5%E7%89%88%E7%99%BB%E5%BD%95_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/1m3=0GS
- 非遗体验活动的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/439
- 图书馆活动策划的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/xvl
- 老年学习活动的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/wP3
- 社区活动策划的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/839=hko
- 社区活动策划的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/rxf=306
- 新能源出行的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/BXg=CU2
- 城市雨天出行的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/065
- 社区心理支持的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/usd
- 图书借阅体验的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/2sM
- 城市骑行环境的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/380=pmf
- 光伏知识科普的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/bto=020
- 数字政务体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/wKn=jiK
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/873
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/qmh
- 校园社团活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/A5g
- 城市绿道建设的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/798=llo
- 基层健康服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/dgh=418
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/K3X=jbv
- 节气饮食文化的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/689
- 无障碍出行的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/yqe
- 开放式学习空间的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/s63
- 家庭防灾准备的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/983=wju
- 生活垃圾减量的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/zax=974
- 家庭教育交流的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8vip-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/HxS=tpn
- 城市树木认养的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/505
- 低碳社区实践的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/dhw
- 街区道路维护的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/2kc
- 城市社区治理的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/808=hzd
- 人工智能科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/cmc=412
- 社区家政服务的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/QFL=0rb
- 城市公共标识的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/429
- 城市博物馆活动的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/dsu
- 数字政务体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/UYW
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/859=bsx
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/ljs=466
- 家庭园艺实践的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/GPC=B8I
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/686
- 节约用水实践的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/qzc
- 城市水环境观察的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/ikn
- 乡村教育资源的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/445=yhq
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/pmk=976
- 家庭健康科普的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%9B%9B%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E6%96%87%E6%91%98?/b5q=Wjh
- 社区教育资源的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%99%BB%E5%BD%95%E6%96%B9%E5%BC%8F_360%E7%A4%BE%E8%AE%BA?/168
- 数字艺术创作的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%99%BB%E5%BD%95%E6%96%B9%E5%BC%8F_360%E7%A4%BE%E8%AE%BA?/rsx
- 社区便利生活的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%99%BB%E5%BD%95%E6%96%B9%E5%BC%8F_360%E7%A4%BE%E8%AE%BA?/JaW
- 数字创作工具的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%99%BB%E5%BD%95%E6%96%B9%E5%BC%8F_360%E7%A4%BE%E8%AE%BA?/021=xij
- 街区更新实践的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%99%BB%E5%BD%95%E6%96%B9%E5%BC%8F_360%E7%A4%BE%E8%AE%BA?/cqa=395
- 社区商业活力的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%99%BB%E5%BD%95%E6%96%B9%E5%BC%8F_360%E7%A4%BE%E8%AE%BA?/iSB=tuM
- 社区教育资源的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/086
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/wrc
- 儿童安全出行的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/ruZ
- 志愿服务平台的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/782=wqp
- 个人信息保护的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/ves=483
- 地方戏曲体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/2W4=7gH
- 社区家校合作的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/189
- 社会体育指导的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/bbn
- 地方文化传播的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/XJI
- 环境监测科普的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/829=reb
- 农贸市场环境的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/wbn=367
- 数字课堂应用的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8welcome_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/bJT=eqD
- 校园节能行动的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/931
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/oii
- 社区文化节活动的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/ZW6
- 社区宠物管理的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/167=jkz
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/cfg=714
- 口袋公园建设的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E7%9B%9B%E4%B8%96%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%91%A8%E6%8A%A5?/FRq=Hju
- 在线教育体验的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/512
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/tim
- 社区慢性病防控的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/FTl
- 城市夜间生活的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/577=iqz
- 城市水环境观察的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/nge=113
- 城乡交流活动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/3F9=cM8
- 小区电梯维护的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%82%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/917
- 社区活动空间的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%82%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/tyn
- 社区快递服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%82%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/5qT
- 网络信息辨识的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%82%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/660=nbj
- 志愿服务平台的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%82%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/fgq=779
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%82%E5%8E%85_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/7j2=EX6
- 节日文化体验的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BE%AE%E4%BF%A1%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/911
- 社区垃圾回收的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BE%AE%E4%BF%A1%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/ull
- 城市地名文化的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BE%AE%E4%BF%A1%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/Rzw
- 节日文化体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BE%AE%E4%BF%A1%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/140=jku
- 公共交通信息服务的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BE%AE%E4%BF%A1%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/jwq=493
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BE%AE%E4%BF%A1%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/cPX=0eQ
- 食品安全科普的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/351
- 绿色生活实践的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/duf
- 智慧城市体验的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/z1M
- 社区消防演练的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/570=ksv
- 小微企业服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/qjp=018
- 社区文化节活动的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/WZN=IJt
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/225
- 乡村阅读空间的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/frb
- 绿色生活实践中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/jpv
- 绿色建筑理念的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/197=ziu
- 儿童阅读角的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/ztc=126
- 文化讲座服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/iOQ=KSM
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/519
- 社区垃圾分类的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/wko
- 科技馆参观体验的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/8Ms
- 老年人文化生活的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/545=xnv
- 城市文明实践的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/orh=888
- 环境监测科普的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%A0%E7%89%A9?/h6R=vOV
- 灵活就业交流的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/727
- 公共场馆服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/jge
- 数字资源检索的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/9Xf
- 社区庭院绿化的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/925=otf
- 社区阅读服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/bon=682
- 城市夜间生活的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/RZP=GQN
- 开源技术交流的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/330
- 个人数据管理的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/nis
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/ctg
- 智能家居应用的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/488=jlk
- 社区共享书架的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/idx=591
- 科学运动指导的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/Krn=wDz
- 城市文化路线的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/433
- 户外活动组织的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/xqo
- 光伏知识科普的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/kGM
- 城市博物馆活动的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/992=wcu
- 智能手机助老的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/jof=461
- 社区家政服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%BA%94%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/fvT=FXW
- 节约用水实践的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/878
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/eaf
- 邻里共享空间的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/bP3
- 城市公共厕所的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/100=eie
- 社区运动空间的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/ksx=947
- 基层服务创新的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/nCE=mS3
- 口袋公园建设的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/771
- 社区信息发布的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/fds
- 家庭节能设备的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/A2M
- 绿色办公实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/723=ewr
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/dtb=977
- 人工智能科普的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/VrK=9w2
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/503
- 节能家电使用的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/ihf
- 传统节日科普的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/DMn
- 社区便民集市的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/361=qkq
- 城市步行友好的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/aci=740
- 绿色消费选择的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/Wdo=wY7
- 生活垃圾减量的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%88%8A%E7%99%BB?/424
- 创业经验分享的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%88%8A%E7%99%BB?/xcr
- 数字公共文化的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%88%8A%E7%99%BB?/LRi
- 软件开发学习的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%88%8A%E7%99%BB?/166=rfs
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%88%8A%E7%99%BB?/old=541
- 社区家校合作的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%88%8A%E7%99%BB?/CbT=1FF
- 绿色办公实践的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/752
- 数字便民地图的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/xkh
- 传统节日科普的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/i38
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/602=fre
- 社区活动空间的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/enj=112
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/CPw=Nfs
- 基层服务创新的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/303
- 社区公共议事的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/apw
- 公共服务数字化的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/tgG
- 乡村生态观察的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/071=dmp
- 家庭安全提示的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/ore=417
- 个人数据管理的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/AiD=Ge3
- 老年友好服务中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/226
- 乡村电商实践的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/cck
- 市民意见收集的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/Znu
- 本地旅行体验的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/389=jxu
- 小微企业服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/fdm=244
- 药品使用科普的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/bOB=kP0
- 科普展览体验的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/696
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/zms
- 城乡公共服务的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/Rpw
- 公共服务评价的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/896=dek
- 基层健康服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/jgj=138
- 城市生活服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%97%B6%E6%8A%A5?/Vnh=Lyh
- 数字阅读服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/615
- 城市公共艺术的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/bmg
- 公共卫生设施的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/8Uj
- 公共服务评价的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/858=xwd
- 运动安全知识的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/evp=486
- 公共交通接驳的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E6%B1%BD%E8%BD%A6?/HMg=br9
- 节假日出行安排的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/136
- 传统节日科普的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/ivl
- 儿童安全出行的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/Sa9
- 家庭环保行动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/571=bsj
- 学校体育活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/dta=496
- 邻里共享空间的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E9%97%AE%E7%AD%94?/1R5=KGC
- 青少年心理健康的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%B2%E5%AD%90?/668
- 城市空气科普的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%B2%E5%AD%90?/htd
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%B2%E5%AD%90?/78C
- 居民健康教育中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%B2%E5%AD%90?/523=mao
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%B2%E5%AD%90?/hvy=767
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E9%A1%BA%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%B2%E5%AD%90?/Tp0=G3g
- 文化场馆预约的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/541
- 家庭环保行动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/oax
- 科学教育活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/ZhA
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/478=xmb
- 城市公共厕所的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/yrq=780
- 人工智能科普的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/Cib=qyd
- 环境监测科普的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/145
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/dqk
- 老年友好服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/UUi
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/056=zqt
- 职业技能学习的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/rjw=987
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E9%A1%BA%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/wRu=dQ4
- 街区更新实践的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%A1%BA%E5%8F%91%E6%BE%B3%E9%97%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/626
- 急救知识普及的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%A1%BA%E5%8F%91%E6%BE%B3%E9%97%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/wqg
- 老年人文化生活的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%A1%BA%E5%8F%91%E6%BE%B3%E9%97%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/wse
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%A1%BA%E5%8F%91%E6%BE%B3%E9%97%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/649=jbn
- 智能家居应用的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%A1%BA%E5%8F%91%E6%BE%B3%E9%97%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/fym=279
- 公共服务沟通的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E9%A1%BA%E5%8F%91%E6%BE%B3%E9%97%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/taY=WIu
- 城市夜间照明的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/089
- 口袋公园建设的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/ymk
- 创业经验分享的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/r2G
- 社区体育组织的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/801=jfo
- 城市水环境观察的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/opj=941
- 家庭网络使用的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/1Ha=Cav
- 公共健身器材的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/527
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/hkd
- 开放式学习空间的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/NKH
- 绿色校园实践的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/816=pin
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/kam=795
- 社区运动空间的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/9Pk=gzN
- 城市便民驿站的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/057
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xxs
- 城市文化路线的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/4Yp
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/517=qku
- 生活垃圾减量的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wpk=081
- 家庭养老规划的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/E4w=DjF
- 社区学习活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/453
- 公共场馆服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/wou
- 农贸市场环境中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/txl
- 乡村文化空间的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/617=dhx
- 线上办事服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/ytz=895
- 社区共享书架的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/vrF=dN1
- 社区读书角建设的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/066
- 无障碍信息设计的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/uad
- 社区志愿服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/BBy
- 亲子科普活动的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/149=dzd
- 地方民俗记录的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/fza=667
- 公共服务沟通的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/50g=Ucn
- 数字课堂应用的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/309
- 城市人文观察的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/ewv
- 老年友好服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/g52
- 城市可持续生活的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/213=otl
- 老年运动活动的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/lte=426
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%9B%9B%E5%AD%A3%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/KAc=NCS

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
