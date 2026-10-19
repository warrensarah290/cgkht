# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 公园亲子设施的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/303
- 节能家电使用的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/izg
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/6Gd
- 数字创作工具的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/289=dfj
- 城市运动公园的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/kut=217
- 社区法律科普的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AE%BA%E5%9D%9B_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/uBI=bWF
- 城市运动公园从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/737
- 社区菜市场服务的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/qzc
- 城市应急广播的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/snm
- 社会体育指导的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/311=hxd
- 社区协商议事的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/cbd=309
- 居家防滑改造的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93D_%E7%99%BE%E5%BA%A6%E6%9B%B2%E8%89%BA?/9GI=X8H
- 数字档案服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/887
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/yzt
- 居民健康教育的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/Qxp
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/076=mda
- 城市公共标识的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/kyu=636
- 校园社团活动中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/Ptg=J7F
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/405
- 公共场馆服务的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/xzp
- 在线教育体验的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/DRJ
- 社区教育资源的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/433=wlv
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/sum=723
- 节能生活方式的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%B7%A5%E5%85%B7%E5%9B%BE%E8%A1%A8_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/hKS=pVL
- 市民意见收集的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/996
- 乡村生活观察的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/qfg
- 农产品消费体验的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/fnJ
- 社区应急准备的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/378=yku
- 城市公共艺术的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/iju=747
- 农村环境治理的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%AF%95%E6%9C%BA%E5%8F%B7_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/XJ9=xxb
- 软件开发学习的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/853
- 灵活就业交流的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/uti
- 健康信息获取的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/ZwI
- 城市慢行系统的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/581=hcg
- 公共空间休憩的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/rwe=127
- 数字资源检索的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%BD%A9%E7%BD%9117500%E5%8E%9F%E5%88%9B%E4%B8%93%E4%B8%9A_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/BES=BqN
- 农产品消费体验的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/277
- 健康信息获取的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/etx
- 家庭照护支持的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/1oe
- 家庭养老规划的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/845=dpt
- 在线教育体验的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/mvr=007
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/EEu=EIa
- 公共空间休憩的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/355
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/awt
- 骑行路线规划中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/3bh
- 便民服务地图的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/840=szi
- 公共空间照明的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/nsc=315
- 在线教育体验的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/xeR=O3G
- 城市博物馆服务的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/264
- 农业科普体验的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/hlb
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/QEE
- 城市步行环境的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/804=hyw
- 街头绿植养护的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/srj=982
- 在线教育体验的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/2K9=00t
- 口袋公园建设的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/830
- 城市适老服务的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/gkn
- 老年运动活动的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/GgY
- 生活技能分享的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/956=ius
- 数字艺术创作中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/cni=761
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%98%9F%E5%BA%A7?/1RH=BLZ
- 线上办事服务的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/631
- 在线学习体验的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/waq
- 数字创作工具的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/SWK
- 街区道路维护的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/289=kyy
- 应急物资管理的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/dkt=851
- 数字便民地图的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/a8c=txu
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/329
- 城市应急科普的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/rcv
- 科普展览体验的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/c4L
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/747=kgu
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/zic=859
- 非遗课堂体验的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8APP_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/K2w=AOA
- 数字便民地图的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/950
- 城市文明出行的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/yim
- 公共空间休憩的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/P47
- 老年人出行服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/800=hea
- 青年职业探索的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/bmc=401
- 科普展览体验的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%8B%E8%BD%BD%E4%B9%90%E5%BD%A9%E7%BD%91app_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/NHJ=k7R
- 青年就业服务的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/016
- 全民阅读推广的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/nmr
- 科学健身方法的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/FLf
- 社区设施共享的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/505=cdj
- 公共服务评价的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ypd=793
- 老年数字阅读的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Jj2=JGH
- 街区小店体验的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/057
- 绿色出行服务的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/mzw
- 邻里共享空间的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/n9B
- 家庭消费规划的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/898=xtj
- 街头绿植养护的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/anl=982
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8365%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/f3G=dq1
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/476
- 家庭教育交流的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/vki
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/ugb
- 公共场馆服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/760=qyi
- 家庭理财科普的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/bbt=833
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%A8%8E%E5%8A%A1?/N5Q=pqB
- 公共服务数字化的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/578
- 科学运动指导中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/eoo
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/8ia
- 老年运动活动的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/173=fvn
- 社区托育服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/kgt=186
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%95%B0%E8%AF%BB?/by0=nlN
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/709
- 城市公共艺术中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/snz
- 科学信息获取的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/MMO
- 急救知识普及的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/199=qxp
- 节假日出行安排的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/pim=309
- 居民健康教育的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/0Lh=8hl
- 绿色出行服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/504
- 租房信息服务的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/tfc
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/yyt
- 家庭节能设备的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/202=luw
- 数字生活课堂的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/nun=825
- 社区运动空间的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/qZC=qdb
- 社区生活指南的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/393
- 基层医疗预约的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/spb
- 社区体育组织的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/Vca
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/926=yhz
- 社区活动策划的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/ppu=299
- 科普展览体验的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/BrH=j2i
- 科学运动指导的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/148
- 节约用水实践的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/ljf
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/wwc
- 节假日出行安排的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/576=gew
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/lci=015
- 城市雨天出行的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/o0E=Y3T
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/318
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/ylm
- 城市微更新实践的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/G9t
- 青少年户外教育中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/430=wgl
- 便民信息查询的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/zbw=282
- 地方民俗记录的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/LZj=d4h
- 智能家居应用的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E7%BD%91%E6%AF%94%E8%B5%9B_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/533
- 便民服务地图的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E7%BD%91%E6%AF%94%E8%B5%9B_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/pbw
- 医院导诊服务的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E7%BD%91%E6%AF%94%E8%B5%9B_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/ucl
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E7%BD%91%E6%AF%94%E8%B5%9B_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/103=kui
- 本地消费场景的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E7%BD%91%E6%AF%94%E8%B5%9B_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/ubx=474
- 公共服务指南的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E7%BD%91%E6%AF%94%E8%B5%9B_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/GMd=P0N
- 城市公共饮水的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/425
- 社区便利生活的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/hqb
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/9D8
- 地方民俗记录的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/082=pic
- 节假日出行安排的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/arv=720
- 乡村文化空间的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E7%BD%91%E7%AB%9E%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%88%8A%E7%99%BB?/Q0h=RCJ
- 公共服务评价的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/949
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/ubi
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/Imp
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/017=lsb
- 便民维修服务的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/jzf=704
- 城市公共标识中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/eAi=swq
- 城市人文观察的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%9B%B4%E6%92%AD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/744
- 城市步行友好的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%9B%B4%E6%92%AD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/iev
- 城市步行环境的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%9B%B4%E6%92%AD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/JCf
- 绿色校园实践的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%9B%B4%E6%92%AD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/031=phv
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%9B%B4%E6%92%AD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/ozp=276
- 节假日出行安排的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%9B%B4%E6%92%AD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/65x=G6u
- 社区文化节活动的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%BC%80%E5%A5%96_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/796
- 本地历史资料的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%BC%80%E5%A5%96_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/wqz
- 乡村阅读空间的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%BC%80%E5%A5%96_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/YOG
- 健康饮水科普中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%BC%80%E5%A5%96_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/463=bmv
- 街头绿植养护的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%BC%80%E5%A5%96_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/krj=709
- 公共空间导览的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%BC%80%E5%A5%96_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%B4%B7?/Fjh=L34
- 数据分析入门的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/924
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/xeb
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/5wM
- 老年智能设备的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/972=rln
- 社区体育组织的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/twi=529
- 社区文化传播的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/1H8=gMG
- 社区应急准备的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/013
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/raq
- 数字设备回收的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/UlM
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/839=bjb
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/blj=529
- 家庭健康科普的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E5%A5%96_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/b77=1UL
- 城市噪声观察的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E8%B4%AD%E4%B9%B0_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/671
- 社区文化传播中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E8%B4%AD%E4%B9%B0_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/ksu
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E8%B4%AD%E4%B9%B0_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/r4J
- 社区垃圾回收的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E8%B4%AD%E4%B9%B0_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/543=xvq
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E8%B4%AD%E4%B9%B0_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/chg=251
- 城市运动公园的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E8%B4%AD%E4%B9%B0_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/0y5=lyY
- 城市夜间照明的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%913d%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/627
- 户外活动组织中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%913d%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/loy
- 家庭教育交流的便捷程度观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%913d%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/cg3
- 地方美食文化的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%913d%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/960=zyk
- 创业经验分享的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%913d%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/zcq=984
- 数字地图应用的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%913d%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%AE%B6%E7%94%B5?/gbz=Rvo
- 通勤路线规划的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/905
- 乡村电商实践的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/rso
- 城市公共艺术的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/Hv8
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/323=xxm
- 社区活动策划的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/bgu=753
- 数字创作工具的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/uDg=6vV
- 口袋公园建设的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/988
- 家庭陪伴活动的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/lrx
- 小区停车协商的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/Itr
- 灵活就业交流的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/708=qxw
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/zxs=662
- 公共服务数字化的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/OZq=mbl
- 社区互助网络的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/270
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/oca
- 市民意见收集的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/O9g
- 公共设施使用的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/784=krm
- 公共交通接驳的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/ksz=558
- 社区便利生活的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E7%AB%9E%E5%BD%A9%E7%BD%91%E9%A6%96%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/RyE=0Py
- 社区公共卫生的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/866
- 绿色出行服务的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/jcz
- 儿童安全出行中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/XV9
- 城市游园体验的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/831=ebr
- 城市共享单车的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/eid=911
- 乡村文化空间的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E7%AB%9E%E5%BD%A9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B?/MMa=8Ri
- 生活垃圾减量的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/507
- 城乡交流活动的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/kvk
- 社区便民集市的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/XYI
- 公共空间导览的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/958=yoa
- 家庭消费规划的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/sza=806
- 机器人科普活动的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/R4d=DBr
- 青少年科普实践的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E6%97%B6%E8%AF%84?/213
- 城市公共座椅的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E6%97%B6%E8%AF%84?/zyh
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E6%97%B6%E8%AF%84?/Pj0
- 传统手工艺体验的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E6%97%B6%E8%AF%84?/122=vow
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E6%97%B6%E8%AF%84?/ajm=059
- 数字艺术创作的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91app_36%E6%B0%AA%E6%97%B6%E8%AF%84?/qnu=WCh
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%85%8D%E8%B4%B9%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/158
- 绿色办公实践的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%85%8D%E8%B4%B9%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/frq
- 老年运动活动的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%85%8D%E8%B4%B9%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/00U
- 科普展览体验的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%85%8D%E8%B4%B9%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/363=dqr
- 科学教育活动的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%85%8D%E8%B4%B9%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/wur=067
- 城市夜间照明的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%85%8D%E8%B4%B9%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/C2L=21c
- 城市空气科普的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/132
- 市民意见收集的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/idn
- 数字档案服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/CuS
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/418=rjy
- 新能源出行的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/fwf=643
- 社区科普课堂的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E7%AB%9E%E5%BD%A9%E7%8C%AB%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/03V=yM8
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/743
- 骑行路线规划的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/ryd
- 社区学习活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/4ES
- 公共服务指南的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/454=nvq
- 就业技能培训的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/ztj=842
- 就业技能培训的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E7%8C%ABapp%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/xk1=Dgn
- 亲子阅读活动的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/954
- 地方文化传播的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/fur
- 家庭收纳实践的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/uGd
- 老年学习活动的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/869=gve
- 无障碍出行的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/vdg=811
- 文化场馆预约的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B1%86%E7%93%A3%E6%A1%A3%E6%A1%88?/M8W=c3w
- 城市休闲步道的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD58_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/113
- 电动汽车充电的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD58_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/fbb
- 社区宠物管理的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD58_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/S9e
- 社区信息发布的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD58_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/473=eaa

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
