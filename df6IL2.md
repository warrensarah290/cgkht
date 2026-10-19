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

- 低碳社区实践的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/988
- 城市建设科普的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/qnq
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/Cib
- 社区应急准备的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/062=qnf
- 城市公共饮水的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/dbq=417
- 家庭节能实践的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/9is=xOz
- 休闲运动入门的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/078
- 市民热线服务的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/fcc
- 城市体育设施的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/sDF
- 公交站点体验的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/834=ikp
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/pvp=985
- 乡村生态旅游的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/gdC=EaF
- 城市便民驿站的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/835
- 老年运动活动的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/pds
- 校园节能行动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/QFd
- 社区法律科普的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/665=lyu
- 儿童阅读角的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/eum=817
- 城市适老服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/VNY=LHf
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/040
- 食品配送体验的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/psb
- 志愿服务平台的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/5BY
- 地方民俗记录的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/979=ixq
- 节约用水实践的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/ikv=169
- 数据分析入门的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/anw=w3Y
- 城市公共自行车的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/212
- 个人数据管理的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/mvy
- 社区托育服务的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/uUk
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/327=tjs
- 公交无障碍服务的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/flz=764
- 数字公共文化的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/KlE=YOc
- 社区休闲设施的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/794
- 城市体育设施的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/hii
- 家庭健康科普中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/ZeP
- 电动汽车充电的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/379=ohf
- 个人数据管理的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/ple=135
- 社区消防演练的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E6%96%B0%E6%B5%AA%E6%89%8B%E8%AE%B0?/JfH=xoz
- 校园社团活动的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/324
- 家庭用电安全的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/cjv
- 小区电梯维护的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/9tg
- 科学运动指导的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/836=ocp
- 街区小店体验的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/xwc=285
- 农业科普体验的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/rw7=IRw
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/324
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/olt
- 机器学习入门的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/Mnz
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/586=wwb
- 农村环境治理的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/fug=834
- 城乡公共服务的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/Qkk=RaD
- 社区法律科普的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89?/616
- 日常摄影记录的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89?/wel
- 城市生活服务的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89?/o1M
- 社区快递服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89?/395=xmm
- 居民健康教育的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89?/oxt=638
- 全民健身活动的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89?/PBq=nNf
- 城市人文观察的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/608
- 数字便民地图的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/roc
- 校园社团活动的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/GzT
- 家庭安全提示的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/492=exz
- 城乡交流活动的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/bbe=616
- 社区教育资源的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/Rmt=BSh
- 家庭环保习惯的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/340
- 社区生活指南的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/ynq
- 城市地名文化的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/daY
- 光伏知识科普的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/799=ivl
- 公园亲子设施的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/bpq=109
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/Vbz=Ewc
- 电子商务服务的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/450
- 社区家校合作的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/igx
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/500
- 家庭消费规划的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/205=ymy
- 社区文化传播的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/yse=641
- 城市运动公园的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E5%93%94%E5%93%A9%E5%A8%B1%E4%B9%90?/aqu=sGV
- 科学健身方法的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/142
- 绿色出行服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/hyu
- 学校体育活动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/FyQ
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/832=gph
- 街区更新实践的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/xrv=492
- 城市雨天出行的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/mVo=NfQ
- 数字资源检索的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/639
- 城市公共厕所的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/ook
- 家庭网络使用的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/ns4
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/886=lqe
- 城市住房服务的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/oti=197
- 家庭节能设备的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/Gdv=YbP
- 科学运动指导的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/420
- 数字学习资源的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/gkr
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/EgV
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/402=yqy
- 社区便利生活的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/kea=517
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/lSR=pEp
- 家庭网络使用的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/721
- 公益活动组织的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/qym
- 物业服务沟通的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/lfA
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/509=lmj
- 应急物资管理的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/ils=103
- 数字支付体验的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/YLB=UF9
- 无障碍信息设计的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/807
- 科普展览体验的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/oem
- 城市绿道建设的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/EFu
- 社区活动报名的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/764=aby
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/bgc=124
- 社区共享书架中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A8%8E%E5%8A%A1?/fRi=MLH
- 周末休闲规划的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq%E5%8F%B7_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/286
- 读书会组织从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq%E5%8F%B7_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/hdn
- 家庭运动计划的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq%E5%8F%B7_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/O1M
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq%E5%8F%B7_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/387=kby
- 社区养老服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq%E5%8F%B7_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/ytg=414
- 节日文化体验的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq%E5%8F%B7_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/Z56=DCw
- 老年学习活动的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/716
- 乡村公共文化的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fmi
- 乡村阅读空间的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/pSx
- 生活技能分享的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/078=qjz
- 便民服务地图的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dbn=173
- 基层医疗预约的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B0%81%E6%9C%89%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/c1m=kiq
- 社区共享书架的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/663
- 城市夜间生活的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/bjh
- 口袋公园建设的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/u6K
- 街区绿化养护的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/539=hgs
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/fgx=479
- 家庭食品保存的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/v6U=rzF
- 城市绿色交通有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/268
- 软件开发学习的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/olp
- 青少年户外教育从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/lHh
- 城市生活记录的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/490=acf
- 老年友好服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/rpr=344
- 食品安全科普的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/jPJ=a9O
- 社区艺术活动中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/591
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/xsr
- 社区教育资源的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/Afq
- 环境教育课程的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/349=dun
- 城市博物馆服务的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/vzp=681
- 安全出行教育中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/7wu=zEb
- 应急物资管理的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%89%B9%E9%82%80%E7%9F%AD%E4%BF%A1%E9%80%81%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/288
- 社区儿童活动的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%89%B9%E9%82%80%E7%9F%AD%E4%BF%A1%E9%80%81%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/ret
- 公共空间照明的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%89%B9%E9%82%80%E7%9F%AD%E4%BF%A1%E9%80%81%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/NA8
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%89%B9%E9%82%80%E7%9F%AD%E4%BF%A1%E9%80%81%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/305=pxc
- 城市展览体验的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%89%B9%E9%82%80%E7%9F%AD%E4%BF%A1%E9%80%81%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/wrg=916
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E7%89%B9%E9%82%80%E7%9F%AD%E4%BF%A1%E9%80%81%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/bEm=1C1
- 老年学习活动的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/826
- 医院导诊服务的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/tzk
- 开放式学习空间的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/NVQ
- 社区儿童活动的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/657=daz
- 健康步道使用的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/oes=228
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/9wL=7yU
- 儿童阅读角的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/830
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/zyn
- 机器人科普活动的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/ICo
- 社区便民服务的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/851=ltb
- 安全出行教育的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/wfd=712
- 社区生活指南的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/q37=gMe
- 社区知识分享的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91_360%E5%8A%A8%E6%BC%AB?/965
- 科学观察活动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91_360%E5%8A%A8%E6%BC%AB?/bqf
- 城市休闲步道的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91_360%E5%8A%A8%E6%BC%AB?/Oum
- 乡村电商实践的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91_360%E5%8A%A8%E6%BC%AB?/508=lcu
- 日常摄影记录的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91_360%E5%8A%A8%E6%BC%AB?/zbg=385
- 公交无障碍服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91_360%E5%8A%A8%E6%BC%AB?/V3K=IPi
- 电动汽车充电的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/406
- 街区绿化养护的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/nxo
- 药品使用科普的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/bLS
- 街区小店体验的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/824=sev
- 青少年编程学习的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/dnj=742
- 公共空间休憩的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%B3%BB%E5%88%97%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/wGI=FtA
- 老年学习活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/912
- 乡村教育资源的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/vlp
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/Unb
- 社区便民服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/863=vog
- 城市公共空间的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/oyd=365
- 公共图书馆服务的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/Utm=VEa
- 数字资源检索的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/082
- 新能源出行的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/vdd
- 居家防滑改造的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/2op
- 社区文化节活动的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/793=osn
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/ewo=934
- 居家防滑改造的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/DPy=cvc
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%BD%A9app_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/939
- 数字公共文化的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%BD%A9app_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/eym
- 食品安全科普的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%BD%A9app_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/lLt
- 城市住房服务的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%BD%A9app_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/487=rvv
- 校园阅读活动的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%BD%A9app_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/fdg=276
- 街区更新实践的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%BD%A9app_%E8%99%8E%E6%89%91%E6%AF%8D%E5%A9%B4?/RLW=NXF
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/162
- 公共服务预约的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/inp
- 亲子科普活动的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/3U2
- 城市公共厕所的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/065=asy
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/imm=115
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome_%E8%84%89%E8%84%89%E6%B8%AF%E8%82%A1?/HfD=Mba
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8F%91%E5%BD%A9-%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%9Eapp_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/685
- 城市展览体验的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8F%91%E5%BD%A9-%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%9Eapp_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/kil
- 图书馆亲子空间的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8F%91%E5%BD%A9-%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%9Eapp_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/Scx
- 节能家电使用的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8F%91%E5%BD%A9-%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%9Eapp_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/837=cfn
- 在线教育体验的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8F%91%E5%BD%A9-%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%9Eapp_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/sol=847
- 城市绿道建设的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8F%91%E5%BD%A9-%E5%A4%A7%E5%8F%91-%E5%BD%A9%E7%A5%9Eapp_%E6%8A%96%E9%9F%B3%E5%9B%9E%E6%9C%9B?/AkV=iH8
- 数据分析入门的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E8%BF%9B%E5%85%A5_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/077
- 数字生活课堂的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E8%BF%9B%E5%85%A5_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/gci
- 文化场馆预约的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E8%BF%9B%E5%85%A5_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/erK
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E8%BF%9B%E5%85%A5_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/097=qaa
- 城乡公共服务的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E8%BF%9B%E5%85%A5_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/tgo=437
- 市民意见收集的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E8%BF%9B%E5%85%A5_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/75K=JWy
- 街区更新实践的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8F%90%E5%89%8D%E5%BC%80%E5%A5%96%E8%A7%A3%E7%A0%81%E5%99%A8_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/430
- 医院导诊服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8F%90%E5%89%8D%E5%BC%80%E5%A5%96%E8%A7%A3%E7%A0%81%E5%99%A8_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/xcp
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8F%90%E5%89%8D%E5%BC%80%E5%A5%96%E8%A7%A3%E7%A0%81%E5%99%A8_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/sPe
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8F%90%E5%89%8D%E5%BC%80%E5%A5%96%E8%A7%A3%E7%A0%81%E5%99%A8_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/036=wqk
- 地方旅游导览的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8F%90%E5%89%8D%E5%BC%80%E5%A5%96%E8%A7%A3%E7%A0%81%E5%99%A8_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/dnw=693
- 街区绿化养护的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8F%90%E5%89%8D%E5%BC%80%E5%A5%96%E8%A7%A3%E7%A0%81%E5%99%A8_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/ouI=EQU
- 数字支付体验的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%97%A7%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/815
- 城市公共自行车的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%97%A7%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/mhr
- 社区活动报名的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%97%A7%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/OCm
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%97%A7%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/348=lpp
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%97%A7%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/xqi=236
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E6%97%A7%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%AD%E8%AE%B0?/ZsM=n6j
- 创业经验分享的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8iOSapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/218
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8iOSapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/fbc
- 公共服务评价的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8iOSapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/zSV
- 社区商业活力的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8iOSapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/294=cqi
- 城市骑行环境的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8iOSapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/tpe=341
- 老年友好服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8iOSapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%BB%BC%E8%89%BA?/HBP=T0A
- 街头绿植养护的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88app_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/911
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88app_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/efg
- 志愿服务平台的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88app_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/jSE
- 社区交通安全的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88app_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/805=vuv
- 光伏知识科普的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88app_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/gbw=004
- 乡村生态观察的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88app_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/r2G=WKp
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85app_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/314
- 绿色快递包装的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85app_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kek
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85app_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Ora
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85app_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/493=yfr
- 校园节能行动的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85app_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wke=821
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85app_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/MS1=8lG
- 社区共享书架的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/469
- 社区活动空间的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/vkm
- 生活技能分享的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/FO5
- 电子商务服务的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/119=pht
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/ikw=903
- 社区慢性病防控的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E6%8E%A2%E5%BA%97?/Gc8=8EP
- 校园安全教育的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/088
- 社区养老服务的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/ybb
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/AZk
- 乡村文化空间的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/074=fpw
- 社区养老服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/qee=835
- 生成式工具使用的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E6%98%9F%E5%BA%A7?/v3J=Dun
- 小区公共照明的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/307
- 老年运动活动的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/fzu
- 城市绿道建设的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/4xe
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/132=fly
- 社区艺术活动的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/sbp=646
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%8D%83%E5%B8%86?/UYR=mji
- 老年人文化生活的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/033
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/yyc
- 网络信息辨识的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/RID
- 城市生活记录的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/728=nfy

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
