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

- 青少年科技社团的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/272
- 机器学习入门的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/hio
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/pXQ
- 乡村电商实践的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/015=sgg
- 志愿者培训交流的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/vor=996
- 开放数据应用的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/29M=UEv
- 科学健身方法的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/121
- 科学信息获取的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/ehr
- 公园无障碍服务的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/ZLt
- 通勤路线规划的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/679=keq
- 公共文化活动的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/kms=158
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/vu6=77l
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/630
- 社区活动空间的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/yiq
- 小区停车协商的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/ieG
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/506=umr
- 城市夜间生活的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/kpl=949
- 智慧停车服务的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/Khl=GbQ
- 儿童安全出行的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/154
- 绿色校园实践的基础设施观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/odi
- 志愿服务平台的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/9QO
- 新能源知识普及的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/366=xgt
- 乡村教育资源的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/uad=518
- 城市生活服务的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/RYj=IKX
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/462
- 社区学习活动的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/wlu
- 灵活就业交流的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/5K1
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/109=ysz
- 城市空气科普的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/sok=044
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%90%86%E8%B4%A2?/dy0=LeJ
- 城市公共标识的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9~%E9%9B%86%E5%9B%A2_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/268
- 智能家居应用的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9~%E9%9B%86%E5%9B%A2_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/yic
- 安全出行教育的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9~%E9%9B%86%E5%9B%A2_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/U6w
- 乡村公共服务中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9~%E9%9B%86%E5%9B%A2_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/921=jca
- 城乡交流活动的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9~%E9%9B%86%E5%9B%A2_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/ejo=954
- 社区体育组织的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9~%E9%9B%86%E5%9B%A2_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/0XP=VgI
- 公共场馆服务的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/537
- 社区家校合作的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/xov
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/T1v
- 居民健康教育的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/432=cfx
- 城市公共自行车的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/ctb=581
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/NEN=Z8X
- 社区文化传播的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/837
- 灵活就业交流的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/xnm
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/HQP
- 无障碍出行中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/147=rey
- 本地历史资料的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/men=692
- 公共卫生宣传的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/edb=EFl
- 全民健身活动的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/857
- 城市运动公园的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/mux
- 城市社区治理的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/dty
- 生活技能分享的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/548=hqi
- 光伏知识科普的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/ywj=348
- 社区活动策划的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/74S=TB8
- 城市体育设施的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/428
- 个人时间管理的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/cla
- 智能家居应用的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/AB6
- 本地消费场景的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/358=msz
- 城市便民驿站的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/uvo=951
- 便民信息查询中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/2ue=638
- 本地消费场景的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/925
- 家庭用电安全的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/bcp
- 社区公共卫生的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/Qcc
- 科学运动指导的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/366=ccu
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/mxf=970
- 个人时间管理的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/Svk=36i
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/115
- 学校体育活动的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/rnf
- 社区教育资源的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/Tvp
- 城市基础设施的资源利用方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/839=jpk
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/hke=873
- 城市文明实践的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/S25=72Y
- 公共空间照明的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/133
- 社区志愿服务的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/blm
- 社区公共卫生的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/4o0
- 公共文化活动的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/314=duu
- 社区托育服务的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/fsg=172
- 绿色消费选择的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/jaY=8tk
- 青年就业服务的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/204
- 城市可持续生活的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/nfy
- 居民健康教育的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/C3M
- 社区故事采集的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/997=evt
- 老年人出行服务的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/dhr=851
- 家庭园艺实践的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E6%89%AC%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/MKY=vbZ
- 社区家校合作中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/487
- 物业服务沟通的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/mfc
- 物业服务沟通的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/MPa
- 城乡公共服务的入门知识整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/185=xlb
- 农贸市场环境的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/rog=163
- 日常摄影记录的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/vNN=B3I
- 终身学习资源的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/539
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/uoi
- 儿童运动体验中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/u36
- 公园休闲体验从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/368=vng
- 城市骑行环境的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/wyc=355
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C?/S7G=CRL
- 地方民俗记录的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/206
- 数字便民地图中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/fst
- 城市生活记录的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/UQP
- 公共健身器材的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/511=evz
- 节日文化体验的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/ply=798
- 乡村电商实践的参与方式与路径 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%9B%BE%E9%89%B4?/Cun=NbT
- 数字阅读服务的常见误区提醒 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/937
- 城市可持续生活的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/vnw
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/7NS
- 社区慢性病防控的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/371=mzo
- 开源技术交流的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/gcb=178
- 科普展览体验的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/kT1=GAS
- 城市住房服务的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90?/272
- 基层健康档案的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90?/qcp
- 地方文化传播的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90?/moZ
- 环境教育课程的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90?/215=mhx
- 线上阅读资源的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90?/wyx=877
- 骑行路线规划的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%89%9B%E7%89%9B%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90?/D4y=52g
- 数字档案服务的线下体验记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9app%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/509
- 青少年科普实践的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9app%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/rek
- 数字政务体验的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9app%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/aKC
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9app%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/405=itv
- 绿色快递包装中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9app%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/ssk=835
- 公共空间照明的服务质量观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9app%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/mD0=aEZ
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/665
- 校园节能行动的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/nnr
- 公共交通接驳的长期维护要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/AY3
- 生活垃圾减量的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/871=nro
- 无障碍出行的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/dgb=872
- 街区道路维护的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E4%B8%AD%E5%BF%83_%E5%A4%AE%E8%A7%86%E4%BF%9D%E9%99%A9?/gE6=q6C
- 健康信息获取的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/727
- 急救知识普及的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/nwi
- 读书会组织从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/l5R
- 灵活就业交流的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/241=vkl
- 电动汽车充电的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/hdu=506
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%8A%E4%BA%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/ZVd=JQL
- 网络安全教育的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/217
- 家庭健康管理的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/ari
- 基层医疗预约的实际需求与回应 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/Jie
- 公共场馆服务的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/503=uvm
- 市民意见收集的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/jkd=631
- 社区设施共享的儿童友好细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/BZC=Vcn
- 社区公共议事的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/827
- 家庭园艺实践的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/abv
- 个人数据管理的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/hi3
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/446=wgk
- 城市共享单车的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/yjn=003
- 城市夜间照明的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/Vdh=BAt
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/001
- 绿色生活实践的学习资源整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/fha
- 家庭养老规划的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/FWm
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/114=lcl
- 社区文化节活动的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/bcg=402
- 科学观察活动的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/uS3=O8g
- 口袋公园建设的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/831
- 公共服务沟通的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/zny
- 城市共享单车的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/Uve
- 居民健康教育的行动步骤参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/439=ogy
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/xyh=308
- 城市休闲步道的日常记录与分享 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/Nfj=exY
- 课后服务体验的协作机制梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88%E6%9C%AC_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/325
- 数字档案服务的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88%E6%9C%AC_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/gir
- 老年人出行服务的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88%E6%9C%AC_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/N7T
- 城市慢行系统的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88%E6%9C%AC_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/244=oco
- 绿色办公实践的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88%E6%9C%AC_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ndc=044
- 社区设施共享的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88%E6%9C%AC_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/eQY=kBO
- 社区活动空间的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/803
- 城市生活记录的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/hul
- 公共空间照明的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/GdZ
- 农产品品牌传播的基础知识问答 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/747=qzq
- 青少年科技社团的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/wuy=914
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/E0e=Ewg
- 社区便民集市的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/236
- 创业经验分享的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/cqj
- 家庭阅读计划的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/1gE
- 老年智能设备的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/501=kga
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/tri=150
- 城市游园体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/0aJ=bjz
- 科普展览体验的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-IOS%E7%89%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/067
- 城市夜间照明的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-IOS%E7%89%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/qxs
- 青少年科普实践的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-IOS%E7%89%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/DzW
- 家庭环保行动的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-IOS%E7%89%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/368=mjr
- 老年运动活动的执行流程参考 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-IOS%E7%89%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/wfu=637
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-IOS%E7%89%88_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/kFZ=sOb
- 就业技能培训的便民做法梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/629
- 科学信息获取的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/cvj
- 城市公共饮水的家庭参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/sk1
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/965=afo
- 公共服务指南的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/zww=332
- 公共服务数字化的数字化应用观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/Otz=UxA
- 社区养老服务的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/342
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/ykj
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/td1
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/221=djg
- 数字创意课程的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/ovd=486
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/Bbk=BQn
- 学校食育活动的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/276
- 气象科普传播的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/kqt
- 城市运动公园的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/1fM
- 个人数据管理的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/638=xun
- 城市共享单车的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/vjk=461
- 城市文明实践的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/r4Y=WRW
- 健康饮水科普中的几个关键细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9welcome_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/556
- 急救知识普及的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9welcome_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/jxp
- 小区公共照明的日常管理方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9welcome_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/9yB
- 青少年编程学习的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9welcome_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/177=bih
- 劳动教育实践的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9welcome_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/sjd=543
- 老年人日常照护的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9welcome_%E8%85%BE%E8%AE%AF%E6%95%B0%E7%A0%81?/ypu=4YZ
- 开放数据应用的服务体验观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/142
- 城市绿色交通的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/noo
- 儿童友好空间的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/jKs
- 城市慢行系统的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/295=xpu
- 节能家电使用的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/lyi=206
- 低碳社区实践的流程优化思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%BC%E8%89%BA?/FtY=Cvr
- 数字公共文化的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/310
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/wbo
- 公共设施维护的协商参与方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/wZA
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/088=rmc
- 街区小店体验的公共参与指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/bqz=431
- 城市游园体验的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/sLx=6Zu
- 学校体育活动的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/979
- 环境监测科普的活动策划思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/bdm
- 线上阅读资源的社区行动案例 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/W2M
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/782=qgj
- 社区阅读服务的家庭实践清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/abh=056
- 城市展览体验的绿色实践方法 |来源：https://github.com/fergusondiamond3/adnd/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/6hl=Ang
- 食品配送体验的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/920
- 城市运动公园的安全使用提示 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/onl
- 社区快递服务的公共信息获取方式 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/ngx
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/302=zcz
- 开源技术交流的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/bze=043
- 社区协商议事的服务细节记录 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/lSx=jwx
- 开放数据应用的居民参与机会 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%97%A7%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/302
- 社区体育组织的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%97%A7%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/myt
- 老年友好服务的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%97%A7%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/JFa
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%97%A7%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/452=emz
- 社区公共议事的适老服务细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%97%A7%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/dnn=298
- 居家防滑改造的常见问题梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E6%97%A7%E7%89%88%E6%9C%AC_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/ywU=OqN
- 城市绿道建设的资源整合思路 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-APP%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/277
- 智能手机助老的设施维护观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-APP%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/tdt
- 数字档案服务的服务信息整理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-APP%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/2Sz
- 城市步行友好的实用信息清单 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-APP%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/615=mus
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-APP%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/quo=424
- 城市公共标识的空间设计要点 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-APP%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/L5m=G1c
- 数字创作工具的组织方法与经验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/933
- 乡村公共阅读的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/kmo
- 公共设施使用的社区参与观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/xIN
- 新能源出行的阅读与学习资源 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/028=fdi
- 数字创意课程的日常使用指南 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/oxi=380
- 科学信息获取的便捷程度观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%BA%B2%E5%AD%90?/7zc=Wsu
- 城市基础设施的数字工具使用体验 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E8%BE%9F%E8%B0%A3?/830
- 城乡交流活动的服务范围梳理 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E8%BE%9F%E8%B0%A3?/inr
- 城市展览体验的持续改进方向 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E8%BE%9F%E8%B0%A3?/o4N
- 街道综合服务的便利性观察 |来源：https://github.com/fergusondiamond3/adnd/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E8%BE%9F%E8%B0%A3?/029=mkf

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
