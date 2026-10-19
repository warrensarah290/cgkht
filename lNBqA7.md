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

- 社区宣传栏更新的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_135cc-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/378
- 儿童友好空间的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_135cc-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/xgo
- 节能生活方式的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_135cc-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/MzL
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_135cc-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/007=vte
- 城市文明出行的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_135cc-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/edp=674
- 环境教育课程的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_135cc-%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/nMJ=VWj
- 城市公共饮水的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/093
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/dcb
- 在线教育体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/xzj
- 绿色生活实践的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/926=flf
- 科学教育活动的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/tqw=293
- 本地历史资料的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/0gQ=ery
- 城市噪声观察的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/169
- 数字便民地图的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/abe
- 城市慢行系统的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/dwh
- 城市生活记录的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/613=dif
- 农村环境治理的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/vmq=653
- 健康饮食教育的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%95%B0%E7%A0%81?/fdS=NI8
- 线上办事服务的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/852
- 家庭安全提示的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/anw
- 城市文明出行的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/xkz
- 城市公共空间的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/998=ffw
- 社区花园共建的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/nvt=958
- 青少年科普实践的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/078=hkO
- 志愿服务平台的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/467
- 绿色生活实践的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/gxk
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/CKf
- 家庭用电安全的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/540=nrx
- 城市步行环境的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/ojr=599
- 青少年科普实践的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/39i=DzD
- 线上阅读资源的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_135cc-%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/963
- 健康信息获取的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_135cc-%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/voz
- 网络安全教育中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_135cc-%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/pjd
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_135cc-%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/102=oav
- 乡村公共服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_135cc-%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/hca=591
- 绿色办公实践的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_135cc-%E9%A6%96%E9%A1%B5_360%E7%A8%8E%E5%8A%A1?/OJ2=ZTE
- 社区休闲设施的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_135cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/134
- 健康信息获取的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_135cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/nsl
- 软件开发学习的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_135cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/qQ3
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_135cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/124=rey
- 城市夜间照明的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_135cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/sng=701
- 便民维修服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_135cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/Eho=n68
- 便民服务地图的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/192
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/pur
- 社区便利生活的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/nW0
- 城市绿色交通的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/034=ssf
- 社区宠物管理的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/mji=429
- 城市公共标识的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/ohM=fIp
- 乡村公共服务的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/842
- 基层健康档案的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/unb
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/63M
- 读书会组织的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/851=ulg
- 职业技能学习的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/nzx=395
- 绿色建筑理念的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/O3d=YrA
- 社区体育组织的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/552
- 安全出行教育的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/mdf
- 城市公共标识的服务范围梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/fWD
- 本地旅行体验的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/215=irk
- 城市运动公园的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/cst=243
- 公园亲子设施的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/jZq=XFk
- 社区志愿服务的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/933
- 社区法律科普的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/isn
- 公共设施使用的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/hIj
- 环境教育课程的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/864=tns
- 数字公共文化的绿色实践方法 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/hvd=118
- 家庭阅读计划的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/r8n=oBX
- 健康信息获取的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/801
- 公共交通接驳的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/per
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/Ffs
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/683=xwk
- 青少年科普实践的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/ymn=932
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%81%A5%E8%BA%AB?/ktW=3Hx
- 数字阅读服务的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/939
- 数字支付体验的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/iat
- 科学运动指导的服务信息整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/dlE
- 数字资源检索的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/191=ukl
- 医院导诊服务的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/qmm=926
- 农产品消费体验的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%BA%E5%A4%A7?/zjv=7I8
- 城市步行环境的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/144
- 社区安全巡查的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/zat
- 社区运动空间的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/g4r
- 社区设施共享的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/240=wfl
- 智慧城市体验的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/ggc=074
- 儿童友好空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/ccm=smg
- 居家适老化改造的空间设计要点 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/284
- 家庭用电安全的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/tbr
- 开放式学习空间的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/eVH
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/214=exs
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/tqk=309
- 开放数据应用的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/ztG=bEu
- 城市生活记录的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/274
- 社区体育组织的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/pmw
- 公共场馆服务的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/AVW
- 公共空间安全的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/726=vnp
- 老年数字阅读的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/irm=071
- 新能源出行的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%A1%A3%E6%A1%88?/mzd=Rv4
- 食品配送体验的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/019
- 家庭教育交流的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/adr
- 公共服务评价的活动组织技巧 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/Rye
- 在线教育体验的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/830=zoh
- 科学观察活动的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/slm=610
- 绿色办公实践的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/xvl=5cc
- 电子商务服务的参与方式与路径 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/119
- 社区故事采集的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/doc
- 图书借阅体验的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/A6G
- 乡村教育资源的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/575=csx
- 城市绿道建设的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/hck=792
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%A8%E6%8A%A5?/YPg=JVW
- 社区停车服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/235
- 社区读书角建设的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/yco
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/sPw
- 公共服务沟通的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/145=oag
- 公共服务数字化的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/blr=157
- 家庭节能设备的设施维护观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/qnU=UHv
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/097
- 校园节能行动的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/qpa
- 图书借阅体验的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/wAR
- 个人时间管理中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/797=let
- 家庭志愿活动的日常管理方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/nkv=940
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/TJd=azv
- 环境监测科普的长期维护要点 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/916
- 家庭安全提示的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/mvh
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/0Xt
- 低碳社区实践的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/824=wic
- 社区交通安全的入门知识整理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/few=325
- 文化讲座服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/pMI=Pd0
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/607
- 城乡公共服务的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/aan
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/ky7
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/623=hmm
- 健康饮食教育的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/vnm=399
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/otq=Z9M
- 安全出行教育的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/621
- 社区互助网络的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/qsw
- 城市社区治理的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/EKo
- 数字设备回收的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/912=paj
- 数字创意课程的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/onq=224
- 青少年户外教育的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/nqp=ucc
- 家庭用电安全的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/160
- 城市共享单车的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/biq
- 公共空间安全的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/2lD
- 小微企业服务的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/514=mbe
- 便民维修服务中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/vgy=594
- 城市应急科普的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/vLI=T0m
- 社区托育服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/526
- 城市基础设施的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/itj
- 家庭食品保存的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/Pfr
- 乡村文化空间的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/028=wsb
- 课后服务体验的线下体验记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/reo=730
- 绿色建筑理念的社区参与观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%81%8C%E5%9C%BA?/fHs=Gym
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/709
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/zkt
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/CmO
- 科学运动指导的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/277=lfb
- 课后服务体验的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/txv=049
- 城市人文观察的服务体验观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/J9o=g3F
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/815
- 社区健康讲座的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/qpt
- 社区托育服务的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/nEx
- 数字创作工具的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/477=lpb
- 城市慢跑路线的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/xaj=468
- 全民健身活动的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%BE%9F%E8%B0%A3?/RbP=yqC
- 数字档案服务的常见误区提醒 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/968
- 数字课堂应用的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/czz
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/VxV
- 数字课堂应用的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/043=dwe
- 电子商务服务的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/fpx=372
- 食品安全科普的数字化应用观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/ZCf=3GP
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/857
- 社区读书角建设的实际需求与回应 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/cid
- 社区信息发布中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/UXF
- 城市体育设施中的几个关键细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/122=fnc
- 城市建设科普的实用信息清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/gka=559
- 运动安全知识的流程优化思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E6%97%B6%E8%AE%AF?/ILV=l8m
- 青年职业探索的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/686
- 街道综合服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/xql
- 公共空间照明的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/246
- 公共卫生设施的基础设施观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/319=jss
- 城市农夫市集的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/keh=020
- 城市公共艺术的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/UUl=n4a
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9C%B0%E6%96%B9?/948
- 街区小店体验的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9C%B0%E6%96%B9?/oyo
- 绿色校园实践的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9C%B0%E6%96%B9?/vEc
- 租房信息服务的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9C%B0%E6%96%B9?/496=uci
- 城市基础设施的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9C%B0%E6%96%B9?/wae=255
- 社区慢性病防控的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E5%9C%B0%E6%96%B9?/u8O=JAv
- 居民健康教育的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/163
- 城乡交流活动的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/gih
- 儿童运动体验的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/jE8
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/006=npq
- 在线学习体验的便利性观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/vih=717
- 公共服务咨询的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/aaq=u1j
- 开放式学习空间的协作机制梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/011
- 公共场所导视的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/scg
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/E8X
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/911=rbb
- 开放数据应用的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/wtu=451
- 科学信息获取的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/2O4=tDr
- 社区故事采集的公共信息获取方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/948
- 青年就业服务的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/dky
- 农业科普体验的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/JxJ
- 街区道路维护的居民参与机会 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/454=smu
- 小区电梯维护的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/rkq=395
- 公交站点体验的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E5%9B%AD%E8%89%BA?/WTR=fVv
- 城市博物馆活动的社区行动案例 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/589
- 节能家电使用的家庭参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/hkm
- 社区家政服务的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/4ct
- 乡村产业科普的基础知识问答 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/310=nur
- 科学健身方法的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/ojp=816
- 老年人文化生活的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/UcM=0pk
- 城市农夫市集的执行流程参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/602
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/ohl
- 家庭运动计划的安全使用提示 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/TSm
- 网络信息辨识的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/033=oiz
- 本地旅行体验的服务细节记录 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/lyo=664
- 便民服务地图的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E8%A7%A3%E5%AF%86?/0P3=iCz
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/505
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/fys
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/fYg
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/888=fxk
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/egd=642
- 社区垃圾回收的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E9%A3%9F%E5%93%81?/pM5=KPy
- 城市绿道建设的日常记录与分享 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_1368%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/836
- 节假日出行安排的日常使用指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_1368%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/pxf
- 城市博物馆活动的服务质量观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_1368%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/nNB
- 节日文化体验的持续改进方向 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_1368%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/253=ckw
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_1368%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/tme=823
- 电动汽车充电的行动步骤参考 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_1368%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E7%95%85%E6%B8%B8?/XdI=Y6f
- 城市步行友好的家庭实践清单 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1368%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/500
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1368%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/fea
- 安全出行教育的适老服务细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1368%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/4Ls
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1368%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/675=wyx
- 公共服务预约的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1368%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/nac=884
- 日常摄影记录的日常实践笔记 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1368%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/6vC=RNG
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%99%BE%E7%A7%91?/027
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%99%BE%E7%A7%91?/ymt
- 城市文明出行的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%99%BE%E7%A7%91?/EHM
- 社区垃圾回收的公共参与指南 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%99%BE%E7%A7%91?/769=ocy
- 社区文化传播的组织方法与经验 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%99%BE%E7%A7%91?/vef=375
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E7%99%BE%E7%A7%91?/IvJ=MXr
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1368%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/407
- 通勤路线规划的资源利用方法 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1368%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/pvg
- 城市共享单车的儿童友好细节 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1368%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/02L
- 开放数据应用的活动体验回顾 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1368%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/338=mkl
- 基层健康服务的阅读与学习资源 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1368%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/epa=800
- 儿童户外活动的便捷程度观察 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_1368%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/vNB=kLK
- 基层健康档案中的沟通与协作 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/860
- 户外活动组织的活动策划思路 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/mzo
- 社区知识分享的便民做法梳理 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/p1M
- 城市博物馆服务的协商参与方式 |来源：https://github.com/olsonbilly11/danm/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/297=yfq

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
