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

- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/343
- 无障碍信息设计的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/rpi
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/Hq2
- 环境教育课程的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/057=toh
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/vum=083
- 数字便民地图的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/vTT=LNx
- 绿色生活实践的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/040
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/zzc
- 全民健身活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/d1D
- 公共交通信息服务的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/073=tjm
- 社区休闲设施的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/ynf=644
- 公共服务指南的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/hgf=kwt
- 乡村生态观察的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/040
- 城市游园体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/ysi
- 社区健康讲座的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/XAn
- 城市公共自行车的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/058=nfm
- 城市文明实践的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/abv=483
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/jeX=yDv
- 城市骑行环境的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/515
- 本地历史资料的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/tge
- 家庭网络使用的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/HW0
- 社区老年食堂的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/355=nhu
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/fud=229
- 老年数字阅读的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/OQ6=RCF
- 社区便民集市的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/758
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/zsl
- 家庭教育交流的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/jtA
- 地方美食文化的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/591=hkf
- 老年人日常照护的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/szt=331
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/kqw=3GK
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/621
- 社区艺术活动的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/dtu
- 在线教育体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/igh
- 城市水环境观察的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/377=veh
- 农业科普体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/bgj=412
- 公共交通接驳的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/ABV=1ju
- 数字政务体验的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/585
- 便民维修服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/sdb
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/QwZ
- 社区阅读服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/865=cod
- 城市生活服务的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/uol=608
- 城市可持续生活的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/yCK=POH
- 校园节能行动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/046
- 食品配送体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/apw
- 乡村文化空间的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/38Y
- 乡村生活观察的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/542=mii
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/pdh=285
- 科学教育活动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/zKC=CFe
- 公共设施使用的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/793
- 终身学习资源的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/ujt
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/vbk
- 生成式工具使用的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/753=pab
- 公园休闲体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/tvm=491
- 文明养宠科普的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/vD0=nFX
- 便民服务窗口的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/264
- 社区手工活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/pry
- 社区读书角建设的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/1NB
- 文明养宠科普的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/363=njs
- 地方民俗记录中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/hia=042
- 劳动教育实践的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/jOd=ll2
- 青少年职业启蒙的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/074
- 社区信息发布的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/mka
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/mJS
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/835=qmn
- 社区文化传播的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/nrj=015
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/ZiB=4P2
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/466
- 城市运动公园的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/zln
- 社区休闲设施的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/ldr
- 城市农夫市集的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/908=rdx
- 课后服务体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/kjy=873
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/2er=LrH
- 社区知识分享的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/908
- 数字公共文化的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/mok
- 家庭园艺实践的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/TpU
- 邻里共享空间的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/522=ufd
- 学校食育活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/pip=166
- 图书馆活动策划的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/BIn=2HB
- 新能源出行的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/848
- 城市噪声观察的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/rsg
- 骑行路线规划的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/76W
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/081=afb
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/zsz=510
- 绿色出行服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/Hq8=AW1
- 食品安全科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/454
- 城市共享单车的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/ifg
- 科学健身方法中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/Jq7
- 个人数据管理的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/908=efu
- 口袋公园建设的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/qcb=080
- 青少年户外教育的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%BD%AC%E8%BD%BD?/ixL=7Q8
- 开源技术交流的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/531
- 社区故事采集的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/vhg
- 城市文明实践的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/m24
- 城市共享单车的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/527=twb
- 城市应急科普的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/odi=477
- 社区信息发布的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/R6x=7iE
- 新能源出行中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/487
- 软件开发学习的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/swx
- 口袋公园建设的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/GOf
- 公共空间导览的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/055=jff
- 公交站点体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/iuu=744
- 公共设施维护的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB?/MaX=B5b
- 非遗课堂体验的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/107
- 青少年编程学习的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/kwo
- 全民健身活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/gLY
- 垃圾分类指导的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/404=ego
- 社区阅读服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/lgp=796
- 公共服务咨询的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/YtD=K7p
- 健康信息获取的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/825
- 社区便利生活的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/eak
- 社区宣传栏更新有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/rtn
- 生成式工具使用的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/920=fgq
- 青少年心理健康的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/bwt=192
- 环境教育课程的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/sJv=3W2
- 老年学习活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/171
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/nqk
- 社区互助网络的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/idA
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/468=lcp
- 传统节日科普的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/hit=876
- 校园社团活动的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/g9V=36P
- 老年人日常照护的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/936
- 城市便民驿站的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/xjc
- 节假日出行安排的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/9hq
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/782=gdi
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/alr=028
- 社区宠物管理中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/clO=2rF
- 就业技能培训的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/355
- 科普展览体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/fjv
- 图书馆活动策划的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/ved
- 休闲运动入门的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/520=ext
- 公共服务沟通的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/asb=081
- 街道综合服务的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/MFQ=63t
- 校园社团活动的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6?/486
- 街区绿化养护的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6?/nor
- 社区活动报名的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6?/0ct
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6?/274=ynl
- 社区托育服务的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6?/nax=470
- 社会体育指导的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6?/wXI=Qgr
- 数字创作工具的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/898
- 家庭环保行动的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/aev
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/pbj
- 城乡公共服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/585=vps
- 新能源出行的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/fqe=146
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/vt4=xrw
- 社区志愿服务的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/756
- 开源技术交流的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/aqc
- 社区庭院绿化的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/9pP
- 公共服务数字化的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/674=cak
- 社区停车服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/xcs=960
- 生活技能分享的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_app%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/Jps=Urs
- 健康饮水科普中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/517
- 数字档案服务的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/uvg
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/5L4
- 城市生活记录的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/608=xmi
- 文明养宠科普的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/vrj=590
- 社区艺术活动的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/cKt=Zhj
- 乡村公共文化的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_app%E5%BD%A9%E7%A5%A8-APP_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/719
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_app%E5%BD%A9%E7%A5%A8-APP_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/ltv
- 公共服务预约的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_app%E5%BD%A9%E7%A5%A8-APP_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/3qG
- 环境监测科普的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_app%E5%BD%A9%E7%A5%A8-APP_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/866=kge
- 乡村教育资源的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_app%E5%BD%A9%E7%A5%A8-APP_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/qmv=979
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_app%E5%BD%A9%E7%A5%A8-APP_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/mOY=vxj
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/284
- 城市文明出行的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/bwr
- 城市生活服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/Nmt
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/695=ukv
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/hhz=214
- 公共空间休憩的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_app%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/KJV=qQO
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/195
- 周末休闲规划的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/qim
- 社区绿色空间的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/ntT
- 数字学习资源的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/910=zaw
- 软件开发学习中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/xpr=938
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/Qeq=wqX
- 旧物循环利用的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/633
- 家庭健康科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/wpz
- 药品使用科普的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/j59
- 社区共享书架的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/903=evv
- 公共服务评价的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/mvf=094
- 城市适老服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_app%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E7%95%85%E6%B8%B8?/xzL=xPO
- 社区公共餐饮的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BD%93%E8%82%B2?/316
- 科技馆参观体验的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BD%93%E8%82%B2?/lfx
- 乡村公共文化的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BD%93%E8%82%B2?/OZs
- 城市绿色交通的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BD%93%E8%82%B2?/367=doo
- 城市绿色交通的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BD%93%E8%82%B2?/zkq=288
- 社区心理支持的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_app%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BD%93%E8%82%B2?/XaC=0ht
- 数字资源检索的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/794
- 社区菜市场服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/hqq
- 新能源知识普及的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/3W8
- 社区商业活力的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/205=kha
- 城市地名文化的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/rzn=465
- 电子商务服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_app%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/wZF=Asm
- 数字生活课堂的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/465
- 公共空间休憩的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/ojb
- 社区艺术活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/ICi
- 网络安全教育的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/333=hcz
- 低碳社区实践的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/wod=759
- 安全出行教育的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_app%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/mAj=T7E
- 社区故事采集的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/760
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/cme
- 口袋公园建设的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/h9X
- 城市公共自行车的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/035=hex
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/ibg=812
- 健康步道使用的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_app%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%88%86%E6%83%85?/XoJ=ajl
- 城市游园体验的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_app%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/913
- 小区电梯维护的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_app%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/bjv
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_app%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/itI
- 科学运动指导的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_app%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/372=iho
- 老年友好服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_app%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/ikm=164
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_app%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/w5E=vKh
- 创业经验分享的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_app%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/750
- 居家防滑改造的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_app%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/zlg
- 儿童户外活动的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_app%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/WCL
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_app%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/124=xpp
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_app%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/ukk=635
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_app%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/nkZ=l4k
- 科技馆参观体验的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/594
- 社区儿童活动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/gpe
- 灵活就业交流的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/NWK
- 非遗课堂体验的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/753=yzh
- 绿色消费选择中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/qxu=830
- 亲子科普活动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_app%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/Cjh=TH1
- 社区停车服务的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_bet365-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/379
- 城市水环境观察中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_bet365-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/cwt
- 街区小店体验的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_bet365-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/rol
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_bet365-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/442=dpx
- 节假日出行安排的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_bet365-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/dap=043
- 运动安全知识的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_bet365-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/UGM=SwJ
- 绿色生活实践的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_bet365-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/310
- 绿色出行服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_bet365-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/qyy
- 老年友好服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_bet365-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/XlC
- 机器学习入门的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_bet365-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/590=jxc
- 校园社团活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_bet365-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/yru=916
- 学校食育活动的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_bet365-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/dSs=9PQ
- 青年就业服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_bet365-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/201
- 城市树木认养的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_bet365-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/kat
- 绿色消费选择的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_bet365-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/3Yk
- 乡村生活观察的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_bet365-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/968=lhw
- 公共服务指南的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_bet365-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/wfc=087
- 公共空间照明的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_bet365-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/PSc=otC
- 数字学习资源的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_bet365-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/586
- 家庭用电安全的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_bet365-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/mxd
- 社区家政服务的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_bet365-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/X5X
- 绿色办公实践的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_bet365-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/401=pta
- 城市体育设施的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_bet365-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/jlv=895
- 城市绿色交通的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_bet365-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E7%94%B5?/NwN=xY7
- 城乡交通衔接的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_bet365-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/729
- 智慧城市体验的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_bet365-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/jjw
- 文明养宠科普的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_bet365-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/9lF
- 本地旅行体验的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_bet365-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/450=ymt

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
