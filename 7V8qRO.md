# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 开放数据应用中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%8E%86%E5%8F%B2?/4tD
- 社区消防演练的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%8E%86%E5%8F%B2?/978=tds
- 青少年户外教育的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%8E%86%E5%8F%B2?/sxy=847
- 青少年科普实践的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%8E%86%E5%8F%B2?/Qc7=uov
- 公共服务咨询的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/377
- 灵活就业交流的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/gzq
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/vTo
- 城乡公共服务的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/309=mue
- 城市文明实践的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/mob=434
- 智能家居应用的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/KVL=E8V
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/514
- 公共交通接驳的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/vsp
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/6iY
- 社区协商议事的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/565=ezk
- 公共空间休憩的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/jtj=651
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8D%9A%E5%AE%A2?/ouw=eAs
- 在线教育体验的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/461
- 智能家居应用的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/qvx
- 社区运动空间的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/Q41
- 城市骑行环境的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/262=paa
- 绿色校园实践中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/qxl=879
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/iWX=Fzl
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/230
- 志愿服务平台的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/moh
- 绿色生活实践的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/Tuo
- 公共空间照明的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/984=ovn
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/fqm=866
- 环境教育课程的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/9qw=8Lh
- 家庭食品保存的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/373
- 城市体育设施的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/rxz
- 社区法律科普的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/8fn
- 小区停车协商的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/704=awn
- 社区科普课堂的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/wah=465
- 城市公共标识的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/ayl=7aM
- 乡村生态旅游的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/766
- 居家防滑改造的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/cgr
- 节日文化体验的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/L3y
- 口袋公园建设的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/675=can
- 城市步行友好的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/ybb=412
- 基层健康档案的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/WMU=zTz
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/539
- 社区科普课堂的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/esa
- 社区健康讲座的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/VpA
- 绿色建筑理念的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/107=qgn
- 城市绿道建设的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/oay=957
- 数字政务体验的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_36%E6%B0%AA%E5%8D%83%E5%B8%86?/xvj=P0k
- 公园休闲体验的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/458
- 户外活动组织的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/rkm
- 家庭健康科普的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/02v
- 基层服务创新的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/375=nnr
- 家庭网络使用的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/qyk=881
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/j6i=Hzg
- 社区心理支持的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/128
- 开源技术交流的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/fak
- 城市夜间照明的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/adQ
- 职业技能学习的流程优化思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/766=gmq
- 日常摄影记录的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/tlq=199
- 科学观察活动的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/IYC=3j9
- 运动安全知识的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/599
- 人工智能科普的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/nll
- 周末休闲规划的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/FYf
- 城市便民驿站的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/201=jzi
- 城市夜间照明的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/wzw=301
- 公共卫生设施中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/AyQ=0RJ
- 家庭阅读计划的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/936
- 文化场馆预约的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/bfq
- 休闲运动入门的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/uyd
- 城市空气科普的服务细节记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/161=dfc
- 老年人日常照护的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/yio=567
- 家庭阅读计划的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/fVP=VAK
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/382
- 地方美食文化的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/sip
- 非遗课堂体验的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/rqe
- 社区公共议事的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/358=yvr
- 城市微更新实践中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/lda=064
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/jcT=kkX
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/486
- 城市公共自行车的服务质量观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/dow
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/ZSC
- 本地消费场景的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/372=sql
- 社区绿色空间的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/azm=660
- 社区邻里服务的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/OZz=5Et
- 居家适老化改造的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/577
- 绿色办公实践的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/hji
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/WIQ
- 小区公共照明的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/931=ldr
- 网络安全教育的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/siy=479
- 社区信息发布中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/5Wj=f1S
- 终身学习资源的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/704
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qcp
- 邻里互助活动的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zNP
- 农村环境治理的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/171=ihm
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/aec=658
- 绿色校园实践的资源整合思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%AE%8F%E4%B8%9A%E8%B4%A2%E7%BB%8F?/G8a=xIw
- 社区法律科普的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/038
- 社区环保活动的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/vol
- 城市游园体验的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/7BY
- 科学运动指导的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/317=swy
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/wlt=005
- 小区公共照明的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/4sO=Y9A
- 社区商业活力的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/166
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/qyh
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/yZQ
- 青年志愿活动的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/738=wjm
- 社区便民集市的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/sdv=327
- 个人时间管理的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/Rzi=xUx
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_APP%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/020
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_APP%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/ldf
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_APP%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/Sjg
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_APP%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/292=foi
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_APP%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/ktc=682
- 家庭节能实践的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_APP%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/5dC=kLV
- 城乡交通衔接的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BF%AB%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/501
- 青少年户外教育的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BF%AB%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/fte
- 社区养老服务的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BF%AB%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/3Nl
- 科学运动指导的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BF%AB%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/862=gmo
- 科学运动指导的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BF%AB%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/dmi=531
- 数字创作工具的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BF%AB%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/UJG=l3p
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/130
- 节约用水实践的服务范围梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/lvt
- 乡村公共文化的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/jo7
- 农村环境治理的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/936=xmn
- 信息无障碍体验的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/mtv=201
- 街区小店体验的活动体验回顾 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/7fi=Hy6
- 小区停车协商的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E7%89%88%E8%8B%B9%E6%9E%9C_360%E5%AE%A0%E7%89%A9?/171
- 家庭运动计划的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E7%89%88%E8%8B%B9%E6%9E%9C_360%E5%AE%A0%E7%89%A9?/cjs
- 社区活动策划的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E7%89%88%E8%8B%B9%E6%9E%9C_360%E5%AE%A0%E7%89%A9?/Jw4
- 绿色消费选择的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E7%89%88%E8%8B%B9%E6%9E%9C_360%E5%AE%A0%E7%89%A9?/259=twq
- 家庭养老规划的便民做法梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E7%89%88%E8%8B%B9%E6%9E%9C_360%E5%AE%A0%E7%89%A9?/htx=424
- 乡村教育资源的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E7%89%88%E8%8B%B9%E6%9E%9C_360%E5%AE%A0%E7%89%A9?/kh0=uY2
- 数字档案服务的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/478
- 邻里共享空间的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/kji
- 社区慢性病防控的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/Jbc
- 家庭安全提示的常见误区提醒 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/415=dqy
- 应急物资管理的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/ucn=240
- 地方民俗记录的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/jso=id4
- 街区更新实践的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E7%9A%84%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/552
- 社区故事采集的长期维护要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E7%9A%84%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/glj
- 社区活动策划的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E7%9A%84%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/JUa
- 城市社区治理的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E7%9A%84%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/674=ehb
- 社区商业活力的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E7%9A%84%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/ykx=277
- 社区家政服务的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E7%9A%84%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/oE3=WXv
- 通勤路线规划的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/520
- 城市社区治理的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/ryk
- 药品使用科普的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/3Gx
- 志愿者培训交流的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/048=uoe
- 校园节能行动的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/jwm=362
- 校园节能行动的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/X1F=658
- 城市社区治理的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%9C%AD%E8%AE%B0?/490
- 骑行路线规划的线下体验记录 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%9C%AD%E8%AE%B0?/cqw
- 家庭科学教育的家庭实践清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%9C%AD%E8%AE%B0?/Jlh
- 绿色建筑理念的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%9C%AD%E8%AE%B0?/588=mbl
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%9C%AD%E8%AE%B0?/aib=166
- 节气饮食文化的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E6%9C%AD%E8%AE%B0?/Mbr=HHW
- 公共服务咨询的便利性观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E5%88%97%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/433
- 健康饮水科普的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E5%88%97%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/yav
- 药品使用科普的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E5%88%97%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/LFY
- 公共服务数字化的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E5%88%97%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/862=dvp
- 市民意见收集的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E5%88%97%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/wvy=419
- 全民健身活动的日常管理方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E5%88%97%E8%A1%A8_%E7%9F%A5%E4%B9%8E%E4%BC%97%E6%B5%8B?/ijH=r9e
- 节假日出行安排的基础知识问答 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/932
- 社区知识分享的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/hha
- 家庭节能设备的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/ZC5
- 科技馆参观体验的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/121=sng
- 家庭网络使用的家庭参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/fpr=000
- 城市便民驿站的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/rFm=RhQ
- 通勤路线规划中的沟通与协作 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/081
- 老年人文化生活的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/nmg
- 在线教育体验的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/qJd
- 数字艺术创作的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/364=ask
- 城市社区治理的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/iij=135
- 旧物循环利用的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E4%BA%B2%E5%AD%90?/la1=qvz
- 数字公共文化的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_767app%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/503
- 城市生活记录的协作机制梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_767app%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/scv
- 基层健康档案的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_767app%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/C6o
- 乡村文化活动的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_767app%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/665=wvm
- 街区绿化养护的入门知识整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_767app%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/xmx=705
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_767app%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/4ho=LuM
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E6%89%8B%E6%9C%BA%E6%8C%82%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/093
- 课后服务体验的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E6%89%8B%E6%9C%BA%E6%8C%82%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/hhp
- 城市体育设施的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E6%89%8B%E6%9C%BA%E6%8C%82%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/zqe
- 公共空间导览的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E6%89%8B%E6%9C%BA%E6%8C%82%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/009=zky
- 劳动教育实践的设施维护观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E6%89%8B%E6%9C%BA%E6%8C%82%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/kxw=207
- 校园社团活动的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E6%89%8B%E6%9C%BA%E6%8C%82%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/Dvp=K3m
- 公共空间休憩的组织方法与经验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%80%893%E5%A4%8D%E5%BC%8F%E9%87%91%E9%A2%9D%E5%AF%B9%E7%85%A7%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/368
- 课后服务体验的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%80%893%E5%A4%8D%E5%BC%8F%E9%87%91%E9%A2%9D%E5%AF%B9%E7%85%A7%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/aqe
- 乡村公共阅读的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%80%893%E5%A4%8D%E5%BC%8F%E9%87%91%E9%A2%9D%E5%AF%B9%E7%85%A7%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/oai
- 城市文明实践的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%80%893%E5%A4%8D%E5%BC%8F%E9%87%91%E9%A2%9D%E5%AF%B9%E7%85%A7%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/248=sol
- 劳动教育实践的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%80%893%E5%A4%8D%E5%BC%8F%E9%87%91%E9%A2%9D%E5%AF%B9%E7%85%A7%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/exw=550
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%80%893%E5%A4%8D%E5%BC%8F%E9%87%91%E9%A2%9D%E5%AF%B9%E7%85%A7%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9B%BD%E9%99%85?/Lnh=xS6
- 租房信息服务的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8F%B0%E6%B9%BE%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/093
- 公共空间导览的社区行动案例 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8F%B0%E6%B9%BE%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/lni
- 社区养老服务的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8F%B0%E6%B9%BE%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/3ns
- 社区故事采集的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8F%B0%E6%B9%BE%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/058=eln
- 文明养宠科普的日常使用指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8F%B0%E6%B9%BE%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/wti=118
- 绿色校园实践的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8F%B0%E6%B9%BE%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/679=wzY
- 学校食育活动的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%E8%87%BA%E5%AE%98%E7%B6%B2%E8%BB%9F%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/666
- 城乡交流活动的基础设施观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%E8%87%BA%E5%AE%98%E7%B6%B2%E8%BB%9F%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/cic
- 公共设施使用的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%E8%87%BA%E5%AE%98%E7%B6%B2%E8%BB%9F%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/K8K
- 乡村文化空间的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%E8%87%BA%E5%AE%98%E7%B6%B2%E8%BB%9F%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/615=uai
- 生成式工具使用的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%E8%87%BA%E5%AE%98%E7%B6%B2%E8%BB%9F%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/ebn=645
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%E8%87%BA%E5%AE%98%E7%B6%B2%E8%BB%9F%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/sDi=ctJ
- 老年人文化生活的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E9%80%81%E5%BD%A9%E9%87%91_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/529
- 城市人文观察的执行流程参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E9%80%81%E5%BD%A9%E9%87%91_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/xvz
- 机器人科普活动的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E9%80%81%E5%BD%A9%E9%87%91_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/Lf0
- 家庭环保习惯的学习资源整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E9%80%81%E5%BD%A9%E9%87%91_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/367=uem
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E9%80%81%E5%BD%A9%E9%87%91_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/hme=207
- 儿童友好空间的日常记录与分享 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E9%80%81%E5%BD%A9%E9%87%91_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/Nmq=W2q
- 绿色办公实践的常见问题梳理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/619
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/nim
- 社区便民服务的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/8R2
- 智慧停车服务的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/715=khr
- 公园亲子设施的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/xez=852
- 老年人出行服务的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/lFw=4NO
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83Welcome_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/941
- 骑行路线规划的空间使用体验 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83Welcome_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/szx
- 社区活动报名的公共信息获取方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83Welcome_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/PAA
- 城市展览体验的日常实践笔记 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83Welcome_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/602=cgv
- 低碳社区实践的安全使用提示 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83Welcome_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/eux=624
- 机器人科普活动的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83Welcome_%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/hHF=NjO
- 骑行路线规划的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%8D%83%E5%B8%86?/560
- 骑行路线规划的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%8D%83%E5%B8%86?/gar
- 租房信息服务的数字化应用观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%8D%83%E5%B8%86?/Xkx
- 社区文化传播中的几个关键细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%8D%83%E5%B8%86?/288=xaz
- 社区信息发布的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%8D%83%E5%B8%86?/yxa=803
- 物业服务沟通的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%8D%83%E5%B8%86?/QbQ=OFi
- 社区共享书架的活动组织技巧 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/312
- 音乐欣赏活动的持续改进方向 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/pse
- 市民热线服务的适老服务细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/UL8
- 社区便民集市的使用门槛与改进 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/358=yyo
- 社区科普课堂的居民参与机会 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/pzp=282
- 社区停车服务的公共参与指南 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/dYc=INC
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/782
- 青少年科技社团的实用信息清单 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/mxt
- 社区安全巡查的协商参与方式 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/JT7
- 邻里互助活动的活动策划思路 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/600=poq
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/obc=461
- 老年人出行服务的服务信息整理 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/R5d=fFX
- 本地历史资料的阅读与学习资源 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E9%83%A8%E4%BC%9A%E5%BC%8020%E5%88%86%E9%92%9F%E5%A5%96%E5%90%97_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/788
- 绿色生活实践的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E9%83%A8%E4%BC%9A%E5%BC%8020%E5%88%86%E9%92%9F%E5%A5%96%E5%90%97_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/ygh
- 社区公共卫生的便捷程度观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E9%83%A8%E4%BC%9A%E5%BC%8020%E5%88%86%E9%92%9F%E5%A5%96%E5%90%97_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/wes
- 食品安全科普的绿色实践方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E9%83%A8%E4%BC%9A%E5%BC%8020%E5%88%86%E9%92%9F%E5%A5%96%E5%90%97_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/474=dpj
- 小微企业服务的资源利用方法 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E9%83%A8%E4%BC%9A%E5%BC%8020%E5%88%86%E9%92%9F%E5%A5%96%E5%90%97_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/fjl=602
- 乡村电商实践的参与方式与路径 |来源：https://github.com/harrisonmorgan3/lony/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E9%83%A8%E4%BC%9A%E5%BC%8020%E5%88%86%E9%92%9F%E5%A5%96%E5%90%97_%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/gHq=swA
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_767%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/897
- 家庭健康管理的社区参与观察 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_767%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/rel
- 城乡交流活动的实际需求与回应 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_767%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/bEF
- 社区故事采集的行动步骤参考 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_767%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/761=bcx
- 节约用水实践的空间设计要点 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_767%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/ucv=068
- 社区托育服务的儿童友好细节 |来源：https://github.com/harrisonmorgan3/lony/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_767%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/yoe=clf

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
