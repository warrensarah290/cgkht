# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 社区垃圾回收的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ojb=667
- 在线教育体验的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E9%B8%BF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/L0c=ouT
- 社区文化传播的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/899
- 城市步行友好的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/bdj
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/6pC
- 校园阅读活动的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/270=jlw
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/zvj=344
- 机器学习入门的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8F%B8%E6%B3%95?/8Xx=1NI
- 城市公共厕所的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360?/613
- 城市公共空间的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360?/gll
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360?/Orx
- 安全出行教育的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360?/910=xoi
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360?/nos=931
- 居民健康教育的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360?/CIs=wd2
- 创业经验分享的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/708
- 家庭园艺实践的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/moi
- 社区花园共建的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/rq8
- 城市基础设施的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/925=ike
- 社区共享书架的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/uki=096
- 城市微更新实践的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/mya=OzE
- 老年人文化生活的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/405
- 城市步行友好的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/zql
- 城市公共自行车的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/KD3
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/880=ezp
- 社区科普课堂的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/wcb=110
- 终身学习资源的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E9%9B%85%E8%99%8E%E5%91%A8%E6%8A%A5?/wKg=6VH
- 公共场馆服务的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/205
- 城市运动公园的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/uyr
- 社区共享书架的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/CVS
- 公园休闲体验的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/706=kjt
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/nyo=175
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/QT6=NMy
- 公共服务沟通的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/445
- 网络信息辨识的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/uef
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/jod
- 无障碍信息设计的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/690=cfc
- 节日文化体验的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/ibm=500
- 社区安全巡查的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/l8a=UUu
- 家庭健康管理的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/219
- 社区活动策划的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/yzw
- 居家适老化改造的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/gto
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/534=sip
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/eqe=230
- 数字公共文化的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/vjh=uh1
- 社区垃圾回收的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/409
- 数字阅读服务有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/bgz
- 社区防暑服务的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/Vef
- 公共服务评价的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/578=akl
- 社区庭院绿化的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/hej=763
- 数字支付体验的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%9B%B2%E8%89%BA?/wyv=IBz
- 消防知识宣传的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/796
- 公共服务数字化的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/gxe
- 绿色出行服务的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/Tjv
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/550=bkb
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/luc=608
- 读书会组织的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/Zsj=xP3
- 社区垃圾回收的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/493
- 口袋公园建设的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/mky
- 开放数据应用的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/0tm
- 节假日出行安排的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/607=qns
- 社区公共餐饮的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/wgf=125
- 绿色出行服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/Kz1=baI
- 光伏知识科普中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/206
- 环境教育课程的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/tnb
- 数字便民地图的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/7ku
- 社区生活指南的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/118=baj
- 软件开发学习的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/gaa=664
- 人工智能科普的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/Iva=vJb
- 个人时间管理的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/726
- 乡村教育资源中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/ewt
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/3i4
- 公共服务数字化的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/083=qez
- 城市文明实践的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/ysb=527
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/K6X=EvR
- 社区读书角建设的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/493
- 新能源知识普及的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/zue
- 数字阅读服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/eyE
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/535=jbp
- 个人时间管理的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/npj=170
- 环境教育课程的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/G5R=dOo
- 儿童户外活动的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/672
- 便民服务地图的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/vhi
- 基层健康服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/sfg
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/975=skg
- 城市农夫市集的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/ave=615
- 食品配送体验的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/3VM=3L4
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/605
- 本地消费场景的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/ous
- 邻里互助活动的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/S40
- 地方民俗记录的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/376=aym
- 城市社区治理的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/whv=343
- 城市公共艺术的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/w3C=Put
- 健康步道使用的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/113
- 老年友好服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/glq
- 急救知识普及的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/WCr
- 数字政务体验的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/438=bjj
- 社区共享书架的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/yzy=800
- 农业科普体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/Q4H=A7x
- 数字学习资源的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/940
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/zjy
- 社区志愿服务的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/12h
- 社区活动策划的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/828=tbf
- 社区活动策划的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/igc=439
- 开源技术交流的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/oM3=DZj
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/459
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/cqi
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/qxf
- 食品配送体验的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/268=lps
- 公园休闲体验的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/uad=069
- 健康步道使用的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/XBj=nYf
- 城市运动公园的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/133
- 社区宠物管理的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/xow
- 公共场所导视的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/Ikv
- 终身学习资源的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/571=ymd
- 老年友好服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/lqu=325
- 老年智能设备的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/jue=K2U
- 社区生活指南的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E4%BC%97%E6%B5%8B?/915
- 社区便民服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E4%BC%97%E6%B5%8B?/opc
- 青年就业服务的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E4%BC%97%E6%B5%8B?/2jh
- 公共服务预约的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E4%BC%97%E6%B5%8B?/613=ydx
- 机器学习入门的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E4%BC%97%E6%B5%8B?/orp=073
- 线上办事服务的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_36%E6%B0%AA%E4%BC%97%E6%B5%8B?/J6g=oja
- 职业技能学习的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/073
- 校园阅读活动的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/bos
- 节能生活方式的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/EIq
- 社区宠物管理的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/608=ojw
- 社区商业活力的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/qic=836
- 社区读书角建设的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/55s=AIx
- 乡村阅读空间的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A5%A8?/605
- 农贸市场环境的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A5%A8?/low
- 城市游园体验的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A5%A8?/tMO
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A5%A8?/635=gpz
- 老年人文化生活的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A5%A8?/vwf=253
- 公共交通接驳的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%8A%95%E7%A5%A8?/j1k=QtF
- 城市应急科普的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/222
- 城市共享单车的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/uch
- 公共空间导览的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/u4R
- 城市绿道建设的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/992=zsx
- 社区阅读服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/zvz=402
- 绿色生活实践的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/QU7=k3Z
- 生活垃圾减量的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/349
- 数字课堂应用的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/ovc
- 便民服务窗口的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/f3g
- 绿色快递包装的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/932=njj
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/msb=290
- 社区知识分享的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/9Nh=oWf
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/930
- 老年智能设备的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/rdj
- 公共卫生设施的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/mYA
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/007=gvf
- 邻里共享空间的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/fxt=438
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/NV6=KYJ
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/319
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/xyd
- 机器人科普活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/Afi
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/630=oko
- 劳动教育实践的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/etl=648
- 通勤路线规划的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/Szs=NW1
- 公共交通接驳的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/597
- 家庭环保习惯的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/qte
- 家庭养老规划的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/iCB
- 租房信息服务的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/013=vmx
- 家庭消费规划的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/lom=685
- 街区小店体验的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E8%A7%86%E9%A2%91?/g3M=MGE
- 城市骑行环境的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8--%E7%94%A8%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/310
- 城市游园体验的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8--%E7%94%A8%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/hql
- 社区文化传播的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8--%E7%94%A8%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/ntg
- 文明养宠科普的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8--%E7%94%A8%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/339=iju
- 乡村文化空间的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8--%E7%94%A8%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/dty=459
- 创业经验分享的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8--%E7%94%A8%E6%88%B7_%E5%A4%B4%E6%9D%A1%E6%B1%BD%E8%BD%A6?/1GI=Rs1
- 公共设施维护的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/901
- 家庭用电安全的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/roq
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/teH
- 社区便民集市的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/990=dda
- 应急物资管理的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/cug=659
- 地方民俗记录的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/YEO=jBp
- 小区公共照明中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/265
- 家庭运动计划的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/sso
- 地方民俗记录的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/cLi
- 传统节日科普的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/888=uxy
- 城市人文观察的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/lla=264
- 非遗课堂体验的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/y09=CmC
- 便民维修服务的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E5%AE%9E%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A5%A8?/702
- 城市生活记录的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E5%AE%9E%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A5%A8?/crp
- 在线学习体验的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E5%AE%9E%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A5%A8?/Obs
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E5%AE%9E%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A5%A8?/177=tmh
- 节日文化体验的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E5%AE%9E%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A5%A8?/juo=265
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E5%AE%9E%E7%9A%84%E5%90%97_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A5%A8?/Top=CbO
- 数字公共文化的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%B7%B1%E5%9C%B3%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A7%91%E6%8A%80%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/333
- 城市夜间生活的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%B7%B1%E5%9C%B3%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A7%91%E6%8A%80%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/mbd
- 社区文化传播的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%B7%B1%E5%9C%B3%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A7%91%E6%8A%80%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/UMu
- 气象科普传播的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%B7%B1%E5%9C%B3%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A7%91%E6%8A%80%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/104=mua
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%B7%B1%E5%9C%B3%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A7%91%E6%8A%80%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/jzv=882
- 城市文化路线的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E6%B7%B1%E5%9C%B3%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A7%91%E6%8A%80%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/XIc=jus
- 节能生活方式的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/775
- 社区阅读服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/krb
- 老年学习活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/61v
- 公共交通信息服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/688=mic
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/cpk=194
- 社区手工活动的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/UL0=g6K
- 公共服务评价的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/580
- 城市公共标识的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/crp
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/3Gp
- 城市适老服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/238=umv
- 生活服务数字化的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/goa=595
- 城市文明实践的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/RRX=nVJ
- 节假日出行安排的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/934
- 社区快递服务的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/aff
- 垃圾分类指导的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/cFt
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/371=stz
- 劳动教育实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/ciz=461
- 无障碍出行的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/KYR=YX3
- 人工智能科普的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A9%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/170
- 科学健身方法的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A9%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/wic
- 数字课堂应用的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A9%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/CF4
- 公园亲子设施的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A9%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/950=iyi
- 数字政务体验的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A9%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/zby=472
- 机器学习入门的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A9%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%5B_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/83d=eQ5
- 远程协作工具的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8App_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/061
- 城市公共标识的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8App_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/xbr
- 青年职业探索的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8App_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/6pA
- 城市慢行系统的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8App_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/961=szj
- 社区公共议事的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8App_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/fcl=702
- 急救知识普及的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A9%E7%9B%88%E5%BD%A9%E7%A5%A8App_%E4%BC%98%E9%85%B7%E7%9E%AD%E6%9C%9B?/W9P=UdV
- 社区家政服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%96%9C%E5%8A%9B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/688
- 电动汽车充电中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%96%9C%E5%8A%9B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/jxd
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%96%9C%E5%8A%9B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/S5q
- 社区邻里服务的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%96%9C%E5%8A%9B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/068=zje
- 生成式工具使用的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%96%9C%E5%8A%9B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/zyz=182
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%96%9C%E5%8A%9B%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/XTB=zAp
- 在线教育体验的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/878
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/ddn
- 街区更新实践的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/wlZ
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/245=wvm
- 城市公共自行车的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/bmd=490
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/z8R=1Vu
- 家庭防灾准备的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9C%89%E6%B2%A1%E4%BA%BA%E7%8E%A9%E8%BF%87%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/123
- 数据分析入门的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9C%89%E6%B2%A1%E4%BA%BA%E7%8E%A9%E8%BF%87%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/rei
- 青少年科普实践的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9C%89%E6%B2%A1%E4%BA%BA%E7%8E%A9%E8%BF%87%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/OOh
- 口袋公园建设的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9C%89%E6%B2%A1%E4%BA%BA%E7%8E%A9%E8%BF%87%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/392=aya
- 社区停车服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9C%89%E6%B2%A1%E4%BA%BA%E7%8E%A9%E8%BF%87%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/gwq=289
- 劳动教育实践的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9C%89%E6%B2%A1%E4%BA%BA%E7%8E%A9%E8%BF%87%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%8F%B8%E6%B3%95?/weU=h1o
- 通勤路线规划的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/004
- 公共设施维护的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/qbe
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/mxX
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/981=inb
- 社区家政服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/ubq=489
- 校园社团活动的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/gX5=M69
- 信息无障碍体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/381
- 绿色快递包装的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%96%9C%E5%8A%9B%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%9E%AD%E6%9C%9B?/cvy

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
