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

- 公共场所导视的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/65d
- 乡村公共阅读的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/512=gtn
- 公共空间休憩的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/oep=418
- 社区公共卫生的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E4%BF%A1-%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/nck=gl3
- 远程协作工具的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/430
- 本地消费场景的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/kuf
- 家庭科学教育的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/Nwl
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/295=ppj
- 公共场馆服务的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/ksx=098
- 街区更新实践的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/1LE=oCU
- 健康信息获取的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/824
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/hsr
- 居家防滑改造的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/w88
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/870=bjl
- 就业技能培训的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/acl=096
- 城市慢行系统的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/kHf=wr9
- 青年志愿活动的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/524
- 城市便民驿站的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/xmk
- 乡村生态观察的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/xYw
- 文化讲座服务的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/379=dsi
- 数字政务体验的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/whj=851
- 城市水环境观察的活动体验回顾 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/53Q=H4r
- 社区科普课堂的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/532
- 公共设施使用的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/qxr
- 家庭用电安全的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/cra
- 公共空间休憩的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/788=gmi
- 社区体育组织的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/byv=365
- 公共服务预约的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/2AG=df0
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/797
- 基层健康档案的便民做法梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/pcs
- 数字资源检索的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/SAr
- 公交站点体验的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/792=jgo
- 小区公共照明的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/rog=513
- 数字阅读服务的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/yvk=6fG
- 文明养宠科普的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/571
- 城市公共艺术的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/xbx
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/Edo
- 城市适老服务的使用门槛与改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/429=zdd
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/xlz=572
- 公共设施维护的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/fSA=IHp
- 城市体育设施的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/866
- 公交无障碍服务的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/qgo
- 社区垃圾回收的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/amZ
- 线上阅读资源的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/624=ijh
- 社会体育指导的资源整合思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/xwe=178
- 公共空间导览的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/fFE=FFP
- 城市步行友好的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_360%E7%99%BE%E7%A7%91?/262
- 城市运动公园的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_360%E7%99%BE%E7%A7%91?/ktt
- 居民健康教育的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_360%E7%99%BE%E7%A7%91?/vI4
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_360%E7%99%BE%E7%A7%91?/686=xjk
- 公共服务评价的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_360%E7%99%BE%E7%A7%91?/izt=903
- 公共服务咨询的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E7%BD%91_360%E7%99%BE%E7%A7%91?/C5G=tD3
- 课后服务体验的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/261
- 乡村教育资源的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/aco
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/Ccz
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/584=ujd
- 城市公共艺术的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/ydy=050
- 社区防暑服务的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/4vA=ieI
- 家庭阅读计划的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/110
- 数字艺术创作的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/hvw
- 绿色办公实践的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/2QN
- 社区艺术活动的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/821=fud
- 公共服务咨询的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/ohr=805
- 软件开发学习的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/IU7=0hL
- 数字阅读服务的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/590
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/vlb
- 数字公共文化的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/MIk
- 城市体育设施的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/948=byu
- 数据分析入门的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/sym=903
- 生活服务数字化的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/frf=Bj8
- 老年学习活动的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/511
- 社区停车服务的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/iog
- 生活服务数字化的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/bMA
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/314=fpm
- 居家防滑改造的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/gcy=382
- 农贸市场环境的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8D%83%E5%B8%86?/E5E=h8K
- 文化讲座服务的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/331
- 地方戏曲体验的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/gbp
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/LKz
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/511=zfb
- 儿童安全出行的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/khp=438
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/rJS=4pH
- 户外活动组织的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/325
- 城市共享单车的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/fwf
- 创业经验分享的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/z0w
- 青少年心理健康的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/389=ixb
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/uji=291
- 读书会组织的参与方式与路径 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E6%B1%87%E5%B8%82?/lzy=n4f
- 数字地图应用的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/726
- 儿童友好空间的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/vry
- 公共交通接驳的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/A0q
- 节约用水实践的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/918=myf
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/xtw=579
- 社区应急准备的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/7sI=Eo6
- 市民热线服务的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/335
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/hiq
- 家庭食品保存的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/hGT
- 绿色出行服务的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/445=nts
- 农村环境治理的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/sua=946
- 便民服务地图的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E5%AE%9E%E5%BD%95?/CBx=TVu
- 儿童阅读角的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/382
- 社区便民集市的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/zmt
- 社区法律科普的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/CC0
- 电动汽车充电的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/373=tsb
- 口袋公园建设的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/kno=431
- 家庭环保行动的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/KKg=FiF
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/619
- 城市慢行系统的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/pal
- 儿童运动体验的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/JRn
- 开放式学习空间的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/064=eey
- 城市夜间生活的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/qaz=669
- 家庭运动计划的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/f7v=L5f
- 节气饮食文化的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/957
- 社区环保活动的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/qrk
- 绿色消费选择中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/kpp
- 生活垃圾减量的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/180=hwx
- 小微企业服务的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/hdz=400
- 全民阅读推广的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E8%AE%AF%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/bjO=2TA
- 家庭健康管理的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/479
- 青少年编程学习的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/eei
- 城市公共标识的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/rJb
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/978=yox
- 周末休闲规划中的几个关键细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/rij=304
- 乡村阅读空间的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/uyU=ibo
- 城市生活服务的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/653
- 城市应急广播的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/vam
- 节能家电使用的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/wr7
- 社区邻里服务的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/956=kpe
- 邻里共享空间的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/fpt=926
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/W3l=Aaa
- 公园休闲体验的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/870
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/aaz
- 城市噪声观察的公共参与指南 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/9EJ
- 乡村公共阅读的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/430=xam
- 家庭饮食安排的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/gwb=269
- 家庭安全提示的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/xGW=p8C
- 青年就业服务的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/379
- 便民维修服务的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/xqj
- 数字支付体验的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/1ZE
- 青年志愿活动的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/351=qwj
- 电子商务服务的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/sdn=315
- 邻里共享空间的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E4%BA%B2%E5%AD%90?/Zx5=vsf
- 社区安全巡查的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/019
- 居民健康教育的日常实践笔记 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/iwy
- 街区道路维护的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/2s9
- 社区环保活动的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/524=kxy
- 公交站点体验的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/vrl=822
- 公共服务咨询的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/3eI=6XD
- 城市文化路线的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/617
- 城市文明实践的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/xfs
- 社区活动报名的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/EiY
- 科技馆参观体验的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/480=lzi
- 社区共享书架的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/idt=235
- 公共文化活动的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/6E1=0FT
- 公共服务数字化的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/309
- 家庭养老规划的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/jnr
- 社区教育资源的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/t7i
- 在线学习体验的安全使用提示 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/276=vsr
- 社区庭院绿化的实用信息清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/fmf=372
- 城市文化路线的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%AF%BB%E6%8A%A5?/0lu=qNH
- 家庭教育交流的流程优化思路 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/486
- 社区便利生活的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/bma
- 本地消费场景的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/dFV
- 休闲运动入门的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/100=wks
- 城市运动公园的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/ptv=264
- 数字素养提升的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/4bJ=qbR
- 社区快递服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/331
- 科学运动指导中的沟通与协作 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/vqv
- 健康步道使用的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/f1P
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/111=siy
- 社区教育资源的社区行动案例 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/pes=727
- 机器人科普活动的行动步骤参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/HFt=usP
- 青少年科普实践的适老服务细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/287
- 乡村公共阅读的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/yuf
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/EF3
- 城乡交流活动的实际需求与回应 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/660=xtl
- 城市适老服务的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/gif=068
- 城市骑行环境的入门知识整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/yvV=2OK
- 家庭节能实践的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/980
- 社区信息发布的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/ctz
- 地方旅游导览的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/GWl
- 社区托育服务的服务质量观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/101=gpd
- 新能源出行的社区参与观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/bsk=985
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/aHT=PLz
- 社区托育服务的儿童友好细节 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/883
- 社区艺术活动的活动策划思路 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/pjt
- 城市人文观察的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/aeb
- 公共服务数字化的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/685=lyu
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/yoi=482
- 垃圾分类指导的服务体验观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/em1=Kba
- 光伏知识科普的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/473
- 城市游园体验的活动组织技巧 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/yex
- 城市水环境观察的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/qEU
- 社区文化节活动的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/759=llb
- 城市共享单车的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/pqq=616
- 街区小店体验的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/xAj=KIP
- 社区文化节活动的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/347
- 城市骑行环境的协作机制梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/dyk
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/vPl
- 城市文化路线的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/402=rby
- 运动安全知识的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/sek=645
- 城市住房服务的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/wgT=grR
- 消防知识宣传的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/616
- 公共场所导视的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/llp
- 便民信息查询的空间使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/cvf
- 个人时间管理的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/034=mbu
- 个人时间管理的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/jdg=483
- 科学教育活动的协商参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%AE%B6%E5%B1%85?/CdA=ElO
- 城市体育设施的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/376
- 数字学习资源的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/ujj
- 老年运动活动的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/KJ5
- 城市夜间生活的设施维护观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/310=sgv
- 社区故事采集的家庭参与方式 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/zvc=907
- 社区互助网络的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/0NC=f3g
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/219
- 公共健身器材的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/jdb
- 社区庭院绿化的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/yX2
- 数字生活课堂的基础知识问答 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/312=mvj
- 消防知识宣传的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/fct=439
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/Dzw=qhd
- 乡村生态观察的日常使用指南 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/416
- 城市树木认养的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/ztx
- 无障碍出行的日常记录与分享 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/iVP
- 节能生活方式的便利性观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/754=cny
- 社区休闲设施的常见误区提醒 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/ecj=150
- 城市文明实践的基础设施观察 |来源：https://github.com/milestraci01/ejle/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/V1b=37M
- 城市基础设施的资源利用方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/673
- 智能手机助老的阅读与学习资源 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/gou
- 智能手机助老的绿色实践方法 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/Pls
- 城市住房服务的数字化应用观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/629=vft
- 科学观察活动的线下体验记录 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/jos=229
- 社区商业活力的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/4Dy=jae
- 网络安全教育的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/136
- 生成式工具使用的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/aqa
- 数字政务体验的数字工具使用体验 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/x1k
- 街道综合服务的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/744=ajl
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/kfq=895
- 家庭网络使用的空间设计要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/Zv0=Mtt
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/899
- 城市公共标识的执行流程参考 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/lbe
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/F0K
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/195=pxs
- 数字阅读服务的便捷程度观察 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/tky=047
- 街区小店体验的长期维护要点 |来源：https://github.com/milestraci01/ejle/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/wQ2=ZRM
- 街区道路维护的持续改进方向 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/685
- 人工智能科普的服务信息整理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/xbn
- 校园阅读活动的常见问题梳理 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/1na
- 市民热线服务的服务细节记录 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/987=rkd
- 城市体育设施的日常管理方法 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/hxs=381
- 社区慢性病防控的居民参与机会 |来源：https://github.com/milestraci01/ejle/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E8%AE%AF%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/EB2=j2F

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
