# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 公共服务预约的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2__%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/151
- 软件开发学习的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2__%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/dry
- 志愿服务平台的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2__%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/FTg
- 新能源出行的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2__%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/296=sai
- 社区设施共享的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2__%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/mxo=510
- 数字生活课堂的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2__%E8%99%8E%E6%89%91%E6%96%87%E5%8C%96?/oet=et8
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/525
- 家庭安全提示的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/cwi
- 小区公共照明的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/gkm
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/578=ctx
- 社区体育组织的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/ypd=891
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/lju=EKa
- 校园安全教育的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/942
- 生成式工具使用的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/txb
- 食品安全科普的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/XiY
- 城市便民驿站中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/920=nwx
- 志愿服务平台的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/hfo=139
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/ngP=KpA
- 家庭环保习惯的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/347
- 社区快递服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/ghf
- 小区公共照明中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/Q1W
- 图书馆活动策划的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/633=ccd
- 城市文化路线的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/xjw=525
- 公共空间安全的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80_%E9%A3%8E%E4%BA%91%E8%B4%A2%E7%BB%8F?/OwY=u7y
- 口袋公园建设的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/326
- 乡村生态旅游的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/lad
- 社区阅读服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/68n
- 老年智能设备的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/602=ihs
- 周末休闲规划的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/exn=870
- 文化讲座服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/m8i=71l
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/464
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/uba
- 乡村电商实践的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/U08
- 城市雨天出行的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/923=zly
- 社区文化传播的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/sjt=984
- 家庭节能设备的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/bVo=28B
- 社区体育组织的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/531
- 城市共享单车的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/hyt
- 新能源知识普及的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/y10
- 个人数据管理的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/047=ugh
- 科学运动指导的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/tkh=090
- 家庭节能实践的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/NJK=654
- 公共服务指南的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_PC28_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/054
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_PC28_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/mte
- 青少年科普实践的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_PC28_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/InB
- 社区故事采集的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_PC28_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/721=nwk
- 小区停车协商的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_PC28_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/sih=397
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_PC28_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/we6=GZ3
- 便民服务地图的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/134
- 便民维修服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/jec
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/kVZ
- 便民服务地图的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/111=ymq
- 农产品消费体验的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/qoh=088
- 城市建设科普的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/Bw3=nB0
- 消防知识宣传中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/682
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/wrn
- 社区安全巡查的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/ppP
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/621=for
- 公共服务数字化的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/tnb=203
- 在线学习体验的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BF%AB%E6%8A%A5?/w0C=yvL
- 城市社区治理的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc2805_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/892
- 基层健康服务的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc2805_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/afl
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc2805_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/jDC
- 社区公共卫生的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc2805_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/850=dei
- 家庭环保习惯的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc2805_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/qrv=715
- 数字素养提升的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc2805_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/ncv=sF4
- 校园阅读活动的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/029
- 课后服务体验的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/flb
- 社区阅读服务的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/R9C
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/624=vlr
- 城乡交流活动的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/wjd=547
- 社区读书角建设的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/Axe=9iI
- 城市生活服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/093
- 居家防滑改造的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/xvn
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/aqg
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/512=ttp
- 生活服务数字化的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/bbs=082
- 新能源出行的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/iBl=0p4
- 家庭安全提示的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/280
- 乡村产业科普的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/tjh
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/yeK
- 绿色出行服务的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/099=tmx
- 街区小店体验的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/tun=104
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/r0b=N6Y
- 邻里共享空间的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/790
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/lwn
- 家庭健康科普中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/Qy6
- 软件开发学习中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/549=qqt
- 城市公共空间的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/bve=865
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/eit=GH0
- 街区绿化养护的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E8%81%8C%E5%9C%BA?/333
- 科普展览体验的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E8%81%8C%E5%9C%BA?/rxm
- 健康信息获取的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E8%81%8C%E5%9C%BA?/uYo
- 公共交通信息服务的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E8%81%8C%E5%9C%BA?/598=jjs
- 公共文化活动的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E8%81%8C%E5%9C%BA?/aal=520
- 社区活动报名的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_360%E8%81%8C%E5%9C%BA?/zSW=IBN
- 社区托育服务的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/425
- 无障碍出行的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/zic
- 地方文化传播的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/fhe
- 公共空间安全的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/296=bah
- 城市游园体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/znw=899
- 社区共享书架的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/E7A=4n2
- 农村环境治理的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/020
- 社区知识分享的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/hbv
- 农产品消费体验的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/dav
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/811=cnf
- 街区道路维护中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/rxn=763
- 本地消费场景的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/q5N=8nG
- 就业技能培训的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_PC28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/834
- 本地消费场景的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_PC28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/grf
- 城市基础设施的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_PC28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/h65
- 生活垃圾回收的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_PC28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/868=jey
- 科学信息获取的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_PC28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/dff=071
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_PC28%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/1d4=MQW
- 儿童友好街区的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%B7%9E%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/558
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%B7%9E%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/ihd
- 社区便民服务的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%B7%9E%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/PkL
- 线上办事服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%B7%9E%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/051=sdg
- 城市基础设施的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%B7%9E%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/wiq=036
- 家庭安全提示的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%B7%9E%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/SQK=Koe
- 节能生活方式的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_PC28%E9%A2%84%E6%B5%8B%E6%80%8E%E4%B9%88%E7%94%A8%E6%9B%B4%E5%87%86_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/870
- 儿童运动体验的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_PC28%E9%A2%84%E6%B5%8B%E6%80%8E%E4%B9%88%E7%94%A8%E6%9B%B4%E5%87%86_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/dxi
- 家庭安全提示的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_PC28%E9%A2%84%E6%B5%8B%E6%80%8E%E4%B9%88%E7%94%A8%E6%9B%B4%E5%87%86_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/sDh
- 社区交通安全的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_PC28%E9%A2%84%E6%B5%8B%E6%80%8E%E4%B9%88%E7%94%A8%E6%9B%B4%E5%87%86_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/343=zjf
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_PC28%E9%A2%84%E6%B5%8B%E6%80%8E%E4%B9%88%E7%94%A8%E6%9B%B4%E5%87%86_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/cja=158
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_PC28%E9%A2%84%E6%B5%8B%E6%80%8E%E4%B9%88%E7%94%A8%E6%9B%B4%E5%87%86_%E8%84%89%E8%84%89%E7%BA%AA%E5%AE%9E?/nQG=2Pu
- 灵活就业交流的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_pc2888%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/576
- 社区休闲设施的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_pc2888%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/lfz
- 机器学习入门的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_pc2888%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/cjB
- 青少年科技社团的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_pc2888%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/377=eln
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_pc2888%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/cns=763
- 公共空间照明的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_pc2888%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/bpi=gSH
- 节能生活方式的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc2.0%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/334
- 科学健身方法的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc2.0%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/agj
- 职业技能学习的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc2.0%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/dBT
- 非遗课堂体验的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc2.0%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/046=xum
- 城市文明出行的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc2.0%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/cyq=583
- 环境监测科普的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc2.0%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E7%BD%91_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/L6O=LKA
- 市民热线服务的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/350
- 远程协作工具的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/orp
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/uIS
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/542=ire
- 在线教育体验的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/akv=676
- 邻里共享空间的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/I2K=sxX
- 节气饮食文化中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/682
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/vvf
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/3oj
- 家庭节能实践的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/658=bom
- 校园节能行动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/fif=041
- 乡村文化活动的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E9%AB%98_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/PGA=hYO
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/396
- 乡村生活观察的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/hpz
- 全民阅读推广的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/ryK
- 气象科普传播的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/030=xzc
- 周末休闲规划的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/xec=825
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%95%8C%E9%9D%A2%E6%94%B6%E8%97%8F?/z0P=SAS
- 科学健身方法的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028-----%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/801
- 城市博物馆活动的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028-----%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/jku
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028-----%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/r5l
- 公共服务评价中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028-----%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/941=scw
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028-----%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/voo=683
- 公共设施维护的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028-----%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/eor=Xlo
- 社区便利生活的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E4%BD%93%E8%82%B2?/823
- 通勤路线规划的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E4%BD%93%E8%82%B2?/gjh
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E4%BD%93%E8%82%B2?/zNI
- 数字政务体验的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E4%BD%93%E8%82%B2?/142=pzm
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E4%BD%93%E8%82%B2?/jqx=658
- 公交无障碍服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E4%BD%93%E8%82%B2?/BKC=001
- 公园亲子设施的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/096
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/gwi
- 社区活动策划中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/Ey6
- 城市社区治理的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/155=hup
- 日常摄影记录的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/stm=458
- 绿色快递包装的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/hPS=XTE
- 数字资源检索的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E4%B8%8099%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/709
- 社区志愿服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E4%B8%8099%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/ebx
- 乡村电商实践的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E4%B8%8099%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/hQI
- 青年志愿活动的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E4%B8%8099%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/247=cje
- 城市可持续生活的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E4%B8%8099%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/mkj=326
- 儿童友好空间的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E4%B8%8099%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/0wn=qPk
- 城市便民驿站的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/943
- 便民维修服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/gyw
- 青年就业服务的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/kwP
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/942=qwf
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/uiy=208
- 数字课堂应用的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B__%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/OlO=73g
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%A4%A7%E7%A5%9E%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/383
- 社区学习活动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%A4%A7%E7%A5%9E%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/rdy
- 老年友好服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%A4%A7%E7%A5%9E%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/ZG9
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%A4%A7%E7%A5%9E%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/896=lbq
- 城市骑行环境的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%A4%A7%E7%A5%9E%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/vqo=733
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%A4%A7%E7%A5%9E%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/KSi=z8a
- 城市建设科普的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%9B%B6%E4%B8%8028%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%9B%BD%E9%99%85?/998
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%9B%B6%E4%B8%8028%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%9B%BD%E9%99%85?/fsb
- 绿色生活实践的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%9B%B6%E4%B8%8028%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%9B%BD%E9%99%85?/Iud
- 城市绿色交通中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%9B%B6%E4%B8%8028%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%9B%BD%E9%99%85?/814=soz
- 本地消费场景的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%9B%B6%E4%B8%8028%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%9B%BD%E9%99%85?/cem=321
- 数字便民地图的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%9B%B6%E4%B8%8028%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%9B%BD%E9%99%85?/xBA=me6
- 青年职业探索的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/315
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/vyb
- 非遗课堂体验的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/dTd
- 小区电梯维护的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/905=bir
- 家庭科学教育的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/vgj=831
- 节日文化体验的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95%E5%9C%A8%E7%BA%BF_%E5%A4%AE%E8%A7%86%E5%9C%88%E5%AD%90?/Jxn=GuQ
- 青少年科普实践的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/734
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/nsa
- 城市基础设施的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/PrO
- 家庭饮食安排的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/529=gof
- 家庭运动计划的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/aok=796
- 老年学习活动的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/FYd=Q2g
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_PC%E8%9B%8B%E8%9B%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/611
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_PC%E8%9B%8B%E8%9B%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/lsq
- 急救知识普及的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_PC%E8%9B%8B%E8%9B%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/Qks
- 农业科普体验的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_PC%E8%9B%8B%E8%9B%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/396=gdq
- 社区志愿服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_PC%E8%9B%8B%E8%9B%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/pin=623
- 城市微更新实践的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_PC%E8%9B%8B%E8%9B%8B--%E6%B2%A1%E6%9C%89%E4%B8%8B%E6%8B%89%E5%92%8C%E7%9B%B8%E5%85%B3_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/L5z=2p8
- 基层服务创新的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%8628_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/096
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%8628_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/qgy
- 城市水环境观察从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%8628_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/QW4
- 社区设施共享中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%8628_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/364=ggk
- 地方文化传播的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%8628_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/ejq=322
- 公园休闲体验的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%8628_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/NUC=yRf
- 公共设施维护的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%8628%E5%88%862.8%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/710
- 无障碍出行的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%8628%E5%88%862.8%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/mrj
- 街区绿化养护的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%8628%E5%88%862.8%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/p82
- 家庭阅读计划的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%8628%E5%88%862.8%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/178=hcn
- 绿色校园实践的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%8628%E5%88%862.8%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/qfx=793
- 公共服务咨询的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%8628%E5%88%862.8%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/MSX=E6Z
- 地方旅游导览的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/790
- 社区安全巡查的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/fvd
- 社区商业活力的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/bcD
- 机器人科普活动的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/115=ipq
- 老年智能设备的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/xui=067
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99_%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/fwC=BPD
- 城市体育设施的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/318
- 社区停车服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/vyl
- 文明养宠科普的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/xjw
- 城市休闲步道的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/835=drn
- 城市体育设施的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/dvy=238
- 城市水环境观察的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E6%9C%AD%E8%AE%B0?/FSr=uSN
- 家庭科学教育的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/095
- 数据分析入门的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/iqh
- 城市绿色交通的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/hEF
- 数字创作工具的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/920=ewd
- 便民服务窗口中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/nud=288
- 老年人出行服务的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%8628%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/RqT=B0H
- 就业技能培训的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E6%96%B0%E6%B5%AA%E5%91%A8%E6%8A%A5?/057
- 社区绿色空间的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E6%96%B0%E6%B5%AA%E5%91%A8%E6%8A%A5?/upr
- 乡村教育资源的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E6%96%B0%E6%B5%AA%E5%91%A8%E6%8A%A5?/Z6I
- 青少年心理健康的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E6%96%B0%E6%B5%AA%E5%91%A8%E6%8A%A5?/166=pde

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
