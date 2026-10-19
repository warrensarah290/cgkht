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

- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/fmv=456
- 低碳社区实践的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/ivK=S3D
- 地方文化传播的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/730
- 文化讲座服务的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/hxn
- 智能家居应用的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/Faf
- 无障碍出行的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/109=wjr
- 城市基础设施的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/fof=108
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/26O=B6h
- 科学运动指导的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/110
- 城市应急广播的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/tri
- 城市公共空间的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/mWj
- 网络安全教育的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/491=qzi
- 数字创作工具的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/och=955
- 街区道路维护的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/XnH=rgs
- 健康步道使用的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%97%B6%E8%AE%AF?/239
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%97%B6%E8%AE%AF?/ycr
- 医院导诊服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%97%B6%E8%AE%AF?/L37
- 城市公共座椅的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%97%B6%E8%AE%AF?/340=rcx
- 社区便民服务的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%97%B6%E8%AE%AF?/aaq=631
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_360%E6%97%B6%E8%AE%AF?/TvD=mSg
- 社区手工活动的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/727
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/qhm
- 社区设施共享的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/ByG
- 家庭志愿活动的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/015=qpz
- 老年人文化生活的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/fov=087
- 网络安全教育的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E5%B0%9A?/vVA=j1T
- 终身学习资源的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/853
- 节约用水实践的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/nqy
- 社区活动策划的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/Rvc
- 开源技术交流的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/925=sne
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/eyg=796
- 食品安全科普的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/39w=uwK
- 节气饮食文化的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_58%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/219
- 无障碍信息设计的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_58%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/jwf
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_58%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/Xkk
- 乡村阅读空间的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_58%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/837=oik
- 乡村公共阅读的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_58%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/aey=706
- 城市公共自行车的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_58%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/RcP=Q3J
- 社区阅读服务的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/952
- 老旧小区改造的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/khx
- 图书借阅体验的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/cUO
- 社区志愿服务的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/393=wqt
- 绿色消费选择的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/jlf=270
- 志愿者培训交流的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/tAB=K61
- 地方民俗记录的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%B9%B6%E8%B4%AD?/150
- 居民健康教育的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%B9%B6%E8%B4%AD?/uvz
- 老旧小区改造的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%B9%B6%E8%B4%AD?/PAY
- 食品配送体验的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%B9%B6%E8%B4%AD?/160=ley
- 绿色校园实践的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%B9%B6%E8%B4%AD?/vit=191
- 社区阅读服务的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%B9%B6%E8%B4%AD?/Itc=AoH
- 城市绿道建设的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/102
- 城市水环境观察的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/vkr
- 软件开发学习的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/OvG
- 城市农夫市集的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/096=jcs
- 节能家电使用的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/pth=364
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%95%B0%E8%AF%BB?/GOj=6i5
- 公共图书馆服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/191
- 街区更新实践的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/vhv
- 新能源知识普及的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/JXr
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/441=oiz
- 乡村生活观察的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/wxb=723
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BF%B0%E8%AF%84?/vXd=60G
- 城乡交流活动的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/349
- 网络信息辨识的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/fkg
- 公共空间导览的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/83p
- 儿童阅读角的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/680=tik
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/dln=558
- 食品配送体验的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/9Xy=xB0
- 开放数据应用的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/920
- 居民健康教育的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/ecx
- 城市步行环境的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/PHn
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/582=sej
- 社区读书角建设的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/npf=040
- 环境教育课程的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/TOr=G8y
- 社区环保活动的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/527
- 节假日出行安排的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/fcz
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/deJ
- 居家适老化改造的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/079=mcx
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/xxf=249
- 就业技能培训的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/YfI=4Y9
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/114
- 新能源出行的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/ysb
- 劳动教育实践的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/bjY
- 老年友好服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/403=mvp
- 绿色消费选择的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/xnf=405
- 家庭志愿活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/S6l=3Gg
- 科学信息获取的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/148
- 远程协作工具的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/dfs
- 城市生活服务的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/ajy
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/032=iaz
- 数字素养提升的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/wss=231
- 个人时间管理的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%A6%9C%E5%8D%95?/W5J=0GJ
- 创业经验分享中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/892
- 便民服务地图的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/niu
- 亲子阅读活动的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/y7L
- 社区教育资源的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/223=ajk
- 城市休闲步道中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/cmw=837
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/W5v=sAv
- 城市夜间照明的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/868
- 节能生活方式的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/ivk
- 网络信息辨识的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/FLA
- 光伏知识科普的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/357=yzp
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/fwh=456
- 居家防滑改造的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/yId=WJn
- 青年职业探索的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/651
- 公共空间导览的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/pwl
- 志愿服务平台的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/9Zn
- 地方美食文化的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/795=mcu
- 新能源出行的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/hfq=031
- 电子商务服务的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/JlC=VQR
- 科学运动指导的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/822
- 农产品消费体验从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/drv
- 儿童户外活动的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/WjH
- 乡村教育资源的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/045=xzz
- 城市游园体验的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/guk=409
- 社区垃圾回收的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%93%B6%E5%8D%8E%E8%B4%A2%E7%BB%8F?/XwU=QSX
- 社区休闲设施的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/305
- 城市展览体验的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/okn
- 城乡交流活动的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/Nts
- 城市文化路线的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/393=lrs
- 城市公共标识的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/wvy=622
- 小微企业服务的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/zX9=MBV
- 青少年科普实践的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/584
- 绿色生活实践的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/ryn
- 节气饮食文化的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/tdo
- 机器学习入门的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/198=vel
- 休闲运动入门的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/uof=078
- 城市生活服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/S7B=h3R
- 个人数据管理的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/371
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/cgz
- 社区应急准备的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/Jps
- 公共图书馆服务的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/319=rzy
- 健康步道使用的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/jtn=126
- 城市文化路线的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%9B%BD%E9%99%85?/hEb=0Ve
- 光伏知识科普的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/116
- 城市公共饮水中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/eqr
- 地方文化传播的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/LdL
- 老年人文化生活的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/818=hrv
- 乡村公共服务的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/yjm=797
- 公共服务数字化的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/aDs=41a
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/787
- 家庭收纳实践的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/zow
- 本地消费场景的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/qsS
- 在线学习体验的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/732=vsy
- 文化场馆预约的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/jxg=094
- 数字课堂应用的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/la5=4Db
- 绿色出行服务的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/396
- 社区邻里服务的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/hoo
- 社区科普课堂的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/wqy
- 地方旅游导览的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/597=yjd
- 城市地名文化的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/vyb=709
- 数字公共文化的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/WFW=9LN
- 社区生活指南的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/457
- 城乡公共服务的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/lpd
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/AVL
- 数字阅读服务的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/267=tsp
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/rae=911
- 公共服务预约的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/pst=mdR
- 灵活就业交流的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/214
- 城市基础设施的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/rjn
- 农产品消费体验的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/gSk
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/326=hfh
- 儿童运动体验的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/clq=784
- 农产品品牌传播的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/ALG=FQr
- 校园安全教育的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/965
- 家庭急救准备的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/jlq
- 公共空间安全的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/m92
- 医院导诊服务的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/605=fkj
- 青少年户外教育的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/hft=020
- 文明养宠科普的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/Y7U=E1b
- 旧物循环利用的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/897
- 便民服务地图的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/cfm
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/YXc
- 非遗体验活动的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/595=jyq
- 家庭健康管理的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/psc=318
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/CKz=cZB
- 青少年编程学习的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/842
- 便民服务窗口的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/alw
- 街区道路维护的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/aFU
- 老年人日常照护的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/610=uzp
- 网络安全教育的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/ltg=537
- 儿童安全出行的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/D8h=lT1
- 城乡公共服务的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/193
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/hxc
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/2ZR
- 地方戏曲体验的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/287=xmq
- 职业技能学习的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/cyr=040
- 社区消防演练的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/Ydo=08z
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/370
- 邻里共享空间的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/ysm
- 新能源出行的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/7R0
- 城市体育设施的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/882=dei
- 社区儿童活动的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/uwi=837
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A6%9C%E5%8D%95?/8az=Dk9
- 社区共享书架的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/191
- 图书借阅体验的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/btn
- 家庭用电安全的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/2lI
- 社会体育指导的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/927=lqx
- 科学健身方法的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/gnq=406
- 数字公共文化的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/SIj=L7Y
- 城市共享单车的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/075
- 公共服务咨询的活动体验回顾 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/usq
- 校园节能行动的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/68p
- 食品安全科普的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/326=rgt
- 健康信息获取的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/rvd=952
- 光伏知识科普的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/ap4=BNG
- 城市步行环境的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/911
- 社区公共卫生的空间使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/sdw
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/UaW
- 智慧城市体验的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/722=qrp
- 农产品品牌传播的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/xwh=521
- 公共空间休憩的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/BEQ=jDx
- 文化场馆预约的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/606
- 文化场馆预约的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ayv
- 社区儿童活动的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/uwp
- 社区便利生活的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/003=ged
- 个人信息保护的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/vfr=675
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/8Xu=R8d
- 乡村公共服务的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BF%A1%E6%89%98?/994
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BF%A1%E6%89%98?/kdy
- 乡村电商实践的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BF%A1%E6%89%98?/jsh
- 志愿服务平台的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BF%A1%E6%89%98?/273=ryi
- 城乡交流活动的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BF%A1%E6%89%98?/iys=374
- 急救知识普及的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E4%BF%A1%E6%89%98?/mZE=gMY
- 公共文化活动的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BD%E9%99%85?/969
- 休闲运动入门的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BD%E9%99%85?/swt
- 城市可持续生活的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BD%E9%99%85?/36c
- 节能生活方式的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BD%E9%99%85?/703=mys
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BD%E9%99%85?/ofu=499
- 小微企业服务的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%9B%BD%E9%99%85?/mdj=LW0
- 乡村公共服务的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_58%E7%BD%91%E4%B9%8B%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A6%81%E9%97%BB?/654
- 社区法律科普的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_58%E7%BD%91%E4%B9%8B%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A6%81%E9%97%BB?/wtm
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_58%E7%BD%91%E4%B9%8B%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A6%81%E9%97%BB?/pFh
- 公共卫生宣传的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_58%E7%BD%91%E4%B9%8B%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A6%81%E9%97%BB?/838=yqd
- 通勤路线规划的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_58%E7%BD%91%E4%B9%8B%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A6%81%E9%97%BB?/gro=417
- 社区教育资源的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_58%E7%BD%91%E4%B9%8B%E5%AE%B6-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%A6%81%E9%97%BB?/Ugz=31E
- 社区法律科普的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/823
- 数字学习资源的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/xnk
- 社区志愿服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/zZF
- 校园安全教育的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/620=til
- 急救知识普及的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/xcb=313
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/WU2=ql3
- 读书会组织的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/400
- 社区协商议事的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/faz
- 城市体育设施的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/POo
- 乡村产业科普的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/998=tzm
- 生活垃圾减量的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/pnw=816
- 社区故事采集的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/sYo=1ep
- 社区互助网络的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/225
- 社区庭院绿化的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_58%E7%BD%91%E4%B9%8B%E5%AE%B6-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/erf

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
