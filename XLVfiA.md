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

- 居民健康教育的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/RyW
- 青年职业探索的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/525=err
- 家庭网络使用的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/wda=457
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/SMj=CBa
- 数字资源检索的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_01%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/699
- 远程协作工具的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_01%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/wlw
- 社区体育组织的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_01%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/LvV
- 文化讲座服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_01%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/928=ztv
- 家庭节能设备的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_01%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/akb=786
- 青少年心理健康的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_01%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/GaO=Exp
- 社区花园共建中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD105%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2?/257
- 社区文化传播的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD105%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2?/cnj
- 城市住房服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD105%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2?/OV2
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD105%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2?/662=xcp
- 地方美食文化的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD105%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2?/ezx=768
- 社区公共卫生的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD105%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8app_%E7%95%8C%E9%9D%A2?/ri1=bNM
- 儿童安全出行中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_888cc%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/149
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_888cc%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/jzg
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_888cc%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/bZh
- 绿色建筑理念的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_888cc%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/998=jep
- 社区艺术活动的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_888cc%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/jsh=971
- 数字创意课程的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_888cc%E5%BD%A9%E7%A5%A8app_%E9%9B%85%E8%99%8E%E7%88%86%E6%96%99?/CNX=uLx
- 社区修缮行动的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%87%A0%E5%B9%B4%E4%BA%86_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/976
- 地方旅游导览的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%87%A0%E5%B9%B4%E4%BA%86_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/dml
- 基层医疗预约的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%87%A0%E5%B9%B4%E4%BA%86_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/0NQ
- 小区停车协商的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%87%A0%E5%B9%B4%E4%BA%86_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/594=pkb
- 志愿服务平台的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%87%A0%E5%B9%B4%E4%BA%86_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/cvw=462
- 公共场馆服务的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%87%A0%E5%B9%B4%E4%BA%86_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/hNT=rCa
- 家庭运动计划的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%9A%E5%AE%A2?/539
- 文明养宠科普的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%9A%E5%AE%A2?/jrh
- 开源技术交流的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%9A%E5%AE%A2?/Pk2
- 社区商业活力的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%9A%E5%AE%A2?/468=hcb
- 城市共享单车的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%9A%E5%AE%A2?/gsn=166
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%9C%80%E6%96%B0%E8%A7%86%E9%A2%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%9A%E5%AE%A2?/9eW=Ecz
- 智能家居应用的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%8D%95%E5%8F%8C%E8%B5%84%E6%96%99_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/256
- 科技馆参观体验的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%8D%95%E5%8F%8C%E8%B5%84%E6%96%99_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/kzj
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%8D%95%E5%8F%8C%E8%B5%84%E6%96%99_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/kEc
- 家庭科学教育的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%8D%95%E5%8F%8C%E8%B5%84%E6%96%99_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/774=fib
- 家庭急救准备的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%8D%95%E5%8F%8C%E8%B5%84%E6%96%99_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/hhv=887
- 街道综合服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%8D%95%E5%8F%8C%E8%B5%84%E6%96%99_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/b0l=FZM
- 读书会组织的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/752
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/uff
- 学校食育活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/Qh1
- 社区公共餐饮的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/056=hau
- 基层健康服务的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/kyo=534
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/NaL=aBr
- 本地历史资料的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/842
- 节气饮食文化的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/dob
- 城市公共座椅的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/Clv
- 社区协商议事的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/446=zhb
- 小区停车协商的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/bcq=193
- 居民健康教育的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/Dpd=HnW
- 社区体育组织的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/293
- 食品安全科普的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/mev
- 社区阅读服务的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/nLx
- 青少年户外教育的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/973=mrg
- 光伏知识科普的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/bzj=188
- 药品使用科普的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/3wB=9Dl
- 社区生活指南的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/328
- 光伏知识科普的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/wzx
- 数字素养提升的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/gOr
- 社区便民集市的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/317=jlw
- 食品安全科普的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/inw=256
- 课后服务体验的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/N8z=dGm
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%89%B4?/728
- 骑行路线规划的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%89%B4?/uap
- 社区便民集市的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%89%B4?/fsK
- 城市生活服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%89%B4?/886=vus
- 城市可持续生活的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%89%B4?/vaa=218
- 社区阅读服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BE%E9%89%B4?/yd4=cZ6
- 数字创作工具的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/188
- 公共服务沟通的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/emr
- 公园亲子设施的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/Jvi
- 数字课堂应用的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/816=ium
- 公共空间安全的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/xbi=990
- 租房信息服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/l31=WqL
- 公共服务指南的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/866
- 社区休闲设施的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/kiu
- 城市文化路线的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/cqR
- 骑行路线规划的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/752=ruc
- 开放式学习空间的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/cjx=692
- 健康信息获取的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/VgR=5is
- 文化场馆预约的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/392
- 城市公共标识的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/bng
- 社区便利生活的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/GsP
- 城市文明实践的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/582=sgd
- 家庭节能实践的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/fro=327
- 公共图书馆服务的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/8x4=oe6
- 读书会组织的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/565
- 数字阅读服务的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/wml
- 数字地图应用中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/EG9
- 职业技能学习的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/084=zvh
- 口袋公园建设的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/ktv=916
- 网络信息辨识的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/n4X=5vG
- 城市共享单车的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_360%E8%B5%84%E8%AE%AF?/238
- 城市游园体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_360%E8%B5%84%E8%AE%AF?/agm
- 数字地图应用的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_360%E8%B5%84%E8%AE%AF?/jgs
- 绿色生活实践的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_360%E8%B5%84%E8%AE%AF?/431=qzn
- 生活服务数字化的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_360%E8%B5%84%E8%AE%AF?/vgk=584
- 城市便民驿站中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_360%E8%B5%84%E8%AE%AF?/yPI=77K
- 社区老年食堂的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/945
- 地方美食文化的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/gof
- 公共服务咨询的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/d3q
- 家庭志愿活动的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/403=ryu
- 开放式学习空间的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/ery=688
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E7%BE%8E%E8%82%A1?/F5U=gVh
- 社区老年食堂的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/856
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/kld
- 低碳社区实践的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/fdM
- 骑行路线规划的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/550=xhd
- 社区手工活动的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/jlg=840
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/Lgq=CV9
- 周末休闲规划的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/175
- 基层服务创新中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/xjf
- 城市夜间照明的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/1pp
- 基层健康档案的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/939=bpa
- 家庭健康科普的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/sgo=180
- 城市夜间生活的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/NiO=ZeI
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/437
- 数字便民地图的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/mnr
- 家庭理财科普的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/3zF
- 老年人文化生活的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/824=dxz
- 社区生活指南的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/vvz=239
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/5G5=l1V
- 绿色办公实践中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/510
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/ann
- 节假日出行安排的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/dNH
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/681=fqb
- 消防知识宣传的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/ibk=972
- 社区家校合作的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E6%8A%95%E8%B5%84?/WfK=vNd
- 居家适老化改造的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/172
- 科学信息获取的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/eye
- 居家防滑改造的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/wgY
- 劳动教育实践的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/589=dfy
- 社区活动报名的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/kyd=257
- 智能手机助老的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/NaW=unf
- 社区儿童活动中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/153
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/uht
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/fxC
- 儿童安全出行的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/180=rfe
- 开放数据应用的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/hxh=322
- 社区停车服务的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/HK6=9SB
- 老年数字阅读的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/092
- 节约用水实践的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/ixq
- 校园社团活动的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/jru
- 家庭科学教育的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/360=uit
- 城市空气科普的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/xyc=854
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/ZJB=KSY
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/443
- 城市博物馆服务的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/oad
- 节假日出行安排的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/gaB
- 青少年户外教育的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/467=qgf
- 社会体育指导的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/csn=842
- 数字创作工具的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/Cjo=i1N
- 亲子科普活动的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/718
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/kcl
- 亲子阅读活动的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/sYX
- 科学运动指导的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/809=uln
- 节约用水实践的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/ukn=237
- 社会体育指导的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/BXL=hD2
- 本地旅行体验的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/648
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/pvp
- 社区公共餐饮的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/2OL
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/182=ffs
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/nmb=225
- 光伏知识科普的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/8Hp=o0e
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/470
- 家庭照护支持的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/bsa
- 社区家政服务的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/Rqv
- 社区公共卫生的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/032=xdu
- 音乐欣赏活动的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/bps=241
- 社区花园共建的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA?/dnb=jcL
- 公共服务评价的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/954
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/bje
- 青少年科普实践的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/Hhi
- 食品配送体验的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/728=oaf
- 居民健康教育的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/rve=211
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/YJg=QS3
- 社区生活指南的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/351
- 科学信息获取的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/uyj
- 绿色消费选择的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/ik4
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/703=blk
- 家庭运动计划的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/tdf=370
- 社区庭院绿化的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%84%E8%AE%BA?/9LX=llZ
- 城市绿色交通的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/263
- 城市空气科普的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/hke
- 绿色消费选择的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/6YE
- 家庭养老规划的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/364=dmw
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/yne=062
- 药品使用科普的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/iHG=7vs
- 社区快递服务的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/947
- 公共交通接驳的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/ebn
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/9CD
- 科学教育活动的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/227=mhx
- 学校体育活动的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/yev=886
- 公共文化活动的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/80B=N68
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_355app%E5%BD%A9%E7%A5%A8_360%E6%98%9F%E5%BA%A7?/744
- 社区托育服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_355app%E5%BD%A9%E7%A5%A8_360%E6%98%9F%E5%BA%A7?/one
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_355app%E5%BD%A9%E7%A5%A8_360%E6%98%9F%E5%BA%A7?/5pw
- 健康信息获取的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_355app%E5%BD%A9%E7%A5%A8_360%E6%98%9F%E5%BA%A7?/379=ypt
- 公共服务咨询的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_355app%E5%BD%A9%E7%A5%A8_360%E6%98%9F%E5%BA%A7?/uaf=933
- 儿童友好空间的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_355app%E5%BD%A9%E7%A5%A8_360%E6%98%9F%E5%BA%A7?/Q5x=AVm
- 城市展览体验的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/973
- 家庭网络使用的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/plu
- 城市住房服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/wK2
- 社区快递服务的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/206=cef
- 数字艺术创作的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/xts=128
- 城市基础设施的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/4S2=FPT
- 乡村公共文化的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/595
- 社区法律科普的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/cwy
- 小微企业服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/rov
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/280=aoy
- 社区防暑服务的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/lzn=296
- 科学运动指导的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/lgY=Gqq
- 社区家校合作的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/308
- 社会体育指导的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/yzh
- 课后服务体验的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/Biu
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/508=pgp
- 在线教育体验的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/fgo=540
- 图书借阅体验的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/Ufu=XvW
- 学校食育活动的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/764
- 社区设施共享的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/dcg
- 骑行路线规划的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/EPo
- 社区信息发布的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/960=hne
- 地方美食文化的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/ran=694
- 开源技术交流的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/QJY=Yot
- 老年人文化生活的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/354
- 小微企业服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/gcl
- 城市绿道建设的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/i9I
- 城市人文观察的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/364=kdm
- 开源技术交流的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/iqb=818
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/qHZ=eB9
- 志愿者培训交流的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/661
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/cad
- 便民信息查询的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/7E9
- 社区协商议事的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/824=fbp
- 社区便民集市的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/tbm=023
- 软件开发学习的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%BD%A9%E7%A5%A8?/0RU=yLD
- 青年志愿活动中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/063
- 儿童运动体验的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/ixe
- 社区安全巡查的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/3iC
- 绿色办公实践的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/989=cfs
- 社区快递服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/jul=517
- 城市体育设施中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/ZOb=wGO
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/232
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/ryz
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/tA5
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/412=bmu
- 环境教育课程的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/tbp=584
- 绿色出行服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/sbi=Hdh

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
