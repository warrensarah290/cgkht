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

- 家庭阅读计划的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/252
- 社区手工活动的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/gyu
- 机器人科普活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/cyZ
- 本地消费场景的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/188=qcq
- 健康饮食教育的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/wgo=953
- 校园节能行动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/l5X=RVO
- 全民健身活动的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/588
- 社区垃圾分类的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/ttp
- 在线学习体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/lCv
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/246=len
- 数字档案服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/zwl=147
- 地方文化传播的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%B9%A6%E7%94%BB?/nps=Mra
- 乡村产业科普的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/214
- 社区公共议事的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/sae
- 儿童安全出行的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/468
- 志愿服务平台的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/360=ecu
- 社区学习活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/rtz=998
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/hYH=7c7
- 邻里互助活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/502
- 健康步道使用的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/cal
- 社区公共议事中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/0Gv
- 社区环保活动的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/273=kcm
- 老旧小区改造的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/tdo=402
- 城市博物馆服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/czU=cfz
- 家庭养老规划的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/842
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/hlm
- 日常摄影记录的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/JVu
- 城市人文观察的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/583=deq
- 食品配送体验中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/vza=505
- 青年职业探索的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/buv=yGL
- 小区公共照明的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/288
- 农产品消费体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/bfb
- 儿童阅读角的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/0eB
- 儿童运动体验的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/930=wgc
- 公园休闲体验的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/aio=505
- 科学信息获取的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/H0M=hs9
- 家庭科学教育的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/221
- 家庭健康管理的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/zyy
- 科学运动指导的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/InB
- 软件开发学习的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/676=qsn
- 便民信息查询的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ayr=385
- 网络安全教育的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/98J=5aJ
- 小区电梯维护的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/875
- 食品配送体验的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/zzm
- 社区交通安全的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/xw2
- 城市文明出行的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/844=ksm
- 城市适老服务的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/mgs=799
- 社区菜市场服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/Y8v=hvC
- 社区绿色空间的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/053
- 家庭健康科普中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/hzs
- 网络安全教育的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/OWk
- 生成式工具使用的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/298=wcj
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/mmo=303
- 数字资源检索的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/oBV=t6t
- 劳动教育实践的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/943
- 消防知识宣传的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/tpn
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/cOF
- 志愿服务平台的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/910=tqj
- 儿童户外活动的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/vxh=375
- 居家适老化改造的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/u3z=Ir1
- 数据分析入门的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/556
- 城市便民驿站的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/tjh
- 社区商业活力的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/x68
- 地方旅游导览中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/897=qur
- 社区学习活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/psa=534
- 劳动教育实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/6G8=inq
- 本地历史资料的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/844
- 小区电梯维护的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/sse
- 居家适老化改造的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/PxC
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/903=snv
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/ons=312
- 社区休闲设施的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/eFu=NoF
- 家庭健康管理的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/612
- 图书馆活动策划的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/fby
- 绿色快递包装的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/6Q8
- 本地旅行体验的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/021=fdj
- 乡村文化活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/kdk=880
- 城乡公共服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/uog=J84
- 地方民俗记录的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/516
- 绿色快递包装的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/fao
- 旧物循环利用的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/jHK
- 数字生活课堂的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/126=hee
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/vfs=691
- 公共交通接驳中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/iMs=o1f
- 城市公共饮水的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/122
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/oih
- 青少年科技社团的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/JvD
- 城市适老服务的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/960=kiq
- 公共服务沟通的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/dfi=643
- 科技馆参观体验的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/U6h=LVq
- 社区交通安全的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/877
- 社区运动空间的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/boj
- 在线教育体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/8Rw
- 数字设备回收的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/696=hgt
- 家庭志愿活动的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/wnh=831
- 家庭照护支持的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%9B%E6%8A%95?/dYQ=tXu
- 数字创意课程的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/546
- 公共空间照明的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/vsi
- 科普展览体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/OwG
- 基层健康档案的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/729=trm
- 绿色出行服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/gzy=041
- 社区设施共享的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/D3w=Cxg
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/539
- 基层健康服务的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/jnr
- 小微企业服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/urD
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/576=fev
- 音乐欣赏活动的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/aak=674
- 数字阅读服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E5%8C%96?/S6t=3vO
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/383
- 在线教育体验的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/ezm
- 城市展览体验的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/tSe
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/772=olg
- 地方美食文化的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/vsw=451
- 光伏知识科普中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/r6C=wXt
- 老年运动活动的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/258
- 社区信息发布的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/rfr
- 社区艺术活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/QpH
- 社区教育资源的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/535=jxv
- 智能手机助老的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/hgj=803
- 数字课堂应用的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_58%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/QTu=LOG
- 公共服务咨询的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_758cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/894
- 社会体育指导的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_758cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/cas
- 文明养宠科普的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_758cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/JxO
- 城市公共空间的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_758cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/857=qsp
- 文明养宠科普中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_758cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/bvg=151
- 校园安全教育的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_758cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/fIO=v8z
- 城市社区治理的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/526
- 社区安全巡查的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/vgz
- 家庭环保行动的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/WMy
- 生活垃圾减量的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/385=stp
- 城市博物馆服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/out=644
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/klu=dwo
- 城市文明出行的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_758cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/867
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_758cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/wps
- 校园节能行动的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_758cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/Rfz
- 社区停车服务的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_758cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/530=fih
- 城市基础设施的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_758cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/guq=205
- 软件开发学习的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_758cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/r3V=B5O
- 街区小店体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_758cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/748
- 社区科普课堂的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_758cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/kcm
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_758cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/Jda
- 人工智能科普的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_758cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/961=xrl
- 城市夜间生活的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_758cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/bdu=012
- 城市微更新实践的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_758cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/Nmq=biZ
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_758cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/829
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_758cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/opu
- 社区法律科普的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_758cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/P9R
- 食品安全科普的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_758cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/858=fao
- 数字公共文化的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_758cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/gew=489
- 社区邻里服务的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_758cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E8%AE%BA?/spt=KZj
- 乡村公共阅读的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_758cc-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/991
- 街头绿植养护的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_758cc-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/iyr
- 社区环保活动的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_758cc-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/moI
- 市民意见收集的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_758cc-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/617=xxb
- 节能家电使用的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_758cc-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/jck=632
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_758cc-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%9B%B2%E8%89%BA?/V5V=umd
- 公共服务沟通的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_758cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/485
- 城市应急科普的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_758cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/yij
- 公共文化活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_758cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/mYz
- 城市基础设施的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_758cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/349=wth
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_758cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/isw=175
- 公共文化活动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_758cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/kuc=Aaf
- 街道综合服务的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_758cc-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/661
- 公共空间照明的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_758cc-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/imh
- 社区宠物管理的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_758cc-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/gzN
- 乡村公共服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_758cc-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/273=ejp
- 城市应急科普的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_758cc-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/afk=620
- 终身学习资源的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_758cc-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/1kW=ySg
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_758cc-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/215
- 市民意见收集的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_758cc-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/abd
- 社区心理支持的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_758cc-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/eqC
- 全民健身活动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_758cc-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/205=ylz
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_758cc-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/hgr=063
- 全民阅读推广的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_758cc-%E5%AE%98%E7%BD%91_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/FUG=vtZ
- 城市生活服务的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_758cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/748
- 老年人出行服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_758cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/loc
- 公共卫生宣传的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_758cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/1gy
- 家庭园艺实践的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_758cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/727=zpc
- 志愿者培训交流的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_758cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/pei=978
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_758cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/BIi=RZG
- 居民健康教育的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_758cc-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/182
- 便民信息查询的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_758cc-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/ulq
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_758cc-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/RuO
- 开源技术交流的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_758cc-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/319=wqw
- 城市绿色交通的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_758cc-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/dbj=884
- 城市公共标识的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_758cc-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/JP7=ad8
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_758cc-APP_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/530
- 青少年户外教育的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_758cc-APP_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/qmx
- 数字学习资源的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_758cc-APP_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/Xtu
- 绿色办公实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_758cc-APP_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/309=nmy
- 旧物循环利用的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_758cc-APP_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/mrg=819
- 网络信息辨识的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_758cc-APP_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/dcQ=XWP
- 读书会组织从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/268
- 社区活动报名的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/gio
- 文化场馆预约的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/sR0
- 数字创意课程的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/445=tdi
- 健康饮水科普的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/mkw=430
- 数字生活课堂的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/YWh=w0V
- 青年职业探索的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_758cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/660
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_758cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/fwj
- 运动安全知识的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_758cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/wKr
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_758cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/662=zmh
- 街区更新实践的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_758cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/pzs=924
- 社区托育服务的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_758cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Myn=v4u
- 公共空间休憩的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/090
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/afe
- 志愿服务平台的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/EbV
- 城市生活服务的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/702=hrw
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/tyy=347
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/o1y=coY
- 家庭急救准备的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758cc-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/468
- 消防知识宣传的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758cc-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/vvy
- 社区家校合作的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758cc-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/H3E
- 社区安全巡查的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758cc-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/892=cgq
- 家庭食品保存的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758cc-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/sxq=256
- 社区科普课堂的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758cc-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/xaf=Eoy
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/386
- 非遗体验活动的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/keo
- 生活技能分享的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/zDB
- 数字生活课堂的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/373=ycw
- 公共设施使用的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/yqs=064
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/K7e=wXV
- 节气饮食文化的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_758cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/015
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_758cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/ddv
- 老年人文化生活的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_758cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/5Nw
- 青年职业探索的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_758cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/293=nnx
- 城市休闲步道的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_758cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/llh=097
- 城市应急科普的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_758cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E4%BC%97%E6%B5%8B?/J7N=pd9
- 基层医疗预约的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/655
- 灵活就业交流的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/zmz
- 校园阅读活动的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/KZV
- 在线学习体验的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/183=jfr
- 城市绿道建设中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/cac=692
- 城市生活记录的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_758cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/gKQ=e2a
- 社区活动策划的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_758cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/578
- 公园休闲体验的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_758cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/ftf
- 家庭饮食安排的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_758cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/ntx
- 城市生活记录的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_758cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/988=jce
- 城市微更新实践的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_758cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/kwm=310
- 社区休闲设施的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_758cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/x65=B2y
- 旧物循环利用的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_758cc-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/605
- 家庭阅读计划的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_758cc-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/yme
- 市民热线服务的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_758cc-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/jGx
- 网络信息辨识的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_758cc-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/547=fmw
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_758cc-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/nqh=092
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_758cc-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/3sK=lKT
- 运动安全知识的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_758cc-%E5%AE%98%E6%96%B9_360%E6%BC%AB%E8%AF%84?/742
- 公共空间导览的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_758cc-%E5%AE%98%E6%96%B9_360%E6%BC%AB%E8%AF%84?/nqe
- 家庭运动计划的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_758cc-%E5%AE%98%E6%96%B9_360%E6%BC%AB%E8%AF%84?/vTh
- 绿色出行服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_758cc-%E5%AE%98%E6%96%B9_360%E6%BC%AB%E8%AF%84?/056=cws

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
