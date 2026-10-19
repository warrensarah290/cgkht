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

- 社区设施共享的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E9%A3%9E%E8%89%87%E5%9B%9E%E8%A1%80%E5%A4%A7%E7%A5%9E_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/anh=676
- 社区环保活动的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E9%A3%9E%E8%89%87%E5%9B%9E%E8%A1%80%E5%A4%A7%E7%A5%9E_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/FA0=Hau
- 社区活动空间的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/716
- 地方美食文化的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/hdo
- 公共场馆服务的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/eWO
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/492=top
- 生活垃圾回收的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/axi=556
- 便民服务窗口的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/V9Q=PuI
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/558
- 家庭消费规划的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/zgg
- 安全出行教育的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/B0N
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/895=vqi
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/zcn=449
- 社区协商议事的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/TXw=zEV
- 社区慢性病防控的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/311
- 城乡交流活动的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/ogo
- 环境教育课程的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/mIp
- 旧物循环利用的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/912=qcx
- 公共服务数字化的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/nuk=020
- 家庭科学教育的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/nkR=xBm
- 社区垃圾回收的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/448
- 绿色校园实践的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/klg
- 个人数据管理的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/jvi
- 社区安全巡查的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/950=tvo
- 数字档案服务的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/sho=468
- 校园阅读活动的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%A5%BD%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/pa8=AVu
- 街区小店体验的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/710
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/cab
- 绿色消费选择的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/1tM
- 街区绿化养护的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/796=xuw
- 基层健康服务的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/zsf=282
- 生成式工具使用的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E7%9A%84%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/ZHZ=0Cg
- 社区花园共建的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%A1%A8%E6%83%85%E5%8C%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/907
- 社区商业活力的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%A1%A8%E6%83%85%E5%8C%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/tpu
- 城市博物馆服务的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%A1%A8%E6%83%85%E5%8C%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/qGI
- 数字政务体验的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%A1%A8%E6%83%85%E5%8C%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/315=byt
- 地方文化传播的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%A1%A8%E6%83%85%E5%8C%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/kdq=556
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88%E8%A1%A8%E6%83%85%E5%8C%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/yNw=pTa
- 社区活动空间的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/866
- 社区活动策划的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/aak
- 数字便民地图的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/WuA
- 全民健身活动的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/464=dho
- 生活服务数字化的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/opn=136
- 家庭健康科普的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/fvB=ybx
- 青年职业探索的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/463
- 图书馆数字服务的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/kgr
- 生活技能分享的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/wEa
- 地方民俗记录的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/651=uzl
- 家庭科学教育的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/xmo=703
- 社会体育指导的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/HUC=xH1
- 校园社团活动的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/088
- 家庭收纳实践的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/ypn
- 数字生活课堂的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/eHF
- 数字支付体验的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/696=wis
- 光伏知识科普的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/wcu=848
- 城市生活服务的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9C%89%E6%B2%A1%E6%9C%89%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/v66=NOs
- 家庭科学教育的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/118
- 社区教育资源的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/xch
- 机器人科普活动的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/UCq
- 公共服务沟通的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/213=jya
- 乡村阅读活动的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/lfz=224
- 城市展览体验的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/vU9=Qgh
- 劳动教育实践的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/181
- 健康步道使用的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/pac
- 乡村公共文化的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/A4r
- 数字档案服务的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/910=nbt
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/fli=847
- 社区体育组织的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/EKi=tiC
- 公共交通接驳的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/098
- 社区托育服务的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/zyx
- 数字政务体验的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/isP
- 公共设施使用的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/164=qbw
- 家庭理财科普的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/aqo=802
- 城市公共自行车的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/DXj=oZV
- 城市博物馆服务的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%B0%8F%E5%A6%99%E6%8B%9B_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/811
- 城市展览体验的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%B0%8F%E5%A6%99%E6%8B%9B_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/agk
- 骑行路线规划的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%B0%8F%E5%A6%99%E6%8B%9B_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/7N9
- 社区家政服务的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%B0%8F%E5%A6%99%E6%8B%9B_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/582=bro
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%B0%8F%E5%A6%99%E6%8B%9B_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/sao=968
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%B0%8F%E5%A6%99%E6%8B%9B_%E8%84%89%E8%84%89%E5%85%AC%E5%BC%80%E8%AF%BE?/SZv=6qh
- 乡村产业科普的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/766
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/bxb
- 就业技能培训的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/q4C
- 节假日出行安排的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/860=hin
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/ypl=129
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/NRt=Z2g
- 数字艺术创作的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E7%A8%B3_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/141
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E7%A8%B3_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/xep
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E7%A8%B3_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/jYu
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E7%A8%B3_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/507=xgh
- 公共设施使用的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E7%A8%B3_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/nnn=881
- 公共空间照明的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E7%A8%B3_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/lkV=CR5
- 无障碍出行的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/395
- 个人数据管理的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/gse
- 节约用水实践的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/1Rx
- 数字档案服务的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/709=jye
- 基层健康档案的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/prc=561
- 日常摄影记录的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BF%AB%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/OEs=PVO
- 城市夜间照明的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/233
- 社区共享书架的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qhf
- 社区心理支持的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/fSZ
- 光伏知识科普的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/413=qbn
- 市民热线服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/oob=797
- 校园节能行动的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%8A%E5%B2%B8%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88qq_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/i2Q=5BT
- 文化讲座服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/670
- 乡村公共文化的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/chs
- 社区商业活力的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/qVY
- 社区消防演练的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/017=jvo
- 社区老年食堂的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/mje=974
- 城市体育设施的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%96%B0%E6%B5%AA%E8%A1%8C%E6%83%85?/yrW=oSb
- 开源技术交流的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%91%80__%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/167
- 家庭志愿活动的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%91%80__%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/mru
- 家庭环保行动的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%91%80__%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/5JV
- 乡村生态观察的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%91%80__%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/275=web
- 租房信息服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%91%80__%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/thb=288
- 社区艺术活动的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%B8%AA%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%91%80__%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/Sf5=TCj
- 公共服务咨询的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/598
- 绿色建筑理念的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/ljh
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/Luc
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/419=rxq
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/xjf=679
- 城市慢行系统的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/p7U=NUM
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/645
- 健康步道使用的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/ccm
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/VZP
- 数字政务体验的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/722=inj
- 人工智能科普的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/dch=302
- 全民阅读推广的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/LgH=V30
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E6%80%8E%E4%B9%88%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8_360%E6%95%B0%E8%AF%BB?/722
- 城市微更新实践的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E6%80%8E%E4%B9%88%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8_360%E6%95%B0%E8%AF%BB?/pfb
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E6%80%8E%E4%B9%88%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8_360%E6%95%B0%E8%AF%BB?/q1p
- 城市空气科普的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E6%80%8E%E4%B9%88%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8_360%E6%95%B0%E8%AF%BB?/203=stx
- 家庭志愿活动的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E6%80%8E%E4%B9%88%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8_360%E6%95%B0%E8%AF%BB?/gii=761
- 周末休闲规划的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E6%80%8E%E4%B9%88%E6%88%90%E5%8A%9F%E4%B8%8A%E5%B2%B8_360%E6%95%B0%E8%AF%BB?/XYE=p2G
- 绿色快递包装的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/823
- 公共空间照明的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/ich
- 乡村生态观察的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/IjK
- 小微企业服务的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/828=yab
- 文化讲座服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/hgt=025
- 食品配送体验的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%86%85%E9%83%A8%E8%AE%A1%E5%88%92_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/RVZ=WVz
- 老年数字阅读的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%B3%95%E5%BE%8B?/680
- 社区家政服务的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%B3%95%E5%BE%8B?/zuo
- 家庭节能实践的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%B3%95%E5%BE%8B?/Hlc
- 公共设施维护中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%B3%95%E5%BE%8B?/861=dwq
- 创业经验分享的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%B3%95%E5%BE%8B?/ltr=176
- 无障碍出行的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%B3%95%E5%BE%8B?/A60=rM2
- 社区教育资源的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/967
- 在线教育体验的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/yee
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/aZg
- 非遗课堂体验的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/820=wfb
- 青少年编程学习的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/lgb=567
- 城市住房服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%80%81%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/KQ7=BYo
- 生活垃圾减量的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/837
- 街区更新实践的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/fen
- 社区宠物管理的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/tDp
- 青少年户外教育的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/722=uoc
- 社区修缮行动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/ogi=353
- 儿童友好空间的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/1jT=Ba6
- 文明养宠科普的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/539
- 社区文化传播的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/qoz
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/Wgn
- 旧物循环利用的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/321=wvy
- 社区便民服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/vmi=177
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%B8%8A%E5%B2%B8_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/PFD=Is8
- 家庭节能实践的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/145
- 智慧停车服务的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/evw
- 便民维修服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/oKT
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/313=yky
- 公共服务预约的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/gcu=039
- 公共图书馆服务的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/lR3=R8y
- 数字阅读服务的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/156
- 社区故事采集的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/god
- 开放数据应用的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/dmu
- 社区心理支持的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/667=awf
- 社区儿童活动的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/qcg=779
- 电子商务服务的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/PBQ=ApG
- 公共服务指南的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/605
- 城乡公共服务的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/wsw
- 公共设施使用中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/n1W
- 公共服务咨询的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/040=alf
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/vai=932
- 数字支付体验的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%BA%94%E5%88%86%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E4%B8%8A%E5%B2%B8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/BI2=OX7
- 在线教育体验的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88qq_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/256
- 城市文化路线的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88qq_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/cgn
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88qq_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/l9G
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88qq_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/267=plm
- 社区环保活动的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88qq_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/yox=994
- 地方戏曲体验的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88qq_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Bs3=NsK
- 科学信息获取的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/975
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/syz
- 志愿者培训交流的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/dOu
- 职业技能学习的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/246=znm
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/euh=879
- 非遗体验活动的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E5%BD%B1%E8%A7%86?/xdo=tAr
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/487
- 药品使用科普的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/aey
- 全民健身活动的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/gHS
- 社区便利生活的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/835=jjz
- 家庭消费规划的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/fcy=541
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/G2N=iUy
- 儿童安全出行中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/048
- 文化场馆预约的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/ylw
- 传统节日科普的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/fYd
- 公共场所导视的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/412=vdf
- 家庭急救准备的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/qop=548
- 城市步行友好的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/vBR=Etn
- 城市适老服务的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88Q_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/850
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88Q_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/bau
- 社区生活指南的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88Q_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/uR6
- 社区生活指南的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88Q_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/245=vtu
- 课后服务体验的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88Q_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/ngj=939
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88Q_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/7BN=a9U
- 地方文化传播的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%81%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/866
- 科学信息获取的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%81%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/mpb
- 数字创意课程的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%81%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/4sk
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%81%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/499=aub
- 社区便民集市的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%81%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/ksx=902
- 社区公共议事的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BD%A0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%81%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/PNa=r7t
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/032
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/bqa
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/GZF
- 家庭食品保存的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/624=udu
- 软件开发学习的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/ime=682
- 家庭运动计划的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E6%8C%A3%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/ETZ=DMA
- 传统手工艺体验的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/075
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/szj
- 健康信息获取的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/Ohn
- 乡村公共服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/371=cpn
- 家庭用电安全的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/ohw=740
- 网络安全教育的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/e22=FPg
- 开放数据应用的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/453
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/vuk
- 城市慢行系统的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/aQV
- 生活垃圾减量的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/189=wkr
- 社区艺术活动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/jof=486
- 城乡交流活动的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E8%AF%BB%E4%B9%A6?/tBO=eq0
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/443
- 社区垃圾回收的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/glc
- 家庭养老规划的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/k9o
- 家庭饮食安排的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/165=odh
- 亲子阅读活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/pej=710
- 市民意见收集的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/9Bh=sfO
- 科学教育活动的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/886
- 数字便民地图的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/tpm
- 传统节日科普的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/5SI
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/752=ypf
- 非遗课堂体验的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/yvl=123
- 家庭教育交流中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.97_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/Zqx=VMK
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/530
- 节日文化体验的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/zbm

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
