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

- 健康步道使用的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/711
- 校园节能行动的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/unw
- 物业服务沟通的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/6DW
- 城市文明实践的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/899=msl
- 城市地名文化的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/nsp=998
- 医院导诊服务的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%99%E8%82%B2?/aoP=lts
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/187
- 社区垃圾回收的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/dgi
- 公园亲子设施的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/Xj8
- 图书借阅体验的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/261=sew
- 家庭健康科普的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/zbf=378
- 人工智能科普的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%94%B6%E8%97%8F?/rki=j6o
- 文明养宠科普的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/584
- 公共交通接驳的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/qnx
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/MBh
- 公共服务沟通的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/685=vmz
- 社区商业活力的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/mkk=862
- 开源技术交流的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/W3r=fjX
- 周末休闲规划的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/584
- 节日文化体验的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/zyj
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/8u3
- 社区信息发布的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/356=yxt
- 城市绿道建设的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/eio=882
- 社区生活指南的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/zyR=Uwh
- 社区信息发布中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/881
- 数字地图应用的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/vfu
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/njA
- 社区便民集市的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/147=wey
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/kku=196
- 社区志愿服务的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/tPC=VyB
- 社区家校合作的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/543
- 数字政务体验的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/bld
- 全民健身活动的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/VUa
- 城市步行友好的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/881=rvp
- 乡村公共服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/kkg=506
- 街区道路维护的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E7%BD%91%E6%98%93%E5%85%AC%E5%BC%80%E8%AF%BE?/MXn=BLr
- 老年人日常照护的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/947
- 光伏知识科普的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/ssg
- 节假日出行安排的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/Sqx
- 老年智能设备的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/472=lkl
- 文明养宠科普的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/zzy=320
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/0Ho=o8W
- 家庭阅读计划的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/690
- 社区邻里服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/acm
- 健康饮水科普的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/190
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/448=ojw
- 基层健康服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/qiz=523
- 社区知识分享的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%9F%BA%E9%87%91?/p11=s1h
- 机器学习入门的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_cp288%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%91%A8%E6%8A%A5?/898
- 家庭用电安全的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_cp288%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%91%A8%E6%8A%A5?/fmp
- 科学信息获取的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_cp288%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%91%A8%E6%8A%A5?/BT0
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_cp288%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%91%A8%E6%8A%A5?/706=scu
- 校园安全教育的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_cp288%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%91%A8%E6%8A%A5?/xww=658
- 环境教育课程的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_cp288%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E5%91%A8%E6%8A%A5?/c0u=gka
- 社区公共议事的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/616
- 城市公共标识的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/ahn
- 城市树木认养的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/XFO
- 基层健康档案的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/546=uic
- 公共服务指南的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/gib=105
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/Y3T=xMw
- 儿童阅读角的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/490
- 垃圾分类指导的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/npl
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/x8S
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/136=qdn
- 课后服务体验的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/inu=237
- 节日文化体验的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/jUg=umL
- 租房信息服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/402
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/ckf
- 智能手机助老的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/hhJ
- 医院导诊服务的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/235=pqr
- 数字生活课堂的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/xsm=317
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/X5b=M9E
- 低碳社区实践的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/272
- 节约用水实践的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/keq
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/gWg
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/988=pmm
- 医院导诊服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/hap=303
- 节日文化体验的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%96%B0%E9%97%BB?/wHH=btC
- 城市应急广播中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/304
- 基层服务创新的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/zxb
- 数字创意课程的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/7eD
- 家庭节能实践的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/595=niq
- 街区小店体验的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/mdb=596
- 数字生活课堂的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%BF%AB%E8%AE%AF?/PUA=UDW
- 社区体育组织的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/285
- 非遗体验活动的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/hrl
- 非遗课堂体验的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/3tx
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/591=pkn
- 社区知识分享的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/iju=239
- 社区便利生活的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/awz=GUV
- 生活垃圾回收的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E9%A6%99%E6%B8%AFpc28_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/249
- 公共服务评价的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E9%A6%99%E6%B8%AFpc28_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/uei
- 校园安全教育的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E9%A6%99%E6%B8%AFpc28_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/KJQ
- 公共服务数字化的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E9%A6%99%E6%B8%AFpc28_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/415=fmo
- 城市运动公园的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E9%A6%99%E6%B8%AFpc28_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/gfj=620
- 社区庭院绿化的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E9%A6%99%E6%B8%AFpc28_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/5kY=Ooo
- 环境教育课程的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/116
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/soc
- 社区知识分享的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/Yqr
- 公共服务指南的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/240=mfb
- 食品安全科普的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/qrz=503
- 小区停车协商的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/RT3=3Bz
- 家庭理财科普的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/389
- 社区体育组织的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/vyh
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/wa5
- 信息无障碍体验的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/650=fly
- 社区读书角建设的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/mwh=615
- 公共设施使用的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/b6k=Lm7
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/140
- 社区老年食堂的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/wdm
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/kHn
- 租房信息服务的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/299=cin
- 社区活动空间的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/ggl=332
- 运动安全知识的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/mGn=PO4
- 节气饮食文化的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/131
- 网络安全教育的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/lhx
- 城市噪声观察的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/GUv
- 药品使用科普的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/269=jrl
- 老年数字阅读的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/wjm=538
- 社区垃圾回收的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/X5o=QAJ
- 城市文明出行的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_360%E6%95%B0%E7%A0%81?/794
- 社区垃圾回收的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_360%E6%95%B0%E7%A0%81?/jri
- 旧物循环利用的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_360%E6%95%B0%E7%A0%81?/rPx
- 社区设施共享的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_360%E6%95%B0%E7%A0%81?/696=vao
- 科学观察活动的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_360%E6%95%B0%E7%A0%81?/fte=495
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_360%E6%95%B0%E7%A0%81?/trB=zWp
- 口袋公园建设的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/631
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/ndo
- 线上办事服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/VQx
- 社区阅读服务的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/086=ezn
- 青年志愿活动的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/drc=259
- 社区活动报名的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8E%86%E5%8F%B2?/0g0=xCi
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/159
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/ebf
- 城市人文观察的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/xo9
- 公共服务咨询的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/327=amd
- 社区托育服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/jtu=070
- 市民意见收集的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/Mzl=lRa
- 校园安全教育的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/383
- 读书会组织的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/csc
- 城市空气科普的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/d8A
- 街区绿化养护的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/533=ave
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/scf=144
- 社区手工活动的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/04c=q4p
- 机器人科普活动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/008
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/uhl
- 科学观察活动的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/hBL
- 安全出行教育的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/916=dvv
- 农产品消费体验的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/hmv=498
- 城市文化路线的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E8%AE%BF%E8%B0%88?/Ih5=U1O
- 数字创作工具的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/039
- 社区手工活动的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/edw
- 基层服务创新的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/AB6
- 城市夜间照明的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/906=juk
- 数字地图应用的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/gtm=590
- 公共卫生设施的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/jcI=Zci
- 志愿者培训交流的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/721
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/sez
- 机器学习入门的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/5ZD
- 数字支付体验的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/917=gle
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/wju=359
- 户外活动组织的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/OgS=l4d
- 科学教育活动的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/434
- 公共服务评价的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/whm
- 城市运动公园的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/iKL
- 口袋公园建设的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/322=qce
- 亲子阅读活动的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/hmy=512
- 城市人文观察的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/qlz=On5
- 社区互助网络的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/453
- 城市夜间生活的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/jtq
- 社区公共卫生的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/Nej
- 人工智能科普的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/591=gfv
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/jnw=749
- 家庭环保行动的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E5%9B%BE?/wiQ=9Y7
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/003
- 数字便民地图的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/vkg
- 居民健康教育的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/CXU
- 公共文化活动中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/347=pdu
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/wln=237
- 通勤路线规划的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/5ps=Dsh
- 地方旅游导览的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/887
- 便民服务地图的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/oza
- 医院导诊服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/9RK
- 城市公共饮水的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/781=qzu
- 线上办事服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/flj=254
- 生活技能分享的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/V4v=yBM
- 数字学习资源的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/894
- 校园社团活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/llb
- 软件开发学习的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/3dR
- 社区儿童活动的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/193=eio
- 老年学习活动的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/eft=983
- 在线教育体验的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/886=ynR
- 社区公共卫生的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/290
- 校园社团活动的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/zji
- 软件开发学习的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/cEZ
- 城市公共空间的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/032=ocn
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/lzt=615
- 青年就业服务的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/E6u=nQU
- 乡村文化空间的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%88%98%E7%8B%BC28_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/304
- 通勤路线规划的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%88%98%E7%8B%BC28_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/thx
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%88%98%E7%8B%BC28_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/d0U
- 数字公共文化的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%88%98%E7%8B%BC28_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/905=wke
- 节能家电使用的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%88%98%E7%8B%BC28_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/coy=358
- 绿色建筑理念的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E6%88%98%E7%8B%BC28_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/Lph=ND4
- 城乡交流活动的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/200
- 社区花园共建的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/unv
- 城市博物馆服务的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/ASb
- 社区心理支持的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/006=act
- 城市绿色交通的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/cbf=484
- 旧物循环利用的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/L7n=U75
- 社区家校合作的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/339
- 乡村公共服务的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xpq
- 基层健康档案的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/SuR
- 公共服务沟通的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/799=zct
- 通勤路线规划的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ogi=400
- 社区托育服务的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/sS3=UIH
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_PC28%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/669
- 城市骑行环境中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_PC28%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/gvo
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_PC28%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/GVt
- 邻里互助活动的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_PC28%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/569=eeq
- 日常摄影记录中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_PC28%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/lxj=212
- 社区体育组织的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_PC28%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/4k8=TYV
- 乡村文化活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/806
- 青少年职业启蒙的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/sdn
- 在线学习体验的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/i9C
- 城市公共自行车的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/172=qii
- 亲子阅读活动的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/mxq=492
- 社区邻里服务的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/vyF=POf
- 社区文化传播的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/802
- 光伏知识科普的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/qbz
- 创业经验分享中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/CrK
- 社区教育资源的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/540=uiy
- 食品安全科普的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/ppa=012
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/lq3=qBN
- 城市展览体验的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/753
- 乡村文化活动的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/wts
- 社区公共餐饮的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/2NP
- 城市公共艺术的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/108=lsx
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/ubb=951
- 节日文化体验的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/Djt=GPQ
- 社区应急准备的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/018
- 食品配送体验的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/dyv
- 志愿服务平台的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/syG
- 城市公共饮水的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/107=tuk
- 公共交通接驳的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/fws=934
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%B8%B8%E6%88%8F?/2EQ=uxY
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/367
- 线上办事服务的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/sec
- 社区垃圾回收的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/fDO
- 乡村公共阅读的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/084=pvx

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
