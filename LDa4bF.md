# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 人工智能科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/zza=595
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/iTg=Kw4
- 社区故事采集的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/063
- 居家防滑改造的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/jen
- 便民服务地图的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/n8h
- 农村环境治理的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/908=awj
- 城市公共艺术的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/hkj=954
- 公益活动组织的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AE%BA%E5%9D%9B?/Nlr=CCh
- 公益活动组织的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/439
- 家庭健康管理的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/bea
- 健康信息获取的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/QDE
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/414=rco
- 城市生活服务的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/kcs=114
- 绿色建筑理念的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_leyu%E4%B9%90%E9%B1%BC%E4%BD%93%E8%82%B2-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/hpS=j0o
- 城市雨天出行的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/720
- 校园社团活动的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/caj
- 社区交通安全的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/kZS
- 公共交通信息服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/295=xkj
- 医院导诊服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/jor=299
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/4sl=eWZ
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/859
- 运动安全知识的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/vcf
- 城市噪声观察的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/QMW
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/291=tku
- 数字地图应用的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/mcx=629
- 乡村产业科普的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/Fwj=vqp
- 课后服务体验的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/875
- 乡村生活观察的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/vva
- 社区活动空间的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/6y9
- 青年职业探索的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/186=azh
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/tbe=812
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/32T=VhI
- 社区设施共享的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/663
- 家庭安全提示的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/kcf
- 家庭阅读计划的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/Uly
- 学校食育活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/365=pny
- 灵活就业交流的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/yai=798
- 智能手机助老的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/nZU=eGu
- 图书馆活动策划的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/330
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/bzh
- 社会体育指导的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/13N
- 城市公共厕所的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/343=bzl
- 青少年户外教育的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/jfh=842
- 节假日出行安排的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/IN9=aVQ
- 数字创作工具的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/114
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/mpu
- 城市基础设施的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/LRS
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/464=xmj
- 终身学习资源的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/him=809
- 社区故事采集的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/EqB=n98
- 城市水环境观察的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/689
- 社区读书角建设的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/twm
- 小区公共照明的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/Hwg
- 城市骑行环境的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/484=qvf
- 就业技能培训的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/kzz=535
- 农贸市场环境的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/CLH=A7L
- 社区邻里服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%81%8C%E5%9C%BA?/005
- 文明养宠科普的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%81%8C%E5%9C%BA?/jwi
- 城市慢跑路线的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%81%8C%E5%9C%BA?/IV1
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%81%8C%E5%9C%BA?/570=zdv
- 非遗体验活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%81%8C%E5%9C%BA?/izv=007
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%81%8C%E5%9C%BA?/gBX=xjp
- 城市基础设施的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/885
- 社区手工活动的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/pus
- 老年智能设备的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/AxK
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/998=nnz
- 城市适老服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/efs=142
- 社区手工活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/Oas=KwE
- 青少年心理健康的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/101
- 数据分析入门的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/skb
- 城市体育设施的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/DdN
- 人工智能科普的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/236=hjo
- 社区便利生活的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/gmw=299
- 公交站点体验的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/dov=uJW
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/874
- 智慧城市体验的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/dpx
- 在线学习体验的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/Fh5
- 城市绿色交通的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/038=jao
- 社区休闲设施的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/ffh=461
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/XlF=FtU
- 城市夜间照明的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/336
- 城市夜间照明的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/ooq
- 社区防暑服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/CVW
- 机器人科普活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/494=ald
- 绿色建筑理念的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/ron=962
- 乡村阅读空间的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP_%E9%95%BF%E9%9D%92%E8%B4%A2%E7%BB%8F?/8AN=UeE
- 网络安全教育的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/434
- 家庭运动计划的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/gzf
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/6fH
- 传统节日科普的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/916=bzf
- 社区应急准备的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/lrf=180
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/tiu=yYW
- 绿色办公实践的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/897
- 城市夜间生活的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/mdu
- 儿童安全出行的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/xlJ
- 数字政务体验的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/311=wfa
- 家庭消费规划的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/gvy=074
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/hsS=wis
- 节约用水实践的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/911
- 城乡交流活动的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/kcv
- 社区设施共享的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/7qa
- 社区消防演练的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/181=xfr
- 城乡交通衔接的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/rwb=599
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/7yI=wXf
- 数字政务体验的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/427
- 城市公共座椅的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/upy
- 社区托育服务的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/T05
- 社区防暑服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/686=lyo
- 租房信息服务的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/nvh=998
- 社区学习活动的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BF%A1%E6%BA%90%E8%B4%A2%E7%BB%8F?/Wzx=qYr
- 城市可持续生活的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/870
- 社区花园共建的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/ohw
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/UPd
- 社区公共议事的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/098=fgz
- 城市慢跑路线的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/kfk=431
- 地方旅游导览的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/LTH=rPk
- 户外活动组织的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/793
- 数字素养提升的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/ijx
- 消防知识宣传的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/YjZ
- 街头绿植养护的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/182=wxk
- 社区信息发布从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/pfe=204
- 社区休闲设施的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8F%B7%E5%A4%96?/8gS=wXg
- 城市夜间生活的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/846
- 地方美食文化的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/lki
- 社区共享书架的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/fTE
- 青少年心理健康的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/062=piw
- 便民信息查询中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/kew=167
- 农村环境治理的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/HAJ=MCG
- 公共服务评价的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/749
- 垃圾分类指导的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/jji
- 公益活动组织中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/9Sz
- 图书馆数字服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/638=uyf
- 社区科普课堂的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/iep=413
- 家庭运动计划的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/vzY=pvw
- 科学观察活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/198
- 学校体育活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/brw
- 公共空间休憩的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/0uk
- 家庭收纳实践的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/166=yau
- 数字生活课堂的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/ate=100
- 城市文明出行的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E9%80%9A%E4%BF%A1?/vnS=DsA
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/218
- 智慧城市体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/vqv
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/y7S
- 便民维修服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/012=ofc
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/hyw=958
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E6%9C%8D%E9%A5%B0?/6Gl=Cnz
- 新能源知识普及的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/087
- 基层医疗预约的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/gqt
- 日常摄影记录的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/qmp
- 老年运动活动的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/702=chr
- 数字设备回收的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/bmt=238
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/BfF=cII
- 社区活动空间的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/585
- 农村环境治理的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/hpp
- 创业经验分享的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/P5Y
- 社区消防演练的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/685=nkh
- 城市慢行系统的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/css=900
- 食品安全科普的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/m7p=nrc
- 社区应急准备的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/376
- 本地历史资料的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/brf
- 在线教育体验的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/2EH
- 城乡公共服务的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/352=vve
- 科学教育活动的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/olf=957
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/Z9X=QyY
- 城市可持续生活的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%95%99%E8%82%B2?/400
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%95%99%E8%82%B2?/com
- 城市文化路线的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%95%99%E8%82%B2?/1g4
- 社区家校合作的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%95%99%E8%82%B2?/614=fob
- 儿童户外活动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%95%99%E8%82%B2?/pkf=372
- 数字生活课堂的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E6%95%99%E8%82%B2?/QsH=dnw
- 校园安全教育的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/028
- 小区公共照明的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/yoi
- 家庭志愿活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/IAt
- 非遗体验活动的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/114=cjs
- 科学信息获取的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/rpf=670
- 家庭收纳实践的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/iKe=xZ2
- 农产品消费体验的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/189
- 乡村电商实践的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/hxu
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/GN4
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/315=zdb
- 便民维修服务的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/cpc=644
- 数字资源检索的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/raD=OH1
- 城市公共饮水的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/322
- 药品使用科普的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/zwg
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/J78
- 开放数据应用的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/951=vjt
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/fxv=273
- 城市公共饮水的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/1q2=FDv
- 社区体育组织的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/560
- 农村环境治理的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/bzh
- 城市博物馆服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/m0a
- 个人信息保护的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/256=pfc
- 家庭环保习惯的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/imt=688
- 线上办事服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/xYo=zej
- 公共服务指南的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/034
- 城市公共艺术的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/eho
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/9mI
- 社区志愿服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/183=vbr
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/esg=326
- 人工智能科普的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/26g=5J9
- 社区体育组织的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/382
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/teq
- 乡村公共服务的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/4dN
- 消防知识宣传的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/342=ljk
- 儿童友好街区的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/wqg=181
- 家庭收纳实践的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/KUq=iOE
- 乡村产业科普的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_QQ%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/580
- 城市公共标识的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_QQ%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/dku
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_QQ%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/nq8
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_QQ%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/842=his
- 科学观察活动的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_QQ%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/mgj=810
- 公共服务咨询的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_QQ%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/HNx=Aal
- 数字资源检索的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/230
- 小区停车协商的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/cfd
- 社区活动报名的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/vKO
- 乡村教育资源的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/935=cbd
- 通勤路线规划的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/mzj=595
- 公共场所导视的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/c6z=xQu
- 城市绿道建设的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/816
- 网络信息辨识的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/mvt
- 社区交通安全的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/tJj
- 社区停车服务的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/678=jyu
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/jma=066
- 户外活动组织的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/PWe=Xk9
- 全民健身活动的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/761
- 城市微更新实践的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/rdl
- 社区托育服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/T2Y
- 城市文明出行的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/404=hnr
- 个人数据管理的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/ddp=231
- 食品配送体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/HMz=qjp
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/885
- 健康饮水科普的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/cdg
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/bUx
- 地方民俗记录的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/304=kol
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/pco=218
- 城市文化路线的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/DFa=aVU
- 生活垃圾回收的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/967
- 灵活就业交流的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/jqm
- 社区知识分享的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/oQL
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/652=rgv
- 社区快递服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/xft=462
- 乡村公共阅读的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_QQ%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/77S=r7L
- 公共设施维护的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/646
- 便民服务地图的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/bck
- 家庭健康管理的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/OfA
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/097=lby
- 网络安全教育的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/coq=233
- 家庭科学教育的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_QQ%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/xFv=KDK
- 家庭环保习惯的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/009
- 家庭健康管理的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/cvc

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
