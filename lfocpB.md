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

- 非遗体验活动的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/MXr
- 健康步道使用的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/984=ttl
- 城市游园体验的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/jry=407
- 创业经验分享的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%93%94%E5%93%A9%E5%9C%B0%E4%BA%A7?/ITZ=y6j
- 青少年职业启蒙的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/688
- 家庭节能实践的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/rpq
- 节能家电使用的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/rnr
- 基层健康服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/843=zjn
- 农村环境治理的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/eph=055
- 数据分析入门的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/Khp=pPv
- 公共场所导视的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/277
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/lxm
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/NAv
- 社区艺术活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/120=lma
- 城市博物馆活动的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/mol=670
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/pY1=gPG
- 食品安全科普的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/467
- 本地消费场景的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/opn
- 家庭防灾准备的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/qyg
- 校园节能行动的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/690=jbo
- 城市体育设施的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/fae=782
- 地方美食文化的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/wac=BlL
- 个人信息保护的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/433
- 社区信息发布的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/thx
- 公共设施使用的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/Hv2
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/127=lpn
- 乡村文化活动的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/wfn=646
- 节假日出行安排的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/lSZ=cv3
- 城市人文观察的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/861
- 生成式工具使用中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/ejd
- 职业技能学习的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/bvu
- 家庭安全提示的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/340=kfd
- 儿童运动体验的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/riq=962
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/4z5=z7l
- 公共设施维护的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/857
- 社区公共卫生的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/plj
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/HzL
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/823=nqn
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/qur=845
- 街区小店体验的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/SPP=auF
- 农村环境治理的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/160
- 骑行路线规划的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/umv
- 基层健康服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/AtM
- 社区停车服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/713=czx
- 在线学习体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/vac=761
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/pK3=JhM
- 乡村生态旅游的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/980
- 消防知识宣传的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/dfm
- 乡村生活观察的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/ZmZ
- 公共文化活动中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/079=ngy
- 农业科普体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/ppq=073
- 城市社区治理的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/Nn2=T7F
- 社区共享书架的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/651
- 老年人出行服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/rlw
- 青年就业服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/W8S
- 开放式学习空间的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/331=vsn
- 小区电梯维护的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/utn=200
- 社区便民服务的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%AE%89%E9%98%B2?/KHc=sf7
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/800
- 城市生活记录的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/kze
- 社区教育资源的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/FGw
- 文化场馆预约的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/818=zol
- 社区读书角建设中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/vbw=803
- 小微企业服务的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/nam=Qnx
- 儿童友好空间的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/192
- 数据分析入门的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/tce
- 消防知识宣传中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/FGi
- 城市公共空间的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/228=ohi
- 公交站点体验的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/yzx=941
- 公共服务数字化的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/Zha=KI9
- 社区宠物管理的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/384
- 青少年科技社团的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/evd
- 社区知识分享的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/Qd0
- 家庭用电安全的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/928=tuz
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/meo=109
- 城市便民驿站的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E9%80%9F%E8%A7%88?/tYy=UUQ
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/322
- 城市公共艺术的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/zpj
- 社区教育资源的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/hDb
- 小区停车协商的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/572=eaz
- 城市便民驿站的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/ijz=882
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/wpL=CWE
- 家庭用电安全的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/326
- 物业服务沟通的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/soq
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/J3b
- 小区公共照明的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/772=ebv
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/eac=087
- 家庭饮食安排的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/oED=teS
- 健康饮食教育的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/809
- 社区老年食堂的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/xsl
- 节假日出行安排的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ye5
- 口袋公园建设的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/152=nei
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/cpq=460
- 网络信息辨识的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wPS=9y3
- 家庭运动计划的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/513
- 城市博物馆服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/jln
- 家庭节能设备的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/4Xx
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/610=rie
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/lnz=691
- 数字艺术创作的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/Q0D=Zyk
- 便民信息查询的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/838
- 公共文化活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/wfv
- 家庭节能设备的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/dhD
- 社区共享书架的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/017=xkn
- 课后服务体验的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/hev=330
- 休闲运动入门的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/OeC=W1u
- 城市步行环境中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/031
- 社区养老服务的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/duy
- 本地消费场景的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/Ik4
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/844=ezt
- 文化讲座服务的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/qat=626
- 数字支付体验的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%8F%8C%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/PU8=Dov
- 家庭园艺实践的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/729
- 公共空间安全的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/mkm
- 健康信息获取的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/hXV
- 图书借阅体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/468=dzl
- 数字课堂应用的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/ric=660
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/6fR=PnD
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8welcome_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/205
- 数字艺术创作中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8welcome_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/iey
- 儿童户外活动的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8welcome_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/RJ6
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8welcome_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/352=xgt
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8welcome_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/ncn=203
- 社区活动空间的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8welcome_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/6PA=snn
- 公共空间照明的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/118
- 数字政务体验的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/iso
- 公共卫生宣传的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/TQq
- 无障碍信息设计的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/564=guu
- 青少年科技社团的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/zev=647
- 社区阅读服务的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/f0y=S34
- 公交无障碍服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/724
- 社区互助网络的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/bwg
- 邻里互助活动的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pjl
- 家庭食品保存的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/122=vjp
- 文化场馆预约的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lau=369
- 街头绿植养护的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/eHM=t4L
- 科学运动指导的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/745
- 图书借阅体验的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/lwr
- 电动汽车充电的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/Bc4
- 安全出行教育的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/141=hbr
- 健康信息获取的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/cax=041
- 文明养宠科普中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/lI8=Rgy
- 通勤路线规划的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/605
- 公共设施维护的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/tmm
- 急救知识普及的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/8fJ
- 老旧小区改造的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/642=xoz
- 运动安全知识的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/lrf=007
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E6%8A%A5?/4DP=mUL
- 环境监测科普的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9VIP-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/583
- 社区文化传播的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9VIP-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/dps
- 社区设施共享的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9VIP-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/DAf
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9VIP-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/265=szb
- 旧物循环利用的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9VIP-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/ddp=892
- 生活垃圾回收的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9VIP-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/kxS=IrM
- 社区垃圾分类的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/493
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ndd
- 社区生活指南中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/sEt
- 城乡交流活动的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/907=vuy
- 数字艺术创作的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/wna=777
- 职业技能学习的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/npq=s0n
- 社区家校合作的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/363
- 社区生活指南的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/cmt
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/K9K
- 生成式工具使用的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/266=kut
- 城市公共艺术的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/tcw=530
- 通勤路线规划中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99~welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/389=LFj
- 数字便民地图的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91hcw%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/721
- 在线学习体验的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91hcw%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xis
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91hcw%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Cwr
- 家庭消费规划的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91hcw%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/699=vrk
- 智慧城市体验的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91hcw%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/spw=306
- 社区家校合作的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91hcw%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/39r=VqJ
- 人工智能科普的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/873
- 社区学习活动的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/tpp
- 终身学习资源的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/NzC
- 城市公共标识的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/785=ooh
- 家庭健康管理的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/try=576
- 电子商务服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/bZm=cBV
- 社会体育指导的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99welcome%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/131
- 乡村公共文化的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99welcome%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/phv
- 网络信息辨识的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99welcome%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/1IW
- 城市步行环境的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99welcome%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/354=smi
- 公园亲子设施的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99welcome%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/gmw=305
- 社区信息发布中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%8E%AF%E5%BD%A9%E7%BD%91%E7%AB%99welcome%E6%9C%80%E6%96%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/64Z=XHy
- 城乡交通衔接的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/837
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/afw
- 数字档案服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/rLb
- 公共场馆服务的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/236=qem
- 城市夜间生活的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/dqu=465
- 儿童安全出行的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/kTh=Sga
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/678
- 文明养宠科普的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/ror
- 城市公共标识中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/gnb
- 家庭阅读计划的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/842=dof
- 绿色消费选择的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/hbg=503
- 公园亲子设施的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E9%99%86_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/7V8=opn
- 医院导诊服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/035
- 绿色生活实践的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/vtb
- 城市游园体验的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/vYP
- 节假日出行安排的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/151=gxc
- 社区家校合作的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/cqw=547
- 小微企业服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/iCv=I8f
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA%E9%87%8C_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/767
- 家庭收纳实践的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA%E9%87%8C_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ssa
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA%E9%87%8C_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/RAI
- 城市应急科普的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA%E9%87%8C_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/547=krm
- 社区花园共建的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA%E9%87%8C_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/uoz=414
- 社区艺术活动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA%E9%87%8C_%E8%93%9D%E6%B5%B7%E8%B4%A2%E7%BB%8F?/VO6=05I
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/753
- 社区学习活动的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/zzk
- 数字公共文化的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/brx
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/481=xft
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/bbc=206
- 校园阅读活动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/FEL=XoG
- 城市博物馆服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/781
- 绿色出行服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/ygi
- 基层健康服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/jeM
- 校园社团活动的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/816=rgt
- 节日文化体验的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/jex=362
- 个人数据管理的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83Welcome_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/i59=tWf
- 城市体育设施的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/932
- 城市步行友好的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/mnv
- 老年人文化生活的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/C4x
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/081=bwm
- 家庭科学教育的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/swb=352
- 社区知识分享的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/4qf=pTS
- 环境监测科普的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-welcome500%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/734
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-welcome500%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/jey
- 数字课堂应用的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-welcome500%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/j0p
- 数字政务体验的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-welcome500%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/234=xvt
- 社区科普课堂的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-welcome500%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/mqc=273
- 食品安全科普的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%8E%AF%E7%90%83%E8%B4%AD%E5%BD%A9-welcome500%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/Fp0=Igw
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/537
- 社区家政服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/cfq
- 城乡公共服务的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/Cyu
- 城市可持续生活的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/507=ooq
- 城市公共艺术的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/ufv=442
- 老年人出行服务的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/WHQ=5Lr
- 基层服务创新的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9A%87%E9%A9%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/904
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9A%87%E9%A9%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/cjt
- 城市展览体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9A%87%E9%A9%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/3Pe
- 创业经验分享的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9A%87%E9%A9%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/339=imn
- 绿色出行服务的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9A%87%E9%A9%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/ryn=830
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%9A%87%E9%A9%AC%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E8%AF%BB%E4%B9%A6?/M5H=gEg
- 居家适老化改造的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/286
- 家庭健康管理中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/yjz
- 农产品消费体验的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/OWB
- 街道综合服务的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/643=zzw
- 个人时间管理的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/fav=327
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%9A%87%E9%A9%AC%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/0qP=nWp

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
