# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 就业技能培训的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/c4l
- 生成式工具使用的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/863=bey
- 光伏知识科普的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/inq=295
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/cpT=aar
- 城市公共标识的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E2%85%A7l_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/626
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E2%85%A7l_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/hpk
- 城市休闲步道的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E2%85%A7l_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/C6W
- 读书会组织的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E2%85%A7l_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/834=vvm
- 街头绿植养护的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E2%85%A7l_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/fzf=944
- 课后服务体验的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%90%E5%8F%91%E2%85%A7l_%E7%9F%A5%E4%B9%8E%E8%BD%AC%E8%BD%BD?/SAC=iuc
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/844
- 家庭消费规划的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/nqt
- 节气饮食文化的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/rcC
- 地方旅游导览的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/819=yfm
- 城市绿道建设的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/jqw=592
- 乡村生态观察的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B6%88%E8%B4%B9?/Zlm=eei
- 城市运动公园的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/309
- 远程协作工具的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/sgu
- 便民维修服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/7HJ
- 基层健康服务的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/772=sid
- 基层健康服务的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/dbn=277
- 环境监测科普的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/abJ=BCq
- 地方民俗记录的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/981
- 智能手机助老的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/yvz
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/Y7S
- 职业技能学习的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/764=mxb
- 基层健康服务的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/fwo=033
- 健康信息获取的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/g3K=tXH
- 安全出行教育中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/617
- 绿色消费选择的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/hqr
- 骑行路线规划的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/pqn
- 户外活动组织的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/734=emz
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/hcc=913
- 公共服务指南的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/j4u=BYH
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91IIIV_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/036
- 数据分析入门的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91IIIV_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/chd
- 地方戏曲体验的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91IIIV_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/ltg
- 社区应急准备的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91IIIV_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/791=vsi
- 公园休闲体验的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91IIIV_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/lls=267
- 农贸市场环境的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91IIIV_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/vPh=Vyi
- 社区体育组织的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/286
- 本地历史资料的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/qgq
- 家庭饮食安排的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/mR5
- 社区阅读服务的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/812=qrd
- 社区菜市场服务的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/nvf=735
- 休闲运动入门的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E8%99%8E%E5%97%85%E4%BF%A1%E6%89%98?/GE8=0LM
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/796
- 智能手机助老的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/pno
- 家庭安全提示的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/ZS9
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/121=ubl
- 运动安全知识的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/ddc=963
- 科普展览体验的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/C0V=j9H
- 终身学习资源的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/722
- 城市树木认养的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/hgu
- 基层医疗预约的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/siL
- 本地消费场景的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/075=xjw
- 在线学习体验的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/mtu=713
- 乡村生态观察的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/ZPL=vsy
- 科技馆参观体验的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/382
- 生活服务数字化的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/wic
- 公共交通接驳的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/Pjl
- 公共文化活动的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/594=wod
- 公共设施维护的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/uav=224
- 公共服务沟通的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/TZA=BqT
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/016
- 智能手机助老的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/fab
- 城市文化路线的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/nef
- 地方文化传播的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/104=vge
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/ebi=235
- 公共空间安全的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/uFE=DJq
- 社区文化传播的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/190
- 市民意见收集的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/hyp
- 乡村电商实践的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/H29
- 社区家政服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/809=whi
- 社区活动空间的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/cln=207
- 社区活动报名的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/wTA=IdQ
- 青年职业探索的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/096
- 城市噪声观察的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/plh
- 社区信息发布的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/NHa
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/617=qha
- 城市住房服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/zzt=811
- 农村环境治理的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/nLS=FaM
- 家庭安全提示的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%8A%92%E6%9E%9C?/001
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%8A%92%E6%9E%9C?/lqj
- 乡村公共阅读的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%8A%92%E6%9E%9C?/5D2
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%8A%92%E6%9E%9C?/489=yvv
- 药品使用科普的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%8A%92%E6%9E%9C?/twu=152
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%8A%92%E6%9E%9C?/lry=YPv
- 小区停车协商的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/230
- 青少年科普实践的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/icj
- 老年友好服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/I4M
- 图书馆活动策划的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/068=uli
- 急救知识普及的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/pbc=473
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%85%BE%E8%AE%AF%E5%AE%8F%E8%A7%82?/zKK=86h
- 节能家电使用的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/075
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/tug
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/gHY
- 物业服务沟通的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/666=osc
- 公共设施使用的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/ozq=784
- 光伏知识科普的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/eM4=LmW
- 职业技能学习的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/977
- 城市休闲步道的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/trm
- 城市微更新实践的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/SlQ
- 小区公共照明的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/216=kyv
- 社区垃圾分类的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/xvo=992
- 物业服务沟通的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AE%AF?/RXl=Ze5
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/201
- 公共空间导览的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/tbo
- 城市空气科普的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/BU0
- 社区便民服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/289=thp
- 城市共享单车的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/gxe=776
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_36%E6%B0%AA%E7%A7%91%E6%8A%80?/Fqi=kiR
- 就业技能培训的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/877
- 城市生活记录的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/riz
- 老年友好服务的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/Nj5
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/442=yvl
- 家庭节能实践的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/biu=688
- 校园节能行动的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/IMz=23f
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91APP_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/621
- 智慧停车服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91APP_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/wxf
- 社区环保活动的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91APP_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/BFO
- 数字资源检索的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91APP_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/530=iut
- 城市可持续生活的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91APP_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/gmt=952
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91APP_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/e87=6WH
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%8F%91VII_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/064
- 青少年心理健康的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%8F%91VII_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/vtz
- 城市体育设施的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%8F%91VII_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/Ggk
- 社区读书角建设的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%8F%91VII_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/230=pea
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%8F%91VII_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/ypq=625
- 社区儿童活动的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B9%90%E5%8F%91VII_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/fKH=KvM
- 家庭健康管理的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91vI_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/735
- 乡村电商实践的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91vI_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/fcl
- 社区慢性病防控的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91vI_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/h9t
- 地方戏曲体验的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91vI_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/328=cio
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91vI_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/dnq=970
- 社区故事采集的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E4%B9%90%E5%8F%91vI_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/3re=oh2
- 城市慢跑路线的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/914
- 家庭健康管理从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/kmx
- 小微企业服务的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/aOt
- 线上阅读资源的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/033=rpu
- 社区活动策划的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/euw=078
- 基层健康服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%8F%91_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/hlS=m6F
- 家庭饮食安排的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/722
- 电子商务服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/xjf
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/1db
- 公共空间安全的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/547=faa
- 城市博物馆活动的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/mxu=413
- 社区停车服务的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/SSB=VW6
- 家庭急救准备的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/674
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/pdx
- 居家防滑改造的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/i7Q
- 城市社区治理的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/023=dox
- 周末休闲规划的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/yyb=826
- 日常摄影记录的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B1%87%E5%B8%82?/N6m=GzA
- 地方文化传播的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/561
- 数字阅读服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/tjh
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/GJc
- 图书借阅体验的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/492=vzj
- 数字生活课堂的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/tup=909
- 家庭运动计划的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/OV9=jFH
- 智能家居应用中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/972
- 学校食育活动的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/inl
- 地方文化传播的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/DlF
- 绿色办公实践的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/134=vvd
- 科学信息获取的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/nyl=830
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E4%B8%93%E6%A0%8F?/QdE=quA
- 便民信息查询的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/064
- 生活垃圾减量的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/uep
- 儿童阅读角的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/3ig
- 生活垃圾减量的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/797=zxu
- 社区防暑服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/qfk=545
- 城市展览体验的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%B2%E5%9D%9B?/Cus=shZ
- 儿童运动体验中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/253
- 全民健身活动的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/zkx
- 城乡交流活动的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/AxX
- 节约用水实践的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/512=wdy
- 社区养老服务的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/egj=325
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%86%9B%E4%BA%8B?/oSf=4a6
- 市民热线服务的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/895
- 家庭食品保存的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/mct
- 社区读书角建设的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/BwA
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/301=prx
- 社区休闲设施的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/vyl=388
- 智慧停车服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%AE%9E%E5%BD%95?/F1M=Kl2
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/953
- 社区故事采集的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/qog
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/UGV
- 城市运动公园的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/007=szx
- 文化场馆预约的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/xjm=187
- 灵活就业交流的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E8%8A%92%E6%9E%9C%E5%AE%A0%E7%89%A9?/zsR=JxX
- 个人信息保护的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/822
- 网络信息辨识的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/qog
- 个人时间管理的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/ybO
- 非遗课堂体验的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/425=wxm
- 公共卫生宣传的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/ubh=069
- 社区公共议事的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/qzL=6sP
- 社区垃圾分类的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/561
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/ggq
- 光伏知识科普的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/nLd
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/648=akp
- 城市游园体验的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/yje=436
- 公共文化活动的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/RMQ=p9I
- 老年智能设备的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/899
- 机器人科普活动的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/bni
- 社区防暑服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/FQz
- 绿色出行服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/512=tyk
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/cld=964
- 读书会组织的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/hw6=CEk
- 社区邻里服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B924%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/316
- 数字便民地图的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B924%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/bge
- 节气饮食文化的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B924%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/9ot
- 城市博物馆服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B924%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/712=qgu
- 科学观察活动的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B924%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/wrr=253
- 地方戏曲体验的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B924%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%81%8A%E5%A4%A9%E5%AE%A4_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/4h2=sbd
- 城市步行环境的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E7%BE%A4_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/829
- 本地旅行体验的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E7%BE%A4_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/okv
- 基层健康服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E7%BE%A4_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/wM6
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E7%BE%A4_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/089=acj
- 公园亲子设施的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E7%BE%A4_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/yzq=602
- 亲子阅读活动的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E7%BE%A4_%E6%BE%8E%E6%B9%83%E8%83%BD%E6%BA%90?/TX9=0oS
- 课后服务体验的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/755
- 城市微更新实践的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/hut
- 公共设施维护的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/lvz
- 家庭消费规划的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/249=maq
- 学校体育活动的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/jqi=157
- 环境教育课程的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/5zJ=Tpc
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E5%88%B0%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/741
- 社区垃圾分类的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E5%88%B0%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/yca
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E5%88%B0%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/qZ9
- 应急物资管理的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E5%88%B0%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/898=bjl
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E5%88%B0%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/tpj=228
- 非遗课堂体验的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%8E%E4%B9%88%E5%81%9A%E5%88%B0%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/iKK=859
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/282
- 青少年心理健康中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/smb
- 城市噪声观察的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/KWA
- 家庭志愿活动的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/600=deq
- 绿色办公实践的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/uln=298
- 青少年户外教育的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/n7n=PmS
- 社区邻里服务的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E4%BF%9D%E9%9A%9C%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/030
- 青少年科普实践的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E4%BF%9D%E9%9A%9C%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/ktz
- 社区设施共享的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E4%BF%9D%E9%9A%9C%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/YCB
- 家庭安全提示的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E4%BF%9D%E9%9A%9C%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/719=slv
- 城市共享单车的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E4%BF%9D%E9%9A%9C%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/uwn=353
- 校园社团活动的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E4%BF%9D%E9%9A%9C%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/cxA=Jrd
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/381
- 亲子阅读活动的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/lgi
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/aMo
- 社区交通安全的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/886=foh
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/ogr=630
- 公共健身器材的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97__%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/iRr=lpy

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
