# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 光伏知识科普的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Ell-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/YLh
- 小区停车协商的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Ell-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/085=zdh
- 健康饮食教育的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Ell-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/uyl=230
- 个人时间管理的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Ell-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/N9K=HDc
- 灵活就业交流的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ell-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/408
- 生活技能分享的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ell-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/tdb
- 社区花园共建的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ell-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/H2k
- 读书会组织的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ell-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/543=syh
- 校园社团活动的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ell-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/tmm=842
- 社区设施共享的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ell-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/J2l=uzy
- 数字阅读服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ell-%E5%AE%98%E6%96%B9_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/610
- 智慧停车服务的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ell-%E5%AE%98%E6%96%B9_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/hfv
- 数字设备回收的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ell-%E5%AE%98%E6%96%B9_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/iZA
- 社区共享书架的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ell-%E5%AE%98%E6%96%B9_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/950=jkf
- 家庭养老规划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ell-%E5%AE%98%E6%96%B9_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/buz=994
- 社区商业活力的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9Ell-%E5%AE%98%E6%96%B9_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/ccA=Vih
- 公共服务预约的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/373
- 儿童友好街区的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/mqu
- 街区更新实践的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/Qac
- 科普展览体验的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/697=scu
- 城市住房服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/ycf=963
- 数字便民地图的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/sMI=LZ7
- 个人时间管理的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/540
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/lpf
- 电动汽车充电的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/yTb
- 绿色生活实践的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/974=ivc
- 数据分析入门的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/pqi=681
- 家庭环保习惯的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/7YZ=dBy
- 开放数据应用的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/899
- 乡村文化活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/cnw
- 食品配送体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/nWp
- 社区健康讲座的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/725=vld
- 社区活动空间的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/qvi=878
- 老年人日常照护的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9F%BA%E9%87%91?/2C5=MBU
- 公共场馆服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/157
- 科学信息获取的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/buh
- 儿童运动体验中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/M53
- 城乡交流活动的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/495=oia
- 城市便民驿站的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/ylz=703
- 公共空间导览的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/gqA=Vav
- 健康饮水科普的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/535
- 生成式工具使用的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/bid
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/9fj
- 社区环保活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/145=hkn
- 数字课堂应用的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/wcg=429
- 公园亲子设施的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E4%B9%A6%E7%94%BB?/8sP=cqo
- 城市微更新实践的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/212
- 节日文化体验的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/ade
- 社区信息发布的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/DIj
- 数字生活课堂的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/969=une
- 家庭健康科普的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/kul=097
- 社区公共卫生的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/Z94=cr7
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/670
- 志愿服务平台的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/qef
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/p1k
- 乡村教育资源的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/935=zwu
- 社区防暑服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/vlz=950
- 基层健康服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/QNz=Ues
- 青少年科普实践的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/365
- 城市便民驿站的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/gwe
- 城市夜间照明的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/PPK
- 安全出行教育的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/356=soe
- 社区托育服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/via=834
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/q18=e4k
- 乡村公共阅读的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/237
- 老年友好服务的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/fup
- 图书借阅体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/FOg
- 社区知识分享的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/351=cnl
- 农产品消费体验的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/mrf=769
- 城乡公共服务的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/JF2=Bzl
- 城市游园体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/973
- 社区故事采集的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/tof
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/2z4
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/536=ecr
- 家庭饮食安排的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/nmy=757
- 开源技术交流的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/fJn=ZdI
- 软件开发学习的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/798
- 社区托育服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/uuw
- 智慧停车服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/ZZK
- 城市基础设施的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/218=nxo
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/rld=940
- 智慧城市体验的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/dJL=D1Q
- 绿色校园实践的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/867
- 城市空气科普的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/iwu
- 家庭阅读计划的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/E1i
- 家庭照护支持的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/125=ywm
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/yle=157
- 开放式学习空间中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/Mts=ogz
- 社区休闲设施的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/902
- 机器学习入门的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/cdk
- 青少年户外教育的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/LHW
- 公共服务评价的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/628=dic
- 社区商业活力的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/ovg=536
- 数字生活课堂的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/NmH=fQ5
- 节能生活方式的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/515
- 校园社团活动的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/uer
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/HQQ
- 家庭用电安全的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/975=xjk
- 家庭阅读计划的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/gvm=338
- 城市文明实践的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%A8%B1%E4%B9%90?/MwB=Ahk
- 开放数据应用的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/868
- 非遗体验活动的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/acg
- 数字艺术创作的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/4ZV
- 儿童运动体验的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/724=xzb
- 城市生活服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/crt=295
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/G2A=PGM
- 休闲运动入门的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/324
- 科技馆参观体验的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/ioc
- 校园社团活动的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/e2i
- 小区电梯维护的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/088=mdw
- 社区设施共享的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/khc=352
- 开源技术交流的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/Fpt=gB5
- 科学健身方法的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/914
- 社区故事采集的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/twc
- 数字支付体验的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/Mwx
- 老年数字阅读的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/765=rsb
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/iuk=479
- 新能源出行从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/OZn=2bH
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/242
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/vhl
- 街头绿植养护的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/UEz
- 数字档案服务的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/443=nqg
- 社区快递服务的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/hxo=240
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/u6V=HfI
- 创业经验分享的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/058
- 城市公共饮水的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/ztp
- 城市基础设施的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/RTw
- 邻里共享空间的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/990=cik
- 小区电梯维护的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/mlv=950
- 市民热线服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/Cyl=SW9
- 城市社区治理的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/201
- 新能源出行的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/fks
- 科学教育活动的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/WjH
- 线上阅读资源的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/073=qex
- 远程协作工具中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/sns=377
- 机器人科普活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/5i0=qX9
- 城市住房服务中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/266
- 城市公共饮水的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/orr
- 口袋公园建设的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/c99
- 乡村公共服务的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/918=yle
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/hfr=334
- 全民阅读推广的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/3Mh=rxP
- 生活垃圾减量的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/378
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/fvy
- 科学教育活动的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/ovf
- 老年人文化生活的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/507=xur
- 农产品消费体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/sxz=260
- 城市夜间照明的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/UPF=P6Z
- 社区共享书架的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/361
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/fvm
- 公共场馆服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/fsO
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/263=gst
- 社区便民服务的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/utk=722
- 社区健康讲座的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/Vk6=9CU
- 乡村教育资源的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/678
- 小微企业服务的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/wlh
- 城市雨天出行的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/6xv
- 急救知识普及的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/658=kpg
- 开源技术交流的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/hvg=334
- 街头绿植养护的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/9YD=VO7
- 社区法律科普的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/462
- 家庭节能设备的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/ldf
- 公共卫生宣传的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/VKd
- 在线教育体验的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/020=qyv
- 休闲运动入门的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/smv=463
- 社区交通安全的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B6%88%E8%B4%B9?/Z7F=56T
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/879
- 数字公共文化的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/uuf
- 家庭环保习惯的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/7je
- 骑行路线规划的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/974=wfo
- 数字创作工具的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/nov=140
- 社区教育资源的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/qeW=B1o
- 数字支付体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/246
- 社区法律科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/rfs
- 老年人出行服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/Xbv
- 社区便利生活的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/637=umb
- 公园无障碍服务的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/krj=606
- 社区设施共享的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%91%A8%E6%8A%A5?/PT0=mM6
- 公交站点体验的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/737
- 街区绿化养护的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/mqb
- 机器学习入门的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/HBC
- 社区文化传播的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/557=dcc
- 环境教育课程的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/byd=641
- 物业服务沟通的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/UjG=5B4
- 城市步行友好的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/864
- 志愿者培训交流的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/eox
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/lJ9
- 非遗体验活动的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/887=ift
- 气象科普传播的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/nfr=504
- 小区公共照明的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/6Lc=kRR
- 租房信息服务的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E6%B0%91%E7%94%9F?/004
- 地方美食文化的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E6%B0%91%E7%94%9F?/rhs
- 社区休闲设施的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E6%B0%91%E7%94%9F?/EVo
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E6%B0%91%E7%94%9F?/770=bpk
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E6%B0%91%E7%94%9F?/xnf=549
- 垃圾分类指导的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E6%B0%91%E7%94%9F?/I5T=E3d
- 药品使用科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/674
- 乡村生态观察的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/flq
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/hZ2
- 环境教育课程的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/013=qsp
- 志愿服务平台的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/hyd=176
- 城市公共厕所中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evlll-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/LBt=8qB
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/240
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/hvj
- 校园社团活动的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/t0f
- 社区环保活动的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/401=ldr
- 乡村产业科普的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/mdz=958
- 安全出行教育的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evlll-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/oWj=OEl
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/208
- 社区公共议事的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/bfu
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/UfX
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/742=knq
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/tak=886
- 远程协作工具的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%A0%E7%89%A9?/PoR=Aom
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-APP_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/098
- 公益活动组织的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-APP_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/plf
- 城市公共自行车的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-APP_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/kiP
- 社区商业活力的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-APP_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/762=cgd
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-APP_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/bpw=932
- 小区电梯维护的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-APP_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/ncm=8aC
- 农贸市场环境的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C?/735
- 社区体育组织的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C?/upg
- 家庭运动计划的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C?/UKK
- 公共空间照明的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C?/893=peq
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C?/ijf=667
- 公共空间休憩的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evlll-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C?/a93=Xtq
- 乡村文化活动的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/169
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/qft
- 就业技能培训的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/Y7b
- 在线学习体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/817=jlo
- 科学运动指导的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/kno=071
- 城市噪声观察的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%AE%89%E9%98%B2?/hvl=xMl
- 农产品品牌传播的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/049
- 数字公共文化的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/kxu
- 社区志愿服务的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/oT8
- 基层健康服务的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/141=bzg
- 乡村公共文化的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/woh=551
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9Evlll-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%86%9B%E4%BA%8B?/R53=OIe
- 城市公共空间的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evlll-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/593
- 小区停车协商的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evlll-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/otm
- 非遗体验活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evlll-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/AFy
- 公共空间休憩的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evlll-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/639=jzb
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evlll-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/knr=022
- 公共空间照明中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evlll-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/0U2=ahQ
- 社区志愿服务的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Evlll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/198
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Evlll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/zqd
- 基层健康档案的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Evlll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/LLY
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Evlll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/573=clu
- 智能家居应用的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Evlll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/vug=455
- 社区修缮行动的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Evlll-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/Ssi=c7h

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
