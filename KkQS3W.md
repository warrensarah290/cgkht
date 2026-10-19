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

- 城市公共标识的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/678
- 环境监测科普的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/rjg
- 社区消防演练的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/JsA
- 城乡公共服务的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/044=ltm
- 安全出行教育的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/qnq=119
- 骑行路线规划的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/d7l=ZAc
- 通勤路线规划的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/396
- 社区艺术活动的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/ada
- 街区小店体验的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/CG9
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/813=nwt
- 数字生活课堂的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/jxe=674
- 绿色办公实践的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/kOq=Bpe
- 老年运动活动的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/103
- 城市可持续生活的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/sfn
- 文化场馆预约的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/mlF
- 网络安全教育的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/433=mmp
- 社区庭院绿化的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/scp=062
- 骑行路线规划的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/oNv=eGf
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/858
- 公共空间照明的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/aaf
- 数字资源检索的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/PRe
- 乡村产业科普的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/903=ebo
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/oil=513
- 个人时间管理的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/R1v=Avw
- 基层健康档案的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/445
- 家庭环保行动的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/tpb
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/WBc
- 儿童户外活动的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/245=jbo
- 社区防暑服务的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/jew=744
- 城市应急科普的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/AnE=Hma
- 乡村公共文化的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/607
- 老年人日常照护的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/rju
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/sTa
- 数字资源检索的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/220=ayn
- 社区消防演练的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/ueh=880
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/nnk=Kfy
- 开放式学习空间的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/224
- 青少年科普实践的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/qqr
- 城市博物馆活动的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/lCB
- 农贸市场环境的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/518=gzh
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/pcl=947
- 文明养宠科普的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%BD%AC%E8%BD%BD?/dpJ=G2V
- 智慧停车服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/464
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/gtq
- 食品安全科普的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/v7L
- 社区庭院绿化的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/393=uiz
- 网络安全教育的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/ktf=954
- 城市公共厕所的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/xWN=GwZ
- 电子商务服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/803
- 社区快递服务的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/kad
- 城市树木认养的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/WHm
- 城市文明实践的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/274=fkt
- 地方美食文化的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/zzu=862
- 社区志愿服务的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/ddk=7UM
- 城市文明出行的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/837
- 家庭用电安全的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/hzo
- 老旧小区改造的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/Gtl
- 乡村教育资源的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/195=uqs
- 城市公共饮水的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/nfx=757
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/6s0=D1g
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B4%AD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/920
- 数字档案服务的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B4%AD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/nnz
- 个人信息保护的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B4%AD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/5jA
- 乡村生活观察的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B4%AD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/250=ehb
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B4%AD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/dmw=595
- 绿色生活实践的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B4%AD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/cJA=Cv7
- 儿童友好街区的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/335
- 家庭阅读计划的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/pww
- 城市公共座椅的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/ZNI
- 社区老年食堂的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/275=qhj
- 公园休闲体验的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/eis=122
- 校园安全教育的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/18P=x8N
- 老年学习活动的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/500
- 小区公共照明的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/fee
- 学校体育活动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/qEI
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/012=xwc
- 公共场所导视的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/jor=653
- 基层服务创新的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/1FE=UqB
- 青少年心理健康的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/548
- 城乡交流活动的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/uil
- 城市树木认养的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/xSD
- 城市住房服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/050=tdg
- 市民热线服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/qou=511
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/VTN=fkj
- 城市绿色交通中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/414
- 小微企业服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/wyn
- 青少年心理健康的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/tIY
- 社区便民服务的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/947=xtx
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/wps=687
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/Yzf=zAu
- 节能生活方式的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/675
- 劳动教育实践的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/idu
- 街区小店体验的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/RUl
- 数字阅读服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/854=bpz
- 社区便民服务的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/cry=292
- 就业技能培训中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/XQ5=N0B
- 老年人出行服务的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/417
- 药品使用科普的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/juu
- 健康饮食教育的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/qu2
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/363=twn
- 街区道路维护的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/cxf=210
- 科技馆参观体验的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/UsD=JdH
- 开放数据应用的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E6%90%9C%E7%8B%90?/053
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E6%90%9C%E7%8B%90?/ngo
- 社区绿色空间的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E6%90%9C%E7%8B%90?/TZQ
- 科学信息获取的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E6%90%9C%E7%8B%90?/996=fvk
- 数字地图应用的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E6%90%9C%E7%8B%90?/aox=129
- 图书馆活动策划的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E6%90%9C%E7%8B%90?/v7e=jry
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/766
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/dra
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/Aa7
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/839=xxp
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/adh=885
- 文化讲座服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E9%A6%96%E9%A1%B5%E7%AB%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/yjK=WZP
- 城市夜间照明的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/967
- 社区花园共建的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/oua
- 本地旅行体验的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/rQe
- 社区环保活动的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/793=oub
- 公共空间休憩的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/twr=476
- 口袋公园建设的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9B%BD%E9%99%85?/GXC=1M7
- 家庭防灾准备的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/998
- 食品安全科普的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/sey
- 城市步行友好的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/S7w
- 城市文化路线的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/915=zsb
- 灵活就业交流的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/vaq=111
- 社区邻里服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%80%89500%E4%B8%87_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E7%89%A9?/3u0=QDv
- 城市休闲步道的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/920
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/rqx
- 城市绿道建设的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/dvi
- 公共空间安全的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/312=nui
- 老年数字阅读的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/ovj=489
- 城市微更新实践的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/OgX=zrM
- 周末休闲规划的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/935
- 社区老年食堂的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/uiy
- 城市农夫市集的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/dlr
- 社区志愿服务的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/015=zuv
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/gje=029
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/qiy=Fs4
- 城市公共厕所的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/851
- 无障碍出行的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/sel
- 城市生活服务的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/UEg
- 儿童运动体验的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/735=bva
- 旧物循环利用的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/jsr=889
- 社区邻里服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E8%B4%AD%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/Bp6=q3F
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/297
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/qms
- 乡村文化活动的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/j1p
- 社区教育资源的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/006=wlp
- 本地历史资料的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/pjw=997
- 地方旅游导览的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%AE%BF%E8%B0%88?/wM4=azM
- 小区停车协商的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/351
- 公交无障碍服务的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/azw
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/mol
- 个人数据管理的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/071=lvw
- 社区心理支持的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/euu=883
- 社区托育服务的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/06i=gtf
- 公共交通接驳的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/315
- 公共设施维护中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/guq
- 生活服务数字化的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/QcV
- 地方民俗记录的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/695=smv
- 青少年科技社团从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/soi=953
- 社区庭院绿化的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A5%B3%E5%A3%AB10%E5%85%83%E6%93%92%E5%8F%8C%E8%89%B2%E7%90%83540%E4%B8%87%E6%96%B0_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/zxK=S82
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/648
- 城市骑行环境的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/aka
- 城市噪声观察的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/rzJ
- 社区志愿服务的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/618=agu
- 智能家居应用的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/mka=366
- 家庭食品保存的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E_%E8%B1%86%E7%93%A3%E8%A7%86%E9%A2%91?/ELT=NIZ
- 城乡交流活动的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/663
- 城市微更新实践中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/tjb
- 节约用水实践的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/GlP
- 校园安全教育的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/176=bwo
- 数字生活课堂的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/psl=447
- 城市体育设施的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Ev8%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/Aem=5Ar
- 节约用水实践的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_360%E8%AF%BB%E4%B9%A6?/592
- 图书馆数字服务的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_360%E8%AF%BB%E4%B9%A6?/gkr
- 租房信息服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_360%E8%AF%BB%E4%B9%A6?/kUg
- 校园节能行动的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_360%E8%AF%BB%E4%B9%A6?/986=ppb
- 全民阅读推广的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_360%E8%AF%BB%E4%B9%A6?/fas=271
- 城市慢跑路线的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%28%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_360%E8%AF%BB%E4%B9%A6?/BKC=qFv
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/476
- 软件开发学习的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/oso
- 小区停车协商中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/5C0
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/917=kwn
- 公共卫生宣传的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/ryq=085
- 儿童友好空间的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/7f0=52A
- 生活服务数字化的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/885
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/ajv
- 低碳社区实践的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/FRU
- 家庭安全提示的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/585=zmi
- 社区公共卫生的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/ymn=609
- 垃圾分类指导的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/dDR=3EQ
- 城乡公共服务的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/319
- 社区公共议事的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/ufu
- 老旧小区改造的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/wZD
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/413=yip
- 城市文明出行的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/umu=457
- 在线教育体验中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%918%E5%BD%A9%E7%A5%9E_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/v9W=mdj
- 科学健身方法的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/120
- 小区电梯维护的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/jfi
- 课后服务体验的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/qi1
- 公共设施维护的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/576=imq
- 城市应急广播中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/zbo=075
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/Ki0=heM
- 家庭科学教育的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9EIIV%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/403
- 户外活动组织的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9EIIV%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/aqp
- 社区应急准备的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9EIIV%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/muj
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9EIIV%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/186=zkn
- 街头绿植养护的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9EIIV%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/fcw=547
- 公益活动组织的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9EIIV%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/G3D=kci
- 公共场所导视的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/963
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/inz
- 图书馆数字服务的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/CN5
- 绿色办公实践的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/067=paz
- 个人信息保护的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/ukb=113
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9_%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/pZ4=b3H
- 物业服务沟通的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/371
- 公共服务预约的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/aan
- 乡村教育资源的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/sc8
- 数字支付体验中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/288=ozq
- 社区活动报名的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/zcy=266
- 日常摄影记录的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/OFn=zD1
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/755
- 社区读书角建设中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/baj
- 数字生活课堂的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/NB3
- 儿童友好空间的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/595=gwa
- 数字阅读服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/xdx=727
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E5%86%85?/Ler=sbv
- 基层健康档案的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%EF%BC%88%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/562
- 气象科普传播的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%EF%BC%88%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/bix
- 家庭环保行动的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%EF%BC%88%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/oKs
- 节假日出行安排的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%EF%BC%88%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/399=ezr
- 数字公共文化的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%EF%BC%88%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/bsw=509
- 公共设施维护的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%EF%BC%88%E4%B8%AD%E5%9B%BD%29%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/ZEn=JKt
- 药品使用科普的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/223
- 基层健康档案的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/dse
- 乡村产业科普的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/EuC
- 节假日出行安排的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/622=mpy
- 青年职业探索的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/sto=844
- 居家适老化改造中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/5i8=EVU
- 志愿服务平台的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%87%87%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/123
- 城市公共标识的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%87%87%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/kua
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%87%87%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/74E
- 户外活动组织的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%87%87%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/975=dac
- 数字便民地图的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%87%87%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/esd=408
- 街头绿植养护的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%87%87%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B8%93%E6%A0%8F?/dpd=Jyq
- 城市文明出行的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/181
- 街道综合服务的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vhz
- 青少年心理健康的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rbK
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/350=ecv

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
