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

- 科学健身方法的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91__%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/599
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91__%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/kso
- 社区运动空间中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91__%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/BdZ
- 健康步道使用的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91__%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/454=fib
- 街道综合服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91__%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/ara=891
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91__%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/dxJ=GrX
- 志愿服务平台的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/525
- 科学教育活动的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/lmo
- 社区消防演练的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/kGl
- 基层健康服务的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/557=cfw
- 邻里共享空间中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/tpm=643
- 绿色生活实践的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/Zsb=fOl
- 城市绿道建设的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/413
- 城市基础设施的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/dxu
- 公共空间照明的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/SGj
- 亲子阅读活动的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/927=whl
- 读书会组织的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/bhd=432
- 个人时间管理的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/z3s=Y9l
- 城市运动公园的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/744
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/esn
- 社区手工活动的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/m5e
- 青少年职业启蒙的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/589=dfj
- 数字课堂应用的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/dmt=915
- 城市共享单车的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/PWq=kG5
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/028
- 科学信息获取的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/dbi
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/1us
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/622=cme
- 青年就业服务的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/bdg=691
- 应急物资管理的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%B5%A2%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/GAe=D3g
- 老年人出行服务的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/402
- 灵活就业交流的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/qwy
- 数字设备回收的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/ON3
- 社区阅读服务的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/079=omd
- 骑行路线规划的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/hig=113
- 城市社区治理的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/wbI=wus
- 绿色生活实践的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84_360%E4%BA%B2%E5%AD%90?/657
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84_360%E4%BA%B2%E5%AD%90?/jhq
- 老年运动活动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84_360%E4%BA%B2%E5%AD%90?/GLn
- 社区读书角建设中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84_360%E4%BA%B2%E5%AD%90?/754=yyq
- 城市公共标识的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84_360%E4%BA%B2%E5%AD%90?/rud=389
- 数字设备回收的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84_360%E4%BA%B2%E5%AD%90?/vZw=zve
- 居民健康教育的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/605
- 新能源出行的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/cuh
- 便民服务地图的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/YUB
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/072=usd
- 本地旅行体验的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/zuf=939
- 社区生活指南的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/N8H=ObY
- 乡村产业科普的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/900
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/sdy
- 社区文化节活动的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/v4w
- 节能生活方式的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/049=ije
- 家庭节能设备的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/ahz=657
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/qug=E66
- 城乡公共服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/994
- 智能家居应用的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/lqs
- 数字阅读服务的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/KVR
- 社区庭院绿化的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/856=zfy
- 社区托育服务的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/czj=370
- 儿童友好空间的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Wz8=ECX
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_360%E6%97%B6%E6%8A%A5?/371
- 城市农夫市集的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_360%E6%97%B6%E6%8A%A5?/siu
- 城市公共标识的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_360%E6%97%B6%E6%8A%A5?/PXc
- 社区手工活动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_360%E6%97%B6%E6%8A%A5?/411=stz
- 户外活动组织中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_360%E6%97%B6%E6%8A%A5?/sco=126
- 本地历史资料的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91_360%E6%97%B6%E6%8A%A5?/kG5=qqQ
- 城市地名文化的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/846
- 社区阅读服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/csc
- 社区消防演练的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/Mpa
- 农业科普体验的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/250=mhk
- 骑行路线规划的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/azf=038
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/fMG=Izp
- 数字支付体验的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/556
- 家庭养老规划的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/mik
- 个人时间管理的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/gkl
- 城市体育设施的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/302=rvn
- 城市树木认养的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/joq=085
- 城市水环境观察的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/7pY=ep4
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/830
- 农贸市场环境的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/syr
- 气象科普传播的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/1ly
- 校园安全教育的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/905=ryr
- 科学教育活动的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/tbq=108
- 光伏知识科普的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/ZAK=i3b
- 社区阅读服务的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/695
- 城市建设科普的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/yno
- 医院导诊服务有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/MNV
- 社区故事采集的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/869=rgc
- 绿色快递包装的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/nxz=865
- 家庭安全提示的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/83r=l5f
- 儿童户外活动的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/406
- 社区养老服务的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/ivx
- 青年志愿活动的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/vWN
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/279=wdy
- 城市人文观察的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/skq=185
- 家庭急救准备的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/GWU=Uyp
- 家庭食品保存的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/002
- 户外活动组织的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/cdw
- 线上办事服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/Onf
- 城市公共饮水的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/963=jrb
- 传统节日科普的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/ahd=743
- 城市噪声观察的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/vV8=R9w
- 数字素养提升的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%B0%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%AE%97%E4%B8%8D%E7%AE%97%E8%B5%8C%E5%8D%9A__%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/584
- 青少年心理健康的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%B0%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%AE%97%E4%B8%8D%E7%AE%97%E8%B5%8C%E5%8D%9A__%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/dup
- 节假日出行安排的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%B0%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%AE%97%E4%B8%8D%E7%AE%97%E8%B5%8C%E5%8D%9A__%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/lxh
- 旧物循环利用中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%B0%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%AE%97%E4%B8%8D%E7%AE%97%E8%B5%8C%E5%8D%9A__%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/510=emo
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%B0%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%AE%97%E4%B8%8D%E7%AE%97%E8%B5%8C%E5%8D%9A__%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/euz=921
- 家庭节能实践的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B9%B0%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%AE%97%E4%B8%8D%E7%AE%97%E8%B5%8C%E5%8D%9A__%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/fdK=rLD
- 开放数据应用的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BA%BF%E4%B8%8A%E9%94%80%E5%94%AE%E7%9A%84%E7%8A%AF%E6%B3%95%E4%B9%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/812
- 社区垃圾回收的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BA%BF%E4%B8%8A%E9%94%80%E5%94%AE%E7%9A%84%E7%8A%AF%E6%B3%95%E4%B9%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/kej
- 社区儿童活动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BA%BF%E4%B8%8A%E9%94%80%E5%94%AE%E7%9A%84%E7%8A%AF%E6%B3%95%E4%B9%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/v5U
- 租房信息服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BA%BF%E4%B8%8A%E9%94%80%E5%94%AE%E7%9A%84%E7%8A%AF%E6%B3%95%E4%B9%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/208=gra
- 社区手工活动中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BA%BF%E4%B8%8A%E9%94%80%E5%94%AE%E7%9A%84%E7%8A%AF%E6%B3%95%E4%B9%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/zxx=667
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%BA%BF%E4%B8%8A%E9%94%80%E5%94%AE%E7%9A%84%E7%8A%AF%E6%B3%95%E4%B9%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/FIm=sGA
- 社区停车服务的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E4%B8%BA%E5%95%A5%E4%B8%8D%E8%AE%A9%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%BA%86_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/194
- 青年就业服务的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E4%B8%BA%E5%95%A5%E4%B8%8D%E8%AE%A9%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%BA%86_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/qnf
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E4%B8%BA%E5%95%A5%E4%B8%8D%E8%AE%A9%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%BA%86_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/gub
- 城市共享单车的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E4%B8%BA%E5%95%A5%E4%B8%8D%E8%AE%A9%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%BA%86_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/120=zec
- 智慧城市体验的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E4%B8%BA%E5%95%A5%E4%B8%8D%E8%AE%A9%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%BA%86_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/bjr=236
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E4%B8%BA%E5%95%A5%E4%B8%8D%E8%AE%A9%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%BA%86_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/OhE=qtb
- 校园节能行动的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E7%AE%97%E8%B5%8C%E5%BE%92%E5%90%97_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/004
- 儿童运动体验的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E7%AE%97%E8%B5%8C%E5%BE%92%E5%90%97_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/yha
- 邻里互助活动的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E7%AE%97%E8%B5%8C%E5%BE%92%E5%90%97_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/TeF
- 城市公共艺术的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E7%AE%97%E8%B5%8C%E5%BE%92%E5%90%97_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/396=hiv
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E7%AE%97%E8%B5%8C%E5%BE%92%E5%90%97_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/rqo=549
- 社区艺术活动的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E7%AE%97%E8%B5%8C%E5%BE%92%E5%90%97_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/5OQ=F8y
- 校园阅读活动的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/495
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/fwd
- 城市公共座椅的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/ulW
- 公共服务数字化的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/243=azu
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/xko=347
- 公交站点体验的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/nlj=DjS
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/733
- 城市适老服务的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/ycs
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/lyt
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/388=rya
- 社区生活指南的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/kcs=796
- 全民阅读推广的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/LTa=OYD
- 智慧城市体验的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/898
- 公共交通接驳的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/yam
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/A2U
- 社区家校合作的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/820=fnb
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/zlc=238
- 城市噪声观察的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/Pvs=DLO
- 安全出行教育的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/556
- 新能源知识普及的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/crj
- 数字阅读服务的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/NI9
- 社区便民集市的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/617=ftz
- 公共空间安全的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/wuj=611
- 志愿者培训交流的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/sgC=w7D
- 数字艺术创作的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/600
- 数字艺术创作的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/icb
- 城市微更新实践的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/tQv
- 社区防暑服务的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/843=stl
- 小区公共照明的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/bcv=814
- 家庭消费规划的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/xSa=f2g
- 社区共享书架的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%BF%AB%EF%BC%8F3_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/202
- 生活技能分享的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%BF%AB%EF%BC%8F3_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/cjh
- 志愿服务平台的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%BF%AB%EF%BC%8F3_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/AEe
- 城市公共厕所的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%BF%AB%EF%BC%8F3_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/857=zzd
- 个人信息保护的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%BF%AB%EF%BC%8F3_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/gke=096
- 青少年科普实践的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%BF%AB%EF%BC%8F3_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/M2f=enl
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/768
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/uxp
- 城市空气科普的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/YXL
- 数字艺术创作的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/432=yaw
- 线上阅读资源的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/vtz=876
- 社区快递服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6_%E8%84%89%E8%84%89%E5%9B%BD%E5%86%85?/whC=cRW
- 家庭节能实践的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/333
- 图书馆数字服务的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/ccr
- 城市人文观察的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/0Ye
- 城市文明出行的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/633=lsu
- 家庭安全提示的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/phr=636
- 科学信息获取的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/dNX=Tp7
- 口袋公园建设的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%EF%BC%8F3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/677
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%EF%BC%8F3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/oog
- 城乡公共服务的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%EF%BC%8F3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/bIX
- 城市博物馆活动的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%EF%BC%8F3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/612=puy
- 校园阅读活动的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%EF%BC%8F3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/mdo=251
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%EF%BC%8F3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/Gk1=T2v
- 公共服务指南的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/653
- 医院导诊服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/lte
- 社区宣传栏更新的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/1rl
- 学校体育活动的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/072=llm
- 儿童安全出行的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/jeb=285
- 公共场所导视的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/5RK=bsh
- 社区活动策划的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/899
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/esy
- 家庭健康科普的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/lga
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/214=oqp
- 开放数据应用的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/oyu=601
- 食品安全科普的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E7%9B%B4%E6%92%AD?/R7Q=gU1
- 文明养宠科普中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/067
- 城市适老服务的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/rvq
- 在线学习体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/um1
- 地方文化传播的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/392=igp
- 社区知识分享的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/rsx=280
- 绿色建筑理念的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/hs5=njW
- 本地历史资料的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/370
- 公共交通信息服务的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/qrt
- 便民信息查询的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/5YJ
- 社区信息发布的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/271=wka
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/uug=146
- 绿色快递包装的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8A%A1?/1Sq=8vL
- 青少年户外教育的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%80%BB%E7%BB%93%29_360%E8%AE%BF%E8%B0%88?/048
- 老年人日常照护的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%80%BB%E7%BB%93%29_360%E8%AE%BF%E8%B0%88?/asn
- 城市可持续生活的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%80%BB%E7%BB%93%29_360%E8%AE%BF%E8%B0%88?/TOZ
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%80%BB%E7%BB%93%29_360%E8%AE%BF%E8%B0%88?/750=vjp
- 社区绿色空间的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%80%BB%E7%BB%93%29_360%E8%AE%BF%E8%B0%88?/jhp=897
- 城市公共艺术的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%94%BB%E7%95%A5%28%E6%80%BB%E7%BB%93%29_360%E8%AE%BF%E8%B0%88?/cwB=XyR
- 电子商务服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/173
- 急救知识普及的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/ikb
- 社区垃圾分类的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/dmF
- 数字资源检索的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/364=fmz
- 亲子科普活动的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/tdf=687
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%9B%98%E7%82%B9?/5ZS=wU1
- 城市公共空间的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/980
- 城市步行环境的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/gne
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/C1l
- 社区公共议事的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/196=jnb
- 就业技能培训的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ghv=293
- 智慧城市体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/gWy=5ie
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/811
- 社区宠物管理的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/kwv
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/8rb
- 社区花园共建的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/762=heo
- 周末休闲规划的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/wbs=095
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E8%AE%BA?/pY8=X4k
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/557
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/ldw
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/I2A
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/402=cmg
- 社区生活指南的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/vcu=189
- 电子商务服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8E%86%E5%8F%B2?/qBX=Dye
- 校园社团活动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/941
- 城市人文观察的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/bao
- 消防知识宣传的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/QJs
- 家庭环保习惯的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/425=wgs
- 城市便民驿站的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/snr=813
- 家庭园艺实践的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/jji=3k3
- 公共健身器材的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/051
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/qai
- 终身学习资源的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/wSB
- 课后服务体验的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/625=ktb
- 光伏知识科普的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/xha=332
- 公共服务指南的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E8%88%86%E6%83%85?/3FD=hc3
- 社会体育指导的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E5%88%86%E4%BA%AB_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/965
- 城市空气科普的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E5%88%86%E4%BA%AB_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/mep
- 城市绿道建设的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E5%88%86%E4%BA%AB_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/saR
- 乡村生态观察的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E5%88%86%E4%BA%AB_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/150=hap

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
