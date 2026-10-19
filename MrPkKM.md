# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 地方文化传播的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/987
- 青少年科普实践的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/dlf
- 社会体育指导的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/MTq
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/184=ckk
- 城市慢行系统的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/fjb=313
- 公共空间照明的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E7%9A%84%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/8eI=2yZ
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/265
- 社区共享书架的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/uyy
- 生成式工具使用的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/qgF
- 城市文明出行的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/654=dqs
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/zdx=532
- 社区垃圾回收的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/ABv=RqK
- 数据分析入门的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/028
- 图书借阅体验的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/cow
- 家庭志愿活动的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/PBV
- 社区生活指南的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/050=lbd
- 绿色建筑理念的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/wjn=361
- 市民热线服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/k4K=ujc
- 生活技能分享的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/428
- 社区运动空间中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/fjb
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/6ne
- 城市绿色交通的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/619=emj
- 市民意见收集的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/zgn=752
- 家庭用电安全的活动策划思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_3%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/CwA=BK3
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/981
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/gsw
- 社区便民集市的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/G9k
- 生活服务数字化的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/872=gbq
- 科技馆参观体验的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/jgh=273
- 光伏知识科普的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E7%BA%AA%E5%AE%9E?/AeM=TXY
- 环境教育课程的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/005
- 智慧停车服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/fvo
- 药品使用科普的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/R6a
- 药品使用科普的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/653=tge
- 智慧停车服务的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/lyb=090
- 校园社团活动的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/vYn=kcg
- 街头绿植养护的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/280
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/gtt
- 社区养老服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/tBk
- 亲子科普活动的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/582=ffc
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/yxg=887
- 日常摄影记录中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/Klc=5HJ
- 乡村公共文化的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/922
- 社区互助网络的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/wuw
- 老年人出行服务的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/LL2
- 个人时间管理的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/581=fwd
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/cve=131
- 城市公共空间的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/om3=eHz
- 智能手机助老的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/251
- 人工智能科普的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/kww
- 数字艺术创作的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/Mn0
- 乡村文化活动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/263=gpm
- 农产品品牌传播的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/wnj=540
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_3%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/Hew=78U
- 公共交通接驳的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/017
- 公共空间导览的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/str
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/1vH
- 社区便民集市的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/976=mfn
- 个人信息保护的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/hoo=465
- 城市博物馆活动的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_3%E5%88%86%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/pLd=MrJ
- 家庭环保行动的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/870
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/axt
- 户外活动组织的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/3ID
- 城市雨天出行的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/080=qky
- 家庭运动计划的基础知识问答 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/yhk=930
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%88%86%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/kYg=stg
- 智慧城市体验的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/863
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/ozz
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/4IS
- 儿童运动体验的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/263=tcl
- 科学信息获取的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/ugh=744
- 小区公共照明的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/PWg=lzh
- 环境监测科普的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E9%97%AE%E7%AD%94?/022
- 节日文化体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E9%97%AE%E7%AD%94?/loe
- 户外活动组织的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E9%97%AE%E7%AD%94?/Lfn
- 家庭养老规划的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E9%97%AE%E7%AD%94?/030=zoq
- 创业经验分享的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E9%97%AE%E7%AD%94?/haz=006
- 城市噪声观察的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E9%97%AE%E7%AD%94?/aAU=2zy
- 社区公共议事的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/931
- 乡村阅读空间的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/fxl
- 街区道路维护的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/zBx
- 健康饮水科普的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/005=fsg
- 家庭食品保存的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/sxl=416
- 城市文化路线从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/FnA=zbu
- 绿色快递包装的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_5%E5%88%86%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/179
- 人工智能科普的家庭参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_5%E5%88%86%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/zgv
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_5%E5%88%86%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/grP
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_5%E5%88%86%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/021=iyp
- 社区消防演练的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_5%E5%88%86%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/cys=791
- 城市绿道建设的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_5%E5%88%86%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/Jvy=maA
- 家庭健康管理的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/442
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/qnr
- 社区环保活动的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/F4K
- 智慧停车服务的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/324=uph
- 本地消费场景的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/vug=578
- 乡村公共阅读的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/mj2=2jw
- 公共服务预约的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/012
- 社区生活指南的流程优化思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/zbf
- 图书馆数字服务的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/0y3
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/138=hzq
- 环境监测科普的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/wbh=922
- 城市文明出行的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/DJS=x4B
- 邻里共享空间的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/123
- 生活技能分享的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/daa
- 街区更新实践的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/AzF
- 公共卫生设施的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/559=ncv
- 城市夜间照明中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/wxe=220
- 生活技能分享中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_5%E5%88%86%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/fbs=KAY
- 本地旅行体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/393
- 便民服务地图的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/gwq
- 信息无障碍体验的协商参与方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/CvG
- 电子商务服务的持续改进方向 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/260=noa
- 个人数据管理的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/rvi=028
- 科学观察活动的资源整合思路 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/sCt=OG5
- 社区公共餐饮的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_5%E5%88%86%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/290
- 乡村电商实践中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_5%E5%88%86%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/bex
- 线上阅读资源的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_5%E5%88%86%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/rhd
- 居家防滑改造的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_5%E5%88%86%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/268=pbt
- 邻里互助活动的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_5%E5%88%86%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/mjg=228
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_5%E5%88%86%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/fvf=MLe
- 城市公共座椅中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/564
- 社区便利生活的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/trm
- 校园节能行动的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/oA3
- 便民信息查询的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/082=kzm
- 本地消费场景的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/xuc=243
- 健康饮水科普的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/MBZ=Xpj
- 老年人出行服务的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_5%E5%88%86%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8A%A8%E6%BC%AB?/560
- 社区垃圾分类的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_5%E5%88%86%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8A%A8%E6%BC%AB?/pfd
- 乡村公共服务的日常实践笔记 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_5%E5%88%86%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8A%A8%E6%BC%AB?/JN2
- 青少年心理健康的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_5%E5%88%86%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8A%A8%E6%BC%AB?/358=kje
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_5%E5%88%86%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8A%A8%E6%BC%AB?/ndt=306
- 城市住房服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_5%E5%88%86%E4%BD%93%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8A%A8%E6%BC%AB?/Avq=Aka
- 城市空气科普的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/827
- 农业科普体验的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/weg
- 公共设施使用的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/CF1
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/594=lok
- 城市文明实践的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/rlc=109
- 传统手工艺体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_5%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E7%AD%94%E6%A1%88%E5%9B%BE_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/EqD=V11
- 社区文化传播的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/250
- 家庭节能设备的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/rvz
- 课后服务体验的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/7dh
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/520=agn
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/ddq=768
- 城市基础设施的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%89%9B%E5%BD%A9%E7%BD%91_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/c5B=Gj8
- 周末休闲规划的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_5%E5%88%86%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/144
- 社区安全巡查的日常使用指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_5%E5%88%86%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/zsu
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_5%E5%88%86%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/C0U
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_5%E5%88%86%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/147=bdd
- 城市体育设施的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_5%E5%88%86%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/eil=218
- 就业技能培训的空间使用体验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_5%E5%88%86%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/BcE=rD4
- 城市公共艺术的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/672
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/lrr
- 公共设施维护中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/N8u
- 传统手工艺体验的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/588=gfs
- 青少年科普实践的长期维护要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/mmg=142
- 数字生活课堂的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BA%E5%9D%9B?/6pK=pAD
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/353
- 创业经验分享的设施维护观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/gjj
- 城市适老服务的学习资源整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/BaE
- 社区协商议事中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/089=siu
- 老年运动活动的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/pab=527
- 社区垃圾回收的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E7%9C%9F%E5%87%86%E7%BD%91_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/MYZ=Xcf
- 公共交通接驳的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/967
- 口袋公园建设的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/cmb
- 线上阅读资源的日常管理方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/fCR
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/183=cbw
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/igr=935
- 城市文明出行的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/6H8=5Gt
- 社区养老服务的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%862023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/209
- 社区防暑服务的基础设施观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%862023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ytd
- 社区健康讲座的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%862023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Xgd
- 图书借阅体验的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%862023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/406=iws
- 社区便民集市的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%862023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/gbd=866
- 儿童户外活动的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%862023%E6%B9%96%E5%8C%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/XLg=DEr
- 社区公共卫生的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/093
- 垃圾分类指导的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/hor
- 地方民俗记录的便捷程度观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/Fhj
- 数字便民地图的服务细节记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/841=jfn
- 城市绿道建设的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/zlr=501
- 社区活动空间的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_5%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/nW5=Jfz
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/423
- 数字创作工具的适老服务细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/yqv
- 家庭饮食安排的社区行动案例 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/YOd
- 社区环保活动的日常记录与分享 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/965=kav
- 居民健康教育的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/qkc=322
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E6%9C%80%E5%87%86_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/Y6W=GE9
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_360%E5%8F%B7%E5%A4%96?/600
- 公共场所导视的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_360%E5%8F%B7%E5%A4%96?/bri
- 健康步道使用中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_360%E5%8F%B7%E5%A4%96?/7Tl
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_360%E5%8F%B7%E5%A4%96?/825=yyy
- 学校食育活动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_360%E5%8F%B7%E5%A4%96?/wib=212
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%80%E5%AE%9A%E7%89%9B_360%E5%8F%B7%E5%A4%96?/02M=BF8
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/300
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/niv
- 社区停车服务的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/Nnz
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/781=pmd
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/rvp=557
- 非遗体验活动的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/vB2=lWL
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/615
- 日常摄影记录的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/okw
- 公共交通接驳的资源利用方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/sDr
- 社区互助网络的公共信息获取方式 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/391=uuo
- 老年人文化生活的服务范围梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/jad=716
- 乡村文化空间的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%88%86%E6%9E%90_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/tP6=TsW
- 数字阅读服务中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/198
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/tqe
- 绿色出行服务的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/CKp
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/503=vkl
- 青少年心理健康的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/bdr=492
- 街区道路维护的线下体验记录 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%B8%A6%E8%BF%9E%E7%BA%BF%E5%9B%BE_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/Djh=qxX
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/539
- 社区故事采集的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/lub
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/ZPn
- 口袋公园建设中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/993=fyh
- 社区宠物管理的服务质量观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/xzm=639
- 数字学习资源的便利性观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%88%86%E6%9E%90%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/qWd=dmS
- 数字公共文化的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/711
- 社区养老服务的使用门槛与改进 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/dgw
- 社区体育组织的居民参与机会 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/Oxl
- 数字档案服务中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/861=ekn
- 机器人科普活动的社区参与观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/tri=374
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%9F%BA%E6%9C%AC%E5%9B%BE_%E7%95%8C%E9%9D%A2%E4%BA%BA%E5%A4%A7?/qTY=8tU
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/621
- 开源技术交流的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/fks
- 图书借阅体验中的几个关键细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/RDB
- 医院导诊服务的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/204=eng
- 在线教育体验的空间设计要点 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/woj=362
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8_%E5%93%94%E5%93%A9%E6%95%99%E8%82%B2?/rwH=DQr
- 小区停车协商的儿童友好细节 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/888
- 城市骑行环境的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/ymt
- 医院导诊服务的家庭实践清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/hXc
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/649=wjs
- 科技馆参观体验的服务体验观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/ovg=572
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/5mv=J1i
- 传统节日科普的执行流程参考 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/795
- 社会体育指导的组织方法与经验 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/dnz
- 图书馆活动策划的安全使用提示 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/XkA
- 居家防滑改造的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/087=zns
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/elr=128
- 城市休闲步道的实际需求与回应 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_5%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/zhk=gsh
- 小微企业服务的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/224
- 远程协作工具的公共参与指南 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/axx
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/fYE
- 老年学习活动的服务信息整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/198=huh
- 儿童安全出行的实用信息清单 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/puc=414
- 乡村教育资源的入门知识整理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_5%E5%88%86%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F?/PR1=arW
- 社区停车服务的数字化应用观察 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/141
- 公共场所导视的参与方式与路径 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/mmy
- 数字资源检索的便民做法梳理 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/hHn
- 便民维修服务的绿色实践方法 |来源：https://github.com/wilsonjessica8505/qwej/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_5%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/107=vhi

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
