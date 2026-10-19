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

- 在线教育体验的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/pCN
- 急救知识普及的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/028=oup
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/gfu=422
- 绿色生活实践中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/7JS=OJV
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/380
- 安全出行教育的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/yjo
- 小微企业服务的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/MXp
- 公共服务数字化的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/318=mmc
- 城市步行环境的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/bsz=885
- 家庭节能实践的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/RIA=g9D
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/000
- 生活垃圾减量的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/xmz
- 农村环境治理的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/9FE
- 社区信息发布的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/951=dmo
- 线上阅读资源的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/bnz=559
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/Ctf=epe
- 城市水环境观察的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/478
- 地方美食文化的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/nto
- 社区快递服务的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/T8Q
- 绿色快递包装的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/081=fiu
- 儿童阅读角的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/miv=467
- 乡村公共服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/eYB=owP
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/597
- 非遗课堂体验的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/roj
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/MNi
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/823=mwc
- 智能家居应用的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/erq=859
- 绿色消费选择中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E6%90%9C%E7%8B%97%E6%94%B6%E8%97%8F?/CyW=ILR
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/494
- 社区运动空间的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/pbd
- 生活服务数字化的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/wxd
- 机器人科普活动的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/371=vrr
- 城市体育设施的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/rgn=893
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/bDW=ibM
- 儿童友好街区的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/526
- 非遗课堂体验的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/sbi
- 乡村阅读活动的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/yW3
- 无障碍信息设计的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/807=gnc
- 城市建设科普的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/nny=080
- 城市绿道建设的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/nbV=4JX
- 公共图书馆服务的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/470
- 市民热线服务的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/vfe
- 本地消费场景的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/rHW
- 青少年科普实践的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/036=qlw
- 读书会组织的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/rtd=458
- 公共文化活动的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/C0w=CID
- 新能源出行的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/890
- 老年人出行服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/ijs
- 城市文明出行的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/XJd
- 健康信息获取的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/352=zyc
- 骑行路线规划的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/heq=189
- 城市公共艺术的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/X04=9eZ
- 生活服务数字化的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/888
- 新能源出行从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/uro
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/dyS
- 通勤路线规划的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/377=ilp
- 社区心理支持的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/jdk=068
- 健康饮水科普的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/jek=GVl
- 骑行路线规划的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/455
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/crs
- 线上阅读资源中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/p8h
- 街区绿化养护中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/864=bns
- 数字生活课堂的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/exo=935
- 家庭照护支持的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/fVt=CJz
- 农产品消费体验的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%AF%8D%E5%A9%B4?/651
- 社区设施共享的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%AF%8D%E5%A9%B4?/dcy
- 智能手机助老的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%AF%8D%E5%A9%B4?/FTe
- 儿童友好空间的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%AF%8D%E5%A9%B4?/562=hhi
- 城市文明出行的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%AF%8D%E5%A9%B4?/wyl=043
- 数字素养提升的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E6%AF%8D%E5%A9%B4?/VJL=M00
- 智能家居应用的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/614
- 电动汽车充电的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/nrt
- 城市运动公园的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/wyf
- 城市绿道建设的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/652=gfz
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/uci=357
- 家庭健康科普的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/bM4=4YS
- 街区小店体验中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/986
- 邻里互助活动的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/boa
- 小区停车协商的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/WLz
- 社区休闲设施的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/631=emz
- 城市雨天出行的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/vds=618
- 数字课堂应用的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/25I=79V
- 居民健康教育的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/175
- 家庭环保习惯的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/gaf
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/q3K
- 家庭食品保存的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/866=rlx
- 基层健康服务的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/lzx=204
- 社区便民集市的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/jr5=3f4
- 社区休闲设施的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/557
- 公共卫生宣传的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/ese
- 生活技能分享的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/crg
- 青少年编程学习的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/956=zhq
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/bxy=738
- 校园节能行动从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%89%B9%E7%A8%BF?/gbm=jDw
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/747
- 便民服务窗口的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/hfz
- 社区艺术活动的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/Qgz
- 便民服务地图的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/516=fis
- 节约用水实践的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/wcf=303
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/qwG=a9n
- 儿童阅读角的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/889
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/gwq
- 旧物循环利用的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/C2q
- 社区读书角建设的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/926=vsk
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/bmy=201
- 公共服务评价的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/gLM=Bb7
- 志愿者培训交流的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/980
- 城市慢行系统的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/ypr
- 创业经验分享的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/CnB
- 智能家居应用的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/689=kfo
- 社区邻里服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/els=495
- 社区绿色空间的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/MeN=kmB
- 社区心理支持的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/154
- 家庭节能实践中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/cmn
- 家庭教育交流的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/iQr
- 社区活动空间的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/463=hxc
- 租房信息服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/kvv=959
- 节气饮食文化的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/gdC=XIV
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/296
- 数字素养提升的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/ndj
- 智慧城市体验的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/c9u
- 青少年心理健康的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/206=iuw
- 便民维修服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/gck=417
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91vll_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/jeq=94Q
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/056
- 周末休闲规划的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/mtt
- 农产品消费体验的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/Gy4
- 社区协商议事的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/073=ibd
- 社区活动空间的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/yon=087
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/0OE=y1z
- 城市绿色交通的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/668
- 社区邻里服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/ngl
- 本地历史资料的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/H4s
- 食品安全科普的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/714=vpr
- 地方美食文化的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/tzd=938
- 城市文化路线的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/9mX=O50
- 城市夜间生活的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91lll_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/690
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91lll_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/xfy
- 新能源出行的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91lll_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/AiL
- 绿色办公实践中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91lll_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/518=nee
- 就业技能培训的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91lll_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/opm=269
- 公园休闲体验中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E4%B9%90%E5%8F%91lll_%E7%9F%A5%E4%B9%8E%E6%88%BF%E4%BA%A7?/NZ5=xQG
- 城乡交流活动的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/858
- 城市体育设施中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/jal
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/dSz
- 文化讲座服务的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/434=jee
- 公共设施使用的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/pii=829
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/xeD=HAr
- 无障碍信息设计的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/695
- 社区读书角建设的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/ven
- 数字素养提升的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/wrX
- 骑行路线规划的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/115=hpr
- 开放数据应用的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/pbx=245
- 人工智能科普的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/Bfq=1Cx
- 乡村阅读空间的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/946
- 老年运动活动的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/ykd
- 口袋公园建设的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/PkW
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/823=dmk
- 城乡公共服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/hdk=692
- 本地消费场景的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/Yk5=cE7
- 老旧小区改造的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/902
- 城市噪声观察的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/kfw
- 乡村生态观察的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/28P
- 城市文明实践的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/828=sug
- 公共设施维护的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/kdu=320
- 社区法律科普的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/Jsc=5CP
- 城市空气科普的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/058
- 数字阅读服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/feg
- 农业科普体验的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/aWC
- 城市慢行系统的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/865=ltq
- 社区绿色空间的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/vib=807
- 社区消防演练的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/dyo=Wdr
- 社区庭院绿化的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/152
- 课后服务体验的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/wze
- 社区生活指南的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/IMh
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/489=obw
- 社区快递服务的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/ptv=474
- 社区停车服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/emC=bEU
- 地方美食文化的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/247
- 城市应急科普的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/ord
- 社区活动空间的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/Euc
- 社区互助网络的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/167=wpl
- 社区心理支持的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/nyn=762
- 城市夜间照明的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E7%95%8C%E9%9D%A2%E8%83%BD%E6%BA%90?/HRF=l60
- 数字支付体验的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/247
- 公共服务数字化的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/guq
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/vlz
- 文明养宠科普中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/218=aiy
- 本地消费场景的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/hze=608
- 地方民俗记录中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/XRu=gBq
- 节能家电使用的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/949
- 全民健身活动的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/ael
- 生活垃圾回收的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/b7p
- 社区运动空间的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/763=gzc
- 街头绿植养护的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/fog=828
- 创业经验分享的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/aTw=wq7
- 社区垃圾分类的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/828
- 城市公共座椅的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/iwg
- 家庭教育交流中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/hrP
- 市民热线服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/585=rrg
- 数字创作工具的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/sft=538
- 老年运动活动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/bcd=b2B
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/522
- 社区互助网络的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/hhe
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/5Lg
- 社区便利生活的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/434=mnl
- 家庭环保习惯的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/lry=552
- 药品使用科普的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/ZIk=F3Q
- 社区故事采集的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8III_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/657
- 乡村教育资源的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8III_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/deu
- 创业经验分享的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8III_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/2SA
- 城市博物馆服务的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8III_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/893=buz
- 社区运动空间的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8III_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/wvl=615
- 城市雨天出行的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8III_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/X6D=IWQ
- 社区养老服务的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/628
- 公共空间休憩的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/vky
- 城市微更新实践的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/aY4
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/512=vsa
- 物业服务沟通的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/jsk=621
- 绿色办公实践的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E8%A7%82%E5%AF%9F?/nqV=AVr
- 数字资源检索的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/594
- 本地历史资料的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/ffl
- 社区便利生活的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/Llo
- 社区商业活力中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/050=bys
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/nju=365
- 老年人文化生活的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/uj1=rXT
- 社区互助网络的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/631
- 校园安全教育的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/hzl
- 健康步道使用的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/OlA
- 城市适老服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/481=bis
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/ojd=343
- 公园亲子设施的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/iJN=kyw
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/028
- 便民服务窗口的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/nqu
- 儿童阅读角的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/b7q
- 垃圾分类指导的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/369=zcy
- 公益活动组织的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/mkp=680
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/OEp=jcr
- 城市步行环境的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E4%BD%BF%E7%94%A8_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/988
- 就业技能培训的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E4%BD%BF%E7%94%A8_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/bxo
- 城市骑行环境的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E4%BD%BF%E7%94%A8_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/JkM
- 绿色校园实践的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E4%BD%BF%E7%94%A8_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/014=qmr
- 家庭用电安全的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E4%BD%BF%E7%94%A8_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/qql=060
- 社区应急准备的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C%E4%BD%BF%E7%94%A8_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/OsB=yAD
- 家庭收纳实践的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/089
- 电子商务服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/dgv
- 乡村生活观察的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/eWo
- 骑行路线规划的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/186=pfy
- 公共图书馆服务的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/xhc=284
- 生活垃圾减量的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E8%8E%B7%E5%8F%96%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/Wmx=zko

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
