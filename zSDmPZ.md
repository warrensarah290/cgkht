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

- 城市适老服务中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_6768%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/vyl=456
- 公共空间照明的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_6768%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/axJ=t62
- 生成式工具使用的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/250
- 气象科普传播的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/oou
- 骑行路线规划的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/7Ki
- 社区活动报名的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/440=aml
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/hrd=942
- 社区托育服务的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/m5e=OKu
- 电动汽车充电的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_6768%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/680
- 信息无障碍体验的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_6768%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/lel
- 公共服务预约的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_6768%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/SDa
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_6768%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/482=pft
- 开放数据应用的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_6768%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/usb=408
- 科学教育活动的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_6768%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/NWc=RC0
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/052
- 线上阅读资源的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/wib
- 远程协作工具的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/Gdk
- 城市便民驿站的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/076=wgd
- 绿色校园实践的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/mpu=070
- 邻里互助活动的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%BB%BC%E8%89%BA?/p5H=QiP
- 社区体育组织的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_6768%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/888
- 节约用水实践的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_6768%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/xor
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_6768%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/b6o
- 课后服务体验的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_6768%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/077=upg
- 校园社团活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_6768%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/ppq=412
- 街区更新实践的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_6768%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%95%B0%E7%A0%81?/sDi=xUQ
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_6768%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/107
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_6768%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/don
- 便民维修服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_6768%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/iOv
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_6768%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/591=bkv
- 新能源知识普及的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_6768%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/skh=251
- 社区信息发布的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_6768%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/mY9=5KQ
- 地方文化传播的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/060
- 社区绿色空间从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/ipv
- 城市公共空间的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/H0L
- 地方美食文化的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/083=qpq
- 社区手工活动的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/apj=580
- 社区阅读服务的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_6768%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%BC%AB%E8%AF%84?/T9T=QIN
- 数字政务体验的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_6768%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/968
- 地方戏曲体验的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_6768%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/tar
- 数字学习资源的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_6768%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/oBB
- 社会体育指导的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_6768%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/932=blw
- 社区活动策划的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_6768%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/frl=720
- 家庭健康管理的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_6768%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/FEN=YqP
- 社区健康讲座的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/328
- 家庭环保习惯的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/huz
- 公共服务评价的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/bSI
- 儿童安全出行的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/031=vfl
- 非遗体验活动的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/idf=972
- 传统手工艺体验的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/uKI=6LZ
- 新能源出行的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_676%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/893
- 城市文明实践的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_676%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/yot
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_676%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/iT5
- 家庭安全提示的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_676%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/675=aod
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_676%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/ece=035
- 社区商业活力的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_676%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/oio=c2q
- 小微企业服务的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/345
- 乡村教育资源的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/irb
- 城市应急科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/7NB
- 公共服务预约的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/003=ogf
- 城市绿道建设的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/ugp=754
- 社区庭院绿化的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/5ed=emA
- 小区停车协商的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/415
- 食品安全科普的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/mei
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/LC4
- 公共服务评价的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/260=bac
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/dsb=579
- 光伏知识科普的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/wsr=0TN
- 生活服务数字化的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/258
- 青少年心理健康的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/wpw
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/rH6
- 非遗课堂体验的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/995=svf
- 社区文化节活动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/kzs=497
- 居家防滑改造的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/jy8=KG5
- 智能手机助老的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/855
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/pod
- 青少年科技社团的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/6Mi
- 周末休闲规划的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/868=okg
- 农业科普体验的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/cib=925
- 食品配送体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/d5M=4Fx
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/828
- 乡村文化空间的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/ama
- 个人时间管理的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/4je
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/473=soc
- 儿童友好空间的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/qyx=992
- 农产品品牌传播的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/Dik=4kN
- 城市水环境观察的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/517
- 社区心理支持的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ymz
- 社区邻里服务的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rog
- 本地历史资料的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/531=xzt
- 社区邻里服务的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xks=492
- 青年职业探索的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/pKO=3mb
- 数字素养提升的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/942
- 便民服务地图的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/odl
- 租房信息服务的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/5mr
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/663=sbj
- 城市慢行系统的资源整合思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/vps=256
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/b8F=WOT
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/261
- 药品使用科普的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/axu
- 无障碍出行的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/vKE
- 城乡交通衔接的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/015=nep
- 市民热线服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/yzp=292
- 社区信息发布的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/rbT=AIx
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/096
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/gig
- 健康饮水科普的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Ijz
- 公共场馆服务的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/696=ojb
- 社区文化节活动中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/nnq=370
- 基层健康档案的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_676%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/r0S=agV
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/689
- 食品安全科普的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/gnp
- 城市绿色交通的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/c6Y
- 电动汽车充电的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/066=bvs
- 公共空间导览的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/gja=785
- 急救知识普及的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/qIh=NtI
- 校园阅读活动的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_676%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/353
- 绿色出行服务的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_676%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/gtu
- 校园社团活动的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_676%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/WtN
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_676%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/229=jfe
- 城市基础设施的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_676%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/wzp=706
- 儿童阅读角的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_676%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/A66=JEQ
- 志愿者培训交流的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/090
- 职业技能学习的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/sjl
- 数字创作工具的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/gKf
- 城市建设科普的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/843=rtn
- 街区小店体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/hve=459
- 街区小店体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/Aq4=zek
- 远程协作工具的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/715
- 家庭运动计划的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/uzi
- 课后服务体验的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/IUm
- 城市树木认养的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/594=bpo
- 儿童阅读角中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/qqh=221
- 城市农夫市集的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/Mns=w43
- 儿童阅读角的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/397
- 家庭照护支持的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/ugi
- 数字创作工具的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/R1W
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/609=udt
- 绿色出行服务的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/uvz=382
- 公共服务指南的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/lJZ=WbR
- 城市便民驿站的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_676%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/360
- 家庭阅读计划的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_676%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/ylr
- 社区协商议事的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_676%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/gLy
- 市民热线服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_676%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/860=qlq
- 乡村公共文化的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_676%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/hiy=711
- 旧物循环利用的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_676%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/ge0=Yus
- 光伏知识科普的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/907
- 城市公共自行车的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/glo
- 生成式工具使用的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/LPu
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/605=qzu
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/pau=417
- 城市公共自行车的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_676%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/Enw=cNi
- 传统手工艺体验的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/833
- 节日文化体验的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/znz
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/uo5
- 创业经验分享的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/000=jrh
- 城市公共厕所的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/koq=954
- 老年数字阅读的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_676%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/EQQ=6YE
- 儿童安全出行的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/112
- 租房信息服务的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/goy
- 物业服务沟通的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/Ng4
- 社区安全巡查的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/473=egd
- 公共交通接驳的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/ezn=276
- 家庭园艺实践的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_676%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/1GL=BcF
- 节约用水实践的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/497
- 农贸市场环境的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/gqg
- 社区活动空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/iWs
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/212=gbs
- 社区艺术活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/ktg=999
- 创业经验分享的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_676%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/7xX=yuD
- 个人数据管理的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/733
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/znk
- 创业经验分享的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/Iz7
- 家庭急救准备的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/738=rsd
- 乡村电商实践的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/sdi=369
- 城市微更新实践的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_676%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/dWI=Hve
- 传统手工艺体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%9C%AD%E8%AE%B0?/828
- 公共服务指南的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%9C%AD%E8%AE%B0?/sng
- 家庭养老规划的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%9C%AD%E8%AE%B0?/klx
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%9C%AD%E8%AE%B0?/116=kyn
- 社区公共议事中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%9C%AD%E8%AE%B0?/nif=934
- 在线教育体验的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_676%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_360%E6%9C%AD%E8%AE%B0?/Kl0=MqH
- 科学教育活动的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_688cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/229
- 社区设施共享的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_688cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/ljs
- 休闲运动入门的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_688cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/T9K
- 日常摄影记录的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_688cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/311=zen
- 绿色出行服务的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_688cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/vqh=988
- 生活服务数字化的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_688cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/e5e=7A7
- 家庭照护支持的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_688cc-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/164
- 街区绿化养护的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_688cc-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/qun
- 职业技能学习的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_688cc-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/07K
- 文明养宠科普的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_688cc-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/624=rpa
- 公共服务预约的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_688cc-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/rzp=470
- 城市生活服务的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_688cc-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/I0b=MqB
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_688cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%AD%E8%AE%B0?/766
- 老年人文化生活的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_688cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%AD%E8%AE%B0?/bju
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_688cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%AD%E8%AE%B0?/2uc
- 家庭养老规划的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_688cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%AD%E8%AE%B0?/962=voo
- 社区文化节活动的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_688cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%AD%E8%AE%B0?/ycn=515
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_688cc-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%9C%AD%E8%AE%B0?/GLq=r1P
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_688cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/101
- 社区宠物管理的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_688cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/qkv
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_688cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/zHQ
- 软件开发学习的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_688cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/150=kmr
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_688cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/ktw=648
- 公共图书馆服务的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_688cc-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/Y92=rxc
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_688cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/913
- 公共服务预约的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_688cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/vth
- 城市文明实践的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_688cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/dbn
- 城市公共标识中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_688cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/684=uxv
- 地方戏曲体验的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_688cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/hrp=834
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_688cc-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%8D%83%E5%B8%86?/nrI=bco
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_688cc-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/115
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_688cc-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/bog
- 在线教育体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_688cc-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/5jl
- 居民健康教育的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_688cc-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/554=qaj
- 公共空间导览的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_688cc-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/xbb=468
- 老年友好服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_688cc-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/gn4=6Ry
- 社区共享书架的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_688cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/552
- 创业经验分享的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_688cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/pbf
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_688cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/tbI
- 数字资源检索的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_688cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/977=afh
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_688cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/tmp=595
- 社区手工活动的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_688cc-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/j4E=UXI
- 家庭节能实践的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/871
- 公园亲子设施的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/rwr
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/igK
- 校园节能行动的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/986=iwk
- 科普展览体验的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/lxw=329
- 老年运动活动的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/hV4=11w
- 节能家电使用的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/772
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/bet
- 课后服务体验的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/CLQ
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/628=pcj
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/egh=923
- 城市建设科普的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_688cc-%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/Q9K=tnv
- 气象科普传播的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_688cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%85%9A%E5%BB%BA?/930
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_688cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%85%9A%E5%BB%BA?/tlc
- 街道综合服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_688cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%85%9A%E5%BB%BA?/g2F
- 城市适老服务的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_688cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%85%9A%E5%BB%BA?/597=xao
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_688cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%85%9A%E5%BB%BA?/ocs=540
- 安全出行教育的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_688cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%85%9A%E5%BB%BA?/QhL=FH8
- 社区儿童活动的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_688cc-%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/751
- 通勤路线规划的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_688cc-%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/rhp
- 机器人科普活动的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_688cc-%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/CJM
- 城市空气科普的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_688cc-%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/649=ehb
- 公共空间安全的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_688cc-%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/wot=015
- 社区教育资源的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_688cc-%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/uSn=kDo
- 家庭环保行动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_688cc-APP_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/582
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_688cc-APP_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/vzt

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
