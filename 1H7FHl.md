# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 社区信息发布的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/swf=405
- 家庭运动计划的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/z51=O8q
- 城市文明实践的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A2%AB%E5%9B%BD%E5%AE%B6%E6%AD%A3%E5%BC%8F%E5%85%B3%E9%97%AD%E4%BA%86%E5%90%97_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/889
- 公共服务咨询的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A2%AB%E5%9B%BD%E5%AE%B6%E6%AD%A3%E5%BC%8F%E5%85%B3%E9%97%AD%E4%BA%86%E5%90%97_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/zis
- 生成式工具使用的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A2%AB%E5%9B%BD%E5%AE%B6%E6%AD%A3%E5%BC%8F%E5%85%B3%E9%97%AD%E4%BA%86%E5%90%97_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/oNo
- 远程协作工具的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A2%AB%E5%9B%BD%E5%AE%B6%E6%AD%A3%E5%BC%8F%E5%85%B3%E9%97%AD%E4%BA%86%E5%90%97_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/827=ryl
- 图书馆数字服务的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A2%AB%E5%9B%BD%E5%AE%B6%E6%AD%A3%E5%BC%8F%E5%85%B3%E9%97%AD%E4%BA%86%E5%90%97_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/aye=935
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A2%AB%E5%9B%BD%E5%AE%B6%E6%AD%A3%E5%BC%8F%E5%85%B3%E9%97%AD%E4%BA%86%E5%90%97_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/Z13=mws
- 本地消费场景的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/318
- 乡村教育资源的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ntn
- 邻里共享空间的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/mVV
- 社区互助网络的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/265=tkf
- 社区故事采集的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/jls=091
- 公共服务预约的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/qKG=ZLn
- 亲子阅读活动的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/423
- 老年人出行服务的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/fpw
- 城乡交流活动的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/hPx
- 城市应急广播的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/315=nch
- 无障碍出行的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/gve=265
- 休闲运动入门的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/BoB=AZe
- 青年志愿活动的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/229
- 个人时间管理的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/kpr
- 老年数字阅读的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/kTf
- 药品使用科普的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/224=lcr
- 智慧城市体验的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/pon=304
- 社区便民集市的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/cDK=jvp
- 租房信息服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/598
- 社区邻里服务的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/lrb
- 人工智能科普的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/Tmq
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/695=exk
- 光伏知识科普的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/qdu=147
- 在线教育体验的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%91%8A?/A8e=o1G
- 社区志愿服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8we_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/987
- 城市空气科普的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8we_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/ala
- 周末休闲规划的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8we_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/9gm
- 公交无障碍服务的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8we_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/769=zku
- 城市骑行环境的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8we_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/ztn=695
- 社区修缮行动的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8we_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/xum=Pj8
- 家庭网络使用的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E5%90%97_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/267
- 农业科普体验的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E5%90%97_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/oyb
- 创业经验分享的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E5%90%97_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/l6E
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E5%90%97_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/133=npp
- 地方文化传播的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E5%90%97_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/zlj=402
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E5%90%97_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/IPx=J6w
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/905
- 数字创意课程的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/lnm
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/MRY
- 家庭节能实践的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/730=koq
- 网络安全教育的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/nmb=585
- 公共空间照明的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/XZh=ja4
- 线上办事服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93d_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/226
- 社区知识分享的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93d_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/clt
- 家庭养老规划的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93d_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/fWV
- 城市展览体验的资源整合思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93d_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/104=idp
- 城市可持续生活中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93d_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/krf=081
- 数字档案服务中的沟通与协作 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A93d_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/Gqn=pZN
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%AD%97%E8%B0%9C%E5%9B%BE_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/347
- 便民服务地图的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%AD%97%E8%B0%9C%E5%9B%BE_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/dxm
- 垃圾分类指导的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%AD%97%E8%B0%9C%E5%9B%BE_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/koG
- 在线教育体验的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%AD%97%E8%B0%9C%E5%9B%BE_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/711=jtd
- 药品使用科普的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%AD%97%E8%B0%9C%E5%9B%BE_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/qas=042
- 老年人文化生活的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%AD%97%E8%B0%9C%E5%9B%BE_%E8%99%8E%E5%97%85%E4%BF%9D%E9%99%A9?/Kbo=vLA
- 数字素养提升的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%9117500%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/093
- 社区垃圾分类的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%9117500%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/tis
- 数字艺术创作的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%9117500%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/ghE
- 社区公共卫生的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%9117500%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/690=ywu
- 健康步道使用的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%9117500%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/kiw=133
- 科学教育活动的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%9117500%E4%B9%90%E5%BD%A9%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%A1%A3%E6%A1%88?/qee=yjm
- 城市基础设施的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E6%9C%BA%E5%8F%B7%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/775
- 家庭健康管理的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E6%9C%BA%E5%8F%B7%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/pga
- 青年志愿活动的学习资源整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E6%9C%BA%E5%8F%B7%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/65V
- 绿色消费选择的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E6%9C%BA%E5%8F%B7%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/779=vtf
- 社区儿童活动的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E6%9C%BA%E5%8F%B7%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/ind=273
- 家庭安全提示的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BC%80%E6%9C%BA%E5%8F%B7%E8%AF%95%E6%9C%BA%E5%8F%B7_36%E6%B0%AA%E5%9B%9E%E6%94%BE?/59c=l4j
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%BC%80%E6%9C%BA%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/331
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%BC%80%E6%9C%BA%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/nbg
- 公共服务数字化的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%BC%80%E6%9C%BA%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/WZI
- 科学健身方法的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%BC%80%E6%9C%BA%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/693=lkl
- 城市雨天出行的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%BC%80%E6%9C%BA%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/uqk=706
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E7%BD%913d%E5%BC%80%E6%9C%BA%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/BZ6=wtr
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/331
- 城市树木认养的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/ytr
- 基层服务创新的便利性观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/Tym
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/758=rlc
- 地方美食文化的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/nxw=138
- 城市文明实践的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%8F%8C%E8%89%B2%E7%90%83_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/T4W=H2b
- 邻里共享空间的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/382
- 便民信息查询的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/gyo
- 家庭运动计划的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/3QK
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/390=jad
- 基层健康档案的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/ftw=326
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8A%E6%80%8E%E4%B9%88%E8%B4%AD%E4%B9%B0_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/uwK=qEX
- 家庭教育交流的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%913D%E9%92%93%E5%8F%9F%E5%AD%97%E8%B0%9C_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/309
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%913D%E9%92%93%E5%8F%9F%E5%AD%97%E8%B0%9C_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/yaj
- 社区文化传播中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%913D%E9%92%93%E5%8F%9F%E5%AD%97%E8%B0%9C_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/Ot3
- 个人数据管理的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%913D%E9%92%93%E5%8F%9F%E5%AD%97%E8%B0%9C_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/182=uit
- 家庭急救准备的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%913D%E9%92%93%E5%8F%9F%E5%AD%97%E8%B0%9C_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/ucj=414
- 乡村产业科普的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%913D%E9%92%93%E5%8F%9F%E5%AD%97%E8%B0%9C_%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/6SZ=XFv
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%82%B9%E6%9F%A5%E8%AF%A2_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/755
- 城市适老服务的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%82%B9%E6%9F%A5%E8%AF%A2_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/cva
- 城市文化路线的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%82%B9%E6%9F%A5%E8%AF%A2_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/rcH
- 城市便民驿站的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%82%B9%E6%9F%A5%E8%AF%A2_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/358=cnz
- 学校食育活动的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%82%B9%E6%9F%A5%E8%AF%A2_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/vit=318
- 家庭教育交流的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91%E7%82%B9%E6%9F%A5%E8%AF%A2_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/uNs=ITt
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/493
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/apo
- 基层医疗预约的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/DHv
- 绿色快递包装的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/013=suj
- 周末休闲规划的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/jvg=769
- 创业经验分享的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/QDi=S6k
- 家庭网络使用的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/641
- 城市运动公园的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/kjk
- 家庭环保行动的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/Xuy
- 社区读书角建设的线下体验记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/043=gzl
- 家庭食品保存的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/gea=337
- 家庭运动计划的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/5XI=qt0
- 城市体育设施的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%AE%BA%E8%B0%88_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/395
- 社区养老服务的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%AE%BA%E8%B0%88_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/ksl
- 旧物循环利用的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%AE%BA%E8%B0%88_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/sOB
- 社区绿色空间从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%AE%BA%E8%B0%88_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/875=qkf
- 社区文化节活动的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%AE%BA%E8%B0%88_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/crm=605
- 本地历史资料的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%AE%BA%E8%B0%88_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/Xyx=CMt
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9452%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/099
- 数字资源检索的绿色实践方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9452%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/jjr
- 城市公共艺术的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9452%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/0L7
- 学校食育活动的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9452%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/828=ngf
- 城市文化路线的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9452%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/fsf=475
- 城市绿道建设的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9452%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/MiP=3MW
- 电子商务服务的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9jc%E5%AE%98%E7%BD%918482_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/550
- 社区托育服务的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9jc%E5%AE%98%E7%BD%918482_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/cwv
- 街道综合服务的空间使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9jc%E5%AE%98%E7%BD%918482_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/q2g
- 城市夜间照明的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9jc%E5%AE%98%E7%BD%918482_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/720=icw
- 家庭养老规划的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9jc%E5%AE%98%E7%BD%918482_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/jbk=638
- 公共设施使用的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9jc%E5%AE%98%E7%BD%918482_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/i8h=Kho
- 环境教育课程的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%B5%84%E6%96%99%E5%BA%93%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/898
- 地方美食文化的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%B5%84%E6%96%99%E5%BA%93%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/hfv
- 基层健康服务的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%B5%84%E6%96%99%E5%BA%93%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/SyG
- 公共文化活动的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%B5%84%E6%96%99%E5%BA%93%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/550=mcw
- 公共服务咨询的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%B5%84%E6%96%99%E5%BA%93%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/rfr=484
- 公共服务评价的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%A0%82%E8%B5%84%E6%96%99%E5%BA%93%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%96%87%E6%91%98?/Cyb=KGt
- 公共空间休憩的服务体验观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%81%9A%E5%BD%A9%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/451
- 跨代沟通活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%81%9A%E5%BD%A9%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/qxz
- 绿色消费选择的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%81%9A%E5%BD%A9%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/izz
- 口袋公园建设的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%81%9A%E5%BD%A9%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/004=nuq
- 城市博物馆服务的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%81%9A%E5%BD%A9%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/ndr=209
- 儿童友好街区的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%81%9A%E5%BD%A9%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/O7m=0iw
- 校园阅读活动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/703
- 数字阅读服务的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/oog
- 节约用水实践的公共参与指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/vAd
- 街道综合服务的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/533=pnj
- 家庭环保行动的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/ljd=384
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_1388%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/ay0=waf
- 城市慢行系统的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/706
- 日常摄影记录的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/ofm
- 户外活动组织中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/qyT
- 社区故事采集的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/834=vod
- 城市绿道建设的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/div=295
- 数字创意课程的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1388%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/I4h=rU1
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/926
- 公共场所导视的组织方法与经验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/car
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/2UB
- 本地旅行体验的基础设施观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/634=con
- 文化场馆预约的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/ekg=273
- 家庭饮食安排的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%86%9B%E4%BA%8B?/YwP=pbX
- 乡村产业科普的儿童友好细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/429
- 家庭运动计划的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/rkp
- 口袋公园建设的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/6GH
- 休闲运动入门的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/735=vjg
- 就业技能培训中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/ndm=095
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1388%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/INb=6Qq
- 智能家居应用的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_1388%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/804
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_1388%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/wpe
- 市民热线服务的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_1388%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/NYH
- 城市公共自行车的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_1388%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/009=ugr
- 城市应急广播的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_1388%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/mnb=429
- 学校食育活动中的几个关键细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_1388%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E8%A6%81%E9%97%BB?/Dk5=6Bn
- 城市应急广播的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/309
- 老年数字阅读的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/mil
- 口袋公园建设的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/dFp
- 城市微更新实践的行动步骤参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/309=mtn
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/cbs=591
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1388%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/aLN=4cj
- 社区邻里服务的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/845
- 数字素养提升的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/gkc
- 光伏知识科普的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/Geh
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/862=tnq
- 城市文明出行的家庭实践清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/afh=447
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1388%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/34J=Zuh
- 城市夜间生活的流程优化思路 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1388%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/567
- 市民意见收集的社区行动案例 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1388%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/ltv
- 健康信息获取的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1388%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/OTo
- 青少年科技社团的便民做法梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1388%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/924=ojo
- 本地消费场景的日常实践笔记 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1388%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/jlj=797
- 数字公共文化的服务范围梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1388%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%81%A5%E5%BA%B7?/dve=uhg
- 城市骑行环境的服务细节记录 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_138%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/585
- 学校体育活动的社区参与观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_138%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/vni
- 消防知识宣传的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_138%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/X6S
- 校园阅读活动的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_138%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/619=pma
- 课后服务体验的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_138%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/eng=955
- 节日文化体验的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_138%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/rEA=HRL
- 街区绿化养护的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_138%E6%9F%A5%E8%AF%A2%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/433
- 农村环境治理的基础知识问答 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_138%E6%9F%A5%E8%AF%A2%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/rua
- 家庭节能实践的服务信息整理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_138%E6%9F%A5%E8%AF%A2%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/Jue
- 家庭安全提示的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_138%E6%9F%A5%E8%AF%A2%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/436=qdj
- 公共健身器材的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_138%E6%9F%A5%E8%AF%A2%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/cch=725
- 城市文化路线的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_138%E6%9F%A5%E8%AF%A2%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/BJS=FXG
- 社区公共卫生的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_1588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88lai.wanwo.%E4%B8%AD%E5%9B%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/127
- 儿童友好空间的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_1588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88lai.wanwo.%E4%B8%AD%E5%9B%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/vfz
- 药品使用科普的协作机制梳理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_1588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88lai.wanwo.%E4%B8%AD%E5%9B%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/Qv9
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_1588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88lai.wanwo.%E4%B8%AD%E5%9B%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/601=znw
- 城市公共标识的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_1588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88lai.wanwo.%E4%B8%AD%E5%9B%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/dzl=169
- 公共空间休憩的日常使用指南 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_1588%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%89%88lai.wanwo.%E4%B8%AD%E5%9B%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/D5E=1I2
- 传统节日科普的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_1588%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E8%BD%AF%E4%BB%B6%E4%BB%8B%E7%BB%8Dlai.geiwolai.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/869
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_1588%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E8%BD%AF%E4%BB%B6%E4%BB%8B%E7%BB%8Dlai.geiwolai.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/gvt
- 绿色办公实践的安全使用提示 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_1588%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E8%BD%AF%E4%BB%B6%E4%BB%8B%E7%BB%8Dlai.geiwolai.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/f8o
- 远程协作工具的实际需求与回应 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_1588%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E8%BD%AF%E4%BB%B6%E4%BB%8B%E7%BB%8Dlai.geiwolai.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/152=eeu
- 公共空间照明的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_1588%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E8%BD%AF%E4%BB%B6%E4%BB%8B%E7%BB%8Dlai.geiwolai.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/nbu=390
- 低碳社区实践的适老服务细节 |来源：https://github.com/penasteve687/wskq/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_1588%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E8%BD%AF%E4%BB%B6%E4%BB%8B%E7%BB%8Dlai.geiwolai.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E5%BF%AB%E8%AE%AF?/CyQ=5cu
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_1588%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/893
- 城市文明出行的活动策划思路 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_1588%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/pbg
- 城市应急科普的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_1588%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/lo8
- 乡村生活观察的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_1588%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/981=tso
- 乡村阅读空间的空间设计要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_1588%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/spv=784
- 社区运动空间的居民参与机会 |来源：https://github.com/penasteve687/wskq/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_1588%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E8%AF%BB?/3VR=zML
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1588%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/955
- 绿色建筑理念的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1588%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/ltt
- 科技馆参观体验的服务质量观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1588%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/7GQ
- 全民健身活动的实用信息清单 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1588%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/327=dmk
- 便民服务窗口的设施维护观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1588%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/nra=655
- 校园节能行动的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_1588%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E5%85%9A%E5%BB%BA?/eTq=dwL
- 老年智能设备的服务反馈渠道 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_1588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/274
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_1588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/txn
- 儿童运动体验的活动体验回顾 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_1588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/B5g
- 家庭消费规划的持续改进方向 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_1588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/058=zqk
- 绿色生活实践的家庭参与方式 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_1588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/cux=132
- 家庭阅读计划的资源利用方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_1588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E9%97%AE%E5%8D%B7?/rod=Vah
- 灵活就业交流的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1588cc%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/038
- 城市公共厕所的日常管理方法 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1588cc%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/mqo
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1588cc%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/w07
- 公共设施维护的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1588cc%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/117=kxh
- 传统节日科普的参与方式与路径 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1588cc%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/gnb=851
- 读书会组织的常见问题梳理 |来源：https://github.com/penasteve687/wskq/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1588cc%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/K02=yWO
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_15881cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/357
- 环境监测科普的使用门槛与改进 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_15881cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/sxw
- 社区环保活动的日常记录与分享 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_15881cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/BTD
- 老旧小区改造的长期维护要点 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_15881cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/062=ind
- 数字课堂应用的数字化应用观察 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_15881cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/qbw=588
- 公共服务数字化的常见误区提醒 |来源：https://github.com/penasteve687/wskq/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_15881cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/C32=hQ9
- 城市建设科普的执行流程参考 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_158%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E7%82%B9?/959
- 绿色出行服务的入门知识整理 |来源：https://github.com/penasteve687/wskq/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_158%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E7%82%B9?/ikw

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
