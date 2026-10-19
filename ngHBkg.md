# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 社区生活指南的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/068
- 药品使用科普的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/ryu
- 儿童运动体验的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/t6c
- 居家防滑改造的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/287=wok
- 社区公共餐饮的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/dpv=169
- 城市住房服务的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%8F%B7%E5%A4%96?/9lH=pHN
- 乡村教育资源的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/530
- 儿童安全出行的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/cnl
- 社区商业活力的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/yXU
- 家庭园艺实践的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/804=fxg
- 青少年科普实践的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/iel=797
- 应急物资管理的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/6XJ=Sbu
- 食品安全科普的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/367
- 社区手工活动的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/gsi
- 公共交通接驳中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/R3J
- 口袋公园建设的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/747=dxu
- 社区快递服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/bui=223
- 城市便民驿站的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/AWP=m8H
- 公共场所导视的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/763
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/lav
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/Nqu
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/201=eoj
- 急救知识普及的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/rsy=321
- 文明养宠科普的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/frH=DGh
- 社区知识分享的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97?/641
- 老年学习活动的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97?/xge
- 远程协作工具的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97?/HcW
- 无障碍出行的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97?/932=wrv
- 家庭节能实践的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97?/jmn=913
- 城市慢行系统的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97?/mw0=ej6
- 青少年户外教育的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/872
- 家庭安全提示的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/crz
- 数字学习资源的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/HKi
- 公交站点体验的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/032=wwr
- 老年智能设备的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/fwx=695
- 在线学习体验的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/WD7=70M
- 租房信息服务的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/039
- 社区庭院绿化的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/ntx
- 乡村文化活动的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/IKm
- 公共空间照明的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/037=nfa
- 城市共享单车的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/rly=475
- 急救知识普及的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/a2X=QYN
- 公交无障碍服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/866
- 城市休闲步道中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/bjh
- 数字学习资源的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ID8
- 社区花园共建的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/656=vmt
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ynk=179
- 社区法律科普的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/wzD=BAD
- 公共服务评价的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BD%AC%E8%BD%BD?/700
- 小区停车协商的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BD%AC%E8%BD%BD?/xns
- 社区活动策划的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BD%AC%E8%BD%BD?/KLz
- 绿色快递包装的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BD%AC%E8%BD%BD?/128=uja
- 生活垃圾回收的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BD%AC%E8%BD%BD?/nmg=520
- 社区学习活动的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E8%BD%AC%E8%BD%BD?/uM3=AE5
- 社区儿童活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/247
- 开放式学习空间的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/hby
- 乡村公共服务中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/opA
- 健康信息获取的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/120=lia
- 老年人文化生活的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/vkj=487
- 城市慢跑路线的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/EJi=OZH
- 绿色生活实践的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/741
- 老年学习活动的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/mzn
- 城市住房服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/TDl
- 健康步道使用的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/564=rfg
- 农产品消费体验的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/abw=027
- 节气饮食文化的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/UaF=e9J
- 开放数据应用的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/757
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/xnt
- 公园休闲体验的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/VZL
- 数字学习资源的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/267=zts
- 科学信息获取的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/mxb=466
- 社区知识分享的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/VY6=jGJ
- 智慧停车服务的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/716
- 便民信息查询的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/ktk
- 生成式工具使用的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/nNa
- 老年运动活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/642=yqv
- 街区道路维护的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/jdu=057
- 城市微更新实践的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/KbD=iC5
- 家庭食品保存的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/693
- 科普展览体验的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/eke
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/QPQ
- 气象科普传播的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/347=xva
- 气象科普传播的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/sjn=190
- 智慧停车服务的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E7%83%AD%E6%A6%9C?/x04=t2c
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/660
- 青少年心理健康的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/hgd
- 个人信息保护的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/xYK
- 地方戏曲体验的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/107=smg
- 口袋公园建设的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/cgn=148
- 课后服务体验的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/Rmy=ne6
- 数字政务体验的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/954
- 公园亲子设施的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/sye
- 社区知识分享的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/EbB
- 老年人文化生活的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/734=yle
- 城市空气科普的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/xgm=460
- 灵活就业交流的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/gn5=fNt
- 社区家校合作的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/720
- 社区邻里服务的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/ftw
- 节能生活方式的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/gfY
- 个人信息保护中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/398=afn
- 公园亲子设施的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/qkd=964
- 气象科普传播的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/zK2=6G5
- 智能家居应用的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/693
- 社区绿色空间的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/dnj
- 乡村文化空间的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/i11
- 数字公共文化的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/270=pgi
- 开放数据应用的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/kfj=343
- 口袋公园建设的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/6p1=jgc
- 社区休闲设施的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/906
- 儿童阅读角的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/sxq
- 智慧停车服务的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/LXO
- 便民服务窗口的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/957=zng
- 户外活动组织的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/zzc=645
- 健康信息获取的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%AE%BF?/tNq=AHk
- 家庭运动计划的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/451
- 社会体育指导的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/sxo
- 职业技能学习的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/0qH
- 图书馆数字服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/557=zkp
- 公共空间安全的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/imd=140
- 文化场馆预约的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/171=lRb
- 基层健康档案的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/190
- 街区绿化养护的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/til
- 城市基础设施的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/ig9
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/358=vpr
- 社区阅读服务的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/hdr=329
- 社区体育组织的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/aDT=iPh
- 乡村产业科普的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/386
- 校园安全教育的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/sew
- 非遗体验活动的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/0K4
- 便民服务窗口的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/289=mka
- 远程协作工具的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/mkg=413
- 社区信息发布的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/yCE=fXA
- 公共服务数字化的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/349
- 家庭健康管理的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/rid
- 地方旅游导览从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/JjF
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/125=ycb
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/kkx=490
- 图书馆活动策划的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%9B%86?/zcj=4CL
- 公园亲子设施的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/652
- 职业技能学习的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/fyk
- 公共空间导览的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/hYP
- 非遗课堂体验的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/138=bja
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/hkh=089
- 城市步行环境的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/syJ=b2h
- 开放数据应用的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/659
- 物业服务沟通的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/qty
- 社区垃圾分类的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/Xww
- 机器人科普活动的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/247=xos
- 人工智能科普的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/vea=212
- 口袋公园建设的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/E1E=GDF
- 城市公共标识中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/887
- 社区共享书架的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/fcx
- 邻里互助活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/bF0
- 消防知识宣传的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/628=xnq
- 街道综合服务的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/duz=558
- 绿色校园实践的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%AF%8D%E5%A9%B4?/lHL=taU
- 开源技术交流的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/225
- 读书会组织的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/bat
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/Swl
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/318=ezl
- 老年人出行服务的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/fol=820
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/yw6=8am
- 校园阅读活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/818
- 社会体育指导的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/kmp
- 城市微更新实践的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/x2k
- 城市建设科普的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/005=zcm
- 节能家电使用的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/pgx=196
- 光伏知识科普中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/zB6=gx4
- 智能家居应用的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/670
- 社区共享书架的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/ttc
- 老年友好服务的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/hFs
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/646=kxy
- 老年数字阅读的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/niz=999
- 老年友好服务的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/1jq=vGR
- 社区宠物管理的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/645
- 老年友好服务的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/wgt
- 社区活动报名的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/bIt
- 老年友好服务的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/061=vxq
- 社区菜市场服务的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/xfg=921
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/ge3=A7p
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/310
- 社区读书角建设的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/vha
- 乡村生态观察的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/N6O
- 急救知识普及的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/986=pih
- 城市骑行环境的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/syv=594
- 节能生活方式的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/1PI=Xot
- 小微企业服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/499
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/dce
- 传统节日科普的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/Jdz
- 节假日出行安排中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/866=iit
- 网络安全教育的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/pfk=322
- 青少年户外教育的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/VTr=JGE
- 社区科普课堂的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/164
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/jpa
- 社区活动策划的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/dGv
- 数字生活课堂的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/908=cbg
- 创业经验分享的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/wch=118
- 社区公共议事的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/LBj=qQo
- 城市体育设施的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/632
- 远程协作工具的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/pfx
- 城市体育设施的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/woH
- 垃圾分类指导的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/677=mxp
- 生活技能分享的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/sma=839
- 基层健康档案的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%86%9B%E4%BA%8B?/Xbh=ekc
- 城市体育设施的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/958
- 安全出行教育的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/yek
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/PuC
- 个人时间管理的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/681=oxc
- 城市建设科普的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/iop=784
- 社区共享书架的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/JG7=xBx
- 城市夜间生活的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/200
- 市民意见收集的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/swr
- 城市步行环境的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/vUQ
- 社区信息发布的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/152=qvw
- 信息无障碍体验的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/ych=175
- 科技馆参观体验的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/I7D=s6H
- 家庭节能实践的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/154
- 健康饮水科普的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/wdo
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/OhP
- 公共服务指南的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/633=mos
- 城市公共厕所的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/wpy=584
- 电子商务服务的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/rZW=XDP
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/295
- 生成式工具使用的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/ecx
- 乡村公共文化的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/QJC
- 社区防暑服务的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/395=cxj
- 家庭园艺实践的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/hig=593
- 社区托育服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%AF%BB%E6%8A%A5?/Kcs=KfN
- 科学信息获取的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/918
- 城市噪声观察的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/cds
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/ByP
- 公共卫生设施的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/870=rvv
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/shp=959
- 科学运动指导的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/5at=YDX
- 城市夜间照明中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/210
- 远程协作工具的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/ilv
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/qAc
- 休闲运动入门的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/553=rlu
- 便民服务地图的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/zfk=928
- 节假日出行安排的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BB%BC%E5%90%88-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/ye5=fw0
- 社区故事采集的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/893
- 城市公共空间的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/ryj
- 城市游园体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/HXG
- 城市文明出行的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/135=yns
- 数字政务体验的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/kpy=820
- 图书馆活动策划的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/uIj=7Cx
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/662
- 公共空间安全的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/dbu
- 家庭照护支持的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/JPi
- 小区电梯维护的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%BD%91%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/044=lwh

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
